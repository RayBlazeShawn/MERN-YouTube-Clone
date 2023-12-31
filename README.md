# MERN YouTube Clone

This project is an attempt to create a clone of YouTube using the MERN (MongoDB, Express.js, React.js, Node.js) tech stack.

## Project Overview

The application allows users to upload, view, and interact with video content. The objective of this project is to demonstrate competency in full-stack web development.

## Tech Stack

The application is built with:

- MongoDB: Our primary database, storing data in a flexible, JSON-like format.
- Express.js: A Node.js framework used for building our backend services.
- React.js: Used to build user interfaces in our front-end application.
- Node.js: The JavaScript runtime enabling us to run our server-side code.

We also use:

- AWS S3: To store video files.
- FFMPEG: For video processing.
- Docker & Kubernetes: For containerization and orchestration.
- Git: For version control.

## Installation and Setup

Ensure you have the following software installed:

- Node.js & npm
- MongoDB
- Git
- Docker (Optional for local development)
- Kubernetes CLI (Optional for local development)

Also, note that we're using AWS S3 for video file storage. You'll need to create a S3 bucket.

To get started:

1. Clone the repository: `git clone https://github.com/RayBlazeShawn/MERN-YouTube-Clone.git`.
2. Navigate into the cloned repository: `cd MERN-YouTube-Clone`
3. Install dependencies in both client and server directories: `cd client && npm install` then `cd ../server && npm install`

## Project Structure

The application consists of two parts:

- `client`: This directory houses the React.js front-end.
- `server`: This directory contains the Express.js back-end, which is further divided into:
    - `users`: Services related to users (registration, login, etc.)
    - `videos`: Services related to videos (upload, processing, viewing)

## Version Control

We're using Git for version control. Regular commits are made to ensure a clear development process. We also frequently push to the remote repository as a backup and to let others follow the progress of the project.
