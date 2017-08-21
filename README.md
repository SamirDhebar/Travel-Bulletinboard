<img src="assets/css/images/bulletinBoard.png" align="right" />

# Travel Bulletinboard [![MIT license](https://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/samirdhebar/travel_bulletinboard_express/master/LICENSE.md)
<br>

## Running this project
* To initialize the project run `npm install` to install the packages for this project
* After install the npm packages, run `npm start` to get the project up and running which can be found at [localhost:4000](localhost:4000)
<br>

## Goals

* Use an Express server that allows people to post messages to a page
	* Each message will consist of a title and body

* Site will have two pages
	* First page will show a list of all the messages people have posted
	* Second page is a form where someone can add their own message

* Messages will be stored in a postgres database:
<br>

## Data Model
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

<br>

## Languages and Stuff Used for this Project:


<img src="assets/css/images/node.png" align= "center" /> <br><br> Node is a multi-platform, open-source Javascript run-time environment that executes code on the server-side.
<br><br>

<img src="assets/css/images/express.png" align="left" /> <br><br> Express is a web application framework for Node.js which acts as its de facto standard server framework
<br><br>
<img src="assets/css/images/postgres.png" align="left" /> <br><br><br><br> PostgreSQL is an object-relational database management system which stores and fetches data securely in response to requests from other software applications.
<br>
<br>


## Contribute

* Contributions are always welcome!
Please read the [contribution guidelines](Contributing.md) first.
<br>

## License
 <img src="assets/css/images/mitLicense.png" align= "center" /> <br><br>This project is available the under the [MIT License](https://github.com/samirdhebar/travel_bulletinboard_express/blob/master/LICENSE.md).
