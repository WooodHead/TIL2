---
icon: ð
slug: 'npmì-missing-write-access-error'
title: 'NPMì "Missing write access error"'
main_category: ETC
category: 2. Bug Fix
created_time: 2021-03-09
---

## ìë¬ ìí©

NPMì ì²ì ì¤ì¹íê³  `global` ìµìì¼ë¡ `yarn` ì ì¤ì¹íë ¤ê³  í  ë ìë¬ê° ë°ìíë¤.

```bash
Missing write access to /usr/local/lib/node_modules
```

![2021-03-09-npmì-missing-write-access-error-image-0](./images/2021-03-09-npmì-missing-write-access-error-image-0.png)

í´ë¹ ëë í ë¦¬ì ì°ê¸° ê¶íì´ ìë¤ë ë»ì´ê¸° ëë¬¸ì, ë¤ìì ëªë ¹ì´ë¥¼ ì¤ííë¤.

```bash
sudo chown -R $USER /usr/local/lib/node_modules
```

<br />
