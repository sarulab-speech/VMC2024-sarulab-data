# VMC2024-sarulab-data

In VoiceMos Challenge 20224, We constructed our original data which follows the similar protocol as the track 1 data.
Specifically, We frist performed EDA on the track 1 validation filelist.
From the EDA, it was assumed that the top half systems of BVCC dataset was used for this challenge.
Based on this assumption, We also selected top half systems of BVCC dataset and conducted subjective evaluation of natularlness of speech.
The number of listeners is 304 and we conducted the test on [Prolific](https://www.prolific.com/)

# Dataset format

The result of subjectvie evaluation is available on file named `VMC2024_MOS` 

The data is fomatted in the following form
systemID/systemID-uttranceID.wav MOS 95%ConfidenceInterval (answer by each listner : total listerns of the utterance)

```
sys00691/sys00691-utt00e6ae6.wav 3.375000 0.886734 (1:0,2:2,3:2,4:3,5:1,total: 8)
sys00691/sys00691-utt04097bc.wav 2.500000 0.631972 (1:1,2:2,3:5,4:0,5:0,total: 8)
sys00691/sys00691-utt0682e32.wav 4.000000 0.631972 (1:0,2:0,3:2,4:4,5:2,total: 8)
sys00691/sys00691-utt12c197c.wav 3.375000 0.765900 (1:0,2:1,3:4,4:2,5:1,total: 8)
```