# Editings

A collection of setting & snippets that have come in handy.

## Sublime Text 3

#### Preferences > Settings - User
```json
{
  "margin": 0,
  "tab_size": 2,
  "translate_tabs_to_spaces": true,
  "highlight_line": true,
  "caret_extra_width": 1,
  "highlight_modified_tabs": true,
  "ignored_packages":
  [
    "Vintage"
  ]
}
```

#### Preferences > Key Bindings - User
```json
[
  { "keys": ["super+shift+up"], "command": "swap_line_up" },
  { "keys": ["super+shift+down"], "command": "swap_line_down" },
  { "keys": ["super+shift+d"], "command": "duplicate_line" }
]
```

#### Snippets
Snippets can be created easily enough with the template provided under the menu **Tools** > New Snippet...

##### ~/Library/Application Support/Sublime Text 3/Packages/User/console_log.sublime-snippet
```xml
<snippet>
  <content><![CDATA[
console.log('${1:var}', ${1:var});
]]></content> 
  <tabTrigger>cons</tabTrigger>
</snippet>
```

##### ~/Library/Application Support/Sublime Text 3/Packages/User/console_dir.sublime-snippet

```xml
<snippet>
  <content><![CDATA[
console.dir(${1:var});
]]></content> 
  <tabTrigger>cond</tabTrigger>
</snippet>
```
