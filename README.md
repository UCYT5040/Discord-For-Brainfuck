# Discord For Brainfuck

Changes:
- There is now a variable called `val`, that can hold a value of more than 1 character. Val is almost like a list that you can navigate and set values.
- `&` (or `a`) is used to go left in `val`. Empty items in `val` are ignored. If you try going too far left, it will be ignored.
- `*` (or `s`) is used to go right in `val`. Empty items in `val` are ignored.
- `^` (or `i`) is used to set the current item in `val`.
- `%` (or `p`) is used to reset `val` to nothing.
- Once you define a command, any lines after that are run on the command, until another command is defined.
- `.` (print) now adds a character to output.
- `,` (input) gets a character from arguments.
- `!` (or `c`) is used to create a command, with `val` as the command name. Arguments are not supported.
