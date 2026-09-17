# MarketMind

## SEG4910 / SEG4911 — Projet de génie logiciel en fin d’études

### Équipe

| Membre | Numéro d’étudiant |
|---|---:|
| Erik Skjenna | 300273106 |
| Océane Prud’Homme | 300272920 |
| Lili Rose Théoret | 300342096 |
| Ryan Awad | 300273078 |
| Andy How Hok Hium | 300306884 |



## Type de projet: Type 2 — Marché ouvert 

## Description (Outline) 

MarketMind est un projet de plateforme financière utilisant l’intelligence artificielle pour analyser les nouvelles et les tendances du marché boursier. 

Plus de détails seront ajoutés au fur et à mesure de la conception du projet. 


## Objectif (Objectives: benefit to customer, key things to accomplish, criteria for success): offrir aux clients une façon centralise de consulter les informations liées aux marches boursières. L’IA va facilite la consultation de plusieurs nouvelles et informations financière disponible. Le système devrait permettre de :  

Réduire le temps nécessaire pour trouver des informations financières 

Présenter les informations de manière claire et facile a comprendre pour les utilisateurs 

Obtenir des analyse générées a partir des informations disponibles 

Suivre les tendances du marché 

## Voici unes listes d’objectif principales à accomplir :  

Un utilisateur peut consulter les principales informations du marché à partir d’une seule interface intuitive. 

Les nouvelles financières peuvent être récupérées et affichées correctement. 

L’IA peut générer des résumés cohérents à partir des nouvelles disponibles/consultés 


The main objective of MarketMind is to provide users with a centralized, clear and easy way to access stock market information. We will use artificial intelligence to help users process information from multiple financial sources more efficiently. Our system should allow users to:  

- Reduce the time needed to find financial information
- View information in a clear and easy way to understand
- Receive summaries and analysis generated from available information
- Follow market trends
- Understand relation between financial news, events and market movements.  


## Architecture anticipée (Expected/anticipated architecture) 

- Front end :
-     Main UI provided to the user
- Back end
-     Handles AI-related functionality, financial/news data retrieval, data processing, and communication with external APIs.
-     Useful tools for training and making predictions:
-             https://auto.gluon.ai/stable/index.html
-             https://optuna.readthedocs.io/en/stable/
-     Useful tools for pulling recent stock data
-             https://lmstudio.ai/
-             Feel free to add more... 

## Technologies envisagées 

- Front-end: React / Next.js
- Back-end: Python
- AI/ML: modèle LLM et bibliothèques Python appropriées
- Database: à déterminer selon les besoins du projet
- Financial data: API financière à déterminer
- News: API ou sources de nouvelles financières à déterminer
- Version control: Git / GitHub
- Development environment: VS Code 


## Risques anticipées (Anticipated risks: engineering challenges) 

- Performance: Consulter plusieurs Nouvelles et données financières pourrait avoir un impact sur les performances de l’application.
- Intégration de l’IA : nécessite plusieurs essais pour garantir des résultats pertinents et fiables
- Intégration des données : Les données financières et les nouvelles proviennent de différentes sources et donc varie et formats, limites et niveaux de disponibilité.  

 

## Problèmes juridiques ou sociales (Legal and social issues) 

- Ressources : les sources que l’on va utiliser devront respecter leurs conditions d’utilisation, licences et limites
- AI : les résultats produits par l’IA peuvent contenir des erreurs et donc on ne peux pas assurer l’information comme des conseil financiers.  

 

## Plan initial pour la première publication (Initial plans for first release, tool setup) 

1. Finaliser les exigences et le scope du projet 

2. Choisir les sources de données financières et de nouvelles 

3. Créer un premier prototype du dashboard 

4. Mettre en place le backend et la récupération des données 

5. Intégrer une première solution IA pour les résumer des nouvelles 

6. Ajouter des graphiques/analyse des tendances 

7. Tester l’intégration entre le front-end, le back-end et les services externes 

8. Effectuer des tests auprès des utilisateurs et récolter tout commentaires afin de corriger les problèmes 

9. Préparer une première version fonctionnelle pour démonstration 

 

## Scope du projet:  

- Front end: Dashboard principale avec l'info importante des récentes conclusions. Section de résumé des nouvelles financières, des tenances et l'analyse de l'AI avec des graphiquess
- IA: résumer des nouvelles, pas de promesse de prédiction
- Marchés analyses:  Indices boursiers (représentations de grandes entreprises: S&P 500, NASDAQ-100… ) et principales actions (entreprise individuelle : Apple, Microsoft, Tesla… ) 

## Sources consultees:  a rajouter

 

## Future Functionalities: the following functionalities may be considered for future versions of MarketMind but outside the MVP: 

- Trading automatique
- Comptes utilisateurs et personnalisation plus avancé
- Utilisation de plusieurs modèles d’IA pour sélectionner le plus efficace
- Prédiction automatisée du marché

 
## MEETING MINUTES SECTION

## Minutes - Meeting on Friday, September 11 (4pm to 5:30pm) - Everyone is present 

- Mock-up of a website by ChatGPT with burgundy/dark red, gold and white
- Separate website for new clients and another platform for existing clients?
- Initially: MVP and later full account
- Later: Login + accounts = more professional and personalization, user info
- Payroll for full access to the AI vs Free version with a less performant AI --> subscription based (not a percentage of our clients’ revenue because too much dependant on the markets)
- Macros
- AI provides only insights vs AI does the trades for the clients, maybe higher subscription fees for AI doing the trades
- Maybe have many different models, and for each trade choose the best model
- Use the cookies/tokens/things-based training (behaviors, not only words)
- AI goes through the news and other social medias like Twitter (watching for specific accounts, like Trump)
- Auto-trading could be interesting
- Look into the companies’ history to help make the link between events/news and the gains and losses on the stock markets (ex: Apple loses with iPhone 7 and audio-jack removal, then it goes back up when it comes back) --> these predictions can be made by LLMs (web search, APIs, open-source AIs) and then fine-tuned them afterwards so that there is a software engineering part to the project
- Confirm with teacher if we have a budget
- Importance of the front-end to attract clients
- Brainstorming over having a domain, link with an email domain, and potentially changing the name of the project
- Day and time for next meeting (Monday, in person after class) 

 

## Minutes - Meeting on Friday, September 14 (after class) - Everyone is present 

- Two algorithms (one for the news, one for the chart) that look at the prices separately and then we calculate the average. Possibly blend then together.
- Next step: Individually analyse the one similar company on the market and note the features that we want to keep or add to our product (we will then meet and compare on our side what we found) 

 
