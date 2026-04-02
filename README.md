# Akhila Karnataka Kuvempu Samskrutika Vedike (R) – Official Website


Official static website for **Akhila Karnataka Kuvempu Samskrutika Vedike (R)** – a registered cultural organisation working for the promotion of Kannada language, literature, and social welfare, inspired by the vision of Rashtrakavi Kuvempu.

🔗 **Live site:** https://akksv.vercel.app



## 📌 About the Organisation

- **Founded:** 2011
- **Registration No:** 447/2011-12
- **Certifications:** 80G, CSR Eligible
- **Headquarters:** Vijayanagar, Bengaluru – 560 040
- **Key Activities:**  
  - Kannada Nudi Sammelana (state‑level literary conference)  
  - Jeevanmuki Awards for literature & social service  
  - Education support for government school students  
  - 'Jeevanmuki' fortnightly magazine (15+ years)  
  - Environment & healthcare initiatives  

This website serves as a digital presence for the Vedike, enabling people to learn about our work, get involved, donate via CSR/80G, and contact us easily.



## 🛠️ Tech Stack

- **HTML5** / **CSS3** – responsive, modern design  
- **JavaScript** – scroll animations, language toggle (English/Kannada)  
- **Formspree** – handles contact form submissions without a backend  
- **GitHub** – version control  
- **Vercel** – static hosting  



## 📧 Form Submissions

The contact form at the bottom of the page sends submissions to **Formspree**.  
To make it work with your own email:

1. Sign up at [formspree.io](https://formspree.io)  
2. Create a new form and copy your unique endpoint URL (e.g., `https://formspree.io/f/xyzabcde`)  
3. Replace `YOUR_FORM_ID` in the `<form>` tag inside `index.html`:  
   ```html
   <form id="cform" action="https://formspree.io/f/xyzabcde" method="POST">