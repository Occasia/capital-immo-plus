# Landing Page & Lead Form Copy (Capital Immo Community)

This document contains the bilingual (EN/FR) copywriting for the **Capital Immo Community** waitlist landing page (or Meta Instant Forms) and the post-registration automated welcome scripts.

---

## 1. Landing Page / Lead Form Structure

### [EN] English Version

#### Section 1: Hero Header
* **Tagline**: Free In-Person Workshops in Montreal & Laval
* **Main Headline**: Learn to Buy Your First Home or Investment Property—Without the Costly Mistakes.
* **Sub-headline**: Join the **Capital Immo Community** waitlist. Get access to free local workshops, real-world case studies, and a network of like-minded buyers and investors.

#### Section 2: Why Join? (The Value Proposition)
* **Section Title**: Why Join the Capital Immo Community?
* **Benefit 1**: **Real Numbers, No Hype**  
  We don’t do generic advice or sales pitches. We look at real MLS sheets, calculate real cash flows, and analyze real local deals in Montreal and Laval.
* **Benefit 2**: **For First-Time Buyers & Investors**  
  Whether you want to escape the rent trap or acquire your first rental duplex, we cover the exact steps, checklists, and Quebec regulations you need.
* **Benefit 3**: **Practical & In-Person**  
  Meet other ambitious buyers, ask questions directly to experts, and build a local network that supports your real estate journey.

#### Section 3: The Waitlist Form
* **Form Title**: Claim Your Priority Spot on the Waitlist
* **Form Fields**:
  * First Name: *[Input]*
  * Last Name: *[Input]*
  * Email Address: *[Input]*
  * Phone Number: *[Input]*
  * What is your primary goal? *[Dropdown: Buy my first home / Start investing in real estate / Both]*
* **CTA Button**: Join the Waitlist 🔑

#### Section 4: Thank You / Confirmation Page
* **Headline**: You’re on the list! 🎉
* **Sub-headline**: Welcome to the Capital Immo Community.
* **Message**: 
  We have received your registration. We are currently finalizing the venue and dates for our first free in-person workshop in Montreal/Laval.
  
  **What happens next?**
  1. Check your email for a confirmation message.
  2. We will send you the exact date, time, and location details via email and SMS as soon as the doors open.
  3. Since seats are limited, waitlist members get first-priority access to secure their tickets before the public.

---

### [FR] French Version

#### Section 1: Hero Header (En-tête)
* **Slogan**: Ateliers en personne gratuits à Montréal et Laval
* **Titre principal**: Apprenez à acheter votre premier foyer ou immeuble de placement — sans faire d'erreurs coûteuses.
* **Sous-titre**: Rejoignez la liste d'attente de la **Communauté Capital Immo**. Accédez à nos ateliers locaux gratuits, des études de cas réelles et un réseau d'acheteurs et d'investisseurs partageant les mêmes objectifs.

#### Section 2: Pourquoi nous rejoindre ?
* **Titre de la section**: Pourquoi rejoindre la Communauté Capital Immo ?
* **Avantage 1**: **Des vrais chiffres, pas de bla-bla**  
  Pas de conseils généraux ou de pitchs de vente. Nous analysons de vraies fiches MLS, calculons les flux de trésorerie réels (cash flow) et décortiquons des transactions locales à Montréal et Laval.
* **Avantage 2**: **Pour les premiers acheteurs et investisseurs**  
  Que vous souhaitiez sortir du cycle de la location ou acquérir votre premier duplex locatif, nous couvrons les étapes exactes, les listes de contrôle et les réglementations du Québec (TAL).
* **Avantage 3**: **Pratique et en personne**  
  Rencontrez d'autres acheteurs ambitieux, posez vos questions directement aux experts et bâtissez un réseau local pour soutenir votre parcours immobilier.

