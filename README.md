# Data Analytics Using Splunk 9.x. 

<a href="https://www.amazon.com/dp/1803249412"><img src="https://m.media-amazon.com/images/I/41QHUNhfiKL._SX404_BO1,204,203,200_.jpg" alt="Data Analytics Using Splunk 9.x. " height="256px" align="right"></a>

This is the code repository for [Data Analytics Using Splunk 9.x. ](https://www.amazon.com/dp/1803249412), published by Packt.

**A practical guide to implementing Splunk’s features for performing data analysis at scale**

## What is this book about?

* This book covers the following exciting features:
* Install and configure the Splunk 9 environment
* Create advanced dashboards using the flexible layout options in Dashboard Studio
* Understand the Splunk licensing models
* Create tables and make use of the various types of charts available in Splunk 9.x
* Explore the new configuration management features
* Implement the performance improvements introduced in Splunk 9.x
* Integrate Splunk with Kubernetes for optimizing CI/CD management

If you feel this book is for you, get your [copy](https://www.amazon.com/dp/1803249412) today!

## Instructions and Navigations

All of the code is organized into folders. For example, Chapter04.

 

The code will look like the following:

```
index=botsv1 earliest=0
index=botsv1 sourcetype=iis http_referer=*
index=botsv1 earliest=0 sourcetype=suricata
| eval bytes=bytes_in+bytes_out
index=botsv1 earliest=0 sourcetype=iis referer_domain=*
| table _time, cs_Referer, referer_domain
index=botsv1 earliest=0 sourcetype="WinEventLog:Security"
| stats count by Account_Name
```

<a href="https://www.packtpub.com/?utm_source=github&utm_medium=banner&utm_campaign=GitHubBanner"><img src="https://raw.githubusercontent.com/PacktPublishing/GitHub/master/GitHub.png" 
alt="https://www.packtpub.com/" border="5" /></a>


**Following is what you need for this book:**
The book is for data analysts, Splunk users, and administrators who want to become well-versed in the data analytics services offered by Splunk 9. You need to have a basic understanding of Splunk fundamentals to get the most out of this book.

With the following software and hardware list you can run all code files present in the book (Chapter 1-12).

### Software and Hardware List
| Chapter | Software required | OS required |
| -------- | ------------------------------------ | ----------------------------------- |
| 1-12 | Splunk Enterprise | Windows, Mac OS , or Linux  |
| 1-12 | Splunk apps and add-ons | Windows, Mac OS , or Linux  |
| 1-12 | BOTS dataset | Windows, Mac OS , or Linux  |
| 1-12 | AWS instances | Windows, Mac OS , or Linux  |
| 1-12 | Amazon Web Services Account | Windows, Mac OS , or Linux  |


### Related products
*Hands-On Data Analysis with Pandas - Second Edition [[Packt]](https://www.packtpub.com/product/hands-on-data-analysis-with-pandas-second-edition/9781800563452?utm_source=github&utm_medium=repository&utm_campaign=9781800563452) [[Amazon]](https://www.amazon.com/dp/1800563450)

*The Data Analysis Workshop [[Packt]](https://www.packtpub.com/product/the-data-analysis-workshop/9781839211386?utm_source=github&utm_medium=repository&utm_campaign=9781839211386) [[Amazon]](https://www.amazon.com/dp/1839211385)

## Get to Know the Author
**Dr. Nadine Shillingford**
is a certified Splunk Architect with 10 years of security consulting experience. She has installed, managed, and configured large-scale and large-volume Splunk deployments in the healthcare, retail, insurance, and federal spaces. In addition, Dr. Shillingford has teaching experience at the undergraduate and graduate levels. Dr. Shillingford holds a Ph.D. in computer science from the University of Notre Dame. She is an artist and the mother of a teenage daughter.




