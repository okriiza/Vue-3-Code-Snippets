# Vue 3 Code Snippets for Visual Studio Code

![GitHub](https://img.shields.io/github/license/okriiza/Vue-3-Code-Snippets)
![Vue Version](https://img.shields.io/badge/vue-3-%234FC08D?logo=vuedotjs)

## Description

A VSCode extension to provide snippets for Vue 3, Nuxt 3 and Pinia.

> I took my inspiration from [vue-vscode-snippets](https://github.com/sdras/vue-vscode-snippets) extension made by @sdras.
>
> I took my inspiration from [vue3-vscode-snippets](https://github.com/ExEr7um/vue3-vscode-snippets) extension made by @ExEr7um.

## Features

- Vue 3 snippets
- Nuxt 3 snippets
- Pinia snippets
- Composition API snippets
- Support for JavaScript and TypeScript

## Usage

Type part of a snippet, press `enter`, and the snippet unfolds.

## Snippets

### Support File `.vue`

| Prefix           | Purpose                                                               |
| ---------------- | --------------------------------------------------------------------- |
| `vstart`         | start for Vue 3 File with `<script setup>` No style                   |
| `vstart-scss`    | start for Vue 3 File with `<script setup>` Style `SCSS`               |
| `vstart-sass`    | start for Vue 3 File with `<script setup>` Style `SASS`               |
| `vstart-less`    | start for Vue 3 File with `<script setup>` Style `LESS`               |
| `vstart-pcss`    | start for Vue 3 File with `<script setup>` Style `PostCSS`            |
| `vstart-css`     | start for Vue 3 File with `<script setup>` Style `CSS`                |
| `vstart-ts`      | start for Vue 3 File with `<script setup lang='ts'>`, No Style        |
| `vstart-ts-scss` | start for Vue 3 File with `<script setup lang='ts'>`, Style `SCSS`    |
| `vstart-ts-sass` | start for Vue 3 File with `<script setup lang='ts'>`, Style `SASS`    |
| `vstart-ts-less` | start for Vue 3 File with `<script setup lang='ts'>`, Style `LESS`    |
| `vstart-ts-pcss` | start for Vue 3 File with `<script setup lang='ts'>`, Style `PostCSS` |
| `vstart-ts-css`  | start for Vue 3 File with `<script setup lang='ts'>`, Style `CSS`     |

| Prefix        | Purpose                       |
| ------------- | ----------------------------- |
| `vscript`     | `<script setup>`              |
| `vscript-ts`  | `<script setup lang='ts'>`    |
| `vtemplate`   | `<template></template>`       |
| `vfor`        | `v-for` statement             |
| `vslot-named` | `<template #name></template>` |

- Nuxt

| Prefix        | Purpose                     |
| ------------- | --------------------------- |
| `nlink`       | Nuxt router link            |
| `nlink-param` | Nuxt router link with param |

### Support File `.js, .ts`

- Vue Router

| Prefix               | Purpose                                         |
| -------------------- | ----------------------------------------------- |
| `vrouter`            | Vue Router start                                |
| `vscrollbehavior`    | Vue Router `scrollBehavior`                     |
| `vbeforeeach`        | Vue Router global guards `beforeEach`           |
| `vbeforeresolve`     | Vue Router global guards `beforeResolve`        |
| `vaftereach`         | Vue Router global guards `afterEach`            |
| `vbeforeenter`       | Vue Router per-route guard `beforeEnter`        |
| `vbeforerouteenter`  | Vue Router component guards `beforeRouteEnter`  |
| `vbeforerouteupdate` | Vue Router component guards `beforeRouteUpdate` |
| `vbeforerouteleave`  | Vue Router component guards `beforeRouteLeave`  |

- Pinia

| Prefix     | Purpose                                                       |
| ---------- | ------------------------------------------------------------- |
| `pstart`   | Start code needed for a Pinia store file                      |
| `pstart-c` | Start code needed for a Pinia store file with Composition API |

### Support File `.vue, .js, .ts`

- Vue

| Prefix             | Purpose                     |
| ------------------ | --------------------------- |
| `vref`             | Vue `ref`                   |
| `vreactive`        | Vue `reactive`              |
| `vcomputed`        | Vue `computed`              |
| `vwatch`           | Watcher                     |
| `vwatcheffect`     | Watch Effect                |
| `vonmounted`       | onMounted hook              |
| `vonbeforemount`   | onBeforeMount hook          |
| `vonbeforeupdate`  | onBeforeUpdate hook         |
| `vonupdated`       | onUpdated hook              |
| `vonerrorcaptured` | onErrorCaptured hook        |
| `vonunmounted`     | onUnmounted hook            |
| `vonbeforeunmount` | onBeforeUnmount hook        |
| `vdefineprops`     | Define props                |
| `vdefineemits`     | Define emits                |
| `vsingleemit`      | Single emit for defineEmits |
| `vdefineslots`     | Define slots                |
| `vsingleslot`      | Single slot for defineSlots |
| `vdefineoptions`   | Define Options              |
| `vdefinemodel`     | Define Model                |

- Nuxt

| Prefix                  | Purpose                                            |
| ----------------------- | -------------------------------------------------- |
| `nfetch`                | `useFetch` composable                              |
| `nfetch-lazy`           | `useLazyFetch` composable                          |
| `ndfetch    `           | `$Fetch`                                           |
| `ndfetch-post`          | `$Fetch` with method POST and Body                 |
| `ndfetch-put`           | `$Fetch` with method PUT and Body                  |
| `ndfetch-delete`        | `$Fetch` with method DELETE and Body               |
| `nasyncdata`            | `useAsyncData` composable                          |
| `nasyncdata-lazy`       | `useLazyAsyncData` composable                      |
| `nhead`                 | `useHead` composable                               |
| `nhead-description`     | `useHead` composable with description              |
| `nhead-template`        | `useHead` composable with title template           |
| `npagemeta`             | `definePageMeta` composable                        |
| `npagemeta-description` | `definePageMeta` composable with description       |
| `npagemeta-layout`      | `definePageMeta` composable with layout            |
| `npagemeta-middleware`  | `definePageMeta` composable with middleware        |
| `npagemeta-ml`          | `definePageMeta` composable with middleware layout |
| `nplugin`               | Start code for Nuxt plugin                         |
| `nmiddleware`           | Start code for Nuxt middleware                     |
| `nserver`               | Start code for Nuxt server                         |

## License

[MIT](https://github.com/okriiza/Vue-3-Code-Snippets/blob/main/LICENSE) © [Rendi Okriza Putra](https://github.com/okriiza)

**Enjoy!**
