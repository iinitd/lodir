# LODIR

mkdir and localize it in macOS.

# INSTALL

```sh
sudo sh -c "curl https://raw.githubusercontent.com/cogons/lodir/master/lodir -o /usr/local/bin/lodir && chmod +x /usr/local/bin/lodir"
```

# USAGE

- **Create**

`cd /home/user/ && lodir music 音乐`

> generate a localized folder under `/home/user/` shown as  **音乐**
>
> the path is `/home/user/music.localized`

- **Change alias**

`cd /home/user/music.localized && lodir 歌曲`

> change the alias of `/home/user/music.localized` to **歌曲**
>
> and it's totally harmless

# FEATURES

## Multiple language support

`lodir music おんがく`

## Emoji folder

`lodir film 🎞️`

