# Showing-Blocks-based-on-a-members-Group
Show blocks to the members with the correct permissions ( Hides blocks for members without permissions ) 

Learn how to show blocks based on a members group that you have set inside of your CRM and store permissions inside the SV Website Builder.

Watch the How to video here https://youtu.be/LU0LUqsbBuU



HOW TO ( More In-depth )
How to Showcase Blocks to members with the Right permissions.



1. Create your Group Names under Contacts



2. Add yourself to the selected groups wanted.



3. Run the Developer Tool Command for the Live Website. 



4.  Locate ( Under Sources ) The code below 

WebPlatform.Members = WebPlatform.Members || {};

              WebPlatform.Members.current = {"lastLogin":1651103647236,"approved":true,"groupIds":[9,14,23],"name"



5. Find the Numbers related to the member groups as you will need to add these into the code. ( Highlighted in blue above, make sure to match them to the correct group ) 



6. Go to the block you want to show/hide to certain member groups and set a custom class to the block.



7. Inside the Page Head Markup code add your Custom Block Class names ( Ex: .course-1, .course-2, .course-3)



8. Inside Page Body Markup Change  the (1) after .indexOF to the number of the member group wanted



9. Change (".course-1") to whatever the class name you set the block as Ex: (".myclassname")  



10. Save all your changes & preview your site logged in & Logged out to see how the blocks only show when you have the right permissions set. 



