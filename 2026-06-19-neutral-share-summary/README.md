# Udostępnianie pokazuje tylko neutralny ślad odkryć

Gotowy pakiet o tym, że przycisk `Udostępnij neutralne podsumowanie` nie
wynosi z aplikacji imion, przewidywań ani prywatnych odpowiedzi dziecka.
Pokazuje tylko liczbę zapisanych odkryć i nazwy ukończonych tematów.

- `instagram-stories/` - pięć plansz 1080 x 1920;
- `facebook-linkedin/` - dwa obrazy 1200 x 1500;
- `neutral-share-summary.zip` - pełna paczka do publikacji;
- `linkedin-facebook-post.md` - osobne teksty dla obu kanałów;
- `preview.png` - podgląd całego zestawu;
- `manifest.json` - pochodzenie grafiki i źródła produktowe.

## Status

`ready`

## Źródła

- prawdziwy ekran panelu dorosłych na desktopie:
  `source/adult-share-desktop-1440x900.png`
- prawdziwy ekran tej samej sekcji na telefonie:
  `source/adult-share-phone-390x844.png`
- logika budowania neutralnego podsumowania:
  `next-app/src/shareSummary.js`
- logika wywołania udostępniania i komunikatów stanu:
  `next-app/src/App.jsx`,
  `next-app/src/platform.js`
- test gwarantujący brak imion i prywatnych odpowiedzi:
  `next-app/tests/product.test.mjs`
- kontrakt prywatności i lokalnego zapisu:
  `docs/agent/PRODUCT_CONTENT.md`
