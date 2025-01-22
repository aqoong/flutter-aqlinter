# aqlinter

A Flutter lints configuration package that combines `flutter_lints` and `analyzer` for enhanced linting and static analysis.

## Features

- Centralized lint rules and analysis configurations.
- Easy-to-use setup with `aqlinter.yaml`.
- Supports custom lint rules for teams and projects.

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
