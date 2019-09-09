# aws_workspace
Descriptive use and administration of AWS workspace
<p> Amazon WorkSpaces offers an easy way to provide a cloud-based desktop experience to your end users. Users can connect from a PC, Mac desktop computer, iPad, Kindle, or Android tablet. Amazon WorkSpaces eliminates the need to procure and deploy hardware or install complex software.</p>
<img src="https://gitresource.s3.us-east-2.amazonaws.com/aws_workspace/Screenshot+from+2019-09-09+20-42-00.png">
<h3>Features</h3>
<ul>
  <li>Choose your operating system (Windows or Amazon Linux) and select from a range of hardware configurations, software configurations, and AWS Regions. For more information, see Amazon WorkSpaces Bundles.

  <li>Connect to your WorkSpace and pick up from right where you left off. Amazon WorkSpaces provides a persistent desktop experience.

  <li>Amazon WorkSpaces provides the flexibility of either monthly or hourly billing for WorkSpaces. For more information, see Amazon WorkSpaces Pricing.

   <li>Deploy and manage applications for your WorkSpaces by using Amazon WorkSpaces Application Manager (Amazon WAM).

  <li>For Windows desktops, you can bring your own licenses and applications, or purchase them from the AWS Marketplace for Desktop Apps.

   <li>Create a standalone managed directory for your users, or connect your WorkSpaces to your on-premises directory so that your users can use their existing credentials to obtain seamless access to corporate resources.

   <li> Use the same tools to manage WorkSpaces that you use to manage on-premises desktops.

   <li>Use multi-factor authentication (MFA) for additional security.

   <li>Use AWS Key Management Service (AWS KMS) to encrypt data at rest, disk I/O, and volume snapshots.

   <li>Control the IP addresses from which users are allowed to access their WorkSpaces.
</ul>

<h3> Before You Begin </h3>
<ul>
   <li> You must have an AWS account to create or administer a WorkSpace. Users do not need an AWS account to connect to and use their WorkSpaces.

   <li> When you launch a WorkSpace, you must select a WorkSpace bundle. For more information, see Amazon WorkSpaces Bundles.

   <li> When you launch a WorkSpace, you must specify profile information for the user, including a user name and email address. Users complete their profiles by specifying a password. Information about WorkSpaces and users is stored in a directory.

   <li> Amazon WorkSpaces is not available in every Region. Verify the supported Regions and select a Region for your WorkSpaces. For more information about the supported Regions, see Amazon WorkSpaces Pricing by AWS Region.
</ul>

<h2> Creating Amazon Workspace </h2>
<p> Under AWS console move to Workspace service, click the "Get Started Now" button to start with Workspace,first create a Active Directory Service. <p>
<img src="https://gitresource.s3.us-east-2.amazonaws.com/aws_workspace/Screenshot+from+2019-09-09+19-10-03.png">
<h2> Creating Simple Active Directory   </h2>
<p>Choose a Directory Type Simple AD </p>
<img src="https://gitresource.s3.us-east-2.amazonaws.com/aws_workspace/Screenshot+from+2019-09-09+19-12-30.png">
<p>Under the Directory Size option choose it as per your requirement </p>
<img src="https://gitresource.s3.us-east-2.amazonaws.com/aws_workspace/Screenshot+from+2019-09-09+19-13-54.png">
<p>
  Now configure the Active Directory Information <br>
  <ul>
    <li>Directory DNS Name = Fully qualified Domain Name (Does not need to be a public domain ,put anything you want) </li>
    <li>Directory NetBios Name = Netbios Name </li>
    <li>Directory description = Put Description here </li>
    <li>Administrator Password = Put administrator password here
   </ul>
      <p> Example :- </p>
<ul>
    <li>Directory DNS Name = ashwinikr.xyz
    <li>Directory NetBios Name = ashwinikr
    <li>Directory description = Test Directory 
</ul>

<p> Next choose VPC and Subnets </p>
  <img src="https://gitresource.s3.us-east-2.amazonaws.com/aws_workspace/Screenshot+from+2019-09-09+19-26-47.png">
  
<p> Finally review and create the Active Directory </p>
<img src="https://gitresource.s3.us-east-2.amazonaws.com/aws_workspace/Screenshot+from+2019-09-09+19-26-54.png">
<br> <br>
<img src ="https://gitresource.s3.us-east-2.amazonaws.com/aws_workspace/Screenshot+from+2019-09-09+19-26-59.png">
<br> <br>
<img src="https://gitresource.s3.us-east-2.amazonaws.com/aws_workspace/Screenshot+from+2019-09-09+19-27-28.png">

  
### Creating Workspace 
<p> Under the Workspace Service ,move the the Directories section and register the Active Directory to be used with Amazon Workspace.</p>
<img src="https://gitresource.s3.us-east-2.amazonaws.com/aws_workspace/Screenshot+from+2019-09-09+20-06-09.png">
<br><br>
<p> Next select a Directory to use with Workspace </p>
<img src="https://gitresource.s3.us-east-2.amazonaws.com/aws_workspace/Screenshot+from+2019-09-09+20-09-02.png">
<br>
<p> Next add users for whom you want to create workspace </p>
<img src="https://gitresource.s3.us-east-2.amazonaws.com/aws_workspace/Screenshot+from+2019-09-09+20-10-47.png">
<br>
<p> Next select a Bundle and assign Workspace Bundle ,further add any tag in case you want (recommended) ,finally review and launch the Workspace/s</p>
<img src="https://gitresource.s3.us-east-2.amazonaws.com/aws_workspace/Screenshot+from+2019-09-09+20-10-56.png">
<img src="https://gitresource.s3.us-east-2.amazonaws.com/aws_workspace/Screenshot+from+2019-09-09+20-11-10.png">
<img src="https://gitresource.s3.us-east-2.amazonaws.com/aws_workspace/Screenshot+from+2019-09-09+20-12-04.png">
<img src="https://gitresource.s3.us-east-2.amazonaws.com/aws_workspace/Screenshot+from+2019-09-09+20-12-19.png">
<br>


