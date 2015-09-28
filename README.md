# nepal.json
The Nepal JSON Files

## Background
__I always wondered why somebody doesn't do something about that. Then I realized I was somebody.__ - _Lily Tomlin_

### About
We will attempt to build the largest open data JSON files covering different aspects of the country. Each sector will have a JSON file, and will grow over time.

### Getting Started
[__index.json__](index.json) is the first file you should start with traversing. It consists of the overall map of categories, category files and their respective sub categories.

### Generic Formation
Each file will contain three sections as follows: 

#### Version
- semantic version of the content in the data file
- can be both scalar of object
- if scalar will follow X.Y.Z format
- if object will contain  
        {
            code: "X.Y.Z",
            name: "<some-version-name>",
            description: "<some-version-description>"
        }

#### Manifest
Manifest will describe meta parameters related to the data file.

#### Data
Everything relevant goes inside the data section.


### How to contribute.
Fork this repo, and make a pull request. The formart / protocol will be decided later. Please check [__templates__](__templates__) directory for differnt types of files and their templates.

### What is JSON ?
JSON (Javascript Object Notation) is a lightweight data-interchange format. It is easy for humans to read and write. It is easy for machines to parse and generate. Please check [http://json.org](http://json.org) for more details.

