
## **🔹 1. Основные команды терминала**  

**pwd** - показывает полный путь к текущей папке.   - echo %cd%

**ls -la** - отображает список всех файлов в папке, включая скрытые.  - dir

**cd название_папки** - переход в указанную папку.  

**mkdir название_папки** - создание новой папки.  

**touch file.txt** - создание пустого файла. - echo $null >> file.txt

**rm file.txt** - удаление файла.  

**rm -rf название_папки** - удаление папки вместе с файлами внутри.  

**cat file.txt** - вывод содержимого файла в терминал.  - type file

**clear** - очистка экрана терминала.  

---

## **🔹 2. Начало работы с Git**  

**git --version** - проверка установленной версии Git.  

**git init** - инициализация репозитория Git в текущей папке.  

**git clone URL** - клонирование удаленного репозитория в локальную папку.  

---

## **🔹 3. Работа с файлами в Git**  

**git status** - проверка состояния репозитория (какие файлы изменены, какие не отслеживаются).  

**git add file.txt** - добавление файла в индекс (подготовка к коммиту).  

**git add .** - добавление всех измененных файлов в индекс.  

**git reset file.txt** - удаление файла из индекса, но без удаления его с диска.  

**git rm file.txt** - удаление файла и фиксация этого изменения в Git.  

**git rm --cached file.txt** - удаление файла из Git, но оставление его на диске.  

---

## **🔹 4. Коммиты**  

**git commit -m "Сообщение"** - создание коммита с указанным сообщением.  

**git commit --amend** - изменение последнего коммита (например, исправление сообщения).  

**git log** - просмотр истории коммитов.  

**git log --oneline --graph** - краткая история коммитов в виде графа.  

---

## **🔹 5. Работа с удаленными репозиториями**  

**git remote -v** - проверка списка удаленных репозиториев.  

**git remote add origin URL** - добавление удаленного репозитория.  

**git push -u origin main** - отправка изменений в удаленный репозиторий.  

**git pull origin main** - получение изменений из удаленного репозитория.  

**git push origin --delete branch_name** - удаление удаленной ветки.  

---

## **🔹 6. Работа с ветками**  

**git branch** - просмотр списка веток.  

**git branch feature-branch** - создание новой ветки.  

**git switch feature-branch** - переключение на другую ветку.  

**git branch -d feature-branch** - удаление ветки (если изменения уже влиты).  

**git branch -D feature-branch** - принудительное удаление ветки.  

---

## **🔹 7. Слияние и перебазирование**  

**git merge feature-branch** - слияние указанной ветки с текущей.  

**git rebase main** - перебазирование текущей ветки на `main`.  

**git cherry-pick commit_hash** - выборочное применение коммита в текущую ветку.  

---

## **🔹 8. Откат изменений**  

**git reset --soft HEAD~1** - отмена последнего коммита, но сохранение изменений.  

**git reset --mixed HEAD~1** - отмена последнего коммита и удаление файлов из индекса.  

**git reset --hard HEAD~1** - полная отмена последнего коммита и удаление изменений.  

**git revert commit_hash** - создание нового коммита, который отменяет указанный коммит.  

**git stash** - временное сохранение изменений без коммита.  

**git stash pop** - восстановление изменений, сохраненных `stash`.  

---

## **🔹 9. Работа с GitHub**  

**git push origin main** - отправка локальных изменений в удаленный репозиторий.  

**git pull origin main** - загрузка последних изменений из удаленного репозитория.  

**git fetch origin** - получение изменений без их автоматического объединения.  

**git push --force** - принудительное обновление удаленной ветки (⚠️ осторожно, может удалить чужие изменения).  

---

🔥 **Теперь у вас есть четкая шпаргалка по основным командам Git и терминала! 🚀**