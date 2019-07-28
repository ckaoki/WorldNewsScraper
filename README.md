# WorldNewsScraper

This is a web app that lets users view and leave comments on the latest news scraped from weeklyworldnews.com.
 

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites
1. Node.js must be installed on local machine or host. See https://nodejs.org/en/download/ for instructions.
  
### Overview

1. Whenever a user visits this site, the app scrapes stories from weeklyworldnews.com and displays. Each scraped article is saved to a mongo database. The app scrapes and displays the following information for each article:

     * Headline - the title of the article

     * Summary - a short summary of the article

     * URL - the url to the original article

2. Users are also be able to leave comments on the articles displayed and revisit them later. The comments are saved to the database as well and associated with their articles. Users are also be able to delete comments left on articles. All stored comments are be visible to every user.


### Installing

1. To install source files use git to clone files from https://github.com/ckaoki/WorldNewsScraper.
2. In a bash terminal or Visual Code terminal navigate to the directory that you downloaded the files from github.
3. Install the Node package (express) by entering the following in the terminal:   
    *npm install* 
4. (optional) If deploying to to a host such as Heroku perform the following:
   1. Navigate to the root project folder in a terminal.
   2. Enter the following command in the terminal:
   *git push heroku master*

### Operation
To view Burger page navigate to https://radiant-plains-54475.herokuapp.com/.
The Burger app can be operated on the local host as instructed below.
1. Using a browser navigate to the main page:   
2. In the left column *News Articles* Click next to the article to leave or view a note.  
3. In the right column leave or view any notes regarding this article.

## Running the tests

Validation of World News app was perform using a chrome browser. World News app was run as directed in the previous section - **Operation**.  

### Break down into end to end tests

Source files have been extensively tested by displaying pages in Visual Code.

### And coding style tests

I'm starting to get some style.

## Deployment

Navigate to https://github.com/ckaoki/WorldNewsScraper to clone.

## Built With

* [Visual Studio Code](https://code.visualstudio.com/)

## Contributing

Please read our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use github for version control (https://github.com/your/project/tags). 

## In development
Implementing textual hints.

## Authors

* **Cullan Aoki** - *Initial work* - https://github.com/ckaoki/WorldNewsScraper

## License

This project is not licensed.

## Acknowledgments
* Joe Rehfuss
* Trae Shanks
* Lan Truong

