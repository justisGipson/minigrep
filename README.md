Basic `grep` command line tool example.

`grep` (**G**lobally search a **R**egular **E**xpression and **P**rint)

 In the simplest use case, grep searches a specified file for a specified string. To do so, grep takes as its arguments a filename and a string. Then it reads the file, finds lines in that file that contain the string argument, and prints those lines.

 `cargo run to poem.txt` to find matches to the word `to` or make it whatever...

 `cargo run to poem.txt > output.txt` for search results in a .txt file, instead of the console
