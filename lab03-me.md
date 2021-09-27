cloudformation部署完成：
![image](https://user-images.githubusercontent.com/26688391/134896543-b144dc12-6639-40a7-af82-a6d685394327.png)
会生成一个cloudfront
![image](https://user-images.githubusercontent.com/26688391/134897155-cef9110e-2123-4f8b-acfb-59bd1b49507a.png)


JuiceShopURL：d2okg38h4ujy4a.cloudfront.net

创建一个web acl
![image](https://user-images.githubusercontent.com/26688391/134897740-5271e353-da97-467a-bcfd-3a6ba85f7edb.png)

在上边新加的web acl中添加两个规则(rule)
![image](https://user-images.githubusercontent.com/26688391/134898323-40e5a47b-4622-493f-be7d-7b1af66d1eb2.png)
![image](https://user-images.githubusercontent.com/26688391/134898470-cc246813-dd82-4bf6-a85f-837df7d6071d.png)
![image](https://user-images.githubusercontent.com/26688391/134898562-58de8d63-8d13-422b-bd84-953336fdac3a.png)
![image](https://user-images.githubusercontent.com/26688391/134898658-24eeea6f-955d-4253-bfe0-98ee41a3c774.png)

跨站脚本攻击测试，下边结果说明已经被上边配置的waf阻挡住了
![image](https://user-images.githubusercontent.com/26688391/134899443-d758147c-f274-4a82-9473-9951ae77f84b.png)
sql注入攻击测试，下边结果说明已经被上边配置的waf阻挡住了
![image](https://user-images.githubusercontent.com/26688391/134899594-e3dd3677-a589-45d8-8530-4d56e6ffbce8.png)

上边使用了了亚马逊云科WAF的托管规则。\n

sdf
