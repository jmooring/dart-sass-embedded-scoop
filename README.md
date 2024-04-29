> [!Note]
> The Dart Sass team discontinued Embedded Dart Sass, with v1.62.1 as the final release. Dart Sass v1.63.0 and later include the embedded compiler, accessible by running `sass --embedded`.

---

# Scoop package for Embedded Dart Sass

Embedded Dart Sass is a wrapper for [Dart Sass] that implements the compiler side of the [Embedded Sass protocol]. It's designed to be embedded in a host language, which then exposes an API for users to invoke Sass and define custom functions and importers.

Project: <https://github.com/sass/dart-sass-embedded>

Package: <https://scoop.sh/#/apps?q=dart-sass-embedded>

## Install, update, and uninstall

You may run Scoop commands from Command Prompt, PowerShell, or Windows PowerShell.

Use the commands below to install, update, or uninstall:

```text
scoop install dart-sass-embedded
scoop update dart-sass-embedded
scoop uninstall dart-sass-embedded
```

Reference: [Scoop commands]

## Usage

Start the compiler and listen on stdin

```text
dart-sass-embedded
```

Display version

```text
dart-sass-embedded --version
```

[Dart Sass]: https://sass-lang.com/dart-sass
[Embedded Sass protocol]: https://github.com/sass/sass-embedded-protocol/blob/master/README.md#readme
[Scoop commands]: https://github.com/ScoopInstaller/Scoop/wiki/Commands
