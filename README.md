# BEMHTML Language support for Visual Studio Code

![BEMHTML](icon.png)

![BEMHTML](https://img.shields.io/maintenance/no/2016.svg)

Adds BEMHTML syntax highlighting and snippets for Visual Studio Code.

Converted from: https://github.com/jchouse/bemhtml

## Snippets

block
    `b` -> `block blockName,`

block
    `b:` -> `block: 'blockName',`

elem
    `e` -> `elem elemName,`

elem
    `e:` -> `elem: 'elemName',`

block + elem
    `be` -> `block blockName, elem elemName,`

mod
    `m` -> `mod modName modValue,`

mods
    `m:` -> `mods: { modName: 'modValue' },`

elemMod
    `em` -> `elemMod modName modValue,`

elemMods
    `em:` -> `elemMods: { modName: 'modValue' },`

mix
    `mi:` -> `mix: [ { block: blockName } ]`

content
    `c:` -> `content: [ { ... } ]`

js
    `js:` -> `js: { ... }`

tag
    `t:` -> `tag: 'tagName',`

attrs
    `a:` -> `attrs: { ... }`

cls
    `cl:` -> `cls: 'className',`

bem: false
    `bf:` -> `bem: false`
