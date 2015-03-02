# TwitterReport2
An automation tool to mass report Twitter accounts.

This is an edit of TwitterReport (found here: https://github.com/anonymous247742/TwitterReport, not mine) that is compatible with the new Twitter update. 

This reports 'This user is abusive > Harrassment > Someone else is (being affected) > Engaging in targeted harassment'

## REQUIREMENTS

-Python 2.7

-Splinter

**UNIX**

Follow these instructions: http://splinter.readthedocs.org/en/latest/install.html

**WINDOWS**

Get the zip: https://github.com/cobrateam/splinter/archive/master.zip
unzip on your disk, open a terminal (start menu -> type cmd -> launch cmd.exe)
go in the folder you unzip splinter (cd XXXX)
launch 'python setup.py install'

## USAGE

Get the twitter accounts list

    Example: 
        https://twitter.com/XXXXXX
        https://twitter.com/XXXXXX
        https://twitter.com/XXXXXX
        https://twitter.com/XXXXXX
        https://twitter.com/XXXXXX
        ...

Save it for example as TwitList.txt in the same folder as twitterReport.py
In the terminal go in the folder you saved twitterReport.py and TwitList.txt

Launch

    python twitterReport.py -u YOUR_USER_NAME -i TwitList.txt

After filling your twitter password, the script will open a browser and do the job.
It's quite slow (about 5s per account) but you can do something while the accounts are reported.
