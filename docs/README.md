# Склонировал репозиторий при помощи git clone, создал дополнительные ветки develop и feature при помощи git checkout, проверил факт появления ветвей при помощи git branch, перемещение между ветвями при помощи git switch. Полный граф истории коммитов вывел при помощи git log --graph --all --oneline . Для отката коммита первый раз использовал git rebase --soft HEAD~1 . Делал домашку два раза, не знал про ключ --hard, поэтому далее очистил индекс при помощи git stash. Объединение двух коммитов совершил при помощи git rebase -i HEAD~2, далее в текстовом редакторе заменил параметр pick на squash у более нового коммита. По какой то причине не смог сразу там же поменять текст сообщения коммита, поэтому далее использовал git commit --amend -m. Далее перешел в ветку main и оттуда создал ветку experiment при помощи git branch.  Скопировал нужные файлы при помощи git checkout <имя ветки>  <путь к файлу> . Сделал коммит. Удалил ненужные файлы при помощи git rm . Сделал финальный коммит.
# How to use calculator:
1. Run `python calculate.py`
2. Enter the figure name. Available are Circle, Square.
3. Enter the function: Area or Perimeter.
4. Enter figure sizes. Radius for circle, one side for square.
5. Get the answer!

# Math formulas
## Area
- Circle: `S = πR²`
- Rectangle: `S = ab`
- Square: `S = a²`
- Triangle: `S = sqrt(p * (p-a) * (p-b) * (p-c))` where p is semiperimeter

## Perimeter
- Circle: `P = 2πR`
- Rectangle: `P = 2a + 2b`
- Square: `P = 4a`
- Triangle: `P = a + b + c`

