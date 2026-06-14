# 67 nagrań jest częścią aplikacji

Gotowy techniczny pakiet o tym, co dzieje się po kliknięciu „Posłuchaj”.
Aktualny build zawiera 67 gotowych nagrań AI. Aplikacja odtwarza je jako
statyczne pliki audio i nie wysyła tekstu do zewnętrznej usługi podczas
odsłuchu. Lokalny polski głos systemowy jest używany tylko wtedy, gdy
konkretnego nagrania brakuje.

- `instagram-stories/` - pięć plansz 1080 x 1920;
- `facebook-linkedin/` - dwa obrazy 1200 x 1500;
- `voice-stays-local.zip` - pełna paczka do publikacji;
- `linkedin-facebook-post.md` - osobne teksty dla obu kanałów;
- `preview.png` - podgląd całego zestawu;
- `manifest.json` - pochodzenie grafiki i źródła produktowe.

## Status

`ready`

## Źródła

- prawdziwy ekran ustawień:
  `source/narration-settings-1440x900.png`;
- odtwarzanie i głos awaryjny: `next-app/src/voicePlayer.js`;
- lista 67 nagrań: `next-app/src/voice-manifest.json`;
- stan produktu i kierunek ludzkiej narracji:
  `docs/agent/PRODUCT_CONTENT.md`;
- ustawienia narracji: `next-app/src/App.jsx`.
