# computer-vision-master-project-2022-2023

### Models
Trained models can be found on the following link:
https://drive.google.com/drive/folders/1-5sNbEa56SWxYy_9pjYhpF_dBjZig87D?usp=sharing

### Demo

To run the demo:
1) Download one of the pre-trained models from the link above.
2) Paste the model in one of the folders under "src/models/checkpoints/".
3) Open "demo.ipynb" notebook and modify the constant "CHECKPOINT_PATH" to point to the model you want to use.
4) Run the whole notebook. In the last three cells you can:
   * See the number of available test images.
   * Select and visualize the image to predict by modifying the variable "pred_index".
   * Predict the image class and compare with the ground truth.

### Training & evaluation

If you wish to train or evaluate the models yourself, beware that the notebooks are written to run on Google
Colab and require access to a Google Drive folder. The easiest way to run them is to import them into Google Colab\
and modify the paths (e.g. "/content/drive/...") to point to your Google Drive folder.
