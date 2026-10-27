# Harborwell Voice

Harborwell is a voice-enabled clinic automation prototype that combines natural conversation, appointment operations, private knowledge retrieval, validation, and automated email generation.

> This repository is a public project showcase. Production source code is maintained privately and is not distributed because of intellectual-property and security requirements.

## My Role

**AI Automation Engineer / Full-Stack Engineer**

- Designed the voice-agent experience and operational boundaries.
- Built full-stack product surfaces and backend integrations.
- Implemented grounded retrieval for approved clinic information.
- Connected appointment events to automated email generation through n8n.
- Designed validation, persistence, failure handling, and deployment configuration.

## What the Prototype Demonstrates

- Natural voice interaction with explicit confirmation before operational changes
- Availability lookup, appointment creation, rescheduling, and cancellation
- Private document retrieval for grounded clinic responses
- Structured appointment and activity data in PostgreSQL/Supabase
- Automated confirmation and update emails generated through n8n
- Clear healthcare boundaries and escalation behavior

## Architecture

1. **Voice agent** - intent detection, turn-taking, and user confirmation
2. **Application tools** - validated scheduling operations and state changes
3. **Supabase/PostgreSQL** - appointments, contacts, documents, and activity state
4. **RAG layer** - retrieval from approved private clinic documents
5. **n8n email automation** - generates and delivers appointment emails from events

## Technology

- Next.js, React, and TypeScript
- Tailwind CSS
- ElevenLabs Voice AI
- Supabase and PostgreSQL
- RAG and vector retrieval
- n8n email automation
- Docker and production environment configuration

## Demo

- [Live Demo](https://harborwell-voice.vercel.app/)
- [Product Walkthrough](https://www.youtube.com/watch?v=Z1uZfet-cLU)

## Source Availability

This repository intentionally contains no production source code, environment configuration, credentials, private documents, database exports, or proprietary assets.

A technical walkthrough and selected implementation details are available upon request.

## Usage and Rights

All project descriptions and materials are provided for portfolio review only. No license is granted to copy, redistribute, or reuse the private implementation.
