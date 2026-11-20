HEX FALL 3D — Android-приложение (APK)

Способ 1 (без Android Studio, бесплатно, ~5 минут):
 1. Зарегистрируйтесь на github.com и создайте новый репозиторий.
 2. Загрузите в него ВСЁ содержимое этой папки (кнопка "Add file → Upload files",
    включая скрытую папку .github).
 3. Откройте вкладку Actions → "Build APK" → дождитесь зелёной галочки.
 4. Внутри запуска скачайте артефакт "HexFall-apk" (zip), распакуйте — там app-debug.apk.
 5. Перекиньте apk на телефон, откройте и разрешите установку из неизвестных источников.

Способ 2 (Android Studio): File → Open → эта папка → Build → Build APK(s).

Иконка: app/src/main/res/mipmap-*; большая версия 512x512 — icon_512.png.
Игра лежит в app/src/main/assets/index.html (работает без интернета).
