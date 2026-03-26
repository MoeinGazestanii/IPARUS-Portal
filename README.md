# PROTOTYPE UPARUS: Genomic Resources for the Parus Genus 🧬🐦

[![Website Status](https://img.shields.io/badge/Website-Live-brightgreen.svg)](https://moeingazestanii.github.io/IPARUS-Portal/) [![Maintained by](https://img.shields.io/badge/Maintained%20by-Gossmann%20Lab-blue.svg)](https://csb.bci.tu-dortmund.de/)

## 📌 Overview
This repository hosts the source code and static web pages for the **IPARUS (Integrated Platform for Parus Alignments, Resources and Useful Sequences)** project. The platform provides public access to genomic resources and metadata of birds from the *Parus* genus (most notably the great tit, *Parus major*). 

The goal of this project is to provide a database of sequence data and corresponding metadata to facilitate collaboration between researchers and provide public access to these datasets.

🌐 **Live Website:** [Click here to visit the IPARUS Portal](https://moeingazestanii.github.io/IPARUS-Portal/)

---

## ✨ Features
This web portal is designed as an interactive, static single-page application (SPA) featuring:
- **📍 Interactive Geographic Map:** Built with Plotly, visualizing sampling locations. Users can click on any location to dynamically filter the sequence data.
- **📊 Sequence Data Table:** A searchable and sortable database of samples, including MD5 checksums for data validation.
- **🔗 Direct Sciebo Integration:** Secure and direct download links routing users to the Sciebo cloud storage.
- **📄 Comprehensive Metadata:** Detailed information regarding sample collection and processing.
- **📚 Publications:** A curated list of related research papers and scientific publications with direct DOI links.

---

## 🛠️ Built With
The portal is purely static and hosted on **GitHub Pages**, ensuring fast loading times and zero server maintenance.
- **Frontend:** HTML5, CSS3 (Modern UI/UX with Inter font), JavaScript (DataTables for smart searching and filtering).
- **Data Processing (Backend preparation):** Python, Pandas, and Plotly were used to process the `.xlsx` metadata, generate MD5 checksums, and export the interactive HTML map and tables.

---

## 👨‍🔬 Team & Contact Information
The IPARUS database and this website are maintained by the **Gossmann lab** at **TU Dortmund University**.

- **Primary Contact:** Dr. Nikolas Vellnow 
- **Database & Web Development:** Mohammadmoein Hajihoseinigazestani (Moein Gazestani) 

**Institution:**
> Laboratory of Computational Systems Biology <br>
> Faculty of Biochemical and Chemical Engineering <br>
> Technical University Dortmund <br>
> Emil-Figge-Str. 66, 44227 Dortmund, Germany

