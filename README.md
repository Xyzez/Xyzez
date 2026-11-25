# Republik Nusantara

An original browser game about a virtual country built by its citizens.
Register as a citizen, get a numbered ID card (KTP), work, buy and build
plots, vote in parliament, fund national projects and rise through the ranks
from *Warga* to *Presiden*.

## Play
Open `index.html` in any browser. It is a single file with no build step and
can be deployed as-is to Cloudflare Pages, GitHub Pages or Netlify.

## Features
- Top-down city map: tap or click to walk (WASD/arrow keys on desktop, `E` to enter)
- Citizen registration with a downloadable KTP image to share
- Kantor Kerja: 20-second tap mini-game to earn RpN coins (energy refills daily)
- Plots (kavling): buy, then upgrade Land → Rumah → Warung → Ruko for daily income
- Gedung Parlemen: a new proposal each day changes the country's stats
- Zona Proyek: crowdfund national projects with the other citizens
- Warung: cosmetics (hat, peci, sunglasses), a motorbike, coffee for energy
- Ranks, rich list, news ticker, chat and emotes with simulated citizens
- 1 in-game day = 1 real minute; income keeps building up while you're away (up to 30 days)
- Progress is saved in the browser (localStorage)

All citizens, chat and leaderboards are simulated on the player's device. To
make the game truly multiplayer (shared map, real chat, real citizen
numbers), add a backend such as Supabase.
