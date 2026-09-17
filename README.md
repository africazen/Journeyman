# StanPan Collection

A growing digital catalogue of African ritual, ceremonial, and cultural artefacts.  
Each artefact is documented in its own Markdown file and paired with one or more images stored in the repository.  
This project aims to create a clear, structured, and accessible archive of objects collected across regions, cultures, and traditions.

---

## 📁 Repository Structure

/artefacts        → Markdown files for each artefact
/images           → Images associated with each artefact
README.md         → Project overview

Example:
/artefacts
MAK026.md
/images
MAK026-front.jpeg


---

## 🔢 Artefact Naming Conventions

Each artefact uses a **unique catalogue ID**, which also becomes the filename for both the Markdown file and its images.

### **Markdown File**
MAK026.md

### **Image Files**
MAK026-front.jpeg
MAK026-side.jpeg
MAK026-detail.jpeg


This keeps the repository consistent and makes linking images simple.

---

## 🖼️ Referencing Images in Markdown

Images are referenced using **relative paths**, ensuring they work directly inside GitHub:

```markdown
<img src="images/MAK026-front.jpeg" width="300">

Additional images can be listed as:
- images/MAK026-side.jpeg
- images/MAK026-detail.jpeg
