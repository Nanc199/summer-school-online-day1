
---

## summer-school-online-day1

### 🏠 `portfolio.html`
- Homepage showcasing:
  - Skills (`<ul>`)
  - Education (`<ol>`)
  - Image (`<img>`)
  - Experience in table format (`<table>`)

### 🙋‍♂️ `about.html`
- Brief personal introduction
- Internal links to `portfolio.html` and `contact.html`
- External links (e.g. [LinkedIn](https://www.linkedin.com)) using `target="_blank"`

### 📬 `contact.html`
- Contact form featuring:
  - `text`, `email`, `tel`, `date`, `radio`, `checkbox`, `range`, `textarea`, and `select`
  - HTML5 validation using `required` and `pattern` attributes

---

## 💡 Key HTML Elements Used

| Element | Purpose |
|--------|---------|
| `<!DOCTYPE html>` | Declares HTML5 document |
| `<html>` | Root of the page |
| `<head>`, `<body>` | Meta and visible content |
| `<header>`, `<nav>`, `<main>`, `<section>`, `<footer>` | Semantic layout |
| `<a href="">` | Navigation and external links |
| `<ul>`, `<ol>`, `<li>` | Lists for skills/education |
| `<table>` | Display experience in tabular format |
| `<form>`, `<input>`, `<select>`, `<textarea>` | Contact form inputs |

---

## 🧾 Why These Input Types?

| Input Type | Use |
|------------|-----|
| `text` | For name |
| `email` | Validates email format |
| `tel` + `pattern="[0-9]{10}"` | Enforces 10-digit number |
| `date` | Easy date of birth selection |
| `radio` | Choose one inquiry type |
| `checkbox` | Select multiple contact methods |
| `select` | Choose from predefined options |
| `range` | Interactive urgency scale |
| `textarea` | Longer messages |
| `required` | Ensures required fields are filled |

---

## 🔗 Navigation

- Consistent `<nav>` in the `<header>` on all pages.
- Links to:
  - Home → `portfolio.html`
  - About → `about.html`
  - Contact → `contact.html`
- External links open in a **new tab** using `target="_blank"`.

---

## 🚀 How to Run

1. **Clone or Download** the repository:
```bash
git clone https://github.com/your-username/summer-school-portfolio.git
