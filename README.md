# Devnagri-AI

First You will need to download the datasets using these steps:
1. Go to this page: http://workshop.colips.org/news2018/dataset.html
2. Under the “NEWS2018 DATASET_04” section, you will find Hindi mentioned.
3. Press the “request data” link to register &amp; get the download link.
4. After downloading the dataset, have a look at the Hindi training set and validation set
XML files.

Once you have the data with you extract it 
After extracting the data look for data ending with En-hi_trn.xml and En-hi_dev.xml

then run the "Devnagri Ai data prep" to convert it into json format.
After converting it into JSON format run the code "Devnagri model building" and save the model and then you can make the prediction from the that model by loading it.

There is a lot of scope for improvement
Some useful github repo that i have referred to 
1).https://bsantraigi.github.io/tutorial/2019/08/31/english-to-hindi-transliteration-using-seq2seq-model.html
This code is written in tensorflow 1.13/1.14 version but i found it useful in order to approrach the problem statement.
2).https://huggingface.co/anuragshas/en-hi-transliteration/blob/main/training_script.ipynb
This is the exact code that , i mean they have used the same dataset and they were able to get good accuracy as well.
