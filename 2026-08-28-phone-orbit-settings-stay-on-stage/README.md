# Telefoniczna orbita trzyma ustawienia nad tą samą planszą

Gotowy pakiet o realnej funkcji działającej aplikacji: telefonicznym widoku
misji orbitalnej, w którym `Ustaw grę` otwiera tryb, grawitację, tempo i metę
wyścigu nad tą samą żywą planszą, więc wspólna zabawa mieści się w jednym
widoku bez rozrywania lotu na osobne ekrany.

- `instagram-stories/` - pięć plansz 1080 x 1920;
- `facebook-linkedin/` - dwa obrazy 1200 x 1500;
- `phone-orbit-settings-stay-on-stage.zip` - pełna paczka do publikacji;
- `linkedin-facebook-post.md` - osobne teksty dla obu kanałów;
- `preview.png` - podgląd całego zestawu;
- `manifest.json` - pochodzenie grafiki i źródła.

## Status

`ready`

## Źródła

- prawdziwy ekran telefonicznej `Misji załogi` z całym układem gry w jednym
  widoku: `source/orbit-phone-390x844.png`
- prawdziwy ekran telefoniczny z otwartym `Ustaw grę` nad tą samą planszą
  `Misji załogi`: `source/orbit-phone-settings-390x844.png`
- prawdziwy ekran telefonicznego `Wyścigu` z otwartym `Ustaw grę` i metą
  `3 / 5 / 10`: `source/orbit-phone-settings-race-390x844.png`
- prawdziwy ekran desktopowej `Misji załogi` z tym samym centrum orbity:
  `source/orbit-desktop-1440x900.png`
- logika mobilnego układu, panelu `Ustaw grę`, trybu wyścigu i widoku bez
  przewijania:
  `next-app/src/RaceGame.jsx`,
  `next-app/src/styles.css`,
  `next-app/src/raceControls.js`,
  `next-app/src/App.jsx`,
  `docs/agent/SCIENCE_GAMEPLAY.md`,
  `docs/agent/PRODUCT_CONTENT.md`
- źródła naukowe:
  NASA Space Place: What Is Gravity?;
  NASA Space Place: What Is an Orbit?;
  NASA Science: Basics of Space Flight, Chapter 3: Gravity & Mechanics;
  JPL Education: Balancing Forces
