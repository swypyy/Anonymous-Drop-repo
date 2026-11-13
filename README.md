# Anonymous Drop

A simple anonymous blogging and discussion app built with Node.js and Express.

🌐 Web page: [Open the blog](https://swypyy.github.io/blog.html)

## Overview

Anonymous Drop is a lightweight project for sharing anonymous posts and comments. It stores data in local JSON files and provides a simple backend API for creating and reading content.

## Features

- Create anonymous posts
- Read posts and comments
- Add comments to existing posts
- Local data storage using JSON files
- Simple Express API
- Beginner-friendly project structure

## Tech stack

- JavaScript
- Node.js
- Express
- JSON for local persistence

## Run locally

```bash
git clone https://github.com/swypyy/Anonymous-Drop-repo.git
cd Anonymous-Drop-repo
npm install
npm start
```

The app runs on port `3000` by default.

## API endpoints

| Method | Endpoint | Description |
| --- | --- | --- |
| `GET` | `/api/posts` | Fetch all posts |
| `POST` | `/api/posts` | Create a new post |
| `GET` | `/api/comments/:postId` | Fetch comments for a post |
| `POST` | `/api/comments/:postId` | Add a comment |

## Project purpose

This repository is meant to help practice backend development, API design, JSON storage, and front-end integration in a small but complete app.

## License

See [LICENSE](LICENSE) for more information.
