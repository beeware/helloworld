<a href="https://beeware.org"><img src="https://beeware.org/static/images/brutus-270.png" alt="BeeWare Logo" height="72"></a> <!-- rumdl-disable-line MD033 MD041 -->

# HelloWorld

[![Discord server](https://img.shields.io/discord/836455665257021440?label=Discord%20Chat&logo=discord&style=plastic)](https://beeware.org/bee/chat/)

This repository is the code for the [BeeWare tutorial](https://tutorial.beeware.org/), saved as a project.

## Getting started

For the full tutorial experience, visit https://tutorial.beeware.org/ and follow the instructions there. However, if you're looking for a quick sampler of development using BeeWare, you can do the following:

### Prerequisites

You will need a supported Python3 interpreter. In addition, you will need the following platform-specific tools:

* **macOS**: Ensure you have installed Xcode, and have accepted the Xcode license. If you're unsure if you've accespted the Xcode license, run `sudo xcodebuild -license`.
* **Windows**: Ensure that you are *not* using Python 3.14+
* **Linux**: Install [system dependencies for your distribution](https://tutorial.beeware.org/tutorial/tutorial-0/#__tabbed_1_2).

### Run the tutorial app

Once you've installed the pre-requisites:

1. Fork this repository into your own GitHub account by clicking the "Fork" button at the top of this page.

2. Check out your fork onto your own machine. Run `git clone https://github.com/brutus/helloworld` (replacing `brutus` with your own Github username).

3. Change into the helloworld directory: `cd helloworld`

4. Create a virtual environment: `python3 -m venv venv`

5. Activate the new virtual environment: `source venv/bin/activate`

6. Install Briefcase: `python -m pip install briefcase`

7. Run the project in developer mode: `briefcase dev`

8. Run the project in developer mode: `briefcase run`

9. Package the project into an installer: `briefcase package --adhoc`

### What next?

You've now got a fully functioning BeeWare app, packaged for distribution.

You can now modify the code in the app. Try some of the following tasks:

* Alter the title of the dialog
* Alter the text of the dialog to display a different greeting for some people (e.g., say "Hail, Brutus!" if the user's name is Brutus)
* Add a second button that displays a second dialog

After making each of your changes, run `briefcase dev` to test the changes in developer mode. Once you've got some changes that you're happy with, run `briefcase run -u` to update and run the updated version of the app.

## Community

You can talk to the BeeWare community through:

- [@beeware@fosstodon.org on Mastodon](https://fosstodon.org/@beeware)
- [Discord](https://beeware.org/bee/chat/)

We foster a welcoming and respectful community as described in our [BeeWare Community Code of Conduct](https://beeware.org/community/behavior/code-of-conduct/).

## Contributing

If you experience problems with the BeeWare Tutorial, [log them on GitHub](https://github.com/beeware/beeware-tutorial/issues). If you want to contribute code, please [fork the code](https://github.com/beeware/beeware-tutorial) and [submit a pull request](https://github.com/beeware/beeware-tutorial/pulls).
