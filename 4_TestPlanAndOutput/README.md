# Test Plan & Test Ouput

| **Test_ID** | **HLT ID** | **Description**                                              | **Exp_IN** | **Exp_OUT** | **Actual_Out** |**PASS/FAIL**  |    
|-------------|-----|--------------------------------------------------------------|------------|-------------|----------------|------------------|
|  T_01|H_01| To book a ticket, enter the required login information.| password| Successfully logined In | Successfully logined In| PASS |
|  T_02|H_01| When wrong password is entered| Password|  Entered Password is wrong | Entered Password is wrong | PASS |
|  T_03|H_02|Display the  details of movie available|  Enter choice | Display list | Display list | PASS |
|  T_04|H_02| Purchase a ticket for the movie that is now showing. | enter choice | ThankYou for Booking Ticket | ThankYou for Booking Ticket| PASS |
|  T_05|H_03|  Summary of a ticket for purchased movie| enter choice | Booking ID,Customer name,Show Name,Hallno,Price | Booking ID,Customer name,Show Name,Hallno,Price| PASS |
|  T_06|H_04| Cancel a ticket   |ID number|  Your ticket is cancelled | Your ticket is cancelled | PASS |
|  T_07|H_03| Change the price of ticket (only admin) | password| Please enter new price | Please enter new price   | PASS |
|  T_08|H_03| After logging in, you can change the ticket's price (only admin) | enter new price -price|Price Updated Successfully | Price Updated Successfully  | PASS |
|  T_09|H_03|When wrong password is entered while Changing the price of ticket (only admin) | password | Entered Password is wrong  |  Entered Password is wrong |PASS |
|  T_10|H_05|To view the reserved ticke |password| summary of tickeT|summary of ticket | PASS |
|  T_11|H_05|When the incorrect password is used to access the reserved ticket|Correct Password | Entered Password is wrongt|Entered Password is wrong | PASS |













