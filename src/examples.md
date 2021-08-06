# Examples

## Notify
```lua
TriggerEvent("noticeme:Notify", {
    message = "Hello, World!",
    timeout = 2000, -- 2 seconds
    audio = true, -- use notification sound
    type = "info", -- use the info colors and icons
})
```

## Notify with Image
```lua
TriggerEvent("noticeme:Notify", {
    message = "Hello, World!",
    timeout = 2000, -- 2 seconds
    audio = true, -- use notification sound
    type = "info", -- use the info colors and icons
    image = "data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACAAAAAgCAYAAABzenr0AAAA1UlEQVRYhc3WzQmEMBCGYau1hq3EMgQPe9EuAlvAVKKngCuZSb7xG6OQgxjzPv4gDgO4fb6/3RroepRoGMYbpkBYcReCHYcQUfEmRHTcRDwVVxFdAdok1lZFlA6KJBpAJPkADEReRwVotyefKJL2bZ3h8LbOf2uoj6EFgCKucQqgFVGK0wAWRAuHAc6IvB8OuEZK4bBHULvC2txbACSunWN+DdF3wDPcX8JugHFaaPFxWmyAhWCMarz7/8ArfsmeQpjxaERTPAoBxdkIV5wBuR32YND1DugxOcv5aT0MAAAAAElFTkSuQmCC",
})
```

## Info
```lua
TriggerEvent("noticeme:Info", "Info notification!")
```

## Warning
```lua
TriggerEvent("noticeme:Warning", "Warning notification")
```

## Error
```lua
TriggerEvent("noticeme:Error", "Error notification")
```
