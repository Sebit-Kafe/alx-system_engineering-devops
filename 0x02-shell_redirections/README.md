0x02. Shell, I/O Redirections and filters README file

0-hello_world
script that prints “Hello, World”
#!/bin/bash
echo "Hello, World"

1-confused_smiley
#!/bin/bash
echo "\"(Ôo)'"

2-hellofile
#!/bin/bash
cat /etc/passwd

3-twofiles
#!/bin/bash
cat /etc/passwd /etc/hosts

4-lastlines
#!/bin/bash
tail -n 10 /etc/passwd

5-firstlines
#!/bin/bash
head -n 10 /etc/passwd

6-third_line
#!/bin/bash
head -n 3 iacta | tail -n 1 

7-file
#!/bin/bash
echo "Best School" > \\\*\\\\'"Best School"\'\\\\*$\\\?\\\*\\\*\\\*\\\*\\\*:\)

8-cwd_state
#!/bin/bash
ls -la > ls_cwd_content

9-duplicate_last_line
#!/bin/bash
last -n 1 iacta >> iacta

10-no_more_js
#!/bin/bash
find -type f . -name "*.js"

11-directories
#!/bin/bash
find -type d -not -name "." | wc -l

12-newest_files
#!/bin/bash
ls -t1 | head -n 10


