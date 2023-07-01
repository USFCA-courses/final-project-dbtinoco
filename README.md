# MSDS 631 Final Project

Adam Ansari, Daniel Tinoco, Yusong Wang

## Running the Notebook
The following notebook details the process of creating a Huggingface style dataset of audio samples with their respective text and creating speaker embeddings using Speechbrain's VoxCeleb model. This is then passed into Microsoft's SpeechT5 model for generating speech given some text input.

We recommend running this notebook on Google Colab with NVIDIA A100. During testing, we used approximately 200 computation units for 158 audio samples and 400 epochs. It should be mentioned that we ran this multiple times, so your units may vary. 10 to 20 units should suffice for a single run of the notebook with a similar data size.

See the first cell of the notebook for the colab version of the notebook.

### Downloading the files from Google Drive

We used Google Drive with Colab to load in all our data. You can access the Drive at the below link. You will need to change the Pathing to your Drive paths. If you do not wish to use Colab or Drive you can instead download the data available in this repo. In addition at each of the core sections we pickled the final output and loaded in these pickles at the start of the next step. If you wish to start from any of the major sections you can instead load in the pickle files. Each major sections starts with code to load in these files and assumes you are doing this. As with all the paths in the notebooks they need to be changed to match yours. 

https://drive.google.com/drive/folders/1T-hKJVBv9Ww4RPknT5WCwlVWbGKVHfwn?usp=sharing

## Viewing the PowerPoint

To view the slides, click here: https://docs.google.com/presentation/d/1W0wwmMcyRBXhGJQQ8YxpH1YOAs_UpkShZbJ1xXalUkg/edit?usp=sharing. A PDF version of the slides is provided in the repo but the PDF does not have sound file output at the end. For the best experience we reccomend going through the slides at the link above. 