#JSHint for Sublime Text 2

The best JavaScript syntax checker: [JSHint](http://www.jshint.com/) for the best text editor: [Sublime Text 2](http://www.sublimetext.com/2)

##Install

Prerequisites:

- node 0.6.x
- npm 1.1.x `curl http://npmjs.org/install.sh | sh`
- jshint 0.5.x `npm install -g jshint`
- [Sublime Package Control](http://wbond.net/sublime_packages/package_control/installation)

1. `command`-`shift`-`P` *or `control`-`shift`-`P` in Linux/Windows*
2. type `install p`, select `Package Control: Install Package`
3. type `jshint`, select `JSHint`

*Without Sublime Package Control, you could manually clone to Packages directory as 'JSHint', exactly.*

##Run JSHint on an active JavaScript file in Sublime Text 2

- `control`-`J` *or Tools/Contextual menus or the Command Palette*
- `F4` jump to next error row/column
- `shift`-`F4` jump to previous error row-column

##Run JSHint on save

Install [SublimeOnSaveBuild](https://github.com/alexnj/SublimeOnSaveBuild)

**Note:** The `control`-`J` shortcut changes the Build System on the current file to JSHint, then Builds to run JSHint on the file and output any errors for jumping to within the file. You could alternatively set the Build System set to Automatic and `command`-`B`/`control`-`B`/`F7`, but only on files that end with .js.

**Mac OS X:** Install node with homebrew `brew update` `brew install node`. Make sure you have either the latest Command Line Tools or Xcode before installing homebrew.

**Windows:** Node should be in your `CLASSPATH` in environment variables, `C:\Program Files (x86)\nodejs`
