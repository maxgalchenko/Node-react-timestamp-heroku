# Timestamp Microservice

<div align="center">

[![Node.js](https://img.shields.io/badge/Node.js-12.18.3-339933?style=for-the-badge&logo=node.js&logoColor=white)](https://nodejs.org/) [![Express](https://img.shields.io/badge/Express-4.x-000000?style=for-the-badge&logo=express&logoColor=white)](https://expressjs.com/) [![CORS](https://img.shields.io/badge/CORS-enabled-5e5e5e?style=for-the-badge)](https://developer.mozilla.org/docs/Web/HTTP/CORS) [![Moment.js](https://img.shields.io/badge/Moment.js-2.29.1-1a1a1a?style=for-the-badge)](https://momentjs.com/)

</div>

## Overview

Simple Express service that returns Unix and UTC timestamps. Built as a FreeCodeCamp APIs & Microservices project and suitable for quick deployment.

## Key Features

- Current timestamp at `/api/timestamp/`.

- Parse `:date` as ISO-8601 string or Unix milliseconds at `/api/timestamp/:date`.

- CORS enabled for remote testing.

## Tech Stack

Node.js 12, Express 4, Moment 2, CORS

## Architecture

Single Express server serving static assets from `build/` and exposing REST endpoints under `/api/timestamp`. No database or persistent storage.

## Prerequisites

- Node.js: `12.18.3`

## Installation

```bash

git clone https://github.com/maxgalchenko/Node-react-timestamp-heroku.git

cd Node-react-timestamp-heroku

npm install

```

## Environment Variables

```env

PORT=3000

```

## Quick Start

```bash

export PORT=3000

npm start

```

Open http://localhost:3000

## Available Scripts

- `npm start` – Start the Express server on `PORT`.

---

<div align="center">

Built with ❤️ by [Maksym Galchenko](https://github.com/maxgalchenko)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/galchenko-max/)

[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-green?style=for-the-badge&logo=web)](https://portfolio-green-six-29.vercel.app/)

[![Email](https://img.shields.io/badge/Email-Contact-red?style=for-the-badge&logo=gmail)](mailto:galchenko.maksym@gmail.com)

![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)

</div>
