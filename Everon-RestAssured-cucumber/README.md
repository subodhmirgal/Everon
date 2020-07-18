Swagger Petstore API Tests (Cucumber - Rest Assured) 
=====================================
This is automation suite is designed to test the Swagger Pet store POST /pet request (Additonal services have also been included but were not essential).

The project has 6 scenarios that that can be located within the feature files: <br>
 - src/test/resources/PetTests.feature<br>

**PetTests.feature scenarios include:**
    Scenario: Users are able to add pets to the system<br>
    Scenario: Users are able to delete pets from the system<br>
    Scenario: Users are able to add pets that have multiple tags<br>
    Scenario: Users are able to add pets that have no tags<br>
    Scenario: Id's are automatically generated for pets when not supplied with the request<br>
    Scenario: Adding a pet with no body for the request results in a 400 response <br>
        
All scenarios designed with tag **@smokeTest** in order to be included in smoke test pack<br>

In order to execute the automation suite navigate to the Project directory within a Terminal/CMD window and run the command: **'mvn clean test'**. OR<br>
**'gradle clean test'**<br>


