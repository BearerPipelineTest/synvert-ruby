# CHANGELOG

## 0.20.0 (2022-08-20)

* Rename `load_rewriters` to `read_rewriters`
* Run a snippet from remote url or local file path

## 0.19.3 (2022-07-18)

* Require json
* update `synvert-core` to 1.5.0

## 0.19.2 (2021-12-15)

* List sub_snippets group and name

## 0.19.1 (2021-10-23)

* Make URI.open work in ruby 2.4

## 0.19.0 (2021-09-10)

* Add `--show-run-process` option
* Deprecate `synvert`, use `synvert-ruby` instead
* Update `synvert-snippets` url
* Fix `affected_files` is Set

## 0.18.0 (2021-07-14)

* Execute a snippet

## 0.17.0 (2021-04-19)

* Run `git checkout .` before `git pull --rebase`

## 0.16.0 (2021-03-24)

* Add `ruby_version` and `gem_spec` to json output

## 0.15.0 (2021-03-23)

* Fix reduce on empty array
* Update synvert-core when syncing snippets

## 0.14.0 (2021-03-13)

* Add CLI option `--format`
* Run one snippet once

## 0.13.0 (2021-03-02)

* Use `ENV['SYNVERT_SNIPPETS_HOME']` to change default snippets home
* Display snippet source code for showing a snippet

## 0.12.0 (2021-03-01)

* Display `synvert-core` and `parser` version
* Generate a new snippet

## 0.11.1 (2021-02-20)

* Use `Synvert::VERSION` instead of `Synvert::Core::VERSION`

## 0.11.0 (2021-02-15)

* Add `--list-all` option
* Add post install message
* Fix `Synvert::Snippet.fetch_core_version`

## 0.10.0 (2021-02-07)

* Use new `Core::Confiruation`
* Use require instead of eval in order to preserve normal Ruby semantics

## 0.9.0

* Add `-o` or `--open` option` to open a snippet

## 0.5.3

* Show warning message if rewriter not found

## 0.5.0

* Rewrite cli for rewriter group

## 0.4.2

* Tell user to update synvert-core if necessary after syncing snippets.

## 0.4.0

* Use synvert-core 0.4.0

## 0.2.0

* Output rewriter warnings
* Ask to run `synvert --sync` if no snippet available

## 0.1.0

* Abstract synvert-core and synvert-snippets

## 0.0.17

* Polish convert_rails_dynamic_finders snippet.
* Add --skip option to cli to skip files and directories.

## 0.0.16

* Add -v, --version cli option.
* Ouput file and line number if there's syntax error.
* Add check_syntax snippet.

## 0.0.15

* Support attr_protected for strong_parameters snippet.

## 0.0.14

* Complement code comments.
* Add MethodNotSupported and RewriterNotFound exceptions.
* Add description dsl to define multi lines description.
* Improve cli, query snippets and show snippet.
* Process rewriter in sandbox mode.

## 0.0.13

* Add keys and values rules for hash node
* Add key and value rules for pair node
* Add ruby new hash syntax snippet
* Add ruby new lambda syntax snippet

## 0.0.12

* Allow define multiple scopes and conditions in one instance
* Polish snippets

## 0.0.11

* Rename gem_spec to if_gem dsl

## 0.0.10

* Add not ast node operator
* Replace with multipe line code
* Add RSpec new syntax snippet

## 0.0.9

* Add add_file dsl
* Upgrade rails 3.0 to 3.1 snippet

## 0.0.8

* Supports travis-ci and coveralls
* Upgrade rails 3.1 to 3.2 snippet

## 0.0.7

* Able to run run specified snippets
* Able to load additional snippets
* Able to list available snippets
* Add helper_method dsl
* Add todo dsl
* Improve rails 3.2 upgrade to 4.0 snippet

## 0.0.6

* Add -> {} only when not exist in rails upgrade snippet
* Add travis support

## 0.0.5

* Add add_snippet dsl for reuse
* Abstract strong_parameters and convert_dynamic_finders snippet

## 0.0.4

* Test snippets
* Lazily execute blocks that allows executing any ruby code
* Be able to save parsed data and use them later

## 0.0.3

* Add snippet to upgrade rails 3.2 to rails 4.0

## 0.0.2

* Rewrite all stuff, dsl style rather than inherit Parser::Rewriter

## 0.0.1

* First version
