# Setting up the dashboard  

### Option 1 – Solution  

Install the MenuMng Kinetic solution file as usual.  

This contains the Kinetic Dashboard, two BAQs required for it (one updateable), and the User Code Type with one User Code. Note that if you have a User Code with CodeTypeID of 'Modules' or CodeID of 'UnLic', better to use option two and adapt the BAQs etc to suit.  

### Option 2 – Components  

Import the two BAQs and the Kinetic App manually. (Not everybody seems to know that there are Import/Export items in the menus of BAQ Designer and Application Studio, but they are there and handy).  

Create a User Code Type of 'Modules', and within it a User Code with ID 'UnLic'. The description for this can be something along the lines of 'Unlicensed Module Codes'.  

If you choose to use different Code Type or Code ID, you will need to change both BAQs, specifically the table criteria on the UDCodes table.  

### Other necessary steps  

If you already know some module codes you don't use, you can add them, separated by tilde characters ('~') in the Long Description of the 'UnLic' User Code. If not, see the user instructions for adding them as invalid modules cause error messages when using the dashboard.  

Unless you want to run the dashboard only by previewing from Application Studio, add a menu item for it somewhere of your choice.  

I also advise applying a security group to both BAQs and the menu item, usually so that only Security Admin users can access it.  
