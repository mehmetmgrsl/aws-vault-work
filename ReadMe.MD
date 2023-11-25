# WIP

### Why do we need aws-vault?

To securely store and access AWS credentials in a development environment.

### Installation

```brew install aws-vault```    

### Test

1. Store AWS credentials for the "test" profile

```aws-vault add test```

2. Execute a command

```aws-vault exec test -- aws s3 ls```

3. open a browser window and login to the AWS Console

```aws-vault login test```

4. List credentials

```aws-vault list```

### Resources

1. https://github.com/99designs/aws-vault