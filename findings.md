AuthContoller/ProjectContoller/TaskController:
-Status: Observed
-Evidence: Cross origin has been assigned to *
-Impact: Any authorized client or service may have access to backend
-Priority: High
- Proposed solution: Allow only known clients/service


TaskService:
-Status: observed
-Evidence: Sql query or database logic is in service. service has to handle business logic
-Impact: It will make maintenance difficult as the project grows
-Priority: Medium
-Proposed solution: database logic should be separated from service/ database queries should be placed in try/catch block





TaskItem:
-Status: Observed
-Evidence: Button label does not change when button is triggered, no function to trigger that
-Impact:
-Priority:
-Proposed solution: Write a function that triggers the button status to change