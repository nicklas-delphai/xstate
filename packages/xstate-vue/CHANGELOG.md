# @xstate/vue

## 1.0.0-next.0

### Patch Changes

- Updated dependencies [[`8c78e120`](https://github.com/davidkpiano/xstate/commit/8c78e1205a729d933e30db01cd4260d82352a9be), [`7f3b8481`](https://github.com/davidkpiano/xstate/commit/7f3b84816564d951b6b29afdd7075256f1f59501), [`602687c2`](https://github.com/davidkpiano/xstate/commit/602687c235c56cca552c2d5a9d78adf224f522d8), [`172d6a7e`](https://github.com/davidkpiano/xstate/commit/172d6a7e1e4ab0fa73485f76c52675be8a1f3362), [`e09efc72`](https://github.com/davidkpiano/xstate/commit/e09efc720f05246b692d0fdf17cf5d8ac0344ee6), [`145539c4`](https://github.com/davidkpiano/xstate/commit/145539c4cfe1bde5aac247792622428e44342dd6), [`3de36bb2`](https://github.com/davidkpiano/xstate/commit/3de36bb24e8f59f54d571bf587407b1b6a9856e0), [`9e10660e`](https://github.com/davidkpiano/xstate/commit/9e10660ec2f1e89cbb09a1094edb4f6b8a273a99), [`6e44d02a`](https://github.com/davidkpiano/xstate/commit/6e44d02ad03af4041046120dd6c975e3b5b3772a), [`97b05690`](https://github.com/davidkpiano/xstate/commit/97b05690cd8b30824eb176c813a145d3ef0d2a78), [`6043a1c2`](https://github.com/davidkpiano/xstate/commit/6043a1c28d21ff8cbabc420a6817a02a1a54fcc8), [`0e24ea6d`](https://github.com/davidkpiano/xstate/commit/0e24ea6d62a5c1a8b7e365f2252dc930d94997c4), [`04e89f90`](https://github.com/davidkpiano/xstate/commit/04e89f90f97fe25a45b5908c45f25a513f0fd70f), [`72b0880e`](https://github.com/davidkpiano/xstate/commit/72b0880e6444ae009adca72088872bb5c0760ce3), [`b24e47b9`](https://github.com/davidkpiano/xstate/commit/b24e47b9e7a59a5b0527d4386cea3af16c84ca7a), [`390eaaa5`](https://github.com/davidkpiano/xstate/commit/390eaaa523cb0dd243e39c6300e671606c1e45fc), [`0c6cfee9`](https://github.com/davidkpiano/xstate/commit/0c6cfee9a6d603aa1756e3a6d0f76d4da1486caf), [`e09efc72`](https://github.com/davidkpiano/xstate/commit/e09efc720f05246b692d0fdf17cf5d8ac0344ee6), [`025a2d6a`](https://github.com/davidkpiano/xstate/commit/025a2d6a295359a746bee6ffc2953ccc51a6aaad), [`e09efc72`](https://github.com/davidkpiano/xstate/commit/e09efc720f05246b692d0fdf17cf5d8ac0344ee6), [`53a594e9`](https://github.com/davidkpiano/xstate/commit/53a594e9a1b49ccb1121048a5784676f83950024), [`31a0d890`](https://github.com/davidkpiano/xstate/commit/31a0d890f55d8f0b06772c9fd510b18302b76ebb)]:
  - xstate@5.0.0-next.0

## 0.3.0

### Minor Changes

- [`8662e543`](https://github.com/davidkpiano/xstate/commit/8662e543393de7e2f8a6d92ff847043781d10f4d) [#1317](https://github.com/davidkpiano/xstate/pull/1317) Thanks [@Andarist](https://github.com/Andarist)! - `useMachine` and `useService` cant be now parametrized with a `TTypestate` parameter which makes leveraging typestates possible on their returned values.

## 0.2.0

### Minor Changes

- [`65c13245`](https://github.com/davidkpiano/xstate/commit/65c132458cdc73b242f9c0b22e61ba9ba7780509) [#1253](https://github.com/davidkpiano/xstate/pull/1253) Thanks [@darrenjennings](https://github.com/darrenjennings)! - Upgraded package for compatibility with the newest `@vue/composition-api@^0.6.0`, which means that a peer dependency requirement has changed to this version, which is a **breaking change**. The only observable behavior change is that exposed refs are now **shallow**.

## 0.1.1

### Patch Changes

- [`c057f38`](https://github.com/davidkpiano/xstate/commit/c057f38aa20d06501fd7e5893eef0d6688e547eb) [#976](https://github.com/davidkpiano/xstate/pull/976) Thanks [@Andarist](https://github.com/Andarist)! - Fixed issue with `useMachine` crashing without providing optional `options` parameter.

- Updated dependencies [[`520580b`](https://github.com/davidkpiano/xstate/commit/520580b4af597f7c83c329757ae972278c2d4494)]:
  - xstate@4.7.8
