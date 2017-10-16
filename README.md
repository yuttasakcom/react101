## React Manual
> คู่มือการใช้งาน React ฉบับ YoProgrammer

## Table of Contents
- [JSX](#jsx)

## JSX
> Javascript XML

index.html
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <title>Document</title>
</head>
<body>
  <div id="app"></div>
  <script src="https://unpkg.com/react@16.0.0/umd/react.development.js"></script>
  <script src="https://unpkg.com/react-dom@16.0.0/umd/react-dom.development.js"></script>
  <script src="/scripts/app.js"></script>
</body>
</html>
```

app.js
```javascript
var template = React.createElement(
  "p",
  null,
  "Hello JSX!"
);

ReactDOM.render(template, document.getElementById('app'));
```