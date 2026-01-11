# aqlinter

This package is a custom linter based on [flutter_lints](https://pub.dev/packages/flutter_lints).

## Features

- Easy-to-use setup with `aqlinter.yaml`.
- Supports custom lint rules for teams and projects.

### Versions
| **Package Version** | **Flutter Version** | **Dependencies**  |
|:-------------------:|:-------------------:|:------------------|
|        1.0.2        |      >= 3.19.0      | flutter_lints: ^4.0.0<br>analyzer: ^6.4.1 |
|        2.0.0        |      >= 3.24.0      | flutter_lints: ^5.0.0<br>analyzer: ^6.7.0 |
|        2.1.0        |      >= 3.27.0      | flutter_lints: ^5.0.0<br>analyzer: ^7.3.0 |
|        3.0.0        |      >= 3.24.5      | flutter_lints: ^5.0.0 |


## Getting Started

### Installation

Add `aqlinter` to your project:
```bash
flutter pub add aqlinter
```

### Usage

Create an analysis_options.yaml file at the root of the package

`analysis_options.yaml` file
```
include: package:aqlinter/aqlinter.yaml

linter:
    rules:
        # You can enter additional rules that you want.
```
