# This repository contains a Node.js application with CRUD functionality for user posts, including authentication using Passport JWT tokens. It also provides an API to retrieve posts based on geolocation coordinates. The dashboard displays the count of active and inactive posts.


# Node.js Login API System
To access protected endpoints, you need to include a valid JWT token in the request headers. You can obtain a token through the login endpoint.

Endpoints
POST /api/user/register: Register a new user.
POST /api/user/login: Log in and receive a JWT token.
GET /api/post: Get all posts for the authenticated user.
GET /api/post/:id: Get a specific post by ID.
POST /api/post: Create a new post.
PUT /api/post/:id: Update an existing post.
DELETE /api/post/:id: Delete a post.
GET /api/post/location?latitude={latitude}&longitude={longitude}: Get posts based on geolocation.
GET /api/dashboard: Get counts of active and inactive posts.
Features
User registration and authentication using JWT tokens.
CRUD operations for user posts.
Geolocation-based post retrieval.
Dashboard displaying counts of active and inactive posts.

