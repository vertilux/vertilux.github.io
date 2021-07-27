# VTX API Documentation

## Introduction

VTX API is a set of programming code that enables data transmission between one software product and another!

## Authentication

To get started using VTX's API platform, you'll need a valid API key. All authenticated API requests should have a header value `X-Api-Key` set with this key.

If you're a Vertilux's customer and don't have an API key, please contact [it support](https://chat.vertilux.com).

## Response status codes

- 200: OK
- 401: Unathorize
- 404: API Key not found

## Generating documentation page

Insomnia Documenter offers a CLI tool to make it super easy to set up a documentation page.

### Requirements

- Node.js (8.x or higher is recommended)
- An exported Insomnia workspace JSON (v4)

### Using npx

`npx insomnia-documenter --config /path/to/insomnia/config.json`

### Running the page locally

To preview the page locally:

`npx server`

The page will be available at http://localhost:5000.
