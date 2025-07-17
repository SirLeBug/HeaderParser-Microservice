# Overview

This is a simple Request Header Parser Microservice built with Node.js and Express. It parses the incoming request headers and returns a JSON response containing the requester's IP address, preferred language(s), and software information extracted from the User-Agent string.

---

## About

This project was completed as part of the [freeCodeCamp](https://www.freecodecamp.org/) Backend Development and APIs curriculum. It helped me practice working with Express, HTTP headers, and how to extract useful client information from requests.

---

## Usage

- **GET** `/api/whoami` — Returns JSON with IP address, language, and software details of the requester.

### Example Response


````json
{
  "ipaddress": "123.45.67.89",
  "language": "en-US,en;q=0.9",
  "software": "Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/115.0.0.0 Safari/537.36"
}
````