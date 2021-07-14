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
8. Создаем тестовый файл file.txt ``` touch file.txt ```
9. Добавляем в файл строку ``` echo "My first line in project" > file.txt ```
10. Добавляем файл для индексирования ``` git add file.txt ```
11. Добавляем в файл строку ``` echo "London is the capital of GB" > file.txt ```
12. Делаем коммит с писанием ``` git commit -m "Capital added" ```
13. Создаем второй файл,индексируем его и делаем коммит
```
touch file1.txt
git add file1.txt
git commit -m "first commit"
```
14. Для удаленного сохранения необходимо создать ключи ssh ``` ssh-keygen ```
15. Появившийся открытый ключи в  ```~/.ssh/``` копируем в созданный репозиторий на githab Settings->SSH and GPG key
16. В созданном репозитории github копируем ссылку доступа по SSH ``git@github.com:Flydog7676/otusgit.git```
17. Создаем удаленный репозитарий ``` git remote add origin git@github.com:Flydog7676/otusgit.git ```
18. И выкладываем на удаленный репозитарий ``` git push -u origin master ```
19. Клонируем имеющийся репозитарий к себе, выйдя из уже индексированного каталога
```
cd ..
git clone git@github.com:eficode-academy/git-katas.git
