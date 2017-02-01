# Selenium-WebDriver-automation-TestNGFramework

Selenium WebDriver automation using TestNGFramework

A Selenium WebDriver automation test case to create a new account in NPU online application using either Junit or TestNG framework), you don’t
need to finish the last step really create a new
account, but should include

1. Create a log file to record each test case step,

2. Take a screenshot when catching exception,

3. Use @BeforeClass or @BeforeTest, @AfterClass or @AfterTest, @Before or @BeforeMethod, @After or @AfterMethod annotations

4. Use as much as functional methods to reuse.

#

@BeforeClass or @BeforeTest

// *** Beginning ***

@AfterClass or @AfterTest

// *** Ending ***

@Before or @BeforeMethod

// 1. Initiation Firefox browser

// 2. Google search and click to open the search result

// 3. Verify NPU web page is loaded (e.g. check NPU logo, check page title etc.)

@Test

// 4.Open drop down menu Applications then click Apply Online to
open For Application

// 5. Verify the default checkbox should not be selected.

// 6. Select checkbox "I understand and I would like to register a new
account"

// 7. Click Link Text "Register Account" to open Create a New Account

// 8. Verify the default radio button should select in New Applicant,
select it if has not selected

// 9. Select your gender (Male or Female)

// 10. Input Given Name/First Name, Surname/Primary Name, Email Address,
Password, Confirm Password

Please use your real First Name, Last Name and Email address for the automation data; Use a fake password by "000+<your student id>", for
example, 00012345 in your automation.

// 11. Click Save button

// 12. Verify error message(s)

// 13. Go back to Create New Account page

// 14. Go back to NPU home page

@After or AfterClass

// 15. Close browser and exit
