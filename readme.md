# Not working, please don't use!

# Heroku Buildpack: s3fs

Add support for s3fs-fuse.

## Usage

```
$ heroku buildpacks:set https://github.com/issueapp/heroku-buildpack-s3fs
$ heroku config:set AWSACCESSKEYID=key AWSSECRETACCESSKEY=secret
$ git commit --allow-empty
$ git push heroku
$ heroku run bin/s3fs --version
# profit!
```

## Reference

[Heroku Buildpacks](https://devcenter.heroku.com/articles/buildpacks)
[s3fs fuse](https://github.com/s3fs-fuse/s3fs-fuse)
[sh](https://www.freebsd.org/cgi/man.cgi?query=sh)
