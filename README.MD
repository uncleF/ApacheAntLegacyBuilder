### Building with Apache ANT

* [Getting started with Apache ANT](http://ant.apache.org/manual/index.html).

Before using this builder you'll have to update `build.xml`, to include
relevant paths to [YUI Compressor](http://yui.github.io/yuicompressor/),
[Rhino](https://developer.mozilla.org/en/docs/Rhino) and [JSHint](http://jshint.com).

`build.xml` also contains basic project configuration options like CSS
files order, directory structure, etc.

Run `ant` to check JavaScript, compile and compress CSS and JavaScript,
copy newly built project into `/build` and update paths in all of the
HTML files.

USES [YUI Compressor](http://yui.github.io/yuicompressor/),
[Rhino](https://developer.mozilla.org/en/docs/Rhino) and [JSHint](http://jshint.com).