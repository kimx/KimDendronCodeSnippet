---
id: 25z42y6qibr7ti2hr6fyw9v
title: Commit
desc: ''
updated: 1673415504420
created: 1673409516656
---

## Note
- 簽入相關應用

## Code

``` git
git commit -m message
```

- 加入及簽入一起
``` git
git commit -a -m ""
```

- 將add的併入最近一次的commit **(不要用在已Push的commit)**
- ps: 要先add (在vs叫stage)
``` git
git commit --amend --no-edit
```

- 承上:加上訊息 **(不要用在已Push的commit)**
- ps: 要先add (在vs叫stage)
``` git
git commit --amend -m "message"
```

## Reference