# ruby-app

Self-contained ruby apps build script with [Traveling Ruby](http://phusion.github.io/traveling-ruby/)

## Supported App List

* [NewRelic Gearman Plugin](https://github.com/channelgrabber/newrelic-gearman-plugin)
* [fpm](https://github.com/jordansissel/fpm)
  * NOTE: due to [this Cent OS bug](https://github.com/jordansissel/fpm/issues/1090#issuecomment-211313877) we can only use fpm 1.4.0 on linux

## Usage Example

After clone: (Note: you need ruby 2.1 installed locally)

```bash
$ cd newrelic-gearman-plugin-app
$ rake package:linux:x86_64
```

A `newrelic-gearman-plugin-0.2.0-linux-x86_64.tar.gz` will be generated.

See [Traveling Ruby Documentation](https://github.com/phusion/traveling-ruby#getting-started) for more details
