# Python: Open Source Audit Project

This repository includes five shell scripts along with a structured report outline for the "Open Source Audit" capstone project. The selected open-source software for this project is **Python**.

## Developer Information

* **Student Name**: Abhijeet Balaji Patil
* **Registration Number**: 24BCE10110
* **Chosen Software**: Python

## Project Shell Scripts

All scripts are created to run in a standard Linux environment and demonstrate basic shell scripting concepts.

1. **`sys_identity.sh`**
   This script displays important system details such as kernel version, Linux distribution name, current user, system uptime, and date/time using variables and command substitution.

2. **`package_inspector.sh`**
   This script checks whether `python3` is installed using package managers like `dpkg` or `rpm`. It also uses a `case` statement to print a short description of selected open-source tools.

3. **`disk_auditor.sh`**
   This script loops through a list of important directories and shows their size along with permissions and ownership using commands like `ls -ld`, `du`, and `awk`.

4. **`log_analyzer.sh`**
   This script reads a given log file line by line using a `while read` loop, counts occurrences of a keyword (such as "error"), and also prints the last five matching lines.

5. **`manifesto.sh`**
   This is an interactive script that asks the user a few questions and generates a personalized open-source manifesto, which is saved into a `.txt` file.

## Instructions to Run

1. Open the terminal and navigate to the project directory or clone the repository.
2. Give execution permission to all scripts:

   ```bash
   chmod +x *.sh
   ```
3. Run any script using:

   ```bash
   ./script_name.sh
   ```

   Example:

   ```bash
   ./sys_identity.sh
   ```

*(Note: Script 4 (`log_analyzer.sh`) requires a file path and optional keyword. Example: `./log_analyzer.sh /var/log/syslog error`)*

## Dependencies

* Bash shell (`/bin/bash`)
* Standard Linux utilities such as `awk`, `cut`, `grep`, `tail`, `du`
* Package managers (`dpkg` or `rpm`)

No additional installations are required on most Linux systems.
