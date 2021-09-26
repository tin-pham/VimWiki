# Tag Command

## Annotated Tags
```shell
git tag -a v1.4 -m "My verson 1.4"
```
## Lightweight Tags
```shell
git tag v1.4
```



## Display tags

* Display all tags
```shell
git tag
```

* Display specific tag
```shell
git show v1.4
```

## Add tag after commit
* You can view the checksum of commit by git [log](log) and add to it
```shell
git tag -a v1.2 9asj19a
```

## Push tag
* This will push tag as difference branch

```shell
git push origin v1.4
```


* Push all tags to the server
```shell
git push origin --tags
```
