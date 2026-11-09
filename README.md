# yemufist

一个用来练习 Git 与 GitHub 基本操作的静态页面项目。

## 这个仓库是什么

这里不是成品网站，而是一个练习用的最小项目骨架：一个说明文件、一份忽略清单，加一个可以直接打开的单页。它存在的目的是让人完整走一遍"本地写文件 → 提交 → 推送到 GitHub → 用 Pages 发布成网页"的流程。

## 目录结构

```
yemufist/
├─ index.html    单页，双击即可在浏览器打开
├─ README.md     本文件
└─ .gitignore    忽略清单，避免把缓存和本地配置提交上去
```

## 本地查看

直接双击 `index.html`，或在文件所在目录执行：

```
start index.html
```

## 发布成网页

已通过 Settings → Pages 开启发布：来源 Deploy from a branch，分支 `main`，目录 `/ (root)`。

线上地址：`https://lengjingalarm.github.io/yemufist/`

每次推送到 `main` 后会自动重新构建，通常一分钟内生效；构建记录在仓库的 Actions 里，工作流名为 pages build and deployment。

## 还可以接着练什么

- 新建一条分支修改 `index.html`，合并回 `main`，观察提交历史的变化；
- 修改本文件的说明，提交时写清楚改了什么、为什么改；
- 在网页端直接编辑文件，对比网页提交与本地提交的区别。
