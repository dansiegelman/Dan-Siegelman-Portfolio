# REPORT: AI TRANSCRIPTION FOR PROBLEM AUDIO

This report compares how three AI-based transcription models, Premiere Speech-To-Text, Trint, and Whisper, perform with clean audio and problem audio.

**“Clean audio”** refers to high-quality audio with clear speech. **“Problem audio”** refers to low-quality audio with clarity issues like background noise and speaker accents.

For this report, each model transcribed a clean audio file and a problem audio file, both three minutes in length:

- **CLEAN AUDIO FILE:** [Barack Obama's 2004 Speech](https://www.youtube.com/watch?v=ueMNqdB1QIE) at the Democratic National Convention. The file contains clear audio with little background noise. Senator Obama (he was not yet President) speaks with clear rhythm and diction.
  
- **PROBLEM AUDIO FILE:** [Theodore Roosevelt's 1912 Speech](https://www.youtube.com/watch?v=uhlzdjPGxrs) at Carnegie Hall. President Roosevelt’s Mid-Atlantic accent differs starkly from modern American English. Artifacts and background noise further obscure the President’s voice, making the speech difficult to understand.

The report assesses model performances by comparing the number of mistakes in each model’s transcripts. In this case, **mistakes** include misspelled words, missing or extra words, and grammatical errors.

The report’s conclusion offers insights on using each model.

## Premiere Speech-To-Text

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

## Trint

Popular with video professionals, [Trint](https://trint.com/) offers paid transcription services for various media formats. The company claims its transcription model performs with up to 99% accuracy.

### Trint Results

Trint’s Obama transcript contains **five mistakes**. However, the mistakes include only small grammatical errors related to person and tense. Trint avoided making larger mistakes like omitting words. While Trint made more mistakes than PSTT, Trint’s Obama transcript is still fully usable.

In contrast, Trint’s Roosevelt transcript contains **over 100 mistakes**. While the transcript improves slightly on PSTT’s version, it suffers from the same issue: every sentence contains major mistakes, which occur frequently enough to cause incoherence. Trint, like PSTT, appears to struggle badly with problem audio.

## Whisper by OpenAI

In 2022, OpenAI released [Whisper](https://openai.com/index/whisper/), an open-source speech recognition model. OpenAI claims that Whisper “approaches human level robustness and accuracy on English speech recognition.”

### Whipser Results 

Whisper’s Obama transcript contains **one mistake**: it misspells “Barack” as “Barak.” Otherwise, Whisper’s transcript captures the speech perfectly.

Whisper’s Roosevelt transcript contains **11 mistakes**. Though not quite perfect, the transcript successfully captures the President’s speech. Its language flows clearly and most sentences contain no mistakes. Whisper correctly transcribed phrases that the first two models struggled with, such as “aesthetic pleasure.” It even succeeded with obscure proper nouns like “Bourbon” and “Robespierre,” which the first two models missed.

## Conclusion

Of the three transcription models, Whisper displayed the best performance with problem audio by a wide margin. Whisper and PSTT performed equally well with clean audio, while Trint’s clean audio transcript contained minor mistakes.

Though further testing can reveal more about the models, this report offers some tentative insights:
- Users can rely on Whisper to transcribe problem audio.
- Whisper costs no money to use and boasts transcription abilities comparable—or even superior—to paid transcription services. Therefore, users may have little reason to pay for Trint or similar platforms.
- Premiere users can transcribe clean audio with the program’s native Speech-To-Text model.
- Premiere allows users to import third-party transcripts. Therefore, Premiere users can transcribe problem audio with Whisper, then import the Whisper transcripts into Premiere.

## Transcripts 

Click the links below to view each model's full transcripts: 

[Obama Speech - PSTT Transcript](https://dansiegelman.github.io/Dan-Siegelman-Portfolio/report-transcripts/Obama-Speech-PSTT-Transcript)

[Obama Speech - Trint Transcript](https://dansiegelman.github.io/Dan-Siegelman-Portfolio/report-transcripts/Obama-Speech-Trint-Transcript)

[Obama Speech - Whisper Transcript](https://dansiegelman.github.io/Dan-Siegelman-Portfolio/report-transcripts/Obama-Speech-Whisper-Transcript)

[Roosevelt Speech - PSTT Transcript](https://dansiegelman.github.io/Dan-Siegelman-Portfolio/report-transcripts/Roosevelt-Speech-PSTT-Transcript)

[Roosevelt Speech - Trint Transcript](https://dansiegelman.github.io/Dan-Siegelman-Portfolio/report-transcripts/Roosevelt-Speech-Trint-Transcript)

[Roosevelt Speech - Whisper Transcript](https://dansiegelman.github.io/Dan-Siegelman-Portfolio/report-transcripts/Roosevelt-Speech-Whisper-Transcript)



