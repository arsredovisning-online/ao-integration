# Årsredovisning Online integration example
This is an example project illustrating a typical integration with 
[Årsredovisning Online](https://www.arsredovisning-online.se/). It's a very simple [Sinatra](http://www.sinatrarb.com/)
app where you can add users and let them connect to Årsredovisning Online. The users can either create new accounts in 
Årsredovisning Online or connect to existing ones. Connected users can also create or update reports.

The app uses a simple data structure as an in memory database and any data entered is lost when the app is restarted.

## Installation
Clone the project and run
```
bundle install
```

Make sure the environment variables `CLIENT_ID`, `CLIENT_SECRET` and `API_HOST` are set (if you run the project locally 
the easiest option might be to add them to a .env file). Then start the server with
```
ruby server.rb
```
