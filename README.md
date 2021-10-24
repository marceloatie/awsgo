# awsgo

Fastest way to use aws-cli
```bash
alias aws='docker run --rm -it \
    -u $(id -u ${USER}):$(id -g ${USER}) \
    -v ~/.aws:/root/.aws \
    -v $(pwd):/aws \
    -v /home:/home \
    amazon/aws-cli'
```

Fastest way to use go compiler
```bash
alias go='docker run --rm -it \
    -u $(id -u ${USER}):$(id -g ${USER}) \
    -v ~/.aws:/root/.aws \
    -v $(pwd):/go \
    golang go'
```
