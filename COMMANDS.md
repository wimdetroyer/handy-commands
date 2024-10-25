## git

### Detective work 

```bash
git log --stat | grep <search term> -i -A40 -B40
```


## Maven

### Dependency tree

```bash
mvn dependency:tree -Dverbose -DoutputFile=dependency-tree
```
