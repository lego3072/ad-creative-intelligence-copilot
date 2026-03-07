# Ad Creative Intelligence Copilot

Analyze ad hooks, CTAs, and message structures; route best candidates into launch-ready campaign drafts.

## Run locally
```bash
pip install -r requirements.txt
uvicorn app.main:app --reload --port 8000
```

## Endpoints
- `/`
- `/docs-page`
- `/health`
- `/v1/public/config`
- `/llms.txt`
