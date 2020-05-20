Copied from https://github.com/amivin/aria2-heroku
# Modified to fetch aria2 builds with custom patches from
https://github.com/P3TERX/aria2-builder
# aria2-heroku

A Heroku buildpack for aria2 that always downloads the latest static build.
Unlike other build packs, I never compile anything and remove this git.

## Usage

Add the following to your `.buildpacks`:

```
https://github.com/SayanthD/aria2-heroku.git#P3TERX
```

Or run the following from the heroku command line:

```
heroku buildpacks:add https://github.com/SayanthD/aria2-heroku.git#P3TERX
```
