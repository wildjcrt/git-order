## git commit parameters

    $ git commit -v --allow-empty --date="Thu May 7 18:26:48 2015 +0800" --author "Jerry Lee <wildjcrt@gmail.com>"

`-v`: 開啟編輯器寫 commit message，也可以用 `-m` 直接寫在 command 中。

`--allow-empty`: 允許產生沒有變動紀錄的 commit。

`--date`: 指定 AuthorDate，建議直接找一個 commit 去 copy 時間最快。

`--author`: 指定 Author，建議直接找一個 commit 去 copy 時間最快。

    $ git rebase master -k -i

`-i`: rebase 互動模式。

`-k`: 允許 commit 保持沒有變動紀錄。
