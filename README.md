# BankNote-Authentication-Model
this is project made on No code machine learning platform name AWS SageMaker to validate a Bank Note

In the first image you can see I am adding data to my dataset and after that I have to name name my data Model.

![1](https://user-images.githubusercontent.com/83278567/200630323-1007a28b-8bc8-475e-9099-e969cc6f8ee8.png)

In the second image we have to chose the target column,the model you build pridicts values for that target columns. 
After that you have select the Model type, but in AWS sageMaker we don't have to worry it automatically recommends the model to analize your data,after selecting model type, you have to validate your data it might take several minutes depending upon the data, there is a option for preview model to preview your data before analysing the data.


![2](https://user-images.githubusercontent.com/83278567/200632424-cac628fc-f1cd-4a81-b6d5-8f0a51a05da4.png)

If you satisfied with your model you can click on build option.There are two option for building your model from which you can choose one option,first option is the quick build the second option is the standard build, it takes 2-15 min in quick build and 2-4 hours for standard build.
You cannot share the Model in quick build because it choose speed over accuracy, vice versa for standard build.
In the third image you can see the prediction and the the chart related to it  

![3](https://user-images.githubusercontent.com/83278567/200638776-648cc341-cb67-4b99-80d3-275ccec50269.png)

after making model we have option to test the model, for that I have test.csv file which is having all the test cases required

![4](https://user-images.githubusercontent.com/83278567/200641643-e2f60e81-e6bf-45eb-b222-622b1e41c462.png)

finally you can check your cases and see how many are fake and how many are original one (according to your model).
