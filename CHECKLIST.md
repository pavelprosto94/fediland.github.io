# Чеклист для нового сервера

Перед тем как создавать пуллреквест для добавления вашего сервера, проверьте соответствие следующему чеклисту.

- [ ] Сервер уже существует хотя бы несколько месяцев
- [ ] Вы уверены, что не решите прекратить поддержку вашего сервера в ближайшие годы
- [ ] Вы уверены, что вы как администратор способны непредвзято относиться к пользователям и ваше с ними несогласие или личные обиды не повлияют на использование вашего сервиса
- [ ] У вашего сервера есть чёткий и понятный свод правил
  - Это не значит, что обязательно должно быть много запрещающих пунктов
  - Это также не значит, что достаточно только упоминания "здравого смысла" или "усмотрения администрации"
  - Пользователь должен иметь возможность легко понять какие его действия могут привести к санкциям со стороны администрации
- Бекапы:
  - [ ] Настроены и автоматически делаются для:
    - [ ] Базы данных
    - [ ] Файлов платформы и её конфигурации
    - [ ] Загружаемых пользователями медиафайлов
  - [ ] Хранятся как минимум не на том же сервере
- [ ] Вы планируете регулярно и оперативно обновлять используемую вами платформу (Mastodon/Pleroma/Misskey/etc)
- [ ] HTTPS
  - [ ] Включён и [корректно настроен](https://ssl-config.mozilla.org)
  - [ ] Включён [HSTS](https://ru.wikipedia.org/wiki/HSTS)
  - [ ] Сертификаты перевыпускаются автоматически и вы это проверяли ([Certbot](https://certbot.eff.org), [acme.sh](https://github.com/acmesh-official/acme.sh), [lego](https://github.com/go-acme/lego), etc)