.. _tracing:
#################################################
**Tracing and Obtaining ICV**
#################################################

*example particuipant 8375

1. Log into the PC in the KK lab with the Wacom tablet
  
- Specifically log in as knaclab

2. Open the Analyze 11.0 application

3. Click the ICV tab

4. Go to file --> load as --> File --> kenrod --> study-jlbs (login if needed) --> Wave3 --> MRI --> T1 --> freesurfer --> 3tb8375 --> MPRAGE2100_SAG.nii--> Open

5. Calculate it

6. Pad/Orient --> change orientation input to transverse --> load

7. Right click the new scan that is surrounded by a red box --> Rename -->  8375

Now the scan has been loaded and is ready to be traced
#################################################

1. Go to the kenrod drive and follow this path to the Study 1 HC_ICV Data file

- study-jlbs --> Wave1 --> MRI --> HRT2 --> Analyze --> JLBS --> data

2. Add Study ID and MRI ID(get study ID from study-jlbs --> Wave3 --> MRI --> T1 --> freesurfer --> documentation --> FreeSurfer_Tracking_w3.xlsw)

- Keep this file open

3. Go back to Analyze

- Single click on the scan of interest, a red box should appear around that scan

  - Click the ROI button

4. Click the magnifying glass with the "+" sign twice to zoom in (maximize the viewer if needed with the square box in the upper right-hand corner next to the "X").

5. Go to Generate --> orientation --> transverse --> Done

6. Now you need to identify the 1st slice that shows the most superior part of the brain. Then you need to identify the most inferior part of the cerebellum. Here's how you do this

- Tools --> Ortho Review --> select "Linked Cursor"

  - Look at the transverse slice (left image) while moving the green line up in the coronal view (middle image) until you see the 1st most superior slice in the axial image. Click on the green line and hold while moving the mouse to make these adjustments. Basically, keep an eye out for the first transverse slice where you see any cortex. For a reference, see the "Study 1HC_ICV Data.xlsx" file where this has already been determined for other scans to get an idea of what to look for.

  - Once this has been identified, mark the number in the transverse panel into the excel file in the D column marked "LAST"

7. Now you need to identify the first slice where you can see the cerebellum. Head over to the right panel and move the green line to where it is below the cerebellum. There is a slide bar under the number for the sagittal pane. Use this slide bar to make sure that the green line is below every slice of the cerebellum. This green line should never go through any part of the cerebellum as you go from slice to slice on the sagittal plane.

- Once you have identified this green line position, mark the number in the transverse panel into the excel file in the C column marked "FIRST"

8. Close the ortho review

9. Calculate the range

- After typing in the values for the FIRST, and LAST, MIDDLE will be calculated automatically. Get this number and subtract 48 from it. Example. For 8375 the MIDDLE was calculated to be 157. Now subtract 48 from that value to get 109. This value is the lower value in your range. To get the upper value in the range add 48 to that MIDDLE number. Example. For 8375, the MIDDLE was calculated to be 157. So now add 48 to get 205.

    - For this example, your range would be 10-205    
    
    - Type that range into the range column in column F

10. Compare this range to the Wavel range, see if it's similar. If not investigate further by opening the Wave1 scan and assess the situation.

11. View --> Objects --> Add Object (click once) --> change the name to "ICV" --> click the tab button on the keyboard --> Done

12. Generate --> Slice...

- Slice(1)

- Increment(2)

- Number(1)

- Click enter on the keyboard

  - Done

13. Now on the bottom right of the screen next to the slide bar there is a number. Change this to the value of the highest number in your range. 

- In 8375, this would be 205

14. Near the bottom right of the screen is a small section that says "Object to Define:" Set this to ICV

15. Click the auto trace icon (oval with a horizontal rectangle below it)

- Click somewhere on the bone area on the scan

- Slide the left scroll bar until the red line has correctly followed the skill

- Click Apply

16. Next, click the "show --> "button. This advances to the next slice. Repeat the process from XV a-c.

17. Sometimes you need to make edits if the red line does not properly encase the skull. Specifically, one thing that needs to be done is to trim off the ears and to smooth out rough edges. We want this line following the bone as much as possible while ignoring the ears.

- Click edit

- Use the Wacom pen to adjust parts of the red line

- Once edits are made re-click the auto trace icon

18. Make sure you have 9 traced slices

19. Go to File --> save object map

- Go to: study-jlbs --> Wave1 --> MRI --> HRT2 --> Analyze --> JLBS --> ICV --> Save

20. Click the Samp Opts icon and make sure only ICV is checked in the upper right box

- Sample Images

  - Make sure there are 9 slices

- Save in same ICV folder 

  - Done

21. Exit out by clicking the X in the upper right hand corner

- Exit

22. In the analyze program, click the X in the upper right hand corner

- Exit

- **DO NOT UPLOAD AND EXIT**








