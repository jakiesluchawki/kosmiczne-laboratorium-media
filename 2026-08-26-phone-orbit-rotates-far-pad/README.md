# Telefoniczna orbita obraca dalszy pulpit

Gotowy pakiet o realnej funkcji działającej aplikacji: telefonicznym widoku
misji orbitalnej, w którym dalszy pulpit obraca się o `180°`, żeby dwoje
dzieci mogło siedzieć naprzeciw siebie i nadal widzieć ten sam tor lotu.

- `instagram-stories/` - pięć plansz 1080 x 1920;
- `facebook-linkedin/` - dwa obrazy 1200 x 1500;
- `phone-orbit-rotates-far-pad.zip` - pełna paczka do publikacji;
- `linkedin-facebook-post.md` - osobne teksty dla obu kanałów;
- `preview.png` - podgląd całego zestawu;
- `manifest.json` - pochodzenie grafiki i źródła.

## Status

`ready`

## Źródła

- prawdziwy ekran telefonicznej `Misji załogi` z odwróconym dalszym pulpitem:
  `source/crew-phone-390x844.png`
- prawdziwy ekran telefoniczny z otwartym panelem `Ustaw grę` nad tą samą
  planszą orbity: `source/crew-phone-settings-390x844.png`
- prawdziwy ekran telefonicznego `Wyścigu` z tym samym układem dwóch pulpitów:
  `source/race-phone-390x844.png`
- prawdziwy ekran desktopowej `Misji załogi`:
  `source/crew-desktop-1440x900.png`
- prawdziwy ekran desktopowego `Wyścigu`:
  `source/race-desktop-1440x900.png`
- logika wspólnej misji orbitalnej, panelu mobilnego, przycisku `Ustaw grę`
  i obrotu dalszego pulpitu:
  `next-app/src/RaceGame.jsx`,
  `next-app/src/styles.css`,
  `next-app/src/raceControls.js`,
  `next-app/src/racePhysics.js`,
  `next-app/src/App.jsx`,
  `docs/agent/SCIENCE_GAMEPLAY.md`,
  `docs/agent/PRODUCT_CONTENT.md`
- źródła naukowe:
  NASA Space Place: What Is Gravity?;
  NASA Space Place: What Is a Satellite?;
  NASA Science: Basics of Space Flight, Chapter 3: Gravity & Mechanics;
  NASA Science: Orbits and Kepler's Laws
