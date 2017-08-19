## Travel Bulletinboard [![MIT license](https://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/samirdhebar/travel_bulletinboard_express/master/LICENSE.md)

### Running this project
* To initialize the project `npm install` to install the packages for this project
* After install the npm packages, `npm start` to get the project up and running which can be found at [localhost:4000](localhost:4000)

### Goals

* Use an Express server that allows people to post messages to a page
	* Each message will consist of a title and body

* Site will have two pages
	* First page will show a list of all the messages people have posted
	* Second page is a form where someone can add their own message

* Messages will be stored in a postgres database:

### Data Model
| Column   | Type                 |
|----------|----------------------|
|`id`      | SERIAL (PRIMARY KEY) |
|`title`| VARCHAR (100)   |
|`body`   | TEXT              |
|`created`   | TIMESTAMP              |

{


  "id": 12345,

  "title": Countries to Visit,

  "body":
  * Cambodia
  * Brazil

  "created": 2017-06-15 18:30:59

  }

### Stuff used to make this:

 * [markdown-editor](https://jbt.github.io/markdown-editor/) for Markdown parsing

## Contribute

Contributions are always welcome!
Please read the [contribution guidelines](Contributing.md) first.

### License
 <img src="assets/css/images/mitLicense.png" align= "center" /> This project is available the under the [MIT License](https://github.com/samirdhebar/travel_bulletinboard_express/blob/master/LICENSE.md).
