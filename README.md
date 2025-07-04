

# MyPortfolio-Techmaestro

This is a simple portfolio website project created to demonstrate basic Git and GitHub workflows.

As the lead developer, the following steps were followed to set up and manage the project:

## 🧱 Project Setup Instructions

1. **Initialize a Git repository** in the project directory:
   git init

2. **Create the homepage (`index.html`)** and commit it:
   echo "<!DOCTYPE html><html><head><title>Home</title></head><body><h1>Welcome</h1></body></html>" > index.html  
   git add index.html  
   git commit -m "Add Homepage"

3. **Create and switch to a new branch named `contact-page`**:
   git checkout -b contact-page

4. **Create `contact.html` in the `contact-page` branch**:
   echo "<!DOCTYPE html><html><head><title>Contact</title></head><body><h1>Contact Me</h1></body></html>" > contact.html  
   git add contact.html  
   git commit -m "Add contact page"

5. **Switch back to the `main` branch** and merge the `contact-page`:
   git checkout main  
   git merge contact-page

6. **Create a `README.md` file** to document the project:
   touch README.md  
   (Enter the project documentation/instructions)  
   git add README.md  
   git commit -m "Add README file"

7. **Push the project to GitHub**:
   git remote add origin https://github.com/npelijah/MyPortfolio-Techmaestro.git  
   git push -u origin main

---

## 📁 Project Files

- `index.html` — Homepage
- `contact.html` — Contact page
- `README.md` — Project documentation

---

## 📌 Repository

https://github.com/npelijah/MyPortfolio-Techmaestro

---

## ✍ Author

Nkereuwem Peter Elijah

