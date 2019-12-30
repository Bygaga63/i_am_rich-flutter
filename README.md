# i_am_rich

Аналог приложения которое стоило 999$ 'I am reach'

![I am reach image](/images/diamond.webp)

## Getting Started
**lib/main.dart** Старт программы начинается с файла

Должна присутстовать функция **main**, которая вызываю функцию **runApp(Widget)**

##Settings
**pubspec.yaml**- аналоги AndroidManifest

Для картинки была создана папка **images**, и добавлена в **pubspec.yaml**
```
flutter:
  ***
  assets:
    - images/       -- все вложения в эту папку теперь можно использовать в проекте
```

####Генератора инокон IOS/Android
[link](https://appicon.co/)