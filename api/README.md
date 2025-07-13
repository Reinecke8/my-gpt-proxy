# Mein GPT-Proxy auf Vercel 🚀

## Setup

1. Diese Dateien in ein GitHub-Repo hochladen.
2. Bei Vercel deployen: https://vercel.com/new
3. Environment Variable `OPENAI_API_KEY` setzen.
4. Dein Chatbot läuft unter `/api/chat`.

## API-Aufruf

POST `/api/chat`

Payload:
```json
{
  "message": "Deine Frage"
}
