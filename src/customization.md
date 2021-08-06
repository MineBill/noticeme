# Customization
Currently there aren't any variables to quickly configure the resource but it's planned. Here you can find some tips on how to manually customize the resource.

### Offset from the top
To change the offset from the top of the screen you need to modify line 17 of `ui.js`

### More notification types
To add your own notification types you need to:
- Create css class and modify any css attributes you want:
```css
.notification.--myType {
    border-left: 5px solid blue;
}
```
- Add an icon for this class in the `icons` dictionary in `ui.js`
- Add a title for this class in the `titles` dictionary in `ui.js`
- Add a sound file in the sounds directory (or copy-paste the existing sound and rename it to match your class name)