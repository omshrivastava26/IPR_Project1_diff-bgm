# IPR_Project1_diff-bgm
Official github repo : [https://github.com/sizhelee/Diff-BGM](url)
#1.Implementation 
pip install -r requirements.txt
pip install -e diffbgm
pip install -e diffbgm/mir_eval (This file is not present in official github repo, I found it here) : [https://github.com/aik2mlj/polyffusion](url)
#2. Training
Preparations
The extracted features of the dataset POP909 can be accessed here. Please put it under /data/ after extraction.

The extracted features of the dataset BGM909 can be accessed [here](https://yukisaki-my.sharepoint.com/personal/aik2_yukisaki_io/_layouts/15/onedrive.aspx?id=%2Fpersonal%2Faik2%5Fyukisaki%5Fio%2FDocuments%2FShare%2Fpolyffusion%2FPOP909%5F4%5Fbin%5Fpnt%5F8bar%2Ezip&parent=%2Fpersonal%2Faik2%5Fyukisaki%5Fio%2FDocuments%2FShare%2Fpolyffusion&ga=1). Please put them under /data/bgm909/ after extraction. We use VideoCLIP to extract the video feature, use BLIP to gain the video caption then use Bert-base-uncased as the language encoder and use TransNetV2 to capture the shot.
We also provide the original captions here.

The needed pre-trained models for training can be accessed here. Please put them under /pretrained/ after extraction. The split of the dataset can be find here.
