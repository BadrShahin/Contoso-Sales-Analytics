# Git Workflow

## Create a Feature Branch

```bash
git checkout develop
git pull
git checkout -b feature/<feature-name>
```

## Commit Changes

```bash
git add .
git commit -m "Meaningful commit message"
```

## Push Changes

```bash
git push -u origin feature/<feature-name>
```

## Create Pull Request

```
feature/* → develop
```

## Merge to Production

```
develop → main
```

## Best Practices

- Commit small logical changes.
- Use meaningful commit messages.
- Never commit directly to `main`.
- Review code before merging.