# sagemaker-r-test-data
Repository to store test data for [sagemaker-r-sdk](https://github.com/DyfanJones/sagemaker-r-sdk). This is to reduce the size of the R package so that it can meet CRAN size requirements of 5MB ([CRAN policies](https://cran.r-project.org/web/packages/policies.html)).

In general R6sagemaker will use testing data directly from [sagemaker-python-sdk](https://github.com/aws/sagemaker-python-sdk). R equivalents will only be stored here if R doesn't have a native way to read test data from sagemaker-python-sdk.
