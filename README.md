# Ina Start

```bash
vagrant destroy && vagrant up
```

Von USB geladen:

```bash
make create-ina
```

<http://192.168.2.10:8888>

```bash
whoami
```

```
vagrant
```

```bash
pwd
```

```
/home/vagrant/www
```

```bash
cloud9_install
```

```
Already up-to-date.
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
100 11980  100 11980    0     0  33712      0 --:--:-- --:--:-- --:--:-- 33651
Installing base packages. Use --help for more options
:Installing Node v4.4.6
--2016-10-19 22:00:50--  https://nodejs.org/dist/v4.4.6/node-v4.4.6-linux-x64.tar.gz
Auflösen des Hostnamen »nodejs.org (nodejs.org)«... 104.20.22.46, 104.20.23.46, 2400:cb00:2048:1::6814:172e, ...
Verbindungsaufbau zu nodejs.org (nodejs.org)|104.20.22.46|:443... verbunden.
HTTP-Anforderung gesendet, warte auf Antwort... 200 OK
Länge: 12174079 (12M) [application/gzip]
In »»node.tar.gz«« speichern.

node.tar.gz         100%[===================>]  11,61M  1,80MB/s    in 6,6s    

2016-10-19 22:00:58 (1,76 MB/s) - »node.tar.gz« gespeichert [12174079/12174079]


real    0m10.959s
user    0m2.824s
sys    0m1.596s
:Installing TMUX
:A good version of tmux was found, creating a symlink

real    0m0.035s
user    0m0.012s
sys    0m0.004s
:Installing Nak
-[0G\[0G|[0G/[0G-[0G\[0G|[0G/[0G-[0G\[0G|[0G/[0G-[0G\[0G|[0G/[0G-[0G\[0G|[0G/[0G-[0G\[0G|[0G/[0G-[0G\[0G|[0G/[0G-[0G\[0G|[0G[37m[40mnpm[0m [0m[30m[43mWARN[0m [0m[35mexcluding symbolic link[0m tests/filelist_fixtures/symlink-to-1.txt -> 1.txt
[0m[37m[40mnpm[0m [0m[30m[43mWARN[0m [0m[35mexcluding symbolic link[0m tests/filelist_fixtures/symlink-to-nowhere.txt -> nowhere.txt
[0m/[0G[37m[40mnpm[0m [0m[30m[43mWARN[0m [0m[35mexcluding symbolic link[0m tests/search_fixtures/symlink-to-file1.txt -> file1.txt
[0m-[0G[37m[40mnpm[0m [0m[30m[43mWARN[0m [0m[35mexcluding symbolic link[0m tests/filelist_fixtures/symlink-to-1.txt -> 1.txt
[0m[37m[40mnpm[0m [0m[30m[43mWARN[0m [0m[35mexcluding symbolic link[0m tests/filelist_fixtures/symlink-to-nowhere.txt -> nowhere.txt
[0m[37m[40mnpm[0m [0m[30m[43mWARN[0m [0m[35mexcluding symbolic link[0m tests/search_fixtures/symlink-to-file1.txt -> file1.txt
[0m-[0G\[0G|[0G/[0G-[0G\[0G|[0G/[0G-[0G[37m[40mnpm[0m [0m[30m[43mWARN[0m [0m[35mengine[0m simplefunc@0.0.2: wanted: {"node":">= 0.6.0 && < 0.9.0"} (current: {"node":"4.4.6","npm":"2.15.5"})
[0mnak@0.3.3 node_modules/nak
├── simplefunc@0.0.2
├── colors@0.6.2
└── isbinaryfile@2.0.0
[2K
real    0m3.806s
user    0m1.604s
sys    0m0.260s
:Installing pty.js
--2016-10-19 22:01:05--  https://github.com/c9/install/releases/download/bin/pty-v4.4.6-linux-x64.tar.gz
Auflösen des Hostnamen »github.com (github.com)«... 192.30.253.113
Verbindungsaufbau zu github.com (github.com)|192.30.253.113|:443... verbunden.
HTTP-Anforderung gesendet, warte auf Antwort... 302 Found
Platz: https://github-cloud.s3.amazonaws.com/releases/15140384/76ba15bc-3b57-11e6-8100-238bb52ef108.gz?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAISTNZFOVBIJMK3TQ%2F20161019%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20161019T200107Z&X-Amz-Expires=300&X-Amz-Signature=be7d7d236bd6e3cb3a349a1ea3544ac0e2b14fe03abbcdc86feda29c7c9b7559&X-Amz-SignedHeaders=host&actor_id=0&response-content-disposition=attachment%3B%20filename%3Dpty-v4.4.6-linux-x64.tar.gz&response-content-type=application%2Foctet-stream [folge]
--2016-10-19 22:01:05--  https://github-cloud.s3.amazonaws.com/releases/15140384/76ba15bc-3b57-11e6-8100-238bb52ef108.gz?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAISTNZFOVBIJMK3TQ%2F20161019%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20161019T200107Z&X-Amz-Expires=300&X-Amz-Signature=be7d7d236bd6e3cb3a349a1ea3544ac0e2b14fe03abbcdc86feda29c7c9b7559&X-Amz-SignedHeaders=host&actor_id=0&response-content-disposition=attachment%3B%20filename%3Dpty-v4.4.6-linux-x64.tar.gz&response-content-type=application%2Foctet-stream
Auflösen des Hostnamen »github-cloud.s3.amazonaws.com (github-cloud.s3.amazonaws.com)«... 54.231.41.19
Verbindungsaufbau zu github-cloud.s3.amazonaws.com (github-cloud.s3.amazonaws.com)|54.231.41.19|:443... verbunden.
HTTP-Anforderung gesendet, warte auf Antwort... 200 OK
Länge: 29252 (29K) [application/octet-stream]
In »»pty.js.tar.gz«« speichern.

pty.js.tar.gz       100%[===================>]  28,57K  --.-KB/s    in 0,1s    

2016-10-19 22:01:06 (255 KB/s) - »pty.js.tar.gz« gespeichert [29252/29252]


real    0m1.181s
user    0m0.084s
sys    0m0.044s
:Installing Collab Dependencies
-[0G\[0G|[0G/[0G-[0G\[0G|[0G/[0G-[0G\[0G|[0G/[0G-[0G\[0G|[0G/[0G-[0G\[0G|[0G/[0G-[0G\[0G|[0G/[0G-[0G\[0G|[0G/[0G-[0G\[0G|[0G/[0G-[0G\[0G|[0G/[0G-[0G\[0G|[0G/[0G-[0G\[0G
> sqlite3@3.1.4 install /home/vagrant/.c9/node_modules/sqlite3
> node-pre-gyp install --fallback-to-build

[sqlite3] Success: "/home/vagrant/.c9/node_modules/sqlite3/lib/binding/node-v46-linux-x64/node_sqlite3.node" is installed via remote
sqlite3@3.1.4 node_modules/sqlite3
└── nan@2.3.5
[2K-[0G\[0G|[0G/[0G-[0G\[0G|[0G-[0G\[0G[37m[40mnpm[0m [0m[30m[43mWARN[0m [0m[35mdeprecated[0m lingo@0.0.5: This project is abandoned
[0m|[0G/[0G-[0G\[0G|[0G/[0G-[0G\[0G|[0G/[0Gsequelize@2.0.0-beta.0 node_modules/sequelize
├── commander@2.0.0
├── promise@3.2.0
├── toposort-class@0.2.1
├── generic-pool@2.0.4
├── dottie@0.0.8-0
├── lingo@0.0.5
├── validator@1.5.1
├── lodash@1.3.1
├── underscore.string@2.3.3
├── sql@0.26.0 (sliced@0.0.5)
└── moment@2.1.0
[2K--2016-10-19 22:01:21--  https://raw.githubusercontent.com/c9/install/master/packages/sqlite3/linux/sqlite3.tar.gz
Auflösen des Hostnamen »raw.githubusercontent.com (raw.githubusercontent.com)«... 151.101.12.133
Verbindungsaufbau zu raw.githubusercontent.com (raw.githubusercontent.com)|151.101.12.133|:443... verbunden.
HTTP-Anforderung gesendet, warte auf Antwort... 200 OK
Länge: 4350866 (4,1M) [application/octet-stream]
In »»sqlite3.tar.gz«« speichern.

sqlite3.tar.gz      100%[===================>]   4,15M  1,78MB/s    in 2,3s    

2016-10-19 22:01:26 (1,78 MB/s) - »sqlite3.tar.gz« gespeichert [4350866/4350866]


real    0m20.409s
user    0m9.788s
sys    0m1.896s
~/.c9/node_modules/.bin ~/.c9/lib
~/.c9/lib
:Done.
c9.ide.language
updating plugin [01;34m1[0m of [01;34m64[0m
[01;32mchecking out [0mhttps://github.com/c9/c9.ide.language
~/cloud9/plugins/c9.ide.language ~/cloud9
HEAD ist jetzt bei 241bd6b Apply code conventions
~/cloud9
c9.ide.language.core
updating plugin [01;34m2[0m of [01;34m64[0m
[01;32mchecking out [0mhttps://github.com/c9/c9.ide.language.core
~/cloud9/plugins/c9.ide.language.core ~/cloud9
HEAD ist jetzt bei bfb5dd2 Merge pull request +14321 from c9/ide-fix-various
~/cloud9
c9.ide.language.css
updating plugin [01;34m3[0m of [01;34m64[0m
[01;32mchecking out [0mhttps://github.com/c9/c9.ide.language.css
~/cloud9/plugins/c9.ide.language.css ~/cloud9
HEAD ist jetzt bei 46ad561 Split c9.ide.language into two plugins
~/cloud9
c9.ide.language.generic
updating plugin [01;34m4[0m of [01;34m64[0m
[01;32mchecking out [0mhttps://github.com/c9/c9.ide.language.generic
~/cloud9/plugins/c9.ide.language.generic ~/cloud9
HEAD ist jetzt bei b47cbe5 Change to Cloud9 SDK license
~/cloud9
c9.ide.language.html
updating plugin [01;34m5[0m of [01;34m64[0m
[01;32mchecking out [0mhttps://github.com/c9/c9.ide.language.html
~/cloud9/plugins/c9.ide.language.html ~/cloud9
HEAD ist jetzt bei cdc3960 Add dual MIT + SDK license
~/cloud9
c9.ide.language.html.diff
updating plugin [01;34m6[0m of [01;34m64[0m
[01;32mchecking out [0mhttps://github.com/c9/c9.ide.language.html.diff
~/cloud9/plugins/c9.ide.language.html.diff ~/cloud9
HEAD ist jetzt bei 7d6cecf Change to Cloud9 SDK license
~/cloud9
c9.ide.language.javascript
updating plugin [01;34m7[0m of [01;34m64[0m
[01;32mchecking out [0mhttps://github.com/c9/c9.ide.language.javascript
~/cloud9/plugins/c9.ide.language.javascript ~/cloud9
HEAD ist jetzt bei a5c1d05 fix several flaky tests
~/cloud9
c9.ide.language.javascript.immediate
updating plugin [01;34m8[0m of [01;34m64[0m
[01;32mchecking out [0mhttps://github.com/c9/c9.ide.language.javascript.immediate
~/cloud9/plugins/c9.ide.language.javascript.immediate ~/cloud9
HEAD ist jetzt bei 82c426d Change to Cloud9 SDK license
~/cloud9
c9.ide.language.javascript.eslint
updating plugin [01;34m9[0m of [01;34m64[0m
[01;32mchecking out [0mhttps://github.com/c9/c9.ide.language.javascript.eslint
~/cloud9/plugins/c9.ide.language.javascript.eslint ~/cloud9
HEAD ist jetzt bei 342a071 Fix match of undefined
~/cloud9
c9.ide.language.javascript.tern
updating plugin [01;34m10[0m of [01;34m64[0m
[01;32mchecking out [0mhttps://github.com/c9/c9.ide.language.javascript.tern
~/cloud9/plugins/c9.ide.language.javascript.tern ~/cloud9
HEAD ist jetzt bei 0545a63 remove browsersupport.js
~/cloud9
c9.ide.language.javascript.infer
updating plugin [01;34m11[0m of [01;34m64[0m
[01;32mchecking out [0mhttps://github.com/c9/c9.ide.language.javascript.infer
~/cloud9/plugins/c9.ide.language.javascript.infer ~/cloud9
HEAD ist jetzt bei b9c2e4b Change to Cloud9 SDK license
~/cloud9
c9.ide.language.jsonalyzer
updating plugin [01;34m12[0m of [01;34m64[0m
[01;32mchecking out [0mhttps://github.com/c9/c9.ide.language.jsonalyzer
~/cloud9/plugins/c9.ide.language.jsonalyzer ~/cloud9
HEAD ist jetzt bei a0549e1 Merge pull request +14231 from c9/ide-fix-python-trash
~/cloud9
c9.ide.language.codeintel
updating plugin [01;34m13[0m of [01;34m64[0m
[01;32mchecking out [0mhttps://github.com/c9/c9.ide.language.codeintel
~/cloud9/plugins/c9.ide.language.codeintel ~/cloud9
HEAD ist jetzt bei 0fe92d6 Clarify OSX installation
~/cloud9
c9.ide.collab
updating plugin [01;34m14[0m of [01;34m64[0m
[01;32mchecking out [0mhttps://github.com/c9/c9.ide.collab
~/cloud9/plugins/c9.ide.collab ~/cloud9
HEAD ist jetzt bei a414999 Bump
~/cloud9
c9.ide.local
updating plugin [01;34m15[0m of [01;34m64[0m
[01;32mchecking out [0mhttps://github.com/c9/c9.ide.local
~/cloud9/plugins/c9.ide.local ~/cloud9
HEAD ist jetzt bei 9169fec Change to Cloud9 SDK license
~/cloud9
c9.ide.find
updating plugin [01;34m16[0m of [01;34m64[0m
[01;32mchecking out [0mhttps://github.com/c9/c9.ide.find
~/cloud9/plugins/c9.ide.find ~/cloud9
HEAD ist jetzt bei e632ecf fix and unblacklist several tests
~/cloud9
c9.ide.find.infiles
updating plugin [01;34m17[0m of [01;34m64[0m
[01;32mchecking out [0mhttps://github.com/c9/c9.ide.find.infiles
~/cloud9/plugins/c9.ide.find.infiles ~/cloud9
HEAD ist jetzt bei ad9ff74 Removed unnecessary if condition
~/cloud9
c9.ide.find.replace
updating plugin [01;34m18[0m of [01;34m64[0m
[01;32mchecking out [0mhttps://github.com/c9/c9.ide.find.replace
~/cloud9/plugins/c9.ide.find.replace ~/cloud9
HEAD ist jetzt bei 8468067 fix and unblacklist several tests
~/cloud9
c9.ide.run.debug
updating plugin [01;34m19[0m of [01;34m64[0m
[01;32mchecking out [0mhttps://github.com/c9/c9.ide.run.debug
~/cloud9/plugins/c9.ide.run.debug ~/cloud9
HEAD ist jetzt bei 8963fb4 Merge remote-tracking branch 'remotes/origin/pull/c9.ide.run.debug/44'
~/cloud9
c9.automate
updating plugin [01;34m20[0m of [01;34m64[0m
[01;32mchecking out [0mhttps://github.com/c9/c9.automate
~/cloud9/plugins/c9.automate ~/cloud9
HEAD ist jetzt bei 47e2c42 Headless now takes the normal flow
~/cloud9
c9.ide.ace.emmet
updating plugin [01;34m21[0m of [01;34m64[0m
[01;32mchecking out [0mhttps://github.com/c9/c9.ide.ace.emmet
~/cloud9/plugins/c9.ide.ace.emmet ~/cloud9
HEAD ist jetzt bei 6dc4585 allow expand_abbreviation emmet command for all modes
~/cloud9
c9.ide.ace.gotoline
updating plugin [01;34m22[0m of [01;34m64[0m
[01;32mchecking out [0mhttps://github.com/c9/c9.ide.ace.gotoline
~/cloud9/plugins/c9.ide.ace.gotoline ~/cloud9
HEAD ist jetzt bei d33220b fix several flaky tests
~/cloud9
c9.ide.ace.keymaps
updating plugin [01;34m23[0m of [01;34m64[0m
[01;32mchecking out [0mhttps://github.com/c9/c9.ide.ace.keymaps
~/cloud9/plugins/c9.ide.ace.keymaps ~/cloud9
HEAD ist jetzt bei 15e7d23 add warning about vimium breaking cloud9 keyboard shortcuts
~/cloud9
c9.ide.ace.repl
updating plugin [01;34m24[0m of [01;34m64[0m
[01;32mchecking out [0mhttps://github.com/c9/c9.ide.ace.repl
~/cloud9/plugins/c9.ide.ace.repl ~/cloud9
HEAD ist jetzt bei 4b88a85 Merge pull request +9561 from c9/fix/repl
~/cloud9
c9.ide.ace.split
updating plugin [01;34m25[0m of [01;34m64[0m
[01;32mchecking out [0mhttps://github.com/c9/c9.ide.ace.split
~/cloud9/plugins/c9.ide.ace.split ~/cloud9
HEAD ist jetzt bei 0ae0151 fix error in package.json files
~/cloud9
c9.ide.ace.statusbar
updating plugin [01;34m26[0m of [01;34m64[0m
[01;32mchecking out [0mhttps://github.com/c9/c9.ide.ace.statusbar
~/cloud9/plugins/c9.ide.ace.statusbar ~/cloud9
HEAD ist jetzt bei 3aab0b6 adapt statusbar to ace api changes
~/cloud9
c9.ide.ace.stripws
updating plugin [01;34m27[0m of [01;34m64[0m
[01;32mchecking out [0mhttps://github.com/c9/c9.ide.ace.stripws
~/cloud9/plugins/c9.ide.ace.stripws ~/cloud9
HEAD ist jetzt bei 042a993 add setting for stripwsKeepCursorPosition
~/cloud9
c9.ide.behaviors
updating plugin [01;34m28[0m of [01;34m64[0m
[01;32mchecking out [0mhttps://github.com/c9/c9.ide.behaviors
~/cloud9/plugins/c9.ide.behaviors ~/cloud9
HEAD ist jetzt bei 6fe68de Remove default key bindings
~/cloud9
c9.ide.closeconfirmation
updating plugin [01;34m29[0m of [01;34m64[0m
[01;32mchecking out [0mhttps://github.com/c9/c9.ide.closeconfirmation
~/cloud9/plugins/c9.ide.closeconfirmation ~/cloud9
HEAD ist jetzt bei cee4674 For SmartfaceCloud project added support for custom IDE provider name
~/cloud9
c9.ide.configuration
updating plugin [01;34m30[0m of [01;34m64[0m
[01;32mchecking out [0mhttps://github.com/c9/c9.ide.configuration
~/cloud9/plugins/c9.ide.configuration ~/cloud9
HEAD ist jetzt bei a936df2 change confusing quit and restart items in cloud9 menu
~/cloud9
c9.ide.dialog.wizard
updating plugin [01;34m31[0m of [01;34m64[0m
[01;32mchecking out [0mhttps://github.com/c9/c9.ide.dialog.wizard
~/cloud9/plugins/c9.ide.dialog.wizard ~/cloud9
HEAD ist jetzt bei 7667ec7 Fix installer button issue
~/cloud9
c9.ide.fontawesome
updating plugin [01;34m32[0m of [01;34m64[0m
[01;32mchecking out [0mhttps://github.com/c9/c9.ide.fontawesome
~/cloud9/plugins/c9.ide.fontawesome ~/cloud9
HEAD ist jetzt bei 781602c fix error in package.json files
~/cloud9
c9.ide.format
updating plugin [01;34m33[0m of [01;34m64[0m
[01;32mchecking out [0mhttps://github.com/c9/c9.ide.format
~/cloud9/plugins/c9.ide.format ~/cloud9
HEAD ist jetzt bei 1e7a5b3 update js_beautify
~/cloud9
c9.ide.help.support
updating plugin [01;34m34[0m of [01;34m64[0m
[01;32mchecking out [0mhttps://github.com/c9/c9.ide.help.support
~/cloud9/plugins/c9.ide.help.support ~/cloud9
HEAD ist jetzt bei fbe8eb5 Call identify on support menu loading in the ide
~/cloud9
c9.ide.imgeditor
updating plugin [01;34m35[0m of [01;34m64[0m
[01;32mchecking out [0mhttps://github.com/c9/c9.ide.imgeditor
~/cloud9/plugins/c9.ide.imgeditor ~/cloud9
HEAD ist jetzt bei 612e75e fix selection in imgeditor
~/cloud9
c9.ide.immediate
updating plugin [01;34m36[0m of [01;34m64[0m
[01;32mchecking out [0mhttps://github.com/c9/c9.ide.immediate
~/cloud9/plugins/c9.ide.immediate ~/cloud9
HEAD ist jetzt bei 0b0ee74 Allow tooltip nodes which have lazily-loaded children to be expanded
~/cloud9
c9.ide.installer
updating plugin [01;34m37[0m of [01;34m64[0m
[01;32mchecking out [0mhttps://github.com/c9/c9.ide.installer
~/cloud9/plugins/c9.ide.installer ~/cloud9
HEAD ist jetzt bei 2921efa update installer
~/cloud9
c9.ide.language.python
updating plugin [01;34m38[0m of [01;34m64[0m
[01;32mchecking out [0mhttps://github.com/c9/c9.ide.language.python
~/cloud9/plugins/c9.ide.language.python ~/cloud9
HEAD ist jetzt bei 9fba572 Merge pull request +14231 from c9/ide-fix-python-trash
~/cloud9
c9.ide.language.go
updating plugin [01;34m39[0m of [01;34m64[0m
[01;32mchecking out [0mhttps://github.com/c9/c9.ide.language.go
~/cloud9/plugins/c9.ide.language.go ~/cloud9
HEAD ist jetzt bei 6ce1c7a Tweak completer configs
~/cloud9
c9.ide.navigate
updating plugin [01;34m40[0m of [01;34m64[0m
[01;32mchecking out [0mhttps://github.com/c9/c9.ide.navigate
~/cloud9/plugins/c9.ide.navigate ~/cloud9
HEAD ist jetzt bei 5d57070 Revert "Revert "Revert "Revert "Vfs fix extend""""
~/cloud9
c9.ide.newresource
updating plugin [01;34m41[0m of [01;34m64[0m
[01;32mchecking out [0mhttps://github.com/c9/c9.ide.newresource
~/cloud9/plugins/c9.ide.newresource ~/cloud9
HEAD ist jetzt bei 981a408 Fix reserved key
~/cloud9
c9.ide.openfiles
updating plugin [01;34m42[0m of [01;34m64[0m
[01;32mchecking out [0mhttps://github.com/c9/c9.ide.openfiles
~/cloud9/plugins/c9.ide.openfiles ~/cloud9
HEAD ist jetzt bei 2ae85a9 fix title of openfiles tree
~/cloud9
c9.ide.preview
updating plugin [01;34m43[0m of [01;34m64[0m
[01;32mchecking out [0mhttps://github.com/c9/c9.ide.preview
~/cloud9/plugins/c9.ide.preview ~/cloud9
HEAD ist jetzt bei 5f5fff0 Revert "Revert "Merge branch 'master' of github.com:c9/newclient""
~/cloud9
c9.ide.preview.browser
updating plugin [01;34m44[0m of [01;34m64[0m
[01;32mchecking out [0mhttps://github.com/c9/c9.ide.preview.browser
~/cloud9/plugins/c9.ide.preview.browser ~/cloud9
HEAD ist jetzt bei 829f0ac always open pdf in browser previewer instead of raw
~/cloud9
c9.ide.preview.markdown
updating plugin [01;34m45[0m of [01;34m64[0m
[01;32mchecking out [0mhttps://github.com/c9/c9.ide.preview.markdown
~/cloud9/plugins/c9.ide.preview.markdown ~/cloud9
HEAD ist jetzt bei c3174d8 add meta utf8
~/cloud9
c9.ide.pubsub
updating plugin [01;34m46[0m of [01;34m64[0m
[01;32mchecking out [0mhttps://github.com/c9/c9.ide.pubsub
~/cloud9/plugins/c9.ide.pubsub ~/cloud9
HEAD ist jetzt bei 99b7289 fix pubsub connection with old vfs
~/cloud9
c9.ide.readonly
updating plugin [01;34m47[0m of [01;34m64[0m
[01;32mchecking out [0mhttps://github.com/c9/c9.ide.readonly
~/cloud9/plugins/c9.ide.readonly ~/cloud9
HEAD ist jetzt bei 7421caa fix out of quota message for non admin users
~/cloud9
c9.ide.recentfiles
updating plugin [01;34m48[0m of [01;34m64[0m
[01;32mchecking out [0mhttps://github.com/c9/c9.ide.recentfiles
~/cloud9/plugins/c9.ide.recentfiles ~/cloud9
HEAD ist jetzt bei 7c099ab fix error in package.json files
~/cloud9
c9.ide.remote
updating plugin [01;34m49[0m of [01;34m64[0m
[01;32mchecking out [0mhttps://github.com/c9/c9.ide.remote
~/cloud9/plugins/c9.ide.remote ~/cloud9
HEAD ist jetzt bei 301d2ab breathe, =, breathe
~/cloud9
c9.ide.processlist
updating plugin [01;34m50[0m of [01;34m64[0m
[01;32mchecking out [0mhttps://github.com/c9/c9.ide.processlist
~/cloud9/plugins/c9.ide.processlist ~/cloud9
HEAD ist jetzt bei 2b12cd1 fix incorrect line height in processlist datagrid
~/cloud9
c9.ide.run
updating plugin [01;34m51[0m of [01;34m64[0m
[01;32mchecking out [0mhttps://github.com/c9/c9.ide.run
~/cloud9/plugins/c9.ide.run ~/cloud9
HEAD ist jetzt bei 3cd1f25 workaround for writing gdbshim too frequently
~/cloud9
c9.ide.run.build
updating plugin [01;34m52[0m of [01;34m64[0m
[01;32mchecking out [0mhttps://github.com/c9/c9.ide.run.build
~/cloud9/plugins/c9.ide.run.build ~/cloud9
HEAD ist jetzt bei 0598fff Revert "Revert "[Trivial] fix sdk issues""
~/cloud9
c9.ide.run.debug.xdebug
updating plugin [01;34m53[0m of [01;34m64[0m
[01;32mchecking out [0mhttps://github.com/c9/c9.ide.run.debug.xdebug
~/cloud9/plugins/c9.ide.run.debug.xdebug ~/cloud9
HEAD ist jetzt bei 0543675 disable tests failing on phantomjs
~/cloud9
c9.ide.save
updating plugin [01;34m54[0m of [01;34m64[0m
[01;32mchecking out [0mhttps://github.com/c9/c9.ide.save
~/cloud9/plugins/c9.ide.save ~/cloud9
HEAD ist jetzt bei 25a63f3 Add vfs.log mock to tests
~/cloud9
c9.ide.scm
updating plugin [01;34m55[0m of [01;34m64[0m
[01;32mchecking out [0mhttps://github.com/c9/c9.ide.scm
~/cloud9/plugins/c9.ide.scm ~/cloud9
HEAD ist jetzt bei 637a68c fix error in twoway diff viewer
~/cloud9
c9.ide.terminal.monitor
updating plugin [01;34m56[0m of [01;34m64[0m
[01;32mchecking out [0mhttps://github.com/c9/c9.ide.terminal.monitor
~/cloud9/plugins/c9.ide.terminal.monitor ~/cloud9
HEAD ist jetzt bei 5a6a54c fix monitor test
~/cloud9
c9.ide.test
updating plugin [01;34m57[0m of [01;34m64[0m
[01;32mchecking out [0mhttps://github.com/c9/c9.ide.test
~/cloud9/plugins/c9.ide.test ~/cloud9
HEAD ist jetzt bei 102942a Moved commit to a panel and tweaks to single line ace
~/cloud9
c9.ide.test.mocha
updating plugin [01;34m58[0m of [01;34m64[0m
[01;32mchecking out [0mhttps://github.com/c9/c9.ide.test.mocha
~/cloud9/plugins/c9.ide.test.mocha ~/cloud9
HEAD ist jetzt bei 38151a9 Split c9.ide.language into two plugins
~/cloud9
c9.ide.theme.flat
updating plugin [01;34m59[0m of [01;34m64[0m
[01;32mchecking out [0mhttps://github.com/c9/c9.ide.theme.flat
~/cloud9/plugins/c9.ide.theme.flat ~/cloud9
HEAD ist jetzt bei 81dadee fix menubar issue when switching between flat themes
~/cloud9
c9.ide.threewaymerge
updating plugin [01;34m60[0m of [01;34m64[0m
[01;32mchecking out [0mhttps://github.com/c9/c9.ide.threewaymerge
~/cloud9/plugins/c9.ide.threewaymerge ~/cloud9
HEAD ist jetzt bei 229382a fix error in package.json files
~/cloud9
c9.ide.undo
updating plugin [01;34m61[0m of [01;34m64[0m
[01;32mchecking out [0mhttps://github.com/c9/c9.ide.undo
~/cloud9/plugins/c9.ide.undo ~/cloud9
HEAD ist jetzt bei b028bcb fix error in package.json files
~/cloud9
c9.ide.upload
updating plugin [01;34m62[0m of [01;34m64[0m
[01;32mchecking out [0mhttps://github.com/c9/c9.ide.upload
~/cloud9/plugins/c9.ide.upload ~/cloud9
HEAD ist jetzt bei e4351f5 upload_manager_test can run only on chrome
~/cloud9
c9.ide.welcome
updating plugin [01;34m63[0m of [01;34m64[0m
[01;32mchecking out [0mhttps://github.com/c9/c9.ide.welcome
~/cloud9/plugins/c9.ide.welcome ~/cloud9
HEAD ist jetzt bei 7b75aef Revert "Remove obsolete onlinedev_helper.js"
~/cloud9
c9.ide.guide
updating plugin [01;34m64[0m of [01;34m64[0m
[01;32mchecking out [0mhttps://github.com/c9/c9.ide.guide
~/cloud9/plugins/c9.ide.guide ~/cloud9
HEAD ist jetzt bei 19f6087 Fix plus button bubble going offscreen
~/cloud9
[01;35m--- Running npm install --------------------------------------------[0m
-[0G\[0G|[0G/[0G-[0G\[0G|[0G/[0G-[0G\[0G|[0G/[0G-[0G\[0G|[0G/[0G-[0G\[0G|[0G/[0G-[0G\[0G|[0G/[0G-[0G\[0G|[0G/[0G-[0G\[0G|[0G/[0G-[0G\[0G|[0G/[0G-[0G\[0G[37m[40mnpm[0m [0m[30m[43mWARN[0m [0m[35mengine[0m simplefunc@0.0.2: wanted: {"node":">= 0.6.0 && < 0.9.0"} (current: {"node":"4.6.1","npm":"2.15.9"})
[0memmet@0.0.1 node_modules/emmet

nak@0.3.3 node_modules/nak
├── simplefunc@0.0.2
├── colors@0.6.2
└── isbinaryfile@2.0.0
[2K[01;35m--------------------------------------------------------------------[0m
Success!
run '[01;33mnode server.js -p 8080 -a :[0m' to launch Cloud9
```

