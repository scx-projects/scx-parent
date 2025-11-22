<p align="center">
    <img src="https://scx.dev/scx-logo/scx-parent-logo.svg" width="300px" alt="scx-parent-logo"/>
</p>
<p align="center">
    <a target="_blank" href="https://github.com/scx-projects/scx-parent/actions/workflows/ci.yml">
        <img src="https://github.com/scx-projects/scx-parent/actions/workflows/ci.yml/badge.svg" alt="CI"/>
    </a>
    <a target="_blank" href="https://central.sonatype.com/artifact/dev.scx/scx-parent">
        <img src="https://img.shields.io/maven-central/v/dev.scx/scx-parent?color=ff69b4" alt="maven-central"/>
    </a>
    <a target="_blank" href="https://github.com/scx-projects/scx-parent">
        <img src="https://img.shields.io/github/languages/code-size/scx-projects/scx-parent?color=orange" alt="code-size"/>
    </a>
    <a target="_blank" href="https://github.com/scx-projects/scx-parent/issues">
        <img src="https://img.shields.io/github/issues/scx-projects/scx-parent" alt="issues"/>
    </a>
    <a target="_blank" href="https://github.com/scx-projects/scx-parent/blob/master/LICENSE">
        <img src="https://img.shields.io/github/license/scx-projects/scx-parent" alt="license"/>
    </a>
</p>

## Maven

``` xml
<parent>
    <groupId>dev.scx</groupId>
    <artifactId>scx-parent</artifactId>
    <version>{version}</version>
    <relativePath/>
</parent>
```

## 快速开始

#### 1. 复制 [scx-build.ps1](./scx-build.ps1) 到您的项目根目录 .

```text
your-project
    ├── src
    ├── pom.xml
    └── scx-build.ps1
```

#### 2. 编辑您的 pom.xml .

```xml
<properties>
    <scx.mainClass>{your.main.class}</scx.mainClass>
</properties>
```

#### 3. 使用 PowerShell 运行 [scx-build.ps1](./scx-build.ps1) .

```
1. 运行项目
2. 构建项目 (不包括依赖项)
3. 构建项目 (包括依赖项)
4. 仅复制依赖项
0. 退出
```
