# Notes

## Tools

Create an account at:

* [https://typing.io/](Typing IO)
* [https://www.shortcutfoo.com](Shortcut Foo)

## Useful links

* [https://en.support.wordpress.com/markdown-quick-reference/](Markdown)

## Vocabulary

* `markdown`, is a language similar to html, it is used to describe the structure of a document. The advantage is its syntax is shorter.
* `prompt`, the text before the cursor on a terminal
* `CDN`. Content Delivery Network.

Cache

Quirks mode

## Terminal Commands

* `pwd`. Print Working Directory
* `cd`. Change directory
* `whoami`. Who am I? What's my user name.
* `mv <origin> <target>` Move a directory or a file to a specific location (target)
* `man <command>` Manual for any terminal command

## Character sets

* Repertoire. It's the set of numeric representations of characters
* Glyph. It's the visual representation of a character
* Character set. It's the numeric range used to represent characters (called code points)
* ASCII. First standard that used a range between  0 adn 255
* UNICODE supports a wider range

# Git

`git init` initializes a git repository
`git status` Outputs the current state of your repository
`git add <file_name>` Start tracking this file with Git
`git commit -m "message here"` Commit some changes
`git remote add origin git@github.com:CodeupClassroom/pinnacles_html.git` This is how you add a remote


VCS. Versioning Control System

* Snapshot -> Commits
* Your name, your email, the date, message, identifier (hash)
* Repository -> folder, your code + git information (history of your code)

Github

* Remote. A remote git repository

## HTML elements

Classification

* Block elements -> br p, div 
* Inline elements -> em, strong, span
* Void elements -> br, hr

* Elements can have attributes. Attributes describe properties for that element

- Required
 - img -> src
 - meta -> charset
- Optional -> id, class

An HTML can be either

They're related to syntax
* Well-formed
* Mal-formed

They're related to the standard
* Valid 
* Invalid

The value of some attributes is optional, for instance disabled in input.
The quotes are also optional unless the value has a space

# Servers paths

The root folder of a server, usually is not the same as the root folder of the machine
For our projects the root of the server is directory where our HTML pages are. For instance `pinnacles_html`. This folder is called the **public directory** 

## Paths

* Absolute paths. It starts with a /
* Relative paths


# Brew and tree

To install [brew](https://brew.sh/) run:

```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

To install tree run:

```
brew install tree
```

`tree` can be executed to colorize files and folders for easier distinction using the `tree -C` flag. For more options run `man tree`

Protocols

HTTP - Hyper-Text Transfer Protocol

HTTP Messages

2 parts
* Header
* Body

2 types of messages
* Request   -> Client-side -> Browser
* Response  -> Server-side -> Web server

HTTP verbs (methods)

GET   -> Read - Download
POST  -> Write - Sending data

Query string

key = value -> key-value pair

examples:
attributes in html elements
GET parameters in query strings

?search_query=javascript



























