# Jeden Księżyc, dwie perspektywy

Gotowy pakiet o działającym Laboratorium Księżyca, które na jednym ekranie
pokazuje ten sam moment na orbicie i ten sam widok z Ziemi przez okular
teleskopu. Dziecko nie musi przeskakiwać między oddzielnym schematem i
gotową odpowiedzią: ruch po orbicie i faza w okularze zmieniają się naraz.

- `instagram-stories/` - pięć plansz 1080 x 1920;
- `facebook-linkedin/` - dwa obrazy 1200 x 1500;
- `one-moon-two-perspectives.zip` - pełna paczka do publikacji;
- `linkedin-facebook-post.md` - osobne teksty dla obu kanałów;
- `preview.png` - podgląd całego zestawu;
- `manifest.json` - pochodzenie grafiki i źródła naukowe.

## Status

`ready`

## Źródła

- prawdziwy ekran desktopowego Laboratorium Księżyca z odsłoniętą pierwszą
  kwadrą: `source/moon-quarter-desktop-1440x900.png`
- prawdziwy ekran telefonu z tym samym stanem Laboratorium Księżyca:
  `source/moon-quarter-phone-390x844.png`
- logika faz, ruchu po orbicie i dwóch perspektyw:
  `next-app/src/MoonLab.jsx`,
  `next-app/src/moonModel.js`,
  `next-app/src/App.jsx`
- kontrakt naukowy i produktowy:
  `docs/agent/SCIENCE_GAMEPLAY.md`,
  `docs/agent/PRODUCT_CONTENT.md`,
  `docs/agent/VISUAL_UX.md`
- źródła naukowe:
  NASA Science: Moon Phases,
  NASA Science: Top Moon Questions,
  NASA Science: The Moon's Rotation
