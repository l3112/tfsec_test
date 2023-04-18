# tfsec_test
To check for naming conventions with S3 Buckets

# Problem
It's there, but it still generates an error saying it does not fit naming conventions.
# Changes made and error still happens
- values have been changed to reflect bucket naming conventions (all lowercase)
- aws_s3_bucket has been changed to aws-s3-bucket

 I can change one thing and suddenly it works, and when I test it with new parameters (i.e, a new bucket name that doesn't fit criteria), it doesn't acknowledge the change and says it's correct.

# Errors in Action:

Loom: https://www.loom.com/share/1d68ab5f33c44f48a72b7c2c5555c7be
