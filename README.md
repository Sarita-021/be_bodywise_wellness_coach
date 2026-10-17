# Be Bodywise AI Wellness Coach

A responsive, clickable web-app prototype built as a single HTML file. It does not require Node.js, npm, an API key, or an internet connection.

## Run locally
1. Extract `be_bodywise_wellness_coach.zip`.
2. Open the `be_bodywise_wellness_coach` folder.
3. Double-click `index.html` to open it in Chrome, Edge, or Firefox.

For a local development server (optional), open a terminal in this folder and run:
- Python: `python -m http.server 8000`
- Then visit `http://localhost:8000`

## Included features
- Responsive navigation and dashboard
- Wellness assessment and profile summary
- Product cards with save/unsave state
- Label-based ingredient comparison
- Ingredient search and plain-language notes
- Realistic results guidance
- Progress journal with local browser storage, delete controls, and photo preview
- Skin routine helper based on self-reported inputs
- Wellness coach with predefined demo responses

## Hybrid prototype notes
The app's interactive features work locally. The coach currently uses predefined responses rather than a live AI model. The skin helper provides general routine notes and does not perform image-based analysis. Photo selection is only a preview; it is not sent anywhere. Data is stored in your browser's local storage and remains on that device/browser.

## Safety and data accuracy
Ingredient lists are transcribed from the label screenshots supplied for this project. Verify current packaging before making product decisions. Shared ingredients do not establish equal quantities, identical formulations, or equivalent benefits. This prototype is educational and does not diagnose conditions or guarantee product results.
