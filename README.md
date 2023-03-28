# Industrialisation du Logiciel

## TP2

### Exercice 1

Les réponses sont basées sur : https://docs.github.com/fr/actions/learn-github-actions/understanding-github-actions

**Quelles étapes sont réalisées par cette action ?**

* *Set up Python 3.10*
* *Install dependencies*
* *Lint with flake8*
* *Test with pytest*

**Une étape est définie au minimum par 2 paramètres, lesquels sont-ils et à quoi servent-ils ?**

* Son nom (paramètre `name`)
* `run` qui contient la ou les commandes à exécuter

**La première étape contient un paramètre ‘with’, a quoi sert-il ?**

A préciser la version à utiliser (ici celle de python)


### Exercice 2

**Sur l’onglet Summary d’une analyse de code, SonarCloud fournit 4 indicateurs. Quels sont-ils et quelles sont leurs utilités ?**

- Bugs,
- Code Smells,
- Vulnerabilities,
- Security Hotspots

**À quoi sert l’indicateur Quality Gate ?**

A Quality Gate is a set of measure-based Boolean conditions. It helps you know immediately whether your project is production-ready. If your current status is not Passed, you'll see which measures caused the problem and the values required to pass.


