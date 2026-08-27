# Wspólna orbita pokazuje klawisze na pulpitach

Gotowy pakiet o realnej funkcji działającej aplikacji: wspólnej misji
orbitalnej, w której te same pedały `HAMUJ` i `DOPALAJ` pokazują też skróty
`Z/X` oraz `O/P`, więc dwoje dzieci może wracać na zielony tor dotykiem albo
klawiaturą bez uczenia się drugiego układu sterowania.

- `instagram-stories/` - pięć plansz 1080 x 1920;
- `facebook-linkedin/` - dwa obrazy 1200 x 1500;
- `orbit-pads-show-keys.zip` - pełna paczka do publikacji;
- `linkedin-facebook-post.md` - osobne teksty dla obu kanałów;
- `preview.png` - podgląd całego zestawu;
- `manifest.json` - pochodzenie grafiki i źródła.

## Status

`ready`

## Źródła

- prawdziwy ekran desktopowej `Misji załogi` z widocznymi skrótami `Z/X` i
  `O/P`: `source/crew-desktop-1440x900.png`
- prawdziwy ekran desktopowego `Wyścigu` z tym samym układem skrótów:
  `source/race-desktop-1440x900.png`
- prawdziwy ekran telefonicznej `Misji załogi` z dwoma pulpitami i tymi samymi
  klawiszami: `source/crew-phone-390x844.png`
- prawdziwy ekran telefonicznego `Wyścigu` z tym samym zestawem skrótów:
  `source/race-phone-390x844.png`
- logika widocznych skrótów, przycisków `HAMUJ` i `DOPALAJ`, wspólnego sygnału
  i trybu wyścigu:
  `next-app/src/RaceGame.jsx`,
  `next-app/src/raceControls.js`,
  `next-app/src/App.jsx`,
  `docs/agent/SCIENCE_GAMEPLAY.md`,
  `docs/agent/PRODUCT_CONTENT.md`
- źródła naukowe:
  NASA Science: Basics of Space Flight, Chapter 3: Gravity & Mechanics;
  NASA Space Place: What Is an Orbit?;
  JPL Education: Balancing Forces
