Setting up for the Media^Alps Workshop on Mac OS X

Please note, Mac OS 10.9 (Mavericks) or higher is recommended. If possible, update your operating system to at least 10.9. 

1. Open up a Terminal on your Mac. You can find Terminal within the Applications folder on your computer. It may be within a folder called "Utilities" You can also use Spotlight (by pressing ⌘ + spacebar) to search for "Terminal"

2. Install Xcode command-line developer tools. At the Terminal prompt, which ends with a $, type
```
xcode-select --install
```
Now press enter. This should start the installation process for the Xcode command line tools. Alternatively, you can download the complete Xcode package from the Mac App Store. Just search for Xcode.

3. Install Homebrew. This is a package manager that will allow you to easily install all of the software necessary for this workshop. To install Homebrew paste this command into your Terminal and press enter to run it. 
```
ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```




