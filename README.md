# 🚀 INTRODUCTION

---

The `push_swap` project at 42 school plunges students into the realm of algorithmic optimization and sorting strategies within the C language.

This challenging task requires a nuanced understanding of data structures, algorithmic complexity, and efficient problem-solving. Students are tasked with developing a program that efficiently sorts a stack of numbers using a restricted set of operations, pushing the boundaries of algorithmic creativity and optimization.

Beyond the algorithmic intricacies, push_swap serves as a platform for refining skills in memory management, linked list manipulation, and the strategic orchestration of operations.

Successful completion of this project not only demonstrates mastery in algorithmic design but also showcases a keen ability to devise efficient solutions for real-world computational challenges.

![](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

# 🛠️  Program Specificities and Considerations

> [!IMPORTANT]
> The program only output the list of operations needed to sort the input stack a while ensuring compliance with the project rules.

Start with cloning my repo :
```bash
git clone git@github.com:jotudela/push_swap.git && cd push_swap
```

Then compile it with :
```bash
make
```

At the heart of the push_swap project lies a set of predefined operations that manipulate the stacks a and b.
These operations are fundamental building blocks for sorting the numbers efficiently.
Understanding these commands is crucial :
- `ra` (rotate a): Moves the first element of stack `a` to the bottom.
- `rra` (reverse rotate a): Moves the last element of stack `a` to the top.
- `rb` (rotate b): Moves the first element of stack `b` to the bottom.
- `rrb` (reverse rotate b): Moves the last element of stack `b` to the top.
- `rr` (rotate both): Simultaneously applies `ra` and `rb`.
- `rrr` (reverse rotate both): Simultaneously applies `rra` and `rrb`.
- `sa` (swap a): Swaps the first two elements of stack `a`.
- `sb` (swap b): Swaps the first two elements of stack `b`.
- `ss` (swap both): Simultaneously applies `sa` and `sb`.
- `pa` (push a): Moves the top element from stack `b` to stack `a`.
- `pb` (push b): Moves the top element from stack `a` to stack `b`.
<br>

## ⚙️ Usage

Push_swap can be executed with two differents way, for even result.

> [!WARNING]
> Invalid input (e.g., non-integer values, duplicates, inputs outside of a regular i32 limits) should result in an appropriate error message without causing undefined behavior.

Examples :
```bash
./push_swap 4 3 2 1
```

or

```bash
./push_swap "4 3 2 1"
```

So, it actualy put in your terminal :
```
rra
pb
ra
sa
pa
```

My final grade :

![](imgs/100_percent.png)

![](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

## 🤝 Contribution
Contributions are open, make a pull request or open an issue 🚀
