# knock bash

### sleep
> 1. ./sleep.sh &
> 2. ps -fp 97647
> 3. fg

### file oprators
> 1. -d True if file is a directory.
> 2. -e True if file exists.
> 3. -f True if file exists and is a regular file.
> 4. -r True if file is readable by you.
> 5. -s True if file exists and is not empty.
> 6. -w True if the file is writable by you.
> 7. -x True if the file is executable by you.
> 8. -z STRING True if string is empty.
> 9. -n STRING True if string is not empty.
> 10. STRING1 = STRING2  True if the strings are equal. 
> 11. STRING1 != STRING2 True if the strings are not equal. 
> 12. arg1 -eq arg2 True if arg1 is equal to arg2
> 13. arg1 -ne arg2 True if arg1 is not equal to arg2
> 14. arg1 -lt arg2 True if arg1 is less than arg2
> 15. arg1 -le arg2 True if arg1 is less than or equal to arg2
> 16. arg1 -gt arg2 True if arg1 is greater than arg2
> 17. arg1 -ge arg2 True if arg1 is greater than or equal to arg2

### Making Decisions
> 1. if statement
    if [ condition-is-true ]
    then
      command 1
      command 2
      command N
    elif [ condition-is-true ]
    then
      command N
    else
      command N
    fi