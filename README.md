# vscode-snippets
vscode 代码片段

```js
{
  // Place your 全局 snippets here. Each snippet is defined under a snippet name and has a scope, prefix, body and
  // description. Add comma separated ids of the languages where the snippet is applicable in the scope field. If scope
  // is left empty or omitted, the snippet gets applied to all languages. The prefix is what is
  // used to trigger the snippet and the body will be expanded and inserted. Possible variables are:
  // $1, $2 for tab stops, $0 for the final cursor position, and ${1:label}, ${2:another} for placeholders.
  // Placeholders with the same ids are connected.
  // Example:
  // "Print to console": {
  // 	"scope": "javascript,typescript",
  // 	"prefix": "log",
  // 	"body": [
  // 		"console.log('$1');",
  // 		"$2"
  // 	],
  // 	"description": "Log output to console"
  // }
  "💡 Daotin async funtion ": {
    "prefix": "asy",
    "body": [
      "async function ${1:xxx}() {",
      "  try {",
      "    const params = {}",
      "    const res = await apis.${2:xxx.xxx}(params)",
      "    message.msgSuccess(t('page.common.msgSuccess'))",
      "  } catch (error) {",
      "    console.error(error)",
      "  }",
      "}"
    ],
    "description": "💡 Daotin async funtion "
  },
  "💡 Daotin try": {
    "prefix": "try",
    "body": ["try {", "  ${0}", "} catch (error) {", "  console.error(error)", "} finally {", "}"],
    "description": "💡 Daotin try"
  },
  "💡 Daotin todo": {
    "prefix": "todo",
    "body": ["TODO daotin 翻译"],
    "description": "Daotin todo"
  },
  "💡 Daotin template": {
    "prefix": "temp",
    "body": ["<template ${0}></template>"],
    "description": "Daotin template"
  }
}

```
