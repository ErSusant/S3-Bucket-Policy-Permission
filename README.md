# S3-Bucket-Policy-Permission

{
	"Version": "2012-10-17",
	"Statement": [
		{
			"Sid": "Stmt1405592139000",
			"Effect": "Allow",
			"Principal": "*",
			"Action": "s3:*",
			"Resource": "arn:aws:s3:::bucketName/*"
		}
	]
}
