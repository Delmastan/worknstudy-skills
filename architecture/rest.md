# REST API

> ❌ A travailler

> ✔️ Auto validation par l'étudiant

## 🎓 J'ai compris et je peux expliquer

- les verbes HTTP ✔️
- les statuts HTTP ✔️
- les endpoints ✔️
- CORS ✔️
- la nomenclature recommandée pour les routes ✔️

## 💻 J'utilise

### Un exemple personnel commenté ❌ / ✔️

Dans le manager

  <!-- async readByEmail(email) {
    const [rows] = await this.database.query(
      `select * from ${this.table} where email = ?`,
      [email]
    );

    return rows[0];
  } -->

Dans le controller

<!-- const readByEmailAndPassToNext = async (req, res, next) => {
  try {
    const user = await tables.user.readByEmail(req.body.email);

    if (user == null) {
      res.sendStatus(401);
    } else {
      req.user = user;
      next();
    }
  } catch (err) {
    next(err);
  }
}; -->

La route

<!-- router.post(
  "/users/login",
  userControllers.readByEmailAndPassToNext,
  verifyPassword
); -->

### Utilisation dans un projet ✔️

[lien github](https://github.com/WildCodeSchool/2023-09-JS-Toulouse-666-Street-Art-Hunter)

Description :

### Utilisation en production si applicable ✔️

[lien du projet](https://street-art-hunter.toulouse-1.wilders.dev/)

Description :

### Utilisation en environement professionnel ❌

## 🌐 J'utilise des ressources

### Titre

- lien
- description

## 🚧 Je franchis les obstacles

### Point de blocage ❌

## 📽️ J'en fais la démonstration

- J'ai ecrit un [tutoriel](...) ❌
- J'ai fait une [présentation](...) ❌
