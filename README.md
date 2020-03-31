# crawler-tester
This is a program that tests the crawler


NOTE: This code and testcase are by no means garantined to be correct. I advise you have a look over it
to double check.

Example usuage:
python test.py tests/web-comp30023-index.txt

Note most of these are pointing to the web1.comp30023 host which can only be accessed on the vms, so you have to push
this over there with your crawler code

python test.py tests/jigsaw_redirect_test.txt
This is currently the only one that puts to a different host, that can be used outside the vm


The first line in the file is what the crawler will be directed to,
every line after that is what the crawler should find, order does not matter, except that the first line 
is the where the crawler goes first. 


Currently it only:
Checks that you printed out the same absolute url as the test case

Do not have any duplicate url (however does not say if you printed out a relative url that is the same as an absolute)

What it does not currently do:
It does not make sure that your header is valid, ie correct Agent name
It does not check that your are fetching the pages only once


Feel free on forking and adding all the functionality that it is currenlty missing.
And adding extra test case on other external sites.


