<h3 align="center">
	Getting started with Localstack
</h3>
<p align="center">Getting started with Localstack. Performs the creation of an s3 bucket and uploads a file to the created bucket. Using Serverless Framework and Docker.</p>
<p align="center">
  <img alt="Repository size" src="https://img.shields.io/github/repo-size/robertosousa1/localstack-getting-started.svg">
  </a>
  <a href="https://github.com/robertosousa1/localstack-getting-started/issues">
    <img alt="Repository issues" src="https://img.shields.io/github/issues/robertosousa1/localstack-getting-started.svg">
  </a>
</p>

<p align="center">
  <a href="#ballot_box_with_check-prerequisites">Prerequisites</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
    <a href="#up-getting-started">Getting started</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
    <a href="#pencil2-how-to-contribute">How to contribute</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-license">License</a>
</p>

## [](#prerequisites):ballot_box_with_check: Prerequisites
-   [Node.js](https://nodejs.org/en/)
-   [NPM](https://www.npmjs.com/) or [Yarn](https://yarnpkg.com/pt-BR/docs/install)
- [Docker](https://www.docker.com/)

## [](#getting-started):up: Getting started

-  Clone this repo
-  Enter the folder `localstack-getting-started`
-  Run `yarn` or `npm install` to install the dependencies
-  Run `yarn test` or `npm test` to perform tests in the application
-  Run `docker-compose up --build` to start the application
-  Run `bash scripts/s3/create-bucket.sh meu-bucket` to create bucket
-  Run `bash scripts/s3/upload-file.sh meu-bucket text.txt` to upload file to bucket
-  Run `curl http://localhost:3000/dev/hello` to list files in the bucket

## [](#how-to-contribute):pencil2: How to contribute

-   Make a fork;
-   Create a branck with your feature:  `git checkout -b my-feature`;
-   Commit changes:  `git commit -m 'feat: My new feature'`;
-   Make a push to your branch:  `git push origin my-feature`.

After merging your receipt request to done, you can delete a branch from yours.


## [](#license):memo: License
This project is under the MIT license. See the [LICENSE](https://github.com/robertosousa1/localstack-getting-started/blob/master/LICENSE) for more information.

----------

Made with by Roberto Sousa  👋  [Get in touch!](https://www.linkedin.com/in/robertosousa01/)
