# Bootstrap-Project2
# The News | Bootstrap 5 Project

A responsive news website project built with **HTML**, **CSS**, and **Bootstrap 5**.

---
### Preview
![preview](https://raw.githubusercontent.com/shirinmohajeri/Car-Exhibition-Luxury-Automotive-Showcase/refs/heads/main/picture1.jpg)
---

## 📌 About The Project

This project is a Bootstrap 5 news-style webpage.

It includes:

- Responsive navbar
- Hero section
- News headline cards
- Featured story section
- Subscribe form
- Footer

The goal of this project is to practice Bootstrap components and responsive layout design.

---

## 🛠 Technologies Used

- HTML5
- CSS3
- Bootstrap 5.3.8

---

## 📚 Bootstrap Features Used

### Navbar

The project uses a responsive Bootstrap navbar:

```html
navbar
navbar-expand-lg
navbar-light
bg-light
navbar-toggler
collapse
```

---

### Hero Section

The hero section includes:

```html
display-5
fw-bold
lead
btn
btn-danger
```

It is styled with a background image and dark overlay using CSS.

---

### Cards

The headline section uses Bootstrap cards:

```html
card
card-img-top
card-body
card-title
card-text
shadow-sm
h-100
```

Cards are used to display news articles.

---

### Grid System

The project uses Bootstrap grid classes:

```html
container
row
col-lg-4
col-md-6
col-12
g-4
```

Meaning:

- `col-lg-4` → 3 cards per row on large screens
- `col-md-6` → 2 cards per row on medium screens
- `col-12` → 1 card per row on small screens
- `g-4` → spacing between cards

---

### Buttons

Buttons used in the project:

```html
btn
btn-danger
btn-outline-danger
btn-primary
btn-lg
w-100
```

---

### Images

Images are styled with:

```html
img-fluid
rounded
shadow
object-fit
```

---

### Subscribe Form

The subscribe section uses:

```html
input-group
form-control
btn
```

---

## 📁 Project Structure

```text
news-bootstrap-project/
│
├── index.html
├── style.css
└── README.md
```

---

## 🎯 What I Learned

In this project, I practiced:

- Creating a responsive navbar
- Using Bootstrap grid system
- Creating responsive cards
- Adding spacing between columns using `g-4`
- Creating a hero section
- Using Bootstrap buttons
- Styling images
- Creating a subscribe input group
- Writing custom CSS with Bootstrap

---

## ⚠️ Important Bootstrap 5 Notes

In Bootstrap 5, use:

```html
data-bs-toggle
data-bs-target
```

Example:

```html
<button 
  class="navbar-toggler"
  data-bs-toggle="collapse"
  data-bs-target="#newsMenu">
</button>
```

Do not use Bootstrap 4 syntax:

```html
data-toggle
data-target
```

---

## 🚀 How To Run The Project

1. Download or clone the project.
2. Open `index.html` in the browser.
3. Make sure `style.css` is in the same folder as `index.html`.

---

## 👩‍💻 Author

Created by **Shirin** as a Bootstrap 5 practice project.
