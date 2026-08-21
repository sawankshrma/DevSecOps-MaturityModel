# [4.7.0](https://github.com/devsecopsmaturitymodel/DevSecOps-MaturityModel/compare/v4.6.0...v4.7.0) (2026-08-21)


### Bug Fixes

* add esnext.disposable lib to fix Vitest spy type error ([790c616](https://github.com/devsecopsmaturitymodel/DevSecOps-MaturityModel/commit/790c61612ac3431a5453588f255ac57f29e2c022))
* **ci:** update Node.js from 16 to 18 in test workflow ([f96e1e0](https://github.com/devsecopsmaturitymodel/DevSecOps-MaturityModel/commit/f96e1e0d0f1ada81d5bbda82195fb387ff51a138))
* **ci:** update Node.js from 18 to 20 in test workflow ([af4a390](https://github.com/devsecopsmaturitymodel/DevSecOps-MaturityModel/commit/af4a390e356a5e3b3ba66d3c636f7f1a8cf7caf4))
* clean up ESLint deps and bump Prettier to safe versions ([ab33874](https://github.com/devsecopsmaturitymodel/DevSecOps-MaturityModel/commit/ab33874de3bdd0ea03005f8869beff9cb6f7b60d))
* complete Angular 22 migration follow-up ([6e39983](https://github.com/devsecopsmaturitymodel/DevSecOps-MaturityModel/commit/6e3998307ddd7798de88c107864a5d720cf414af))
* **deps:** explicitly add @typescript-eslint/utils for CI linting ([552b62f](https://github.com/devsecopsmaturitymodel/DevSecOps-MaturityModel/commit/552b62fa020c85bd3117bc2e49fc35d16dd7a46c))
* **heatmap:** add explicit [value] binding to team group chips ([c84d4bc](https://github.com/devsecopsmaturitymodel/DevSecOps-MaturityModel/commit/c84d4bc4bcdb5f38ee9eeb0888cc6ba0e0290287))
* **heatmap:** resolve MDC chip selection and styling issues ([8405569](https://github.com/devsecopsmaturitymodel/DevSecOps-MaturityModel/commit/840556982f67f53efe9fb1b09f81703a7b3daad3))
* MatChip declaration in specs ([584a334](https://github.com/devsecopsmaturitymodel/DevSecOps-MaturityModel/commit/584a334bacd863c1b80d27f129cdeec4a1c3cd9f))
* **matrix:** resolve MDC chip selection and styling issues ([e7ba491](https://github.com/devsecopsmaturitymodel/DevSecOps-MaturityModel/commit/e7ba491944994509edc8246896e555431d7fd337))
* **matrix:** update spec to use MatChipSelectionChange API after MDC migration ([3ca5e9e](https://github.com/devsecopsmaturitymodel/DevSecOps-MaturityModel/commit/3ca5e9e421370b1b900d45b461b056b5610d06df))
* **overall app:** resolve button, inputs and mat-panel broken css issue ([a183555](https://github.com/devsecopsmaturitymodel/DevSecOps-MaturityModel/commit/a1835556c5b0434ba29fa35ccf57f135241042df))
* remove unnecessary optional chaining operators (NG8107 warnings) ([2bad7c3](https://github.com/devsecopsmaturitymodel/DevSecOps-MaturityModel/commit/2bad7c36fac17ae0f32fe5654e6a4cab0e685638))
* replace deprecated --prod flag in heroku-postbuild script ([fe8893b](https://github.com/devsecopsmaturitymodel/DevSecOps-MaturityModel/commit/fe8893bead40b81b94d4b503c494f814083cf020))
* replace deprecated RouterTestingModule in specs ([e62fa22](https://github.com/devsecopsmaturitymodel/DevSecOps-MaturityModel/commit/e62fa22b395bde2afd26dd934f852472c14c35c8))
* replace v17 TODO placeholders with all-component-themes mixin ([42829a6](https://github.com/devsecopsmaturitymodel/DevSecOps-MaturityModel/commit/42829a690add5f9533642e6ac0a73ad1e3cd6be4))
* resolve ActivityDescription spec timeout in CI ([18d22df](https://github.com/devsecopsmaturitymodel/DevSecOps-MaturityModel/commit/18d22df136c1c226a54c7b0b481ba7cb84a28e37))
* resolve button and info icon CSS regressions from Angular Material MDC and Material 17 upgrade ([2189473](https://github.com/devsecopsmaturitymodel/DevSecOps-MaturityModel/commit/2189473043ff1ca99d673a58c89c9f973318b073))
* resolve NG0100 test failures from Angular 21 TestBed error rethrow ([5acaee5](https://github.com/devsecopsmaturitymodel/DevSecOps-MaturityModel/commit/5acaee5f52d521a66218cc4084449e01007af3fb))
* **sidenav:** apply primary color to all nav icons ([afb3d58](https://github.com/devsecopsmaturitymodel/DevSecOps-MaturityModel/commit/afb3d58feb32f56d2ed78a0b46639842693591e4))
* **sidenav:** migrate mat-line and mat-list-icon to MDC directives ([c3ca3cd](https://github.com/devsecopsmaturitymodel/DevSecOps-MaturityModel/commit/c3ca3cd8630facb6beb8cce76ade2ba4fd5372d7))
* **styles:** remove Important and unecessary styling from custom-theme.scss ([2533be2](https://github.com/devsecopsmaturitymodel/DevSecOps-MaturityModel/commit/2533be2b2f49d87e47c94316e033d79b2b860b7b))
* **styles:** replace Important in component stylesheets with specificity selectors ([ce39ba9](https://github.com/devsecopsmaturitymodel/DevSecOps-MaturityModel/commit/ce39ba965ae83d1c2dc870ae9da2037f6bfe4e88))
* **styles:** replace important in slider with MDC token API and remove unnecessary styles (which were not affecting the UI) ([3e093fc](https://github.com/devsecopsmaturitymodel/DevSecOps-MaturityModel/commit/3e093fcf6bd54471ce051f953ada0ec5c9f10410))
* **theme:** correct dialog surface background override ([83e75f6](https://github.com/devsecopsmaturitymodel/DevSecOps-MaturityModel/commit/83e75f6de50cfa476c76db19559ea31bd40c20b3))
* **UI:** mat-accordin trailing line fix ([dae53b6](https://github.com/devsecopsmaturitymodel/DevSecOps-MaturityModel/commit/dae53b67ceb0bda1ff75304c5886b3f81a3aa73b))
* **UI:** mat-button ([7e7a441](https://github.com/devsecopsmaturitymodel/DevSecOps-MaturityModel/commit/7e7a441142bd8c2d1d86c12a16671e549789b3bb))
* **UI:** mat-chips ([ae99467](https://github.com/devsecopsmaturitymodel/DevSecOps-MaturityModel/commit/ae9946746730c60ff97b72646f7feb48641deb62))
* **UI:** mat-expansion-panel ([8ddcc87](https://github.com/devsecopsmaturitymodel/DevSecOps-MaturityModel/commit/8ddcc87888481dcb28c8384f294f126f11c91d30))
* **UI:** mat-slider ([6185748](https://github.com/devsecopsmaturitymodel/DevSecOps-MaturityModel/commit/6185748ff2d2df1af2c01cf3b6d3fc288a8cd1d6))
* **UI:** MatDialog - PopUp Modal ([fdaa7db](https://github.com/devsecopsmaturitymodel/DevSecOps-MaturityModel/commit/fdaa7db8a5d6d0494db7b799da3afdff6bf8b7ee))
* **UI:** Matrix Page Icons ([b7eb30b](https://github.com/devsecopsmaturitymodel/DevSecOps-MaturityModel/commit/b7eb30bee3dce4c5739257b05747d3f23a10270b))
* **UI:** sidenav component ([d9b526e](https://github.com/devsecopsmaturitymodel/DevSecOps-MaturityModel/commit/d9b526e445b700a54934c1de21c236a360665923))
* use listbox (change) event instead of chip (selectionChange) to prevent infinite filter loops ([2ad10b0](https://github.com/devsecopsmaturitymodel/DevSecOps-MaturityModel/commit/2ad10b037a0133f5a8a6594d7ed0762ef5646ef9))


### Features

* add identity mangement ([85bb2e7](https://github.com/devsecopsmaturitymodel/DevSecOps-MaturityModel/commit/85bb2e74c292af4c0601052892a13f8108814422))
* **build:** migrate to esbuild application builder ([88d53ea](https://github.com/devsecopsmaturitymodel/DevSecOps-MaturityModel/commit/88d53ea51fbfdb999c834a3c18244f7f5108b770))
* **heatmap:** word-wrap long segment labels across two arc lines ([144b50f](https://github.com/devsecopsmaturitymodel/DevSecOps-MaturityModel/commit/144b50f749810f9d45009b947e8c7cc7a4b68505))
* upgrade Angular 21 → 22 via ng update ([bd54f9d](https://github.com/devsecopsmaturitymodel/DevSecOps-MaturityModel/commit/bd54f9dc0b5f143145eb2a65a1696e4c64cc5bff))

# [3.10.0](https://github.com/devsecopsmaturitymodel/DevSecOps-MaturityModel/compare/v3.9.0...v3.10.0) (2023-11-10)


### Features

* decouple yaml-data and application ([45611e8](https://github.com/devsecopsmaturitymodel/DevSecOps-MaturityModel/commit/45611e8ee58ec7e9ed8ecf5bb1c54b5bfcb8e885))
* enhance signing description ([231a5e9](https://github.com/devsecopsmaturitymodel/DevSecOps-MaturityModel/commit/231a5e97b66a49b95bbc14147ea43d5ce9646788))

# [3.9.0](https://github.com/devsecopsmaturitymodel/DevSecOps-MaturityModel/compare/v3.8.0...v3.9.0) (2023-11-09)


### Features

* enhance signing description ([4546078](https://github.com/devsecopsmaturitymodel/DevSecOps-MaturityModel/commit/454607882a909ef5d7c3e5f2f14bcc0a6a43076e))

## [3.5.2](https://github.com/devsecopsmaturitymodel/DevSecOps-MaturityModel/compare/v3.5.1...v3.5.2) (2023-11-07)


### Bug Fixes

* YAML Structure description ([33e50f0](https://github.com/devsecopsmaturitymodel/DevSecOps-MaturityModel/commit/33e50f0fb168c5c91b4fedb5a2a7d5e8a4ac0a80))

## [3.5.1](https://github.com/devsecopsmaturitymodel/DevSecOps-MaturityModel/compare/v3.5.0...v3.5.1) (2023-11-07)


### Bug Fixes

* YAML ([889422b](https://github.com/devsecopsmaturitymodel/DevSecOps-MaturityModel/commit/889422b791cf141838e2ec637406a14d8849ff6a))

# [3.5.0](https://github.com/devsecopsmaturitymodel/DevSecOps-MaturityModel/compare/v3.4.0...v3.5.0) (2023-11-07)


### Features

* add WAF ([a98947d](https://github.com/devsecopsmaturitymodel/DevSecOps-MaturityModel/commit/a98947da41691e23af255cad8778208db09ccc53))

# [3.4.0](https://github.com/devsecopsmaturitymodel/DevSecOps-MaturityModel/compare/v3.3.0...v3.4.0) (2023-11-07)


### Features

* Activity Contexualized Encoding ([f81d3cf](https://github.com/devsecopsmaturitymodel/DevSecOps-MaturityModel/commit/f81d3cfedd013b579fac73e1b62bb57dfbc5a7a3))
