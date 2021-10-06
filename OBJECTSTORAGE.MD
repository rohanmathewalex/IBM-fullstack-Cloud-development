### Hands on Lab: Creating IBM Cloud Object Storage

## Lab overview:
*After completing this lab, you will have created an Object Storage instance, a bucket, and added objects to the bucket.

## Objectives:
IBM Cloud offers numerous cloud resources and services.

After completing this lab, you will be able to:

Use your IBM Cloud Lite account to create an instance of Object Storage
. Create a bucket to store data
. Add objects to your bucket
. Share objects in your bucket.

## Create an IBM Cloud Object storage

 # Task I: Create an instance of IBM Cloud Object Storage:

 Log in to your IBM Cloud account that you created in an earlier lab and open the IBM Cloud Catalog
  https://cloud.ibm.com/catalog.
 1. Log in to your IBM Cloud account that you created in an earlier lab and open the IBM Cloud Catalog
 https://cloud.ibm.com/catalog.

2. On the Catalog page, make sure the Services tab is selected and search and select Object Storage:
![view](https://github.com/rohanmathewalex/IBM-fullstack-Cloud-development/blob/main/lab-screnshots/screenshot_objectstorage.png)

3. On the Cloud Object Storage (COS) page, choose the Lite plan. You can use the name that is shown in Service name or rename it as you want, accept the Default resource group, and then click Create.
4. The Objects page appears where you can click Upload and select Files or Folders from the dropdown. You can also drag and drop files or folders into the space.
 [''](https://github.com/rohanmathewalex/IBM-fullstack-Cloud-development/blob/main/lab-screnshots/screenshot_upload.png)
5. For this lab, we’ve provided an Html file that you can use to add to your bucket. Download the index.html file to your  computer.
6. Upload the Index.html file from your computer to your COS bucket.

# Task IV: Share Objects in your Bucket:
If you need to share objects in your buckets with other users, you can setup Access Policies. You can set access policies for specific users and groups, or you can choose to make certain buckets public so that anyone can access them (e.g. if you want to host static files on your website)

1. In the navigation pane under buckets, click Access Policies. On the Bucket access policies page, click Need to Add users? to add user access for your bucket.
![''](https://github.com/rohanmathewalex/IBM-fullstack-Cloud-development/blob/main/lab-screnshots/screenshot_needtoadduser.png)
2. You can select users if they’ve already been added and select roles for this bucket. But for this exercise we need to provide public access to the file we added to the bucket. Click Public Access and notice Public Access appears in the Access group, and then click Create Access policy.
![''](https://github.com/rohanmathewalex/IBM-fullstack-Cloud-development/blob/main/lab-screnshots/screenshotpublicaccess.png)
3.When you click on Public Access, a popup window appears. Click Enable to allow public access.
![](https://github.com/rohanmathewalex/IBM-fullstack-Cloud-development/blob/main/lab-screnshots/screenshot_enablepublicaccess.png)


