# SPECS.md

## Architecture Overview

ChronosGPT consists of two main components:
1. **Chat Interface (v1)** – A Node.js backend using OAuth2 and Google Calendar API.
2. **Voice Mode (v2)** – AWS Amazon Connect integrated with a voice clone system.

## Technical Decisions

- **Node.js**: Chosen for speed of integration with Google APIs and frontend compatibility.
- **Google OAuth2**: For secure user identity and API access.
- **Amazon Connect**: Enables voice integration with phone call capabilities.
