Base Atomic CSS     
=============================

This is the start of the Base Atomic CSS for rapid prototyping 

## Flexbox 

```
.flex{
    diisplay: flex; 
}
```


```javascript
var deploy = require("gulp-gh-pages");

gulp.task("deploy", ["jekyll-build"], function () {
    return gulp.src("./_site/**/*")
        .pipe(deploy());
});
```
