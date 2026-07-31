# Implementation Plan: OAuth2 Authentication

## Overview
Add social authentication using OAuth2 with Google and GitHub providers.

## Tasks
- [ ] Install dependencies (passport, passport-google-oauth20, passport-github2)
- [ ] Create authentication routes in `/api/auth`
- [ ] Implement passport strategies for each provider
- [ ] Add session management middleware
- [ ] Create login/logout UI components
- [ ] Add environment variables for OAuth credentials
- [ ] Write integration tests

## Detailed Steps
1. **Dependencies**: Add to package.json...
2. **Routes**: Create `/api/auth/google` and `/api/auth/github`...