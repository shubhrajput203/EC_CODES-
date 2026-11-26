# RedLine

RedLine is a single-file web app that connects patients who urgently need blood with compatible donors nearby. There is no backend or complicated setup. Just open the file in a browser and it works.

# What it does
- Raise a request: Enter the patient details, blood group, units needed, urgency level, and hospital. You can pick a neighborhood (currently set up for Bhopal) or tap a button to use your current GPS location.
- Find the right donors fast: When you open a ticket, the app checks blood-type compatibility, skips anyone marked unavailable, and filters out donors who gave blood within the last 90 days. Everyone else is sorted by distance so the closest people show up first.
- Track outreach: Call matched donors directly from the ticket, mark them as contacted so you do not lose track, and update the ticket status (Open, In progress, Fulfilled, or Cancelled) as things move along.
- Manage donors: Anyone can register with their blood group, area, and last donation date, and flip their availability status whenever they want.

# How it is built
Everything lives inside one HTML file using plain HTML, CSS, and JavaScript. It saves all your tickets and donor lists locally in your browser using localStorage, and comes pre-loaded with a few sample entries so you can try it out right away. It also adapts to your device light or dark mode automatically.

# Running it
1. Download or clone this repository.
2. Open RedLine - Blood donor registration and requests.html in any modern browser.
3. That is it.
