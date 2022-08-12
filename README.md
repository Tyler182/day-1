# День 1

### Задание 1. Интерфейс

Реализован пользовательский интерфейс экрана авторизации.

<p align="center">
<img src="./docs/assets/day1/auth-loading.png" width="400" alt="" />
</p>

### Задание 2. Логика

Реализована логика авторизации, перехода на экран чата в случае успешной авторизации.

<p align="center">
<img src="./docs/assets/day1/chat-screen.png" width="400" alt="" />
</p>

Реализовано сохранение токена с использованием shared_preferences.

var prefs = await SharedPreferences.getInstance();

await prefs.setString('token', token.token);

### Задание 3. Снекбар

Реализовано отображение SnackBar при ошибке.

<p align="center">
<img src="./docs/assets/day1/auth-error.png" width="400" alt="" />
</p>

## Чат. Рефакторинг

### Задание 1. Сообщение геолокации

Реализовано отображение `ChatMessageGeolocationDto`.

<p align="center">
<img src="./docs/assets/day1/chat-message-geo-location-dto.png" width="400" alt="" />
</p>

### Задание 3. Отправка геолокации 🔥

Реализована отправка координат в сообщение с использованием geolocator.

<p align="center">
<img src="./docs/assets/day1/chat-message-geo-location-dto.png" width="400" alt="" />
</p>
