This directory is used for debugging code

0-fizzbuzz.py
I fixed the bug in this code by checking for fizzbuzz before checking for fizz and buzz

1-print_square.js
I fixed the bug by changing this line:
from size = parseInt(process.argv[2], 16) to size = parseInt(process.argv[2], 10)
so that it works with base 10 and not base 16

2-sort.rb
I fixed the bug by changing how integers were being added to the results list
from result.insert(i - 1, i_arg) to result.insert(i, i_arg)

3-user.py
I fixed the bug by changing self._password in line 43 to self.__password and also using a .lower() instead in line 57

