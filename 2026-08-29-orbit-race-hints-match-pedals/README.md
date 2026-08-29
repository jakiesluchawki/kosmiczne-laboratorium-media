# Wyścig orbitalny łączy podpowiedź z pedałami

Gotowy pakiet o realnej funkcji działającej aplikacji: wyścigu orbitalnym,
w którym wskazówka pod planszą używa tych samych słów `HAMUJ` i `DOPALAJ`,
które wracają na prawdziwych pedałach sterowania, więc wyjaśnienie od razu
łączy się z ruchem na desktopie i telefonie.

- `instagram-stories/` - pięć plansz 1080 x 1920;
- `facebook-linkedin/` - dwa obrazy 1200 x 1500;
- `orbit-race-hints-match-pedals.zip` - pełna paczka do publikacji;
- `linkedin-facebook-post.md` - osobne teksty dla obu kanałów;
- `preview.png` - podgląd całego zestawu;
- `manifest.json` - pochodzenie grafiki i źródła.

## Status

`ready`

## Źródła

- prawdziwy ekran desktopowego `Wyścigu po orbicie` z widocznym paskiem
  `Zręcznościowy model orbity`, wyborem mety `3` i pulpitami graczy:
  `source/orbit-desktop-1440x900.png`
- prawdziwy ekran telefonicznego `Wyścigu po orbicie` z tym samym startem,
  paskiem komunikatu i pedałami `HAMUJ` oraz `DOPALAJ`:
  `source/orbit-phone-390x844.png`
- logika wyścigu orbitalnego, etykiet `HAMUJ`/`DOPALAJ`, komunikatów
  `za blisko planety` i `za daleko od planety` oraz liczenia zielonego obiegu:
  `next-app/src/RaceGame.jsx`,
  `next-app/src/raceControls.js`,
  `docs/agent/SCIENCE_GAMEPLAY.md`
- źródła naukowe:
  NASA Space Place: What Is Gravity?;
  NASA Space Place: What Is an Orbit?;
  NASA Science: Basics of Space Flight, Chapter 3: Gravity & Mechanics;
  JPL Education: Balancing Forces
