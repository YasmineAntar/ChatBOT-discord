# ChatBOT Discord avec OpenAI


### Installation

1. **Clonage du dépôt :** Clonez ce dépôt sur votre machine locale en utilisant la commande suivante :

    ```
    git clone <URL_DU_REPO>
    ```

2. **Installation des dépendances :** Naviguez vers le répertoire du projet et installez les dépendances en exécutant la commande suivante :

    ```
    npm install
    ```

3. **Configuration des variables d'environnement :** Créez un fichier `.env` à la racine du projet et fournissez les informations suivantes :

    ```
    CHANNEL_ID=ID_DU_CANAL
    TOKEN=VOTRE_JETON_DISCORD
    OPENAI_API_KEY=VOTRE_CLÉ_API_OPENAI
    ```

    Remplacez `ID_DU_CANAL` par l'identifiant du canal Discord dans lequel vous souhaitez que le bot opère, `VOTRE_JETON_DISCORD` par le jeton d'authentification de votre bot Discord, et `VOTRE_CLÉ_API_OPENAI` par votre clé API OpenAI.

### Utilisation

Une fois les dépendances installées et les variables d'environnement configurées, vous pouvez démarrer le bot en exécutant la commande suivante :

```
npm start
```

Le bot sera activé et commencera à écouter les messages dans le canal Discord spécifié. Il générera des réponses en fonction des conversations antérieures dans le canal.

### Fonctionnalités

- Le bot génère des réponses en fonction des conversations précédentes dans le canal Discord.
- Il utilise l'API OpenAI pour générer les réponses en se basant sur le modèle de langage GPT-3.5.
- Les réponses sont générées de manière contextuelle, en tenant compte des échanges précédents dans le canal.
