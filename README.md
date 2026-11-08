# tscircuit status

<!-- START_STATUS_TABLE -->

| Service               | Current Status |
| --------------------- | -------------- |
| `registry-api` | ✅ Operational |
| `freerouting-cluster` | ✅ Operational |
| `jlcsearch-api` | ✅ Operational |
| `registry_bundling` | ✅ Operational |
| `fly_registry_api` | ✅ Operational |
| `compile_api` | ✅ Operational |
| `svg_service` | ✅ Operational |
| `browser_preview` | ✅ Operational |
| `tscircuit_package` | ❌ tscircuit package health check failed: Command failed: npm install -g tscircuit --force
npm warn using --force Recommended protections disabled.
npm warn ERESOLVE overriding peer dependency
npm warn While resolving: react-reconciler@0.34.0
npm warn Found: react@19.1.0
npm warn node_modules/tscircuit/node_modules/react
npm warn   react@"^19.1.0" from tscircuit@0.0.3119
npm warn   node_modules/tscircuit
npm warn     tscircuit@"*" from the root project
npm warn     2 more (@tscircuit/cli, @tscircuit/krt-wasm)
npm warn   11 more (@tscircuit/props, jscad-fiber, react-dom, ...)
npm warn
npm warn Could not resolve dependency:
npm warn peer react@"^19.3.0" from react-reconciler@0.34.0
npm warn node_modules/tscircuit/node_modules/react-reconciler
npm warn   peer react-reconciler@"*" from jscad-fiber@0.0.93
npm warn   node_modules/tscircuit/node_modules/jscad-fiber
npm warn
npm warn Conflicting peer dependency: react@19.3.1
npm warn node_modules/react
npm warn   peer react@"^19.3.0" from react-reconciler@0.34.0
npm warn   node_modules/tscircuit/node_modules/react-reconciler
npm warn     peer react-reconciler@"*" from jscad-fiber@0.0.93
npm warn     node_modules/tscircuit/node_modules/jscad-fiber
npm warn ERESOLVE overriding peer dependency
npm warn While resolving: jscad-electronics@0.0.243
npm warn Found: @tscircuit/alphabet@0.0.25
npm warn node_modules/tscircuit/node_modules/@tscircuit/alphabet
npm warn   @tscircuit/alphabet@"0.0.25" from tscircuit@0.0.3119
npm warn   node_modules/tscircuit
npm warn     tscircuit@"*" from the root project
npm warn     2 more (@tscircuit/cli, @tscircuit/krt-wasm)
npm warn   5 more (graphics-debug, circuit-json-to-gltf, circuit-to-svg, ...)
npm warn
npm warn Could not resolve dependency:
npm warn peer @tscircuit/alphabet@"^0.0.24" from jscad-electronics@0.0.243
npm warn node_modules/tscircuit/node_modules/circuit-json-to-gltf/node_modules/jscad-electronics
npm warn   jscad-electronics@"^0.0.243" from circuit-json-to-gltf@0.0.164
npm warn   node_modules/tscircuit/node_modules/circuit-json-to-gltf
npm warn
npm warn Conflicting peer dependency: @tscircuit/alphabet@0.0.24
npm warn node_modules/@tscircuit/alphabet
npm warn   peer @tscircuit/alphabet@"^0.0.24" from jscad-electronics@0.0.243
npm warn   node_modules/tscircuit/node_modules/circuit-json-to-gltf/node_modules/jscad-electronics
npm warn     jscad-electronics@"^0.0.243" from circuit-json-to-gltf@0.0.164
npm warn     node_modules/tscircuit/node_modules/circuit-json-to-gltf
npm warn ERESOLVE overriding peer dependency
npm warn While resolving: jscad-electronics@0.0.243
npm warn Found: circuit-json@0.0.547
npm warn node_modules/tscircuit/node_modules/circuit-json
npm warn   circuit-json@"^0.0.547" from tscircuit@0.0.3119
npm warn   node_modules/tscircuit
npm warn     tscircuit@"*" from the root project
npm warn     2 more (@tscircuit/cli, @tscircuit/krt-wasm)
npm warn   16 more (@tscircuit/checks, @tscircuit/circuit-json-util, ...)
npm warn
npm warn Could not resolve dependency:
npm warn peer circuit-json@"^0.0.426" from jscad-electronics@0.0.243
npm warn node_modules/tscircuit/node_modules/circuit-json-to-gltf/node_modules/jscad-electronics
npm warn   jscad-electronics@"^0.0.243" from circuit-json-to-gltf@0.0.164
npm warn   node_modules/tscircuit/node_modules/circuit-json-to-gltf
npm warn
npm warn Conflicting peer dependency: circuit-json@0.0.426
npm warn node_modules/circuit-json
npm warn   peer circuit-json@"^0.0.426" from jscad-electronics@0.0.243
npm warn   node_modules/tscircuit/node_modules/circuit-json-to-gltf/node_modules/jscad-electronics
npm warn     jscad-electronics@"^0.0.243" from circuit-json-to-gltf@0.0.164
npm warn     node_modules/tscircuit/node_modules/circuit-json-to-gltf
npm warn deprecated prebuild-install@7.1.3: No longer maintained. Please contact the author of the relevant native addon; alternatives are available.
npm error code 1
npm error path /usr/local/lib/node_modules/tscircuit/node_modules/sharp
npm error command failed
npm error command sh -c (node install/libvips && node install/dll-copy && prebuild-install) || (node install/can-compile && node-gyp rebuild && node install/dll-copy)
npm error sharp: Downloading https://github.com/lovell/sharp-libvips/releases/download/v8.14.5/libvips-8.14.5-linux-x64.tar.br
npm error sharp: Integrity check passed for linux-x64
npm error
npm error make: Entering directory '/usr/local/lib/node_modules/tscircuit/node_modules/sharp/build'
npm error   CC(target) Release/obj.target/nothing/../node-addon-api/nothing.o
npm error rm -f Release/obj.target/../node-addon-api/nothing.a Release/obj.target/../node-addon-api/nothing.a.ar-file-list; mkdir -p `dirname Release/obj.target/../node-addon-api/nothing.a`
npm error ar crs Release/obj.target/../node-addon-api/nothing.a @Release/obj.target/../node-addon-api/nothing.a.ar-file-list
npm error   COPY Release/nothing.a
npm error   TOUCH Release/obj.target/libvips-cpp.stamp
npm error   CXX(target) Release/obj.target/sharp-linux-x64/src/common.o
npm error make: Leaving directory '/usr/local/lib/node_modules/tscircuit/node_modules/sharp/build'
npm error (node:2337) [DEP0176] DeprecationWarning: fs.R_OK is deprecated, use fs.constants.R_OK instead
npm error (Use `node --trace-deprecation ...` to show where the warning was created)
npm error prebuild-install warn install No prebuilt binaries found (target=7 runtime=napi arch=x64 libc= platform=linux)
npm error gyp info it worked if it ends with ok
npm error gyp info using node-gyp@12.4.0
npm error gyp info using node@24.22.2 | linux | x64
npm error gyp info find Python using Python version 3.14.4 found at "/usr/bin/python3"
npm error gyp http GET https://nodejs.org/download/release/v24.22.2/node-v24.22.2-headers.tar.gz
npm error gyp http 200 https://nodejs.org/download/release/v24.22.2/node-v24.22.2-headers.tar.gz
npm error gyp http GET https://nodejs.org/download/release/v24.22.2/SHASUMS256.txt
npm error gyp http 200 https://nodejs.org/download/release/v24.22.2/SHASUMS256.txt
npm error gyp info spawn /usr/bin/python3
npm error gyp info spawn args [
npm error gyp info spawn args '/usr/local/lib/node_modules/npm/node_modules/node-gyp/gyp/gyp_main.py',
npm error gyp info spawn args 'binding.gyp',
npm error gyp info spawn args '-f',
npm error gyp info spawn args 'make',
npm error gyp info spawn args '-I',
npm error gyp info spawn args '/usr/local/lib/node_modules/tscircuit/node_modules/sharp/build/config.gypi',
npm error gyp info spawn args '-I',
npm error gyp info spawn args '/usr/local/lib/node_modules/npm/node_modules/node-gyp/addon.gypi',
npm error gyp info spawn args '-I',
npm error gyp info spawn args '/home/runner/.cache/node-gyp/24.22.2/include/node/common.gypi',
npm error gyp info spawn args '-Dlibrary=shared_library',
npm error gyp info spawn args '-Dvisibility=default',
npm error gyp info spawn args '-Dnode_root_dir=/home/runner/.cache/node-gyp/24.22.2',
npm error gyp info spawn args '-Dnode_gyp_dir=/usr/local/lib/node_modules/npm/node_modules/node-gyp',
npm error gyp info spawn args '-Dnode_lib_file=/home/runner/.cache/node-gyp/24.22.2/<(target_arch)/node.lib',
npm error gyp info spawn args '-Dmodule_root_dir=/usr/local/lib/node_modules/tscircuit/node_modules/sharp',
npm error gyp info spawn args '-Dnode_engine=v8',
npm error gyp info spawn args '--depth=.',
npm error gyp info spawn args '--no-parallel',
npm error gyp info spawn args '--generator-output',
npm error gyp info spawn args 'build',
npm error gyp info spawn args '-Goutput_dir=.'
npm error gyp info spawn args ]
npm error <string>:108: SyntaxWarning: "\/" is an invalid escape sequence. Such sequences will not work in the future. Did you mean "\\/"? A raw string is also an option.
npm error gyp info spawn make
npm error gyp info spawn args [ 'BUILDTYPE=Release', '-C', 'build' ]
npm error ../src/common.cc:13:10: fatal error: vips/vips8: No such file or directory
npm error    13 | #include <vips/vips8>
npm error       |          ^~~~~~~~~~~~
npm error compilation terminated.
npm error make: *** [sharp-linux-x64.target.mk:142: Release/obj.target/sharp-linux-x64/src/common.o] Error 1
npm error gyp ERR! build error 
npm error gyp ERR! stack Error: `make` failed with exit code: 2
npm error gyp ERR! stack at ChildProcess.<anonymous> (/usr/local/lib/node_modules/npm/node_modules/node-gyp/lib/build.js:219:23)
npm error gyp ERR! System Linux 7.0.0-1019-azure
npm error gyp ERR! command "/usr/local/bin/node" "/usr/local/lib/node_modules/npm/node_modules/node-gyp/bin/node-gyp.js" "rebuild"
npm error gyp ERR! cwd /usr/local/lib/node_modules/tscircuit/node_modules/sharp
npm error gyp ERR! node -v v24.22.2
npm error gyp ERR! node-gyp -v v12.4.0
npm error gyp ERR! $npm_package_name sharp
npm error gyp ERR! $npm_package_version 0.32.6
npm error gyp ERR! not ok
npm error A complete log of this run can be found in: /home/runner/.npm/_logs/2026-11-08T08_53_20_936Z-debug-0.log
 |
| `usercode_api` | ✅ Operational |

<!-- END_STATUS_TABLE -->

Status checks for tscircuit internal services.

Runs every 10 minutes using github workflows.

Every time it runs it appends the status check results to `statuses.jsonl` (limiting to
2 weeks of logs)

Each service has a specific method to check it, see [./service-checks](./service-checks)

You may need particular auth environment variables to run the checks.
