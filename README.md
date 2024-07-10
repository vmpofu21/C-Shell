# C-Shell

<h2>Introduction</h2>
<p>
C-shell program implemented in C is a simple Unix shell that supports job control, providing basic shell functionalities, including executing commands, handling built-in commands, and managing jobs (foreground and background processes).

</p>

----------------------------------------------------------------------------------------------------

<h2>Functions</h2>

• eval: Parses and executes commands entered by the user.
• builtin_cmd: Checks and executes built-in commands.
• do_bgfg: Implements the bg and fg built-in commands.
• waitfg: Waits for a foreground job to complete.
• sigchld_handler: Handles SIGCHLD signals.
• sigint_handler: Handles SIGINT (Ctrl-C) signals.
• sigtstp_handler: Handles SIGTSTP (Ctrl-Z) signals.

----------------------------------------------------------------------------------------------------

<h2>Features</h2>

• Command Execution: Executes both built-in and external commands.
• Job Control: Supports job control commands such as bg (background) and fg (foreground).
• Signal Handling: Handles signals like SIGINT, SIGTSTP, and SIGCHLD.
• Built-in Commands: Includes built-in commands like quit, jobs, bg, and fg.
