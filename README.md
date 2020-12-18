# clintp.xyz

![lint and deploy site](https://github.com/yuhonas/clintp.xyz/workflows/lint%20and%20deploy%20site/badge.svg)

## Getting Started

This is a simple one page bio site that uses [vuejs](https://vuejs.org) with some basic CI/CD using [github actions](https://github.com/actions) and a resume built using [latex](https://www.latex-project.org/)

### Prerequisites

### Site

* Node.js 14.x

### Installing

Install all our dependencies

```
$ npm install
```

## Development

To run a local web server for development

```
$ npm run serve
```

## Running the tests


### Unit tests
```
npm run test:unit
```

### End-to-end tests
```
npm run test:e2e
```

### Lints and fixes files
```
npm run lint
```

## Building the site

To build a static website for hosting

```
npm run build
```

## Deployment


This site is automatically built and deployed by [github actions](https://github.com/actions) to [Github Pages](https://pages.github.com/)


## Building the resume

My resume is built using [latex](https://www.latex-project.org/)

![picture of latex envy](./public/latexenvy-300.png)

To export it to pdf

```
$ npm resume:export
```
