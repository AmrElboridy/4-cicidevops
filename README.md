##########################################################
##                      Section 1                       ##
##########################################################

1-  Selling CI/CD to your Team/Organization  	  attached

##########################################################
##			Section 2			##
##########################################################

 Deploying Working, Trustworthy Software

	A- A public git repository with your project code. 
			https://github.com/AmrElboridy/4-cicidevops.git

	B- Evidence of code-based CI/CD configuration in the form of yaml files in your git repository.
			https://github.com/AmrElboridy/4-cicidevops.git

	C-Console output of various pre-deploy job failure scenarios:

    		-- Build Jobs that failed because of compile errors. [SCREENSHOT01]
    		-- Failed unit tests. [SCREENSHOT02]
    		-- Failure because of vulnerable packages. [SCREENSHOT03]
    		-- An alert from one of your failed builds. [SCREENSHOT04]

	D-Evidence in your code that:

    		-- Compile errors have been fixed.		attached		
                -- Unit tests have been fixed.			attached
    		-- All critical security vulnerabilities caught by the “Analyze” job have been fixed.					attached

############################################################
Utilize a configuration management tool to accomplish deployment to cloud-based servers. 

	A- Console output of appropriate failure for infrastructure creation job (using CloudFormation). [SCREENSHOT05]

	B- Console output of a smoke test job that is failing appropriately. [SCREENSHOT06]

	C- Console output of a successful rollback after a failed smoke test. [SCREENSHOT07]

	D- Console output of successful promotion of new version to production in CloudFront. [SCREENSHOT08]

	E- Console output of successful cleanup job that removes old S3 bucket and EC2 instance. [SCREENSHOT09]

	F- Evidence that deploy jobs only happen on master branch. [SCREENSHOT10]

	G- Evidence of deployed and functioning front-end application in an S3 bucket [URL02] 
	https://s3.console.aws.amazon.com/s3/buckets/mrss3amrbueckrrrrret?region=us-east-1&tab=objects
	and in CloudFront. [URL03]

	H- Evidence of healthy back-end application. [URL04]



##########################################################
##                      Section 3                       ##
##########################################################
	A -Evidence of Prometheus Server. [URL05]

	B- Evidence that Prometheus is monitoring memory, cpu and disk usage of EC2 instances. [SCREENSHOT11]

	C- Evidence that Prometheus and AlertManager send alerts when certain conditions exist in the EC2 instance. [SCREENSHOT12]
