# @milkdown/plugin-indent

## 7.2.1

### Patch Changes

- df03a2cb: Bug fix

  Fix commands not working for multiple editors. #977
  Fix inline math conflicts with inline sync plugin. #983

- Updated dependencies [df03a2cb]
  - @milkdown/utils@7.2.1

## 7.2.0

### Minor Changes

- f5e00085: Add inspector and telemetry.

### Patch Changes

- 45cd3c76: Fix circular deps in commands plugin.
- c69f3076: Rename inspection to telemetry
- 10139088: Fix incorrect system plugin store ref.
- 828cceb9: Add support for editor inspector #960
- Updated dependencies [f5e00085]
- Updated dependencies [45cd3c76]
- Updated dependencies [c69f3076]
- Updated dependencies [10139088]
- Updated dependencies [828cceb9]
  - @milkdown/utils@7.2.0

## 7.1.2-next.3

### Patch Changes

- 10139088: Fix incorrect system plugin store ref.
- Updated dependencies [10139088]
  - @milkdown/utils@7.1.2-next.3

## 7.1.2-next.2

### Patch Changes

- c69f3076: Rename inspection to telemetry
- Updated dependencies [c69f3076]
  - @milkdown/utils@7.1.2-next.2

## 7.1.2-next.1

### Patch Changes

- 45cd3c76: Fix circular deps in commands plugin.
- Updated dependencies [45cd3c76]
  - @milkdown/utils@7.1.2-next.1

## 7.1.2-next.0

### Patch Changes

- 828cceb9: Add support for editor inspector #960
- Updated dependencies [828cceb9]
  - @milkdown/core@7.1.2-next.0
  - @milkdown/ctx@7.1.2-next.0
  - @milkdown/prose@7.1.2-next.0
  - @milkdown/utils@7.1.2-next.0

## 7.1.1

### Patch Changes

- f4aaf467: Use slugify to create id for heading nodes
  Fix inline sync plugin causes unneeded changes #924
  Upgrade typescript version to 5 #943
  Add hard break leafText #944
- Updated dependencies [f4aaf467]
  - @milkdown/utils@7.1.1

## 7.1.0

### Minor Changes

- 4a60eae7: Add support for HTML nodes.
  Export css files from prosemirror packages.

### Patch Changes

- Updated dependencies [4a60eae7]
  - @milkdown/utils@7.1.0

## 7.0.1

### Patch Changes

- 52dcbbe8: Bug fix.
- Updated dependencies [52dcbbe8]
  - @milkdown/utils@7.0.1

## 7.0.0

### Major Changes

- 069d719b: Milkdown v7.

  - The editor becomes a first-class headless component.
  - Factory plugins are deprecated and replaced by composable plugins.
  - Runtime plugin toggle.
  - Universal widget plugins.
  - Better Vue and React support.
  - API documentation.

### Patch Changes

- 46010daf: Fix bugs of async composables.
- 2ad4b566: Fix some bugs for rc version.
- ff8a568b: Fix issues in nord-theme and block-plugin.
- 76bed778: Align the API of block plugin with slash and tooltip.
- fc2f4f94: Bug fix version
- cbe8b734: Upgrade prosemirror version and rename collab plugin
- Updated dependencies [46010daf]
- Updated dependencies [2ad4b566]
- Updated dependencies [ff8a568b]
- Updated dependencies [76bed778]
- Updated dependencies [fc2f4f94]
- Updated dependencies [cbe8b734]
- Updated dependencies [069d719b]
  - @milkdown/utils@7.0.0

## 7.0.0-next.6

### Patch Changes

- cbe8b734: Upgrade prosemirror version and rename collab plugin
- Updated dependencies [cbe8b734]
  - @milkdown/utils@7.0.0-next.6

## 7.0.0-next.5

### Patch Changes

- 76bed778: Align the API of block plugin with slash and tooltip.
- Updated dependencies [76bed778]
  - @milkdown/utils@7.0.0-next.5

## 7.0.0-next.4

### Patch Changes

- 46010daf: Fix bugs of async composables.
- Updated dependencies [46010daf]
  - @milkdown/utils@7.0.0-next.4

## 7.0.0-next.3

### Patch Changes

- ff8a568b: Fix issues in nord-theme and block-plugin.
- Updated dependencies [ff8a568b]
  - @milkdown/utils@7.0.0-next.3

## 7.0.0-next.2

### Patch Changes

- fc2f4f94: Bug fix version
- Updated dependencies [fc2f4f94]
  - @milkdown/utils@7.0.0-next.2

