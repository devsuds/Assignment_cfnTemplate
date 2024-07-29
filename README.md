# Create SSM parameter
aws ssm put-parameter \
    --name "UserName" \
    --value "JohnDoe" \
    --type String

# Then create a S3 bucket named : devsudss3bucket (as this name used in the template)
# Next, upload yaml file at AWS console -> cloudformation