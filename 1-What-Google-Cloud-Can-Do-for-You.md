# Frictional Airport

#### As a first project they are building a mobile app

##### App engine -- Front end (Known for rapid deploment with its minimal infrastructure management)
##### Compute engine -- Back end (Customizable virtual machine service)
##### Both can interact with google cloud database services including
* Cloud storage
* Cloud datastore
* Cloud SQL
##### As the app gets popular, the data also grows. They decide add kubernates engines to support the backend which uses docker container (Standard approach).
##### Popularity continues . . . More functionality is added to front end. Rather than expanding the code base, they make use of Google cloud functions. **Cloud functions are serverless component. They can respond events from front end or back end all without provisioning or managing a single server**
##### Now you will want to protect the code which is undergoing development and improvement by multiple teams. IAM (Identity and access management) is perfect for this.
* Developers or engineers can access code in App engine, compute engine, cloud storage.
* Data entry guys can access and change data in cloud SQL and cloud datastore
###### Cloud SQL -- The traditional relational database queries, looking at passangers, flights and airlines
###### Cloud Datastore -- **Key value pair**, quick look up for flight information, such as current departure gates.
###### Cloud storage -- Central service for putting and retrieving objects, documents, images, videos and more.
##### App enhances their data management with the additional of bigtable (No SQL). 
##### Cloud VPC, Virtual Private Cloud, is a global service, so all of LACA International's engineering staff can gain access as though they were on a private internal network.
##### Cloud CDM -- This is to to host the extensive, ever-increasing and highly popular number of videos (Like a video going viral). Such a dedicated content delivery service is perfect for reducing latency as well as serving costs.
##### BigQuery -- This can handle the increased information with standard SQL queries without having to rely on a database administrator. This also be able to accept streaming data and output real time analysis to spreadsheets and reports.
##### Finally incorporating AI.
