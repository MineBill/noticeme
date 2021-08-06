# Usage

NoticeMe can be used with event or exports, both are available
```lua
TriggerEvent("noticeme:Notify", "Hello, World!")
-- or
exports.noticeme:Notify("Hello, World")
```

## Available functions
| Name | Description | Parameters |
| ---- | ----------- | ---------- |
| `Notify` | Default | `message/options`: If the argument is of type string then it will be the message printed. Alternatively a table can be used to specify [options](#options) |
| `Info` | Alias for `Notify` with set options | `message`: The message to print |
| `Warning`| Alias for `Notify` with set options | `message`: The message to print |
| `Error` | Alias for `Notify` with set options | `message`: The message to print |

## Options
| Name | Type | Description |
| ---- | ---- | ----------- |
| `message` | string | The message to print |
| `timeout` | integer | How long(ms) the notification should be visible for |
| `type` | string | The type of the notification |
| `audio` | boolean | Whether to play audio or not |
| `image` | string | A base64 encoded image to display instead of icons |

### Default options
| Name | Default |
| ---- | ------- |
|`message` | `"Null Content"` |
|`timeout` | `2000` for Info, `2500` for Warning, `3000` for Error |
|`type` | `"info"` for Info, `"warn"` for Warning, `"error"` for Error |
|`audio` | `false` for Notify, `true` for the Aliases |
|`image` | `null` |
