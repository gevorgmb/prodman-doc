# API Documentation

This folder contains the split OpenAPI specification for the Laravel API.

## Files

- `openapi.yaml` - root OpenAPI document
- `components.yaml` - shared schemas, parameters, responses, security schemes
- `paths/*.yaml` - endpoint groups by feature
- `index.html` - Swagger UI viewer
- `swagger-init.js` - Swagger UI initialization

## Local usage

Open `index.html` in a browser from a static server.

If needed, serve this folder from the Laravel public directory or any local static server.

## Notes

The API uses Bearer authentication with Laravel Sanctum.
