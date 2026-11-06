# Lobby Hub 2.0 — Version B prototype

A clickable prototype of the redesigned Lobby Hub check-in screen (Version B), built from the "Lobby of the Future" Figma file, plus a side panel that tracks the eight usability-test tasks.

## Run it

Open `index.html` in a browser, or turn on GitHub Pages for this repository (Settings → Pages → Deploy from branch → `main`, folder `/ (root)`). The prototype will then be live at `https://<your-username>.github.io/<repo-name>/`.

## What's in it

- `index.html`: the whole prototype. The Hub screen is built in HTML so check-in, search, select mode and adding bags change its state.
- `img/`: exports of the detail screens from Figma (Profile, Documents, Bags, SSRs, Seats, VCR, Remarks and the sheets that open from them).

## Testing on an iPad mini

The participant view shows only the app screen, edge to edge, with no task panel or toolbar. The iPad mini's screen is the same size the design was drawn at (744 × 1133), so it appears 1:1.

1. On the iPad, open `https://niraliasmani.github.io/Lobby-hub-prototype-B/#test` in Safari.
2. For true full screen, tap Share → **Add to Home Screen**, then launch "Lobby Hub B" from the Home Screen. It opens without Safari's address bar and always in the participant view.
3. Hold the iPad in portrait and turn on Guided Access (Settings → Accessibility) if you want to stop participants leaving the app.

**Facilitator menu:** press and hold the status bar (the strip with the time at the very top) for about 1.5 seconds. From there you can restart for the next participant or exit the participant view.

## Using it in a test session

- Tasks tick themselves off as the participant completes them; click a task to toggle it by hand.
- Tapping a blank area briefly highlights everything that can be tapped.
- **Restart** resets guests, bags and task progress between participants.
