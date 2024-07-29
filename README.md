# Create SSM parameter
aws ssm put-parameter \
    --name "UserName" \
    --value "JohnDoe" \
    --type String

# Next, upload yaml file at AWS console -> cloudformation