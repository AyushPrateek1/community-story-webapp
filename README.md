# Community Story Webapp

A collaborative story-sharing web application where users can create stories, continue stories written by others, and manage their own content through a user-focused platform.

## Overview

Community Story Webapp enables users to share their stories with a wider community while allowing other readers to contribute to ongoing stories. The application also provides user profiles, personal story management, and an indexed home page for discovering community content.

## Features

- **Story Creation** — Users can create and publish their own stories.
- **Story Continuation** — Readers can continue existing stories and contribute to collaborative storytelling.
- **Story Editing** — Story owners can edit and manage their published content.
- **User Profiles** — Users can maintain profiles and access their activity.
- **My Stories** — Dedicated view for managing stories created by the user.
- **Home Page Indexing** — Stories are indexed and surfaced through the application's home page.
- **User Authentication** — Secure signup and login flow with JWT-based authentication.
- **User Verification** — Verification functionality for registered users.

## Technology Stack

- **Node.js**
- **Express.js**
- **MongoDB**
- **React**
- **JWT**
- **JavaScript**
- **GitHub**

## Project Structure

```text
community-story-webapp/
├── index.js
├── db.js
├── package.json
├── package-lock.json
├── signup.js
├── login.js
├── jwtToken.js
├── userVerification.js
├── create.js
├── append.js
└── fetchPosts.js
