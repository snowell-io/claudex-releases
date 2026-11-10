# Claudex Alpha для macOS

Нативное приложение для работы с Claude Code: чаты, отдельные Git worktree,
терминал и просмотр изменений в одном окне.

**[Скачать Claudex для Mac с Apple Silicon](https://github.com/snowell-io/claudex-releases/releases/download/v0.1.0-alpha.1/Claudex-0.1.0-alpha.1-arm64.zip)**

Требования: Mac с Apple Silicon (M1 и новее), macOS 13 или новее,
установленный Claude Code с выполненным входом в аккаунт.
Аккаунт GitHub и Homebrew для скачивания и установки Claudex не нужны.

## Установка

1. Скачайте ZIP по ссылке выше и распакуйте его двойным щелчком.
2. Перенесите **Claudex.app** в папку **Программы / Applications**.
3. Откройте Claudex из папки Applications.

У этой альфы пока нет Developer ID и нотариализации Apple. Если macOS
заблокирует запуск, после попытки открытия перейдите в
**Системные настройки → Конфиденциальность и безопасность → Всё равно открыть
(Open Anyway)** и подтвердите запуск.
[Инструкция Apple](https://support.apple.com/en-us/102445).
После обновления это разрешение может потребоваться снова.

Claude Code нужно установить отдельно и авторизовать командой
`claude auth login`. Инструкция — в
[официальной документации Claude Code](https://code.claude.com/docs/en/setup).

## Обновление

Перед заменой приложения выберите в меню Claudex **Stop All Work and Quit**.
Обычный Quit оставляет фоновую работу запущенной.
С остановленным фоновым помощником сохраните резервную копию
`~/Library/Application Support/ClaudexAlpha` и предыдущую версию приложения.
Затем скачайте новый ZIP и замените Claudex.app в Applications.

[Все версии и контрольные суммы](https://github.com/snowell-io/claudex-releases/releases).

Этот репозиторий содержит установочные архивы и инструкции.
