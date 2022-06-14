# Инструкция по работе с **Git**
Git - программа для контроля версий

Программа Git берёт на себя контроль версий.
проекта и позволяет переключаться между
ними. Обратите внимание: Git хранит не файлы целиком, а отличия между ними.

<span style="color:green">**Основные команды Git:**</span>


Осваивать Git проще процессе редактирования текстовых файлов. Markdown – язык разметки,
который позволяет форматировать текст. Для написания в редакторе VS Code используется
синтаксис языка.

Все команды задаём при помощи написания кода в терминале.
Прежде чем создавать репозиторий и инициализировать Git, проверим текущую установленную
версию пограммы. Для этого в терминале введём команду:

>git --version

>![Doc.U.Ment](Images/Git_version.png)



*Если Git установлен на компьютер, вы увидите его текущую версию.
Программа использует мнемонические команды, которые легко запомнить, если знать
английский язык.*

>git init – инициализация локального репозитория
![Doc.U.Ment](Images/git_init.png)

>git status – получить информацию от git о его текущем состоянии
![Doc.U.Ment](Images/git_status.png)

>git add – добавить файл или файлы к следующему коммиту
![Doc.U.Ment](Images/git_add.png)

>git commit -m “message” – создание коммита.
![Doc.U.Ment](Images/git_commit.png)

>git log – вывод на экран истории всех коммитов с их хеш-кодами
![Doc.U.Ment](Images/git_log.png)

>git checkout – переход от одного коммита к другому
![Doc.U.Ment](Images/git_checkout.png)

>git checkout master – вернуться к актуальному состоянию и продолжить работу
![Doc.U.Ment](Images/git_checkout_main.png)

>git diff – увидеть разницу между текущим файлом и закоммиченным файлом
![Doc.U.Ment](Images/git_diff.png)

>git branch <название ветки> – создать новую ветку  
![Doc.U.Ment](Images/git_branch_name.png)

>git branch – посмотреть список веток в репозитории
![Doc.U.Ment](Images/git_branch.png)

>git branch -d <название ветки> – удалить ветку
![Doc.U.Ment](Images/git_branch_d.png)

>git log --graph  – журнал коммитов с визуализацией
![Doc.U.Ment](Images/git_log_graph.png)

>git commit -a -m “текст_коммита”  –  создание изменения и его коммит
![Doc.U.Ment](Images/git_commit_am.png)
