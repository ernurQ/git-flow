# Dev
```sh
git checkout dev
```

```sh
git pull origin dev
```

```sh
git add .
```

```sh
git commit -m ""
```

```sh
git push origin dev
```

# Release
```sh
git checkout release
```

```sh
git pull origin release
```

```sh
git log dev --oneline -1 | cat
```

```sh
git cherry-pick
```

```sh
git push origin release
```


# Master
```sh
git checkout master
```

```sh
git pull origin master
```

```sh
git checkout -b master-25
```

```sh
git cherry-pick
```

```sh
git push origin master-25
```

