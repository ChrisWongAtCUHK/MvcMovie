README.md
# Deploy to Heroku
```
heroku apps:create mvcmovie
heroku create --buildpack http://github.com/heroku/dotnet-buildpack.git
heroku buildpacks:set heroku/dotnet
```