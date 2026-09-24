# OpenChat
- Frontend: Next.js 16, React 19, Typescript 7, Tailwind CSS 4, shadcn/ui in frontend/ 
- Backend: FastAPI, Python 3.13, using python uv, ruff, pytest in backend/
- AI: Ollama at localhost:11434, model qwen3.5:2b , Local AI APIs
- AI: OpenAI or Anthropic AI or Gemini Cloud AI APIs (fallback)
- Start Frontend: (port 3000)
cd frontend/
npm run dev
- Start Backend: (port 8000)
cd backend/
uv run fastapi dev
- Install Backend Dependancies: uv add <package_name>
- uv sync (if project clone)
- Install Frontend Dependancies: npm install <package_name>
- Test: cd backend && pytest

# Rules
- Never commit .env or API keys
- Run the tests after every change