## Instructions for Dedicated Screen  

The 'Menu with Layers' grid holds menus on the system that have been customised. At the far right of the grid is a count of how many menu items there are based on the core screen (whether customised or not), in a column called Menu Count. Next to it is a column called Layer Variants, which holds the number of distinct customised versions there are. If this is more than one and you want all the screens to look and behave the same way, this indicates that some will be different.  

Clicking on any row in the upper grid populates the grid below it with all the matching menu items for the same base screen.  

In the 'Matching Menus' grid, the menus can be updated directly, or used to find the item in the main Menu Maintenance if preferred, which will be necessary for more than basic synchronising. The Path to Menu column shows where the particular menu can be found.  

Typically, this screen is useful if you have one screen behaving correctly, and others that should look and behave the same way. In which case, the steps to follow are:  

1. Find the menu item which is correct. Copy the complete data from the 'URL' column only (in the 'Matching Menus' grid), making sure it's the whole path, to the clipboard.  
2. For each menu item which you want to match it, in the same grid, paste the copied text into the 'URL' column.  
3. If the row you paste into has the 'System' column ticked, then also tick the 'Customise' column. Without that, that menu will remain read-only.  
4. If you have ticked 'Customise' for any rows, click 'Make Custom Menu', otherwise click 'Save'.  
5. Refresh the grid. If you have clicked 'Make Custom Menu' then check whether the URLs have updated correctly, because one step may not always work. If needed, paste the URLs again and click 'Save'.  
6. For each updated menu item, go to a freshly loaded home page and try clicking on that menu to check whether the correct customised version loads.  

Note: the dashboard may give an error when attempting to "Make Custom Menu" if the selected menu belongs to a module that Expo hasn't licensed. In that case, go to User Codes, bring up Code Type "Modules" and Code "UnLic" (Unlicensed Modules). In the Full Description field (which will be reached by clicking on the code in List view), the modules to exclude from any admin like this are a tilde-separated list (~), and if you add the one that gave the error, save, and refresh the dashboard, it should be removed. If new modules are licensed in future, they should be removed from this list.  
