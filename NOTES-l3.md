## Варіант
Журнал 33, варіант 3, прізвище Tonkova

## 1. stash list
stash@{0}: On lab3/variant-3-Tonkova: чернетка конфігурації v3
Рядок успішно збережено у сховищі.

## 2. cherry-pick
Старий хеш: 990421d 
Новий хеш: 1812acd
Хеші різні, тому що cherry-pick не просто переносить коміт, а створює його нову копію (патч) з новими метаданими.

## 3. reflog
6d4d9b3 (HEAD -> lab3/variant-3-Tonkova) HEAD@{0}: commit (amend): Уточнити тему звіту, варіант 3
1812acd HEAD@{1}: cherry-pick: Оновити тему звіту

## 4. revert
46a3b51 (HEAD -> lab3/variant-3-Tonkova, origin/lab3/variant-3-Tonkova) Revert "Зіпсувати рядок"
a99c149 Зіпсувати рядок
6d4d9b3 Уточнити тему звіту, варіант 3

## 5. тег
tag v0.1-Tonkova
Tagger: Tonkova Oleksandra <dusirde@gmail.com>
Перший зріз варіанта 3

## 6. rebase -i
Під час rebase у першому рядку залишено `pick`, у другому `pick` замінено на `squash`. Підсумкове повідомлення для склеєного коміту: "Оновити тему звіту".

## 7. blame
24bf64bf (Tonkova Oleksandra 2026-11-10 18:35:56 +0100 5) WIP1

## 8. fork
origin — це мій особистий репозиторій-форк, upstream — оригінальний репозиторій викладача. Зміни (оновлення) затягуються командою fetch upstream. Свої коміти відправляємо командою push у свій origin. Здача роботи відбувається через створення Pull Request з мого origin у гілку upstream/main.