4 warnings and 1 error generated.
make: *** [Release/obj.target/fse/fsevents.o] Error 1
gyp ERR! build error 
gyp ERR! stack Error: `make` failed with exit code: 2
gyp ERR! stack     at ChildProcess.onExit (/usr/local/lib/node_modules/npm/node_modules/node-gyp/lib/build.js:258:23)
gyp ERR! stack     at ChildProcess.emit (events.js:182:13)
gyp ERR! stack     at Process.ChildProcess._handle.onexit (internal/child_process.js:235:12)
gyp ERR! System Darwin 17.5.0
gyp ERR! command "/usr/local/Cellar/node/10.1.0/bin/node" "/usr/local/lib/node_modules/npm/node_modules/node-gyp/bin/node-gyp.js" "build" "--fallback-to-build" "--module=/Users/sergeygultyayev/Projects/portfolio/node_modules/fsevents/lib/binding/Release/node-v64-darwin-x64/fse.node" "--module_name=fse" "--module_path=/Users/sergeygultyayev/Projects/portfolio/node_modules/fsevents/lib/binding/Release/node-v64-darwin-x64"
gyp ERR! cwd /Users/sergeygultyayev/Projects/portfolio/node_modules/fsevents
gyp ERR! node -v v10.1.0
gyp ERR! node-gyp -v v3.6.2
gyp ERR! not ok 
node-pre-gyp ERR! build error 
node-pre-gyp ERR! stack Error: Failed to execute '/usr/local/Cellar/node/10.1.0/bin/node /usr/local/lib/node_modules/npm/node_modules/node-gyp/bin/node-gyp.js build --fallback-to-build --module=/Users/sergeygultyayev/Projects/portfolio/node_modules/fsevents/lib/binding/Release/node-v64-darwin-x64/fse.node --module_name=fse --module_path=/Users/sergeygultyayev/Projects/portfolio/node_modules/fsevents/lib/binding/Release/node-v64-darwin-x64' (1)
node-pre-gyp ERR! stack     at ChildProcess.<anonymous> (/Users/sergeygultyayev/Projects/portfolio/node_modules/fsevents/node_modules/node-pre-gyp/lib/util/compile.js:83:29)
node-pre-gyp ERR! stack     at ChildProcess.emit (events.js:182:13)
node-pre-gyp ERR! stack     at maybeClose (internal/child_process.js:957:16)
node-pre-gyp ERR! stack     at Process.ChildProcess._handle.onexit (internal/child_process.js:246:5)
node-pre-gyp ERR! System Darwin 17.5.0
node-pre-gyp ERR! command "/usr/local/Cellar/node/10.1.0/bin/node" "/Users/sergeygultyayev/Projects/portfolio/node_modules/fsevents/node_modules/node-pre-gyp/bin/node-pre-gyp" "install" "--fallback-to-build"
node-pre-gyp ERR! cwd /Users/sergeygultyayev/Projects/portfolio/node_modules/fsevents
node-pre-gyp ERR! node -v v10.1.0
node-pre-gyp ERR! node-pre-gyp -v v0.6.39
node-pre-gyp ERR! not ok 
Failed to execute '/usr/local/Cellar/node/10.1.0/bin/node /usr/local/lib/node_modules/npm/node_modules/node-gyp/bin/node-gyp.js build --fallback-to-build --module=/Users/sergeygultyayev/Projects/portfolio/node_modules/fsevents/lib/binding/Release/node-v64-darwin-x64/fse.node --module_name=fse --module_path=/Users/sergeygultyayev/Projects/portfolio/node_modules/fsevents/lib/binding/Release/node-v64-darwin-x64' (1)
npm WARN optional SKIPPING OPTIONAL DEPENDENCY: fsevents@1.1.3 (node_modules/fsevents):
npm WARN optional SKIPPING OPTIONAL DEPENDENCY: fsevents@1.1.3 install: `node install`
npm WARN optional SKIPPING OPTIONAL DEPENDENCY: Exit status 1

+ firebase@5.0.2
updated 16 packages in 59.177s
[!] 85 vulnerabilities found [24751 packages audited]
    Severity: 35 Low | 32 Moderate | 18 High
    Run `npm audit` for more detail

#Solution

`remove yarn.lock & reinstall (yarn install)`
