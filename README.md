# angular-portfolio

Student Portfolio Project


## Requirements

- git
- Node (tested on Node v0.10.24)
- npm.
- Some modules will need need to be compiled.


## Install

- `npm install -g grunt-cli`
- `npm install`


## build

- `grunt build`

or

- `grunt dev` to keep building assets while working on source files.


## Development

Install the pre-commit hook. It will run tests and make sure assets are 
properly updated.

- ln -s ../../config/pre-commit.sh .git/hooks/pre-commit
