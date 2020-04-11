#### App engine is code centric, and it provides automatic scaling globally

#### App Engine Fundamentals
1. PaaS: Platform as a service. 
    * Highly managed compute service in Google Cloud's lineup.
    * No server set up, no provisioning and minimal management required.
    * **You can't customize App Engine the way you can customise compute engine**
1. Automatic scaling and load-balancing.
    * Up and down to the virtual instances and it's fast.
    * Very responsive.
1. Great for websites, mobile apps, and line of business apps 
    * Can go viral at a snap.
    * For business apps, can be up and running with minimal investment of resources.

#### App comes in two environment
1. Standard Environment
    * Earliest or Original implementaion
    * More proporietory: Use specific google APIs
    * Limited languages and access
    * Faster instance sign-up
    * Less expensive
1. Flexible Environment
    * Recently introduced
    * Standardized on Docker
    * Broader language/version use
    * Slower instance sign-up 
    * More expensive

#### App engine has access to SQL database serive. Photos and documents are stored in Cloud storage
#### Many services kick in automaticaly. For example when your code is ready to deploy cloud load balancing is ready to work
#### You can create services. You can't call code in one service from another, but you can use RESTful API or http request
