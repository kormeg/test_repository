git version
git config --global user.name 'Pasha'
git config --global user.email 'kormeg@yandex.ru'
git config -l
в корневом каталоге юзера появляется файл .gitconfig с инфой (эта инфа в последствии отображается в отчете о коммите в строке author)

1. git init инициализация репозитория в папке (.)
создается скрытая папка .git со всякой шляпой
можно создать файл .gitignore в этой же папке (этот файл указывает гиту, что из текущего и будущего содержимого папки игнорировать
[про gitignore](https://support.rdb24.com/hc/ru/articles/115000463769-%D0%9F%D1%80%D0%B0%D0%B2%D0%B8%D0%BB%D0%B0-%D1%81%D0%B8%D0%BD%D1%82%D0%B0%D0%BA%D1%81%D0%B8%D1%81%D0%B0-%D1%84%D0%B0%D0%B9%D0%BB%D0%B0-gitignore)

2. git status состояние папки на текущий момент (показаны несохраненные изменения если они есть. созданный или отредактированный - красный > add > зеленый > commit > исчезает)

3. git add file.py(txt,md,ipynb) добавление нового файла к отслеживаемым или измененного файла уже присутствующего в репозитории
git rm --cached file.txt возврат из зеленого в красное состояние.
git restore file.txt если хочешь отменить изменения в файле и вернуть к состоянию последнего коммита (из красного в исходное до редактирования)
git checkout -- file.txt - то же самое в bash работает точно
git diff --staged - отображает результат, который будет, если сейчас сделать коммит. (на зеленой стадии, после add)
4. git commit -m 'comment' фиксация измененений в файле локально
git reset --hard HEAD~3 - возвращение к предыдущей версии с уничтожением всего, что было после(локально тоже) (цифра в конце - кол-во уничтожаемых коммитов)
5. git branch ***-M*** main(master - стоит по умолчанию) выбор ветки необязательное действие
6. git remote add ***origin*** https://github.com/blabla_everything_from_address_bar.git создание ссылки на репозиторий
7. git remote отображает ссылку origin, когда она уже существует
переход в удаленку
8. git push ***-u*** origin main(master) отправка файла на удаленный репозиторий
9. git clone https://blabla_everything_from_address_bar создание клона репозитория на другом компухтере
10. git log просмотр истории изменений
git log -1 -p
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
4. ls == (get_childitem) (ls -h)hidden для powershell / ls - в строку, ll - списком (l -list), ll -a - co скрытыми. (a - all) для bash
5. pwd
6. cd .. (cd ..\..\..)
7. del (powershell)
8. notepad.exe name.py ctrl+s, ctrl+w
9. python.exe name.py ::
10. man (man mkdir or another command) мануал полный или по определенной команде ctrl+c f (powershell)
11. echo 'something' >> file.txt добавление строки в файл (>) переписывает файл так же можно создать новый файл

12 cat file.txt просмотр содержимого файла в консоли 
nano file.txt (bash)
vim file.txt  - редактор (выход из редактора c coхранением :wq) (вим на винду устанавливается отдельно)
cp file.txt folder_name/ - копирование файла в папку



blablabla
































