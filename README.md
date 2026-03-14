# POUI — Aromatherapy & Wellness Brand Concept

![Node.js](https://img.shields.io/badge/Node.js-Runtime-339933?logo=nodedotjs&logoColor=white) ![Vanilla JS](https://img.shields.io/badge/Vanilla_JS-Logic-F7DF1E?logo=javascript&logoColor=black) ![CSS3](https://img.shields.io/badge/CSS3-Styling-1572B6?logo=css3&logoColor=white) ![HTML5](https://img.shields.io/badge/HTML5-Structure-E34F26?logo=html5&logoColor=white)

Welcome to the repository for **POUI**, a web platform designed for an aromatherapy entrepreneur specializing in scented candles, diffusers, and wellness products.

This project focuses on creating a warm and elegant **User Experience (UX)** that reflects the brand's identity, highlighting artisanal quality and the sensory benefits of its products through a clean, sophisticated design.



## Features

* **Custom HTTP Server Architecture:** Manual route management developed from scratch using Node.js's native modules to ensure full control over the request-response cycle.
* **Dynamic Form Processing:** Advanced reading and processing of parameters sent via forms for seamless user interaction.
* **Robust Routing System:** Native implementation of specific and default routes for efficient navigation.
* **Intelligent Error Handling:** Custom responses for non-existent routes (404) and internal server issues (500) to maintain system stability.
* **Optimized Static Asset Streaming:** High-performance serving of HTML, CSS, images, and other static files without external frameworks.

## Tech Stack

* **Runtime Environment:** Node.js.
* **Core Native Modules:**
    * `http`: For server creation and request management.
    * `url`: For parsing and analyzing complex URL structures.
    * `fs`: For secure file reading and writing operations.
    * `path`: For cross-platform file path management.

---

## Project Structure

```bash
project-root/
├── server.js 
├── src/
    ├── app.js
    └── validar.js                
├── public/             
│   ├── index.html      
│   ├── catalogo.html   
│   ├── formulario.html 
│   ├── quienesomos.html 
│   ├── desc_product.html
│   ├── mensaje-enviado.html
│   ├── css/    
│   ├── js/    
│   ├── video/    
│   └── img/                        
```

---

## Installation and Usage

   ```bash
   git clone https://github.com/Pulpoide/aoi1_w2.git
   cd
   npm install
   node server.js
   ```

---

## Author

**Joaquín Olivero** ~ Software & AI Engineer

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/JoaquinOlivero)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Pulpoide)

