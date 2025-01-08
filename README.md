# Travaux_BootcampPythonAdacorp2024
Repo pour les différents travaux liés à la formation de développeur fullstack python Adacorp 2024
---

## **Tuto : Comment utiliser le dépôt GitHub partagé**

### **1. Préparer l'environnement**
- Assurez-vous que Git est installé sur votre ordinateur. Si ce n’est pas encore fait, téléchargez et installez-le depuis [Git](https://git-scm.com/).
- Configurez Git avec vos informations :
  ```bash
  git config --global user.name "VotreNom"
  git config --global user.email "VotreEmail@example.com"
  ```

---

### **2. Cloner le dépôt partagé**
1. Ouvrez un terminal ou l’invite de commandes.
2. Tapez la commande suivante pour cloner le dépôt sur votre machine locale :
   ```bash
   git clone https://github.com/votre-utilisateur/votre-repo
   ```
3. Accédez au répertoire cloné :
   ```bash
   cd votre-repo
   ```

---

### **3. Créer un dossier à votre nom**
1. Dans le répertoire cloné, créez un nouveau dossier portant votre nom (par exemple, `Etudiant1`) :
   ```bash
   mkdir Etudiant1
   ```
2. Ajoutez vos travaux dans ce dossier :
   - Copiez/collez vos fichiers dans le dossier `Etudiant1`.
   - Vous pouvez ajouter plusieurs fichiers (par exemple, `mon-projet.py`, `rapport.pdf`, etc.).

---

### **4. Ajouter et envoyer vos modifications au dépôt**
1. Vérifiez l’état des fichiers :
   ```bash
   git status
   ```
2. Ajoutez les fichiers modifiés ou créés :
   ```bash
   git add .
   ```
3. Enregistrez vos modifications avec un message clair :
   ```bash
   git commit -m "Ajout des travaux de Etudiant1"
   ```
4. Envoyez vos modifications sur le dépôt distant :
   ```bash
   git push origin main
   ```

---

### **5. Ajouter de nouveaux travaux**
Lorsque vous avez de nouveaux travaux à déposer :
1. Ajoutez-les dans votre dossier existant (par exemple, `Etudiant1`).
2. Répétez les étapes :
   - `git add .`
   - `git commit -m "Ajout de nouveaux travaux"`
   - `git push origin main`

---

### **6. Récupérer les dernières mises à jour du dépôt**
Pour vous assurer que vous avez les dernières modifications avant de travailler :
1. Téléchargez les mises à jour du dépôt :
   ```bash
   git pull origin main
   ```
2. Résolvez les conflits s'il y en a (Git vous guidera si cela se produit).

---

### **7. Conseils importants**
- **Toujours tirer les dernières modifications avant de travailler :**
  ```bash
  git pull origin main
  ```
- **Travaillez uniquement dans votre propre dossier** pour éviter d’écraser ou de modifier accidentellement les travaux des autres.
- Si vous supprimez ou déplacez un fichier, assurez-vous que c'est uniquement dans votre dossier.

---

### **Résumé des commandes**
Voici un récapitulatif des commandes Git les plus importantes :
| **Action**                              | **Commande**                          |
|-----------------------------------------|---------------------------------------|
| Cloner le dépôt                         | `git clone <URL>`                     |
| Ajouter un fichier                      | `git add <nom-du-fichier>`            |
| Ajouter tous les fichiers               | `git add .`                           |
| Enregistrer les modifications           | `git commit -m "Message clair"`       |
| Envoyer les modifications au dépôt      | `git push origin main`                |
| Récupérer les dernières mises à jour    | `git pull origin main`                |
| Vérifier l’état des fichiers            | `git status`                          |

---

### **Exemple complet**
Imaginons que votre nom est **Etudiant1** :
1. Cloner le dépôt :
   ```bash
   git clone https://github.com/votre-utilisateur/votre-repo
   cd votre-repo
   ```
2. Créer un dossier :
   ```bash
   mkdir Etudiant1
   ```
3. Ajouter un fichier :
   ```bash
   echo "Mon premier fichier" > Etudiant1/fichier1.txt
   ```
4. Ajouter, committer et pousser :
   ```bash
   git add .
   git commit -m "Ajout du fichier fichier1.txt pour Etudiant1"
   git push origin main
   ```
5. Récupérer les mises à jour :
   ```bash
   git pull origin main
   ```

---
