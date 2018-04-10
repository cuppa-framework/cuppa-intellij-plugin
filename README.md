# IntelliJ Plugin for [Cuppa](http://cuppa.forgerock.org) [![Build Status](https://travis-ci.org/cuppa-framework/cuppa-intellij-plugin.svg?branch=master)](https://travis-ci.org/cuppa-framework/cuppa-intellij-plugin)

This repository is for the IntelliJ plugin for Cuppa.
Cuppa is a test framework for Java 8.
For more details on Cuppa, see the [website](http://cuppa.forgerock.org).

The plugin currently provides the following features:

* Live templates for quickly writing Cuppa tests.
* Stacktrace folding for hiding Cuppa calls in stacktraces.

## Getting Started

You can install the plugin from within IntelliJ.
Alternatively, you can download the plugin from the [plugin's page](https://plugins.jetbrains.com/plugin/8254) on the
JetBrains site.

## Contributing

Check out the [active issues](https://github.com/cuppa-framework/cuppa-intellij-plugin/issues) to get some ideas for
what to work on.

### Building

Cuppa is built using [Gradle](https://gradle.org/):

```shell
$ cd cuppa-intellij-plugin
$ ./gradlew build
```

Run `./gradlew tasks` to see a list of all available tasks.

We use the `intellij` Gradle plugin to bundle and run the plugin in IDEA using the `buildPlugin` and `runIde` tasks,
respectively.

## License

Cuppa and this plugin are licensed under an [Apache 2.0 license](./LICENSE).
