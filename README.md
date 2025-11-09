# Hi, I'm **byKenvi** 👋 / Salut, je suis **byKenvi** 👋

<p align="center">
  <!-- Banner image: place banner_byKenvi.png at the repo root as ./banner.png -->
  ![Banner](./banner.png)
</p>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=26&duration=3000&pause=700&color=8A2BE2&center=true&vCenter=true&width=800&height=50&lines=Full+Stack+Developer+%7C+Web+Architect+%7C+Problem+Solver;Perfectionist+about+Clean+Code+and+Automation" alt="Typing..."/>
</p>

---

## 🇫🇷 À propos / About me 🇬🇧

* Passionné par le **code propre**, les architectures modernes et l'automatisation. / Passionate about **clean code**, modern architectures and automation.
* J'aime concevoir des solutions élégantes, performantes et bien testées. / I design elegant, high-performance, well-tested solutions.
* Langues / Languages: **Français** · **Anglais**

---

## ⚒️ Compétences / Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat\&logo=python\&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat\&logo=javascript\&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat\&logo=typescript\&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat\&logo=angular\&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat\&logo=react\&logoColor=61DAFB)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=flat\&logo=laravel\&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat\&logo=django\&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-43853D?style=flat\&logo=node.js\&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat\&logo=docker\&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-38B2AC?style=flat\&logo=tailwindcss\&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat\&logo=mysql\&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat\&logo=postgresql\&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat\&logo=firebase\&logoColor=black)

---

## 📫 Contact

* Email: **[lihounhintoe@gmail.com](mailto:lihounhintoe@gmail.com)**
* LinkedIn: [open profile](https://www.linkedin.com)

---

## 📈 Stats & Visuals

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=byKenvi&show_icons=true&theme=tokyonight&hide_border=true" alt="GitHub stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=byKenvi&layout=compact&theme=tokyonight&hide_border=true" alt="Top languages"/>
</p>

<p align="center">
  <img src="https://activity-graph.herokuapp.com/graph?username=byKenvi&theme=react-dark&area=true&hide_border=true" alt="Contributions graph" />
</p>

> **Nota / Note:** Si les visuels ne s'affichent pas immédiatement, vérifie que le nom d'utilisateur dans les URLs (`byKenvi`) correspond bien à ton pseudo GitHub.

---

## 🔧 Principes de travail / Work Principles

* Clean code, tests, PRs soignés. / Clean code, tests, tidy PRs.
* Automatisation progressive: CI/CD, linting, tests unitaires et e2e.
* Documentation : README concis + exemples.

---

## 🧩 Enigmes & Challenges / Puzzles (révèle la réponse en cliquant)

### 1) Dev Puzzle / Énigme dev

**Q:** What value will `result` hold after this snippet? / Quelle valeur `result` contiendra après ceci?

```javascript
const arr = [1, 2, 3];
const result = arr.map(x => x * 2).filter(x => x > 3).reduce((s, v) => s + v, 0);
console.log(result);
```

<details>
  <summary>Answer / Réponse</summary>
  - Steps / Étapes : map → [2,4,6] ; filter x>3 → [4,6] ; reduce → 10. So `result` is **10**.
</details>

---

### 2) Logic Puzzle / Puzzle logique

**Q:** Je pense à un nombre. Multiplié par 3, puis on ajoute 6, on obtient 21. Quel est le nombre ? / I think of a number. Multiply by 3, add 6, you get 21. What is it?

<details>
  <summary>Answer / Réponse</summary>
  (21 - 6) / 3 = 5 → **5**.
</details>

---

### 3) Bonus: Mini-challenge (à cloner) / Mini challenge

Un petit challenge que tu peux héberger dans un dossier `challenge/` du repo.

**But / Goal (FR / EN)**

* Écrire une petite CLI Node.js qui lit un fichier JSON de tâches (todos), filtre celles due aujourd'hui, et affiche un résumé : nombre total, nombre terminé, et une liste triée par priorité.
* Build a small Node.js CLI that reads a JSON todo file, filters tasks due today, and prints a summary: total count, completed count, and a list sorted by priority.

**Structure suggérée / Suggested structure**

```
challenge/
├─ README.md       # instructions & tests
├─ sample_todos.json
├─ index.js         # CLI entry (ex: node index.js todos.json)
├─ package.json
└─ tests/
   └─ test_cli.js   # basic tests using node assert
```

**Exemples d'API & commandes**

* `node index.js sample_todos.json` → affiche le résumé
* `npm test` → exécute les tests

<details>
  <summary>Contenu exemple pour `sample_todos.json`</summary>

```json
[
  {"id":1,"title":"Deploy API","due":"2025-11-09","priority":2,"done":false},
  {"id":2,"title":"Fix bug #342","due":"2025-11-09","priority":1,"done":true},
  {"id":3,"title":"Write README","due":"2025-11-10","priority":3,"done":false}
]
```

</details>

<details>
  <summary>Contenu exemple pour `index.js` (squelette)</summary>

```javascript
// Usage: node index.js sample_todos.json
const fs = require('fs');
const path = require('path');

function isToday(dateStr){
  const d = new Date(dateStr);
  const today = new Date();
  return d.getFullYear()===today.getFullYear() && d.getMonth()===today.getMonth() && d.getDate()===today.getDate();
}

const file = process.argv[2];
if(!file){ console.error('Usage: node index.js <todos.json>'); process.exit(1); }

const todos = JSON.parse(fs.readFileSync(path.resolve(file), 'utf8'));
const todayTodos = todos.filter(t => isToday(t.due));
const total = todayTodos.length;
const done = todayTodos.filter(t => t.done).length;
const list = todayTodos.sort((a,b)=>a.priority - b.priority);

console.log(`Today: ${total} tasks (${done} done)`);
list.forEach(t=> console.log(`- [${t.done? 'x':' '}] (p${t.priority}) ${t.title}`));
```

</details>

---

## 🔮 Extras (animations & astuces)

* *Typing SVG* en haut : l'URL pointe vers un service public qui génère une animation SVG. Tu peux modifier le texte en changeant `lines=` dans l'URL.
* *Activity graph* & *stats* viennent de services gratuits (activity-graph, github-readme-stats). Si tu veux d'autres thèmes ou styles, je peux les ajuster.

---

## ✅ How to use / Comment l'utiliser

1. Crée un repo GitHub nommé exactement **`byKenvi`**.
2. Place `banner_byKenvi.png` (fichier que je t'ai fourni) à la racine et renomme-le `banner.png`.
3. Crée un dossier `challenge/` et colle la structure suggérée (README.md, sample_todos.json, index.js, package.json, tests/).
4. Colle ce README.md dans la racine du repo et push.

---

<p align="center">Made with ❤️ · Contribuer proprement · / Crafted with ❤️ · Clean contributions</p>
