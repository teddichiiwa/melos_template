# 📮 Melos Template

A CLEAN melos template. 🌊🏄‍♂️

## 🙋 What is `melos`?

> Melos is a [CLI](https://en.wikipedia.org/wiki/Command-line_interface) tool used to help manage Dart projects with multiple packages (also known as mono-repos). It is currently still in active development however is in use on projects such as [FlutterFire](https://github.com/FirebaseExtended/flutterfire).
>
> Splitting up large code bases into separate independently versioned packages is extremely useful for code sharing. However, making changes across many repositories is messy and difficult to track, and testing across repositories gets complicated. Melos helps solve these issues by allowing multiple packages to work together within one repository, whilst being totally independent of each other. Features include:
>
> - Automatic versioning & changelog generation.
> - Automated publishing of packages to pub.dev.
> - Local package linking and installation.
> - Executing simultaneous commands across packages.
> - Listing of local packages & their dependencies.
> - Melos also works great on CI/CD environments to help automate complex tasks and challenges.

👉 [Melos website](https://melos.invertase.dev)

## → Install `melos`

Melos can be installed as a global package via [pub.dev](https://pub.dev/):

```bash
dart pub global activate melos
```

## 🛫 Bootstrap

> Once installed & setup, Melos needs to be bootstrapped. Bootstrapping has 2 primary roles:
>
> 1. Installing all package dependencies (internally using pub get).
> 2. Locally linking any packages together.

Clean and Bootstrap all packages:

```bash
melos clean_and_bootstrap
```

## 📝 Predefine scripts

Perform buildrunner run:

```bash
melos build_runner:build
```

Run flutter test:

```bash
melos test:flutter
```
