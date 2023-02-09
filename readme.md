1. 代码上传检测规范
2. git提交规范管理

Note:
在项目开发配置前，请在 Terminal中运行以下命令：
cp pre-commit-ktlint .git/hooks/pre-commit
这个命令将会在你每次提交代码时，执行pre-commit-klint脚本，这个脚本将自动检测你的代码格式，如果有问题，你将无法提交代码。

Note:
手动检测项目代码格式，请在提交代码前，手动输入以下命令：
./gradlew ktlintCheck
并将报错的地方进行修改，知道运行这个命令结果为 “build successful.”