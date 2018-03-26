---
title: Settings
---

Dart Code has a number of configurable settings that can be modified in your User Settings (`Ctrl`+`,` or `Cmd`+`,`) or Workspace Settings files.

* TOC
{:toc}

<!-- TODO: Split into Window/Resource scope -->

## dart.allowAnalytics `true`

Whether to send analytics such as startup timings, frequency of use of features and analysis server crashes.

## dart.closingLabels `true`

Whether to show annotations against constructor, method invocations and lists that span multiple lines.

## dart.checkForSdkUpdates `true`

Whether to check you are using the latest version of the Dart SDK at startup.

## dart.debugSdkLibraries `false`

Whether SDK libraries should be marked as debuggable.

## dart.debugExternalLibraries `false`

Whether libraries should be marked as debuggable.

## dart.flutterHotReloadOnSave `true`

Whether to automatically send a 'hot reload' request during a Flutter debug session when saving files.

## dart.flutterSdkPath

Override the detected Flutter SDK to allow you to run from another location.

## dart.insertArgumentPlaceholders `true`

Whether to insert argument placeholders during code completions.

## dart.lineLength `80`

The maximum length of a line of code. This is used by the document formatter.

## dart.pubAdditionalArgs

Additional args to pass to `pub get` and `pub upgrade` commands (eg. `--packages-dir`).

## dart.runPubGetOnPubspecChanges `true`

Whether to automatically run `pub get` whenever pubspec.yaml is saved.

## dart.promptToGetPackages `true`

Whether to prompt to get packages when opening a project with out of date packages.

## dart.promptToUpgradeWorkspace `true`

Whether to prompt to upgrade folders to Workspace Folders when projects are detected in sub-folders.

## dart.sdkPath

If the Dart SDK is not automatically found on your machine from your `PATH` you can enter the path to it here.

## dart.sdkPaths

If you often switch between multiple Dart SDKs, setting this option to an array of Dart SDK folders or folders that contain multiple Dart SDKs in sub-folders will allow fast switching by clicking the Dart SDK version in the status bar.

## dart.flutterSdkPaths

If you often switch between multiple Flutter SDKs/channels, setting this option to an array of Flutter SDK folders or folders that contain multiple Flutter SDKs in sub-folders will allow fast switching by clicking the Flutter SDK version in the status bar.

## dart.showLintNames `false`

Whether to show the names of linter rules in the problems panel to make it easier to `// ignore:`.

## dart.showTodos `true`

Whether to show TODOs in the Problems list.

## dart.vmAdditionalArgs

Additional args to pass to the Dart VM when running/debugging apps.