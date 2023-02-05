# Speakers
A simple Speaker Management System built using Azure Functions and TypeScript.

## Prerequisites
Before you begin, you need to have the following installed on your machine:

Node.js
Azure Functions Core Tools

## Getting Started
Clone the repository: https://github.com/luisfff/speakers

Install the dependencies: `npm install`

Start the Backend Functions host: `func start --javascript --port 5001`

## Available Functions

The following Functions are available in this project:

createSpeaker: [POST] http://localhost:5001/api/createSpeaker

deleteSpeaker: [DELETE] http://localhost:5001/api/deleteSpeaker

getSpeaker: [GET] http://localhost:5001/api/getSpeaker

getSpeakers: [GET] http://localhost:5001/api/getSpeakers

updateSpeaker: [PUT] http://localhost:5001/api/updateSpeaker
