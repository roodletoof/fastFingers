**This program is a single file python script that will test your typing-speed in the terminal.**

Set your preferred settings by changing the relevant constants at the top of the file.

The goal of this is to have something that is easy to just download and test.


***To reach that goal I have done the following things:***


- The high-score is updated each time it is beat, and stored at the top of the script as a constant.
The constant is found and updated using a regular expression, so as long as the regex still matches the MY_RECORD constant, there should be no problem.


- The list of words is downloaded each time the script runs.
