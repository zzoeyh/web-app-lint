# web-app-lint

React项目lint配置:
eslint,prettier,husky,commitlint

src中的app.tsx为测试使用,故没有安装react依赖

**eslint**:检测不符合lint规范的代码,eslint 的 --fix 的参数可以用来进行自动修复
**husky**:在代码提交的阶段来保证代码规范

husky使用:
1. pnpm run prepare
2. npx husky install
3. npx husky add...
要按照这个顺序初始化husky,并且要保持版本与其他的配置对应,不然容易创建文件失败,
报错内容:add command is deprecated

**commitlint**:进行 commit 信息的检查