# Misja dla dwojga zaczyna się od załogi

Gotowy pakiet o prawdziwym flow, który otwiera się po wybraniu bonusowej misji
`Ratunek i wyścig po orbicie` z mapy misji. Zamiast od razu wrzucać dziecko do
wspólnej gry, aplikacja najpierw pyta, czy odkrywamy samemu czy razem, a potem
pozwala zostawić neutralne nazwy albo wpisać własne. Dopiero potem otwiera
wspólny ekran orbitalny na jednym urządzeniu.

- `instagram-stories/` - pięć plansz 1080 x 1920;
- `facebook-linkedin/` - dwa obrazy 1200 x 1500;
- `crew-setup-before-shared-mission.zip` - pełna paczka do publikacji;
- `linkedin-facebook-post.md` - osobne teksty dla obu kanałów;
- `preview.png` - podgląd całego zestawu;
- `manifest.json` - pochodzenie grafiki i źródła.

## Status

`ready`

## Źródła

- prawdziwy ekran mapy misji z widoczną kartą `Ratunek i wyścig po orbicie`:
  `source/mission-home-duo-card-1440x900.png`
- prawdziwy ekran wyboru `Odkrywam sam` albo `Gramy we dwoje`:
  `source/crew-setup-choice-1440x900.png`
- prawdziwy ekran z opcjonalnymi nazwami graczy:
  `source/crew-setup-names-1440x900.png`
- prawdziwy ekran wspólnego laboratorium orbitalnego na telefonie
  (na grafice pokazany wariant `Misja załogi`):
  `source/crew-mission-phone-390x844.png`
- logika wejścia do bonusowej misji dla dwojga, kroki setupu i zapis lokalnych
  nazw:
  `next-app/src/App.jsx`,
  `next-app/src/playerSetupFlow.js`,
  `next-app/src/bonusMissions.js`
- logika wspólnej misji orbitalnej po zakończeniu setupu:
  `next-app/src/RaceGame.jsx`,
  `docs/agent/PRODUCT_CONTENT.md`,
  `docs/agent/VISUAL_UX.md`
- źródła naukowe dla kontekstu orbity:
  NASA: What Is an Orbit? (Grades 5-8),
  NASA Science: Basics of Space Flight — Gravity & Mechanics
