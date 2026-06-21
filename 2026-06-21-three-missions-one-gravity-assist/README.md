# Jedna proca, trzy różne zadania

Gotowy pakiet o widocznej w aplikacji sekcji `Proca grawitacyjna w ruchu`,
która pozwala porównać trzy prawdziwe misje na jednym ekranie. Apollo 13
wraca po pętli ratunkowej, Voyager 2 zbiera kolejne asysty ku zewnętrznym
planetom, a Galileo układa dłuższą trasę przez Wenus i dwie asysty Ziemi.

- `instagram-stories/` - pięć plansz 1080 x 1920;
- `facebook-linkedin/` - dwa obrazy 1200 x 1500;
- `three-missions-one-gravity-assist.zip` - pełna paczka do publikacji;
- `linkedin-facebook-post.md` - osobne teksty dla obu kanałów;
- `preview.png` - podgląd całego zestawu;
- `manifest.json` - pochodzenie grafiki i źródła naukowe.

## Status

`ready`

## Źródła

- prawdziwy ekran sekcji z aktywnym Apollo 13 i widocznym wyborem trzech misji:
  `source/apollo-tabs-desktop-1440x900.png`
- prawdziwy ekran tej samej sekcji po przełączeniu na Voyagera 2:
  `source/voyager-tabs-desktop-1440x900.png`
- prawdziwy ekran telefonu po przełączeniu na Galileo:
  `source/galileo-phone-390x844.png`
- logika sekcji, sterowania etapami i wyboru misji:
  `next-app/src/GravityAssistLab.jsx`,
  `next-app/src/gravityAssistMission.js`,
  `next-app/src/gravityAssistController.js`,
  `next-app/src/App.jsx`
- kontrakt naukowy dla historii asyst grawitacyjnych:
  `docs/agent/SCIENCE_GAMEPLAY.md`
- źródła naukowe:
  NASA Apollo 13 Mission Details,
  NASA Science Basics of Spaceflight: A Gravity Assist Primer,
  NASA Science Galileo,
  NASA Science Voyager 2
