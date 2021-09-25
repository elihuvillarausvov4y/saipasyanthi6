# Contributing

If you discover issues, have ideas for improvements or new features, or
want to contribute a new module, please report them to the
[issue tracker][1] of the repository or submit a pull request. Please,
try to follow these guidelines when you do so.

## Issue reporting

* Check that the issue has not already been reported.
* Check that the issue has not already been fixed in the latest code
  (a.k.a. `master`).
* Be clear, concise and precise in your description of the problem.
* Open an issue with a descriptive title and a summary in grammatically correct,
  complete sentences.
* Include any relevant code to the issue summary.

## Pull requests

* Use a topic branch to easily amend a pull request later, if necessary.
* Write good commit messages.
* Use the same coding conventions as the rest of the project.
* Ensure your edited codes with four spaces instead of TAB.
* Please commit code to `dev` branch and we will merge into `master` branch in feature

## Install environment

#### Create empty project

```console
$ npm install -g yo generator-code
$ yo code
```

#### Create publisher

```console
$ npm install -g vsce
$ vsce create-publisher (publisher name)
$ vsce login (publisher name)
```

#### Build and publish

```console
$ vsce package
$ vsce publish [version]
```

## Financial contributions

We also welcome financial contributions in full transparency on our [open collective](https://opencollective.com/xmake).
Anyone can file an expense. If the expense makes sense for the development of the community, it will be "merged" in the ledger of our open collective by the core contributors and the person who filed the expense will be reimbursed.

## Credits

### Backers

Thank you to all our backers! [[Become a backer](https://opencollective.com/xmake#backer)]

<a href="https://opencollective.com/xmake#backers" target="_blank"><img src="https://opencollective.com/xmake/backers.svg?width=890"></a>

### Sponsors

Thank you to all our sponsors! (please ask your company to also support this open source project by [becoming a sponsor](https://opencollective.com/xmake#sponsor))

<a href="https://opencollective.com/xmake/sponsor/0/website" target="_blank"><img src="https://opencollective.com/xmake/sponsor/0/avatar.svg"></a>
<a href="https://opencollective.com/xmake/sponsor/1/website" target="_blank"><img src="https://opencollective.com/xmake/sponsor/1/avatar.svg"></a>
<a href="https://opencollective.com/xmake/sponsor/2/website" target="_blank"><img src="https://opencollective.com/xmake/sponsor/2/avatar.svg"></a>
<a href="https://opencollective.com/xmake/sponsor/3/website" target="_blank"><img src="https://opencollective.com/xmake/sponsor/3/avatar.svg"></a>
<a href="https://opencollective.com/xmake/sponsor/4/website" target="_blank"><img src="https://opencollective.com/xmake/sponsor/4/avatar.svg"></a>
<a href="https://opencollective.com/xmake/sponsor/5/website" target="_blank"><img src="https://opencollective.com/xmake/sponsor/5/avatar.svg"></a>
<a href="https://opencollective.com/xmake/sponsor/6/website" target="_blank"><img src="https://opencollective.com/xmake/sponsor/6/avatar.svg"></a>
<a href="https://opencollective.com/xmake/sponsor/7/website" target="_blank"><img src="https://opencollective.com/xmake/sponsor/7/avatar.svg"></a>
<a href="https://opencollective.com/xmake/sponsor/8/website" target="_blank"><img src="https://opencollective.com/xmake/sponsor/8/avatar.svg"></a>
<a href="https://opencollective.com/xmake/sponsor/9/website" target="_blank"><img src="https://opencollective.com/xmake/sponsor/9/avatar.svg"></a>

# 贡献代码

如果你发现一些问题，或者想新增或者改进某些新特性，或者想贡献一个新的模块
那么你可以在[issues][1]上提交反馈，或者发起一个提交代码的请求(pull request).

## 问题反馈

* 确认这个问题没有被反馈过
* 确认这个问题最近还没有被修复，请先检查下 `master` 的最新提交
* 请清晰详细地描述你的问题
* 如果发现某些代码存在问题，请在issue上引用相关代码

## 安装环境

#### 安装cnpm

```console
$ npm install -g cnpm --registry=https://registry.npm.taobao.org
```

#### 创建空工程

```console
$ cnpm install -g yo generator-code
$ yo code
```

#### 创建发布者

```console
$ cnpm install -g vsce
$ vsce create-publisher (publisher name)
$ vsce login (publisher name)
```

#### 构建发布

```console
$ vsce package
$ vsce publish [version]
```

## 提交代码

* 请先更新你的本地分支到最新，再进行提交代码请求，确保没有合并冲突
* 编写友好可读的提交信息
* 请使用余工程代码相同的代码规范
* 确保提交的代码缩进是四个空格，而不是tab
* 请提交代码到`dev`分支，如果通过，我们会在特定时间合并到`master`分支上
* 为了规范化提交日志的格式，commit消息，不要用中文，请用英文描述

[1]: https://github.com/xmake-io/xmake-vscode/issues

## 支持项目

xmake项目属于个人开源项目，它的发展需要您的帮助，如果您愿意支持xmake项目的开发，欢迎为其捐赠，支持它的发展。 🙏 [[支持此项目](https://opencollective.com/xmake#backer)]

<a href="https://opencollective.com/xmake#backers" target="_blank"><img src="https://opencollective.com/xmake/backers.svg?width=890"></a>

## 赞助项目

通过赞助支持此项目，您的logo和网站链接将显示在这里。[[赞助此项目](https://opencollective.com/xmake#sponsor)]

<a href="https://opencollective.com/xmake/sponsor/0/website" target="_blank"><img src="https://opencollective.com/xmake/sponsor/0/avatar.svg"></a>
<a href="https://opencollective.com/xmake/sponsor/1/website" target="_blank"><img src="https://opencollective.com/xmake/sponsor/1/avatar.svg"></a>
<a href="https://opencollective.com/xmake/sponsor/2/website" target="_blank"><img src="https://opencollective.com/xmake/sponsor/2/avatar.svg"></a>
<a href="https://opencollective.com/xmake/sponsor/3/website" target="_blank"><img src="https://opencollective.com/xmake/sponsor/3/avatar.svg"></a>
<a href="https://opencollective.com/xmake/sponsor/4/website" target="_blank"><img src="https://opencollective.com/xmake/sponsor/4/avatar.svg"></a>
<a href="https://opencollective.com/xmake/sponsor/5/website" target="_blank"><img src="https://opencollective.com/xmake/sponsor/5/avatar.svg"></a>
<a href="https://opencollective.com/xmake/sponsor/6/website" target="_blank"><img src="https://opencollective.com/xmake/sponsor/6/avatar.svg"></a>
<a href="https://opencollective.com/xmake/sponsor/7/website" target="_blank"><img src="https://opencollective.com/xmake/sponsor/7/avatar.svg"></a>
<a href="https://opencollective.com/xmake/sponsor/8/website" target="_blank"><img src="https://opencollective.com/xmake/sponsor/8/avatar.svg"></a>
<a href="https://opencollective.com/xmake/sponsor/9/website" target="_blank"><img src="https://opencollective.com/xmake/sponsor/9/avatar.svg"></a>



