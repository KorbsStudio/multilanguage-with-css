# i18n with CSS
This example shows how to change to a different language easily and also saving it like a setting (`localStorage.getItem`). The script that saves the settting is thanks to [Divano's light and dark mode](https://github.com/divanov11/light-dark-mode/blob/master/index.html#L28) repo.

As for the CSS files, this uses `<span>` and the id set to the text that'll be used on your website/app. CSS will add text by using `content: ""` with `::before`.

Example:
HTML
```html
<span id="welcome-home"></span>
```

CSS
```css
span#welcome-home::before {content: "Welcome Home!"}
```
