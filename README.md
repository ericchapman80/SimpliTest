# SimpliTest 
SimpliTest (formerly known as Café) was created by CGI Group Inc. members to accelerate the adoption of ATDD/BDD using Cucumber/Gherkin as the base framework. At it's core are many predefined step definitions backed by helper and utility methods.  Mainly focused on the web interfaces using Selenium, but not restricted to only web apps, your imagination is it's limitation.

## Installation 

	1) Install Ruby & DevKit: https://rubyinstaller.org/downloads/
	
	2) Download Selenium drivers and place them in Ruby bin
		- http://www.seleniumhq.org/projects/webdriver/
	
	3) Build this Ruby gem
		$ gem build SimpliTest.gemspec
    		$ gem install SimpliTest
		$ If you receive an error related to tiny_tds not being installed
		  you are likely facing an issue related to your computer's architecture.
	          Run this command to indicate the architecture.
		  `sudo ARCHFLAGS="-arch x86_64" gem install tiny_tds`

		$ You should now successfully be able to run the gem install.
	4) Use it
		$SimpliTest new MyNewSimpliTestProject
			or cd into an existing directory and run 
		$SimpliTest init
		
		$SimpliTest run
		$SimpliTest smoketest
		
