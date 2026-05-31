# VTC Firstly - Plateforme Professionnelle de Réservation en Ligne

> Dépôt officiel du site vitrine et de l'application de réservation de **VTC Firstly**, service de chauffeur privé haut de gamme opérant à Paris, en Île-de-France (notamment Provins, Marne-la-Vallée, Disneyland Paris) et vers les grands hubs aéroportuaires.

🔗 **Lien de production :** [https://www.vtcfirstly.com](https://www.vtcfirstly.com)

---

## 📊 Présentation du Projet

L'objectif de ce projet est de fournir une interface utilisateur (UI) fluide, rapide et entièrement responsive (Mobile-First) permettant aux clients de planifier et réserver leurs trajets en temps réel. La plateforme met en avant une flotte premium (Berline Éco / Tesla Model Y, Van Mercedes Classe V) et assure une transparence totale des tarifs.

---

## 🛠️ Architecture Technique & Intégrations

Le projet s'appuie sur une structure optimisée pour le SEO local et la conversion SIA :

* **Frontend :** HTML5 sémantique, CSS3 (Design épuré Dark/Luxurious) et JavaScript.
* **Moteur de Réservation :** Intégration asynchrone du widget natif de réservation (`wix-bookings` / scripts d'intégration partenaires) permettant le calcul d'itinéraire, l'estimation du tarif fixe et le paiement sécurisé.
* **Optimisation SEO Local :** Implémentation de métadonnées Open Graph (Facebook/WhatsApp) et injection de données structurées JSON-LD (`TaxiService` / `LocalBusiness`) pour maximiser l'indexation sur Google Maps et le moteur de recherche Google.

---

## 🗂️ Structure du Dépôt

```text
vtcfirstly/
├── index.html          # Page d'accueil principale et tunnel de conversion
├── README.md           # Documentation technique du projet (ce fichier)
├── css/
│   └── style.css       # Feuilles de style (Layout, Flexbox/Grid, Media Queries)
└── assets/             # Ressources médias optimisées
    ├── logo.png        # Identité visuelle de la marque
    └── vehicles/       # Images de la flotte au format ultra-léger (.webp)
