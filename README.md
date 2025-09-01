# Semantic vs Non-Semantic HTML

## 1. What is Semantic HTML?
**Semantic HTML** uses elements that have a clear, meaningful purpose.  
These tags describe the role of the content inside them, making it easier for **browsers, developers, and assistive technologies (like screen readers)** to understand the structure of the page.

**Examples:**
- `<header>` → Represents the top section of a page or article.  
- `<nav>` → Defines navigation links.  
- `<main>` → The main content of the document.  
- `<article>` → Independent, self-contained content (e.g., a blog post).  
- `<section>` → Groups related content under a common theme.  
- `<footer>` → Represents the bottom section of a page or article.  

**Advantages of Semantic HTML**:
- Improves accessibility for screen readers.  
- Better SEO (search engines understand content meaning).  
- Cleaner, more organized code.  
- Easier to maintain.  

---

**2. What is Non-Semantic HTML?**
**Non-semantic HTML** uses generic elements that **do not convey meaning** about their content.  
The most common non-semantic tags are:  
- `<div>` → A generic container.  
- `<span>` → A generic inline container.  

These tags rely heavily on **classes, IDs, or ARIA attributes** to provide meaning.  

 **Example:**
```html
<div class="top">
  <div class="logo">MySite</div>
  <div class="links">
    <a href="/">Home</a>
    <a href="/about">About</a>
  </div>
</div>
