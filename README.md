# AICPS-Final-Project

You can access to the AudioASR model through this link: [visual_asr.pth - Google Drive](https://drive.google.com/file/d/1nvzG-C0gxnl4axXGmajkDXSClBfBSaMD/view?usp=sharing). Once you have pull all the code from the GitHub, download this model and put it inside the inference folder. It was unable to be uploaded to GitHub due to its size. Then run the inference file, which you can directly observe the pipeline, and generate output of specific input video.

## Inference
For the model inference, there is a notebook file under the folder inference, called inference. It consists of six parts. 

First run the **set up environment**, it will directly help you to download all the required packages and set up the environment needed for this problem. It is recommended to run this part under your own virtual environment. 

Then, run through **Visual ASR, Audio ASR** and **Fusion** parts, which will get you really for those inference functions.

The part **Inference** is straightforward. By modifying name of the video, you can generate the transcription of any video you want in the dataset. You can see the name of the datasets from the folder data/video.

The part **Generate Transcript for All Files** is running the inference parts iteratively on all the videos. This will also generate the all the transcription from different model and save them into corresponding folder. The generated results are accessible  from the corresponding folder in data folder. 10 samples of each scenario of the dataset are being selected and placed in the video folder.

## Evaluation
The evaluation is a notebook also in inference folder. It evaluates the performance of baselines from the file generated in inference step.