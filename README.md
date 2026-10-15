# ucp-agent-profile

Profil d'agent [UCP](https://ucp.dev) de l'assistant e-commerce open source « le chatbot qui pilote le site ».

Les boutiques compatibles UCP (par exemple les boutiques Shopify) lisent ce fichier à chaque appel pour savoir ce que l'agent sait faire. Il ne contient aucune donnée personnelle, aucun code et aucune clé.

- Profil : [`profile.json`](profile.json)
- Adresse à transmettre aux boutiques (servie en `application/json`) : `https://cdn.jsdelivr.net/gh/LudoArno/ucp-agent-profile@main/profile.json`

Capacités déclarées : recherche et consultation du catalogue, panier. Pas de paiement.
