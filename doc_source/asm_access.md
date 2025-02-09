# Access AWS Secrets Manager<a name="asm_access"></a>

**Topics**
+ [Secrets Manager console](#asm-console)
+ [Command line tools](#asm-cli)
+ [AWS SDKs](#asm-sdks)
+ [HTTPS Query API](#asm-sdks_query-api)
+ [Secrets Manager endpoints](#endpoints)

## Secrets Manager console<a name="asm-console"></a>

You can manage your secrets using the browser\-based [Secrets Manager console](https://console.aws.amazon.com/secretsmanager/) and perform almost any task related to your secrets by using the console\.

## Command line tools<a name="asm-cli"></a>

The AWS command line tools allows you to issue commands at your system command line to perform Secrets Manager and other AWS tasks\. This can be faster and more convenient than using the console\. The command line tools can be useful if you want to build scripts to perform AWS tasks\.

When you enter commands in a command shell, there is a risk of the command history being accessed or utilities having access to your command parameters\. See [Mitigate the risks of using the AWS CLI to store your AWS Secrets Manager secrets](security_cli-exposure-risks.md)\.

AWS provides two sets of command line tools: 
+ [AWS Command Line Interface \(AWS CLI\)](https://docs.aws.amazon.com/cli/latest/reference/secretsmanager/index.html) 
+ [AWS Tools for Windows PowerShell](https://docs.aws.amazon.com/powershell/latest/reference/)

## AWS SDKs<a name="asm-sdks"></a>

The AWS SDKs consist of libraries and sample code for various programming languages and platforms, for example, Java, Python, Ruby, \.NET, and others\. The SDKs include tasks such as cryptographically signing requests, managing errors, and retrying requests automatically\. For more information, see [AWS SDKs](#asm-sdks)\.

To download and install any of the SDKs, see [Tools for Amazon Web Services](https://aws.amazon.com/tools/#sdk)\.

For SDK documentation, see:
+ [C\+\+](http://sdk.amazonaws.com/cpp/api/LATEST/namespace_aws_1_1_secrets_manager.html)
+ [Java](https://docs.aws.amazon.com/AWSJavaSDK/latest/javadoc/com/amazonaws/services/secretsmanager/package-summary.html)
+ [PHP](https://docs.aws.amazon.com//aws-sdk-php/v3/api/namespace-Aws.SecretsManager.html)
+ [Python](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/secretsmanager.html)
+ [Ruby](https://docs.aws.amazon.com/sdk-for-ruby/v3/api/Aws/SecretsManager.html)
+ [\.NET](https://docs.aws.amazon.com/sdkfornet/v3/apidocs/items/SecretsManager/NSecretsManagerModel.html)
+ [Node\.js](https://docs.aws.amazon.com/AWSJavaScriptSDK/latest/AWS/SecretsManager.html)
+ [Go](https://docs.aws.amazon.com/sdk-for-go/api/service/secretsmanager/)

## HTTPS Query API<a name="asm-sdks_query-api"></a>

The HTTPS Query API gives you [programmatic access](https://docs.aws.amazon.com/secretsmanager/latest/apireference/Welcome.html) to Secrets Manager and AWS\. The HTTPS Query API allows you to issue HTTPS requests directly to the service\. 

Although you can make direct calls to the Secrets Manager HTTPS Query API, we recommend that you use one of the SDKs instead\. The SDK performs many useful tasks you otherwise must perform manually\. For example, the SDKs automatically sign your requests and convert responses into a structure syntactically appropriate to your language\.

To make HTTPS calls to Secrets Manager, you connect to a Secrets Manager endpoint\.

## Secrets Manager endpoints<a name="endpoints"></a>

To connect programmatically to Secrets Manager, you use an *endpoint*, the URL of the entry point for the service\. The AWS SDKs and the AWS CLI automatically use the default endpoint for the service in an AWS Region\. But you can specify an alternate endpoint for your API requests\. 

Secrets Manager offers endpoints that support [Federal Information Processing Standard \(FIPS\) 140\-2](http://aws.amazon.com/compliance/fips/) in some Regions\.

[\[See the AWS documentation website for more details\]](http://docs.aws.amazon.com/secretsmanager/latest/userguide/asm_access.html)