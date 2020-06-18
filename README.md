# aws-backup-cloudformation

aws cloudformation create-stack --stack-name pjname-test-setupiam  --template-body file:///tmp/pjname-test-setupiam.yaml --capabilities CAPABILITY_NAMED_IAM
aws cloudformation create-stack --stack-name pjname-test-backupec2 --template-body file:///tmp/pjname-test-backupec2.yaml 
