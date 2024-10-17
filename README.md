# Exercise 8: Basic Web Automation - Fill a Web Form

### Reg No : 212221040013

## AIM: 
  To automate filling a simple web form with user data and submit.

## Activities Required:
  1. Use Browser
  2. Type Into
  3. Click

## Procedure:
  1. Choose a simple web form on the internet (e.g., a contact form or demo form).
  
  2. Open UiPath Studio and create a new project called WebAutomation.
  
  3. In the **Activities Panel**, search for **Open Browser** and drag it into the **Designer Panel**.
  
  4. Set the **URL** property of **Use Browser** to the web form's URL (e.g., `"https://example.com/form"`).
  
  5. In the **Activities Panel**, search for **Type Into** and drag it into the **Use Browser** scope.
  
  6. Set the **Text** property of the **Type Into** activity to `"John Doe"` for the **Name** field of the form.
  
  7. Add another **Type Into** activity inside the **Open Browser** scope.
  
  8. Set the **Text** property of the second **Type Into** activity to `"john.doe@example.com"` for the **Email** field of the form.
  
  9. In the **Activities Panel**, search for **Click** and drag it inside the **Open Browser** scope.
  
  10. Use the **Click** activity to select the **Submit** button on the form.
  
  11. Save and Run the workflow.

## Workflow:
![image](https://github.com/user-attachments/assets/ec63076e-ef26-44e0-9a43-de7d8fd95647)

## Output:
![image](https://github.com/user-attachments/assets/50881892-e9b3-4bb1-b170-0572366870da)

## Result:
  Thus, the automation for filling a simple web form is implemented successfully.
