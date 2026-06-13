# To ten sam Księżyc. Zmienia się światło

Gotowy pakiet o sposobie budowania faz Księżyca w aplikacji. Osiem faz nie
jest zestawem ośmiu niezależnych naklejek. Model korzysta z jednej malowanej
powierzchni i przesuwa po niej oświetlenie wraz ze zmianą położenia Księżyca.

- `instagram-stories/` - pięć plansz 1080 x 1920;
- `facebook-linkedin/` - dwa obrazy 1200 x 1500;
- `same-moon-moving-light.zip` - pełna paczka do publikacji;
- `linkedin-facebook-post.md` - osobne teksty dla obu kanałów;
- `preview.png` - podgląd całego zestawu;
- `manifest.json` - pochodzenie grafiki i źródła produktowe.

## Status

`ready`

## Źródła

- prawdziwy ekran pierwszej kwadry:
  `source/first-quarter-1440x900.png`
- prawdziwy ekran ostatniej kwadry:
  `source/last-quarter-1440x900.png`
- jedna tekstura i obliczane oświetlenie: `next-app/src/MoonSphere.jsx`
- ruch i obrót Księżyca: `next-app/src/MoonLab.jsx`,
  `next-app/src/moonModel.js`
- kontrakt wizualny i naukowy: `docs/agent/VISUAL_UX.md`,
  `docs/agent/SCIENCE_GAMEPLAY.md`
