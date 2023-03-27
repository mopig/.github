# About default community health files

> [Community health files](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file)

您可以将默认的社区健康文件添加到名为 `.github` 的公共存储库中，该存储库位于根目录或 `docs` 或 `.github` 文件夹中。 

`GitHub` 将使用并显示默认文件，用于任何由账户拥有但没有自己类型的文件的存储库，在以下任何一个位置都没有：

- 存储库根目录
- `.github` 文件夹
- `docs` 文件夹

例如，对于在没有自己 `CONTRIBUTING` 文件的存储库中创建问题或拉取请求的任何人都会看到指向默认 `CONTRIBUTING` 文件的链接。如果仓库在其自己 `.github/ISSUE_TEMPLATE` 文件夹中有任何文件（包括问题模板或 `config.yml` 文件），则不会使用默认 `.github/ISSUE_TEMPLATE` 文件夹中内容。

因为它们只保存在 `.github` 存储库中，默认文件不包含在单个存储库克隆、软件包或下载中。
