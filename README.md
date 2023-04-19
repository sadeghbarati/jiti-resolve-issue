## Refrences

- https://github.com/vitejs/vite/issues/5370
- https://github.com/unjs/unbuild/issues/121
- https://github.com/unjs/unbuild/issues/20
- https://github.com/unjs/unbuild/issues/35
- https://github.com/unjs/unbuild/issues/248

```shell
pnpm run dev
```

## Vite

```
Error: The following dependencies are imported but could not be resolved:
│   file:///D:/Sadegh/Test/unbuild-jiti-monorepo/node_modules/.pnpm/jiti@1.18.2/node_modules/jiti/lib/index.js (imported by D:/Sadegh/Test/unbuild-jiti-mon
│ Are they installed?
│     at file:///D:/Sadegh/Test/unbuild-jiti-monorepo/node_modules/.pnpm/vite@4.2.2/node_modules/vite/dist/node/chunks/dep-d305c21f.js:44678:23
│     at process.processTicksAndRejections (node:internal/process/task_queues:95:5)
│     at async Timeout._onTimeout (file:///D:/Sadegh/Test/unbuild-jiti-monorepo/node_modules/.pnpm/vite@4.2.2/node_modules/vite/dist/node/chunks/dep-d305c2
```

## Rspack

```
The system cannot find the path specified. (os error 3)

// after manually modifying packages/lib/dist/index.mjs
// then undo changes

Failed to resolve (util/fs/path/url/os/module/vm/proccess) in 
D:/Sadegh/Test/unbuild-jiti-monorepo/node_modules/.pnpm/jiti@1.18.2/node_modules/jiti\dist\jiti.js
```


## Parcel

```
Build failed.

unknown: Could not find entry: D:\Sadegh\Test\unbuild-jiti-monorepo\packages\parcel
```


## Turbopack

```
Could not resolve React Refresh runtime
  React Refresh will be disabled.
  To enable React Refresh, install the `react-refresh` and `@next/react-refresh-utils` modules.

  [500] error (34s): timeout while receiving message from process

Caused by:
- deadline has elapsed

Debug info:
- Execution of get_from_source failed
- Execution of resolve_source_request failed
- Execution of NodeRenderGetContentResult::get failed
- Execution of render_static failed
- timeout while receiving message from process
- deadline has elapsed
event - GET /, and [project]/ changed 34s
event - GET /favicon.ico 17ms
[500] error (30s): timeout while receiving message from process
```
