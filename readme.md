# 测试github Action的使用方法
[参考文章](https://zhuanlan.zhihu.com/p/670799488)
[yml文件配置文档](https://docs.github.com/cn/actions/using-workflows/workflow-syntax-for-github-actions)
[在工作流程中使用作业](https://docs.github.com/zh/actions/writing-workflows/choosing-what-your-workflow-does)


## 步骤
1. 创建一个项目

2. 添加一个文件夹 .github/workflows

3. 添加一个文件，例如 test.yml

4. 添加内容,其中 <b>working-directory: ./scripts</b> 表示执行文件在scripts文件夹下, 在执行之前必须要先<b>存储库签出到运行器</b>, 也就是<b>uses: actions/checkout@v4</b> 命令

