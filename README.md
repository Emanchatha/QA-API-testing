# QA API Testing — Postman Collection

## Overview
A professional API test collection built with Postman 
covering REST API testing fundamentals with automated 
assertions.

## What's tested
- GET /users — fetch all users
- GET /users/:id — fetch single user  
- GET /users/999 — non-existent user (404 handling)
- POST /posts — create new post (201 validation)
- PUT /posts/1 — update existing post
- DELETE /posts/1 — delete post
- GET /posts/:id — fetch single post
- GET /posts/:id/comments — nested endpoint
- GET /posts/999 — non-existent post (404 handling)

## Test coverage
- 33 automated assertions
- 0 failures
- Avg response time: 253ms
- HTTP methods: GET, POST, PUT, DELETE
- Status codes tested: 200, 201, 404
- Environment variables for base URL

## Tools used
- Postman
- JSONPlaceholder API (free REST API)
- JavaScript (Chai assertions)

## How to run
1. Import `QuickBite-API-Collection.json` into Postman
2. Import `QuickBite-Environment.json` into Postman
3. Select "QuickBite development" environment
4. Click "Run Collection".
