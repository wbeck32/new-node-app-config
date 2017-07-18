# Default configuration for a new node project

### files included:

- .eslintrc
- .gitignore
- .travis.yml
- .npmrc (this one doesn't work yet)
- There's also a file with the default eslint properties for reference

## Notes


### package.json test scripts entry for mocha


`"scripts": {
    "test": "mocha tests",
    "start": "npm test -- -w"
  }`

### npm install devDependencies command


`npm install -D packagename
`

### alias to run the script, copy these files and start npm init

## TODOS

- make an alias for the command

- add build file structure to script

- configure .npmrc and add to the files

- make .eslintrc more robust
- call npm init after files have been copied
- alternately create package.json with mostly default values and copy the test scripts into it