## 7.0.0-next.1

### Patch Changes

- 2ad4b566: Fix some bugs for rc version.
- Updated dependencies [2ad4b566]
  - @milkdown/utils@7.0.0-next.1

## 7.0.0-next.0

### Major Changes

- 069d719b: Pre-release for milkdown v7.

### Patch Changes

- Updated dependencies [069d719b]
  - @milkdown/core@7.0.0-next.0
  - @milkdown/ctx@7.0.0-next.0
  - @milkdown/prose@7.0.0-next.0
  - @milkdown/utils@7.0.0-next.0

## 6.5.4

### Patch Changes

- b4003d9: Fix bugs and make some small improvements.
- Updated dependencies [b4003d9]
  - @milkdown/utils@6.5.4

## 6.5.3

### Patch Changes

- d5c337d: Ux improvements and bug fix.
- Updated dependencies [d5c337d]
  - @milkdown/utils@6.5.3

## 6.5.2

### Patch Changes

- 3cb8683: Fix floating widget positions by @iHaPBoy
- Updated dependencies [3cb8683]
  - @milkdown/utils@6.5.2

## 6.5.0

### Minor Changes

- 77ae1d3: Removable plugins, editor status, table inputrule and `injectSlices` factory options.

### Patch Changes

- Updated dependencies [77ae1d3]
  - @milkdown/utils@6.5.0

## 6.4.1

### Patch Changes

- c1fd2fe2: Bug fix for android list and prism SSR.
- Updated dependencies [c1fd2fe2]
  - @milkdown/utils@6.4.1

## 6.4.0

### Minor Changes

- cd6a6139: Inline sync plugin, vscode paste support, and new internal ctx.

### Patch Changes

- Updated dependencies [cd6a6139]
  - @milkdown/utils@6.4.0

## 6.3.2

### Patch Changes

- 161d7104: Fix bug of plugin-menu, react strict mode and muptiple editors.
- Updated dependencies [161d7104]
  - @milkdown/utils@6.3.2

## 6.3.1

### Patch Changes

- 8478db7a: Fix bug for memory leak, hardbreak and em to px.
- Updated dependencies [8478db7a]
  - @milkdown/utils@6.3.1

## 6.3.0

### Minor Changes

- d3b2bd9d: https://github.com/Saul-Mirone/milkdown/milestone/4

### Patch Changes

- Updated dependencies [d3b2bd9d]
  - @milkdown/utils@6.3.0

## 6.2.0

### Minor Changes

- 26afcdaf: New react and vue API, custom heading id, prosemirror upgrade, and async composable API.

### Patch Changes

- Updated dependencies [26afcdaf]
  - @milkdown/utils@6.2.0

## 6.1.5

### Patch Changes

- ccf70357: Fix extended factories cannot inject slices
- Updated dependencies [ccf70357]
  - @milkdown/utils@6.1.5

## 6.1.4

### Patch Changes

- d866dded: Fix bugs for clipboard plugin and i18 support
- Updated dependencies [d866dded]
  - @milkdown/utils@6.1.4

## 6.1.3

### Patch Changes

- b5bb4c3f: Fix bugs: inline nodes cursor, theme & emoji for next/nuxt, hardbreak only paragraph.
- Updated dependencies [b5bb4c3f]
  - @milkdown/utils@6.1.3

## 6.1.2

### Patch Changes

- 2c651a96: Fix bugs for collab editing and theme.
- Updated dependencies [2c651a96]
  - @milkdown/utils@6.1.2

## 6.1.1

### Patch Changes

- 1b52931a: Fix input chip bug
- Updated dependencies [1b52931a]
  - @milkdown/utils@6.1.1

## 6.1.0

### Minor Changes

- 1daf87dd: Improve support for collaborative editing.

### Patch Changes

- Updated dependencies [1daf87dd]
  - @milkdown/utils@6.1.0

## 6.0.2

### Patch Changes

- e956c5e3: Fix bugs for collaboration mode
- Updated dependencies [e956c5e3]
  - @milkdown/utils@6.0.2

## 6.0.1

### Patch Changes

- 08a442de: Fix peer dependency error
- Updated dependencies [08a442de]
  - @milkdown/utils@6.0.1

## 6.0.0

### Major Changes

- 00dcdee9: Release milkdown@6
- 4c2846d5: Release milkdown@v6 next.

### Patch Changes

- e27e7e62: Improve UX and API.
- Updated dependencies [e27e7e62]
- Updated dependencies [00dcdee9]
- Updated dependencies [4c2846d5]
  - @milkdown/utils@6.0.0

