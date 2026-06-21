# CS 499 Computer Science Capstone ePortfolio

## Author

Duran Morrison

## Overview

This repository contains my final CS 499 Computer Science Capstone ePortfolio. The ePortfolio presents my professional self-assessment, code review, original artifact, enhanced artifact, and enhancement narratives.

For my capstone artifact, I selected my CS-465 Travlr Full Stack Application. Travlr is a full stack travel website built with Node.js, Express, MongoDB, Mongoose, Handlebars, and Angular.

## ePortfolio Contents

* Professional self-assessment
* Code review
* Original Travlr artifact
* Enhanced Travlr artifact
* Enhancement One: Software Design and Engineering
* Enhancement Two: Algorithms and Data Structures
* Enhancement Three: Databases

## Artifact Summary

The Travlr application includes a customer-facing travel website, backend API routes, MongoDB database models, authentication logic, and an Angular admin application.

The enhanced version improves the original artifact in three major areas:

1. **Software Design and Engineering**

   * Centralized configuration
   * Refactored controller logic
   * Reusable helper functions
   * Travel page fallback behavior

2. **Algorithms and Data Structures**

   * Backend search
   * Sorting
   * Result limiting
   * Structured API response metadata
   * MongoDB ObjectId validation

3. **Databases**

   * Controlled admin seeding behavior
   * Stronger trip schema validation
   * Stronger user schema validation
   * Safer image filename validation
   * Email validation
   * Timestamps
   * Stronger password hashing

## Repository Structure

```text
cs-499-eportfolio
├── index.html
├── README.md
├── assets
│   ├── documents
│   ├── images
│   └── videos
└── artifacts
    ├── original
    └── enhanced
```

## Notes

The enhanced artifact does not include local environment secrets or dependency folders.

Excluded files/folders include:

```text
.env
node_modules
travlr-admin/node_modules
travlr-admin/.angular/cache
```

The repository includes `.env.example` in the enhanced artifact to show required environment variables safely.
