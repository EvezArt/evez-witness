# EVEZ Witness

Compliance and policy enforcement API for EVEZ agents.

## Run
```bash
uvicorn witness:app --reload
```

## API
- `GET /health` — Health check
- `POST /report` — Report a violation
- `GET /violations` — List violations
- `GET /audit` — Audit summary

---
*Built by EVEZ Factory (Steven AI)*
