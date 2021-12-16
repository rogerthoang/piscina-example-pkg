```npm install```
```npm run-script build```
 > run the .exe created in the .dist dir
 > an error like this will be thrown

 ```
 $ ./piscina-example.exe 

node:internal/process/promises:246
          triggerUncaughtException(err, true /* fromPromise */);
          ^
Error: Cannot find module 'C:\snapshot\piscina-example\node_modules\piscina\dist\src\worker.js'
    at Function.Module._resolveFilename (node:internal/modules/cjs/loader:933:15)
    at Function._resolveFilename (pkg/prelude/bootstrap.js:1819:46)
    at Function.Module._load (node:internal/modules/cjs/loader:778:27)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:81:12)
    at MessagePort.<anonymous> (node:internal/main/worker_thread:187:24)
    at MessagePort.[nodejs.internal.kHybridDispatch] (node:internal/event_target:562:20)
    at MessagePort.exports.emitMessage (node:internal/per_context/messageport:23:28) {
  code: 'MODULE_NOT_FOUND',
  requireStack: []
}
 ```