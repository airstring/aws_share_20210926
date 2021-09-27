# aws_share_20210926
20210926杨浦区朗廷酒店线下aws边缘产品分享会实验

实操：



lab02
CloudFormation创建后的输出如下：
![image](https://user-images.githubusercontent.com/26688391/134867502-546f00a9-b8c6-4b4c-937a-436c71170295.png)
第一四行与cdn CloudFront有关系
第二三行与Cognito有关系
第五行是个私有s3
第六行是个公有s3


![image](https://user-images.githubusercontent.com/26688391/134868784-a5d3d941-aaf8-44bc-a489-9bca7c36eb74.png)
查看创建出的cloudfront
![image](https://user-images.githubusercontent.com/26688391/134874915-10fc2eb2-ea61-420a-aaf0-500441878165.png)
![image](https://user-images.githubusercontent.com/26688391/134874990-f811ee90-9b01-47f8-ac58-21814af3ef63.png)


![image](https://user-images.githubusercontent.com/26688391/134868937-c26354dd-79ae-47e7-9487-a7da0020c5b4.png)
![image](https://user-images.githubusercontent.com/26688391/134870317-43b53ae1-5ad6-41c5-8d29-02828eef87e9.png)
![image](https://user-images.githubusercontent.com/26688391/134869848-4f8d5aee-bfe6-45ec-856f-01167a0d058e.png)
![image](https://user-images.githubusercontent.com/26688391/134872424-fcab53a0-c707-45bc-9585-f88a9719f332.png)
![image](https://user-images.githubusercontent.com/26688391/134872859-138d75f2-9101-43b2-b9a9-706ecf5fb475.png)
![image](https://user-images.githubusercontent.com/26688391/134873804-435cf407-c352-4156-926d-1f6c44066f03.png)
上边选择缓存行为的时候没有private/*这个选择，只看到了*这个选择

部署到前
![image](https://user-images.githubusercontent.com/26688391/134874275-dac1961b-cb7f-4c12-899d-8a9d153350c7.png)

部署到后
