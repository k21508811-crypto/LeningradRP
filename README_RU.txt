ЛЕНИНГРАД RP — проект Android APK

СБОРКА БЕЗ КОМПЬЮТЕРА (через GitHub):
1. Создай аккаунт на github.com и войди в него с телефона.
2. Нажми New repository, назови репозиторий LeningradRP, выбери Public или Private, затем Create repository.
3. Загрузи содержимое этого архива в корень репозитория (не сам ZIP): Add file -> Upload files.
4. Нажми Commit changes.
5. Открой вкладку Actions. Если появится запрос, разреши GitHub Actions.
6. Выбери workflow "Build Ленинград RP APK" -> Run workflow.
7. Дождись зелёной галочки. Открой завершённый запуск, внизу раздел Artifacts, скачай LeningradRP-APK.
8. Распакуй скачанный архив и установи app-debug.apk на Android. При запросе разреши установку из этого источника.

ПРИМЕЧАНИЯ:
- Сборка выполняется на облачных runner-ах GitHub Actions; свой сервер не нужен.
- Для аккаунта GitHub требуется регистрация.
- Это debug APK для тестирования и личной установки, не подписанный релиз для Google Play.
- Кнопка ИГРАТЬ открывает Roblox experience с place ID 86706967486022.
- Roblox должен быть установлен; если нет, Android предложит открыть ссылку в браузере/установить Roblox.
