# Module 1 - Lab 2 - Exercise 1 - Configure Self-service password reset (SSPR) for user accounts in Azure AD


### Scenario

The Help Desk has indicated that a large number of support tickets are related to password resets. You have been asked to setup a way for users to reset their password on their own. 



#### Task 1: self-service password reset

1.  Switch to **LON-CL1** and sign in as **Adatum\\Administrator** with the password **Pa55w.rd**.

2.  On the task bar select **Microsoft Edge**, open Azure by going to `https:/portal.azure.com/`.  Login as Holly Dickson from the previous lab. Navigate to **Azure Active Directory**
    

3.  In the navigation pane under **Manage** select **Users**, then select **Password reset**.

4.  In the **Password reset | Properties** window, select **All** to enable self-service password reset to all users. Select **Save**.

5.  On the **Password reset | Properties** blade, select **Authentication methods**.

6.  For the methods available to users, ensure that **Mobile Phone (SMS only)** and
    **Email** are selected, and then select **Security Questions**.

7.  For the **Number of questions required to register**, select **3**.

8.  For the **Number of questions required to reset**, select **3**.

9.  In the **Select security questions** section, select **No security questions configured**, then select **Predefined**. Select three questions of your choice, and then select **OK** twice.

10. Select **Save**.

11. Select **Registration** Select **No** for **Require users to register when signing in**, and the select **Save**.


#### Task 2: Test self-service password reset

1.   In Microsoft Edge at the upper right of the page, select your account name, and then select
    **Sign in with a different account**. 

2.  Sign in as **AllanD@yourtenant.onmicrosoft.com** with the password that was assigned by your lab hosting service.   

3.  Browse to `https://myapps.microsoft.com`. 

4.  At the **More information required** screen, click **Next**.

5.  Enter your phone number and choose **text** or **call me** then click **Next**.

6.  Enter the code you receive and click **Next**.

7.  Click **Next** and then **Done**.

8.  Go to `https://aka.ms/sspr` and enter the username for Alan.

9.  Complete the Captcha and click **Next**.

10. Enter your phone number and then click **Text**.

11. Enter the verification code you received and then click **Next**.

12. Enter a **new password** and click **Finish**.


    _Note: If prompted to use an email you will need to use an e-mail address other than the tenant domain 
    provided for this lab. If one is not available, you can skip the e-mail 
    verification and continue with the next step. Sign in to your email account, read the code, type it in the verification field, and then select **Verify**. 
    
    _Note: If you don’t find a message with a code in your inbox, check the junk folder.


# Continue to Exercise 2
