# sox-buildpack

A [Heroku](https://www.heroku.com/) buildpack for using [SoX](http://sox.sourceforge.net/) in your Dockerized application. It's only purpose is to provide access to the SoX binary, so in order to actually compile your application you should utilize [heroku-buildpack-multi](https://github.com/heroku/heroku-buildpack-multi). The buildpack will install version 14.4.1 of SoX.
