# LinkVideo.Helper.Updates

Публичный канал обновлений **LinkVideo.Helper**.

Этот репозиторий не содержит исходный код приложения. Здесь автоматически публикуются только проверенные релизные артефакты из приватного `WellJons/LinkVideo.Helper`:

- `update-manifest.json` — актуальная версия, URL, SHA-256 и доступные патчи;
- `LinkVideo_VPN_Helper_Setup.exe` — полный установщик;
- `LinkVideo.Helper_Patch_*.exe` — дифференциальные патчи между поддерживаемыми версиями.

`update-manifest.json` создаётся GitHub Actions при публикации нового релиза. До первого релиза файл намеренно отсутствует, чтобы LinkVideo.Helper 3.0.8 мог использовать переходный Google Drive fallback.
