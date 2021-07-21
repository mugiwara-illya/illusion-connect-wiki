# Illusion Connect Wiki

Repository for [illusionconnect.wiki](https://illusionconnect.wiki) static content. The website layout is updated automatically with any changes committed to the [master](https://github.com/illusion-connect-wiki/illusion-connect-wiki) branch of this repository.

[![Build Status](https://app.travis-ci.com/illusion-connect-wiki/illusion-connect-wiki.svg?branch=master)](https://app.travis-ci.com/illusion-connect-wiki/illusion-connect-wiki)

## Structure

Public pages [illusionconnect.wiki](https://illusionconnect.wiki)`/{page}/{id}` are generated dynamically from by the matching file `{page}/{id}/index.json`.

Page indexes are generated dynamically from the folder structure `{section}/{id}/**`, such as the [characters](https://illusionconnect.wiki/characters) page.

## Publishing changes

The default way.

### Requiremtents

- [GitHub](https://github.com/) account
- Git [client](https://git-scm.com/downloads/guis)

### Getting started

[Fork](https://docs.github.com/en/get-started/quickstart/fork-a-repo#forking-a-repository) the repository [master](https://github.com/illusion-connect-wiki/illusion-connect-wiki) and clone it:

```
git clone https://github.com/my-github-username/illusion-connect-wiki.git
```

Create a local branch:

```
git checkout -b feature/my-changes
```

The remote branch is automatically created when you push it to the remote server:

```
git push origin feature/my-changes
```

Make your code changes then push them on your fork:

```
git add -u
git add <new files if applicable>
git status
git commit -m "Some meaningful message"
git push origin feature/my-changes
```

Submit a pull request from your fork branch by following these [instructions](https://docs.github.com/en/github/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request-from-a-fork).

The data files will be validated for each change. Refer to the [documentation](https://github.com/illusion-connect-wiki/illusion-connect-wiki/wiki) for data schema specifications.