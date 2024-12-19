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


13. Click **OK** at the bottom of the pop-up box to create your A-Camera sequence.

14. Navigate back to your work bin and right click the A-Camera sequence.
Select **Open in Timeline** in the dropdown menu.

15. Scrub through the A-Camera sequence and fix any out-of-sync clips.

16. Relabel the A-Camera sequence as your master scene sequence. Save this sequence. You will add the remaining camera clips to this sequence in the next section.

17. Repeat Steps 5–14 with your B-Camera clips, and with any additional camera clips if applicable.

## Create Multi-Camera Sequence

Follow the steps below to combine your single-camera sequences into a multi-camera master sequence.

1. Open your **B-Camera** sequence in the timeline. Highlight the camera clips on V1. Leave the audio unselected.

2. Move the playhead to the first frame of the timeline. Write down the timecode displayed in the top left of the timeline window. See Fig. 5 below for an example.

   <figure style="text-align: center; margin-left: -20px;">
    <img src="userguide-photos/Fig%205.png" alt="Fig. 5: Premiere Sequence Timecode" width="700" style="display: block; margin: 0 auto;">
    <figcaption style="font-size: small; font-style: italic; color: darkblue; margin-top: 5px;">Fig. 5: Premiere Sequence Timecode</figcaption>
   </figure>

3. Copy the B-Camera clips from the timeline by typing **Command + C** (Mac) or **Ctrl + C** (Windows).

4. Open your master sequence in the timeline. (This is the A-Camera master sequence you saved in Step 15 of the Previous Section.)

5. Right click below the master sequence timecode and select **Add Tracks...**

   In the Add Tracks pop-up box, add a new video track (V2) to the master sequence.

   Click **OK** to save and exit. See Fig. 6 below for these settings.

   <figure style="text-align: center; margin-left: -20px;">
    <img src="userguide-photos/Fig%206.png" alt="Fig. 6: Add Tracks Settings" width="700" style="display: block; margin: 0 auto;">
    <figcaption style="font-size: small; font-style: italic; color: darkblue; margin-top: 5px;">Fig. 6: Add Tracks Settings</figcaption>
   </figure>

7. Move the master sequence playhead to the timecode you wrote down in Step 2.

8. Select video track V2 on the left of the timeline, then paste the B-Camera clips to V2.

9. Sync the B-Camera clips to the A-Camera and audio. You may only need to move a few clips, depending on the jam sync.

10. Repeat Steps 1–8 for any additional cameras, if applicable.

11. Zoom in fully on your master sequence by clicking and dragging the zoom slider below the timeline. See Fig. 7 below.

   <figure style="text-align: center; margin-left: -20px;">
    <img src="userguide-photos/Fig%207.png" alt="Fig. 7: Timeline Zoom Slider" width="700" style="display: block; margin: 0 auto;">
    <figcaption style="font-size: small; font-style: italic; color: darkblue; margin-top: 5px;">Timeline Zoom Slider</figcaption>
   </figure>

11. Carefully scrub through your master sequence and delete all camera audio, leaving only external field audio. Camera audio may appear in single-frame gaps between two field audio clips. See Fig. 8 below for an example.

   

