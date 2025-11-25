---
marp: true
title: Product Documentation Presentation
author: Technical Writer
email: 25f1000165@ds.study.iitm.ac.in
theme: default
paginate: true
footer: "Contact: 25f1000165@ds.study.iitm.ac.in"
---

<style>
/* Custom theme: Solarized-inspired light theme */
@import url('https://fonts.googleapis.com/css2?family=Source+Sans+Pro:wght@400;600&display=swap');

section {
  font-family: 'Source Sans Pro', sans-serif;
  background: linear-gradient(135deg, #fdf6e3 0%, #eee8d5 100%);
  color: #586e75;
  justify-content: center;
  align-items: center;
}

h1, h2, h3 {
  color: #d33682;
  text-shadow: 1px 1px 2px rgba(0,0,0,0.1);
}

blockquote {
  border-left: 4px solid #268bd2;
  padding-left: 1em;
  font-style: italic;
  color: #2aa198;
}

pre {
  background: #eee8d5;
  border: 1px solid #93a1a1;
  border-radius: 4px;
}

code {
  background: #eee8d5;
  color: #dc322f;
  padding: 0.2em 0.4em;
  border-radius: 3px;
}
</style>

<!-- _class: lead -->

# Product Documentation Presentation

**Overview of Our Software Product**

- Maintainable in Git for version control
- Easily exportable to HTML, PDF, PPTX
- Built with Marp for simplicity

---
<!-- _backgroundColor: #fdf6e3 -->

## Introduction to the Product

Our software streamlines workflows for technical teams.

Key benefits:
- Scalable architecture
- Intuitive UI
- Robust API integration

![bg right:40%](https://via.placeholder.com/800x600/268bd2/ffffff?text=Product+Dashboard)

---
<!-- _class: lead -->
<!-- _backgroundImage: url('https://via.placeholder.com/1920x1080/eee8d5/586e75?text=Documentation+Background') -->
<!-- _backgroundSize: cover -->

# Core Features

This slide features a full background image for visual emphasis.

**Feature Highlights:**

| Feature | Description | Benefit |
|---------|-------------|---------|
| User Authentication | Secure login with OAuth | Enhanced security |
| Data Analytics | Real-time dashboards | Informed decisions |
| Collaboration Tools | Shared editing | Team efficiency |

---
## Algorithmic Complexity Analysis

Understanding performance is key for scalable documentation.

Inline math: The average case complexity is $O(n \log n)$.

Block equation for sorting algorithm (e.g., Merge Sort):

$$
T(n) = 
\begin{cases} 
\theta(1) & \text{if } n = 1 \\
2T\left(\frac{n}{2}\right) + \theta(n) & \text{otherwise}
\end{cases}
$$

This solves to $O(n \log n)$.

---
<!-- _color: #d33682 -->
<!-- _header: "Advanced Usage" -->

## Integration and Customization

**Custom Styling Example:** This slide uses a custom header and text color directive.

- Integrate with CI/CD pipelines for automated builds
- Use directives for dynamic styling
- Export scripts in `package.json` for format conversion

> "Documentation should evolve with the product." – Technical Writer

---
<!-- _footer: "© 2025 | 25f1000165@ds.study.iitm.ac.in" -->

# Conclusion

- Keep docs version-controlled
- Test exports regularly
- Use Marp for maintainable slides

Thank you!

Questions? Email: 25f1000165@ds.study.iitm.ac.in
