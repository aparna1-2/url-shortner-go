# URL Shortener Service

A backend project that converts long URLs into short links.

Example:

Long URL:
https://example.com/very/long/link

Short URL:
http://localhost:8080/aB12x

## Features

- Generate short links
- Redirect to original URL
- Track click count
- Expiration support

## Project Structure

main.go → server entry point  
handlers → API endpoints  
models → data models  
storage → database/memory storage  
utils → helper functions