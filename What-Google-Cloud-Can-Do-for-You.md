# Frictional Airport

#### As a first project they are building a mobile app

###### App engine -- Front end (Known for rapid deploment with its minimal infrastructure management)
###### Compute engine -- Back end (Customizable virtual machine service)
###### Both can interact with google cloud database services including
* Cloud storage
* Cloud datastore
* Cloud SQL
###### As the app gets popular, the data also grows. They decide add kubernates engines to support the backend which uses docker container (Standard approach).
###### Popularity continues . . . More functionality is added to front end. Rather than expanding the code base, they make use of Google cloud functions. **Cloud functions are serverless component. They can respond events from front end or back end all without provisioning or managing a single server**
