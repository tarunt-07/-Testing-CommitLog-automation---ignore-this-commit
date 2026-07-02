# Workflow Export

Export your n8n workflow as JSON and place it here as `commitlog-workflow.json`.

## How to export
1. Open the workflow in n8n
2. Click the three-dot menu (top right) → Download
3. Rename the downloaded file to `commitlog-workflow.json` and place it in this folder

⚠️ Before committing, open the JSON and search for "key", "token", "secret" —
double check no raw credentials got embedded before pushing to a public repo.
