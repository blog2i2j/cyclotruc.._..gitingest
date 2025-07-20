# Changelog

## [1.0.0](https://github.com/blog2i2j/cyclotruc.._..gitingest/compare/v0.1.4...v1.0.0) (2025-07-20)


### ⚠ BREAKING CHANGES

* 
* 

### Features

* `include_submodules` option ([#313](https://github.com/blog2i2j/cyclotruc.._..gitingest/issues/313)) ([38c2317](https://github.com/blog2i2j/cyclotruc.._..gitingest/commit/38c23171a14556a2cdd05c0af8219f4dc789defd))
* add /llm.txt ([#307](https://github.com/blog2i2j/cyclotruc.._..gitingest/issues/307)) ([1545dc8](https://github.com/blog2i2j/cyclotruc.._..gitingest/commit/1545dc8f4270f94b56d5ca2735f7b770a9a36d27))
* add private-repo support to CLI & core (UI coming next) ([#282](https://github.com/blog2i2j/cyclotruc.._..gitingest/issues/282)) ([1dd133c](https://github.com/blog2i2j/cyclotruc.._..gitingest/commit/1dd133c3e02b899ff035a9863c6071af61a3479f))
* add Tailwind CSS pipeline, tag-aware cloning & overhaul CI/CD ([#352](https://github.com/blog2i2j/cyclotruc.._..gitingest/issues/352)) ([b683e59](https://github.com/blog2i2j/cyclotruc.._..gitingest/commit/b683e59b5b1a31d27cc5c6ce8fb62da9b660613b))
* add Tailwind CSS pipeline, tag-aware cloning & overhaul CI/CD ([#352](https://github.com/blog2i2j/cyclotruc.._..gitingest/issues/352)) ([016817d](https://github.com/blog2i2j/cyclotruc.._..gitingest/commit/016817d5590c1412498b7532f6e854d20239c6be))
* **ci:** build Docker Image on PRs ([#382](https://github.com/blog2i2j/cyclotruc.._..gitingest/issues/382)) ([bc8cdb4](https://github.com/blog2i2j/cyclotruc.._..gitingest/commit/bc8cdb459482948c27e780b733ac7216d822529a))
* ignore .gitignore files by default (use --include-gitignored to stay  ([ba701a8](https://github.com/blog2i2j/cyclotruc.._..gitingest/commit/ba701a80c9ce1e4623397ec3d03accce726ebdd2))
* implement prometheus exporter ([#406](https://github.com/blog2i2j/cyclotruc.._..gitingest/issues/406)) ([1016f6e](https://github.com/blog2i2j/cyclotruc.._..gitingest/commit/1016f6ecb3b1b066d541d1eba1ddffec49b15f16))
* integrate Sentry for error tracking and performance monitoring ([#408](https://github.com/blog2i2j/cyclotruc.._..gitingest/issues/408)) ([590e55a](https://github.com/blog2i2j/cyclotruc.._..gitingest/commit/590e55a4d28a4f5c0beafbd12c525828fa79e221))
* **parser:** relax host validation to support self-hosted GitLab & git.* domains ([#314](https://github.com/blog2i2j/cyclotruc.._..gitingest/issues/314)) ([e5fadce](https://github.com/blog2i2j/cyclotruc.._..gitingest/commit/e5fadce15864aa47418980d426a8a15a526737e8))
* Refactor backend to a rest api ([#346](https://github.com/blog2i2j/cyclotruc.._..gitingest/issues/346)) ([2b1f228](https://github.com/blog2i2j/cyclotruc.._..gitingest/commit/2b1f228ae1f6d1f7ee471794d258b13fcac25a96))
* switch to o200k_base, require tiktoken ≥ 0.7.0, drop Python 3.7 ([2dea7c8](https://github.com/blog2i2j/cyclotruc.._..gitingest/commit/2dea7c886530ef8a04d24f0901bfb56a7442fb62))
* **ui:** add inline PAT info tooltip inside token field ([#348](https://github.com/blog2i2j/cyclotruc.._..gitingest/issues/348)) ([2592303](https://github.com/blog2i2j/cyclotruc.._..gitingest/commit/25923037ea6cd2f8ef33a6cf1f0406c2b4f0c9b6))
* **ui:** show `<owner>/<repo>` in page title ([#303](https://github.com/blog2i2j/cyclotruc.._..gitingest/issues/303)) ([09ffc44](https://github.com/blog2i2j/cyclotruc.._..gitingest/commit/09ffc446a4e1313d4d39f9772d6d5caf165ee8eb))
* **web-ui:** add private-GitHub ingestion via PAT ([#286](https://github.com/blog2i2j/cyclotruc.._..gitingest/issues/286)) ([3869aa3](https://github.com/blog2i2j/cyclotruc.._..gitingest/commit/3869aa32e30c794b1fb07721d42a541a7c14d394))


### Bug Fixes

* Add proper test isolation for CLI stdout output test ([#298](https://github.com/blog2i2j/cyclotruc.._..gitingest/issues/298)) ([db7ee0c](https://github.com/blog2i2j/cyclotruc.._..gitingest/commit/db7ee0cc070c140de5d5996e9c0676fb47fc639b))
* adding missing suggested changes from [#252](https://github.com/blog2i2j/cyclotruc.._..gitingest/issues/252) ([#256](https://github.com/blog2i2j/cyclotruc.._..gitingest/issues/256)) ([d36b3a0](https://github.com/blog2i2j/cyclotruc.._..gitingest/commit/d36b3a08d317d16e015ec4f1d07736022825d750))
* cleanup webui links ([#300](https://github.com/blog2i2j/cyclotruc.._..gitingest/issues/300)) ([49b941e](https://github.com/blog2i2j/cyclotruc.._..gitingest/commit/49b941e1282a60600f25a7e4d549c0a59e8ad93b))
* enable metrics if env var is defined instead of being "True" ([#407](https://github.com/blog2i2j/cyclotruc.._..gitingest/issues/407)) ([fa2e192](https://github.com/blog2i2j/cyclotruc.._..gitingest/commit/fa2e192c05864c8db90bda877e9efb9b03caf098))
* frontend directory tree ([#363](https://github.com/blog2i2j/cyclotruc.._..gitingest/issues/363)) ([0fcf8a9](https://github.com/blog2i2j/cyclotruc.._..gitingest/commit/0fcf8a956f7ec8403a025177f998f92ddee96de0))
* **git_form:** prevent PAT “Get your token” link from overlapping sample-repo buttons ([#305](https://github.com/blog2i2j/cyclotruc.._..gitingest/issues/305)) ([65a0bbd](https://github.com/blog2i2j/cyclotruc.._..gitingest/commit/65a0bbdfe578a280fad78b35e5d26447bfcda05a))
* gitignore and gitingestignore files are now correctly processed … ([#416](https://github.com/blog2i2j/cyclotruc.._..gitingest/issues/416)) ([74e503f](https://github.com/blog2i2j/cyclotruc.._..gitingest/commit/74e503fa1140feb74aa5350a32f0025c43097da1))
* Potential fix for code scanning alert no. 75: Uncontrolled data used in path expression ([#421](https://github.com/blog2i2j/cyclotruc.._..gitingest/issues/421)) ([9ceaf6c](https://github.com/blog2i2j/cyclotruc.._..gitingest/commit/9ceaf6cbbb0cdefbc79f78c5285406b9188b2d3d))
* Skip files where decoding raises an exception ([#250](https://github.com/blog2i2j/cyclotruc.._..gitingest/issues/250)) ([688c1d0](https://github.com/blog2i2j/cyclotruc.._..gitingest/commit/688c1d0b1d418dfae29c1b0c520cdc9003eaf7b1))
* temp files cleanup after ingest([#309](https://github.com/blog2i2j/cyclotruc.._..gitingest/issues/309)) ([e669e44](https://github.com/blog2i2j/cyclotruc.._..gitingest/commit/e669e444fa1e6130f3f22952dd81f0ca3fe08fa5))
* traverse directories to allow pattern matching of files within them ([#259](https://github.com/blog2i2j/cyclotruc.._..gitingest/issues/259)) ([789be9b](https://github.com/blog2i2j/cyclotruc.._..gitingest/commit/789be9b339f80e215505bf07b48383cccc6041c5))
* **ui:** update directory-picker logic to compute full file paths ([#295](https://github.com/blog2i2j/cyclotruc.._..gitingest/issues/295)) ([3c53843](https://github.com/blog2i2j/cyclotruc.._..gitingest/commit/3c5384322c6ba79e3e1ff4f2cab27c931c2b5ed4))
* **ui:** update layout in PAT section to avoid overlaps & overflows ([#331](https://github.com/blog2i2j/cyclotruc.._..gitingest/issues/331)) ([b39ef54](https://github.com/blog2i2j/cyclotruc.._..gitingest/commit/b39ef5416c1f8a7993a8249161d2a898b7387595))
* **ui:** use proper decimal prefixes (kB / MB) in file-size selector ([#294](https://github.com/blog2i2j/cyclotruc.._..gitingest/issues/294)) ([327958e](https://github.com/blog2i2j/cyclotruc.._..gitingest/commit/327958eae8377bdc7b97a49624dd27b3e2abf7c1))
* **windows:** warn if Git long path support is disabled, do not fail ([b8e375f](https://github.com/blog2i2j/cyclotruc.._..gitingest/commit/b8e375f71cae7d980cf431396c4414a6dbd0588c))


### Documentation

* add GitHub Issue Form for bug reports ([#403](https://github.com/blog2i2j/cyclotruc.._..gitingest/issues/403)) ([4546449](https://github.com/blog2i2j/cyclotruc.._..gitingest/commit/4546449bbc1e4a7ad0950c4b831b8855a98628fd))
* add GitHub Issue Form for feature requests ([#404](https://github.com/blog2i2j/cyclotruc.._..gitingest/issues/404)) ([9b1fc58](https://github.com/blog2i2j/cyclotruc.._..gitingest/commit/9b1fc58900ae18a3416fe3cf9b5e301a65a8e9fd))
* add links to other language versions of README ([#311](https://github.com/blog2i2j/cyclotruc.._..gitingest/issues/311)) ([c19f275](https://github.com/blog2i2j/cyclotruc.._..gitingest/commit/c19f275010dce40289787833b9882568d23e7d8b))
* Fix CLI help text accuracy ([#332](https://github.com/blog2i2j/cyclotruc.._..gitingest/issues/332)) ([fdcbc53](https://github.com/blog2i2j/cyclotruc.._..gitingest/commit/fdcbc53cadde6a5dc3c3626120df1935b63693b2))


### Code Refactoring

* centralize PAT validation, streamline repo checks & misc cleanup ([#349](https://github.com/blog2i2j/cyclotruc.._..gitingest/issues/349)) ([cea0edd](https://github.com/blog2i2j/cyclotruc.._..gitingest/commit/cea0eddce8c6846bc6271cb3a8d15320e103214c))
* centralize PAT validation, streamline repo checks & misc cleanup ([#349](https://github.com/blog2i2j/cyclotruc.._..gitingest/issues/349)) ([f8d397e](https://github.com/blog2i2j/cyclotruc.._..gitingest/commit/f8d397e66e3382d12f8a0ed05d291a39db830bda))
