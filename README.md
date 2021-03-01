# Dok

Dok is a documentation tool/system that helps you to document (almost) everything. It can be seen as a personal assistant, it invites you to write, organize and then publish your personal knowledge online.

![dok-system](dok-system.jpg)

## Status

Dok is currently in full development. Things will be broken, then repaired, then broken again. To use it is to accept its experimental phase.

## Installation

### Project structure

Clone this repository inside your project folder. In addition to this repository, you will have a content folder, where you have your own folders, markdown files, media files, etc. and an automatically generated public folder.

```
my-project                  # your project folder
├── dok                     # this repository (inside your project folder)
│   ├── requirements.txt    # python dependencies
│   ├── script.py           # dok script
│   └── settings.yml        # default settings
│   └── assets              # default CSS
│   └── templates           # default templates
│   └── ...
├── content                 # your content
│   ├── 2021-01-01-about    # an article folder         
│       ├── _index.md       # an article content file
│   └── ...
├── assets                  # your own assets that overwrite the main ones
│   ├── css
│       ├── style.scss      # your own scss styles
├── public                  # public files, automatically generated             
└── ...
```

### Python and PIP

Dok requires [Python](https://en.wikipedia.org/wiki/Python_(programming_language)). You can download it from the [official Python website](https://www.python.org/downloads/), for Linux, Mac OS X or Windows.

PIP, the package manager for Python, is also required to run Dok. The Python installer installs `pip`, so it should be ready for you to use. You can verify that `pip` is available by running the following command in your console: `pip --version`. It should give you information about the current pip version, if it is correctly installed.

### Dependencies

In order to install the dependencies:
1. Open a terminal and make sure you are inside the `dok` folder: `cd my_project/dok`
2. run `pip install -r requirements.txt`

## Quickstart

### Create a project
### Create an article
### Generate your site

Run `python dok/script.py`.

### Preview your site

Open your web browser and visit the path provided by the script when you run it. Under Linux, this looks like: `file:///home/antoine/repo/my-project/public/index.html`.

## Write
### Metadata
### Markdown
### Images
### Videos
### Extras

## Organize
### Folders
### Links
### Bookmarks
### Images feed

## Publish
### Gitlab
### Github

## Command-line interface
### Create a shortcut
### Options

