# Machine_Learning_Resource_Sharing

> `author`: [tsungruihon](https://github.com/tsungruihon), [tankeryang](https://github.com/tankeryang) and summer.
>
> `date`: 2018-05-18

这是一个共享学习资源的库，请遵守以下提交规则

- 所有资源必须以链接形式提供
- 所有资源必须做好分类，统一放到指定文件夹下
- 严格按照`markdown`格式撰写文档
- 所有文档统一命名`README.md`

------

## 开发流程

### FIRST OF ALL

- 先`fork`[源repo](https://github.com/tsungruihon/Machine-Learning-Resource-Sharing)

- `clone`自己fork后的库到本地:
    ```shell
    git clone git@github.comgit@github.com:YOUR_USERNAME/Machine_Learning_Resource_Sharing.git
    ```

- 添加 __源repo__ 的上游:
    ```shell
    git remote add upstream https://github.com/tsungruihon/Machine_Learning_Resource_Sharing.git
    ```

### HOW TO DEVELOP

- 先抓取 __源repo__ 最新版本到本地:
    ```shell
    git fetch upstream
    ```

- review后无问题则合并至本地`master`:
    ```shell
    git merge upstream/master
    ```

- 每次添加内容前，先拉取自己远程`master`:
    ```shell
    git pull origin master
    ```

- 添加内容，并提交:
    ```shell
    git add <你新加或者修改过的文件>
    git commit -m <添加⼀一个版本修改的说明>
    ```

- 然后`push`到自己的远程库:
    ```shell
    git push origin master
    ```

- 发起`pull request`
- 在 __源repo__ review后无大问题则`comfirm merge`

## Markdown Format

- __链接提供格式__--需用`列表`形式给出资源链接:
    ```markdown
    - [标题1](链接1)
    - [标题2](链接2)
    ```
    显示如下:
    - [标题1](#markdown-format)
    - [标题2](#markdown-format)

- __资源说明__--在链接资源的下方，先用`tab`缩进，再使用`引用`进行说明:
    ```markdown
    - [标题1](链接1)
        > 我是标题1
    - [标题2](链接2)
        > 我是标题2
    ```
    显示如下:
    - [标题1](#markdown-format)
        > 我是标题1
    - [标题2](#markdown-format)
        > 我是标题2