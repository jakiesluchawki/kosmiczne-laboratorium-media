# Głos, który robi miejsce na odkrycie

Gotowy pakiet o narracji w aplikacji: krótki głos pomaga wejść w zadanie,
ale nie opisuje każdego ruchu. Odsłuch jest wyborem, tekst pozostaje widoczny,
a aktualna wersja korzysta głównie z gotowych nagrań AI zapisanych w aplikacji.
Lokalny polski głos systemowy uruchamia się tylko wtedy, gdy konkretnego
nagrania brakuje. Obie wersje są przejściowe przed nagraniem jednej ludzkiej
narratorki.

- `instagram-stories/` - pięć plansz 1080 x 1920;
- `facebook-linkedin/` - dwa obrazy 1200 x 1500;
- `voice-makes-room.zip` - pełna paczka do publikacji;
- `linkedin-facebook-post.md` - osobne teksty dla obu kanałów;
- `preview.png` - podgląd całego zestawu;
- `manifest.json` - pochodzenie grafiki i źródła produktowe.

## Status

`ready`

## Źródła

- prawdziwy ekran ustawień: `source/narration-settings-1440x900.png`
- zachowanie narracji: `next-app/src/voicePlayer.js`,
  `next-app/src/voice-manifest.json`, `next-app/src/App.jsx`
- kontrakt treści i dostępności: `docs/agent/PRODUCT_CONTENT.md`
