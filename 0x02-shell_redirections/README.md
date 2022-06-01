0. Hello World - echo "Hello, World" - prints the text "Hello, World"
1. Confused smiley - echo \"\(Ôo\)\' - prints "(Ôo)'
2. Let's display a file - cat /etc/passwd - Display the content of the /etc/passwd file.
3. What about 2? - cat /etc/passwd /etc/hosts - Display the content of /etc/passwd and /etc/hosts
4. Last lines of a file - tail /etc/passwd - Display the last 10 lines of /etc/passwd
5. I'd prefer the first ones actually - head /etc/passwd - Display the first 10 lines of /etc/passwd
6. Line #2 - head -3 iacta | tail -1 -displays the third line of the file iacta.
7. It is a good file that cuts iron without making a noise - echo 'Best School' >>  "\\*\\\'\"Best School\"\'\\\*$\\?\\*\*\*\*\*:)" - Write a shell script that creates a file named exactly \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) containing the text Best School ending by a new line.
8. Save current state of directory - ls -la > ls_cwd_content - writes into the file ls_cwd_content the result of the command ls -la
9. Duplicate last line - cat iacta | tail -n 1 >> iacta - Write a script that duplicates the last line of the file iacta
10. No more javascript - find -name "*.js" -type f -delete - deletes all the regular files (not the directories) with a .js
11. Don't just count your directories, make your directories count - find -mindepth 1 -type d | wc -l - Write a script that counts the number of directories and sub-directories in the current directory.
12.What’s new - ls -t | head -10 - Create a script that displays the 10 newest files in the current directory.
13.Being unique is better than being perfect - sort | uniq -u - Create a script that takes a list of words as input and prints only words that appear exactly once.
14.It must be in that file - grep -i "root" /etc/passwd - Display lines containing the pattern “root” from the file /etc/passwd
15.Count that word - grep -c -i "bin" /etc/passwd - Display the number of lines that contain the pattern “bin” in the file /etc/passwd
16.What's next? - grep -i "root" -A 3 /etc/passwd - Display lines containing the pattern “root” and 3 lines after them in the file /etc/passwd.
17.I hate bins - grep -i -v "bin" /etc/passwd - Display all the lines in the file /etc/passwd that do not contain the pattern “bin”.
18.Letters only please - grep -i "^[a-z]" /etc/ssh/sshd_config - Display all lines of the file /etc/ssh/sshd_config starting with a letter.
19.A to Z - tr "A" "Z" | tr "c" "e" - Replace all characters A and c from input to Z and e respectively.
20.Without C, you would live in hiago - tr -d "cC" - Create a script that removes all letters c and C from input.
21.esreveR - rev - Write a script that reverse its input.
22.DJ Cut Killer - cut -d : -f 1,6 /etc/passwd | sort - Write a script that displays all users and their home directories, sorted by users.
