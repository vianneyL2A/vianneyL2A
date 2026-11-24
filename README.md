# Bonjour, je suis BARCOLA Mazamesso 👋

**Ingénieur IA & Big Data**, diplômé d'un Master Informatique spécialité IA & Big Data (Université de Lomé × UTBM, 2026). Je conçois des **agents IA qui tournent en production** et automatisent des processus métier. J'ai aussi livré une **application mobile** utilisée par une entreprise de livraison à Lomé.

📍 Lomé, Togo

---

### 🧠 Ce que je fais

- **Agents LLM et automatisation** : orchestration n8n, sortie structurée, RAG, garde-fous déterministes, transfert vers un humain
- **NLP et évaluation** : corpus annotés, précision / rappel / F1, comparaison de modèles chiffrée et analyse d'erreurs
- **Data engineering** : parsing et nettoyage de données conversationnelles réelles, pipelines Python, exports JSONL
- **Mobile** : applications Flutter de bout en bout, de l'API au paiement, jusqu'à la mise en production

### 🛠️ Stack

**IA / Data**

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![OpenAI](https://img.shields.io/badge/GPT--4o-412991?logo=openai&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-pgvector-3ECF8E?logo=supabase&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?logo=n8n&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?logo=pytest&logoColor=white)
<!-- TODO(Vianney) : ajouter d'autres outils IA/Data que vous maîtrisez (Pandas, Scikit-learn, PyTorch, Spark, LangChain…) -->

**Mobile / Intégration / Déploiement**

![Flutter](https://img.shields.io/badge/Flutter-02569B?logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?logo=dart&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?logo=firebase&logoColor=black)
![WhatsApp](https://img.shields.io/badge/WhatsApp%20Cloud%20API-25D366?logo=whatsapp&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black)
![Java](https://img.shields.io/badge/Java-ED8B00?logo=openjdk&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white)

---

### 🚀 Projets à la une

#### 🤖 [AI Orchestrator](https://github.com/vianneyL2A/AI_Orchestrator) : agent IA de prise de commande sur WhatsApp
Projet de master réalisé en stage chez **Speed Server** (coursiers, Lomé). Un agent **en production** reçoit les commandes sur WhatsApp, écrites en français togolais informel. Il comprend la demande, localise les adresses, calcule le prix et crée la course. Il affecte ensuite le livreur le moins chargé et déclenche le paiement mobile money (FedaPay). Tout cela se fait sans opérateur.

- **n8n + GPT-4o + RAG pgvector** construit sur **1 069 conversations réelles** (10 k messages nettoyés)
- **Le LLM ne décide de rien d'irréversible** : prix, GPS, création de course et paiement sont du code déterministe, avec une barrière de validation et un transfert humain traçable
- **Benchmark NLU** sur 120 tours annotés : GPT-4o contre GPT-4o-mini, avec **+24 points** d'exactitude sur l'intention

<a href="https://github.com/vianneyL2A/AI_Orchestrator"><img src="https://raw.githubusercontent.com/vianneyL2A/AI_Orchestrator/main/docs/images/architecture_globale.png" alt="Architecture de l'agent IA WhatsApp" width="100%"></a>

#### 🛵 [Speed Delivery](https://github.com/vianneyL2A/speed-delivery-showcase) : application de livraison multi-services
Application Flutter pour **Speed Server** (Lomé) : repas, colis, pharmacie, supermarché, paiement mobile FedaPay et notifications push. J'en suis le **développeur principal** (≈85 % des commits). J'ai notamment mené une refonte d'architecture qui a fait passer les avertissements du linter de **615 à 41**.

<a href="https://github.com/vianneyL2A/speed-delivery-showcase"><img src="https://raw.githubusercontent.com/vianneyL2A/speed-delivery-showcase/main/assets/banner.png" alt="Speed Delivery" width="100%"></a>

#### 🏙️ [city-skyline](https://github.com/vianneyL2A/city-skyline) : simulation de réseau électrique
Projet universitaire en binôme (EPL, Université de Lomé). Jeu de simulation en **Java 21 / Swing** où l'on gère le réseau électrique d'une ville en croissance : production, demande, budget et bonheur des habitants, avec 3 niveaux de difficulté. [▶ Vidéo de démonstration](https://youtu.be/Q8_tt2a1WrQ)

---

<!-- TODO(Vianney) : décommenter et compléter avec les liens que vous voulez rendre publics
### 📫 Me contacter
- LinkedIn : https://www.linkedin.com/in/...
- Email : ...
-->
