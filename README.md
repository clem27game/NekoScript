# NekoScript Editor

**NekoScript** est un langage de programmation simplifié, visuel et fun, conçu pour permettre à tout le monde de créer facilement des **sites**, **chatbots**, **quizz**, **jeux** et **scripts interactifs**, sans avoir besoin de connaître HTML, CSS ou JavaScript.

Il s’utilise via un éditeur visuel moderne avec des fonctionnalités complètes : exécution en direct, console interactive, fenêtres dynamiques de test, et exportation multi-format (HTML, JSON, TXT).

---

## Fonctionnalités

- **Langage simplifié** : Syntaxe intuitive adaptée aux débutants.
- **Exécution directe** : Tester son script en un clic.
- **Console intelligente** : Affiche les messages, résultats ou réponses.
- **Création de chatbot** : Interaction dynamique via conditions.
- **Création de quiz** : Série de questions à choix multiples avec score.
- **Exportation HTML** : Générer un vrai site web statique.
- **Exportation JSON** : Utilisable avec des IA ou outils no-code.
- **Exportation TXT** : Pour stocker ou partager les scripts.

---

## Syntaxe NekoScript

### Afficher un message
```neko
neko = ("Bienvenue dans NekoScript !")
```

### Titre principal
```neko
<parnek>Mon premier titre<%parnek>
```

### Paragraphe
```neko
/page-neko>Voici un texte explicatif.\page-neko.
```

### Image
```neko
nekimg = ("https://exemple.com/image.jpg")
```

---

## Créer un Chatbot

```neko
mchatbot

Si neko = "bonjour"
réponse = "Salut ! Comment ça va ?"

Si neko contient "aide"
réponse.aléatoire = ["Tu peux poser une question.", "Je suis là pour t'aider."]
```

> L'exécution ouvre une fenêtre de chat où vous pouvez parler au bot.

---

## Créer un Quizz

```neko
jeuNeko = créer.quizz

quizz = "Quelle est la capitale de la France ?"
a. = "Lyon"
b. = "Paris"
c. = "Marseille"
réponse : bonne = "b"

quizz = "Combien de pattes a un chat ?"
a. = "2"
b. = "4"
c. = "6"
réponse : bonne = "b"
```

> L'exécution ouvre une interface interactive de quiz.

---

## Console

La console affiche les messages issus de `neko = ("...")`.

---

## Exports

### Export HTML
- Génère une version du script traduite en page web.
- Téléchargement direct via navigateur.

### Export JSON
```json
{
  "neko": "script original ici"
}
```
- Utilisable avec des **outils IA** ou **plateformes no-code**.

### Export TXT
- Sauvegarde brute du code source `.neko`.

---

## Utilisation de l’export JSON avec une IA

1. Exportez votre fichier au format `.json`.
2. Copiez le contenu du fichier.
3. Ouvrez un outil IA (comme ChatGPT, Claude, Poe…).
4. Dites :  
   **"Voici un script NekoScript en JSON. Peux-tu me créer un chatbot/quiz/HTML à partir de ce contenu ?"**
5. Collez le contenu JSON. L’IA pourra le convertir automatiquement.

---

## À venir

- possibilité de créer ses mini jeux en nekoScript 
- possibilité de créer d'autres types de bots en nekoScript 
- Partage public de scripts
- Modules personnalisés
- Thèmes graphiques pour quiz & chatbots
- et bien plus

---

## Éditeur et outils :
 [https://nekoscript.created.app/]

## agent nekoScript :
[https://app.relevanceai.com/agents/d7b62b/67ef8c14954b-41ea-bdea-ca720964a31c/e4b2f2fe-6723-407f-9b5d-ebdfccf96a70]
---

## Licence
© clem27games start 2025

MIT – Utilisation libre et open-source

---
