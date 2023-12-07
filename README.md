# AWS
DATA IS THE NEW OIL
Oracle is the better

1. **CLOUD COMPUTING** - is the delivery of computing services wherein they provide <u>servers, storage, databases, networking, software, analytics, and intelligence</u> over the internet ("the cloud") for faster innovation, flexible resources, and economies of scale.
   
 - On-demand delivery
 - Pay-as-you-go model
 - Provision only the size you need(exactly right type and size)
 - Access resources instantly
   
<br> <br>

5. **BENEFITS OF CLOUD**
   - ***Faster time to market*** - Instead of investing funds in creating a new data structure, the org relies on clouds like AWS and utilises these funds in their business.
     
   - ***Scalability and flexibility*** - cloud offers an **unlimited amount of virtual resources**
     
   - ***Cost savings*** 
     
   - ***Better collaboration*** - teams can still collaborate in different geographical regions.
     
   - ***Advanced security*** - cloud ensures data security.
     
   - ***Data loss prevention*** - customers cant lose their data in **S3**. <br> <br>
  
6. **DISADVANTAGES OF CLOUD**
   - ***Risk of vendor lock-in***- it's **impossible** for the organisation to move from one cloud to another. 
     
   - ***Less control over underlying cloud infrastructure*** - If a company wants more control of their compliance(at the under-neath layer), then it must refrain from using the cloud.
     
   - ***Concerns about security risks like data privacy and online threats*** 
     
   - ***Integration complexity with existing systems*** 
     
   - ***Unforeseen costs and unexpected expenses.*** <br> <br>
  
7. **GARTNER's MAGIC QUADRANT** -  A big org that does analytics part. <br> <br>

8. **PUBLIC CLOUD v/s PRIVATE CLOUD** -

   
  |Public Cloud|Private Cloud|
  |------------|-------------|
   | a. Hosted at **service provider** site. | a. Hosted at **Enterprise or Service Provider** site.|
   |b. Supports connectivity over the Internet. | b. Supports connectivity over internet/private network(WAN)|
   |c. Suitable for information not very sensitive. | c. Suitable for very sensitive information|
   |d. Cheaper than Private cloud. | d. Costlier than the public cloud.|
   |e. Utilises shared infrastrucure.| e. Doesn't utilise shared infrastructure.|
   |f. Supports multiple customers.| f. Supports **one** customer.|
   |g. Requires **high-level** of security| g. Requires **medium-level** security.|
   |h. May use VLANs, access list, VRF file,  MPLs to logic||
   |i. Eg: Open Nebula|i. Eg: Eucalyptus|

   ![image](https://github.com/Ashmita-1/AWS/assets/146411027/5e08699c-b9dd-4384-a7a2-765ab90ece62)


6. **CLOUD SERVICE MODEL**
   - ***IaaS(Infrastructure as a Service)***
     
   - ***PaaS(Platform as a Service)***
     
   - ***SaaS(Software as a Service)***

<br><br>
7. **SERVICE MODELS**

   ![image](https://github.com/Ashmita-1/AWS/assets/146411027/76d91c0a-9f7d-441b-8c12-d6cbd6054e55)

   Elastic Beanstalk, Zoho cloud, Salesforce - software service provider. <br><br>


8. **AMAZON WEB SERVICES (AWS)**
   - Offers 200 fully featured services <br><br>
   
9. **COMPUTE SERVICES**
      -   ***Elastic Compute Cloud (EC2)*** - manage scanning of both EC2 and ECS
        
      -   ***Elastic Container Service (ECS)*** - provides containers

      -   ***Lambda - Serverless*** - to make a database architecture **serverless**. <br><br>

10. ***STORAGE SERVICES***
    - **Simple Storage Service (S3)**  - is an object storage which means it is already pre-formatted and doesn't allow formatting at a later stage. Storage is k/a buckets. can put necessary authentication, passwords, and authorization.
      
    - **Elastic Block Store (EBS)** - that storage which **can be formatted** at any point of  time and is generally which are attached to an OS. Provides volume which can be attached to our EC@ instances.
      
    - **Elastic File System (EFS)** - is a **shared** file system which is used in BRDB solutions (multiple clients working on a single desk i.e. database.) can be used in logging instances. Provides seamless storage.
      
    - **Archival Service - Glacier** - AWS Glacier provides **cheapest** storage where data is not used regularly.   
   
**RAID 5(Redundant Array of Independent Disks)** - data is sliced in 3 disks. 1disk - 1, 5,9,10 2disk - 2, 6,7  3disk - 3,4,8. If 1 disk is damaged, still it can be recovered. are done on hardware. <br><br>

11. ***NETWORK SERVICES***
    - **Virtual Private Cloud (VPC)** - Internal network. 
   
    - **Domain Name Service - Route 53** 
   
    - **Direct Connect** - Direct Connect(costliest service) is a service provided by AWS where they connect your data centre to AWS through a wired connection. <br><br>

----
# S3

1. **S3**
- Object Storage with durability of 99.99999%, 11 9's
- Infinitely scaling storage
- Can keep files in buckets
- S3 is a global service but buckets are created in specific regions
- Globally unique bucket names.

2. **Durability** - **11 9's durability** = if 1,00,00,000 objects are stored, avg incurred loss of a single object once every 10,000 years.
  
3. **S3 standard has 99.99% availabilty = not available 53 minutes a year.**

4. **SECURITY**
   - ***User based*** - IAM policies
     
   - ***Resource based***
       - Bucket policies
       - Bucket ACLs
       - Object ACLs

   - ***Public vs Private accessible Buckets***

   - ***Object versioning***
  
   - ***State-of-the-art in transit and at-rest encryption***
  
5. **STORAGE CLASSES**
    ![image](https://github.com/Ashmita-1/AWS/assets/146411027/d0d962ae-3b40-4b31-9c83-8244377e0486) <br><br>


6. **EC2**
   - Most popular AWS offering
   - Infrastructure as a code service
   - Provides rented Virtual machines
   - EC2 uses EBS and instance store to store data
   - EC2 uses ELB to ditribute data
   - EC2 uses autoscaling for scaling purposes
   - Bootstrapping can be done using userdata scripts.
  
**Instance store vs EBS**
|---|---|
|a. Fastest storage.||
|b. Once shut, data is wiped off.||

7. **EC2 Instance Type**
   a. ***C-type instances*** - CPU intensive which provides more **CPU**
   b. ***M-type instances*** - General purpose instances which have **balanced** memory and CPU
   c. ***R-type instances*** - which has more **RAM**
   d. ***T-type instances***

