# GymOffice.StaffLogin 
This is for temporary app setting to test and setup login in the admin app

#DONE:
- Standard Identity UI
- DB contains 4 roles: Customer, Admin, Receptionist, Coach. 
- Customers cannot log in
- All other roles can login and watch all the pages. The Register a coach page is visible for them but the access is denied there
- Admin has a right to use the register page where he can register a coach. 
- EmailSender added with SendGrid key in the Windows secret area. This allows user to confirm email and reset password

#TODO:
- Add external login services (Facebook, Google). But there is basic external app functional (the user can install an app at a mobile and enter the code)
