<!-- DO NOT EDIT THIS FILE! -->
<!-- Instead edit recipe/symfony5.php -->
<!-- Then run bin/docgen -->

# symfony5

[Source](/recipe/symfony5.php)



* Require
  * [`recipe/common.php`](/docs/recipe/common.md)
* Config
  * [`shared_dirs`](#shared_dirs)
  * [`shared_files`](#shared_files)
  * [`writable_dirs`](#writable_dirs)
  * [`migrations_config`](#migrations_config)
  * [`console_options`](#console_options)
* Tasks
  * [`database:migrate`](#databasemigrate) — Migrate database
  * [`deploy:cache:clear`](#deploycacheclear) — Clear cache
  * [`deploy:cache:warmup`](#deploycachewarmup) — Warm up cache
  * [`deploy`](#deploy) — Deploy project

## Config
### shared_dirs
[Source](/recipe/symfony5.php#L6)

* Overrides [`shared_dirs`](/docs/recipe/common.md#shared_dirs) from `recipe/common.php`



### shared_files
[Source](/recipe/symfony5.php#L7)

* Overrides [`shared_files`](/docs/recipe/common.md#shared_files) from `recipe/common.php`



### writable_dirs
[Source](/recipe/symfony5.php#L8)

* Overrides [`writable_dirs`](/docs/recipe/deploy/writable.md#writable_dirs) from `recipe/deploy/writable.php`



### migrations_config
[Source](/recipe/symfony5.php#L9)



### console_options
[Source](/recipe/symfony5.php#L15)




## Tasks
### database:migrate
[Source](/recipe/symfony5.php#L20)



### deploy:cache:clear
[Source](/recipe/symfony5.php#L30)



### deploy:cache:warmup
[Source](/recipe/symfony5.php#L35)



### deploy
[Source](/recipe/symfony5.php#L40)



This task is group task which contains next tasks:
* [`deploy:prepare`](/docs/recipe/common.md#deployprepare)
* [`deploy:vendors`](/docs/recipe/deploy/vendors.md#deployvendors)
* [`deploy:cache:clear`](/docs/recipe/symfony5.md#deploycacheclear)
* [`deploy:cache:warmup`](/docs/recipe/symfony5.md#deploycachewarmup)
* [`deploy:publish`](/docs/recipe/common.md#deploypublish)


