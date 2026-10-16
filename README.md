# Forms – Assignment 4

**Student:** Temirzakhov Adilzhan <br>
**Website:** https://tubular-treacle-dbf49f.netlify.app

## Description

A website with HTML forms, Bootstrap form components and form validation.
Built with HTML, CSS and Bootstrap 5. No JavaScript is used.

## Pages

| Page | File | Task |
|---|---|---|
| Contact | `index.html` | Task 1: simple contact form with HTML5 validation |
| Bootstrap Form | `bootstrap-form.html` | Task 2: contact form made with Bootstrap classes and grid |
| Validation | `validation.html` | Task 3: Bootstrap validation messages (valid and invalid) |
| Registration | `register.html` | Task 4: registration form with validation |

## What is used

- HTML5 validation: `required`, `minlength`, `maxlength`, `pattern`, `type="email"`
- Bootstrap 5 form classes: `form-control`, `form-label`, `form-text`, `form-select`, `form-check`
- Bootstrap grid (`row`, `col-md-6`, `col-12`) for a responsive layout
- Validation messages: "Looks good!" for valid fields and error text for invalid fields
- Navbar on every page

## Project structure

```
├── index.html
├── bootstrap-form.html
├── validation.html
├── register.html
├── styles.css
└── README.md
```

Internet is needed because Bootstrap is loaded from CDN.

## Note

The forms do not send data anywhere (`action="#"`), because this assignment has no server part.
