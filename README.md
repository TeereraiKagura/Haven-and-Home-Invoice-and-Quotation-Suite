# Haven-and-Home-Invoice-and-Quotation-Suite
A robust, offline-first web application designed to generate professional quotations and invoices instantly. Built as a single-file solution, it requires no backend or database, relying entirely on the browser for a fast and reliable experience.

✨ Key Features

100% Offline Capable (Auto-Save): Built to withstand power cuts and internet drops. Every keystroke is automatically saved to your browser's localStorage. If you close the tab, your data will still be there when you return.

Single File Architecture: All HTML, CSS (Tailwind), and JavaScript logic are bundled into one standalone index.html file for ultimate portability.

Custom Branding: Upload your company logo directly from your computer. The image is processed and saved locally without needing a server.

Multi-Currency & Tax Support: Easily toggle between currencies (USD, ZiG, ZAR) and adjust VAT percentages (defaults to Zimbabwe's standard 15.5%).

Print-to-PDF Optimized: Specially crafted CSS media queries ensure the user interface hides itself during printing, leaving only a perfectly formatted, professional A4 document.

Zero Setup: No npm install, no servers, no databases. Just double-click and run.

🚀 How to Use

Download or clone this repository to your local machine.

Open the index.html file in any modern web browser (Chrome, Edge, Safari, Firefox).

Customize your settings in the left sidebar (upload your Haven & Home logo, set the VAT, choose the currency).

Input client details and add your line items (e.g., Curtains, Rails, Installation).

Generate: Click the "Generate PDF / Print" button at the bottom of the sidebar to save the document as a PDF or print it directly.

🛠️ Built With

HTML5 - Semantic document structure.

JavaScript (Vanilla) - Controller logic and local state management.

Tailwind CSS - Utility-first styling (via CDN).

FontAwesome - UI Icons (via CDN).

💡 Architecture & SDLC Principles Applied

This application was designed with strict Software Development Life Cycle (SDLC) robustness and non-functional requirements in mind:

Reliability: Implements aggressive data persistence mechanisms using localStorage to prevent data loss.

Maintainability: JavaScript is structured cleanly, separating State/Data, Logic (Controller), and Rendering (View) for easier future updates.

Usability: Features non-blocking toast notifications and input validations to prevent empty or broken line items.

Developed for Haven & Home Interiors - Masvingo, Zimbabwe
