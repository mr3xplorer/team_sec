# Linux Modules
Linux is an operating system like Windows or macOS. 
It's the software that manages all the hardware in your computer and lets you run programs. 
It's popular because it's free, open-source, and very flexible, meaning you can customize it a lot. 
It's used on everything from phones and laptops to servers and supercomputers.

## Basics Commands

- **du:** du is a command in linux (short for disk usage) which helps you identify what files/directories are consuming how much space.

- **Grep, Egrep, Fgrep:** The grep filter searches a file for a particular pattern of characters, and displays all lines that contain that pattern. The pattern that is searched in the file is referred to as the regular expression. 
  -  In other terms, grep -E functions same as egrep and grep -F functions same as fgrep.
  - **Syntax:**  grep "PATTERN" file.txt

- **String Manipulations (STRing OPerationS):** String manipulations are operations performed on text strings, such as combining, splitting, replacing, or modifying characters and substrings.
  - **Syntax (Splitting):**  (IFS=',' read -ra filename <<< "$text")
  
- **tr:** Translate command(tr) can help you in number of ways, ranging from changing character cases in a string to replacing characters in a string. It's awesome at it's usage. Plus, it's the easiest command and a must know module for quick operations on strings.
  - **Syntax:** tr [flags] [source]/[find]/[select] [destination]/[replace]/[change]


