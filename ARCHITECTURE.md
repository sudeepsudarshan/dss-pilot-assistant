# Architecture Overview

## Modules

### backend/ingestion  
- PDF parsing & chunking  
- Embedding with Gemini or OpenAI  
- Vector store upserts

### backend/api  
- FastAPI service  
- `/ingest` endpoint (optional)  
- `/query` endpoint: retrieve + call ChatGPT

### frontend/expo-app  
- React Native (Expo)  
- Phase selector + chat UI  
- Streaming response display  
- Source snippet viewer

### adapters/efb-integrations  
- Pluggable connectors for FlySmart+, AvioBook, etc.  
- API wrappers or web-view embeds
