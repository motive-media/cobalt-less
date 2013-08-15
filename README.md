# Install via Bower

    bower install cobalt-less

# Include in your project
Locate the vendor folder ```cobalt-less``` where ever you set your bower path to.

Inside your projects less file ```@import``` the ```cobalt.less``` file and that is it.

### Example
```css
@import "../vendor/cobalt-less/cobalt.less";

/* start your less here */
```

# Documentation

## Animate.less

### Transition
```css
.transition(@transition);
```

## Border_Radius.less

### Border Radius
```css
.border-radius(@radius);
```

### Background Clip
```css
.clip-radius();
```

## Gradient.less

### Gradient
```css
.gradient(@bg: #efefef, @start: #ffffff, @stop: #eeeeee);
```

### Linear Gradient
```css
.linear-gradient(@start: #ffffff, @stop: #eeeeee);
```
### Transparent Background Color
```css
.transparent-background-color(@color);
```
