echo "Hello, World" -- script that prints “Hello, World”, followed by a new line to the standard output

echo "(Ôo)" -- script that displays a confused smiley

cat /etc/passwd -- script that displays the content of the /etc/passwd file

less /etc/passwd /etc/hosts -- script to display the content of /etc/passwd and /etc/hosts

tail -n 10 /etc/passwd -- script to display the last 10 lines of /etc/passwd

head -n 10 /etc/passwd -- script to display the first 10 lines of /etc/passwd

head -n 3 iacta | tail -n 1 -- script that displays the third line of the file iacta

echo Best School > \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) -- script creating file \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) containing the text Best School

ls -la >ls_cwd_content -- script that writes into the file ls_cwd_content the result of the command ls -la

tail -n 1 iacta >> iacta -- script that duplicates the last line of the file iacta`

find . -type f -name "*.js" -delete -- script that deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders

find ./* -type d | wc -l -- script that counts the number of directories and sub-directories in the current

ls -t -1 | head -- script that displays the 10 newest files in the current directory

sort | uniq -u -- script that takes a list of words as input and prints only words that appear exactly once

grep -e "root" /etc/passwd -- Display lines containing the pattern “root” from the file /etc/passwd

grep -c "bin" /etc/passwd -- Display the number of lines that contain the pattern “bin” in the file

grep -A 3 "root" /etc/passwd --Display lines containing the pattern “root” and 3 lines after them in the file

grep -v "bin" /etc/passwd -- Display all the lines in the file /etc/passwd that do not contain the pattern “bin”

grep ^[a-zA-Z] /etc/ssh/sshd_config -- Display all lines of the file /etc/ssh/sshd_config starting with a letter

tr A Z | tr c e -- Replace all characters A and c from input to Z and e respectively

tr -d c | tr -d C -- script that removes all letters c and C from input
