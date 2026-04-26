============================================================
GORDON'S MASTER CONTROL CHEAT SHEET
============================================================

--- GIT & WEB DEPLOYMENT ---
git add . -> Tell Git to "track" all your new changes.
git commit -m "msg" -> Lock in your changes with a specific note.
git push -> Send your changes to the live website.
git pull -> Grab the latest code from GitHub.
git status -> See exactly what files you've changed.

--- WSL & LINUX NAVIGATION ---
ls -> List everything in the current folder.
cd [folder-name] -> Move into a specific folder.
cd .. -> Move "up" one level (back out).
pwd -> "Where am I?" (Shows full path).
code . -> Open the current folder in VS Code.

--- OPENCLAW / JARVIS CONTROLS ---
openclaw gateway start -> Launch the agent system.
openclaw gateway stop -> Shut it down.
openclaw gateway restart -> Refresh everything (Fixes most errors).

--- CHANGING MODELS (GEMINI 3) ---
openclaw config set agents.defaults.model google/gemini-3-flash-preview
openclaw config set agents.defaults.imageModel google/gemini-3-flash-image-preview

--- SYSTEM FIXES ---
wsl --shutdown -> The "Reboot" for the Linux side.
source ~/.bashrc -> Refresh your terminal settings/aliases.
============================================================
