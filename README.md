# selenium_test_case_for_codeando
selenium_runner_for_codeando_automated__task.


this testcase was recorded with the selenium extension for chrome, and used with the selenium cli-side-runner, you can also export and use the script in ruby, python or java but in this case we will use the selenium CLI which seems to be faster and more practical.

for this case we will automate several clicks on the page by coding and normal routines to test routes  of the page.
 the way to install the selenium CLI is as follows:

node (the Node.js programming language) version 8 or 10
npm (the NodeJS package manager) which typically gets installed with node
selenium-side-runner (the Selenium IDE command line runner)
and the browser driver we want to use (more on that in the next section)

install node and npm:

it is recommended that you have installed a script that manages node versions I use nvm for this test I have used node version 10
> nvm use node 10
> npm install -g selenium-side-runner

after this if you are going to run the test locally you should use a webdriver you can install it with npm as follows:

chrome
> npm install -g chromedriver

edge
> npm install -g edgedriver

Firefox
> npm install -g geckodriver

finally after the installation it is advisable to restart the computer at least in my case it worked perfectly only after a reboot.

after having everything installed you can use the script in the following way:

>selenium-side-runner /path/to/calippo1.side (calippo1 is a recorded script) 



Translated with www.DeepL.com/Translator 
new transcripts, translates or any feedback are welcome!



