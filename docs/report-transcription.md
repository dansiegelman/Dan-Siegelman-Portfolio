## REPORT: AI TRANSCRIPTION FOR PROBLEM AUDIO

This report compares how three AI-based transcription models, Premiere Speech-To-Text, Trint, and Whisper, perform with clean audio and problem audio.

**“Clean audio”** refers to high-quality audio with clear speech. **“Problem audio”** refers to low-quality audio with clarity issues like background noise and speaker accents.

For this report, each model transcribed a clean audio file and a problem audio file, both three minutes in length:

- **CLEAN AUDIO FILE:** [Barack Obama's 2004 Speech](https://www.youtube.com/watch?v=ueMNqdB1QIE) at the Democratic National Convention. The file contains clear audio with little background noise. Senator Obama (he was not yet President) speaks with clear rhythm and diction.
  
- **PROBLEM AUDIO FILE:** [Theodore Roosevelt's 1912 Speech](https://www.youtube.com/watch?v=uhlzdjPGxrs) at Carnegie Hall. President Roosevelt’s Mid-Atlantic accent differs starkly from modern American English. Artifacts and background noise further obscure the President’s voice, making the speech difficult to understand.

The report assesses model performances by comparing the number of mistakes in each model’s transcripts. In this case, **mistakes** include misspelled words, missing or extra words, and grammatical errors.

The report’s conclusion offers insights on using each model.

### Premiere Speech-To-Text

Native to Adobe Premiere 15.4 and later, [Premiere Speech-To-Text](https://www.adobe.com/products/premiere/speech-to-text.html) **(PSTT)** allows users to transcribe media directly within the program. According to Adobe, the model transcribes English-language audio with high accuracy.

### Premiere Speech-To-Text Results

PSTT’s Obama transcript contains **one mistake**: a misplaced question mark at the end of the final word. Otherwise, PSTT correctly transcribed every word in the file.

In contrast, PSTT’s Roosevelt transcript contains over **150 mistakes**. Every sentence contains at least one major mistake. Many sentences contain more incorrect words than correct words. See examples below:

>**Correct Transcription:** "I believe they are. My opponents do not."
>
>**PSTT Transcription:** "I believe. Right? I have promised to them."

>**Correct Transcription:** "at the cost of the whirlwind of the red terror"
>
>**PSTT Transcription:** "the gospel, the borrowing, the political"

PSTT’s Roosevelt transcript lacks any coherence, highlighting the model’s apparent struggle to transcribe problem audio.

### Trint

Popular with video professionals, Trint offers paid transcription services for various media formats. The company claims its transcription model performs with up to 99% accuracy.


