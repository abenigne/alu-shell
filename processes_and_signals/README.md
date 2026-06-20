# alu-shell

Shell scripting projects exploring core Unix/Linux concepts in Bash.

## processes_and_signals

Scripts covering processes, PIDs, and signals on Ubuntu 20.04 LTS.

### Learning Objectives
- What is a PID
- What is a process
- How to find a process's PID
- How to kill a process
- What is a signal
- What are the 2 signals that cannot be ignored

### Files
| File | Description |
|---|---|
| `0-what-is-my-pid` | Displays its own PID |
| `1-list_your_processes` | Lists all running processes, all users, with hierarchy |
| `2-show_your_bash_pid` | Shows lines containing "bash" (using ps + grep) |
| `3-show_your_bash_pid_made_easy` | Shows PID + name of processes named bash (no ps) |
| `4-to_infinity_and_beyond` | Infinite loop, prints a message every 2 seconds |
| `5-dont_stop_me_now` | Stops `4-to_infinity_and_beyond` using kill |
| `6-stop_me_if_you_can` | Stops `4-to_infinity_and_beyond` without kill/killall |
| `7-highlander` | Infinite loop immune to SIGTERM |
| `67-stop_me_if_you_can` | Stops `7-highlander` |
| `8-beheaded_process` | Kills `7-highlander` |
| `10-process_and_pid_file` | Writes a PID file, handles SIGTERM/SIGINT/SIGQUIT |
| `11-manage_my_process` / `manage_my_process` | Init-style start/stop/restart script and its daemon |

### Requirements
All scripts:
- Start with `#!/usr/bin/env bash`
- Have a second-line comment explaining what they do
- Pass `shellcheck` with no errors
