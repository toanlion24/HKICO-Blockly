# BLOCKLY PROGRAMMING - ADVANCED QUIZ
## 20 Difficult Multiple Choice Questions

**Name:** _________________________________ **Date:** _____________

**Instructions:** Choose the best answer for each question. Circle your answer (A, B, C, D, or E).

---

### **THEORY QUESTIONS (30%)**

---

**Question 1: Block Connections**

In Blockly, what is the fundamental difference between a "statement connection" and a "value connection"?

A) Statement connections are horizontal; value connections are vertical  
B) Statement connections stack blocks vertically and execute sequentially; value connections pass data horizontally between blocks  
C) Statement connections only work with loops; value connections only work with variables  
D) Statement connections are colored blue; value connections are colored green  
E) There is no difference; they are interchangeable terms  

---

**Question 2: Block Categories**

Which statement accurately describes the relationship between Blockly's "mutator" feature and block functionality?

A) Mutators allow blocks to change color dynamically during execution  
B) Mutators enable blocks to modify their shape and inputs at edit-time, such as adding more else-if clauses to an if block  
C) Mutators are used exclusively for mathematical operations  
D) Mutators convert text blocks into number blocks automatically  
E) Mutators are deprecated and no longer supported in modern Blockly  

---

**Question 3: Code Generation**

In Blockly's architecture, what is the primary role of "generators" in the code production pipeline?

A) Generators create new visual blocks from templates  
B) Generators translate the visual block workspace into executable code in a target programming language  
C) Generators produce random numbers for mathematical blocks  
D) Generators automatically save workspace state to local storage  
E) Generators handle user input validation exclusively  

---

**Question 4: Workspace Concepts**

What happens when a block is placed in Blockly's "flyout" area versus the main workspace?

A) Blocks in the flyout execute immediately; blocks in workspace wait for user action  
B) Flyout blocks are templates that create copies when dragged to workspace; workspace blocks are the actual program elements  
C) Flyout blocks run faster than workspace blocks  
D) There is no functional difference between the two areas  
E) Flyout blocks can only contain variables; workspace blocks can contain any type  

---

**Question 5: Shadow Blocks**

What is the primary purpose of "shadow blocks" in Blockly?

A) They make blocks invisible during execution  
B) They provide default values that can be replaced by other blocks but reappear when the replacement is removed  
C) They create duplicate copies of blocks automatically  
D) They are used only for debugging purposes  
E) They prevent blocks from being deleted  

---

**Question 6: Block Definitions**

In Blockly's JSON block definition, what does the "inputsInline" property control?

A) Whether the block accepts keyboard input  
B) Whether multiple value inputs are arranged horizontally (inline) or vertically (external)  
C) The speed at which blocks execute  
D) Whether the block can be copied  
E) The font size of text within the block  

---

### **APPLICATION QUESTIONS (70%)**

---

**Question 7: Variable Operations**

Analyze the following Blockly pseudocode:

```
set [score] to [0]
set [bonus] to [10]
change [score] by [bonus]
change [score] by [bonus * 2]
```

What is the final value of `score`?

A) 10  
B) 20  
C) 30  
D) 40  
E) 0  

---

**Question 8: Nested Loops**

Examine this Blockly loop structure:

```
set [result] to [0]

repeat [3] times
    repeat [4] times
        change [result] by [1]
```

What is the final value of `result`?

A) 3  
B) 4  
C) 7  
D) 12  
E) 16  

---

**Question 9: Conditional Logic**

Given the following Blockly code:

```
set [x] to [15]
set [y] to [20]
set [output] to ["none"]

if <[x] > [10]> and <[y] < [25]> then
    set [output] to ["both"]
else if <[x] > [10]> then
    set [output] to ["first"]
else if <[y] < [25]> then
    set [output] to ["second"]
```

What is the value of `output`?

A) "none"  
B) "both"  
C) "first"  
D) "second"  
E) Error: undefined  

---

**Question 10: List Operations**

Analyze this Blockly list manipulation:

```
set [myList] to [create list with: 5, 10, 15, 20, 25]
set [sum] to [0]

for each [item] in list [myList]
    if <[item] mod [10]> = [0] then
        change [sum] by [item]
```

What is the final value of `sum`?

A) 15  
B) 30  
C) 50  
D) 75  
E) 25  

---

**Question 11: String Manipulation**

Examine the following Blockly text operations:

```
set [text] to ["BLOCKLY"]
set [result] to [""]

for [i] from [1] to [length of [text]] by [2]
    set [result] to [join [result] [letter [i] in [text]]]
```

What is the value of `result`?

