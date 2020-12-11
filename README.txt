Step 1. Close ACT and Extract the files to Your Overlay Plugin's Resources' image Folder. Example: C:\Program Files (x86)\Advanced Combat Tracker\OverlayPlugin-0.3.3.9-x64-full\resources\images
Step 2. Overwrite the files obviously that need to be. You now have RDM and SAM image files for the three types.
Step 3. Next you need to look in ACT and see which Rainbow Mage Html Parsing file you were using. and Open it. (See Example Image 1 in archive.)
Step 4. Find the lines that read #combatantTableBody .(job) td, The (job)is the class or job that is showing. Some of these HTML files will have them broken up by role. Place RDM and SAM in the DPS section of this.
Step 5. To do that you will need to add the following two lines... (See Example Image 2 in archive for visual)
===============================
Start Copy Text
===============================
#combatantTableBody .Sam td,
#combatantTableBody .Rdm td,
===============================
End Copy Text
===============================
Step 6. Save and Close the Html file and start ACT.
Step 7. Profit
