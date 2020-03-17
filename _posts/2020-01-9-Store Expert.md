---
layout: post
title: "Store Expert"
featured-img: se
---

The "Store Expert" is an entrepreneurial project with several classmates. The "Store Expert" consists of several products, such as business data analyze, customer statistics, AI advertisements, etc. The purpose of these products is to help businesses making better use of data. And precise marketing for customers. These products have been used in several chain store companies in China.

We use artificial intelligence and data analysis in the retail field. Provide store owners with customer or VIP identification, business data analysis,customer statistics, etc. 

In this page, I focus on the part of data analyze and combination of shopping information and face data. There are other sections of the "Store Expert", and I will display them on other pages of my site.



## Background 

When customers in front of the checkout counter, the program will automatically capture the face image of the customer, then identify VIP and frequent customer by it. The system will also record the age, gender and other attributes of the customer. When the customer checks out, the face-id data of customer will be matched with the shopping information. These information will then be uploaded to the cloud server. The above data will be linked to the previous information of this customer, such as shopping history, consumer preference, etc.

In addition, when customers enter the store, the VIP and the frequent customers will be identified by the camera at the entrance, then the information of this customer will be pushed to the shop employee's APP. The information includs the consumer preference, shopping history, purchase level, VIP number, etc. Furthermore, the camera will also statistics the number of different ages and genders customers.(in project "Customer Statistics and Identification System")

Finally, in the admin website, we will show analyzed data to brand managers, such as store transaction rate, buyer retention rate, product sales forecast, customer preferences, product portraits, etc.

The entire system consists of multiple parts, such as the store analyze device, APP on phone and pad for shop staff, admin website for business manager, spark data anlayze system, some data acquisition equipment, etc. The backend services for above are provided by a micro-service which developed by myself(detail in project "LM-MS"). A open-source version has been uploaded to github (<https://github.com/ashjpo/LM-MS>). And Some computer vision algorithm such as "Face recognition, face detection, multi-object tracker, etc" by CNN are involved. And some tricks has been done in them. At the same time, in order to speed up the face-id match speed in the database, we search in a tree structure based on the Attributes, such as shop, region, age, and gender, etc.

## Responsibilities

I responsible for most development and algorithm work.


## Demonstrate

![](/images/store_expert/p8.png)

![](/images/store_expert/p3.jpg)

![](/images/store_expert/a6.png)

![](/images/store_expert/p6.jpg)

![](/images/store_expert/p5.jpg)

![](/images/store_expert/a3.jpg)

![](/images/store_expert/p7.jpg)
