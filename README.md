# python-selenium-translator
This is a script written in python using selenium library to automate translation from german to english. The DeepL translator is used  for translation, which takes only 5000 characters at a time. It also does not remove the '-' character from the end of each line which changes the meaning of word after translation. With this script, the '-' character will be automatically removed from the end of each line and one can add as much as data in a file in small paragraphs to translate the whole thing at once rather than translating only 5000 characters at a time.

**Prerequisites**
* Firefox browser
* python
* selenium and webdriver_manager packages

**Steps**
* Run the commands below to install selenium and webdriver_manager.<br />
   * pip install selenium<br />
   * pip install webdriver_manager
   
* Create a file translator.py in your local machine and paste all the code from translator.py file above to your file.
* Create a file with .txt extension in the same directory where your translator.py file exists.
* Paste all the text in that you want to convert from german to english in small paragraphs. Make sure to keep one line gap after each paragraphs. One para should not be more than 5000 characters.
* Change the directory in command line in which your translator.py file exists.
* Run the file "translator.py" with command:<br />
   * python3 translator.py
 
![image](https://user-images.githubusercontent.com/89373629/235847090-3b5ad5c1-60a0-471b-830a-17aadfc94b38.png)

* Check out the file output.txt in the directory where your translator.py file exists. (This file will contain all the translated text)

