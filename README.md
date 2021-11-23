# redyt

Scrape Reddit images from the Terminal

This shell script will automatically create the following folder:

  - `~/.config/redyt`

Also, another file, containing the subreddits, will be created:

  - `~/.config/redyt/subreddit.txt`

If the user does not modify this file, it will contain, by default, subreddit `linuxmemes`.
However, this default subreddit can be changed by modifying the variable `defaultsub`.

Note that you can either pass a subreddit as an argument (`./redyt [your-subreddit]`)
or, from selector, type the name of another subreddit.

Here's an example of a custom `subreddit.txt`: http://0x0.st/-rbq.txt

Please note: you will need to install the following programs:
  - dmenu or rofi or fzf (User Input)
  - jq (JSON parsing)
  - sxiv or feh (Image Viewing)

`notify-send` is also recommended but, if not present, `echo` will be used as a notifier.

## Usage

```sh
$ redyt [-l LIMIT] [-v] [-k] [-s SORT] [SUBREDDIT]
$ redyt [--limit LIMIT] [--verbose] [--keep] [--sort SORT] [SUBREDDIT]
```

## Arguments

* `-l LIMIT, --limit LIMIT` set the maximum number of files to be downloaded
* `-k, --keep` don't remove files after quitting `sxiv`
* `-v, --verbose` use notifier
* `-s, --sort` change post sort type
