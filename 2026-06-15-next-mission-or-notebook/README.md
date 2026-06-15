# Zapis prowadzi do następnej misji albo do zeszytu

Gotowy pakiet o tym, co dzieje się po zapisaniu odkrycia. Pokazuje prawdziwy
flow aplikacji: po trzecim zapisanym odkryciu pojawia się kolejna misja `4 z 6`,
a po pełnej ścieżce `6 z 6` ten sam obszar prowadzi do zeszytu odkryć zamiast
kończyć zabawę pustym ekranem.

- `instagram-stories/` - pięć plansz 1080 x 1920;
- `facebook-linkedin/` - dwa obrazy 1200 x 1500;
- `next-mission-or-notebook.zip` - pełna paczka do publikacji;
- `linkedin-facebook-post.md` - osobne teksty dla obu kanałów;
- `preview.png` - podgląd całego zestawu;
- `manifest.json` - pochodzenie grafiki i źródła produktowe.

## Status

`ready`

## Źródła

- prawdziwa mapa po trzech odkryciach:
  `source/mission-home-next-1440x900.png`
- prawdziwe podsumowanie po zapisie orbity:
  `source/completion-next-1440x900.png`
- prawdziwy handoff do zeszytu po `6 z 6`:
  `source/mission-home-notebook-handoff-1440x900.png`
- logika prowadzenia dalszej drogi:
  `next-app/src/missionProgress.js`, `next-app/src/App.jsx`,
  `docs/agent/PRODUCT_CONTENT.md`, `next-app/README.md`
