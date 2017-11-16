# &lt;starcounter-debug-aid&gt;

Polymer Elements for debugging Starcounter Palindrom web apps

Pressing <kbd>CTRL</kbd>+<kbd>&#96;</kbd> (or <kbd>CTRL</kbd>+<kbd>§</kbd> or any other key that's above your <kbd>Tab</kbd> key) brings up a popup that helps to debug Starcounter apps

<img src="https://rawgit.com/StarcounterSamples/starcounter-debug-aid/master/keyboard.svg">

<img src="https://raw.githubusercontent.com/StarcounterSamples/starcounter-debug-aid/master/screenshot.png">

Currently composed of:

- `fast-json-patch-error-reporter` - shows incorrect JSON-Patches (the incorrect patch and the expanable JSON tree)
- `juicy-error-stacktrace-reporter` - shows uncaught errors (stack traces)
- `palindrom-js-listener.js` - subscribes to palindrom-client `patchreceived` & `patchsent` events. Has shared `getPalindromClient` method.
- `palindrom-js-patches.html` - shows JSON-Patches log from PalindromListenter.

## [Contributing and Development](CONTRIBUTING.md)

## License

MIT
