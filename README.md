This repo is a fork of https://github.com/amivin/aria2-heroku

# aria2-heroku v1.36.0

A Heroku buildpack for aria2 that always downloads the latest static build.
Unlike other build packs, I never compile anything and remove this git.

## Usage

Add the following to your `.buildpacks`:

```
https://github.com/SayanthD/aria2-heroku.git
```

Or run the following from the heroku command line:

```
heroku buildpacks:add https://github.com/SayanthD/aria2-heroku.git
```

## Credits
* [amivin/aria2-heroku](https://github.com/amivin/aria2-heroku)
* [q3aql/aria2-static-builds](https://github.com/q3aql/aria2-static-builds)