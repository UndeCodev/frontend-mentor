Hey Katia! Great job on the Social Links Profile component! The design looks clean and your CSS skills are showing. I noticed a few areas where you could make your good code even better:

### 1. Use More Semantic HTML
Instead of generic `div` elements, consider using semantic tags:

```html
<!-- Instead of -->
<div class="card">
  
<!-- Try -->
<article class="card">
```

### 2. Target Elements by Class, Not Tag
This makes your CSS more maintainable:

```css
/* Instead of */
.links li { }

/* Try */
.links__item { }
```

### 3. More Descriptive CSS Custom Properties
Make your color variables more intuitive:

```css
:root {
  --accent-color: hsl(75, 94%, 57%);
  --background-dark: hsl(0, 0%, 8%);
  --card-background: hsl(0, 0%, 12%);
}
```

### 4. Consider BEM Methodology
This would help with organization:

```css
/* Block Element Modifier approach */
.card__info { }
.card__profile-pic { }
.card__link--hover { }
```

You can find more information about BEM right here: [BEM Methodology ](https://getbem.com/)


Your implementation is already solid - these tweaks would just take it to the next level! Keep up the great work! 🚀