# Changelog

## master (unreleased)

### New features

* Improve `helm-source-proctile-project-list` by also inheriting the `helm-type-file` class to benefit of it's functionality
  such as candidate transformer or file cache.

### Changes

### Bugs fixed

* [#176](https://github.com/bbatsov/helm-projectile/pull/178): Correctly remove current buffer from `helm-source-projectile-buffers-list`.
* [#151](https://github.com/bbatsov/helm-projectile/pull/157): Teach `helm-projectile-rg` to respect ignored files and directories.
* [#151](https://github.com/bbatsov/helm-projectile/issues/151): Rename `helm-projectile-switch-to-eshell` -> `helm-projectile-switch-to-shell`.
* [#143](https://github.com/bbatsov/helm-projectile/issues/143): Fix rg command for helm-ag arity.
* [#145](https://github.com/bbatsov/helm-projectile/issues/145): Fix bug in `M-D` / remove from project list action for first project in the list.
* [#143](https://github.com/bbatsov/helm-projectile/issues/143): Fix `rg` command for `helm-ag` arity.
* [#140](https://github.com/bbatsov/helm-projectile/pull/140): Fix interactive options for `helm-projectile-grep` and `helm-projectile-ack`.

## 1.0.0 (2020-05-18)

Initial stable release.
