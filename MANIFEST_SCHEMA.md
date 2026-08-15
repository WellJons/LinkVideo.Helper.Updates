# update-manifest.json

Основные поля стабильного канала:

```json
{
  "version": "3.0.8",
  "download_url": "https://github.com/WellJons/LinkVideo.Helper.Updates/releases/download/v3.0.8/LinkVideo_VPN_Helper_Setup.exe",
  "sha256": "<64 hex>",
  "notes": "Доступна версия LinkVideo.Helper 3.0.8.",
  "mandatory": false,
  "patches": {
    "3.0.7": {
      "download_url": "https://github.com/WellJons/LinkVideo.Helper.Updates/releases/download/v3.0.8/LinkVideo.Helper_Patch_3.0.7_to_3.0.8.exe",
      "sha256": "<64 hex>"
    }
  }
}
```

`patches` индексируется по точной установленной версии. Если подходящего патча нет, клиент использует полный Setup.
