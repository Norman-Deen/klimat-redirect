# 🔁 Klimat Redirect

This is a minimal static redirect page for the **Klimat** project.

Visitors who land on this domain are automatically redirected to the official Wix website.

---

## 🌐 Purpose

To handle domain-level redirection using a static `index.html` hosted via GitHub Pages.

---

## 📁 Files

- `index.html` – Contains the redirect logic using JavaScript.
- `CNAME` – Sets the custom domain for GitHub Pages.
- `.nojekyll` – Prevents GitHub Pages from processing the site with Jekyll.

---

## 🚀 How it Works

The `index.html` file includes a JavaScript snippet that instantly redirects users to the target site:

```html
<script>
  window.location.href = "https://your-wix-site.com";
</script>
````

Once deployed, the page forwards all traffic to the designated Wix address.

---

## 👨‍💻 Maintained by

[Nour Altinawi](https://www.linkedin.com/in/nour-tinawi)

