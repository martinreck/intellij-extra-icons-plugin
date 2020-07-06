<h1 align="center">
    <a href="https://travis-ci.org/jonathanlermitage/intellij-extra-icons-plugin">
      <img src="./resources/META-INF/pluginIcon.svg" width="84" height="84" alt="logo"/>
    </a><br/>
    Extra Icons
</h1>

<p align="center">
    <a href="https://travis-ci.org/jonathanlermitage/intellij-extra-icons-plugin"><img src="https://travis-ci.org/jonathanlermitage/intellij-extra-icons-plugin.svg?branch=master"/></a>
    <a href="https://plugins.jetbrains.com/plugin/11058-extra-icons"><img src="https://img.shields.io/jetbrains/plugin/v/11058-extra-icons.svg"/></a>
    <a href="https://plugins.jetbrains.com/plugin/11058-extra-icons"><img src="https://img.shields.io/jetbrains/plugin/d/11058-extra-icons.svg"/></a>
    <a href="https://github.com/jonathanlermitage/intellij-extra-icons-plugin/blob/master/LICENSE.txt"><img src="https://img.shields.io/github/license/jonathanlermitage/intellij-extra-icons-plugin.svg"/></a>
</p>

Intellij IDEA (Community and Ultimate) plugin that adds icons for files like Travis YML, Appveyor YML, etc.  
Starting from version 0.4, it works with all JetBrains products like WebStorm, DataGrip, etc.

Download plugin from [JetBrains Plugins Repository](https://plugins.jetbrains.com/plugin/11058-extra-icons) or via your JetBrains IDE (<kbd>File</kbd>, <kbd>Settings</kbd>, <kbd>Plugins</kbd>, <kbd>Browse repositories...</kbd>).

## Build

Install JDK8+. You should be able to start Gradle Wrapper (`gradlew`).

### Gradle commands

* build plugin: `./gradlew buildPlugin`. See generated jar in: `build/libs/`.
* run IDE with plugin: `./gradlew runIde`.
* check for dependencies updates: `./gradlew dependencyUpdates -Drevision=release -DoutputFormatter=plain -DoutputDir=./build/`.

### Branches

* [master](https://github.com/jonathanlermitage/intellij-extra-icons-plugin): plugin is compatible with 183.0+ IDE builds (2018.3 and newer).
* [ide201](https://github.com/jonathanlermitage/intellij-extra-icons-plugin/tree/ide201): plugin is compatible with 201.0+ IDE builds (2020.1 and newer). Contains features that need capabilities introduced in IntelliJ 2020.1. Will be merged into master once IntelliJ 2020.2 is released: I don't want to force users to install latest IDE, I'd like to keep compatibility with previous IDE version.
* [ide173](https://github.com/jonathanlermitage/intellij-extra-icons-plugin/tree/ide173): ~~plugin is compatible with 173.0+ IDE builds (2017.3 and newer), but doesn't support AngularJS icons.~~ this branch is terminated.

## Contribution

Open an issue or a pull-request:

* feature request -> support new icons: please provide SVG or 32x32 PNG (with transparency) file(s) and filename patterns.
* contributions: they should be tested.      
  Please reformat new and modified code only: do not reformat the whole project or entire existing file (in other words, try to limit the amount of changes in order to speed up code review).  
  To finish, don't hesitate to add your name or nickname (and LinkedIn profile, etc.) to contributors list ;-)

## License

MIT License. In other words, you can do what you want: this project is entirely OpenSource, Free and Gratis.

## Credits

### 🤝 Contributors

* (author) Jonathan Lermitage (<jonathan.lermitage@gmail.com>, [![linkedin](misc/linkedin_profile_badge.png)](https://www.linkedin.com/in/jonathan-lermitage-092711142/), [buymeacoff.ee](http://buymeacoff.ee/jlermitage))
* Edoardo Luppi (<lp.edoardo@gmail.com>)
* Matthias Kunnen ([github.com/MatthiasKunnen](https://github.com/MatthiasKunnen))
* Florian Böhm ([github.com/Sheigutn](https://github.com/Sheigutn))
* Mateusz Bajorek (<mateusz.bajorek@gmail.com>)

### 🤝 [JetBrains](https://www.jetbrains.com/idea/)

Thanks for their Open-Source licence to their amazing IDEs.

### 🤝 [Syntevo](https://www.syntevo.com/smartgit/)

Thanks for their licence for **SmartGit** (an excellent graphical Git client, free for non-commercial projects).

## Screenshots

![Dark Screenshot](misc/screenshots/intellijidea-ce_dark.png)

![Screenshot](misc/screenshots/intellijidea-ce.png)

![Config Panel Screenshot](misc/screenshots/config-panel.png)
