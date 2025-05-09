# Flutter Counter App / Gendin Nikolay

Это простое приложение на Flutter, которое демонстрирует использование состояния (state) для управления счетчиком. Приложение позволяет пользователю увеличивать, уменьшать и сбрасывать значение счетчика.

## Описание

Приложение состоит из двух основных страниц:
- **MyApp**: Корневой виджет, который устанавливает материальный дизайн и тему приложения.
- **MyHomePage**: Основная страница, на которой отображается текущее значение счетчика и кнопки для управления им.

## Функциональность

- **Инкремент**: Увеличивает значение счетчика на 1.
- **Декремент**: Уменьшает значение счетчика на 1, если оно больше 0.
- **Сброс**: Сбрасывает значение счетчика до 0.

## Установка

1. Убедитесь, что у вас установлен [Flutter SDK](https://flutter.dev/docs/get-started/install).
2. Склонируйте репозиторий или скопируйте код в новый проект Flutter.
3. Перейдите в директорию проекта и выполните команду:
   ```sh
   flutter pub get
   ```
4. Запустите приложение на эмуляторе или физическом устройстве:
   ```sh
   flutter run
   ```

## Использование

- Запустите приложение на устройстве или эмуляторе.
- Используйте кнопки "+" и "-" для изменения значения счетчика.
- Нажмите кнопку "Сбросить", чтобы вернуть значение счетчика к 0.

## Структура проекта

- `lib/main.dart`: Основной файл, содержащий точку входа в приложение и определение виджетов `MyApp` и `MyHomePage`.

## Зависимости

Приложение использует только стандартные пакеты Flutter и Dart, поэтому дополнительные зависимости не требуются.

---

Спасибо за использование Flutter Counter App!
```
