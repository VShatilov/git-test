# git-test

git log

git status
(сравнивает комп с онлайн)

git add song.txt
(копирует мой новый файл в онлайн)

git commit -m "comment_text"
(добавляет коммент)

git push
(кидает изменения в онлайн)

git pull
(сразу делает git fetch & git merge: тянет на комп изменения из онлайн)

git gui&
(открывает UI в новом окне)

gitk&
(открывает UI с историей коммитов в новом окне)

git show -s --pretty=row 2c972
(покажет коммент и tree)

git ls-tree 98ca1e504
(покажет файлы)

git show d96d00
(покажет содержимое файла)

git restore -- README.md
(откатит изменения ЛОК файла)

git restore .
(откатит ЛОК изменения в файлах папки и вложенных в неё, но не удалит новые файлы)

git clean -xdf
(удалит новые ЛОК файлы.
x:игнорить правила
d:удалить и папки тоже
f:force принудительно, без f не удалит ничего)

git reset -- song.txt
или
git restore -- staged song.txt
(вернёт файл из IND в ЛОК а оттуда можно git restore)

git commit --amend -m"add text to commit"
(ЗАМЕНИТ текст последнего коммита)

 git reset HEAD^^
 или
 git reset HEAD~2
 (удалит 2 последних коммита)