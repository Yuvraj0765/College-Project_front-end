### 1. **Page Boilerplate**

- `<!DOCTYPE html>` → tells browser it’s HTML5
    
- `<html>`, `<head>`, `<body>` → skeleton of every page
    
- `<title>` → page title in browser tab
    
- `<meta charset="UTF-8">` → supports all characters
    
- `<meta name="viewport">` → makes it mobile-friendly
    

👉 Without this, your webpage may behave weird on different devices.

---

### 2. **Text Structure**

- `<h1>` → `<h6>` → Headings (big to small)
    
- `<p>` → Paragraphs
    
- `<br>` → Line breaks (use rarely, better to use `<p>`)
    
- `<hr>` → Horizontal divider line
    

👉 Needed to create readable content.

---

### 3. **Grouping & Layout**

- `<div>` → Generic container (always start with new line and take the full width available)
    
- `<span>` → Inline container (highlight small text parts)
    
- `<section>` → Big content block (like About, Services)
    
- `<article>` → Self-contained block (like a blog post)
    
- `<aside>` → Sidebar or extra info
    
- `<header>` → Top part of page/section (title, nav)
    
- `<footer>` → Bottom part (contact, copyright)
    
- `<main>` → Central content of the page
    
- `<nav>` → Menu/navigation links
    

👉 These are what make your site **scalable** — you can add as many sections, footers, and headers as you like.

---

### 4. **Lists & Navigation**

- `<ul>` → Unordered list (bullets)
    
- `<ol>` → Ordered list (numbers)
    
- `<li>` → List item
    
- `<a href="...">` → Link
    

👉 Lets you build menus, TOCs, sidebars, etc.

---

### 5. **Media**

- `<img src="...">` → Images
    
- `<video>` → Videos
    
- `<audio>` → Audio
    
- `<iframe>` → Embed external content (YouTube, maps)
    

---

### 6. **Tables (for data)**

- `<table>` → Table container
    
- `<tr>` → Table row
    
- `<td>` → Table cell
    
- `<th>` → Header cell
    

---

### 7. **Forms (for input)**

- `<form>` → Collects data
    
- `<input>` → Textbox, password, checkbox, radio, etc.
    
- `<textarea>` → Multi-line input
    
- `<button>` → Buttons
    
- `<label>` → Labels for input fields
    
- `<select>` + `<option>` → Dropdown menu
    

---

### 8. **Attributes you must know**

- `id="..."` → Unique name for an element
    
- `class="..."` → Group of elements (for styling later)
    
- `style="..."` → Quick inline styling (not recommended long-term)
    
- `alt="..."` → Text for images (important for accessibility)
    
- `target="_blank"` → Open links in new tab
    

---

### 9. **Extra helpers**

- `<!-- comment -->` → Notes inside code
    
- `<strong>` / `<em>` → Bold / Italic with meaning
    
- `<small>` / `<mark>` / `<sup>` / `<sub>` → Extra text formatting