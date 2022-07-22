# Shell redirections.

Here, we explore a powerful feature used by command line programs called input/output redirection.

# Table of Contents

* [A script that prints “Hello, World”, followed by a new line to the standard output.](https://github.com/Chidiagb/alx-system_engineering-devops/blob/master/0x02-shell_redirections/0-hello_world)
* [A script that displays a confused smiley "(Ôo)'.](https://github.com/Chidiagb/alx-system_engineering-devops/blob/master/0x02-shell_redirections/1-confused_smiley)
* [Display the content of the /etc/passwd file.](https://github.com/Chidiagb/alx-system_engineering-devops/blob/master/0x02-shell_redirections/2-hellofile)
* [Display the content of /etc/passwd and /etc/hosts](https://github.com/Chidiagb/alx-system_engineering-devops/blob/master/0x02-shell_redirections/3-twofiles)
* [Display the last 10 lines of /etc/passwd](https://github.com/Chidiagb/alx-system_engineering-devops/blob/master/0x02-shell_redirections/4-lastlines)
* [Display the first 10 lines of /etc/passwd](https://github.com/Chidiagb/alx-system_engineering-devops/blob/master/0x02-shell_redirections/5-firstlines)
* [A script that displays the third line of the file iacta.](https://github.com/Chidiagb/alx-system_engineering-devops/blob/master/0x02-shell_redirections/6-third_line)
* [A shell script that creates a file named exactly \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) containing the text Best School ending by a new line.](https://github.com/Chidiagb/alx-system_engineering-devops/blob/master/0x02-shell_redirections/7-file)
* [A script that writes into the file ls_cwd_content the result of the command ls -la.](https://github.com/Chidiagb/alx-system_engineering-devops/blob/master/0x02-shell_redirections/8-cwd_state)
* [A script that duplicates the last line of the file iacta.](https://github.com/Chidiagb/alx-system_engineering-devops/blob/master/0x02-shell_redirections/9-duplicate_last_line)
* [A script that deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders.](https://github.com/Chidiagb/alx-system_engineering-devops/blob/master/0x02-shell_redirections/10-no_more_js)
* [A script that counts the number of directories and sub-directories in the current directory.](https://github.com/Chidiagb/alx-system_engineering-devops/blob/master/0x02-shell_redirections/11-directories)
* [A script that displays the 10 newest files in the current directory.](https://github.com/Chidiagb/alx-system_engineering-devops/blob/master/0x02-shell_redirections/12-newest_files)
* [A script that takes a list of words as input and prints only words that appear exactly once.](https://github.com/Chidiagb/alx-system_engineering-devops/blob/master/0x02-shell_redirections/13-unique)
* [Display lines containing the pattern “root” from the file /etc/passwd.](https://github.com/Chidiagb/alx-system_engineering-devops/blob/master/0x02-shell_redirections/14-findthatword)
* [Display the number of lines that contain the pattern “bin” in the file /etc/passwd](https://github.com/Chidiagb/alx-system_engineering-devops/blob/master/0x02-shell_redirections/15-countthatword)
* [Display lines containing the pattern “root” and 3 lines after them in the file /etc/passwd.](https://github.com/Chidiagb/alx-system_engineering-devops/blob/master/0x02-shell_redirections/16-whatsnext)
* [Display all the lines in the file /etc/passwd that do not contain the pattern “bin”.](https://github.com/Chidiagb/alx-system_engineering-devops/blob/master/0x02-shell_redirections/17-hidethisword)
* [Display all lines of the file /etc/ssh/sshd_config starting with a letter.](https://github.com/Chidiagb/alx-system_engineering-devops/blob/master/0x02-shell_redirections/18-letteronly)
* [Replace all characters A and c from input to Z and e respectively.](https://github.com/Chidiagb/alx-system_engineering-devops/blob/master/0x02-shell_redirections/19-AZ)
* [A script that removes all letters c and C from input.](https://github.com/Chidiagb/alx-system_engineering-devops/blob/master/0x02-shell_redirections/20-hiago)
* [A script that reverse its input.](https://github.com/Chidiagb/alx-system_engineering-devops/blob/master/0x02-shell_redirections/21-reverse)
* [A script that displays all users and their home directories, sorted by users.](https://github.com/Chidiagb/alx-system_engineering-devops/blob/master/0x02-shell_redirections/22-users_and_homes)
* [A command that finds all empty files and directories in the current directory and all sub-directories.](https://github.com/Chidiagb/alx-system_engineering-devops/blob/master/0x02-shell_redirections/100-empty_casks)
* [A script that lists all the files with a .gif extension in the current directory and all its sub-directories.](https://github.com/Chidiagb/alx-system_engineering-devops/blob/master/0x02-shell_redirections/101-gifs)
* [Create a script that decodes acrostics that use the first letter of each line.](https://github.com/Chidiagb/alx-system_engineering-devops/blob/master/0x02-shell_redirections/102-acrostic)
* [A script that parses web servers logs in TSV format as input and displays the 11 hosts or IP addresses which did the most requests.](https://github.com/Chidiagb/alx-system_engineering-devops/blob/master/0x02-shell_redirections/103-the_biggest_fan)
