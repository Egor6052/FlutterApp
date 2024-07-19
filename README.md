Test Android app with Flutter.
It was created in the terminal, not in the IDE.

INSTRUCTIONS

# Інструкція з офіціального сайту 1-3;
# 1. To develop Flutter on Linux:

which bash file mkdir rm which
/bin/bash
/usr/bin/file
/bin/mkdir
/bin/rm
which: shell built-in command


# 2.Install the following packages: curl, git, unzip, xz-utils, zip, libglu1-mesa

sudo apt-get update -y && sudo apt-get upgrade -y;
sudo apt-get install -y curl git unzip xz-utils zip libglu1-mesa

# 3.To develop Android apps:

sudo apt-get install \
    libc6:i386 libncurses5:i386 \
    libstdc++6:i386 lib32z1 \
    libbz2-1.0:i386

# на всяк випадок, якщо буде ругатися під час створення файлів
sudo apt install cmake

# створити файл
flutter create android_app

# заходимо
cd android_app

# запускаємо
flutter run

# створюємо apk файл. Шлях до файлу по автомату: build/app/outputs/flutter-apk/app-release.apk (17.6MB).
flutter build apk