# 06-11-22 First Try FAILED!!

## Console Commands & Output Logs to LEARN from.

jmt@penguin:~/ALL Test Projects/takenote$ pnpm add takenote
 WARN  deprecated @types/axios@0.14.0: This is a stub types definition for axios (https://github.com/mzabriskie/axios). axios provides its own type definitions, so you don't need @types/axios installed!
 WARN  deprecated @types/jszip@3.4.1: This is a stub types definition. jszip provides its own type definitions, so you do not need this installed.
 WARN  deprecated @types/react-helmet-async@1.0.3: This is a stub types definition. react-helmet-async provides its own type definitions, so you do not need this installed.
 WARN  deprecated request@2.88.2: request has been deprecated, see https://github.com/request/request/issues/3142
 WARN  deprecated chokidar@2.1.8: Chokidar 2 does not receive security updates since 2019. Upgrade to chokidar 3 with 15x fewer dependencies
 WARN  deprecated fsevents@1.2.13: fsevents 1 will break on node v14+ and could be using insecure binaries. Upgrade to fsevents 2.
 WARN  deprecated source-map-resolve@0.6.0: See https://github.com/lydell/source-map-resolve#deprecated
 WARN  deprecated har-validator@5.1.5: this library is no longer supported
 WARN  deprecated uuid@3.4.0: Please upgrade  to version 7 or higher.  Older versions may use Math.random() in certain circumstances, which is known to be problematic.  See https://v8.dev/blog/math-random for details.
 WARN  deprecated querystring@0.2.0: The querystring API is considered Legacy. new code should use the URLSearchParams API instead.
 WARN  deprecated svgo@1.3.2: This SVGO version is no longer supported. Upgrade to v2.x.x.
 WARN  deprecated tar@2.2.2: This version of tar is no longer supported, and will not receive security updates. Please upgrade asap.
 WARN  deprecated sane@4.1.0: some dependency vulnerabilities fixed, support for node < 10 dropped, and newer ECMAScript syntax/features added
 WARN  deprecated source-map-resolve@0.5.3: See https://github.com/lydell/source-map-resolve#deprecated
 WARN  deprecated source-map-url@0.4.1: See https://github.com/lydell/source-map-url#deprecated
 WARN  deprecated urix@0.1.0: Please see https://github.com/lydell/urix#deprecated
 WARN  deprecated resolve-url@0.2.1: https://github.com/lydell/resolve-url#deprecated
Packages: +1
+
Progress: resolved 1720, reused 1709, downloaded 1, added 1, done

dependencies:
+ takenote 0.1.0
jmt@penguin:~/ALL Test Projects/takenote$ pnpm run client

> takenote@0.7.2 client /home/jmt/ALL Test Projects/takenote
> cross-env NODE_ENV=development webpack serve --config config/webpack.dev.js

ℹ ｢wds｣: Project is running at http://localhost:3000/
ℹ ｢wds｣: webpack output is served from /
ℹ ｢wds｣: Content not from webpack is served from /home/jmt/ALL Test Projects/takenote
ℹ ｢wds｣: 404s will fallback to /index.html
ℹ ｢wdm｣: wait until bundle finished: /
✖ ｢wdm｣: assets by info 14.8 MiB [immutable]
  assets by path *.png 1.59 MiB 3 assets
  assets by path *.svg 3.66 KiB
    asset 90beb9080e8c3ccb8565.svg 2.04 KiB [emitted] [immutable] [from: src/resources/assets/logo-square-white.svg] (auxiliary name: main)
    asset 26da41caf83070639053.svg 1.61 KiB [emitted] [immutable] [from: src/resources/assets/logo-square-color.svg] (auxiliary name: main)
  asset main.f861e01d05468e341509.bundle.js 13.2 MiB [emitted] [immutable] (name: main)
assets by path *.html 836 bytes
  asset index.html 443 bytes [emitted]
  asset template.html 393 bytes [emitted] [from: public/template.html] [copied]
asset logo512.png 44.7 KiB [emitted] [from: public/logo512.png] [copied]
asset logo192.png 15.5 KiB [emitted] [from: public/logo192.png] [copied]
asset favicon.ico 4.31 KiB [emitted] [from: public/favicon.ico] [copied]
asset manifest.json 505 bytes [emitted] [from: public/manifest.json] [copied]
asset _redirects 23 bytes [emitted] [from: public/_redirects] [copied]
asset robots.txt 14 bytes [emitted] [from: public/robots.txt] [copied]
runtime modules 26.6 KiB 15 modules
modules by path ./node_modules/.pnpm/ 4.22 MiB
  javascript modules 4.22 MiB 717 modules
  json modules 3.95 KiB
    ./node_modules/.pnpm/axios@0.21.4/node_modules/axios/package.json 1.92 KiB [built] [code generated]
    ./node_modules/.pnpm/remark-parse@5.0.0/node_modules/remark-parse/lib/block-elements.json 521 bytes [built] [code generated]
    + 2 modules
modules by path ./src/ 216 KiB (javascript) 1.59 MiB (asset)
  modules by path ./src/client/ 211 KiB 59 modules
  modules by path ./src/resources/ 5.24 KiB (javascript) 1.59 MiB (asset)
    asset modules 210 bytes (javascript) 1.59 MiB (asset) 5 modules
    javascript modules 5.03 KiB
      ./src/resources/LabelText.ts 1.6 KiB [built] [code generated]
      ./src/resources/TestID.ts 3.43 KiB [built] [code generated]
./node_modules/dayjs/locale/ sync ^\.\/.*\.js$ 1.98 KiB [optional] [built] [code generated]

ERROR in ./node_modules/.pnpm/codemirror@5.65.5/node_modules/codemirror/lib/codemirror.css (./node_modules/.pnpm/css-loader@5.2.7_webpack@5.73.0/node_modules/css-loader/dist/cjs.js??ruleSet[1].rules[4].use[1]!./node_modules/.pnpm/sass-loader@10.2.1_ezofvu22aqgk6fclz7jsopgpf4/node_modules/sass-loader/dist/cjs.js??ruleSet[1].rules[4].use[2]!./node_modules/.pnpm/codemirror@5.65.5/node_modules/codemirror/lib/codemirror.css)
Module Error (from ./node_modules/.pnpm/sass-loader@10.2.1_ezofvu22aqgk6fclz7jsopgpf4/node_modules/sass-loader/dist/cjs.js):
Node Sass does not yet support your current environment: Linux 64-bit with Unsupported runtime (108)
For more information on which environments are supported please see:
https://github.com/sass/node-sass/releases/tag/v4.14.1
 @ ./node_modules/.pnpm/codemirror@5.65.5/node_modules/codemirror/lib/codemirror.css 2:12-284 9:17-24 13:7-21 45:20-34 49:6-59:7 50:38-52 56:26-40 58:21-28 68:15-29 47:4-60:5
 @ ./src/client/containers/NoteEditor.tsx 18:0-40
 @ ./src/client/containers/TakeNoteApp.tsx 50:19-53
 @ ./src/client/containers/App.tsx 32:20-55
 @ ./src/client/index.tsx 21:12-39

ERROR in ./node_modules/.pnpm/codemirror@5.65.5/node_modules/codemirror/lib/codemirror.css (./node_modules/.pnpm/css-loader@5.2.7_webpack@5.73.0/node_modules/css-loader/dist/cjs.js??ruleSet[1].rules[4].use[1]!./node_modules/.pnpm/sass-loader@10.2.1_ezofvu22aqgk6fclz7jsopgpf4/node_modules/sass-loader/dist/cjs.js??ruleSet[1].rules[4].use[2]!./node_modules/.pnpm/codemirror@5.65.5/node_modules/codemirror/lib/codemirror.css)
Module build failed (from ./node_modules/.pnpm/css-loader@5.2.7_webpack@5.73.0/node_modules/css-loader/dist/cjs.js):
Error: PostCSS received undefined instead of CSS string
    at new Input (/home/jmt/ALL Test Projects/takenote/node_modules/.pnpm/postcss@8.4.14/node_modules/postcss/lib/input.js:24:13)
    at parse (/home/jmt/ALL Test Projects/takenote/node_modules/.pnpm/postcss@8.4.14/node_modules/postcss/lib/parse.js:8:15)
    at new LazyResult (/home/jmt/ALL Test Projects/takenote/node_modules/.pnpm/postcss@8.4.14/node_modules/postcss/lib/lazy-result.js:133:16)
    at Processor.process (/home/jmt/ALL Test Projects/takenote/node_modules/.pnpm/postcss@8.4.14/node_modules/postcss/lib/processor.js:28:14)
    at Object.loader (/home/jmt/ALL Test Projects/takenote/node_modules/.pnpm/css-loader@5.2.7_webpack@5.73.0/node_modules/css-loader/dist/index.js:140:51)
 @ ./node_modules/.pnpm/codemirror@5.65.5/node_modules/codemirror/lib/codemirror.css 2:12-284 9:17-24 13:7-21 45:20-34 49:6-59:7 50:38-52 56:26-40 58:21-28 68:15-29 47:4-60:5
 @ ./src/client/containers/NoteEditor.tsx 18:0-40
 @ ./src/client/containers/TakeNoteApp.tsx 50:19-53
 @ ./src/client/containers/App.tsx 32:20-55
 @ ./src/client/index.tsx 21:12-39

ERROR in ./node_modules/.pnpm/codemirror@5.65.5/node_modules/codemirror/theme/base16-light.css (./node_modules/.pnpm/css-loader@5.2.7_webpack@5.73.0/node_modules/css-loader/dist/cjs.js??ruleSet[1].rules[4].use[1]!./node_modules/.pnpm/sass-loader@10.2.1_ezofvu22aqgk6fclz7jsopgpf4/node_modules/sass-loader/dist/cjs.js??ruleSet[1].rules[4].use[2]!./node_modules/.pnpm/codemirror@5.65.5/node_modules/codemirror/theme/base16-light.css)
Module Error (from ./node_modules/.pnpm/sass-loader@10.2.1_ezofvu22aqgk6fclz7jsopgpf4/node_modules/sass-loader/dist/cjs.js):
Node Sass does not yet support your current environment: Linux 64-bit with Unsupported runtime (108)
For more information on which environments are supported please see:
https://github.com/sass/node-sass/releases/tag/v4.14.1
 @ ./node_modules/.pnpm/codemirror@5.65.5/node_modules/codemirror/theme/base16-light.css 2:12-286 9:17-24 13:7-21 45:20-34 49:6-59:7 50:38-52 56:26-40 58:21-28 68:15-29 47:4-60:5
 @ ./src/client/containers/NoteEditor.tsx 19:0-44
 @ ./src/client/containers/TakeNoteApp.tsx 50:19-53
 @ ./src/client/containers/App.tsx 32:20-55
 @ ./src/client/index.tsx 21:12-39

ERROR in ./node_modules/.pnpm/codemirror@5.65.5/node_modules/codemirror/theme/base16-light.css (./node_modules/.pnpm/css-loader@5.2.7_webpack@5.73.0/node_modules/css-loader/dist/cjs.js??ruleSet[1].rules[4].use[1]!./node_modules/.pnpm/sass-loader@10.2.1_ezofvu22aqgk6fclz7jsopgpf4/node_modules/sass-loader/dist/cjs.js??ruleSet[1].rules[4].use[2]!./node_modules/.pnpm/codemirror@5.65.5/node_modules/codemirror/theme/base16-light.css)
Module build failed (from ./node_modules/.pnpm/css-loader@5.2.7_webpack@5.73.0/node_modules/css-loader/dist/cjs.js):
Error: PostCSS received undefined instead of CSS string
    at new Input (/home/jmt/ALL Test Projects/takenote/node_modules/.pnpm/postcss@8.4.14/node_modules/postcss/lib/input.js:24:13)
    at parse (/home/jmt/ALL Test Projects/takenote/node_modules/.pnpm/postcss@8.4.14/node_modules/postcss/lib/parse.js:8:15)
    at new LazyResult (/home/jmt/ALL Test Projects/takenote/node_modules/.pnpm/postcss@8.4.14/node_modules/postcss/lib/lazy-result.js:133:16)
    at Processor.process (/home/jmt/ALL Test Projects/takenote/node_modules/.pnpm/postcss@8.4.14/node_modules/postcss/lib/processor.js:28:14)
    at Object.loader (/home/jmt/ALL Test Projects/takenote/node_modules/.pnpm/css-loader@5.2.7_webpack@5.73.0/node_modules/css-loader/dist/index.js:140:51)
 @ ./node_modules/.pnpm/codemirror@5.65.5/node_modules/codemirror/theme/base16-light.css 2:12-286 9:17-24 13:7-21 45:20-34 49:6-59:7 50:38-52 56:26-40 58:21-28 68:15-29 47:4-60:5
 @ ./src/client/containers/NoteEditor.tsx 19:0-44
 @ ./src/client/containers/TakeNoteApp.tsx 50:19-53
 @ ./src/client/containers/App.tsx 32:20-55
 @ ./src/client/index.tsx 21:12-39

ERROR in ./src/client/styles/index.scss (./node_modules/.pnpm/css-loader@5.2.7_webpack@5.73.0/node_modules/css-loader/dist/cjs.js??ruleSet[1].rules[4].use[1]!./node_modules/.pnpm/sass-loader@10.2.1_ezofvu22aqgk6fclz7jsopgpf4/node_modules/sass-loader/dist/cjs.js??ruleSet[1].rules[4].use[2]!./src/client/styles/index.scss)
Module Error (from ./node_modules/.pnpm/sass-loader@10.2.1_ezofvu22aqgk6fclz7jsopgpf4/node_modules/sass-loader/dist/cjs.js):
Node Sass does not yet support your current environment: Linux 64-bit with Unsupported runtime (108)
For more information on which environments are supported please see:
https://github.com/sass/node-sass/releases/tag/v4.14.1
 @ ./src/client/styles/index.scss 2:12-312 9:17-24 13:7-21 45:20-34 49:6-59:7 50:38-52 56:26-40 58:21-28 68:15-29 47:4-60:5
 @ ./src/client/index.tsx 25:0-30

ERROR in ./src/client/styles/index.scss (./node_modules/.pnpm/css-loader@5.2.7_webpack@5.73.0/node_modules/css-loader/dist/cjs.js??ruleSet[1].rules[4].use[1]!./node_modules/.pnpm/sass-loader@10.2.1_ezofvu22aqgk6fclz7jsopgpf4/node_modules/sass-loader/dist/cjs.js??ruleSet[1].rules[4].use[2]!./src/client/styles/index.scss)
Module build failed (from ./node_modules/.pnpm/css-loader@5.2.7_webpack@5.73.0/node_modules/css-loader/dist/cjs.js):
Error: PostCSS received undefined instead of CSS string
    at new Input (/home/jmt/ALL Test Projects/takenote/node_modules/.pnpm/postcss@8.4.14/node_modules/postcss/lib/input.js:24:13)
    at parse (/home/jmt/ALL Test Projects/takenote/node_modules/.pnpm/postcss@8.4.14/node_modules/postcss/lib/parse.js:8:15)
    at new LazyResult (/home/jmt/ALL Test Projects/takenote/node_modules/.pnpm/postcss@8.4.14/node_modules/postcss/lib/lazy-result.js:133:16)
    at Processor.process (/home/jmt/ALL Test Projects/takenote/node_modules/.pnpm/postcss@8.4.14/node_modules/postcss/lib/processor.js:28:14)
    at Object.loader (/home/jmt/ALL Test Projects/takenote/node_modules/.pnpm/css-loader@5.2.7_webpack@5.73.0/node_modules/css-loader/dist/index.js:140:51)
 @ ./src/client/styles/index.scss 2:12-312 9:17-24 13:7-21 45:20-34 49:6-59:7 50:38-52 56:26-40 58:21-28 68:15-29 47:4-60:5
 @ ./src/client/index.tsx 25:0-30

ERROR in ./src/client/utils/history.ts 3:16-34
Module not found: Error: Can't resolve 'history' in '/home/jmt/ALL Test Projects/takenote/src/client/utils'
Did you mean './history'?
Requests that should resolve in the current directory need to start with './'.
Requests that start with a name are treated as module requests and resolve within module directories (node_modules).
If changing the source code is not an option there is also a resolve options called 'preferRelative' which tries to resolve these kind of requests in the current directory too.
 @ ./src/client/index.tsx 24:32-58

ERROR in /home/jmt/ALL Test Projects/takenote/src/client/sagas/index.ts
./src/client/sagas/index.ts 36:25-30
[tsl] ERROR in /home/jmt/ALL Test Projects/takenote/src/client/sagas/index.ts(36,26)
      TS2571: Object is of type 'unknown'.
 @ ./src/client/index.tsx 22:30-48

ERROR in /home/jmt/ALL Test Projects/takenote/src/client/sagas/index.ts
./src/client/sagas/index.ts 60:13-33
[tsl] ERROR in /home/jmt/ALL Test Projects/takenote/src/client/sagas/index.ts(60,14)
      TS7057: 'yield' expression implicitly results in an 'any' type because its containing generator lacks a return-type annotation.
 @ ./src/client/index.tsx 22:30-48

ERROR in /home/jmt/ALL Test Projects/takenote/src/client/sagas/index.ts
./src/client/sagas/index.ts 62:14-44
[tsl] ERROR in /home/jmt/ALL Test Projects/takenote/src/client/sagas/index.ts(62,15)
      TS7057: 'yield' expression implicitly results in an 'any' type because its containing generator lacks a return-type annotation.
 @ ./src/client/index.tsx 22:30-48

ERROR in /home/jmt/ALL Test Projects/takenote/src/client/sagas/index.ts
./src/client/sagas/index.ts 68:29-34
[tsl] ERROR in /home/jmt/ALL Test Projects/takenote/src/client/sagas/index.ts(68,30)
      TS2571: Object is of type 'unknown'.
 @ ./src/client/index.tsx 22:30-48

ERROR in /home/jmt/ALL Test Projects/takenote/src/client/sagas/index.ts
./src/client/sagas/index.ts 77:13-38
[tsl] ERROR in /home/jmt/ALL Test Projects/takenote/src/client/sagas/index.ts(77,14)
      TS7057: 'yield' expression implicitly results in an 'any' type because its containing generator lacks a return-type annotation.
 @ ./src/client/index.tsx 22:30-48

ERROR in /home/jmt/ALL Test Projects/takenote/src/client/sagas/index.ts
./src/client/sagas/index.ts 79:14-49
[tsl] ERROR in /home/jmt/ALL Test Projects/takenote/src/client/sagas/index.ts(79,15)
      TS7057: 'yield' expression implicitly results in an 'any' type because its containing generator lacks a return-type annotation.
 @ ./src/client/index.tsx 22:30-48

ERROR in /home/jmt/ALL Test Projects/takenote/src/client/sagas/index.ts
./src/client/sagas/index.ts 84:34-39
[tsl] ERROR in /home/jmt/ALL Test Projects/takenote/src/client/sagas/index.ts(84,35)
      TS2571: Object is of type 'unknown'.
 @ ./src/client/index.tsx 22:30-48

ERROR in /home/jmt/ALL Test Projects/takenote/src/client/sagas/index.ts
./src/client/sagas/index.ts 92:11-34
[tsl] ERROR in /home/jmt/ALL Test Projects/takenote/src/client/sagas/index.ts(92,12)
      TS7057: 'yield' expression implicitly results in an 'any' type because its containing generator lacks a return-type annotation.
 @ ./src/client/index.tsx 22:30-48

ERROR in /home/jmt/ALL Test Projects/takenote/src/client/sagas/index.ts
./src/client/sagas/index.ts 109:24-29
[tsl] ERROR in /home/jmt/ALL Test Projects/takenote/src/client/sagas/index.ts(109,25)
      TS2571: Object is of type 'unknown'.
 @ ./src/client/index.tsx 22:30-48

ERROR in /home/jmt/ALL Test Projects/takenote/src/client/sagas/index.ts
./src/client/sagas/index.ts 115:21-46
[tsl] ERROR in /home/jmt/ALL Test Projects/takenote/src/client/sagas/index.ts(115,22)
      TS7057: 'yield' expression implicitly results in an 'any' type because its containing generator lacks a return-type annotation.
 @ ./src/client/index.tsx 22:30-48

ERROR in /home/jmt/ALL Test Projects/takenote/src/client/utils/history.ts
./src/client/utils/history.ts 1:37-46
[tsl] ERROR in /home/jmt/ALL Test Projects/takenote/src/client/utils/history.ts(1,38)
      TS2307: Cannot find module 'history' or its corresponding type declarations.
 @ ./src/client/index.tsx 24:32-58

ERROR in /home/jmt/ALL Test Projects/takenote/src/server/handlers/auth.ts
98:43-48
[tsl] ERROR in /home/jmt/ALL Test Projects/takenote/src/server/handlers/auth.ts(98,44)
      TS2571: Object is of type 'unknown'.

ERROR in /home/jmt/ALL Test Projects/takenote/src/server/handlers/auth.ts
138:20-25
[tsl] ERROR in /home/jmt/ALL Test Projects/takenote/src/server/handlers/auth.ts(138,21)
      TS2769: No overload matches this call.
  Overload 1 of 2, '(message?: string | undefined, options?: ErrorOptions | undefined): Error', gave the following error.
    Argument of type 'unknown' is not assignable to parameter of type 'string | undefined'.
  Overload 2 of 2, '(message?: string | undefined): Error', gave the following error.
    Argument of type 'unknown' is not assignable to parameter of type 'string | undefined'.

ERROR in /home/jmt/ALL Test Projects/takenote/src/server/handlers/auth.ts
156:20-25
[tsl] ERROR in /home/jmt/ALL Test Projects/takenote/src/server/handlers/auth.ts(156,21)
      TS2769: No overload matches this call.
  Overload 1 of 2, '(message?: string | undefined, options?: ErrorOptions | undefined): Error', gave the following error.
    Argument of type 'unknown' is not assignable to parameter of type 'string | undefined'.
  Overload 2 of 2, '(message?: string | undefined): Error', gave the following error.
    Argument of type 'unknown' is not assignable to parameter of type 'string | undefined'.

ERROR in /home/jmt/ALL Test Projects/takenote/src/server/handlers/sync.ts
78:25-30
[tsl] ERROR in /home/jmt/ALL Test Projects/takenote/src/server/handlers/sync.ts(78,26)
      TS2571: Object is of type 'unknown'.

ERROR in /home/jmt/ALL Test Projects/takenote/src/server/handlers/sync.ts
99:45-50
[tsl] ERROR in /home/jmt/ALL Test Projects/takenote/src/server/handlers/sync.ts(99,46)
      TS2571: Object is of type 'unknown'.

ERROR in /home/jmt/ALL Test Projects/takenote/src/server/handlers/sync.ts
106:25-30
[tsl] ERROR in /home/jmt/ALL Test Projects/takenote/src/server/handlers/sync.ts(106,26)
      TS2571: Object is of type 'unknown'.

ERROR in /home/jmt/ALL Test Projects/takenote/src/server/handlers/sync.ts
127:45-50
[tsl] ERROR in /home/jmt/ALL Test Projects/takenote/src/server/handlers/sync.ts(127,46)
      TS2571: Object is of type 'unknown'.

ERROR in /home/jmt/ALL Test Projects/takenote/src/server/handlers/sync.ts
134:25-30
[tsl] ERROR in /home/jmt/ALL Test Projects/takenote/src/server/handlers/sync.ts(134,26)
      TS2571: Object is of type 'unknown'.

ERROR in /home/jmt/ALL Test Projects/takenote/tests/unit/client/testHelpers.tsx
2:51-60
[tsl] ERROR in /home/jmt/ALL Test Projects/takenote/tests/unit/client/testHelpers.tsx(2,52)
      TS2307: Cannot find module 'history' or its corresponding type declarations.

ERROR in /home/jmt/ALL Test Projects/takenote/tests/unit/client/components/NoteList/NoteListButton.test.tsx
33:19-31
[tsl] ERROR in /home/jmt/ALL Test Projects/takenote/tests/unit/client/components/NoteList/NoteListButton.test.tsx(33,20)
      TS2551: Property 'toBeDisabled' does not exist on type 'JestMatchers<HTMLElement | null>'. Did you mean 'toBeSealed'?

ERROR in /home/jmt/ALL Test Projects/takenote/tests/unit/client/components/SettingsModal/IconButton.test.tsx
36:19-31
[tsl] ERROR in /home/jmt/ALL Test Projects/takenote/tests/unit/client/components/SettingsModal/IconButton.test.tsx(36,20)
      TS2551: Property 'toBeDisabled' does not exist on type 'JestMatchers<HTMLElement | null>'. Did you mean 'toBeSealed'?

ERROR in /home/jmt/ALL Test Projects/takenote/tests/unit/client/components/editor/EditorEmpty.test.tsx
21:27-36
[tsl] ERROR in /home/jmt/ALL Test Projects/takenote/tests/unit/client/components/editor/EditorEmpty.test.tsx(21,28)
      TS2339: Property 'toBeValid' does not exist on type 'JestMatchers<HTMLElement | null>'.

4 errors have detailed information that is not shown.
Use 'stats.errorDetails: true' resp. '--stats-error-details' to show it.

webpack 5.73.0 compiled with 30 errors in 128608 ms
ℹ ｢wdm｣: Failed to compile.
