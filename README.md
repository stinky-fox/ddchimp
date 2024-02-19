# dyn53
Dynamic DNS using Route 53 

# .config.json sample 
```
{
     "system": {
        "check_timeout" : 300
    },
    "aws": {
        "aws_access_key": "ABCDE",
        "aws_secret_key": "QWERTY",
        "aws_r53_zone_id": "Z0121231",
        "aws_r53_name": "sub.example.com"
    }
}
```
# Docker Repo
Docker Image can be pulled from this [Docker repository](https://hub.docker.com/repository/docker/puffago/dyn53/general)