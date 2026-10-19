
# Compiler Design Lab Programs

A collection of C programs implemented as part of the **Compiler Design Lab**. These experiments demonstrate fundamental compiler concepts, including lexical analysis, parsing, intermediate code generation, code optimization, and target code generation.

## Experiments

| No. | Experiment | Description |
|---:|---|---|
| 1 | Lexical Analyzer in C | Identifies tokens such as keywords, identifiers, operators, and constants. |
| 2 | Lexical Analyzer using LEX | Uses LEX patterns to recognize tokens. |
| 3 | Count Lines, Words, and Characters using LEX | Counts lines, words, and characters in input. |
| 4 | Replace a Substring using LEX | Replaces occurrences of `abc` with `ABC`. |
| 5 | Count Vowels and Consonants using LEX | Counts vowels and consonants in input text. |
| 6 | Arithmetic Expression Recognition using LEX and YACC | Recognizes arithmetic expressions according to grammar rules. |
| 7 | Identifier Validation using LEX and YACC | Checks whether an input follows identifier naming rules. |
| 8 | Calculator using LEX and YACC | Evaluates arithmetic expressions. |
| 9 | ε-Closure of an NFA | Computes epsilon-closure sets for NFA states. |
| 10 | FIRST and FOLLOW | Computes FIRST and FOLLOW sets for a grammar. |
| 11 | Shift-Reduce Parser | Demonstrates shifting and reducing symbols using grammar productions. |
| 12 | Simulation of Code Optimization | Demonstrates loop unrolling by comparing a loop with repeated statements. |
| 13 | Intermediate Code Generation | Converts simple arithmetic expressions into intermediate instructions. |
| 14 | 8086 Target Code Generation | Converts three-address code into simplified assembly-style instructions. |

## Requirements

- C compiler, such as GCC
- LEX/FLEX and YACC/Bison for experiments that use them
- Terminal or command prompt

## Compile and Run C Programs

For a C program:

```bash
gcc filename.c -o program
./program
```

On Windows, run:

```bash
gcc filename.c -o program.exe
program.exe
```

Replace `filename.c` with the name of the source file.

## Compile and Run LEX/YACC Programs

For programs using LEX and YACC, the typical commands are:

```bash
lex lexer.l
yacc -d parser.y
gcc lex.yy.c y.tab.c -o parser -ll
./parser
```

Depending on the installed tools, you may need to use `flex` and `bison` instead of `lex` and `yacc`. Some systems also require linking with `-lfl`.

## Notes

- These programs are intended for educational and lab-practical use.
- Some implementations are simplified to demonstrate the core concept and may support only the input formats described in the corresponding experiment.
- Check each program's comments and sample input before running it.

## Author

**Evlin Sara Johny**  
B.Tech Computer Science and Engineering  
St. Joseph's College of Engineering and Technology, Palai
