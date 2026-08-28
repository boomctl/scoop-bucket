# boomctl/scoop-bucket

[Scoop](https://scoop.sh) bucket for [`git-ark`](https://github.com/boomctl/git-ark)
— a write-only backup vault that fronts your own git host.

```powershell
scoop bucket add git-ark https://github.com/boomctl/scoop-bucket
scoop install git-ark
```

Installs the prebuilt Windows release binary. To upgrade:

```powershell
scoop update git-ark
```

The manifest lives in [`bucket/git-ark.json`](bucket/git-ark.json) and
auto-updates from the `SHA256SUMS` asset on each
[git-ark release](https://github.com/boomctl/git-ark/releases).
