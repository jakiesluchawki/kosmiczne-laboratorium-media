# Jeden ekran, dwa tryby orbity

Gotowy pakiet o realnej funkcji działającej aplikacji: tej samej misji
orbitalnej, która przełącza się między `Misją załogi` a `Wyścigiem` bez
uczenia dziecka dwóch osobnych układów sterowania na desktopie i telefonie.

- `instagram-stories/` - pięć plansz 1080 x 1920;
- `facebook-linkedin/` - dwa obrazy 1200 x 1500;
- `one-screen-two-orbit-modes.zip` - pełna paczka do publikacji;
- `linkedin-facebook-post.md` - osobne teksty dla obu kanałów;
- `preview.png` - podgląd całego zestawu;
- `manifest.json` - pochodzenie grafiki i źródła.

## Status

`ready`

## Źródła

- prawdziwy ekran desktopowej misji orbitalnej z aktywnym `Wyścigiem`:
  `source/race-mode-desktop-1440x900.png`
- prawdziwy ekran desktopowej misji orbitalnej z aktywną `Misją załogi`:
  `source/crew-mode-desktop-1440x900.png`
- prawdziwy ekran telefoniczny z otwartym panelem `Ustaw grę` i aktywnym
  `Wyścigiem`: `source/race-mode-phone-390x844.png`
- prawdziwy ekran telefoniczny z otwartym panelem `Ustaw grę` i aktywną
  `Misją załogi`: `source/crew-mode-phone-390x844.png`
- logika przełącznika `Tryb`, wspólnego sygnału i wyścigu po zielonym pasie:
  `next-app/src/RaceGame.jsx`,
  `next-app/src/crewMission.js`,
  `next-app/src/racePhysics.js`,
  `next-app/src/raceControls.js`,
  `next-app/src/App.jsx`,
  `docs/agent/SCIENCE_GAMEPLAY.md`,
  `docs/agent/PRODUCT_CONTENT.md`
- źródła naukowe:
  NASA Science: Basics of Space Flight, Chapter 3: Gravity & Mechanics;
  NASA Science: Orbits and Kepler's Laws
