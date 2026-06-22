# Jedna Ziemia, kilka chwil roku

Gotowy pakiet o działającym laboratorium pór roku, które pokazuje jedną
Ziemię w kilku chwilach tego samego obiegu. Na ekranie zostają widoczne
pozycje zimy, wiosny, lata i jesieni, żeby dziecko mogło porównać tę samą
planetę przy stałym kierunku osi, a nie pomylić model z czterema osobnymi
globami.

- `instagram-stories/` - pięć plansz 1080 x 1920;
- `facebook-linkedin/` - dwa obrazy 1200 x 1500;
- `one-earth-four-seasons.zip` - pełna paczka do publikacji;
- `linkedin-facebook-post.md` - osobne teksty dla obu kanałów;
- `preview.png` - podgląd całego zestawu;
- `manifest.json` - pochodzenie grafiki i źródła naukowe.

## Status

`ready`

## Źródła

- prawdziwy ekran zimy w laboratorium pór roku:
  `source/season-winter-desktop-1440x900.png`
- prawdziwy ekran lata w laboratorium pór roku:
  `source/season-summer-desktop-1440x900.png`
- prawdziwy ekran telefonu w tym samym laboratorium:
  `source/season-summer-phone-390x844.png`
- logika laboratorium, orbity sezonowej i odczytów światła:
  `next-app/src/App.jsx`,
  `next-app/src/seasonsGeometry.js`,
  `next-app/src/discoveryNavigation.js`
- kontrakt naukowy i produktowy:
  `docs/agent/SCIENCE_GAMEPLAY.md`,
  `docs/agent/PRODUCT_CONTENT.md`,
  `docs/agent/VISUAL_UX.md`
- źródła naukowe:
  NASA Space Place: What Causes the Seasons?,
  NASA Science: Helio and You: Seasons on Earth, Mars, and Beyond,
  NASA Scientific Visualization Studio: Solstice Animations
