heroku-buildpack-xpdf
===========================
Added the libraries to use Xpdf 3.04 on Heroku

This buildpack is built to be used through [heroku-buildpack-multi](https://github.com/ddollar/heroku-buildpack-multi).
In your app you need to:
```
heroku config:set BUILDPACK_URL=https://github.com/ddollar/heroku-buildpack-multi
```

Then, create a `.buildpacks` file inside your app:
```
https://github.com/heroku/_YOUR_MAIN_BUILDPACK
https://github.com/shemer77/heroku-buildpack-xpdf
```
See the documentation of heroku-build-multi for a undetailed explanation on how to use it.

## License
WTFPL License. Copyright 2014 ARK.
