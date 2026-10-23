# Web Dev Prep Hub

A prep hub for web development learners: track study topics, log practice and revise weak areas.

![Status](https://img.shields.io/badge/status-in%20development-orange)
![License](https://img.shields.io/badge/license-MIT-blue)

> Currently at v0.1 (HTML structure). No live demo yet.

## Overview
I am a BCA (AI) student learning full-stack development, DSA and GenAI. Between lectures, practice and revision it is easy to lose track of what is done and what needs another pass. This project is my attempt to fix that for myself.

I build it in stages, applying each skill as I learn it. The commit history is meant to show that progression honestly, from plain HTML to a full-stack app with AI features.

## Planned features
- [ ] Topics grouped by subject, with status and progress
- [ ] Practice log: problem link, difficulty, tags, status, notes
- [ ] Revision list for weak topics
- [ ] Search and filters
- [ ] Accounts with login and per-user data
- [ ] Progress analytics and streaks
- [ ] AI quiz questions and hints (stretch)

## Roadmap
I start a version only after learning the skills it needs. Each version is a GitHub milestone and is tagged as a release when finished.

### Phase 1 - Frontend foundations
v0.1 - HTML structure (in progress)
- Semantic layout, accessible forms, SEO basics
- Done when: W3C validator passes and Lighthouse accessibility is 90+

v0.2 - CSS and responsive layout
- Flexbox, Grid, CSS variables, mobile-first, light animations
- Done when: it works from 360px to 1440px with no horizontal scroll

v0.3 - JavaScript and DOM
- Add, edit, delete topics, mark done, debounced search and filter
- Form validation, data in localStorage
- Done when: data survives a refresh and bad input is handled

### Phase 2 - Modern frontend
v0.4 - React, TypeScript and Tailwind
- Components, routing, custom hooks, shared state, typed data models
- Forms with React Hook Form and Zod
- Done when: feature parity with v0.3, deployed, live link in README

### Phase 3 - Backend
v0.5 - REST API
- Node, Express, MongoDB with Mongoose, versioned routes (/v1)
- Input validation, central error handling, logging, security headers, rate limiting
- Frontend connected with TanStack Query
- Done when: the API is documented and a Postman collection is included

v0.6 - Authentication and accounts
- Signup and login with bcrypt, JWT access and refresh tokens, auth middleware
- Per-user data isolation, optional Google login and avatar upload
- Done when: users only see their own data and no secrets are in the repo

v0.7 - Data and performance
- Indexes for search (checked with explain), aggregation pipelines for stats
- Redis caching with TTL and invalidation
- Done when: dashboard stats are cached and index use is documented

### Phase 4 - Production
v0.8 - Quality and deployment
- Jest tests, ESLint and Prettier, GitHub Actions CI
- Docker and Docker Compose (app, MongoDB, Redis), deployment with a domain and SSL
- Done when: CI is green on every push and the app starts with one command

### Phase 5 - AI
v0.9 - AI features
- Quiz and hints from an LLM API with schema-validated JSON and retries
- Streaming responses, token and cost limits, request logging
- Done when: invalid model output never breaks the UI

v1.0 - Docs and polish
- Architecture diagram, short design notes, changelog, demo GIF

### Design decisions
- A single monolith by choice: this product does not need microservices.
- DSA solutions live in a separate repository.
- Out of scope: payments, public leaderboards and real-time features.

## Tech stack
- Now: HTML
- Planned: CSS, JavaScript, React, TypeScript, Tailwind, Node.js, Express, MongoDB, Redis, Docker

## Getting started
Coming with v0.1. The first version is a static page you can open directly in a browser.

## Development notes
- Commit messages follow `type: description` (feat, fix, docs, chore).
- Each version is tagged as a release.
- Planned work is tracked in GitHub Issues.

## Author
Sanjeev Kumar Sahani, BCA (AI) student at JNCU Ballia
[LinkedIn](www.linkedin.com/in/sanjeevsahanix) | [Portfolio](your-portfolio-link) | [Kaggle](your-kaggle-link)

## License
MIT. See the LICENSE file.
