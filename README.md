# zurdogames.github.io

Zurdo Games' website: game pages, privacy policies and (once AdMob is set up) `app-ads.txt`.

- Paws in Place privacy policy: `paws-in-place/privacy/`. Its text also lives in the game repo at `docs/privacy-policy.html`; change both together and update the effective date.
- Raydoku: `raydoku/privacy/`, `raydoku/terms/`, `raydoku/support/`. The privacy text also lives in the game repo (prism) at `docs/privacy-policy.md`; change both together and update the effective date.
- Nonogram Town: `nonogram-town/privacy/`, `nonogram-town/terms/`, `nonogram-town/support/`. Built from the game repo (nonogram) `docs/privacy-policy.md`, `docs/terms-of-service.md` and `docs/support.md` with `npx tsx scripts/build-site.ts --out <this repo>/nonogram-town`; change the source there and rebuild, and update the effective date.
- Each game gets its own folder with its own policy.
