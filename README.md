# Работа с подподулями git

## Добавить репозиторий как подмодуль (Git Submodule)
Если нужно подтянуть код другого репозитория внутрь текущего проекта:

```shell
git submodule add https://github.com/username/repository-name.git path/to/submodule
```

После этого в проекте появится папка path/to/submodule, связанная с внешним репозиторием.
Чтобы обновить подмодуль:
```shell
git submodule update --remote --merge
```
