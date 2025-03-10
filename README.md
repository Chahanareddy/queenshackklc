# queenshackklc
queens hackathon 2025 - Likhitha Koppula, Chahana Reddy, Krishna Mehta

Mission Complete - Rocket Focus
MC - Rocket Focus is a Chrome Extension that keeps you on-task by detecting distracting websites, blocking them, and offering a Pomodoro timer—all with a fun rocket animation.

How It Works
Set a Goal
In the popup, enter your mission objective and click Launch Mission. The extension starts tracking your tabs.

Analysis
Each time you load or switch tabs, Mission Complete uses its backend, which leverages Gemini, to determine how off-task you might be.

Blocking
If you’re off-task, it automatically redirects or closes the tab.

Pomodoro Timer
A 25-minute timer you can start, pause/resume, or reset in the popup.
Continues counting in the background—even if you close the popup—and notifies you when time's up.
Installation
Clone or download this repository.
Load the unpacked extension in chrome://extensions (enable Developer Mode).
Run the Backend:
pip install flask openai
export GEMINI_API_KEY="YOUR_GEMINI_KEY"
python backend.py
Edit background.js to call http://localhost:8080 if needed, or point to your deployed server.
Usage
Open the extension popup, type your goal, and click Launch Mission.
Use the Pomodoro controls to manage your focus timer.
Browse as normal; Mission Complete will handle any off-task sites.
Enjoy your rocket-powered productivity!
