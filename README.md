**🗲TXT🗲**

*Задание 1. Создать внешний репозиторий c названием TXT.*

`Решение`⮯

1. Перейти по ссылке
2. Нажать "New"
3. Ввести "TXT" в поле "Repository name"
4. Выбрать "Public" и "Add a README file"
5. Нажать "Create repository"
---

*Задание 2. Клонировать репозиторий TXT на локальный компьютер.*

`Решение`⮯

1. Нажать "Code"
2. Выбрать "SSH"
3. Нажать "Скопировать ссылку на репозиторий"
4. В GitBash зайти в папку (в которой будет размещен репозиторий)
5. Клонировать репозиторий на локальный компьютер:

```bash
git clone "git@github.com:VitasQA/TXT.git"
```

6. Войти в папку "Txt":

```bash
cd Txt
```
---

*Задание 3. Внутри локального "TXT" создать файл “new.txt.*

`Решение`⮯

1. Создать файл:

```bash
touch new.txt
```

2. Посмотреть состояние файлов в рабочем каталоге и индексе:

```bash
git status
``` 
---

*Задание 4. Добавить файл под гит.*

`Решение`⮯

1. Добавить содержимое рабочего каталога в индекс для последующего коммита:

```bash
git add new.txt
```
2. Посмотреть состояние файлов в рабочем каталоге и индексе:

```bash
git status
``` 
---

*Задание 5. Закоммитить файл.*

`Решение`⮯

1. Сделать снимок текущего состояния изменений, добавленных в раздел проиндексированных файлов:

```bash
git commit -m "add file"
``` 
---

*Задание 6. Отправить файл на внешний GitHub репозиторий.*

`Решение`⮯

1. Выгрузить содержимое локального репозитория в удаленный:

```bash
git push
```
---

*Задание 7. Отредактировать содержание файла “new.txt - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT.*

`Решение`⮯

1. Открыть текстовый редактор Vim:

```bash
vim new.txt
```

2. Нажать " i "
3. Ввести информацию:

```txt
Full_name: Kruglik_Vitaliy_Iv,
Age: 32,
Pets: I don't have anyy pets,
Future_salary: 1500$
```

4. Нажать "Esc"
5. Нажать ":wq"
---

*Задание 8. Отправить изменения на внешний репозиторий.*

`Решение`⮯

```bash
git add new.txt
git commit -m "modified new file"
git push
```
---

*Задание 9. Создать файл preferences.txt.*

`Решение`⮯

```bash
cat > preferences.txt
```
---

*Задание 10. В файл preferences.txt добавить информацию о своих предпочтениях (Любимый фильм,сериал, еда, время года, страна которую хотели бы посетить) в формате TXT.*

`Решение`⮯

1. Ввести информацию:
   
```txt
favorite_film: Terminator,
favorite_series: The Last Of Us,
favorite_food: Pasta,
favorite_season: Winter,
favorite_country: Italia
```

2. Нажать "Enter"
3. Нажать "Ctrl + D"
---

*Задание 11. Создать файл sklls.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT.*

`Решение`⮯

1. Ввести:

```bash
cat > skills.txt
```

2. Ввести информацию:

```txt
Skills:
  Mobile testing,
  Postman,
  Software testing theory,
  Client-server arhitecture,
  API testing,
  Android Studio
  Python. Learning the basics
```

3. Нажать "Enter"
4. Нажать "Ctrl + D"
---

*Задание 12. Отправить сразу 2 файла на внешний репозиторий.*

`Решение`⮯

```bash
git add .

git commit -m "add file"

git push
```
---

*Задание 13. На веб интерфейсе создать файл bug_report.txt.*

`Решение`⮯

1. Зайти в репозиторий "TXT"
2. Нажать кнопку "Add file"
3. Нажать кнопку "Create new file"
4. В поле "Name your file" ввести "bug_report.txt"
---

*Задание 14. Сделать Commit changes (сохранить) изменения на веб интерфейсе.*

`Решение`⮯

1. Нажать кнопку "Commit new file"
---

*Задание 15. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT.*

`Решение`⮯

1. Открыть файл "bug_report.txt"
2. Нажать кнопку "Редактировать" 
3. Ввести информацию:

```txt
Summary: The login page crashes when attempting to enter a username with a special character.
Description: WS doesn't provide information if response contains more than 9 characters.
Actual Result: information gets.
Expected Result: information doesn't get.
Requirement Id: requirement.
Reproduced on: Win 11.
Reproducibility: always.
Workaround: no.
Steps to reproduce: 1. Navigate to the login page
                    2. Enter a username with a special character (e.g. !@#$%)
                    3. Click on the 'Login' button
                    4. Observe the page crashing
Severity: Minor
Priority: Low
```
---

*Задание 16. Сделать Commit changes (сохранить) изменения на веб интерфейсе.*

`Решение`⮯

1. Нажать кнопку "Commit changes"
---

*Задание 17. Синхронизировать внешний и локальный репозиторий TXT.*

`Решение`⮯

```bash
git pull
```