## 6.0.0-next.1

### Patch Changes

- e27e7e62: Improve UX and API.
- Updated dependencies [e27e7e62]
  - @milkdown/utils@6.0.0-next.1

## 6.0.0-next.0

### Major Changes

- 4c2846d5: Release milkdown@v6 next.

### Patch Changes

- Updated dependencies [4c2846d5]
  - @milkdown/core@6.0.0-next.0
  - @milkdown/prose@6.0.0-next.0
  - @milkdown/utils@6.0.0-next.0

## 5.5.0

### Minor Changes

- d79264e6: Prism plugin now can be configured. And bug fixes with UX optimization.

### Patch Changes

- Updated dependencies [d79264e6]
  - @milkdown/utils@5.5.0

## 5.4.1

### Patch Changes

- 1a882652: Quick fix for new dep orgnization
- Updated dependencies [1a882652]
  - @milkdown/utils@5.4.1

## 5.4.0

### Minor Changes

- 6eef6cd1: Bug fixes, UX improvements and dependency optimization.

### Patch Changes

- Updated dependencies [6eef6cd1]
  - @milkdown/utils@5.4.0

## 5.3.5

### Patch Changes

- d28d71c1: Bug fixes and ux improvements
- Updated dependencies [d28d71c1]
  - @milkdown/core@5.3.5
  - @milkdown/prose@5.3.5
  - @milkdown/utils@5.3.5

## 5.3.4

### Patch Changes

- 1e8cce33: Image load status improvement and support for heading id
- Updated dependencies [1e8cce33]
  - @milkdown/core@5.3.4
  - @milkdown/prose@5.3.4
  - @milkdown/utils@5.3.4

## 5.3.3

### Patch Changes

- f7609d48: Bug fix and ux improvements
- Updated dependencies [f7609d48]
  - @milkdown/core@5.3.3
  - @milkdown/prose@5.3.3
  - @milkdown/utils@5.3.3

## 5.3.2

### Patch Changes

- d62a6011: Bug fixes and new listener API
- Updated dependencies [d62a6011]
  - @milkdown/core@5.3.2
  - @milkdown/prose@5.3.2
  - @milkdown/utils@5.3.2

## 5.3.1

### Patch Changes

- 0f32decd: Bug fixe and ux improvement
- Updated dependencies [0f32decd]
  - @milkdown/utils@5.3.1

## 5.3.0

### Minor Changes

- ed679a03: Optimize vue and react renderer.

### Patch Changes

- Updated dependencies [ed679a03]
  - @milkdown/utils@5.3.0

## 5.2.1

### Patch Changes

- eb74e3b5: Add es and cjs bundle, fix bugs and improve ux
- Updated dependencies [eb74e3b5]
  - @milkdown/utils@5.2.1

## 5.2.0

### Minor Changes

- 42055660: Add menu plugin and lots of optimize.

### Patch Changes

- Updated dependencies [42055660]
  - @milkdown/utils@5.2.0

## 5.1.2

### Patch Changes

- b25da66e: Fix add mark issue for hr
- Updated dependencies [b25da66e]
  - @milkdown/utils@5.1.2

## 5.1.1

### Patch Changes

- e7c701a1: Fix view configuration.
- Updated dependencies [e7c701a1]
  - @milkdown/utils@5.1.1

## 5.1.0

### Minor Changes

- 9519c4c4: Add composable plugins API.

### Patch Changes

- Updated dependencies [9519c4c4]
  - @milkdown/utils@5.1.0

## 5.0.1

### Patch Changes

- 1538bd4a: Fix bugs
- Updated dependencies [1538bd4a]
  - @milkdown/utils@5.0.1

## 5.0.0

### Major Changes

- 35e76858: Refactor the plugin system

### Patch Changes

- Updated dependencies [35e76858]
  - @milkdown/utils@5.0.0

## 4.14.2

### Patch Changes

- 29861bee: Upgrade remark version
- Updated dependencies [29861bee]
  - @milkdown/utils@4.14.2

## 4.14.1

### Patch Changes

- b2618f24: Rollback heading slug feature.
- Updated dependencies [b2618f24]
  - @milkdown/utils@4.14.1

## 4.14.0

### Minor Changes

- e942946d: Add prose and ctx package, improve UX and fix bugs.

### Patch Changes

- Updated dependencies [e942946d]
  - @milkdown/utils@4.14.0

## 4.13.3

### Patch Changes

- db2e3e59: Add indent plugin and upload plugin
- Updated dependencies [db2e3e59]
  - @milkdown/utils@4.13.3
