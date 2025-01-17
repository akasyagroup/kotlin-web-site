[//]: # (title: IDEs for Kotlin development)
[//]: # (description: JetBrains provides Kotlin plugin support for IntelliJ IDEA and Android Studio.)

JetBrains provides the official Kotlin plugin for two Integrated Development Environments (IDEs): [IntelliJ IDEA](#intellij-idea) and [Android Studio](#android-studio).

Other IDEs and source editors, such as Eclipse, Visual Studio Code, and Atom, have Kotlin community-supported plugins.

## IntelliJ IDEA

[IntelliJ IDEA](https://www.jetbrains.com/idea/download/) is an Integrated Development Environment (IDE) for JVM languages designed to maximize developer productivity.
It does the routine and repetitive tasks for you by providing clever code completion, static code analysis, and refactorings, and lets you focus on the bright side of software development, making it not only productive but also an enjoyable experience.

Kotlin plugin is bundled with each IntelliJ IDEA release.

Read more about IntelliJ IDEA in the [official documentation](https://www.jetbrains.com/help/idea/discover-intellij-idea.html).

## Android Studio

[Android Studio](https://developer.android.com/studio) is the official Integrated Development Environment (IDE) for Android app development, based on [IntelliJ IDEA](https://www.jetbrains.com/idea/). 
On top of IntelliJ's powerful code editor and developer tools, Android Studio offers even more features that enhance your productivity when building Android apps.

Kotlin plugin is bundled with each Android Studio release.

Read more about Android Studio in the [official documentation](https://developer.android.com/studio/intro).

## Compatibility with the Kotlin language versions

For IntelliJ IDEA and Android Studio the Kotlin plugin is bundled with each IDE release.
When the new Kotlin version is released, these IDEs will suggest updating Kotlin to the latest version automatically.
See the latest supported language version for each IDE in [Kotlin releases](releases.md#ide-support)

## Other IDEs support

JetBrains doesn't provide the Kotlin plugin for other IDEs.
However, some of the other IDEs and source editors, such as Eclipse, Visual Studio Code, and Atom, have their own Kotlin plugins developed by the Kotlin community.

You can use any text editor to write the Kotlin code, but without IDE-related features: code formatting, debugging tools, and so on.
To use Kotlin in text editors, you can download the latest Kotlin command-line compiler (`kotlin-compiler-%kotlinVersion%.zip`) from Kotlin [GitHub Releases](%kotlinLatestUrl%) and [install it manually](command-line.md#manual-install).
Also, you could use package managers, such as [Homebrew](command-line.md#homebrew), [SDKMAN!](command-line.md#sdkman), and [Snap package](command-line.md#snap-package).

## What's next?

* [Start your first project using IntelliJ IDEA IDE](jvm-get-started.md)
* [Create your first cross-platform mobile app using Android Studio](multiplatform-mobile-create-first-app.md)
* Learn how to [install EAP version of the Kotlin plugin](install-eap-plugin.md)