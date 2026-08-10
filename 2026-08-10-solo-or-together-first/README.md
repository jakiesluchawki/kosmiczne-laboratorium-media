# Najpierw solo albo we dwoje

Gotowy pakiet o pierwszym ekranie działającej aplikacji. Zanim dziecko wejdzie
do obserwatorium, Kosmiczne Laboratorium pyta spokojnie `Jak dziś
odkrywamy?`: samemu czy razem. Nazwy są opcjonalne, zostają lokalnie na
urządzeniu i nie blokują wejścia do właściwej mapy misji.

- `instagram-stories/` - pięć plansz 1080 x 1920;
- `facebook-linkedin/` - dwa obrazy 1200 x 1500;
- `solo-or-together-first.zip` - pełna paczka do publikacji;
- `linkedin-facebook-post.md` - osobne teksty dla obu kanałów;
- `preview.png` - podgląd całego zestawu;
- `manifest.json` - pochodzenie grafiki i źródła.

## Status

`ready`

## Źródła

- prawdziwy ekran pierwszego pytania `Jak dziś odkrywamy?` na desktopie:
  `source/player-choice-desktop-1440x900.png`
- prawdziwy ekran tego samego pytania na telefonie:
  `source/player-choice-phone-390x844.png`
- prawdziwy ekran mapy misji po wyborze trybu solo:
  `source/mission-home-solo-desktop-1440x900.png`
- prawdziwy ekran kroku z opcjonalnymi nazwami po wyborze gry we dwoje:
  `source/player-names-desktop-1440x900.png`
- prawdziwy ekran tego samego kroku na telefonie:
  `source/player-names-phone-390x844.png`
- logika pierwszego pytania o styl odkrywania, lokalnych nazw i wejścia do
  mapy misji:
  `next-app/src/App.jsx`,
  `next-app/src/playerSetupFlow.js`,
  `next-app/src/bonusMissions.js`,
  `docs/agent/PRODUCT_CONTENT.md`
- źródła naukowe dla kontekstu wspólnej misji orbitalnej i odkryć o grawitacji:
  NASA: What Is an Orbit? (Grades 5-8),
  NASA Science: Basics of Space Flight
