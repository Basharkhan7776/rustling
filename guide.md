# How to do the Rustlings Exercises

This guide will walk you through the process of completing the Rustlings exercises.

## The `watch` command

The easiest way to work through the exercises is to use the `watch` command:

```bash
rustlings watch
```

This command will start by trying to compile the first exercise. It will fail, and show you the error message from the compiler.

Your task is to fix the code in the exercise file to make the compiler happy.

The `watch` command will keep monitoring the file, and as soon as you save it, it will try to compile it again. If you fixed the code correctly, it will move on to the next exercise.

## The Workflow

1.  **Run `rustlings watch`** in your terminal.
2.  **Identify the failing exercise:** The output will tell you which file you need to edit (e.g., `exercises/variables/variables1.rs`).
3.  **Open the exercise file** in your favorite editor.
4.  **Fix the code:** Read the comments in the file and the compiler error to understand what you need to do. In early exercises, you might just need to remove the `// I AM NOT DONE` line.
5.  **Save the file.**
6.  **Check the terminal:** The `watch` command will automatically re-run the exercise.
7.  **Repeat:** If you fixed it, `watch` will move to the next exercise. If not, you'll see a new error message.

## Other useful commands

Here are some other commands you might find useful:

*   `rustlings verify`: Runs all exercises and shows you which ones are passing and which are failing.
*   `rustlings run <exercise_name>`: Runs a specific exercise (e.g., `rustlings run variables1`).
*   `rustlings hint <exercise_name>`: Gives you a hint for a specific exercise.
*   `rustlings list`: Lists all the exercises and their status (pending or done).

Happy coding!
