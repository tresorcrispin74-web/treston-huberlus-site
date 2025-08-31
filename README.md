# 🌐 TRESTON HUBERLUS Invest & Co.,Ltd

Bienvenue sur le dépôt officiel du site web de **TRESTON HUBERLUS Invest & Co.,Ltd**, une entreprise spécialisée dans :

- 🏢 Immobilier  
- 🏗️ Construction  
- 🛣️ Travaux publics  
- 📈 Investissements  

## 💡 Nos valeurs
- **Durabilité** 🌱  
- **Innovation** 🚀  
- **Fiabilité** 🤝  
- **Croissance** 📊  

## 🚀 Site en ligne
Ce site est déployé gratuitement grâce à **GitHub Pages** :  
👉 [Voir le site](https://tresorcrispin74-web.github.io/treston-huberlus-site/)

## 📂 Structure du projet
- `index.html` → page principale  
- (Autres fichiers CSS/JS/images selon évolution)  

## 🔧 Hébergement
- Plateforme : [GitHub Pages](https://pages.github.com/)  
- Déploiement automatique à chaque mise à jour sur la branche `main`.  

## ✨ Auteur
Créé et maintenu par **TRESTON HUBERLUS Invest & Co.,Ltd**.

<a href="#accueil" class="flex items-center gap-3">
  <!-- Ancien SVG -->
  <svg>...</svg>
  <span class="font-semibold text-[15px] sm:text-base" style="color:var(--blue)">TRESTON HUBERLUS</span>
</a>

<a href="#accueil" class="flex items-center gap-3">
  <img src="logo.png" alt="TRESTON HUBERLUS Logo" class="h-10 w-auto">
  <span class="font-semibold text-[15px] sm:text-base" style="color:var(--blue)">TRESTON HUBERLUS</span>
</a>

<!DOCTYPE html><html lang="fr">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>TRESTON HUBERLUS Invest &amp; Co.,Ltd — Immobilier • Construction • Travaux publics</title>
  <meta name="description" content="Immobilier, construction et travaux publics. Valeurs : durabilité, innovation, fiabilité, croissance." />
  <meta property="og:title" content="TRESTON HUBERLUS Invest &amp; Co.,Ltd" />
  <meta property="og:description" content="Projets durables et innovants dans l'immobilier, la construction et les travaux publics." />
  <meta property="og:type" content="website" />
  <link rel="icon" href="logo.png" />
  <script src="https://cdn.tailwindcss.com"></script>
  <style>
    :root{
      --blue:#0E3A63;  /* confiance */
      --green:#198754; /* croissance/durabilité */
      --gold:#C9A227;  /* prestige */
      --white:#ffffff;
    }
    html{scroll-behavior:smooth}
    .shadow-soft{box-shadow:0 12px 30px rgba(0,0,0,.08)}
    .chip{display:inline-flex;align-items:center;gap:.5rem;padding:.4rem .75rem;border-radius:9999px;border:1px solid rgba(0,0,0,.08);background:#fff}
    .hero-bg{background: radial-gradient(1200px 600px at 20% -10%, #e9f5ff 0, transparent 60%), radial-gradient(900px 500px at 120% 10%, #effcf3 0, transparent 60%)}
    .gold{color:var(--gold)}
  </style>
</head>
<body class="bg-white text-slate-800">
  <!-- Navbar -->
  <header class="sticky top-0 z-40 bg-white/90 backdrop-blur border-b">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <div class="flex items-center justify-between h-16">
        <a href="#accueil" class="flex items-center gap-3">
          <img src="logo.png" alt="TRESTON HUBERLUS Logo" class="h-10 w-auto" onerror="this.style.display='none'">
          <span class="font-semibold text-[15px] sm:text-base" style="color:var(--blue)">TRESTON HUBERLUS</span>
        </a>
        <nav class="hidden md:flex gap-6">
          <a href="#accueil" class="hover:text-slate-900" data-i18n="nav.home">Accueil</a>
          <a href="#services" class="hover:text-slate-900" data-i18n="nav.services">Services</a>
          <a href="#corporate" class="hover:text-slate-900" data-i18n="nav.corporate">Corporate</a>
          <a href="#projets" class="hover:text-slate-900" data-i18n="nav.projects">Projets</a>
          <a href="#apropos" class="hover:text-slate-900" data-i18n="nav.about">À propos</a>
          <a href="#contact" class="hover:text-slate-900" data-i18n="nav.contact">Contact</a>
        </nav>
        <div class="flex items-center gap-2">
          <button id="lang-fr" class="px-3 py-1 rounded-full border text-sm" aria-label="Français">FR</button>
          <button id="lang-en" class="px-3 py-1 rounded-full border text-sm" aria-label="English">EN</button>
          <button id="menuBtn" class="md:hidden p-2 rounded border" aria-label="Menu">☰</button>
        </div>
      </div>
      <div id="mobileNav" class="md:hidden hidden pb-4">
        <div class="flex flex-col gap-3">
          <a href="#accueil" class="py-1" data-i18n="nav.home">Accueil</a>
          <a href="#services" class="py-1" data-i18n="nav.services">Services</a>
          <a href="#corporate" class="py-1" data-i18n="nav.corporate">Corporate</a>
          <a href="#projets" class="py-1" data-i18n="nav.projects">Projets</a>
          <a href="#apropos" class="py-1" data-i18n="nav.about">À propos</a>
          <a href="#contact" class="py-1" data-i18n="nav.contact">Contact</a>
        </div>
      </div>
    </div>
  </header>  <!-- Hero -->  <section id="accueil" class="relative hero-bg">
    <div class="relative max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-20">
      <div class="grid md:grid-cols-2 gap-10 items-center">
        <div>
          <h1 class="text-3xl sm:text-5xl font-extrabold leading-tight" style="color:var(--blue)" data-i18n="hero.title">Bâtir l’avenir — durable, fiable, innovant.</h1>
          <p class="mt-4 text-lg text-slate-600" data-i18n="hero.subtitle">Immobilier, construction et travaux publics. Nous livrons des projets performants qui créent de la valeur à long terme.</p>
          <div class="mt-6 flex flex-wrap gap-3">
            <a href="#services" class="rounded-2xl px-5 py-3 text-white" style="background:var(--blue)" data-i18n="cta.services">Voir nos services</a>
            <a href="#contact" class="rounded-2xl px-5 py-3 border" style="border-color:var(--gold)" data-i18n="cta.quote">Demander un devis</a>
          </div>
          <div class="mt-6 flex gap-2 text-sm flex-wrap">
            <span class="chip">🌱 <span data-i18n="values.sustainability">Durabilité</span></span>
            <span class="chip">🚀 <span data-i18n="values.innovation">Innovation</span></span>
            <span class="chip">🤝 <span data-i18n="values.reliability">Fiabilité</span></span>
            <span class="chip">📈 <span data-i18n="values.growth">Croissance</span></span>
          </div>
          <div class="mt-6 text-sm text-slate-600" data-i18n="hero.note">Prêt pour les marchés publics internationaux — documentation, conformité et références sur demande.</div>
        </div>
        <div class="shadow-soft rounded-3xl overflow-hidden">
          <img src="https://images.unsplash.com/photo-1501183638710-841dd1904471?q=80&w=1500&auto=format&fit=crop" alt="Chantier et bâtiments modernes" class="w-full h-[360px] object-cover">
        </div>
      </div>
    </div>
  </section>  <!-- Services -->  <section id="services" class="py-16 bg-slate-50">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <h2 class="text-2xl sm:text-3xl font-bold mb-8" style="color:var(--blue)" data-i18n="services.title">Nos services</h2>
      <div class="grid sm:grid-cols-2 lg:grid-cols-4 gap-6">
        <div class="bg-white rounded-2xl p-6 shadow-soft border">
          <div class="text-3xl">🏢</div>
          <h3 class="font-semibold mt-3" data-i18n="services.realestate.title">Immobilier</h3>
          <p class="text-sm text-slate-600 mt-2" data-i18n="services.realestate.text">Promotion, acquisition et gestion d’actifs à haute valeur durable.</p>
        </div>
        <div class="bg-white rounded-2xl p-6 shadow-soft border">
          <div class="text-3xl">🏗️</div>
          <h3 class="font-semibold mt-3" data-i18n="services.construction.title">Construction</h3>
          <p class="text-sm text-slate-600 mt-2" data-i18n="services.construction.text">Conception et réalisation d’ouvrages performants et sécurisés.</p>
        </div>
        <div class="bg-white rounded-2xl p-6 shadow-soft border">
          <div class="text-3xl">🛣️</div>
          <h3 class="font-semibold mt-3" data-i18n="services.publicworks.title">Travaux publics</h3>
          <p class="text-sm text-slate-600 mt-2" data-i18n="services.publicworks.text">Infrastructures routières et urbaines au service des communautés.</p>
        </div>
        <div class="bg-white rounded-2xl p-6 shadow-soft border">
          <div class="text-3xl">📈</div>
          <h3 class="font-semibold mt-3" data-i18n="services.investment.title">Investissements</h3>
          <p class="text-sm text-slate-600 mt-2" data-i18n="services.investment.text">Montage et financement de projets à fort potentiel.</p>
        </div>
      </div>
    </div>
  </section>  <!-- Corporate (capabilities + compliance) -->  <section id="corporate" class="py-16">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <div class="grid lg:grid-cols-3 gap-8">
        <div class="lg:col-span-2">
          <h2 class="text-2xl sm:text-3xl font-bold mb-4" style="color:var(--blue)" data-i18n="corp.title">Présentation corporate</h2>
          <p class="text-slate-700" data-i18n="corp.lead">Nous combinons excellence opérationnelle, gouvernance solide et approche partenariale pour livrer des projets à l’échelle internationale.</p>
          <div class="mt-6 grid sm:grid-cols-2 gap-6">
            <div class="p-5 bg-white border rounded-2xl shadow-soft">
              <h3 class="font-semibold" data-i18n="corp.vision.title">Vision</h3>
              <p class="text-sm text-slate-600 mt-2" data-i18n="corp.vision.text">Bâtir des infrastructures et des espaces qui améliorent durablement la qualité de vie et la compétitivité des territoires.</p>
            </div>
            <div class="p-5 bg-white border rounded-2xl shadow-soft">
              <h3 class="font-semibold" data-i18n="corp.mission.title">Mission</h3>
              <p class="text-sm text-slate-600 mt-2" data-i18n="corp.mission.text">Concevoir, financer et exécuter des projets avec des standards internationaux de qualité, sécurité et transparence.</p>
            </div>
          </div>
          <h3 class="font-semibold mt-8" data-i18n="corp.capabilities">Compétences clés</h3>
          <ul class="grid sm:grid-cols-2 gap-3 text-slate-700 mt-2">
            <li>✔ <span data-i18n="cap.item1">Gestion EPC et conduite de chantier</span></li>
            <li>✔ <span data-i18n="cap.item2">Contrôle qualité, sécurité &amp; conformité</span></li>
            <li>✔ <span data-i18n="cap.item3">Efficacité énergétique &amp; matériaux durables</span></li>
            <li>✔ <span data-i18n="cap.item4">Planification, coûts, délais (PMO)</span></li>
            <li>✔ <span data-i18n="cap.item5">Partenariats publics-privés (PPP)</span></li>
            <li>✔ <span data-i18n="cap.item6">Montage financier &amp; investissements</span></li>
          </ul>
        </div>
        <div class="lg:col-span-1">
          <h3 class="font-semibold" data-i18n="compliance.title">Conformité &amp; Qualité</h3>
          <ul class="text-sm text-slate-700 space-y-1 mt-2">
            <li>• <span data-i18n="compliance.item1">Système QSE (Qualité–Sécurité–Environnement)</span></li>
            <li>• <span data-i18n="compliance.item2">Procédures anti-corruption &amp; éthique des affaires</span></li>
            <li>• <span data-i18n="compliance.item3">Traçabilité fournisseurs &amp; due diligence</span></li>
            <li>• <span data-i18n="compliance.item4">Rapports ESG sur demande</span></li>
          </ul>
          <div class="mt-4 p-4 bg-green-50 border rounded-2xl text-sm" data-i18n="compliance.note">Certifications et références disponibles sur demande. Alignement sur les exigences ONU, UE et banques de développement.</div>
        </div>
      </div>
    </div>
  </section>  <!-- Projects -->  <section id="projets" class="py-16 bg-slate-50">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <div class="flex items-end justify-between mb-8">
        <h2 class="text-2xl sm:text-3xl font-bold" style="color:var(--blue)" data-i18n="projects.title">Projets réalisés</h2>
        <span class="text-sm font-semibold gold" data-i18n="projects.subtitle">Sélection de références</span>
      </div>
      <div class="grid sm:grid-cols-2 lg:grid-cols-3 gap-6">
        <article class="rounded-2xl overflow-hidden border shadow-soft">
          <img src="https://images.unsplash.com/photo-1465808883810-8d4ac0b7de5a?q=80&w=1200&auto=format&fit=crop" alt="Complexe immobilier" class="h-44 w-full object-cover">
          <div class="p-4">
            <h3 class="font-semibold" data-i18n="projects.p1.title">Complexe immobilier</h3>
            <p class="text-sm text-slate-600 mt-1" data-i18n="projects.p1.text">Efficacité énergétique &amp; certifications environnementales.</p>
          </div>
        </article>
        <article class="rounded-2xl overflow-hidden border shadow-soft">
          <img src="https://images.unsplash.com/photo-1503387762-592deb58ef4e?q=80&w=1200&auto=format&fit=crop" alt="Tour de bureaux" class="h-44 w-full object-cover">
          <div class="p-4">
            <h3 class="font-semibold" data-i18n="projects.p2.title">Tour de bureaux HQ</h3>
            <p class="text-sm text-slate-600 mt-1" data-i18n="projects.p2.text">Architecture innovante et performances élevées.</p>
          </div>
        </article>
        <article class="rounded-2xl overflow-hidden border shadow-soft">
          <img src="https://images.unsplash.com/photo-1541888946425-d81bb19240f5?q=80&w=1200&auto=format&fit=crop" alt="Pont urbain" class="h-44 w-full object-cover">
          <div class="p-4">
            <h3 class="font-semibold" data-i18n="projects.p3.title">Pont urbain &amp; voirie</h3>
            <p class="text-sm text-slate-600 mt-1" data-i18n="projects.p3.text">Mobilité améliorée et impact positif local.</p>
          </div>
        </article>
      </div>
    </div>
  </section>  <!-- About -->  <section id="apropos" class="py-16">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 grid md:grid-cols-2 gap-8 items-center">
      <div>
        <h2 class="text-2xl sm:text-3xl font-bold mb-4" style="color:var(--blue)" data-i18n="about.title">À propos</h2>
        <p class="text-slate-700" data-i18n="about.text">TRESTON HUBERLUS Invest &amp; Co.,Ltd conçoit et livre des projets qui allient esthétique, performance et responsabilité. Nous travaillons avec des standards internationaux et une gouvernance solide.</p>
        <ul class="mt-4 space-y-2 text-slate-700">
          <li>• <span data-i18n="about.item1">Gouvernance responsable &amp; conformité</span></li>
          <li>• <span data-i18n="about.item2">Éthique, sécurité et qualité</span></li>
          <li>• <span data-i18n="about.item3">Partenariats durables &amp; innovation utile</span></li>
        </ul>
      </div>
      <div class="rounded-3xl overflow-hidden shadow-soft">
        <img src="https://images.unsplash.com/photo-1496307042754-b4aa456c4a2d?q=80&w=1500&auto=format&fit=crop" alt="Équipe au travail" class="w-full h-[320px] object-cover">
      </div>
    </div>
  </section>  <!-- Contact -->  <section id="contact" class="py-16 bg-slate-50">
    <div class="max-w-3xl mx-auto px-4 sm:px-6 lg:px-8">
      <h2 class="text-2xl sm:text-3xl font-bold mb-6" style="color:var(--blue)" data-i18n="contact.title">Contact</h2>
      <form class="bg-white rounded-2xl p-6 shadow-soft border" onsubmit="handleSubmit(event)">
        <div class="grid md:grid-cols-2 gap-4">
          <div>
            <label class="text-sm" data-i18n="contact.name">Nom</label>
            <input id="input-name" type="text" required class="mt-1 w-full rounded-xl border px-3 py-2" placeholder="Votre nom" data-i18n-placeholder="contact.name.ph">
          </div>
          <div>
            <label class="text-sm" data-i18n="contact.email">Email</label>
            <input id="input-email" type="email" required class="mt-1 w-full rounded-xl border px-3 py-2" placeholder="vous@exemple.com" data-i18n-placeholder="contact.email.ph">
          </div>
        </div>
        <div class="mt-4">
          <label class="text-sm" data-i18n="contact.message">Message</label>
          <textarea id="input-msg" required class="mt-1 w-full rounded-xl border px-3 py-2 h-32" placeholder="Parlez-nous de votre projet..." data-i18n-placeholder="contact.message.ph"></textarea>
        </div>
        <div class="mt-6 flex items-center justify-between">
          <div class="text-sm text-slate-600">
            <span data-i18n="contact.alt">ou écrivez-nous :</span>
            <a href="mailto:contact@treston-huberlus.com" class="underline" style="color:var(--blue)">contact@treston-huberlus.com</a>
          </div>
          <button type="submit" class="rounded-2xl px-5 py-2 text-white" style="background:var(--green)" data-i18n="contact.send">Envoyer</button>
        </div>
      </form>
      <p id="formNote" class="mt-3 text-sm text-slate-600" data-i18n="contact.note">Astuce : connectez ce formulaire à Formspree ou Netlify Forms pour l’envoi réel.</p>
    </div>
  </section>  <footer class="border-t py-8">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 flex flex-col md:flex-row items-center justify-between gap-4">
      <div class="flex items-center gap-3">
        <img src="logo.png" alt="Logo" class="h-8 w-auto" onerror="this.style.display='none'">
        <span class="text-sm">© <span id="year"></span> TRESTON HUBERLUS Invest &amp; Co.,Ltd — <span data-i18n="footer.rights">Tous droits réservés.</span></span>
      </div>
      <div class="text-sm">
        <a href="#corporate" class="hover:underline" data-i18n="footer.proc">Procurement</a> ·
        <a href="#contact" class="hover:underline" data-i18n="footer.quote">Devis</a>
      </div>
    </div>
  </footer>  <script>
    // Mobile nav
    const menuBtn = document.getElementById('menuBtn');
    const mobileNav = document.getElementById('mobileNav');
    menuBtn && menuBtn.addEventListener('click', ()=> mobileNav.classList.toggle('hidden'));
    // Year
    document.getElementById('year').textContent = new Date().getFullYear();
    // Fake form submit
    function handleSubmit(e){
      e.preventDefault();
      e.target.reset();
      document.getElementById('formNote').textContent = t('contact.sent');
    }

    // --- i18n ---
    const I18N = {
      fr: {
        'nav.home':'Accueil','nav.services':'Services','nav.corporate':'Corporate','nav.projects':'Projets','nav.about':'À propos','nav.contact':'Contact',
        'hero.title':'Bâtir l\u2019avenir \u2014 durable, fiable, innovant.',
        'hero.subtitle':'Immobilier, construction et travaux publics. Nous livrons des projets performants qui créent de la valeur à long terme.',
        'cta.services':'Voir nos services','cta.quote':'Demander un devis',
        'values.sustainability':'Durabilité','values.innovation':'Innovation','values.reliability':'Fiabilité','values.growth':'Croissance',
        'hero.note':'Prêt pour les marchés publics internationaux — documentation, conformité et références sur demande.',
        'services.title':'Nos services',
        'services.realestate.title':'Immobilier','services.realestate.text':'Promotion, acquisition et gestion d\u2019actifs à haute valeur durable.',
        'services.construction.title':'Construction','services.construction.text':'Conception et réalisation d\u2019ouvrages performants et sécurisés.',
        'services.publicworks.title':'Travaux publics','services.publicworks.text':'Infrastructures routières et urbaines au service des communautés.',
        'services.investment.title':'Investissements','services.investment.text':'Montage et financement de projets à fort potentiel.',
        'corp.title':'Présentation corporate','corp.lead':'Nous combinons excellence opérationnelle, gouvernance solide et approche partenariale pour livrer des projets à l\u2019échelle internationale.',
        'corp.vision.title':'Vision','corp.vision.text':'Bâtir des infrastructures et des espaces qui améliorent durablement la qualité de vie et la compétitivité des territoires.',
        'corp.mission.title':'Mission','corp.mission.text':'Concevoir, financer et exécuter des projets avec des standards internationaux de qualité, sécurité et transparence.',
        'corp.capabilities':'Compétences clés',
        'cap.item1':'Gestion EPC et conduite de chantier','cap.item2':'Contrôle qualité, sécurité & conformité','cap.item3':'Efficacité énergétique & matériaux durables','cap.item4':'Planification, coûts, délais (PMO)','cap.item5':'Partenariats publics-privés (PPP)','cap.item6':'Montage financier & investissements',
        'compliance.title':'Conformité & Qualité','compliance.item1':'Système QSE (Qualité–Sécurité–Environnement)','compliance.item2':'Procédures anti-corruption & éthique des affaires','compliance.item3':'Traçabilité fournisseurs & due diligence','compliance.item4':'Rapports ESG sur demande','compliance.note':'Certifications et références disponibles sur demande. Alignement sur les exigences ONU, UE et banques de développement.',
        'projects.title':'Projets réalisés','projects.subtitle':'Sélection de références','projects.p1.title':'Complexe immobilier','projects.p1.text':'Efficacité énergétique & certifications environnementales.','projects.p2.title':'Tour de bureaux HQ','projects.p2.text':'Architecture innovante et performances élevées.','projects.p3.title':'Pont urbain & voirie','projects.p3.text':'Mobilité améliorée et impact positif local.',
        'about.title':'À propos','about.text':'TRESTON HUBERLUS Invest & Co.,Ltd conçoit et livre des projets qui allient esthétique, performance et responsabilité. Nous travaillons avec des standards internationaux et une gouvernance solide.','about.item1':'Gouvernance responsable & conformité','about.item2':'Éthique, sécurité et qualité','about.item3':'Partenariats durables & innovation utile',
        'contact.title':'Contact','contact.name':'Nom','contact.email':'Email','contact.message':'Message','contact.alt':'ou écrivez-nous :','contact.send':'Envoyer','contact.note':'Astuce : connectez ce formulaire à Formspree ou Netlify Forms pour l\u2019envoi réel.','contact.sent':'Merci ! Votre message a été simulé. Connectez un service (Formspree / Netlify Forms) pour l\u2019envoi réel.',
        'contact.name.ph':'Votre nom','contact.email.ph':'vous@exemple.com','contact.message.ph':'Parlez-nous de votre projet...','footer.rights':'Tous droits réservés.','footer.proc':'Procurement','footer.quote':'Devis'
      },
      en: {
        'nav.home':'Home','nav.services':'Services','nav.corporate':'Corporate','nav.projects':'Projects','nav.about':'About','nav.contact':'Contact',
        'hero.title':'Building the future — sustainable, reliable, innovative.',
        'hero.subtitle':'Real estate, construction and public works. We deliver high‑performance projects that create long‑term value.',
        'cta.services':'Explore services','cta.quote':'Request a quote',
        'values.sustainability':'Sustainability','values.innovation':'Innovation','values.reliability':'Reliability','values.growth':'Growth',
        'hero.note':'Ready for international public procurement — documentation, compliance and references upon request.',
        'services.title':'Our services',
        'services.realestate.title':'Real Estate','services.realestate.text':'Development, acquisition and management of sustainable assets.',
        'services.construction.title':'Construction','services.construction.text':'Design and execution of safe, high‑performance works.',
        'services.publicworks.title':'Public Works','services.publicworks.text':'Road and urban infrastructure serving communities.',
        'services.investment.title':'Investments','services.investment.text':'Project structuring and financing with strong potential.',
        'corp.title':'Corporate overview','corp.lead':'We combine operational excellence, solid governance and partnership approach to deliver projects at international scale.',
        'corp.vision.title':'Vision','corp.vision.text':'Build infrastructure and spaces that sustainably improve quality of life and territorial competitiveness.',
        'corp.mission.title':'Mission','corp.mission.text':'Design, finance and execute projects under international standards of quality, safety and transparency.',
        'corp.capabilities':'Core capabilities',
        'cap.item1':'EPC management & site execution','cap.item2':'Quality, Safety & Compliance control','cap.item3':'Energy efficiency & sustainable materials','cap.item4':'Planning, cost & schedule (PMO)','cap.item5':'Public–Private Partnerships (PPP)','cap.item6':'Financial structuring & investments',
        'compliance.title':'Compliance & Quality','compliance.item1':'QSE system (Quality–Safety–Environment)','compliance.item2':'Anti‑corruption procedures & business ethics','compliance.item3':'Supplier traceability & due diligence','compliance.item4':'ESG reporting on request','compliance.note':'Certifications and references available upon request. Alignment with UN, EU and development banks requirements.',
        'projects.title':'Selected projects','projects.subtitle':'Reference selection','projects.p1.title':'Premium housing complex','projects.p1.text':'Energy efficiency & environmental certifications.','projects.p2.title':'HQ office tower','projects.p2.text':'Innovative architecture and high performance.','projects.p3.title':'Urban bridge & roadworks','projects.p3.text':'Improved mobility and positive local impact.',
        'about.title':'About us','about.text':'TRESTON HUBERLUS Invest & Co.,Ltd designs and delivers projects that combine aesthetics, performance and responsibility. We operate under international standards with strong governance.','about.item1':'Responsible governance & compliance','about.item2':'Ethics, safety and quality','about.item3':'Long‑term partnerships & useful innovation',
        'contact.title':'Contact','contact.name':'Name','contact.email':'Email','contact.message':'Message','contact.alt':'or write to us:','contact.send':'Send','contact.note':'Tip: connect this form to Formspree or Netlify Forms to enable real submissions.','contact.sent':'Thank you! Your message was simulated. Connect a service (Formspree / Netlify Forms) for real sending.',
        'contact.name.ph':'Your name','contact.email.ph':'you@example.com','contact.message.ph':'Tell us about your project…','footer.rights':'All rights reserved.','footer.proc':'Procurement','footer.quote':'Quote'
      }
    };

    function t(key){
      const lang = localStorage.getItem('lang') || 'fr';
      return (I18N[lang] && I18N[lang][key]) || key;
    }

    function applyI18n(){
      const lang = localStorage.getItem('lang') || 'fr';
      document.documentElement.lang = lang === 'fr' ? 'fr' : 'en';
      document.querySelectorAll('[data-i18n]').forEach(el=>{ el.textContent = t(el.getAttribute('data-i18n')); });
      document.querySelectorAll('[data-i18n-placeholder]').forEach(el=>{ el.setAttribute('placeholder', t(el.getAttribute('data-i18n-placeholder'))); });
    }

    document.getElementById('lang-fr').addEventListener('click', ()=>{ localStorage.setItem('lang','fr'); applyI18n(); });
    document.getElementById('lang-en').addEventListener('click', ()=>{ localStorage.setItem('lang','en'); applyI18n(); });

    applyI18n();
  </script></body>
</html>

<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Capability Statement - TRESTON HUBERLUS Invest & Co.,Ltd</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    // Textes FR/EN
    const translations = {
      fr: {
        title: "Capability Statement",
        intro: "TRESTON HUBERLUS Invest & Co.,Ltd est une entreprise spécialisée dans l’immobilier, la construction et les travaux publics. Nous nous engageons à fournir des solutions durables, innovantes et fiables qui favorisent la croissance.",
        expertise: "Domaines d’expertise",
        expList: ["Immobilier", "Construction", "Travaux publics", "Investissements"],
        values: "Valeurs fondamentales",
        valList: ["Durabilité", "Innovation", "Fiabilité", "Croissance"],
        projects: "Projets phares",
        projDesc: "Nous avons mené avec succès plusieurs projets dans l’immobilier et les travaux publics, toujours avec une vision durable et moderne.",
        strengths: "Atouts compétitifs",
        strList: [
          "Expertise technique et stratégique",
          "Équipe professionnelle et expérimentée",
          "Approche axée sur la durabilité et l’innovation",
          "Réseau solide dans les marchés locaux et internationaux"
        ],
        contact: "Contact institutionnel",
        address: "Siège : [Ton adresse complète]",
        email: "Email : contact@treston-huberlus.com",
        phone: "Téléphone : +XXX XXX XXX",
        pdf: "📄 Télécharger en PDF"
      },
      en: {
        title: "Capability Statement",
        intro: "TRESTON HUBERLUS Invest & Co.,Ltd is a company specialized in real estate, construction, and public works. We are committed to delivering sustainable, innovative, and reliable solutions that foster growth.",
        expertise: "Areas of Expertise",
        expList: ["Real Estate", "Construction", "Public Works", "Investments"],
        values: "Core Values",
        valList: ["Sustainability", "Innovation", "Reliability", "Growth"],
        projects: "Flagship Projects",
        projDesc: "We have successfully delivered multiple real estate and public works projects, always with a sustainable and modern vision.",
        strengths: "Competitive Strengths",
        strList: [
          "Technical and strategic expertise",
          "Professional and experienced team",
          "Sustainability and innovation driven approach",
          "Strong network in local and international markets"
        ],
        contact: "Institutional Contact",
        address: "Head Office: [Your full address]",
        email: "Email: contact@treston-huberlus.com",
        phone: "Phone: +XXX XXX XXX",
        pdf: "📄 Download PDF"
      }
    };

    let currentLang = "fr";
    function switchLang(lang) {
      currentLang = lang;
      const t = translations[lang];
      document.getElementById("title").innerText = t.title;
      document.getElementById("intro").innerText = t.intro;
      document.getElementById("expertise").innerText = t.expertise;
      document.getElementById("expList").innerHTML = t.expList.map(i => `<li>${i}</li>`).join("");
      document.getElementById("values").innerText = t.values;
      document.getElementById("valList").innerHTML = t.valList.map(i => `<li>${i}</li>`).join("");
      document.getElementById("projects").innerText = t.projects;
      document.getElementById("projDesc").innerText = t.projDesc;
      document.getElementById("strengths").innerText = t.strengths;
      document.getElementById("strList").innerHTML = t.strList.map(i => `<li>${i}</li>`).join("");
      document.getElementById("contact").innerText = t.contact;
      document.getElementById("address").innerText = t.address;
      document.getElementById("email").innerText = t.email;
      document.getElementById("phone").innerText = t.phone;
      document.getElementById("pdfBtn").innerText = t.pdf;
    }
    window.onload = () => switchLang("fr");
  </script>
</head>
<body class="bg-gray-50 text-gray-800 font-sans">
  <!-- Header -->
  <header class="bg-white shadow-md p-4 flex justify-between items-center">
    <img src="logo.png" alt="Logo" class="h-12">
    <div>
      <button onclick="switchLang('fr')" class="px-2">FR</button> | 
      <button onclick="switchLang('en')" class="px-2">EN</button>
    </div>
  </header>

  <!-- Main -->
  <main class="max-w-5xl mx-auto p-6 space-y-8">
    <h1 id="title" class="text-3xl font-bold text-blue-900"></h1>
    <p id="intro" class="text-lg"></p>

    <section>
      <h2 id="expertise" class="text-2xl font-semibold text-green-700"></h2>
      <ul id="expList" class="list-disc pl-6"></ul>
    </section>

    <section>
      <h2 id="values" class="text-2xl font-semibold text-green-700"></h2>
      <ul id="valList" class="list-disc pl-6"></ul>
    </section>

    <section>
      <h2 id="projects" class="text-2xl font-semibold text-green-700"></h2>
      <p id="projDesc"></p>
    </section>

    <section>
      <h2 id="strengths" class="text-2xl font-semibold text-green-700"></h2>
      <ul id="strList" class="list-disc pl-6"></ul>
    </section>

    <section>
      <h2 id="contact" class="text-2xl font-semibold text-green-700"></h2>
      <p id="address"></p>
      <p id="email"></p>
      <p id="phone"></p>
    </section>

    <div class="text-center">
      <button id="pdfBtn" onclick="window.print()" class="bg-blue-600 text-white px-4 py-2 rounded-lg shadow">
        📄 Télécharger en PDF
      </button>
    </div>
  </main>

  <!-- Footer -->
  <footer class="bg-gray-900 text-white p-4 text-center">
    © 2025 TRESTON HUBERLUS Invest & Co.,Ltd. All rights reserved.
  </footer>
</body>
</html>