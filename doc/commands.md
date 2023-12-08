# KaIndex Commands

## Retrieval

Quickly retrieve content from different websites.

#### search Web Search

Introduction: Supports quick searches for content from different platforms.

Aliases: s, sousuo, sou, query

Usage: search <search content> [-f from] [-s whether to open the current page]

Parameters:

- word (required) - Search content

Options:

- -f, --from (optional) - Default: baidu
- -s, --self (optional) - Whether to open the current page



#### baidu Baidu Search

Usage: baidu <search content> [-s whether to open the current page] [-p whether to search for images]

Parameters:

- word (required) - Search content

Options:

- -s, --self (optional) - Whether to open the current page
- -p, --picture (optional) - Whether to search for images



#### baidudev Baidu Developer Search

Aliases: dev

Usage: baidudev <search content> [-s whether to open the current page]

Parameters:

- word (required) - Search content

Options:

- -s, --self (optional) - Whether to open the current page



#### bilibili Bilibili Search

Aliases: bzhan, bili

Usage: bilibili <search content> [-s whether to open the current page] [-b Bilibili video id]

Parameters:

- word (required) - Search content

Options:

- -s, --self (optional) - Whether to open the current page
- -b, --bvid (optional) - Bilibili video id



#### bing Bing Search

Usage: bing <search content> [-s whether to open the current page]

Parameters:

- word (required) - Search content

Options:

- -s, --self (optional) - Whether to open the current page



#### github GitHub Search

Usage: github <search content> [-s whether to open the current page]

Parameters:

- word (required) - Search content

Options:

- -s, --self (optional) - Whether to open the current page



#### douban Douban Search

Usage: douban <search content> [-s whether to open the current page]

Parameters:

- word (required) - Search content

Options:

- -s, --self (optional) - Whether to open the current page



#### douyin Douyin Search

Usage: douyin <search content> [-s whether to open the current page]

Parameters:

- word (required) - Search content

Options:

- -s, --self (optional) - Whether to open the current page



#### google Google Search

Usage: google <search content> [-s whether to open the current page]

Parameters:

- word (required) - Search content

Options:

- -s, --self (optional) - Whether to open the current page



#### wangyiyun Netease Cloud Music Search

Usage: wangyiyun <search content> [-s whether to open the current page]

Parameters:

- word (required) - Search content

Options:

- -s, --self (optional) - Whether to open the current page



#### zhihu Zhihu Search

Usage: zhihu <search content> [-s whether to open the current page]

Parameters:

- word (required) - Search content

Options:

- -s, --self (optional) - Whether to open the current page



#### geng Meme Search

Aliases: xiaoji

Usage: geng <search content> [-s whether to open the current page]

Parameters:

- word (required) - Search content

Options:

- -s, --self (optional) - Whether to open the current page



#### codenav Programming Resources Search

Usage: codenav <search content> [-s whether to open the current page]

Parameters:

- word (required) - Search content

Options:

- -s, --self (optional) - Whether to open the current page



## Space

Manage your favorite websites like managing files.

#### list List Space Entries

Aliases: ls

Usage: list [directory] [-r whether to list recursively]

Parameters:

- dir (optional) - Directory

Options:

- -r, --recursive (optional) - Whether to list recursively



#### remove Remove Space Entry

Aliases: rm, delete, del

Usage: remove <item path to delete> [-r whether to delete recursively] [-f whether to force delete]

Parameters:

- item (required) - Item path to delete

Options:

- -r, --recursive (optional) - Whether to delete recursively
- -f, --force (optional) - Whether to force delete



#### add Add Space Entry

Aliases: touch, new

Usage: add <-n entry name> <-l link> [-d target directory]

Options:

- -n, --name (required) - Entry name
- -l, --link (required) - Link
- -d, --dir (optional) - Target directory



#### mkdir Create Space Directory

Usage: mkdir <new directory path>

Parameters:

- dir (required) - New directory path



#### pwd Display Current Space Location

Usage: pwd



#### cd Change Space Directory

Usage: cd <target directory>

Parameters:

- dir (required) - Target directory



#### move Move Space Entry

Usage: move <source path> <target path> [-r whether to move recursively]

Parameters:

- source (required) - Source path
- target (required) - Target path

Options:

- -r, --recursive (optional) - Whether to move recursively



#### copy Copy Space Entry

Aliases: cp

Usage: copy <source path> <target path> [-r whether to copy recursively]

Parameters:

- source (required) - Source path
- target (required) - Target path

Options:

- -r, --recursive (optional) - Whether to copy recursively



## User

Usage: user <subcommand>

Subcommands:

- login User login
- register User registration
- logout User logout

Parameters:

- subCommand (required) - Subcommand



#### User Registration

Usage: user register <-u username> <-p password> <-e email>

Options:

- -u, --username (required) - Username
- -p, --password (required) - Password
- -e, --email (required) - Email



#### User Login

Usage: user login <-u username> <-p password>

Options:

- -u, --username (required) - Username
- -p, --password (required) - Password



#### User Logout

Usage: user logout



## Tools

#### goto Web Page Navigation

Aliases: to, open, visit, jump

Usage: goto <target link> [-s whether to open in the current page]

Parameters:

- link (required) - Target link

Options:

- -s, --self (optional) - Whether to open in the current page



#### fanyi Translation

Usage: fanyi <content to translate> [-f source language] [-t target language]

Parameters:

- word (required) - Content to translate

Options:

- -f, --from (optional) - Default: auto Source language
- -t, --to (optional) - Default: auto Target language



#### todo To-Do List

Usage: todo <subcommand

>

Subcommands:

- add Add task

Parameters:

- subCommand (required) - Subcommand



#### Add Task

Usage: todo add <-n task name>

Options:

- -n, --name (required) - Task name



#### timing Timer

Usage: timing <-s seconds>

Options:

- -s, --seconds (required) - Seconds



#### date Date

Usage: date



#### ping Network Check

Introduction: Check if a specific address is alive.

Usage: ping <target address>

Parameters:

- dest (required) - Target address



#### ddos

Introduction: Launch a network attack, use with caution!

Usage: ddos



## Terminal Related

### Terminal Operations

#### clear Clear Screen

Aliases: cl

Usage: clear

Shortcut: Ctrl + L



#### history View Execution History

Aliases: h

Usage: history



#### help View Help

Aliases: man

Usage: help [command English name]

Parameters:

- commandName (optional) - Command English name



#### info View Site Information

Aliases: author, about

Usage: info



#### shortcut Shortcuts

Introduction: View shortcuts

Usage: shortcut



### Terminal Configuration

#### background Switch Terminal Background

Aliases: bg

Usage: background [image URL (leave blank for random)]

Parameters:

- url (optional) - Image URL (leave blank for random)



#### reset Reset Terminal Configuration

Usage: reset



#### hint Toggle Hints

Turn on/off input hints



## Leisure and Entertainment

#### music Music

Introduction: Listen to music online

Usage: music <music name>

Parameters:

- name (required) - Music name



#### moyu Fish

Usage: moyu



#### ikun Kun Kun

Usage: ikun