# Shell Basics

## Navigation
- `pwd` — shows current location
- `cd foldername` — move into a folder
- `cd ..` — move up one level
- `cd ~` — jump to home directory
- `cd ~/any/path` — jump anywhere directly

## Files & Folders
- `ls` — list visible files
- `ls -la` — list all files including hidden ones
- `mkdir foldername` — create a folder
- `mkdir folder1 folder2` — create multiple folders at once
- `touch filename.md` — create an empty file
- `cat filename` — read a file

## Key lessons
- Terminal is exact — hyphens and underscores are different
- Hidden files start with a `.`
- `~` is a shortcut for your home directory




/web-bootcamp/web-challenges ❯ ls                                                                                                                                                               17:02:27
Desktop                    Desktop.pub                newfile                    newfile.pub                shell-basics_treasure-hunt
~/web-bootcamp/web-challenges ❯ cd shell-basics_treasure-hunt                                                                                                                                    17:02:30
~/web-bootcamp/web-challenges/shell-basics_treasure-hunt ❯ ls                                                                                                                                    17:02:42
package.json    README.md       treasure-island
~/web-bootcamp/web-challenges/shell-basics_treasure-hunt ❯ cd treasure-island                                                                                                                    17:02:43
~/web-bootcamp/web-challenges/shell-basics_treasure-hunt/treasure-island ❯ ls                                                                                                                    17:02:50
beach  cliffs forest
~/web-bootcamp/web-challenges/shell-basics_treasure-hunt/treasure-island ❯ cd beach                                                                                                              17:02:51
~/web-bootcamp/web-challenges/shell-basics_treasure-hunt/treasure-island/beach ❯ ls                                                                                                              17:03:22
cave         shipwreck.md
~/web-bootcamp/web-challenges/shell-basics_treasure-hunt/treasure-island/beach ❯ cat shipwreck.md                                                                                                17:03:23
```
|\    \ \ \ \ \ \ \      __
|  \    \ \ \ \ \ \ \   | O~-_
|   >----|-|-|-|-|-|-|--|  __/
|  /    / / / / / / /   |__\
|/     / / / / / / /
```
~/web-bootcamp/web-challenges/shell-basics_treasure-hunt/treasure-island/beach ❯ cd ..                                                                                                           17:03:46
~/web-bootcamp/web-challenges/shell-basics_treasure-hunt/treasure-island ❯ ls                                                                                                                    17:03:56
beach  cliffs forest
~/web-bootcamp/web-challenges/shell-basics_treasure-hunt/treasure-island ❯ cd beach                                                                                                              17:03:57
~/web-bootcamp/web-challenges/shell-basics_treasure-hunt/treasure-island/beach ❯ ls                                                                                                              17:04:02
cave         shipwreck.md
~/web-bootcamp/web-challenges/shell-basics_treasure-hunt/treasure-island/beach ❯ cd cave                                                                                                         17:04:04
~/w/web-challenges/shell-basics_treasure-hunt/treasure-island/beach/cave ❯ ls                                                                                                                    17:04:08
barrel.md           note-in-a-bottle.md underwater-cave.md
~/w/web-challenges/shell-basics_treasure-hunt/treasure-island/beach/cave ❯ cat barrel.md                                                                                                         17:04:10
```
 _       _
(_'-----'_)
(_.'""""._) fsc
```
~/w/web-challenges/shell-basics_treasure-hunt/treasure-island/beach/cave ❯ cd ..                                                                                                                 17:05:07
~/web-bootcamp/web-challenges/shell-basics_treasure-hunt/treasure-island/beach ❯ ls                                                                                                              17:05:11
cave         shipwreck.md
~/web-bootcamp/web-challenges/shell-basics_treasure-hunt/treasure-island/beach ❯ cd cave                                                                                                         17:05:12
~/w/web-challenges/shell-basics_treasure-hunt/treasure-island/beach/cave ❯ ls                                                                                                                    17:05:17
barrel.md           note-in-a-bottle.md underwater-cave.md
~/w/web-challenges/shell-basics_treasure-hunt/treasure-island/beach/cave ❯ cat note-in-a-bottle.md                                                                                               17:05:18
```
+--------------------+
|                    |
| Hey Barry,         |
|                    |
| come and visit me  |
| in my cave, you    |
| have a beautiful   |
| view from up here. |
| Follow the  river. |
|                    |
| Garry              |
|                    |
|                    |
+--------------------+
```
~/w/web-challenges/shell-basics_treasure-hunt/treasure-island/beach/cave ❯ cd ..                                                                                                                 17:05:36
~/web-bootcamp/web-challenges/shell-basics_treasure-hunt/treasure-island/beach ❯ ld                                                                                                              17:05:45
ls
ld: no object files specified
~/web-bootcamp/web-challenges/shell-basics_treasure-hunt/treasure-island/beach ❯ ls                                                                                                           5s 17:05:55
cave         shipwreck.md
~/web-bootcamp/web-challenges/shell-basics_treasure-hunt/treasure-island/beach ❯ cd cave                                                                                                         17:05:55
~/w/web-challenges/shell-basics_treasure-hunt/treasure-island/beach/cave ❯ ls                                                                                                                    17:06:00
barrel.md           note-in-a-bottle.md underwater-cave.md
~/w/web-challenges/shell-basics_treasure-hunt/treasure-island/beach/cave ❯ cat underwater-cave.md                                                                                                17:06:02
```
  .-"""-.
 /      o\
|    o   0).-.
|       .-;(_/     .-.
 \     /  /)).---._|  `\   ,
  '.  '  /((       `'-./ _/|
    \  .'  )        .-.;`  /
     '.             |  `\-'
       '._        -'    /
 jgs      ``""--`------`
```
~/w/web-challenges/shell-basics_treasure-hunt/treasure-island/beach/cave ❯ cd ..                                                                                                                 17:06:11
~/web-bootcamp/web-challenges/shell-basics_treasure-hunt/treasure-island/beach ❯ cd ..                                                                                                           17:06:44
~/web-bootcamp/web-challenges/shell-basics_treasure-hunt/treasure-island ❯ ls                                                                                                                    17:06:49
beach  cliffs forest
~/web-bootcamp/web-challenges/shell-basics_treasure-hunt/treasure-island ❯ cd cliffs                                                                                                             17:06:50
~/web-bootcamp/web-challenges/shell-basics_treasure-hunt/treasure-island/cliffs ❯ ls                                                                                                             17:06:57
nest.md
~/web-bootcamp/web-challenges/shell-basics_treasure-hunt/treasure-island/cliffs ❯ cat nest.md                                                                                                    17:06:58
```
 ,''.
 (9/\9)
|\}\/{ /| ,     ,
\ `^./^ / \`/\/`/
 `.___.'   `._,'
```
~/web-bootcamp/web-challenges/shell-basics_treasure-hunt/treasure-island/cliffs ❯ cd ..                                                                                                          17:07:07
~/web-bootcamp/web-challenges/shell-basics_treasure-hunt/treasure-island ❯ ls                                                                                                                    17:07:28
beach  cliffs forest
~/web-bootcamp/web-challenges/shell-basics_treasure-hunt/treasure-island ❯ cd forest                                                                                                             17:07:30
~/web-bootcamp/web-challenges/shell-basics_treasure-hunt/treasure-island/forest ❯ ls                                                                                                             17:07:33
deep-forest meadow
~/web-bootcamp/web-challenges/shell-basics_treasure-hunt/treasure-island/forest ❯ cd deep-forest                                                                                                 17:07:34
~/w/web-challenges/shell-basics_treasure-hunt/treasure-island/forest/deep-forest ❯ ls                                                                                                            17:07:59
very-deep-forest
~/w/web-challenges/shell-basics_treasure-hunt/treasure-island/forest/deep-forest ❯ cd very-deep-forest                                                                                           17:08:00
~/w/w/shell-basics_treasure-hunt/t/forest/deep-forest/very-deep-forest ❯ ls                                                                                                                      17:08:10
ruins
~/w/w/shell-basics_treasure-hunt/t/forest/deep-forest/very-deep-forest ❯ cd ruins                                                                                                                17:08:11
~/w/w/shell-basics_treasure-hunt/t/forest/deep-forest/very-deep-forest/ruins ❯ ls                                                                                                                17:08:15
temple tower
~/w/w/shell-basics_treasure-hunt/t/forest/deep-forest/very-deep-forest/ruins ❯ cd temple                                                                                                         17:08:17
~/w/w/shell-basics_treasure-hunt/t/f/deep-forest/very-deep-forest/ruins/temple ❯ ls                                                                                                              17:08:23
altar.md
~/w/w/shell-basics_treasure-hunt/t/f/deep-forest/very-deep-forest/ruins/temple ❯ cat altar.md                                                                                                    17:08:24
```
      _.--._  _.--._
,-=.-":;:;:;\':;:;:;"-._
\\\:;:;:;:;:;\:;:;:;:;:;\
 \\\:;:;:;:;:;\:;:;:;:;:;\
  \\\:;:;:;:;:;\:;:;:;:;:;\
   \\\:;:;:;:;:;\:;::;:;:;:\
    \\\;:;::;:;:;\:;:;:;::;:\
     \\\;;:;:_:--:\:_:--:_;:;\
      \\\_.-"      :      "-._\
       \`_..--""--.;.--""--.._=>
        "
```
~/w/w/shell-basics_treasure-hunt/t/f/deep-forest/very-deep-forest/ruins/temple ❯ cd ..                                                                                                           17:08:29
~/w/w/shell-basics_treasure-hunt/t/forest/deep-forest/very-deep-forest/ruins ❯ cd tower                                                                                                          17:09:16
~/w/w/shell-basics_treasure-hunt/t/f/deep-forest/very-deep-forest/ruins/tower ❯ ls                                                                                                               17:09:23
old-door.md
~/w/w/shell-basics_treasure-hunt/t/f/deep-forest/very-deep-forest/ruins/tower ❯ cat old-door.md                                                                                                  17:09:24
```
                           ,--.
                          {    }
                          K,   }
                         /  `Y`
                    _   /   /
                   {_'-K.__/
                     `/-.__L._
                     /  ' /`\_}
                    /  ' /
            ____   /  ' /
     ,-'~~~~    ~~/  ' /_
   ,'             ``~~~%%',
  (                     %  Y
 {                      %% I
{      -                 %  `.
|       ',                %  )
|        |   ,..__      __. Y
|    .,_./  Y ' / ^Y   J   )|
\           |' /   |   |   ||
 \          L_/    . _ (_,.'(
  \,   ,      ^^""' / |      )
    \_  \          /,L]     /
      '-_`-,       ` `   ./`
         `-(_            )
             ^^\..___,.--`
```
~/w/w/shell-basics_treasure-hunt/t/f/deep-forest/very-deep-forest/ruins/tower ❯ cd ..                                                                                                            17:09:31
~/w/w/shell-basics_treasure-hunt/t/forest/deep-forest/very-deep-forest/ruins ❯ ls                                                                                                                17:10:08
temple tower
~/w/w/shell-basics_treasure-hunt/t/forest/deep-forest/very-deep-forest/ruins ❯ cd ..                                                                                                             17:10:10
~/w/w/shell-basics_treasure-hunt/t/forest/deep-forest/very-deep-forest ❯ cd ../..                                                                                                                17:10:14
~/web-bootcamp/web-challenges/shell-basics_treasure-hunt/treasure-island/forest ❯ ls                                                                                                             17:10:22
deep-forest meadow
~/web-bootcamp/web-challenges/shell-basics_treasure-hunt/treasure-island/forest ❯ cd meadow                                                                                                      17:10:26
~/w/web-challenges/shell-basics_treasure-hunt/treasure-island/forest/meadow ❯ ls                                                                                                                 17:10:31
old-tree.md river-bed
~/w/web-challenges/shell-basics_treasure-hunt/treasure-island/forest/meadow ❯ cat old-tree.md                                                                                                    17:10:32
```
             ____
            / . .\
MT          \  ---<
             \  /
   __________/ /
-=:___________/
```
~/w/web-challenges/shell-basics_treasure-hunt/treasure-island/forest/meadow ❯ cd ..                                                                                                              17:10:39
~/web-bootcamp/web-challenges/shell-basics_treasure-hunt/treasure-island/forest ❯ ls                                                                                                             17:11:04
deep-forest meadow
~/web-bootcamp/web-challenges/shell-basics_treasure-hunt/treasure-island/forest ❯ cd meadow                                                                                                      17:11:07
~/w/web-challenges/shell-basics_treasure-hunt/treasure-island/forest/meadow ❯ ls                                                                                                                 17:11:11
old-tree.md river-bed
~/w/web-challenges/shell-basics_treasure-hunt/treasure-island/forest/meadow ❯ cd river bed                                                                                                       17:11:12
cd: string not in pwd: river
~/w/web-challenges/shell-basics_treasure-hunt/treasure-island/forest/meadow ❯ cd river-bed                                                                                                       17:11:17
~/w/w/shell-basics_treasure-hunt/treasure-island/forest/meadow/river-bed ❯ ls                                                                                                                    17:11:26
mountain-path
~/w/w/shell-basics_treasure-hunt/treasure-island/forest/meadow/river-bed ❯ cd mountain-path                                                                                                      17:11:27
~/w/w/shell-basics_treasure-hunt/t/forest/meadow/river-bed/mountain-path ❯ ls                                                                                                                    17:11:35
cave-camp     mountain-peak
~/w/w/shell-basics_treasure-hunt/t/forest/meadow/river-bed/mountain-path ❯ cd cave-camp                                                                                                          17:11:38
~/w/w/shell-basics_treasure-hunt/t/f/meadow/river-bed/mountain-path/cave-camp ❯ ls                                                                                                               17:12:28
piece-of-paper-on-table.md skeleton.md
~/w/w/shell-basics_treasure-hunt/t/f/meadow/river-bed/mountain-path/cave-camp ❯ cat piece-of-paper-on-table.md                                                                                   17:12:29
```
+------------------+
|                  |
|    use ls -la    |
|       near       |
|   the altar in   |
|    the sacred    |
|       halls.     |
|                  |
+------------------+
```
~/w/w/shell-basics_treasure-hunt/t/f/meadow/river-bed/mountain-path/cave-camp ❯ cd ..                                                                                                            17:13:06
~/w/w/shell-basics_treasure-hunt/t/forest/meadow/river-bed/mountain-path ❯ ls                                                                                                                    17:13:29
cave-camp     mountain-peak
~/w/w/shell-basics_treasure-hunt/t/forest/meadow/river-bed/mountain-path ❯ cd cave-camp                                                                                                          17:13:35
~/w/w/shell-basics_treasure-hunt/t/f/meadow/river-bed/mountain-path/cave-camp ❯ ls                                                                                                               17:13:43
piece-of-paper-on-table.md skeleton.md
~/w/w/shell-basics_treasure-hunt/t/f/meadow/river-bed/mountain-path/cave-camp ❯ cat skeleton.md                                                                                                  17:13:45
```
    \ /
    oVo
\___XXX___/
 __XXXXX__
/__XXXXX__\
/   XXX   \
     V
```
~/w/w/shell-basics_treasure-hunt/t/f/meadow/river-bed/mountain-path/cave-camp ❯ cd ..                                                                                                            17:13:51
~/w/w/shell-basics_treasure-hunt/t/forest/meadow/river-bed/mountain-path ❯ ls                                                                                                                    17:14:07
cave-camp     mountain-peak
~/w/w/shell-basics_treasure-hunt/t/forest/meadow/river-bed/mountain-path ❯ cd mountain-peak                                                                                                      17:14:11
~/w/w/shell-basics_treasure-hunt/t/f/m/river-bed/mountain-path/mountain-peak ❯ ls                                                                                                                17:14:16
viewpoint.md
~/w/w/shell-basics_treasure-hunt/t/f/m/river-bed/mountain-path/mountain-peak ❯ cat viewpoint.md                                                                                                  17:14:18
```
                                        |
                                      \ _ /
                                    -= (_) =-
   .\/.                               /   \
.\\//o\\                      ,\/.      |              ,~
//o\\|,\/.   ,.,.,   ,\/.  ,\//o\\                     |\
  |  |//o\  /###/#\  //o\  /o\\|                      /| \
^^|^^|^~|^^^|' '|:|^^^|^^^^^|^^|^^^""""""""("~~~~~~~~/_|__\~~~~~~~~~~
 .|'' . |  '''""'"''. |`===`|''  '"" "" " (" ~~~~ ~ ~======~~  ~~ ~
 jgs^^   ^^^ ^ ^^^ ^^^^ ^^^ ^^ ^^ "" """( " ~~~~~~ ~~~~~  ~~~ ~
```
~/w/w/shell-basics_treasure-hunt/t/f/m/river-bed/mountain-path/mountain-peak ❯ cd ..                                                                                                             17:14:31
~/w/w/shell-basics_treasure-hunt/t/forest/meadow/river-bed/mountain-path ❯ cd ..                                                                                                                 17:19:56
~/w/w/shell-basics_treasure-hunt/treasure-island/forest/meadow/river-bed ❯ cd ..                                                                                                                 17:20:00
~/w/web-challenges/shell-basics_treasure-hunt/treasure-island/forest/meadow ❯ cd ..                                                                                                              17:20:05
~/web-bootcamp/web-challenges/shell-basics_treasure-hunt/treasure-island/forest ❯ ls                                                                                                             17:20:11
deep-forest meadow
~/web-bootcamp/web-challenges/shell-basics_treasure-hunt/treasure-island/forest ❯ cd deep-forest                                                                                                 17:20:13
~/w/web-challenges/shell-basics_treasure-hunt/treasure-island/forest/deep-forest ❯ ls                                                                                                            17:20:21
very-deep-forest
~/w/web-challenges/shell-basics_treasure-hunt/treasure-island/forest/deep-forest ❯ cd very-deep-forest                                                                                           17:20:23
~/w/w/shell-basics_treasure-hunt/t/forest/deep-forest/very-deep-forest ❯ ls                                                                                                                      17:20:32
ruins
~/w/w/shell-basics_treasure-hunt/t/forest/deep-forest/very-deep-forest ❯ cd ruins                                                                                                                17:20:34
~/w/w/shell-basics_treasure-hunt/t/forest/deep-forest/very-deep-forest/ruins ❯ ls                                                                                                                17:20:37
temple tower
~/w/w/shell-basics_treasure-hunt/t/forest/deep-forest/very-deep-forest/ruins ❯ cd temple                                                                                                         17:20:38
~/w/w/shell-basics_treasure-hunt/t/f/deep-forest/very-deep-forest/ruins/temple ❯ ls                                                                                                              17:20:43
altar.md
~/w/w/shell-basics_treasure-hunt/t/f/deep-forest/very-deep-forest/ruins/temple ❯ ls -ls                                                                                                          17:20:44
total 8
8 -rw-r--r--  1 josereyes  staff  300 Jun  4 16:09 altar.md
~/w/w/shell-basics_treasure-hunt/t/f/deep-forest/very-deep-forest/ruins/temple ❯ ls -la                                                                                                          17:20:52
total 8
drwxr-xr-x  4 josereyes  staff  128 Jun  4 16:09 .
drwxr-xr-x  4 josereyes  staff  128 Jun  4 16:09 ..
drwxr-xr-x  3 josereyes  staff   96 Jun  4 16:09 .secret-door
-rw-r--r--  1 josereyes  staff  300 Jun  4 16:09 altar.md
~/w/w/shell-basics_treasure-hunt/t/f/deep-forest/very-deep-forest/ruins/temple ❯ cat .secret-door                                                                                                17:21:03
cat: .secret-door: Is a directory
~/w/w/shell-basics_treasure-hunt/t/f/deep-forest/very-deep-forest/ruins/temple ❯ cat .secret-door                                                                                                17:22:02
cat: .secret-door: Is a directory
~/w/w/shell-basics_treasure-hunt/t/f/deep-forest/very-deep-forest/ruins/temple ❯ cd .secret-door                                                                                                 17:22:18
~/w/w/shell-basics_treasure-hunt/t/f/d/v/ruins/temple/.secret-door ❯ ls                                                                                                                          17:22:51
tunnel
~/w/w/shell-basics_treasure-hunt/t/f/d/v/ruins/temple/.secret-door ❯ cd tunnel                                                                                                                   17:22:52
~/w/w/shell-basics_treasure-hunt/t/f/d/v/ruins/temple/.secret-door/tunnel ❯ ls                                                                                                                   17:22:57
chest.md
~/w/w/shell-basics_treasure-hunt/t/f/d/v/ruins/temple/.secret-door/tunnel ❯ cat chest.md                                                                                                         17:22:58
```
Behold the secret treasure!
  .     '     ,
    _________
 _ /_|_____|_\ _
   '. \   / .'
     '.\ /.'
       '.'
```
~/w/w/shell-basics_treasure-hunt/t/f/d/v/ruins/temple/.secret-door/tunnel ❯ pwd                                                                                                                  17:23:05
/Users/josereyes/web-bootcamp/web-challenges/shell-basics_treasure-hunt/treasure-island/forest/deep-forest/very-deep-forest/ruins/temple/.secret-door/tunnel
~/w/w/shell-basics_treasure-hunt/t/f/d/v/ruins/temple/.secret-door/tunnel ❯ cd ~/web-bootcamp/session-notebook                                                                                   17:25:31
~/web-bootcamp/session-notebook ❯ pwd                                                                                                                                                            17:26:24
/Users/josereyes/web-bootcamp/session-notebook
~/web-bootcamp/session-notebook ❯ touch shell-basics.md                                                                                                                                          17:26:33
~/web-bootcamp/session-notebook ❯ ls                                                                                                                                                             17:27:20
shell-basics.md
~/web-bootcamp/session-notebook ❯ cat shell-basics.md                                                                                                                                            17:27:22
~/web-bootcamp/session-notebook ❯ ls                                                                                                                                                             17:27:38
shell-basics.md
~/web-bootcamp/session-notebook ❯                                                                                                                                                                17:27:40
