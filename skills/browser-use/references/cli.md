# browser-use CLI cheat sheet

## Install / setup

- `browser-use doctor`
- `browser-use setup`
- `browser-use install` (install Chromium)

## Navigation / tabs

- `browser-use open <url>`
- `browser-use back`
- `browser-use scroll down|up [--amount N]`
- `browser-use switch <tab>`
- `browser-use close-tab [<tab>]`

## Inspection / screenshots

- `browser-use state`
- `browser-use screenshot [path]`
- `browser-use screenshot --full path.png`

## Interactions

- `browser-use click <index>`
- `browser-use input <index> "text"`
- `browser-use type "text"`
- `browser-use keys "Enter"`
- `browser-use select <index> "option"`
- `browser-use hover <index>`

## Data / JS

- `browser-use get title`
- `browser-use get text <index>`
- `browser-use get html [--selector "h1"]`
- `browser-use eval "document.title"`

## Wait

- `browser-use wait selector "css"`
- `browser-use wait text "Success"`

## Session

- `browser-use sessions`
- `browser-use close`
- `browser-use close --all`
