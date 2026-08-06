# Branching Strategy

This project follows a simplified Git Flow.

```
main
│
develop
│
feature/*
```

## Branches

### main
- Production-ready code.
- Protected branch.
- No direct commits.

### develop
- Integration branch.
- Features are merged here after review.

### feature/*
- Used for new features or enhancements.
- Created from `develop`.
- Merged back into `develop` using a Pull Request.

## Workflow

1. Create a feature branch from `develop`.
2. Develop and commit changes.
3. Push the feature branch.
4. Open a Pull Request.
5. Merge into `develop`.
6. Promote changes to `main` after testing.