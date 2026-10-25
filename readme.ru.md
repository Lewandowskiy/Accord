[English](README.md) | Русский

# Accord

Локальный музыкальный плеер для Android с дизайном в стиле Apple. Поддерживает синхронизированные тексты песен (LRC/SRT), воспроизведение без пауз между треками и сторонние эквалайзеры.

Форк [Accord](https://github.com/v3ndable/Accord) (который, в свою очередь, является форком проекта [@v3ndable](https://github.com/v3ndable)), содержащий небольшие обновления и исправления.

## Скриншоты

<p>
  <img src="fastlane/metadata/android/en-US/images/phoneScreenshots/Home.jpg" width="220" />
  <img src="fastlane/metadata/android/en-US/images/phoneScreenshots/Browse.jpg" width="220" />
  <img src="fastlane/metadata/android/en-US/images/phoneScreenshots/Library.jpg" width="220" />
</p>
<p>
  <img src="fastlane/metadata/android/en-US/images/phoneScreenshots/Search.jpg" width="220" />
  <img src="fastlane/metadata/android/en-US/images/phoneScreenshots/Player.jpg" width="220" />
  <img src="fastlane/metadata/android/en-US/images/phoneScreenshots/Lyrics.png" width="220" />
</p>

## Установка

Скачать оригинальный Accord (от [@emylfy](https://github.com/emylfy), который больше не поддерживается) можно тут [GitHub Releases](https://github.com/emylfy/Accord/releases/latest).

## Требуемая настройка

Перед сборкой проекта необходимо создать файл `package.properties` в корневом каталоге:

```bash
$ touch package.properties
```

Затем добавьте в него следующее содержимое:

```properties
releaseType=SelfBuilt
```

Это необходимо, чтобы Gradle правильно определил тип сборки и разрешил компиляцию проекта.

## Сборка

```bash
git clone https://github.com/Lewandowskiy/Accord.git
cd Accord
./gradlew assembleRelease
```

Готовый APK будет находиться в каталоге `app/build/outputs/apk/release/`.

> <sub><small>Не забудьте потом подписать релизную сборку.</small></sub>

## Благодарности

Проект основан на форке [@v3ndable](https://github.com/v3ndable), который, в свою очередь, является форком [Accord](https://github.com/emylfy/Accord) от [@emylfy](https://github.com/emylfy), который основан на проектах [Gramophone](https://github.com/AkaneTan/Gramophone) и [AccordLegacy](https://github.com/FoedusProgramme/AccordLegacy).

Первоначальные разработчики: [@AkaneTan](https://github.com/AkaneTan), [@lightsummer233](https://github.com/lightsummer233), [@123Duo3](https://github.com/123Duo3).

Форк поддерживается [@Lewandowskiy](https://github.com/Lewandowskiy).

## Лицензия

Проект по-прежнему распространяется под лицензией GNU General Public License v3.0.

GPL-3.0 — подробности см. в файле [LICENSE](LICENSE).
