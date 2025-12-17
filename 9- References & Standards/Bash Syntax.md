
### `Definition`

A reference for **Bash shell syntax and language rules**, describing **how Bash parses, expands, and executes commands**. This defines Bash as a **scripting language**, not just a command runner.

---
### `Purpose`

To document the **grammar and execution rules of Bash**, enabling correct scripting, predictable command behavior, and a clear understanding of what is **shell logic vs external tooling**.

---
### `Structure`

##### ==`Variables & Expansion`==

- `VAR=value` — variable assignment
    
- `$VAR`, `${VAR}` — variable expansion
    
- `${VAR:-default}` — default value expansion
    
- `$(command)` — command substitution
    
- `$((expression))` — arithmetic expansion

##### ==`Quoting & Globbing`==

- `#` — comment delimiter (everything after is ignored by the shell)
	
- `*` — wildcard match
    
- `?` — single-character match
	
- `;` — command separator
	
- `[]` — character class
    
- `"double quotes"` — expand variables, preserve spaces
    
- `'single quotes'` — literal strings
    
- `\` — escape character

##### ==`Redirection & Pipes`==

- `>` — redirect stdout
    
- `>>` — append stdout
    
- `2>` — redirect stderr, overwrite
	
- `2>>` — redirect stderr, append
    
- `&>` — redirect stdout + stderr
    
- `<` — redirect stdin
    
- `|` — pipe output to another command

##### ==`Conditionals`==

- `if ... then ... fi` — conditional execution
    
- `[ condition ]` — POSIX test
    
- `[[ condition ]]` — Bash conditional

Common tests:

- `-f file` — file exists
    
- `-d dir` — directory exists
    
- `-z str` — empty string
    
- `-n str` — non-empty string

##### ==`Loops & Flow Control`==

- `for i in {0..5}; do ... done`
	
- `for item in ${my_array[@]}; do ... done`
    
- `while condition; do ... done`
    
- `until condition; do ... done`
    
- `break` — exit loop
    
- `continue` — skip iteration

##### ==`Execution Control`==

- `cmd1 && cmd2` — run if success
    
- `cmd1 || cmd2` — run if failure
    
- `cmd &` — background execution

##### ==`Scripting Essentials`==

- `#!/usr/bin/env bash` — Bash shebang
    
- `set -e` — exit on error
    
- `set -u` — error on unset variables
    
- `set -o pipefail` — fail on pipeline error

---
### `Connected Notes`

- [[bash]]