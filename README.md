# VTEX CLI Plugin URL

Extend the `vtex` toolbelt!

## Developing

1. Clone `vtex/toolbelt` and follow the steps on the Contributing section.
2. Clone/Create a plugin with this template.
3. Change the template name under this project's `package.json`.
2. Run `yarn link` on this project.
3. Now run `vtex link @vtex/cli-plugin-template` (or the new name) on the `vtex/toolbelt` project.
4. Run `yarn watch` on the `vtex/toolbelt`
5. Test the command on a VTEX IO app with `vtex-test hello`

For more information, read [Ocliff Docs](https://oclif.io/docs/introduction).

[![oclif](https://img.shields.io/badge/cli-oclif-brightgreen.svg)](https://oclif.io)
![npm](https://img.shields.io/npm/v/@vtex/cli-plugin-template)

<!-- toc -->
* [VTEX CLI Plugin URL](#vtex-cli-plugin-url)
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
# Usage
<!-- usage -->
```sh-session
$ npm install -g @vtex/cli-plugin-url
$ vtex COMMAND
running command...
$ vtex (-v|--version|version)
@vtex/cli-plugin-url/0.0.0 linux-x64 node-v12.19.0
$ vtex --help [COMMAND]
USAGE
  $ vtex COMMAND
...
```
<!-- usagestop -->
# Commands
<!-- commands -->
* [`vtex url`](#vtex-url)

## `vtex url`

Prints base URL for current account, workspace and environment

```
USAGE
  $ vtex url

OPTIONS
  -h, --help     show CLI help
  -v, --verbose  Show debug level logs
  --trace        Ensure all requests to VTEX IO are traced

EXAMPLE
  vtex url
```

_See code: [build/commands/url.ts](https://github.com/vtex/cli-plugin-url/blob/v0.0.0/build/commands/url.ts)_
<!-- commandsstop -->