A) "BLCY"  
B) "LOKL"  
C) "BOKY"  
D) "BLKY"  
E) "LCLY"  

---

**Question 12: Mathematical Functions**

Given this Blockly calculation:

```
set [a] to [round [√ of [144]]]
set [b] to [abs of [-8]]
set [c] to [[a] ^ [2]]
set [result] to [[c] - [b] + [a]]
```

What is the value of `result`?

A) 148  
B) 156  
C) 160  
D) 152  
E) 140  

---

**Question 13: Complex Conditionals**

Analyze this Blockly logic:

```
set [grade] to [75]
set [attendance] to [true]
set [result] to ["F"]

if <[grade] ≥ [90]> then
    set [result] to ["A"]
else if <[grade] ≥ [80]> and <[attendance]> then
    set [result] to ["B"]
else if <[grade] ≥ [70]> then
    if <[attendance]> then
        set [result] to ["C"]
    else
        set [result] to ["D"]
```

What is the value of `result`?

A) "A"  
B) "B"  
C) "C"  
D) "D"  
E) "F"  

---

**Question 14: While Loop with Counter**

Examine this Blockly while loop:

```
set [n] to [1]
set [total] to [0]

repeat while <[n] ≤ [5]>
    change [total] by [[n] * [n]]
    change [n] by [1]
```

What is the final value of `total`?

A) 15  
B) 30  
C) 55  
D) 25  
E) 50  

---

**Question 15: List Modification**

Given this Blockly code:

```
set [numbers] to [create list with: 2, 4, 6, 8, 10]
replace item [3] of [numbers] with [100]
insert [50] at position [2] of [numbers]
set [value] to [item [4] of [numbers]]
```

What is the value of `value`?

A) 6  
B) 8  
C) 100  
D) 50  
E) 4  

---

**Question 16: Function with Return**

Analyze this Blockly function and its call:

```
define function [calculate] with parameters [x] [y]
    set [temp] to [[x] + [y]]
    return [[temp] * [2]]

set [a] to [5]
set [b] to [3]
set [result] to [call [calculate] with [a] [b]]
set [final] to [[result] + [a]]
```

What is the value of `final`?

A) 16  
B) 21  
C) 26  
D) 13  
E) 18  

---

**Question 17: Nested Conditionals with Logic**

Examine this complex Blockly structure:

```
set [p] to [true]
set [q] to [false]
set [r] to [true]
set [answer] to [0]

if <[p]> or <[q]> then
    if <not [q]> and <[r]> then
        set [answer] to [1]
    else
        set [answer] to [2]
else
    set [answer] to [3]
```

What is the value of `answer`?

A) 0  
B) 1  
C) 2  
D) 3  
E) undefined  

---

**Question 18: List Filtering with Loop**

Given this Blockly code:

```
set [original] to [create list with: 3, 7, 12, 5, 18, 9, 14]
set [filtered] to [create empty list]

for each [num] in list [original]
    if <[num] > [6]> and <[num] < [15]> then
        add [num] to list [filtered]

set [count] to [length of [filtered]]
```

What is the value of `count`?

A) 2  
B) 3  
C) 4  
D) 5  
E) 6  

---

**Question 19: Recursive-like Pattern**

Analyze this Blockly iteration:

```
set [value] to [2]
set [counter] to [0]

repeat while <[value] < [100]>
    set [value] to [[value] * [2]]
    change [counter] by [1]
```

What is the final value of `counter`?

A) 4  
B) 5  
C) 6  
D) 7  
E) 8  

---

**Question 20: Combined Operations**

Examine this comprehensive Blockly program:

```
set [data] to [create list with: 10, 20, 30, 40, 50]
set [multiplier] to [2]
set [threshold] to [25]
set [total] to [0]

for each [item] in list [data]
    set [processed] to [[item] * [multiplier]]
    if <[processed] > [[threshold] * [2]]> then
        change [total] by [processed]
    else
        change [total] by [[processed] / [2]]
```

What is the final value of `total`?

A) 250  
B) 270  
C) 290  
D) 300  
E) 280  

---

## ANSWER SHEET

| Question | Your Answer |
|----------|-------------|
| 1 | _____ |
| 2 | _____ |
| 3 | _____ |
| 4 | _____ |
| 5 | _____ |
| 6 | _____ |
| 7 | _____ |
| 8 | _____ |
| 9 | _____ |
| 10 | _____ |
| 11 | _____ |
| 12 | _____ |
| 13 | _____ |
| 14 | _____ |
| 15 | _____ |
| 16 | _____ |
| 17 | _____ |
| 18 | _____ |
| 19 | _____ |
| 20 | _____ |

**Total Score:** _____ / 20
