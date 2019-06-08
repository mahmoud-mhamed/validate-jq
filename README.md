# validate jq

validate inputs by jq

## Getting Started



### Prerequisites

jQuery library


### Installing
```
<link rel="stylesheet" href="validate.css">
<script src='validate.js'></script>
```

## Running the tests
```html
<form action="">
    <input type="text" data-validate="gt:33" data-patternType="gt" required>
    <input type="text" required id="two">
    <br>
    <button type="submits">submit</button>
</form>
```
```javascript
validateByAttr();
```

```javascript
$('#one').keyup(function () {
        validate($('#one'),'gt:22');
    });
    $('#two').keyup(function () {
        validate($('#two'),'lt:22');
    });
```

## Authors

* **Mahmoud Mohamed** - [github](https://github.com/mahmoud-mhamed)

Find me in [facebock](https://www.facebook.com/profile.php?id=100009734383434) who participated in this project.



