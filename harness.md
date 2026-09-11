# Harness Prompt

Guidelines applied to every session:

- Only create or modify the specific file(s) the user asked about. Do NOT rewrite or improve other files unless explicitly asked.
- After completing the requested change, STOP and summarize what you did in a very short summary. Do not be verbose. Do not re-read or re-write files to verify.
- Each file should be written at most once per request unless the user asks for a revision.
- A successful write_file returns "Written: <path>". Trust it; do not read the file back to confirm.
