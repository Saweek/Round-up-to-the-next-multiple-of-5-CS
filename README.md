# Round up to the next multiple of 5

### What we must do?
Given an integer as input, can you round it to the next (meaning, "higher") multiple of 5?

Examples:
```
input:    output:
0    ->   0
2    ->   5
3    ->   5
12   ->   15
21   ->   25
30   ->   30
-2   ->   0
-5   ->   -5
etc.
```
Input may be any positive or negative integer (including 0).

You can assume that all inputs are valid integers.

### What we did?
1. Мы создали цыкл "ПОКА", со условием, что пока данное нам число, при делении на 5 имеет остаток то мы добавляем 1 к нашему числу.
2. Возвращаем число.

#FUNDAMENTALS
