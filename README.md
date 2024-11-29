
# Storage Service

## Purpose
Manages file uploads/downloads and integrates with storage backends.

## Tech Stack
- Nest.js
- MinIO
- AWS S3 SDK

## Features
- File chunking and deduplication
- File encryption and compression
- Storage backend integration (S3 or MinIO)

## Directory Structure
```plaintext
/src
  /controllers      # Route handlers for file operations
  /services         # Core business logic for storage
  /adapters         # Interfaces for S3/MinIO APIs
  /utils            # Helper functions
