# Webdriverclass
## Run test:
  - Clone repo git@github.com:KrzysztofNalewajek1/Webdriverclass.git
  - run npm install
  - run yarn wdio



[0-0] PASSED in chrome - C:\Users\krn\EVO\Webdriverclass\features\bootcamp.feature
2022-11-29T07:28:32.141Z INFO @wdio/cli:launcher: Run onWorkerEnd hook
2022-11-29T07:28:32.142Z INFO @wdio/cli:launcher: Run onComplete hook

 "spec" Reporter:
------------------------------------------------------------------
[chrome 107.0.5304.122 windows #0-0] Running: chrome (v107.0.5304.122) on windows
[chrome 107.0.5304.122 windows #0-0] Session ID: 737fd2f414b467f8e221044e1f6aaa64
[chrome 107.0.5304.122 windows #0-0]
[chrome 107.0.5304.122 windows #0-0] » \features\bootcamp.feature
[chrome 107.0.5304.122 windows #0-0] Bootcamp E2E
[chrome 107.0.5304.122 windows #0-0] Search bar
[chrome 107.0.5304.122 windows #0-0]    ✓ Given I am on the home page
[chrome 107.0.5304.122 windows #0-0]    ✓ When I enter the word 'Windows' in the search bar
[chrome 107.0.5304.122 windows #0-0]    ✓ And I click the search
[chrome 107.0.5304.122 windows #0-0]    ✓ Then I Check that at least one item appears
[chrome 107.0.5304.122 windows #0-0]
[chrome 107.0.5304.122 windows #0-0]    ✓ Given I am on the home page
[chrome 107.0.5304.122 windows #0-0]    ✓ When I open 'Today's Best Deals' tab
[chrome 107.0.5304.122 windows #0-0]    ✓ And I click on the Internet shop logo
[chrome 107.0.5304.122 windows #0-0]    ✓ Then I expect that the main page opened
[chrome 107.0.5304.122 windows #0-0]
[chrome 107.0.5304.122 windows #0-0] 8 passing (10.7s)


Spec Files:      1 passed, 1 total (100% completed) in 00:00:13















## Project Installation:
    - Check node version node -v (if needed, install)
    - Check yarn version yarn -v (if needed, install)
    - Create project folder and navigate to it
    - yarn init
    - yarn create wdio .
      - On my local machine
      - Which framework do you want to use? (cucumber)
      - Do you want to use a compiler? (No)
      - Where are your feature files located? (defalut)
      - Where are your step definitions located? (default)
      - Do you want WebdriverIO to autogenerate some test files? (yes)
      - Do you want to use page objects (https://martinfowler.com/bliki/PageObject.html)? (n)
      - Which reporter do you want to use? (allure + spec)
      - Do you want to add a plugin to your test setup? (n)
      - Do you want to add a service to your test setup? (chromedriver)
      - What is the base url?  (default)
      - Do you want me to run `npm install`  (y)





## Home task:
//TA-Bootcamp-E2E
Develop E2E automated JS tests for https://www.newegg.com

//Create bootcamp.feature file with the following 2 scenarios. Prepare tests only for Desktop run

//Feature: Bootcamp E2E

//Scenario: Search bar
//Open the home page
//Close the promo banner if it appears
//Entry the word "Windows" in the search bar (top middle)
//Click the search
//Check that at least one item appears

//Scenario: Internet shop logo button
//Open the home page
//Close the promo banner if it appears
//Open "Today's Best Deals" tab
//Click on the Internet shop logo (top right corner)
//Check that the main page opened

Extra requirements:
//For task set up WebdriverIO + Cucumber (As it was done in Cucumber lectures)
//As you may already notice, the 2 first steps are the same for both scenarios. Please use Background: to reduce the number of steps.
Before sending me a task prepare README.md so I can run your tests.
Good practice, avoid magic numbers (You can google if you don't know what it means)
Use consts for variables
For assertions use WebdriverIO
Hint
For "Close the promo banner if it appears" 2 possible ideas. You can use try-catch. Or the banner disappears if you refresh the page when the banner appears.
