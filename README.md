# CSE237-project: Bear Banks

**This project was created as part of the Programming Tools and Techniques course at Washington University.**

**Group members**: Ian Youth; Jessica Wu; Jack Cho; Jaehwi Park

**Program Name**: Bear Banks

**Coding Language**: Java 

**IDE**: Eclipse

**Interface**: Text-based; command line application

**Overarching Project Summary**: "Bear Banks" simulates an ATM machine with which customers and employees can interact and execute various bank-related tasks. Our **target audience** would theoretically be (1) people who would like to bank with Bear Banks, (2) people who work for Bear Banks (limited functionality as of 04/28/2021).

**Key Features**: Bear Banks does anything that an ATM might normally do. The following is a working list of Bear Banks' capabilities:
    
    CUSTOMERS may:
        1.) Open an account
        
        2.) Set credentials (name and PIN)
                        
        3.) View their account balance
        
        4.) Withdraw cash from their account
        
        5.) Deposit cash to their account
        
        6.) “Print” a receipt of their transaction history (after withdrawing/depositing cash)
                
        7.) View their account balance in terms of WashU meal points

        8.) View WashU-related apparel that they can purchase with their current balance
        
    EMPLOYEES may:
        1.) Lock the ATM for use
                        
        2.) Do anything that a customer might normally do under the customer interface (see above)

**How to Run This Program**

    1.) After cloning this repository on your personal computer, open a Command Prompt and 
        navigate to the folder that contains "runBearBanks.sh".

    2.) Run "runBearBanks.sh" by typing "./runBearBanks.sh".

        A.) If an error is encountered, it might be due to how Windows treats newline characters.
            
        B.) To fix this error, type "dos2unix runBearBanks.sh"; afterwards, type "./runBearBanks.sh" 
            again.
