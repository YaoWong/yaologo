# yao

## English

`yao` is my personal project incubator repository.
It is meant to hold ideas, experiments, prototypes, and more formal projects at different stages.

> If this repository has already become a concrete project and this README is still the current one, rewrite the entire README to fit that project instead of keeping this incubator-level version.

### Repository Purpose

This is not a single-project repository.
It is a long-term starting point for personal projects, where multiple project directions can be incubated and developed within the same repository through branch isolation.

### Branch Naming Rule

Each project can have multiple branches, but every branch name must follow this format:

```text
project_branch
```

For example:

```text
yaotools_init
yaotools_featureA
yaoweb_redesign
```

### Naming Constraints

- The `project` part is recommended to start with `yao`
- The `project` part should not contain any separator
- Use `_` as the only separator between `project` and `branch`

Recommended examples:

```text
yaodemo_main
yaonote_mvp
yaoagent_experiment
```

Not recommended:

```text
yao-demo_main
yao_demo_main
demo_feature
```

### Usage

When I start a new project, I first decide on a project name and then create branches following the naming rule.
If the same project needs development, experiments, refactoring, or staged iterations, it should continue using the same project prefix.

### Goal

With a unified branch naming rule and project convention, this repository should remain:

- easy to expand
- easy to identify by project ownership
- easy to maintain over time

This is the basic convention for `yao` as the birthplace of my personal projects.

---

## 中文

`yao` 是我的个人项目孵化仓库，用来集中承载不同阶段的想法、实验、原型和正式项目。

> 如果这个仓库已经进入某个具体项目阶段，而当前仍然是这份 README，那么应该整体重写整份 README，使其适配该项目，而不是继续保留这个孵化仓库版本。

### 仓库定位

这个仓库不是单一项目仓库，而是一个长期使用的个人项目起点。
我会在这里为不同项目创建各自分支，在同一个仓库内持续孵化、验证和推进多个方向。

### 分支命名规则

每个项目都可以拥有多个分支，但分支名必须遵循下面的格式：

```text
项目名_分支名
```

例如：

```text
yaotools_init
yaotools_featureA
yaoweb_redesign
```

### 命名约束

- `项目名` 建议统一以 `yao` 开头
- `项目名` 不使用任何分隔符
- 使用下划线 `_` 作为 `项目名` 与 `分支名` 的唯一分隔符

也就是说，推荐写法类似：

```text
yaodemo_main
yaonote_mvp
yaoagent_experiment
```

不推荐：

```text
yao-demo_main
yao_demo_main
demo_feature
```

### 使用方式

当我准备启动一个新项目时，会先确定项目名，再按规则创建对应分支。
同一个项目下如果需要开发、实验、重构或阶段性迭代，也继续沿用同一个项目名前缀。

### 目标

通过统一的分支命名和项目约定，让这个仓库保持：

- 易于扩展
- 易于识别项目归属
- 易于长期维护

这是 `yao` 作为个人项目诞生地的基本约定。
