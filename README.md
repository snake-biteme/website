Biteme Landing page
--------
A basic landing page for Biteme

## Technologies

The page is based on `Bootstrap` 4.5.2. and leverages the `SASS`. 
Templating done through `nunjucks`.

The site is running on AWS. The whole deployment is automated by CI/CD pipeline in GitHub Actions.

## Requirements
 - NodeJS 14


## Installation & Run

```
#!bash

docker-compose -f docker-compose.yml -f docker-compose.dev.yml up
```

## Storybook

To run storybook locally run inside container:

```commandline
npm run storybook
```
