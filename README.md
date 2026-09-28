# 武汉大学物联网安全实验室网站

## 文件结构

```
index.html        网站页面（样式和显示逻辑，平时不用改）
data/             全部内容，每个栏目一个文件
  lab.json          实验室名称、简介、首页数字、联系方式
  news.json         新闻动态
  research.json     研究方向
  team.json         负责人、研究人员、博士后、学生
  projects.json     科研项目
  output.json       论文、奖励、专利、著作
  training.json     毕业生去向、培养方式、校友寄语
  join.json         招聘岗位
images/           照片（通过后台上传）
.pages.yml        后台表单配置
```

## 成员怎么更新内容（推荐：网页后台）

1. 打开 https://app.pagescms.org ，用自己的 GitHub 账号登录。
2. 选择本仓库，左侧菜单就是网站的各个栏目。
3. 例如发新闻：点「新闻动态」→「添加」→ 填写日期、类别、标题、摘要 →「保存」。
4. 保存后 1–2 分钟，网站自动更新。