```bash
cloud9_init
```

```
                        -------------

   Looking for a complete monitoring and management tool for PM2?
    _                             _        _            _
   | | _____ _   _ _ __ ___   ___| |_ _ __(_) ___ ___  (_) ___
   | |/ / _ \ | | | '_ ` _ \ / _ \ __| '__| |/ __/ __| | |/ _ \
   |   <  __/ |_| | | | | | |  __/ |_| |  | | (__\__ \_| | (_) |
   |_|\_\___|\__, |_| |_| |_|\___|\__|_|  |_|\___|___(_)_|\___/
             |___/

                          Features

                   - Real Time Dashboard
                   - CPU/Memory monitoring
                   - HTTP monitoring
                   - Event notification
                   - Custom value monitoring
                   - Real Time log display

                          Checkout

                   https://keymetrics.io/

                        -------------

[PM2] Spawning PM2 daemon with pm2_home=/home/vagrant/.pm2
[PM2] PM2 Successfully daemonized
[PM2] Starting /home/vagrant/cloud9/server.js in fork_mode (1 instance)
[PM2] Done.
┌──────────┬────┬──────┬──────┬────────┬─────────┬────────┬─────┬───────────┬──────────┐
│ App name │ id │ mode │ pid  │ status │ restart │ uptime │ cpu │ mem       │ watching │
├──────────┼────┼──────┼──────┼────────┼─────────┼────────┼─────┼───────────┼──────────┤
│ server   │ 0  │ fork │ 5931 │ online │ 0       │ 0s     │ 12% │ 21.3 MB   │ disabled │
└──────────┴────┴──────┴──────┴────────┴─────────┴────────┴─────┴───────────┴──────────┘
 Use `pm2 show <id|name>` to get more details about an app
```

<http://192.168.2.10:8181>

Zum Stoppen:

```bash
vagrant halt
```

Zum erneuten Starten:

```bash
vagrant up
```

Achtung: Cloud9 startet noch nicht automatisch neu. Daher `cloud9_init`

```bash
```
