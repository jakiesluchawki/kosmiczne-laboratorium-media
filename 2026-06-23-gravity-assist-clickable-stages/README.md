# Proca grawitacyjna ma etapy, do których można wrócić

Gotowy pakiet o widocznej w działającej aplikacji sekcji `Proca grawitacyjna w
ruchu`, w której każda misja ma własne, nazwane etapy. Dziecko może wrócić
prosto do `Saturn zmienia kierunek` w Voyagerze 2 albo do `Drugie podanie
Ziemi` w Galileo, zamiast oglądać całą animację od początku.

- `instagram-stories/` - pięć plansz 1080 x 1920;
- `facebook-linkedin/` - dwa obrazy 1200 x 1500;
- `gravity-assist-clickable-stages.zip` - pełna paczka do publikacji;
- `linkedin-facebook-post.md` - osobne teksty dla obu kanałów;
- `preview.png` - podgląd całego zestawu;
- `manifest.json` - pochodzenie grafiki i źródła naukowe.

## Status

`ready`

## Źródła

- prawdziwy ekran sekcji z aktywnym Apollo 13:
  `source/apollo-intro-desktop-1440x900.png`
- prawdziwy ekran sekcji po skoku do etapu `Drugie podanie Ziemi` w Galileo:
  `source/galileo-stage4-desktop-1440x900.png`
- prawdziwy ekran sekcji po skoku do etapu `Saturn zmienia kierunek` w
  Voyagerze 2:
  `source/voyager-timeline-desktop-1440x900.png`
- prawdziwy ekran telefonu z tym samym etapem Voyagera 2:
  `source/voyager-stage3-phone-390x844.png`
- logika wyboru misji, przechodzenia po etapach i widocznych opisów:
  `next-app/src/GravityAssistLab.jsx`,
  `next-app/src/gravityAssistMission.js`,
  `next-app/src/gravityAssistController.js`,
  `next-app/src/App.jsx`
- kontrakt naukowy i produktowy:
  `docs/agent/SCIENCE_GAMEPLAY.md`,
  `docs/agent/PRODUCT_CONTENT.md`
- źródła naukowe:
  NASA Apollo 13 Off to the Moon,
  NASA Science Basics of Spaceflight: A Gravity Assist Primer,
  NASA Science Voyager 2,
  NASA Science Galileo
