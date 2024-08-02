# Demystifying-AMI-Visibility-How-to-Make-Your-EC2-Image-Public-
Demystifying AMI Visibility: How to Make Your EC2 Image Public 

### Introduction

To make an AMI public. 

### What is AMI?

An Amazon Machine Image (AMI) is a supported and maintained image provided by AWS that provides the information required to launch an instance. You must specify an AMI when you launch an instance. You can launch multiple instances from a single AMI when you require multiple instances with the same configuration. You can use different AMIs to launch instances when you require instances with different configurations.

### Launch an instance

- Launch an instance in any region with a key.

### Create an Image of the instance(AMI-Amazon Machine Image)

- Select the instance and click on **Actions** and select **Image and templates** in that click on **create image**

- Create image give a **image name, description** and click on **create image.**

- An image has a default permission of private.

- To make it public.
- go to ec2 settings.

### Block public access for AMIs

- Manage Block public access for AMIs.

- Uncheck the block for block new public sharing.

### Edit AMI Permission

- Go to AMIs
- Select the AMI click on Actions and Select Edit AMI permission

- Edit AMI permissions in AMI availability make it public and save changes.

- When checking the AMI dashboard you can see the image has become public in the visibility.

### Summary

We can make an AMI public by just making changes to the EC2 settings and editing the AMI permission.
