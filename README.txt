This is a combination of awesome templates by HTML5. 

I am using them as an attempt to create a mobile app with cordova and jquery.

Deleteing lines of codes that are needed are taking up a lot of time.

This is primarily a webapp and is posted in aws.


use the bucket policy:

{
  "Id": "Policy1569048588734",
  "Version": "2012-10-17",
  "Statement": [
    {
      "Sid": "Stmt1569048587703",
      "Action": "s3:*",
      "Effect": "Allow",
      "Resource": "arn:aws:s3:::bucket_name/*",
      "Principal": "*"
    }
  ]
}

Credits:

	Demo Images:
		Michael Domaradzki (md.photomerchant.net)

	Icons:
		Font Awesome (fontawesome.io)

	Other:
		jQuery (jquery.com)
		Scrollex (github.com/ajlkn/jquery.scrollex)
		Responsive Tools (github.com/ajlkn/responsive-tools)