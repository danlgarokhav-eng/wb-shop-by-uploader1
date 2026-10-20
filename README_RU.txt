WB SHOP BY Uploader — сайт для TikTok Developers
===================================================

Сайт подготовлен для аккаунта GitHub: danlgarokhav-eng
Рекомендуемое название репозитория: wb-shop-by-uploader

ЧТО ВНУТРИ:
  index.html      — главная страница / Web/Desktop URL
  terms.html      — условия использования / Terms of Service URL
  privacy.html    — политика конфиденциальности / Privacy Policy URL
  styles.css      — оформление, адаптация под мобильные устройства
  assets/         — логотип и реальный скриншот Creator Studio
  .nojekyll       — отключает Jekyll, полезно для URL verification TikTok

КАК ОПУБЛИКОВАТЬ:
1. Открой https://github.com/new
2. Repository name: wb-shop-by-uploader; Visibility: Public.
3. Создай репозиторий.
4. Открой Add file -> Upload files.
5. Загрузи СОДЕРЖИМОЕ этой папки (а не сам ZIP). Файлы index.html, terms.html,
   privacy.html, styles.css должны лежать прямо в корне репозитория.
   Также сохрани папку assets и файл .nojekyll.
6. Сделай Commit changes.
7. Перейди Settings -> Pages -> Build and deployment -> Source: Deploy from a branch
   -> Branch: main -> Folder: /(root) -> Save.
8. Подожди, пока появится публикация (обычно несколько минут).
9. Открой в браузере все три адреса и проверь, что они возвращают сайт:
   https://danlgarokhav-eng.github.io/wb-shop-by-uploader/
   https://danlgarokhav-eng.github.io/wb-shop-by-uploader/terms.html
   https://danlgarokhav-eng.github.io/wb-shop-by-uploader/privacy.html
10. Только ПОСЛЕ проверки адресов вставляй их в TikTok Developers.

ПОДТВЕРЖДЕНИЕ ДОМЕНА В TIKTOK:
Открой URL properties -> Verify properties -> URL prefix (НЕ Domain, потому что
домен github.io тебе не принадлежит целиком). Получи verification file от TikTok,
загрузи его в нужный путь репозитория и убедись, что файл доступен по HTTPS.
Если требует .well-known, соблюдай точный путь и название.

ВАЖНО ПЕРЕД МОДЕРАЦИЕЙ:
- Главная и legal страницы подготовлены как стартовый черновик. Проверь,
  соответствуют ли они фактическим способам сбора/хранения данных твоего ПО.
- В Privacy Policy сейчас указан GitHub-профиль в качестве контакта. Для подачи
  на модерацию лучше добавить реальный адрес поддержки (email), не секретный.
- Не загружай в публичный репозиторий .env, client_secret.json, token.json,
  instagram_token.json, tiktok_token.json, ключи и другие файлы бота.
- TikTok не гарантирует одобрение личных одноразовых автопостеров:
  требуются работающая интеграция, видео-демо из Sandbox, соответствие правилам.
- Сайт — информационный. Он НЕ подключает TikTok OAuth, не загружает MP4.

Для проверки в Windows открой index.html двойным щелчком.
