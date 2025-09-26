### Dom Heallis
### 040728287
### Lab 1
---

## 1. Create an Azure blob/Storage account for region US East and select local redundant storage
Got this error using US East

![alt text](image-1.png)

Used canada central instead

![alt text](image.png)

## 2. Add file named sample_container.csv objects to containers via GUI    

![alt text](image-2.png)

## 3. Create file share 

![alt text](image-3.png)
![alt text](image-4.png)

## 4. Work with objects in the containers, using AzCopy and download sample_container.csv file to a local folder, take screenshot of AzCopy commands and output - NO USE OF SAS TOKEN IN COMMAND 

had to give myself permissions

![alt text](image-8.png)
![alt text](image-9.png)


shows me contents of the container

![alt text](image-5.png)

downloaded successfully
![alt text](image-6.png)

here it is

![alt text](image-7.png)

## 5. Add file named sample_fc.json to file share using SAS token via command line, take screenshot of steps and output   

found token here

![alt text](image-11.png)

successful upload

![alt text](image-10.png)

browsed to find .json file uploaded

![alt text](image-12.png)

## 6. Check your current IAM policy for yourself   

![alt text](image-13.png)   

## 7. Create IAM policy for storage account, that is relevant to the service that would allow you to view all resources, but does not allow you to make any changes.  

finding user

![alt text](image-14.png)

giving myself read only access

![alt text](image-15.png)

read only access (minus the inherited roles)

![alt text](image-16.png)

## 8. Delete everything

![alt text](image-17.png)

![alt text](image-18.png)
