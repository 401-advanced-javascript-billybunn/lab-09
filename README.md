![CF](http://i.imgur.com/7v5ASc8.png) LAB
=================================================
[![Build Status](https://travis-ci.com/401-advanced-javascript-billybunn/lab-09.svg?branch=working)](https://travis-ci.com/401-advanced-javascript-billybunn/lab-09)

## Notes
* UML diagrams done
* jsdocs almost complete
* started swagger, but had trouble completing (and getting it hosted somewhere?)
* didn't have time to write the tests. also think there's an issue with supergoose

<!-- LINKS -->
<!-- Replace the link for each in brackets below -->
<!-- PR (working into submission) -->
[1]: https://github.com/401-advanced-javascript-billybunn/lab-09/pull/1
<!-- travis build -->
[2]: https://travis-ci.com/401-advanced-javascript-billybunn/lab-09/builds/106270634
<!-- back-end -->
[3]: https://billybunn-401-lab-09.herokuapp.com/
<!-- front-end -->
[4]: http://xyz.com
<!-- swagger -->
[5]: http://xyz.com
<!-- jsdoc-->
[6]: https://billybunn-401-lab-09.herokuapp.com/docs/ 

## API Server

### Author: Billy Bunn

### Links and Resources
* [PR][1]
* [travis][2]
<!-- (when applicable) -->
* [back-end][3]
<!-- (when applicable) -->
<!-- * [front-end][4] -->

#### Documentation
<!-- API assignments only -->
* [swagger][5]
<!-- (All assignments) -->
* [jsdoc][6]

<!-- ### Modules
#### `modulename.js`
##### Exported Values and Methods

###### `foo(thing) -> string` -->
<!-- If you finished everything, you should be able to copy/paste the lab requirements and put them in present tense. -->
<!-- Usage Notes or examples -->

<!-- ###### `bar(array) -> array`
Usage Notes or examples -->

### Setup
#### `.env` requirements
* `npm i`
* `PORT` - assign a port number
* `MONGODB_URI` - URL to the running mongo instance/db


<!-- #### Running the app
* `npm start`
* Endpoint: `/`
* Endpoint: `/foo/bar/`
  * Returns a JSON object with abc in it.
* Endpoint: `/bing/zing/`
  * Returns a JSON object with xyz in it. -->
  
#### Tests
* How do you run tests?
  * `npm run test`
  * `npm run lint`
<!-- * What assertions were made?
* What assertions need to be / should be made? -->

#### UML
![get](./assets/all.jpg)

##### `GET /api/v1/:model`
![get](./assets/get.jpg)

##### `GET /api/v1/:model/:id`
![get](./assets/get.jpg)

##### `POST /api/v1/:model`
![get](./assets/post.jpg)

##### `DELETE /api/v1/:model/:id`
![get](./assets/delete.jpg)

##### `PUT /api/v1/:model/:id`
![get](./assets/put.jpg)
