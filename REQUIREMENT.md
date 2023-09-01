In the context of a waterfall model, the development process follows a sequential structure where each phase must be completed before moving on to the next. Here are the functional requirements for an Online Banking System based on the waterfall model:

# 1. Requirement Analysis Phase:
   - *User Authentication:*
     - User registration<br>
     <br>
       Users should be able to register for online banking and create a profile.
       The users must enter their personal details along with email id and mobile number for registration.
       the user must enter a password and confirm it once more.
       At the same time the users create theit profile.
     - Link your bank account
       Users must be able to link their online banking profile to the registered bank account.
       Users must enter their permanent account number in order to link their account.
       Users must confirm the linking through the registered mail id.
       Users must be able to link their multiple bank accounts to their online profile.
     - *User login*
     - Registered user must login into the account before doing any further actions.
       Registered user must be able to change password.
       Users must use multi-factor authentication involving PASSWORD AND OTP.
     - *Change Password*
       Allow the registered users to change password in case they forget the password durign LOGIN.
       Allow the users to change the password through a registered e-mail.
       Allow users to solve the captcha during authentication to receive an e mail.
       
   - *User Profiles:
      - *Manage profile*
        Users must be able to add a secondary e-mail id as recovery mail.
        Users must be able to set language preferences for the website.
        Users must be able tio access required detailsrelated to the bank account whenever needed.
     
      - *Edit Profile*
        Allow users to change their registered address , phone number.
        Enable users to change their username if it is unique.
        
     

# 2. System Design Phase:
   - *User Interface:*
      - Dashboard:
        The user should be able to access all the broad features of the website using the dashboard.
        The user should have aaccess to various elements like summary of recent transactions and account balances.
        The user should also have the option to custokmize the layout out of the several available options.
        The user should be able to choose from various options available like cards,accounts,loans,insurance,Forex etc.
      - *Account Management:* Enable users to create new accounts, view existing accounts, and link external accounts.
      - *Transaction Tracking:* Provide a dashboard for users to monitor their transaction history, including deposits, withdrawals, and transfers.

*3. Implementation Phase:*
   - *Security Measures:* Implement encryption protocols, secure socket layer (SSL) for data transmission, and secure password storage.
   - *User Roles:* Define roles such as customer, administrator, and support staff, each with specific access levels and permissions.
   - *Transaction Processing:* Develop a real-time transaction processing system that handles transfers, payments, and account updates accurately.

*4. Testing Phase:*
   - *Usability Testing:* Verify the user interface for ease of use, responsiveness, and compatibility across various devices and browsers.
   - *Functional Testing:* Validate all features including login, account creation, fund transfers, bill payments, and user profile management.
   - *Security Testing:* Conduct thorough security assessments to identify and address vulnerabilities, ensuring data protection.

*5. Deployment Phase:*
   - *Server Infrastructure:* Set up and configure the necessary servers, databases, and network components to host the online banking system.
   - *Data Migration:* Safely transfer existing customer data to the new system without data loss or corruption.
   - *User Training:* Provide user documentation and training resources to help customers understand and navigate the new system.

*6. Maintenance Phase:*
   - *Bug Fixes:* Address and resolve any issues, bugs, or glitches identified post-deployment.
   - *Regular Updates:* Implement updates to enhance security, fix vulnerabilities, and introduce new features based on customer feedback.
   - *User Support:* Provide ongoing customer support through various channels such as online help, chat, or a dedicated support center.

*7. Documentation Phase:*
   - *User Manuals:* Create comprehensive user manuals and guides for customers to understand the system's features and functionalities.
   - *Technical Documentation:* Prepare detailed technical documentation for developers, administrators, and support staff.

*8. Project Closure:*
   - *Evaluation:*
     Assess the success of the project in meeting the defined functional requirements and business goals.
   - *Lessons Learned:* Document the lessons learned during the development process for future projects.
   - *Handover:* Transition the system to operational teams and provide necessary training for system administrators and support staff.
*9. . Customer Support:*
  - Users should be able to resolve their queries and get necessaryu supprot from customer support portal.
  - User must have access to all the centralized bank department info, phone numbers and email ids in the customer support portal.
  - Users must be able to use the option of loive chat in case they face any difficulty related to their transactions.



In the waterfall model, each phase must be completed before moving to the next one, making it crucial to thoroughly define and document the functional requirements at the beginning to ensure a successful project outcome.
