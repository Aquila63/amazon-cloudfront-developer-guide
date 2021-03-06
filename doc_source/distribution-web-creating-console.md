# Creating or Updating a Web Distribution Using the CloudFront Console<a name="distribution-web-creating-console"></a>

You can create or update a web distribution by using the CloudFront console or programmatically\. This topic is about working with web distributions by using the console\.

If you want to create or update a web distribution by using the CloudFront API, go to [ Create Distribution](http://docs.aws.amazon.com/cloudfront/latest/APIReference/API_CreateDistribution.html) or [Update Distribution](http://docs.aws.amazon.com/cloudfront/latest/APIReference/API_UpdateDistribution.html) in the *Amazon CloudFront API Reference*\. 

**Note**  
To see the current limit on the number of web distributions that you can create for each AWS account, or to request a higher limit, [General Limits on Web Distributions](cloudfront-limits.md#limits-web-distributions)\.<a name="CreatingDownloadDistributionsConsoleProcedure"></a>

**To create a CloudFront web distribution using the CloudFront console**

1. Sign in to the AWS Management Console and open the CloudFront console at [https://console\.aws\.amazon\.com/cloudfront/](https://console.aws.amazon.com/cloudfront/)\.

1. Choose **Create Distribution**\.

1. On the first page of the **Create Distribution Wizard**, in the **Web** section, choose **Get Started**\.

1. Specify settings for the distribution\. For more information, see [Values That You Specify When You Create or Update a Web Distribution](distribution-web-values-specify.md)\.

1. Save changes\.

1. After CloudFront creates your distribution, the value of the **Status** column for your distribution will change from **InProgress** to **Deployed**\. If you chose to enable the distribution, it will be ready to process requests after the status switches to **Deployed**\. 

   The domain name that CloudFront assigns to your distribution appears in the list of distributions\. \(It also appears on the **General** tab for a selected distribution\.\) 
**Tip**  
You can use an alternate domain name, instead of the name assigned to you by CloudFront; by following the steps in [Adding and Moving Alternate Domain Names \(CNAMEs\)](CNAMEs.md)\.

1. When your distribution is deployed, confirm that you can access your content using your new CloudFront URL or CNAME\. For more information, see [Testing Your Web Distribution](distribution-web-testing.md)\.

To update a web distribution \(for example, to add or change cache behaviors\), see [Viewing and Updating CloudFront Distributions](HowToUpdateDistribution.md)\.