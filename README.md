# test repo

## Базовые команды

1. Инициализировать репозиторий

```bash
git init
```

2. Добавить файлы в список для будущего коммита

```bash
git add .
git add filename
```

3. ВЫполнить коммит

```bash
git commit -m'comment'
```

## Log & hash

Отображение лога
```bash
git log
# or
git log --oneline
```
Будет отображена история коммитов. Каждый коммит отобразится в виде хэша коммита, автора, даты и комментария к  коммиту.
В короткой форме `--oneline` начало строки хэша и комметарий к коммиту.
