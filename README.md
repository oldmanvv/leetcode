# 用typescript刷leetcode题

我的环境：
* VSCode: 1.66.2
* Node.js: 16.13.0
* TypeScript: 4.6.3
* OS: Windows_NT x64 10.0.19044

`src/0099/题号.ts`，是第1~99题，目录以此类推
`src/base/` ts实现的常用基础库，如链表
`.eslintrc.js` ESLint规则
`.eslintignore` ESLint忽略文件
`.vscode` 该工程的vscode设置
`tsconfig.json` TypeScript编译设置

我的步骤：

1. 先写测试用例`题号.test.ts`，用单元测试框架`mocha`，NodeJS自带断言库`assert`
2. 做题`题号.ts`，调试用`npm run tsc --file=0099/题号.ts`单独编译该文件
3. `npm start --file=0099/题号.ts` 编译题目和跑测试
