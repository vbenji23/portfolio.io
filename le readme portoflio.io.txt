# 💼 Portfolio.io

Bienvenue sur mon portfolio hébergé sur GitHub.  
Ce projet contient mes pages web personnelles et illustre mes compétences en développement.

---

## 🌐 Structure du projet

- `index.html` → page d’accueil  
- `apropos.html` → section À propos  
- `contact.html` → formulaire de contact  
- `projets.html` → liste de mes projets  
- `styles.css` → feuille de style principale  

---

## 🐍 Exemple Python

```python
class Projet:
    def __init__(self, titre, description, lien):
        self.titre = titre
        self.description = description
        self.lien = lien

    def afficher(self):
        print(f"📌 {self.titre}")
        print(f"   {self.description}")
        print(f"   🔗 {self.lien}\n")

projets = [
    Projet("Portfolio Web", "Site personnel en HTML/CSS/JS", "https://monportfolio.com"),
    Projet("API Python", "API REST avec Flask", "https://github.com/moi/api-python"),
    Projet("Application C", "Programme système en C", "https://github.com/moi/app-c")
]

for p in projets:
    p.afficher()
