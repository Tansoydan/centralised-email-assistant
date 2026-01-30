# LENAH Email Assistant (MVP)

Property email assistant using a central/shared LENAH mailbox.

## MVP Goals
- Connect to Gmail/Google Workspace shared mailbox via Gmail API (read-only first)
- Fetch relevant emails (unread / label-based)
- Classify + draft replies with a LOCAL Ollama LLM
- Create Gmail draft replies (do not auto-send)
- Produce auditable logs of decisions

## Setup
- Python + virtualenv
- `requirements.txt` for dependencies
- Secrets are stored locally in `.env` (not committed)

## Milestones
- M1: Project skeleton + venv + dependencies
- M2: Gmail API auth + read-only smoke test
- M3: Filtering (unread/labels) + logging
- M4: Ollama classification + draft generation
- M5: Gmail draft creation + audit trail
EOF
