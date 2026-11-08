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
npm error sharp: Please see https://sharp.pixelplumbing.com/install for required dependencies
npm error sharp: Installation error: Status 504 Gateway Time-out
npm error A complete log of this run can be found in: /home/runner/.npm/_logs/2026-11-08T09_43_19_959Z-debug-0.log
 |
| `usercode_api` | ✅ Operational |

<!-- END_STATUS_TABLE -->

Status checks for tscircuit internal services.

Runs every 10 minutes using github workflows.

Every time it runs it appends the status check results to `statuses.jsonl` (limiting to
2 weeks of logs)

Each service has a specific method to check it, see [./service-checks](./service-checks)

You may need particular auth environment variables to run the checks.
