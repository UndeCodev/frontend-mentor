Hey Henry 👋! Great job on the Four Card section - the layout looks clean and your use of CSS Grid is solid! I found just a few small areas where we can make it even better.

#### **Quick Suggestions for Improvement:**

**1. Minor HTML Tweaks:**
```html
<!-- Add a main heading level -->
<header>
  <div class="wrapper wrapper--narrow"> <!-- Fix typo in class name -->
    <h1>Reliable, efficient delivery<br> <!-- Use <br> instead of span for line break -->
      <span>Powered by Technology</span>
    </h1>
```

**2. CSS Refinements:**
```css
/* Improve line-height consistency */
.card h2 { /* Specific selector for card titles */
  line-height: 1.2; /* Better than 0.3 */
  margin-bottom: 0.5rem;
}

.card p {
  line-height: 1.6;
}

/* Better image handling */
.card img {
  display: block; /* Remove float */
  margin-top: 2rem;
  margin-left: auto; /* Push to right */
}

/* Add mobile responsiveness */
@media (max-width: 894px) {
  .layout-grid {
    grid-template-columns: 1fr;
    max-width: 400px;
    margin-inline: auto;
  }
  
  .wrapper--narrow {
    width: 100%; /* Full width on mobile */
    max-width: 500px;
  }
}
```

**3. Accessibility Enhancement:**
```css
/* Ensure proper color contrast */
:root {
  --dark-grey: hsl(234, 12%, 25%); /* Slightly darker for better contrast */
}
```

Your code is already really good - these are just polish touches! The grid layout is particularly well-implemented. Keep up the great work! 🚀
