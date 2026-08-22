# Ten sam wyścig, dwa tempa

Gotowy pakiet o realnej funkcji działającej aplikacji: wyścigu orbitalnym,
który pozwala wybrać tempo `Spokojnie` albo `Normalnie` bez zmieniania tej
samej zasady zielonej orbity, hamowania i dopalania.

- `instagram-stories/` - pięć plansz 1080 x 1920;
- `facebook-linkedin/` - dwa obrazy 1200 x 1500;
- `orbit-race-two-paces.zip` - pełna paczka do publikacji;
- `linkedin-facebook-post.md` - osobne teksty dla obu kanałów;
- `preview.png` - podgląd całego zestawu;
- `manifest.json` - pochodzenie grafiki i źródła.

## Status

`ready`

## Źródła

- prawdziwy ekran desktopowego wyścigu orbitalnego z wybraną opcją
  `Spokojnie` i metą `5` okrążeń:
  `source/race-calm-desktop-1440x900.png`
- prawdziwy ekran desktopowego wyścigu orbitalnego z wybraną opcją
  `Normalnie` i metą `5` okrążeń:
  `source/race-normal-desktop-1440x900.png`
- prawdziwy ekran telefonicznego wyścigu orbitalnego z otwartym panelem
  ustawień i wybranym tempem `Spokojnie`:
  `source/race-calm-phone-390x844.png`
- prawdziwy ekran telefonicznego wyścigu orbitalnego z otwartym panelem
  ustawień i wybranym tempem `Normalnie`:
  `source/race-normal-phone-390x844.png`
- logika wyboru tempa, wariantu wyścigu i wspólnej orbity:
  `next-app/src/RaceGame.jsx`,
  `next-app/src/racePhysics.js`,
  `next-app/src/raceControls.js`,
  `next-app/src/App.jsx`,
  `docs/agent/SCIENCE_GAMEPLAY.md`,
  `docs/agent/PRODUCT_CONTENT.md`
- źródła naukowe:
  NASA Space Place: What Is an Orbit?;
  NASA Glenn Research Center: What is Microgravity?;
  NASA Science: Basics of Spaceflight, Chapter 3: Gravity & Mechanics
