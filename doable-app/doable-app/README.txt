Doable — To-Do List App
========================

HOW TO RUN
1. Unzip this folder.
2. Double-click todo-app.html (or right-click -> Open with -> Chrome/Edge).
   It opens directly in your browser — no installation, no server needed.

FEATURES
- Dashboard with stats, today's progress ring, and upcoming tasks
- Add / edit / delete tasks with title, description, due date, priority, category
- Filters: All, Pending, Completed, Today, Overdue + search
- Categories view, Settings (compact view toggle, auto-save toggle)
- Export to Excel: click "Export to Excel" anytime to download a snapshot (.xlsx)

AUTO-SAVE TO EXCEL (Chrome / Edge only)
Because you're opening this file directly (not inside a chat preview),
auto-save will work here:
1. Go to Settings in the sidebar.
2. Click "Connect file" and choose or create an .xlsx file.
3. From then on, every add/edit/delete automatically writes to that file.
4. Note: this connection resets each time you close and reopen the page —
   you'll need to click "Connect file" again and re-pick the same file.
   This is a browser security limit, not a bug.

NOTES
- All data lives in memory in the browser tab. Refreshing the page resets
  the task list back to the sample seed data (unless you re-load from Excel
  yourself — ask if you'd like that "load back from Excel" feature added).
- Requires an internet connection on first load (loads Google Fonts and the
  SheetJS library from a CDN).
