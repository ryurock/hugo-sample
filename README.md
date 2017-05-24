# hugo-sample

## live load

```
hugo server
```

## deploy

1. create html

```
hugo
```

1. s3 sync

```
aws --profile myaws s3 sync --delete ./public s3://{your backet name}/ --acl public-read
```
