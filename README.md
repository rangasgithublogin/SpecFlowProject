# SpecFlow Test Automation Demo
- A sample test automation project to test API's using SpecFlow & .Net 6
- Test Features added for List Users, GET Single User, Post, Put & Patch
- Single User test inclues the 404 not found, a negative test
- The List Users test is a data-driven test for different users & the JSON response is parsed to findout the availability of each user
- To demonstrate usage of vital info like password etc effective Login test feature uses a encoded password
- From powershell prompt run 'dotnet test -e env="SIT"' to execute all the tests
- The test environment name is externalized and passed as a command line parameter. Depending on the value given, the respective URL can be used.
- From powershell prompt run 'LivingDoc feature-folder C:\users\<yourUserName>\source\repos\SpecFlowProject\SpecFlowProject -t C:\Users\<yourUserName>\source\repos\SpecFlowProject\SpecFlowProject\bin\Debug\net6.0\TestExecution.json'
- Access LivingDoc.html on the root of the project to view the test report
