This AWS lambda function will automatically enable flow logs upon vpc creation >> triggered via cloudwatch events.

To prevent deletion of the vpc flow logs >> use IAM policy "prevent-deletion.json" 

For debugging purposes if any case of issue with permissions >> use flowlog-policy.json and attach along with other necessary permissions via IAM (lambda permissions, vpc, ec2, cloudwatch, cloudtrail etc.)
