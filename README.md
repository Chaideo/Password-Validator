# Password-Validator
To generate a logic for Password Validation


Password Validator Tool Following Rules to be followed:

Length of password should be of at-least 8 characters
At-least one uppercase character
At-least one alpha-numeric character
No whitespace character is allowed
optional arguments: -h, --help show this help message and exit

Execution:
(env) C:\Users\Admin\Desktop\assignments\python_asg\passwordvalidator>python main.py -p Wel@1234
26-Jul-20 17:36:25 - Password entered by User: Wel@1234
26-Jul-20 17:36:25 - Valid Password, All checks done!!

(env) C:\Users\Admin\Desktop\assignments\python_asg\passwordvalidator>c:/Users/Admin/Desktop/assignments/env/Scripts/python.exe c:/Users/Admin/Desktop/assignments/python_asg/passwordvalidator/test_main.py
...ERROR:root:Password wel 12345 shouldn't contain any whitespace character
.ERROR:root:Password abcd12 length is less than at-least 8 characters
.ERROR:root:Password !@#$%^ should contain at-least one alphanumeric character
.ERROR:root:Password wel12345 should contain at-least one special characters ~!@#$%^&*
.ERROR:root:Password wel@1234 should contain at-least one uppercase character
...
----------------------------------------------------------------------
Ran 10 tests in 0.025s

OK
