# redyt
forked from [Bugswriter/redyt](https://github.com/Bugswriter/redyt)
ported for my system and preferences

Please note: you will need to install the following programs:
  - fzf (User Input)
  - jq (JSON parsing)
  - nsxiv (Image Viewing)
  - curl (Downloader)
  - ripgrep (instead of grep)

## Usage

```sh
$ redyt [-l LIMIT] [-s SORT] [SUBREDDIT]
$ redyt [--limit LIMIT] [--sort SORT] [SUBREDDIT]
```

## Arguments

* `-l LIMIT, --limit LIMIT` set the maximum number of files to be downloaded
* `-s, --sort` change post sort type
