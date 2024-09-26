``` bash
# 타입스크립트 ㅋ컴파일러 설치
npm i -g typescript ts-node
```

``` bash
tsc -v
ts-node -v
```

``` bash
# 타입스크립트 프로그램 만들고 컴파일하기
 mkdir ch01_TIL/ch01_04/src
 touch ch01_TIL/ch01_04/src/index.ts
 cd ch01/ch01_04


만났던 에러
 $ ts-node ./src/index.ts
(node:22012) Warning: To load an ES module, set "type": "module" in the package.json or use the .mjs extension.
(Use `node --trace-warnings ...` to show where the warning was created)
C:\workspace\typescript\webApp_TIL\ch01_til\ch01_04\src\index.ts:2
export {};
^^^^^^

SyntaxError: Unexpected token 'export'
    at wrapSafe (node:internal/modules/cjs/loader:1378:20)
    at Module._compile (node:internal/modules/cjs/loader:1428:41)
    at Module.m._compile (C:\Users\song\AppData\Roaming\npm\node_modules\ts-node\src\index.ts:1618:23)
    at Module._extensions..js (node:internal/modules/cjs/loader:1548:10)
    at Object.require.extensions.<computed> [as .ts] (C:\Users\song\AppData\Roaming\npm\node_modules\ts-node\src\index.ts:1621:12)
    at Module.load (node:internal/modules/cjs/loader:1288:32)
    at Function.Module._load (node:internal/modules/cjs/loader:1104:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:174:12)
    at phase4 (C:\Users\song\AppData\Roaming\npm\node_modules\ts-node\src\bin.ts:649:14)
    at bootstrap (C:\Users\song\AppData\Roaming\npm\node_modules\ts-node\src\bin.ts:95:10)