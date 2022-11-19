git version
git config --global user.name 'Pasha'
git config --global user.email 'kormeg@yandex.ru'
git config -l
в корневом каталоге юзера появляется файл .gitconfig с инфой

1. git init инициализация репозитория в папке (.)
создается скрытая папка .git со всякой шляпой
2. git status состояние папки на текущий момент (показаны несохраненные изменения)
3. git add file.py(txt,md,ipynb) добавление нового файла к отслеживаемым или измененного файла
4. git commit -m 'comment' фиксация измененений в файле локально
5. git branch ***-M*** main(master - стоит по умолчанию) выбор ветки необязательное действие
6. git remote add ***origin*** https://github.com/blabla_everything_from_address_bar.git создание ссылки на репозиторий
7. git remote отображает ссылку origin, когда она уже существует
8. git push ***-u*** origin main(master) отправка файла на удаленный репозиторий
9. git clone https://blabla_everything_from_address_bar создание клона репозитория на другом компухтере
10. git log просмотр истории изменений
11. git commit --amend (esc :w q- сохранение и выход из редактора) изменяет коммент последнего коммита (этого делать не стоит в совместных проектах)
12. git pull origin master при конфликтах изменений с разных компов заливает проект с изменениями того, кто был первым второму 
13. git add . добавить всё
14. git branch отображает название ветки, в которой находишься
15. git branch name создание новой ветки это под вопросом
16. git checkout -b new_branch_name переход на отдельную ветку(вместе с созданием ее)

-M - главная ветка
origin - общепринятое название ссылки на удаленный репозииторий (название может быть любым)
-u  (set upstream) -  при следующих вызовах git push не нужно указывать репозиторий достаточно git push

___

1. mkdir name ('two words') or path 
2. cd path or name ('two words')
3. new-item name.py(txt, md, ipynb)
4. ls == (get_childitem) (ls -h)hidden
5. pwd
6. cd .. (cd ..\..\..)
7. del
8. notepad.exe name.py ctrl+s, ctrl+w
9. python.exe name.py 
10. man (man mkdir or another command) мануал полный или по определенной команде ctrl+c f



































