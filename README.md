# AWS-Application-load-balancer
- #### Go to the compute>ec2 instance.
![step1](https://user-images.githubusercontent.com/103019032/170917481-61ab7809-2515-44ed-94e1-a3fc9fcb555b.PNG)
- #### Click on instances new and create new instance.
![step2](https://user-images.githubusercontent.com/103019032/170918004-83664803-fb75-494f-ba65-99ff99963278.PNG)
- #### Choose ecw(AMI),i have selected free tier window server 2012,and go to the next steps.
![step3](https://user-images.githubusercontent.com/103019032/170918015-90cb9ae2-fb5a-4822-a5a3-fca7062cd4bb.PNG)
- #### Choose instance type,i have choosed free tier instance type.
![step4](https://user-images.githubusercontent.com/103019032/170918029-a77326f7-5c29-4df0-9930-a79db15f779a.PNG)
- #### I haven't no changes,i have taken default.
![step5](https://user-images.githubusercontent.com/103019032/170918036-11619c6e-6af2-4c28-ab2e-cb0ddab0d8ab.PNG)
- #### Add storage,aws provide free tier upto 30gb.
![step6](https://user-images.githubusercontent.com/103019032/170918045-1f65bdd8-d9ac-4549-8146-13ef4adb8a20.PNG)
- #### Next is add tag,i have given the key is Name ,and value is ELBSERVER1.
![step7](https://user-images.githubusercontent.com/103019032/170918055-f5fe5ef2-7c87-4ed7-9ff8-492913bd9e4b.PNG)
- #### Next is configure security group,create new security group,name given by ELBSG1,and add two rules HTTP,HTTPS for web access.
![step8](https://user-images.githubusercontent.com/103019032/170918064-bac29a1e-9eff-4fca-9215-f972be79ee09.PNG)
- #### You can review what you have configured,otherwise click on launch.
![step9](https://user-images.githubusercontent.com/103019032/170918078-0fd8cf91-8555-4bde-af37-cdc93045cbac.PNG)
- #### After review instance,Download a key pair for connect ec2 securely.
![step10](https://user-images.githubusercontent.com/103019032/170918086-869c28fc-4000-4056-87de-5ba7d458d615.PNG)
- #### After that,it show the message, your instance is running.
![step11](https://user-images.githubusercontent.com/103019032/170918104-e22e90a2-3511-4e7e-ae9f-aaf96b25eab0.PNG)
- #### We can see, our instance ELBSERVER1 is running,after completing initializing,it will ready for connect.
![step12](https://user-images.githubusercontent.com/103019032/170918116-2fc24ae5-d1f3-4c31-beb5-c0f90169695d.PNG)
- #### Create one othe machine for APPLICATION LOAD BALANCER.
![step13](https://user-images.githubusercontent.com/103019032/170918131-79cd9979-a52c-48ae-bc74-6f8a8c8d58f1.PNG)
- #### Choose instance type,i have choosed free tier instance type.
![step14](https://user-images.githubusercontent.com/103019032/170918136-72f3f530-a664-4840-9d13-1b4750fe06f1.PNG)
- #### I haven't no changes,i have taken default.
![step15](https://user-images.githubusercontent.com/103019032/170918147-f9333ad5-2e23-4220-bcf6-8dede573820f.PNG)
- #### Add storage,aws provide free tier upto 30gb.
![step16](https://user-images.githubusercontent.com/103019032/170918152-03058976-89f6-408c-b86a-130cba858dbe.PNG)
- #### Next is add tag,i have given the key is Name ,and value is ELBSERVER2.
![step17](https://user-images.githubusercontent.com/103019032/170918162-19b3691a-5405-479f-b586-628ac1fd9d8b.PNG)
- #### Next is configure security group,create new security group,name given by ELBSG1,and add two rules HTTP,HTTPS for web access.
![step18](https://user-images.githubusercontent.com/103019032/170918175-9c0cb59d-4bf1-4ae0-a56e-de51682c5f7c.PNG)
- #### You can review what you have configured,otherwise click on launch.
![step19](https://user-images.githubusercontent.com/103019032/170918191-764b0be8-d30f-4105-866e-5b334460ed79.PNG)
- #### After review instance,Download a key pair for connect ec2 securely.
![step20](https://user-images.githubusercontent.com/103019032/170918209-f68d73c2-5e0e-4e41-8049-0a4105dfc9a8.PNG)
- #### After that,it show the message, your instance is running.
![step21](https://user-images.githubusercontent.com/103019032/170918219-2f654eb4-d3aa-4e16-9e44-fb28b93d225d.PNG)
- #### We can see, our instance ELBSERVER2 is running,and it is ready for connect.
![step22](https://user-images.githubusercontent.com/103019032/170918231-612b2c69-f959-42a9-b22d-9255009bae16.PNG)
- #### Click on ELBSERVER1 for connect instance.
![step23](https://user-images.githubusercontent.com/103019032/170918243-235f032d-fed2-4255-be18-db5ebcf92f7e.PNG)
- #### Here we will paste the text file of the key pair we downloaded.
![step24](https://user-images.githubusercontent.com/103019032/170918251-ebc92036-e23d-48ea-86f7-676831a82f0a.PNG)

![step25](https://user-images.githubusercontent.com/103019032/170918258-5ced36d2-3a62-429a-8608-53f7610d8e6d.PNG)
![step26](https://user-images.githubusercontent.com/103019032/170918274-36cf2fac-1569-4104-945e-f7ce1ae9e075.PNG)
![step27](https://user-images.githubusercontent.com/103019032/170918286-bcf92069-7728-4063-bb91-effa2526d4e2.PNG)
![step28](https://user-images.githubusercontent.com/103019032/170918292-edd28c10-61eb-4bbe-aaea-ec557ccdebea.PNG)
![step29](https://user-images.githubusercontent.com/103019032/170918295-bcc7ac52-3fd6-4c82-980f-cd6f6bcb654b.PNG)
![step30](https://user-images.githubusercontent.com/103019032/170918307-f6a52e6b-2fcb-4458-8888-421c7f0c750b.PNG)
![step31](https://user-images.githubusercontent.com/103019032/170918315-dc2acfd3-370b-418f-a987-bcff111435ef.PNG)
![step32](https://user-images.githubusercontent.com/103019032/170918320-496ed4df-8a26-4473-81cf-d3e95cbe3f93.PNG)
![step33](https://user-images.githubusercontent.com/103019032/170918327-2f336840-374d-4907-adc1-cc34ec4805ac.PNG)
![step34](https://user-images.githubusercontent.com/103019032/170918336-b21e14ce-8a05-4325-ab45-a4c2706cc2aa.PNG)
![step35](https://user-images.githubusercontent.com/103019032/170918358-7f203934-bf92-42dc-bf64-a83da980030c.PNG)
![step36](https://user-images.githubusercontent.com/103019032/170918366-007d8cc7-f8d5-4bfd-b9c6-6f303aeb060e.PNG)
![step37](https://user-images.githubusercontent.com/103019032/170918377-67ac7306-83bf-44c0-9ef0-efd6e102734d.PNG)
![step38](https://user-images.githubusercontent.com/103019032/170918385-671cb046-5058-4685-b800-e6ec46b9c28c.PNG)
![step39](https://user-images.githubusercontent.com/103019032/170918391-754c70ff-343c-4e54-886c-4fb76bf227be.PNG)
![step40](https://user-images.githubusercontent.com/103019032/170918403-52c736ce-6f4e-48b6-831e-8ad9c9774a56.PNG)
![step41](https://user-images.githubusercontent.com/103019032/170918415-3a438725-06cf-4fe5-80b0-ca297f9bdea1.PNG)
![step42](https://user-images.githubusercontent.com/103019032/170918438-e1e1959e-dcef-4479-a3df-0839adfaf2e1.PNG)
![step43](https://user-images.githubusercontent.com/103019032/170918448-76d4aca3-e73d-4b3e-85a4-d9f05793a50c.PNG)
![step44](https://user-images.githubusercontent.com/103019032/170918456-540c0363-3001-479d-b640-854d4b05bf67.PNG)
![step45](https://user-images.githubusercontent.com/103019032/170918463-2a35d607-561d-4cb0-a073-801dfc143c8f.PNG)
![step46](https://user-images.githubusercontent.com/103019032/170918474-0de60f67-1958-4d35-b4ee-4baab7d1a45d.PNG)
![step47](https://user-images.githubusercontent.com/103019032/170918482-e0864ff9-2cfd-4540-8101-781e3c420c09.PNG)
![step48](https://user-images.githubusercontent.com/103019032/170918493-c7a5aaf3-44c6-4149-ba2a-8cbac527f7e2.PNG)
![step49](https://user-images.githubusercontent.com/103019032/170918502-9ac89ee8-55e4-49dd-b078-2a3ada6005e3.PNG)
![step50](https://user-images.githubusercontent.com/103019032/170918519-a64eb455-e40e-4d72-bb53-94d7375a797c.PNG)
![step51](https://user-images.githubusercontent.com/103019032/170918524-8b6de934-9656-4841-b761-f83792b12d81.PNG)
![step52](https://user-images.githubusercontent.com/103019032/170918539-121ae9ac-cf0f-4dee-a65a-2b092e869f25.PNG)
![step53](https://user-images.githubusercontent.com/103019032/170918547-eeb6d0e5-5192-4896-b637-f048eb83f93c.PNG)
![step54](https://user-images.githubusercontent.com/103019032/170918556-842cff4d-19a6-458a-94fb-d691172619e9.PNG)

