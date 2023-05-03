# Лабораторна робота #2 "База знань"

Запускати наступним чином:

``` bash
python3 main.py <path-to-facts> <path-to-rules>
```

Далі програма в stdin очікує предикат у вигляді рядка, у відповідь 
вона виведе в stdout зміні для яких цей предикат виконується, приклад:

``` bash
python3 main.py resources/facts.txt resources/rules.txt
Child ?child ?parent
?child : jill_mother, ?parent : donald_grandfather
?child : joe_father, ?parent : stacy_grandmother
?child : karen_child, ?parent : joe_father
?child : sam_mother, ?parent : donald_grandfather
?child : alex_child, ?parent : joe_father
?child : karen_child, ?parent : jill_mother
?child : alex_child, ?parent : jill_mother
```

Для завершення програми введіть `exit`
