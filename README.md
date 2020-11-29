# rcs3

## Actions
* using https://github.com/marketplace/actions/s3-sync

### Permissions
* created RC_rcBucketWrite policy (see https://aws.amazon.com/blogs/security/writing-iam-policies-how-to-grant-access-to-an-amazon-s3-bucket/)
* created rcBucketWriteGroup tied to that policy
* created rcBucketWriter user belonging to that group
  * downloaded access keys

### notes
* bucketname is just rc.com
* also needed s3:PutObjectAcl

