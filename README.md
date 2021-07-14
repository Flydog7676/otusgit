# otusgit
1. Установка git на CentOs ```sudo dnf install git```
2. Проверяем что git установился и его версию
```
git --version
#git version 2.27.0
```
3. Создаем локальный репозиторий
```
mkdir git_repo
cd git_repo
git init
```
5. Вводим имя пользователя ``` git config --global user.name "otus demo" ```
6. Вводим электронную почту ``` git config --global user.email a.trubin@ulnanotech.com ```
7. Ставим текстовый редактор по умолчанию ``` git config --global core.editor nano ```
8. Создаем тестовые файлы file.txt и file1.txt ``` touch file1.txt,file.txt ```
9. 
