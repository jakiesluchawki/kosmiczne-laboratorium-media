# Deszcz kulek pokazuje wiele torów naraz

Gotowy pakiet o działającym przycisku `Deszcz kulek` w bonusowym `Kosmicznym
placu zabaw`. Jedno kliknięcie uruchamia serię małych lotów w tym samym polu
grawitacyjnym, więc dziecko może porównać kilka torów naraz zamiast patrzeć
tylko na jeden pojedynczy przykład.

- `instagram-stories/` - pięć plansz 1080 x 1920;
- `facebook-linkedin/` - dwa obrazy 1200 x 1500;
- `ball-rain-shows-gravity.zip` - pełna paczka do publikacji;
- `linkedin-facebook-post.md` - osobne teksty dla obu kanałów;
- `preview.png` - podgląd całego zestawu;
- `manifest.json` - pochodzenie grafiki i źródła.

## Status

`ready`

## Źródła

- prawdziwy, ciaśniejszy ekran desktopowego `Kosmicznego placu zabaw` po
  uruchomieniu `Deszczu kulek`:
  `source/playground-rain-focus-desktop-1440x900.png`
- prawdziwy ekran telefonu z tym samym narzędziem i stanem po zatrzymaniu:
  `source/playground-rain-paused-phone-390x844.png`
- prawdziwy pełny ekran desktopowy z tym samym stanem:
  `source/playground-rain-paused-desktop-1440x900.png`
- logika przycisku `Deszcz kulek`, pauzy i czyszczenia torów:
  `next-app/src/App.jsx`
- logika lotu i grawitacji w bonusowym placu zabaw:
  `next-app/src/playgroundPhysics.js`,
  `docs/agent/SCIENCE_GAMEPLAY.md`,
  `docs/agent/PRODUCT_CONTENT.md`
- źródła naukowe dla grawitacji i orbit:
  NASA Space Place: What Is Gravity?,
  NASA: What Is an Orbit? (Grades 5-8)
