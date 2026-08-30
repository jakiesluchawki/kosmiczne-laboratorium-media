# Wyścig orbitalny pokazuje chwilę dobrej orbity

Gotowy pakiet o realnej funkcji działającej aplikacji: wyścigu orbitalnym,
w którym każdy gracz ma własny wskaźnik z zielonym pasem między `HAMUJ`
i `DOPALAJ`, więc dziecko widzi chwilę `DOBRA ORBITA` dokładnie tam,
gdzie już steruje lotem na desktopie i telefonie.

- `instagram-stories/` - pięć plansz 1080 x 1920;
- `facebook-linkedin/` - dwa obrazy 1200 x 1500;
- `orbit-gauge-shows-good-orbit.zip` - pełna paczka do publikacji;
- `linkedin-facebook-post.md` - osobne teksty dla obu kanałów;
- `preview.png` - podgląd całego zestawu;
- `manifest.json` - pochodzenie grafiki i źródła.

## Status

`ready`

## Źródła

- prawdziwy ekran desktopowego `Wyścigu po orbicie` z pełnym widokiem trybu,
  wyborem mety `5` i sceną gry: `source/orbit-desktop-1440x900.png`
- prawdziwy ekran desktopowego `Wyścigu po orbicie` przesunięty na żywe
  wskaźniki `DOBRA ORBITA`, zielony pas oraz etykiety `DOPALAJ` i `HAMUJ`:
  `source/orbit-desktop-scroll-1440x900.png`
- prawdziwy ekran telefonicznego `Wyścigu po orbicie` z tym samym startem,
  paskiem komunikatu, wynikiem `0 / 5` i dużymi pedałami `HAMUJ` oraz
  `DOPALAJ`:
  `source/orbit-phone-390x844.png`
- logika wyścigu orbitalnego, statusu `DOBRA ORBITA`, zielonego pasa,
  etykiet `HAMUJ`/`DOPALAJ`, komunikatów `za blisko planety` i
  `za daleko od planety` oraz liczenia zielonego obiegu:
  `next-app/src/RaceGame.jsx`,
  `next-app/src/raceControls.js`,
  `docs/agent/SCIENCE_GAMEPLAY.md`
- źródła naukowe:
  NASA Space Place: What Is a Satellite?;
  NASA Science: Basics of Space Flight, Chapter 4: Trajectories;
  NASA Science Blog: How to Be an Orbital Mechanic: Reading Orbit Plots with
  Parker Solar Probe
