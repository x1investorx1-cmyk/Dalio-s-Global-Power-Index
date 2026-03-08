Global Power Index — Dalio Framework Visualizer
A static, server-free web application that ranks and compares nations across 17 key indicators of national power, built on Ray Dalio's framework from Principles for Dealing with the Big Debt Crisis and his work at Bridgewater Associates.
What it does
The app scores 100+ countries on a 0–10 scale across indicators including rule of law, military strength, education, corruption, infrastructure, debt levels, internal conflict, and geographic advantage. Each country receives a total score out of 170, establishing a global power ranking grounded in publicly available data from Transparency International, the IMF, World Bank, IISS, UNDP, WEF, and the Global Peace Index.
Users can search any country by name and instantly add it to a live comparison table. The interface shows five countries at a time — defaulting to the global top five scorers — and replaces the oldest entry each time a new country is searched. A reset button returns the view to the top five at any time.
Why it matters
Most geopolitical rankings are either paywalled, academically dense, or lack visual clarity. This tool makes the Dalio power framework accessible and interactive for anyone — investors, students, policy researchers, or the simply curious — without requiring a login, subscription, or backend server.
Technical approach
The entire dataset is embedded directly in the JavaScript, making the app fully static. There is no database, no API, and no server. It deploys instantly on Vercel or any static hosting platform as a single index.html file. The color-coded scoring table (green to red scale) allows for rapid cross-country pattern recognition at a glance.
Stack
Pure HTML, CSS, and vanilla JavaScript. No frameworks, no dependencies, no build step required.

Ratings reflect a synthesis of 2024–2025 data and involve interpretive judgment. Scores may vary by one to two points depending on the source weighting applied. This tool is intended for educational and analytical purposes.
