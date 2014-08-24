# Synopsis

Yet another "run a command when a file changes" script.

[![license - MIT](http://b.repl.ca/v1/license-MIT-blue.png)](http://pluma.mit-license.org) [![Flattr this](https://api.flattr.com/button/flattr-badge-large.png)](https://flattr.com/submit/auto?user_id=pluma&url=https://github.com/pluma/dirwatch)

[![NPM status](https://nodei.co/npm/dirwatch.png?compact=true)](https://npmjs.org/package/dirwatch)

[![Dependencies](https://david-dm.org/pluma/dirwatch.png?theme=shields.io)](https://david-dm.org/pluma/dirwatch)

# Usage

`dirwatch -c [command] [path...]`

Runs the given command every time a file in the given path(s) changes.

# Options

* `cmd`, `c`: The command to execute.
* `debounce`, `d`: Only execute the command once within this many milliseconds.
* `verbose`, `v`: More output.

# License

The MIT/Expat license. For more information, see http://pluma.mit-license.org/ or the accompanying [LICENSE](https://github.com/pluma/dirwatch/blob/master/LICENSE) file.