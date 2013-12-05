SelWeb_Cucumber
===============

Tests to explore the automation possibilities using Selenium Webdriver used in combination with Ruby

This is my first repo!!!! :)

I have been trying out different automation tools and wanted to explore Selenium webdriver with cucumber and ruby.
Thought of documenting it as and when i work on it.Not much technical details are specified as i have come from a testing background, but i hope the details are clear !!!

Steps to get started:

Create a folder for the sample project and install the following at this location:

1. Install ruby and ruby gems. Have installed RVM as well as it gives greater flexibility Multiple ways of installing Ruby, used Homebrew for installing ruby http://brew.sh/

2. Install cucumber https://github.com/cucumber/cucumber/wiki/Install

3. Install rspec http://rspec.info/

4. Install Selenium webdriver:
   gem install selenium-webdriver

5. Install Anvil for hosting the website locally, it assigns a .dev domain

6. Create a folder named 'features' within this sample project

7. Create a folder named 'support' under 'features' folder.We need to set up the following two files in support:
   - env.rb : 
   This is for managing environment variables
   https://rubygems.org/gems/env.rb
   For this sample project, i have included the selenium-webdriver and rspec
   - hooks.rb :
     Cucumber uses this files for checking what action needs to be done for each of the scenarios i.e. before and 
     after each scenario.More information can be found at :
     https://github.com/cucumber/cucumber/wiki/Hooks
     For this example, i have just added 
     - before : initializes the browser before each scenario 
     - after : closes the browser after the scenario has been completed
  
   
