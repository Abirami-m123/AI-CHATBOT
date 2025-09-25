echo "# n8n Workflow

How to import:
1) In n8n, click **Workflows ▸ Import from File**.
2) Choose \`Myworkflow.json\`.
3) Update credentials & environment variables (not included in the JSON).
" > README.md

git add README.md
git commit -m "Add README with import steps"
git push
