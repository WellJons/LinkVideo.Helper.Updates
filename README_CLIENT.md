# Клиентский доступ

LinkVideo.Helper обращается к этому репозиторию только по публичному HTTPS:

- читает `update-manifest.json`;
- скачивает выбранный Setup или patch asset из GitHub Release;
- сверяет SHA-256 перед запуском обновления.

GitHub Personal Access Token в клиентское приложение не встраивается.
