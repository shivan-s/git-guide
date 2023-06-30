<div align='center'>
  <h1>
    <p>Git Guide</p>
  </h1>
</div>

## Introduction

The best way to get better at programming is by sharing personal projects. GitHub is an excellent way to share source code and `git` is an excellent tool to make sharing code easier.

What is `git`?

This is a tool that allows you to track changes in your code.

What is `GitHub`?

This is a place for code to live in order to be shared and worked on collaboratively.

## Initialisation

Use the command to initial a git repository.

```bash

git init

```

There will be instructions provided by `git` and on `GitHub` on how to add your code to a repository on GitHub.

**Tip:** I like to create the repository on GitHub first and then clone this. It saves having to set up and connect the repository.

You can add changes to you code like do:

```bash

git add .

git commit -m '<your message>'

git commit --amend # can be used to amend a commit message

```

Refer to [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) on better commit messages.
