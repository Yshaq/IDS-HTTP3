This Folder contains the following ipynb notebook files:
1. Feature selection - Contains Anova Feature Selection algorithm used to rank features
2. Files for training the model and printing metric on data from caddy, cloudflare, h20, litespeed, nginx servers
3. N-Class classification notebook for comparing multiple ML Models.

The 'h23q-data' Folder contains pre-processed flows from the H23Q Dataset.
The CSV files were produced after Flow Generation and Feature Extraction.
The files contain 80+ statistical time based Features.
The original H23Q Dataset (Packet Capture Files) is available at https://icsdweb.aegean.gr/awid/other-datasets/H23Q

The 'h23q-data' Folder also contains '*.pth' files which are trained models. Code is included in the training notebooks to load this model.
After loading, this model can be used without further training.
Code needed to train the model from scratch is also included in the notebooks.

We conducted our experiments on Google Colab. The code required to mount the Drive is included in the notebook. Just paste the h23q-data folder in the appropriate directory.
The code may also be run locally, please make the required changes accordingly.

Regards,
A V Vysakh & Yash Raj
Dept. of Computer Science and Engineering
IIT (BHU) Varanasi