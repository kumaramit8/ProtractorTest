# ProtractorTest
#Setup Use npm to install Protractor globally with:

npm install -g protractor
This will install two command line tools, protractor and webdriver-manager. Try running protractor --version to make sure it's working.

The webdriver-manager is a helper tool to easily get an instance of a Selenium Server running. Use it to download the necessary binaries with:

webdriver-manager update

# Now start up a server with:

webdriver-manager start
This will start up a Selenium Server and will output a bunch of info logs. Your Protractor test will send requests to this server to control a local browser. You can see information about the status of the server at http://localhost:4444/wd/hub.

Write a test
Open a new command line or terminal window and create a clean folder for testing.

Protractor needs two files to run, a spec file and a configuration file.

# Run the test
Now run the test with:

protractor conf.js
You should see a Chrome browser window open up and navigate to the todo list in the AngularJS page, then close itself (this should be very fast!). The test output should be 1 test, 3 assertions, 0 failures. Congratulations, you've run your first Protractor test!

# Experience summary:
# Pros
Very Easy to learn
Set up is easy
USes Java language

#Cons
Need to learn syntax of the tool.Hence as of now,
PRotractor Script has:
Hardcoded dates and test data.




