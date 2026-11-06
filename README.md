# Pangu rollout dataset

Original archive: `pangu_rollout_8739_20261106.tar.gz` (545,739,645 bytes).

The archive is stored in 7 ordered parts to fit GitHub's per-file size limit.

## Download and restore

```bash
git clone https://github.com/weiformal-w/toolathlon_trace.git
cd toolathlon_trace
(cd data && sha256sum -c SHA256SUMS)
cat data/pangu_rollout_8739_20261106.tar.gz.part[0-9][0-9][0-9] > pangu_rollout_8739_20261106.tar.gz
sha256sum -c SHA256SUMS
tar -xzf pangu_rollout_8739_20261106.tar.gz
```

SHA-256 of the original archive: `fcc5cb74a471f4903b13c9e8057b2504ee5b90fe59b07254a71b64e184108c3e`.
