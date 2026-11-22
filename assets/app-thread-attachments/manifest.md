# SessionThread attachments: screenshots

- Branch: feat/app-thread-attachments, on desplega-ai/agent-swarm main@60a897e9a.
- Captured 2026-11-22 with headless Chromium (Playwright), desktop 1280x800, light (and dark for two states).
- The dashboard ran locally from this change (Vite) against a local API and a local agent-fs server (filesystem backend). The apps/ui tree matches the branch head.
- Before: an App whose SessionThread has no attachments prop (renders the same as main). After: the same App with attachments set.
- States: files before send, the sent message with its files, the count error, a failed upload that keeps text and files, a dropped PDF plus a pasted image.
- Not covered: thumbnails through presigned S3 URLs, the OS clipboard (paste was a synthetic event).
