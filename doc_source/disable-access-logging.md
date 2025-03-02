# Disable access logs for your Application Load Balancer<a name="disable-access-logging"></a>

You can disable access logs for your load balancer at any time\. After you disable access logs, your access logs remain in your S3 bucket until you delete them\. For more information, see [Working with buckets](https://docs.aws.amazon.com/AmazonS3/latest/user-guide/creating-buckets-s3.html) in the *Amazon Simple Storage Service User Guide*\.

**To disable access logs using the console**

1. Open the Amazon EC2 console at [https://console\.aws\.amazon\.com/ec2/](https://console.aws.amazon.com/ec2/)\.

1. In the navigation pane, choose **Load Balancers**\.

1. Select your load balancer\.

1. On the **Description** tab, choose **Edit attributes**\.

1. For **Access logs**, clear **Enable**\.

1. Choose **Save**\.

**To disable access logs using the AWS CLI**  
Use the [modify\-load\-balancer\-attributes](https://docs.aws.amazon.com/cli/latest/reference/elbv2/modify-load-balancer-attributes.html) command\.