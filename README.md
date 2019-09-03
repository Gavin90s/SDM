# SDM
Code (Python2.7, TF1.4) of the Sequential Deep Matching (SDM) model for recommender system at Taobao.
Current version only contains the core code of our model. The processes of data processing and evaluation are executed on our internal cloud platform [ODPS](https://www.alibabacloud.com/campaign/10-year-anniversary).

## Datasets

**JD Dataset:** [raw data](https://drive.google.com/open?id=19PemKrhA8j-RZj0i20_j4ERcnzaxl5JZ), [train and test data](https://drive.google.com/open?id=1pam-_ojsKooRLVeOXEvbh3AwJ6S4IZ7B) in the paper (tfrecord).
The schema of raw data is shown in data/sample_data/.

**Taobao Dataset:** We will release the dataset after internal checking procedure if possible.


## Disclaimer
This is an implementation on experiment of offline JD dataset rather than the online official version.
There may be differences between results reported in the paper and the released one,
because the former one is achieved in distribution tensorflow on our internal deep learning platform [PAI](https://data.aliyun.com/product/learn).
