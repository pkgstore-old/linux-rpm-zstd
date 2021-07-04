# Zstandard

**Zstandard**, or `zstd` as short version, is a fast lossless compression algorithm, targeting real-time compression scenarios at zlib-level and better compression ratios. It's backed by a very fast entropy stage, provided by [Huff0 and FSE library](https://github.com/Cyan4973/FiniteStateEntropy).

## Install

### Fedora COPR

```
$ dnf copr enable pkgstore/zstd
$ dnf install -y zstd
```

### Open Build Service (OBS)

```
# Work in Progress
```

## Update

```
$ dnf upgrade -y zstd
```

## Remove

```
$ dnf erase -y zstd
$ dnf copr remove pkgstore/zstd
```

## How to Build

1. Get source from [src.fedoraproject.org](https://src.fedoraproject.org/rpms/zstd).
2. Write last commit SHA from [src.fedoraproject.org](https://src.fedoraproject.org/rpms/zstd) to [CHANGELOG](CHANGELOG).
3. Modify & update source (and `*.spec`).
4. Build SRPM & RPM.
