# Można zacząć odkrycia od początku

Gotowy pakiet o świadomym wyczyszczeniu lokalnego postępu. Strefa dorosłych
otwiera się po przytrzymaniu przycisku przez 2,5 sekundy, a sam reset wymaga
osobnego potwierdzenia. Po usunięciu licznik odkryć wraca z 6/6 do 0/6.

- `instagram-stories/` - pięć plansz 1080 x 1920;
- `facebook-linkedin/` - dwa obrazy 1200 x 1500;
- `local-reset-starts-over.zip` - pełna paczka do publikacji;
- `linkedin-facebook-post.md` - osobne teksty dla obu kanałów;
- `preview.png` - podgląd całego zestawu;
- `manifest.json` - pochodzenie grafiki i źródła produktowe.

## Status

`ready`

## Źródła

- prawdziwy ekran zabezpieczonej strefy dorosłych:
  `source/adult-gate-1440x900.png`
- prawdziwe ekrany potwierdzenia i zakończonego resetu:
  `source/reset-confirmation-1440x900.png`,
  `source/reset-complete-1440x900.png`
- logika lokalnego postępu i resetu: `next-app/src/App.jsx`
- zasady prywatności i postępu: `docs/agent/PRODUCT_CONTENT.md`
