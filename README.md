<p align="center">
  <a href="https://nodejs.org/">
    <img
      alt="Node.js"
      src="https://nodejs.org/static/images/logo-light.svg"
      width="400"
    />
  </a>
</p>

# Описание
Бот предназначен для игрового бота ВК - World of Clans

# Настройки
* Получение токена (token):

Откройте [эту](https://oauth.vk.com/authorize?client_id=6378721&scope=1073737727&redirect_uri=https://api.vk.com/blank.html&display=page&response_type=token&revoke=1) ссылку и нажмите разрешить

После этого в адресной строке будет подобное: **https://api.vk.com/blank.html#access_token=xxxxxxxxxxxx&expires_in=0&user_id=user_id&email=email**

Токеном будет являться строка от **access_token** до **&expires**. В этом случае **xxxxxxxxxxxx**

В настройках нужно указать Ваш токен и токен от RuCapcha (config.js):
```console
token: `токен страницы`, // string
ru_key: `RuCapcha token`, // string
```
