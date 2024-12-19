# USER GUIDE: MULTIGROUPING IN ADOBE PREMIERE

This user guide teaches Assistant Editors how to create synced sequences with two or more cameras in Adobe Premiere. The process involves two steps:

1. Create sequences for each camera

2. Combine single camera sequences into a master sequence

> **NOTE**: This process works only with jam-synced cameras and audio.

## Create Single-Camera Sequences

Follow the steps below to create single-camera sequences. 

1. Copy a scene’s camera and audio clips to a single work bin. Label the bin with the scene name and date.

2. Sort the clips from each camera into assigned folders within the work bin. Label each folder with the camera name: **A-Camera**, **B-Camera**, and so on.

3. Move the field audio clips to a folder within the work bin. Label the folder **Audio**.

4. Label the field audio clips with a different color than the camera clips, if needed.
Premiere may have done this automatically.

5. Open the **A-Camera** and **Audio** folders. Highlight all the clips in both folders.

6. Right click the highlighted clips. Select **Create Multi-Cam Source Sequence** to open the Create Multi-Camera Source Sequence pop-up box.

   <figure style="text-align: center; margin-left: -20px;">
    <img src="userguide-photos/Fig%201.png" alt="Fig. 1: Timecode Settings for Single-Camera Sequence" width="700" style="display: block; margin: 0 auto;">
    <figcaption style="font-size: small; font-style: italic; color: darkblue; margin-top: 5px;">Fig. 1: Timecode Settings for Single-Camera Sequence</figcaption>
   </figure>

7. Select **Timecode** under **Synchronize Point**. See Fig. 1 above for this setting.

8. Select **Create single multicam source sequence** in the checkbox under **Timecode**. See Fig. 1 above for this setting.

   <figure style="text-align: center; margin-left: -20px;">
    <img src="userguide-photos/Fig%202.png" alt="Fig. 2: Move Source Clips Settings" width="700" style="display: block; margin: 0 auto;">
    <figcaption style="font-size: small; font-style: italic; color: darkblue; margin-top: 5px;">Fig. 2: Move Source Clips Settings</figcaption>
   </figure>

9. Uncheck the box labelled **Move source clips to Processed Clips bin**. See Fig. 2 above for this setting.

   <figure style="text-align: center; margin-left: -20px;">
    <img src="userguide-photos/Fig%203.png" alt="Fig. 3: Camera Name Settings" width="700" style="display: block; margin: 0 auto;">
    <figcaption style="font-size: small; font-style: italic; color: darkblue; margin-top: 5px;">Fig. 3: Camera Name Settings</figcaption>
   </figure>

10. Select **Enumerate Cameras** under **Camera Names**. See Fig. 3 above for this setting.

11. Use defaults for all other settings. See Fig. 4 below for full multi-camera settings. Double-check that your settings match those in Fig. 4.

   <figure style="text-align: center; margin-left: -20px;">
    <img src="userguide-photos/Fig%204.png" alt="Fig. 4: Full Multi-Camera Source Setings" width="700" style="display: block; margin: 0 auto;">
    <figcaption style="font-size: small; font-style: italic; color: darkblue; margin-top: 5px;">Fig. 4: Full Multi-Camera Source Setings</figcaption>
   </figure>

12. Click **OK** at the bottom of the pop-up box to create your A-Camera sequence.

13. Navigate back to your work bin and right click the A-Camera sequence.
Select **Open in Timeline** in the dropdown menu.

14. Scrub through the A-Camera sequence and fix any out-of-sync clips.

15. Relabel the A-Camera sequence as your master scene sequence. Save this sequence. You will add the remaining camera clips to this sequence in the next section.

16. Repeat Steps 5–14 with your B-Camera clips, and with any additional camera clips if applicable.