#### Section 3: Le formulaire de la liste d'attente
* **Titre du formulaire**: Réservez votre place prioritaire sur la liste d'attente
* **Champs du formulaire**:
  * Prénom : *[Saisie]*
  * Nom de famille : *[Saisie]*
  * Adresse courriel : *[Saisie]*
  * Numéro de téléphone : *[Saisie]*
  * Quel est votre objectif principal ? *[Menu déroulant : Acheter ma première maison / Investir en immobilier / Les deux]*
* **Bouton d'action**: Rejoindre la liste d'attente 🔑

#### Section 4: Page de confirmation (Merci)
* **Titre**: Vous êtes inscrit ! 🎉
* **Sous-titre**: Bienvenue dans la Communauté Capital Immo.
* **Message**: 
  Nous avons bien reçu vos informations. Nous finalisons actuellement le choix de la salle et les dates pour notre premier atelier gratuit en personne à Montréal/Laval.
  
  **Que se passe-t-il ensuite ?**
  1. Vérifiez votre boîte de réception pour notre courriel de confirmation.
  2. Nous vous enverrons la date, l'heure et l'adresse de l'événement par courriel et SMS dès que les inscriptions officielles débuteront.
  3. Les places étant limitées, les membres de la liste d'attente bénéficieront d'un accès prioritaire pour réserver leur billet avant le grand public.

---
---

## 2. Automated Welcome Sequence (GoHighLevel/Klaviyo Flow)

Immediately after a user submits the form, they enter the welcome automation.

### Email 1: Welcome & Community Introduction (Sent immediately)

* **Subject (EN)**: Welcome to the Capital Immo Community 🔑
* **Subject (FR)**: Bienvenue dans la Communauté Capital Immo 🔑
* **Body (Bilingual)**:
  
  *(English version)*
  Hi {{ contact.first_name }},
  
  Veronica here from Capital Immo Plus. 
  
  Thank you for joining the **Capital Immo Community** waitlist! I created this collaborative space for renters, future buyers, and aspiring investors in Montreal and Laval to connect, share experiences, and learn about real estate transparently and honestly.
  
  We are currently finalizing the details and date for our next free in-person workshop. Since you are officially on our private invite list, you will receive the registration link and venue details first before we open it to the public.
  
  Keep an eye on your inbox—I will be reaching out very soon with the event announcements!
  
  Talk soon,
  
  **Veronica Pillay**  
  Founder, Capital Immo Plus  
  info@veronicapillay.com
  
  ---
  
  *(Version française)*
  Bonjour {{ contact.first_name }},
  
  Ici Veronica de Capital Immo Plus.
  
  Merci d'avoir rejoint la liste d'attente de la **Communauté Capital Immo** ! J'ai créé cet espace d'entraide pour rassembler les locataires, futurs premiers acheteurs et aspirants investisseurs de Montréal et Laval qui veulent échanger et s'approprier le marché immobilier en toute transparence.
  
  Nous finalisons actuellement l'organisation et la date de notre prochain atelier gratuit en personne. Tu es officiellement sur notre liste d'invitation privée, ce qui signifie que tu recevras tous les détails et ton lien d'inscription en priorité avant le grand public.
  
  Reste à l'affût, je te contacte très bientôt pour t'annoncer le lancement de notre prochain événement !
  
  À très bientôt,
  
  **Veronica Pillay**  
  Fondatrice, Capital Immo Plus  
  info@veronicapillay.com

---

### SMS 1: Instant Confirmation (Sent 2 minutes after signup)

* **Text (Bilingual)**:
  
  *Capital Immo Community*: Hi {{ contact.first_name }}! Thanks for joining our community waitlist. We are locking in the date for our next free workshop in Montreal/Laval and will text you with details very soon. Veronica 🔑
  
  ---
  
  *Communauté Capital Immo* : Bonjour {{ contact.first_name }} ! Merci d'avoir rejoint notre liste d'attente. Nous finalisons la date du prochain atelier gratuit à Mtl/Laval et nous t'envoyons les détails par SMS très bientôt. Veronica 🔑
