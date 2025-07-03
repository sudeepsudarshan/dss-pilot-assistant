# DSS Pilot Assistant

**Objective:**  
Enable A321 pilots to get precise, flight-phase–aware procedural guidance via a simple chat interface.

## MVP Spec

**Core User Stories**  
1. PDF Ingestion  
2. Flight-Phase Context  
3. Ask Question  
4. Get Guidance  
5. View Source

**Must-Have Features**  
- Document Ingestion: PDF → text chunks → embeddings  
- Backend API: `/query?phase=&q=` → ChatGPT/Gemini → answer + sources  
- Frontend UI: phase dropdown, chat input, streaming answer, expandable sources  
- Deployment: Backend on Replit, Frontend on Vercel  
- Secure env & secrets (OpenAI, Gemini API keys)
