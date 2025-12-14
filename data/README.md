# Database Download Instructions:

Go to [kaggle](https://www.kaggle.com/competitions/titanic/overview). Once there, access the **Data** section and click the **Download All** button. Unzip the downloaded file into a folder named "data" in your local repository.

You can also run the **remote_download_competition** or **remote_download** script, depending on whether it's a competition or not. (Make sure you have the necessary libraries downloaded and that your Kaggle environment is configured. Also, verify that you have the API token in your **.kaggle** folder. If not, go to the directory indicated by the script's error code, create your **.kaggle** folder there, and copy your **kaggle.json** file into it.)

To use the **remote_download** script from the URL *https://www.kaggle.com/datasets/username/dataset_name* of your Kaggle dataset, copy the fragment username/dataset_name and replace it in the **KAGGLE_ID** variable.

To use the **remote_competition_download** script from the URL *https://www.kaggle.com/competitions/competition-name* of your Kaggle dataset, copy the fragment competition-name and replace it in the **KAGGLE_DATASET_ID** variable.

--