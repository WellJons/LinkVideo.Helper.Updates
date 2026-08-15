# Publishing gate

Новый публичный manifest и Release должны появляться только после ручной публикации проверенного Release в приватном `WellJons/LinkVideo.Helper`.

Workflow в source-репозитории использует secret `UPDATES_REPO_TOKEN`, ограниченный этим публичным репозиторием и правом `Contents: Read and write`.
