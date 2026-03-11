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
        address: "Siège : [08, Avenue Esanga,Quartier CPA Mushie, Localité de Mbudi, Commune de Mont-Ngafula]",
        email: "Email : contact@treston-huberlus.com",
        phone: "Téléphone : +243859105718, +243811431593",
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
        address: "Head Office: [08, Avenue Esanga, Quartier CPA Mushie, Localité de Mbudi, Commune de Mont-Ngafula]",
        email: "Email: contact@treston-huberlus.com",
        phone: "Phone: +243859105718, +243811431593",
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

<a href="capability.html" class="hover:text-blue-500">Capability Statement</a>

<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>TRESTON HUBERLUS Invest & Co.,Ltd</title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gray-50 text-gray-800 font-sans">

  <!-- Header -->
  <header class="bg-white shadow-md fixed w-full top-0 z-50">
    <div class="max-w-7xl mx-auto flex justify-between items-center p-4">
      <div class="flex items-center space-x-3">
        <img src="logo.png" alt="Logo" class="h-12">
        <span class="font-bold text-xl text-blue-900">TRESTON HUBERLUS</span>
      </div>
      <nav class="space-x-6 font-medium text-gray-700">
        <a href="index.html" class="hover:text-blue-500">Accueil</a>
        <a href="#about" class="hover:text-blue-500">À propos</a>
        <a href="#services" class="hover:text-blue-500">Services</a>
        <a href="capability.html" class="hover:text-blue-500">Capability Statement</a>
        <a href="#contact" class="hover:text-blue-500">Contact</a>
      </nav>
    </div>
  </header>

  <!-- Hero -->
  <section class="bg-gradient-to-r from-blue-900 to-green-700 text-white text-center h-screen flex flex-col justify-center items-center">
    <h1 class="text-4xl md:text-6xl font-bold">TRESTON HUBERLUS Invest & Co.,Ltd</h1>
    <p class="mt-4 text-lg md:text-2xl">Durabilité • Innovation • Fiabilité • Croissance</p>
    <a href="#services" class="mt-6 bg-white text-blue-900 px-6 py-3 rounded-lg shadow-lg font-semibold hover:bg-gray-200">Nos Services</a>
  </section>

  <!-- About -->
  <section id="about" class="max-w-6xl mx-auto py-16 px-6">
    <h2 class="text-3xl font-bold text-blue-900 mb-6">À propos de nous</h2>
    <p class="text-lg leading-relaxed">
      TRESTON HUBERLUS Invest & Co.,Ltd est une entreprise spécialisée dans l’immobilier, la construction et les travaux publics.
      Nous nous engageons à créer des projets modernes, durables et de haute qualité qui contribuent à la croissance économique
      et au bien-être des communautés.
    </p>
  </section>

  <!-- Services -->
  <section id="services" class="bg-gray-100 py-16 px-6">
    <div class="max-w-6xl mx-auto">
      <h2 class="text-3xl font-bold text-blue-900 mb-10">Nos Services</h2>
      <div class="grid md:grid-cols-3 gap-8">
        <div class="bg-white shadow-lg rounded-xl p-6">
          <h3 class="text-xl font-semibold text-green-700 mb-4">Immobilier</h3>
          <p>Développement et gestion de projets immobiliers modernes et durables.</p>
        </div>
        <div class="bg-white shadow-lg rounded-xl p-6">
          <h3 class="text-xl font-semibold text-green-700 mb-4">Construction</h3>
          <p>Conception et réalisation de bâtiments résidentiels, commerciaux et industriels.</p>
        </div>
        <div class="bg-white shadow-lg rounded-xl p-6">
          <h3 class="text-xl font-semibold text-green-700 mb-4">Travaux publics</h3>
          <p>Infrastructure urbaine, routes, ponts et aménagements pour le développement durable.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Contact -->
  <section id="contact" class="max-w-6xl mx-auto py-16 px-6">
    <h2 class="text-3xl font-bold text-blue-900 mb-6">Contactez-nous</h2>
    <p class="mb-4">Vous souhaitez collaborer avec nous ou en savoir plus sur nos services ?</p>
    <p class="mb-2">📧 Email : contact@treston-huberlus.com</p>
    <p class="mb-2">📞 Téléphone : +243859105718, +243811431593</p>
    <p>🏢 Adresse : [08,Avenue Esanga, Quartier CPA Mushie, Quartier Mbudi-Terminus, Commune de Mont-Ngafula, Kinshasa, République Démocratique du Congo]</p>
  </section>

  <!-- Footer -->
  <footer class="bg-gray-900 text-white text-center py-4">
    © 2025 TRESTON HUBERLUS Invest & Co.,Ltd. Tous droits réservés.
  </footer>

</body>
</html>

<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mentions légales & Politique de confidentialité - TRESTON HUBERLUS Invest & Co.,Ltd</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    const translations = {
      fr: {
        title: "Mentions légales & Politique de confidentialité",
        legal: "Mentions légales",
        legalText: `
          <p><strong>Raison sociale :</strong> TRESTON HUBERLUS Invest & Co.,Ltd</p>
          <p><strong>Secteurs d'activité :</strong> Immobilier, Construction, Travaux publics</p>
          <p><strong>Siège social :</strong> [08, Avenue Esanga, Quartier CPA Mushie, Localité de Mbudi, Commune de Mont-Ngafula]</p>
          <p><strong>Email :</strong> contact@treston-huberlus.com</p>
          <p><strong>Téléphone :</strong> +243859105718, +243811431593</p>
        `,
        privacy: "Politique de confidentialité",
        privacyText: `
          <p>Nous respectons la confidentialité de vos données personnelles.</p>
          <p>Les informations collectées via ce site sont utilisées uniquement à des fins professionnelles (prise de contact, collaboration, partenariats).</p>
          <p>Aucune donnée n’est partagée avec des tiers sans votre consentement.</p>
          <p>Conformément à la loi, vous disposez d’un droit d’accès, de rectification et de suppression de vos données.</p>
        `
      },
      en: {
        title: "Legal Notice & Privacy Policy",
        legal: "Legal Notice",
        legalText: `
          <p><strong>Company name:</strong> TRESTON HUBERLUS Invest & Co.,Ltd</p>
          <p><strong>Business sectors:</strong> Real Estate, Construction, Public Works</p>
          <p><strong>Head office:</strong> [08, Avenue Esanga, Quartier CPA Mushie, Localité de Mbudi, Commune de Mont-Ngafula]</p>
          <p><strong>Email:</strong> contact@treston-huberlus.com</p>
          <p><strong>Phone:</strong> +243859105718, +243811431593</p>
        `,
        privacy: "Privacy Policy",
        privacyText: `
          <p>We respect the confidentiality of your personal data.</p>
          <p>Information collected via this site is used solely for professional purposes (contact, collaboration, partnerships).</p>
          <p>No data is shared with third parties without your consent.</p>
          <p>In accordance with applicable law, you have the right to access, correct, and delete your data.</p>
        `
      }
    };

    function switchLang(lang) {
      const t = translations[lang];
      document.getElementById("title").innerText = t.title;
      document.getElementById("legal").innerText = t.legal;
      document.getElementById("legalText").innerHTML = t.legalText;
      document.getElementById("privacy").innerText = t.privacy;
      document.getElementById("privacyText").innerHTML = t.privacyText;
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

    <section>
      <h2 id="legal" class="text-2xl font-semibold text-green-700"></h2>
      <div id="legalText" class="space-y-2"></div>
    </section>

    <section>
      <h2 id="privacy" class="text-2xl font-semibold text-green-700"></h2>
      <div id="privacyText" class="space-y-2"></div>
    </section>
  </main>

  <!-- Footer -->
  <footer class="bg-gray-900 text-white text-center p-4">
    © 2025 TRESTON HUBERLUS Invest & Co.,Ltd. All rights reserved.
  </footer>
</body>
</html>

<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Capability Statement - TRESTON HUBERLUS Invest & Co.,Ltd</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    const translations = {
      fr: {
        title: "Capability Statement",
        intro: "Présentation de l’entreprise",
        introText: "TRESTON HUBERLUS Invest & Co.,Ltd est un acteur international dans l’immobilier, la construction et les travaux publics. Nous accompagnons les gouvernements, les institutions et les investisseurs privés dans des projets d’envergure, en mettant en avant la durabilité, l’innovation et la fiabilité.",
        expertise: "Domaines d’expertise",
        expertiseList: `
          <li>Développement immobilier résidentiel et commercial</li>
          <li>Grandes infrastructures et travaux publics</li>
          <li>Construction durable & éco-responsable</li>
          <li>Investissements et partenariats stratégiques</li>
        `,
        values: "Valeurs fondamentales",
        valuesList: `
          <li>Durabilité : projets respectueux de l’environnement</li>
          <li>Innovation : technologies modernes et ingénierie avancée</li>
          <li>Fiabilité : respect des délais et des standards internationaux</li>
          <li>Croissance : création de valeur pour nos partenaires</li>
        `,
        stats: "Chiffres clés",
        statsData: `
          <li>+15 ans d’expérience cumulée</li>
          <li>+50 projets achevés avec succès</li>
          <li>+10 partenaires internationaux</li>
          <li>Présence dans 4 continents</li>
        `,
        markets: "Présence internationale & marchés cibles",
        marketsText: "Notre expertise s’étend en Afrique, en Europe, en Asie et en Amérique. Nous collaborons avec des acteurs publics et privés pour répondre aux besoins en infrastructures, logements et investissements stratégiques.",
        references: "Références & clients institutionnels",
        referencesText: "Nous avons travaillé avec des gouvernements, des institutions financières, des banques de développement et des entreprises privées dans des projets de construction, de rénovation et d’investissement.",
        certifications: "Certifications & conformité",
        certificationsText: "Nous respectons les normes internationales de qualité et de sécurité (ISO 9001, ISO 14001, normes anti-corruption, conformité RGPD).",
        contact: "Contact institutionnel",
        contactText: `
          <p><strong>Email :</strong> contact@treston-huberlus.com</p>
          <p><strong>Téléphone :</strong> +243859105718, +243811431593</p>
          <p><strong>Siège social :</strong> [08, Avenue Esanga, Quartier CPA Mushie, Localité de Mbudi, Commune de Mont-Ngafula]</p>
        `,
        download: "Télécharger le Corporate Profile (PDF)"
      },
      en: {
        title: "Capability Statement",
        intro: "Company Overview",
        introText: "TRESTON HUBERLUS Invest & Co.,Ltd is an international player in real estate, construction, and public works. We support governments, institutions, and private investors in large-scale projects, emphasizing sustainability, innovation, and reliability.",
        expertise: "Areas of Expertise",
        expertiseList: `
          <li>Residential & commercial real estate development</li>
          <li>Large-scale infrastructure and public works</li>
          <li>Sustainable & eco-friendly construction</li>
          <li>Investments and strategic partnerships</li>
        `,
        values: "Core Values",
        valuesList: `
          <li>Sustainability: environmentally responsible projects</li>
          <li>Innovation: modern technologies and advanced engineering</li>
          <li>Reliability: compliance with deadlines and international standards</li>
          <li>Growth: creating value for our partners</li>
        `,
        stats: "Key Figures",
        statsData: `
          <li>15+ years of combined experience</li>
          <li>50+ successfully completed projects</li>
          <li>10+ international partners</li>
          <li>Presence across 4 continents</li>
        `,
        markets: "International Presence & Target Markets",
        marketsText: "Our expertise extends to Africa, Europe, Asia, and the Americas. We collaborate with public and private stakeholders to meet infrastructure, housing, and strategic investment needs.",
        references: "References & Institutional Clients",
        referencesText: "We have worked with governments, financial institutions, development banks, and private companies on construction, renovation, and investment projects.",
        certifications: "Certifications & Compliance",
        certificationsText: "We comply with international quality and safety standards (ISO 9001, ISO 14001, anti-corruption standards, GDPR compliance).",
        contact: "Institutional Contact",
        contactText: `
          <p><strong>Email:</strong> contact@treston-huberlus.com</p>
          <p><strong>Phone:</strong> +243859105718, +243811431593</p>
          <p><strong>Head office:</strong> [08, Avenue Esanga, Quartier CPA Mushie, Localité de Mbudi, Commune de Mont-Ngafula]</p>
        `,
        download: "Download Corporate Profile (PDF)"
      }
    };

    function switchLang(lang) {
      const t = translations[lang];
      document.getElementById("title").innerText = t.title;
      document.getElementById("intro").innerText = t.intro;
      document.getElementById("introText").innerText = t.introText;
      document.getElementById("expertise").innerText = t.expertise;
      document.getElementById("expertiseList").innerHTML = t.expertiseList;
      document.getElementById("values").innerText = t.values;
      document.getElementById("valuesList").innerHTML = t.valuesList;
      document.getElementById("stats").innerText = t.stats;
      document.getElementById("statsData").innerHTML = t.statsData;
      document.getElementById("markets").innerText = t.markets;
      document.getElementById("marketsText").innerText = t.marketsText;
      document.getElementById("references").innerText = t.references;
      document.getElementById("referencesText").innerText = t.referencesText;
      document.getElementById("certifications").innerText = t.certifications;
      document.getElementById("certificationsText").innerText = t.certificationsText;
      document.getElementById("contact").innerText = t.contact;
      document.getElementById("contactText").innerHTML = t.contactText;
      document.getElementById("download").innerText = t.download;
    }

    window.onload = () => switchLang("fr");

    function downloadPDF() {
      window.print();
    }
  </script>
</head>
<body class="bg-gray-50 text-gray-800 font-sans">

  <!-- Header -->
  <header class="bg-white shadow-md p-4 flex justify-between items-center">
    <img src="logo.png" alt="Logo" class="h-12">
    <nav class="space-x-6">
      <a href="index.html" class="text-gray-700 hover:text-blue-700">Accueil</a>
      <a href="capability.html" class="text-blue-700 font-bold">Capability Statement</a>
      <a href="mentions.html" class="text-gray-700 hover:text-blue-700">Mentions légales</a>
    </nav>
    <div>
      <button onclick="switchLang('fr')" class="px-2">FR</button> | 
      <button onclick="switchLang('en')" class="px-2">EN</button>
    </div>
  </header>

  <!-- Main -->
  <main class="max-w-5xl mx-auto p-6 space-y-10">
    <h1 id="title" class="text-4xl font-bold text-blue-900"></h1>

    <section>
      <h2 id="intro" class="text-2xl font-semibold text-green-700"></h2>
      <p id="introText" class="mt-2"></p>
    </section>

    <section>
      <h2 id="expertise" class="text-2xl font-semibold text-green-700"></h2>
      <ul id="expertiseList" class="list-disc list-inside mt-2 space-y-1"></ul>
    </section>

    <section>
      <h2 id="values" class="text-2xl font-semibold text-green-700"></h2>
      <ul id="valuesList" class="list-disc list-inside mt-2 space-y-1"></ul>
    </section>

    <section>
      <h2 id="stats" class="text-2xl font-semibold text-green-700"></h2>
      <ul id="statsData" class="list-disc list-inside mt-2 space-y-1"></ul>
    </section>

    <section>
      <h2 id="markets" class="text-2xl font-semibold text-green-700"></h2>
      <p id="marketsText" class="mt-2"></p>
    </section>

    <section>
      <h2 id="references" class="text-2xl font-semibold text-green-700"></h2>
      <p id="referencesText" class="mt-2"></p>
    </section>

    <section>
      <h2 id="certifications" class="text-2xl font-semibold text-green-700"></h2>
      <p id="certificationsText" class="mt-2"></p>
    </section>

    <section>
      <h2 id="contact" class="text-2xl font-semibold text-green-700"></h2>
      <div id="contactText" class="mt-2"></div>
    </section>

    <div class="text-center mt-6">
      <button id="download" onclick="downloadPDF()" class="bg-blue-700 text-white px-6 py-2 rounded shadow-lg hover:bg-blue-900"></button>
    </div>
  </main>

  <!-- Footer -->
  <footer class="bg-gray-900 text-white text-center p-4">
    © 2025 TRESTON HUBERLUS Invest & Co.,Ltd. All rights reserved.
  </footer>
</body>
</html>

# 🌍 TRESTON HUBERLUS Invest & Co., Ltd
**Entreprise de Construction & Immobilier – Kinshasa, RDC**

---

## 🚀 Notre Mission
Construire l’avenir à travers des projets durables, innovants et attractifs pour les investisseurs.

- 🏗️ **BTP & Infrastructures modernes**  
- 🏠 **Immobilier durable et rentable**  
- 🌐 **Projets d’investissement internationaux**  
- 💼 **Partenariats stratégiques pour le développement**  

---

## 📂 Nos Dépôts GitHub
- [🏢 Site officiel – version 1](https://github.com/tresorcrispin74-web/treston-huber-lus-site)  
- [🏢 Site officiel – version 2](https://github.com/tresorcrispin74-web/treston-huberlus-site)  

---

## 📞 Contact
- 📧 Email : **contact@treston-huberlus.com**  
- 📍 Kinshasa, République Démocratique du Congo  
- 🔗 LinkedIn : [TRESTON HUBERLUS](#)  

---

> 💡 *Nous croyons en un avenir où l’innovation et la construction créent des opportunités durables pour l’Afrique et le monde.*

# 🌐 Site officiel – TRESTON HUBERLUS Invest & Co., Ltd

## 📖 Description
Ce dépôt contient le **site web officiel** de l’entreprise **TRESTON HUBERLUS Invest & Co., Ltd**, spécialisée dans :  
- 🏗️ Construction (BTP)  
- 🏠 Immobilier  
- 🌐 Investissements et projets internationaux  

## 🚀 Objectif
Présenter nos services, nos projets et attirer :  
- des investisseurs  
- des partenaires  
- des clients à l’échelle internationale  

## 🛠️ Technologies utilisées
- HTML5  
- CSS3  
- JavaScript  

## 🌍 Mise en ligne
Ce site sera hébergé via **GitHub Pages** et accessible à tous.  

## 📞 Contact
📧 contact@treston-huberlus.com

https://tresorcrispin74-web.github.io/nom-du-depot

# 🌐 Site officiel – TRESTON HUBERLUS Invest & Co., Ltd

## 📖 Description
Ce dépôt contient le **site web officiel** de l’entreprise **TRESTON HUBERLUS Invest & Co., Ltd**, spécialisée dans :  
- 🏗️ Construction (BTP)  
- 🏠 Immobilier  
- 🌐 Investissements et projets internationaux  

## 🚀 Objectif
Présenter nos services, nos projets et attirer :  
- des investisseurs  
- des partenaires  
- des clients à l’échelle internationale  

## 🛠️ Technologies utilisées
- HTML5  
- CSS3  
- JavaScript  

## 🌍 Mise en ligne
Ce site sera hébergé via **GitHub Pages** et accessible à tous.  

## 📞 Contact
📧 contact@treston-huberlus.com

# 🌍 TRESTON HUBERLUS Invest & Co., Ltd
**Entreprise de Construction & Immobilier – Kinshasa, RDC**

---

## 🚀 Notre Mission
Construire l’avenir à travers des projets durables, innovants et attractifs pour les investisseurs.

- 🏗️ **BTP & Infrastructures modernes**  
- 🏠 **Immobilier durable et rentable**  
- 🌐 **Projets d’investissement internationaux**  
- 💼 **Partenariats stratégiques pour le développement**  

---

## 📂 Nos Dépôts GitHub
- [🏢 Site officiel – version 1](https://github.com/tresorcrispin74-web/treston-huber-lus-site)  
- [🏢 Site officiel – version 2](https://github.com/tresorcrispin74-web/treston-huberlus-site)  

---

## 📞 Contact
- 📧 Email : **contact@treston-huberlus.com**  
- 📞 Téléphone : **+243 859 105 718 / +243 811 431 518**  
- 📍 Adresse : **08, Avenue Esanga, Quartier CPA Mushie, Localité de Mbudi,  
  Commune de Mont-Ngafula, Kinshasa 1, R.D. Congo**  
- 🔗 LinkedIn : [TRESTON HUBERLUS](#)  

---

> 💡 *Nous croyons en un avenir où l’innovation et la construction créent des opportunités durables pour l’Afrique et le monde.*

# 🌐 Site officiel – TRESTON HUBERLUS Invest & Co., Ltd

## 📖 Description
Ce dépôt contient le **site web officiel** de l’entreprise **TRESTON HUBERLUS Invest & Co., Ltd**, spécialisée dans :  
- 🏗️ Construction (BTP)  
- 🏠 Immobilier  
- 🌐 Investissements et projets internationaux  

## 🚀 Objectif
Présenter nos services, nos projets et attirer :  
- des investisseurs  
- des partenaires  
- des clients à l’échelle internationale  

## 🛠️ Technologies utilisées
- HTML5  
- CSS3  
- JavaScript  

## 🌍 Mise en ligne
Ce site sera hébergé via **GitHub Pages** et accessible à tous.  

## 📞 Contact
- 📧 Email : **contact@treston-huberlus.com**  
- 📞 Téléphone : **+243 859 105 718 / +243 811 431 518**  
- 📍 Adresse : **08, Avenue Esanga, Quartier CPA Mushie, Localité de Mbudi,  
  Commune de Mont-Ngafula, Kinshasa 1, R.D. Congo**

/assets
   /css
      style.css
   /img
      (logos, images, photos de projets)
   /js
      script.js
index.html
about.html
services.html
projects.html
contact.html

/assets
   /css/style.css
   /img/ (logo + images si tu veux en ajouter)
index.html

/* ====== RESET ====== */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: Arial, sans-serif;
  line-height: 1.6;
  color: #333;
}

/* ====== HEADER ====== */
header {
  background: #111;
  color: #fff;
  padding: 15px 0;
  position: fixed;
  width: 100%;
  top: 0;
  z-index: 1000;
}

header .container {
  display: flex;
  justify-content: space-between;
  align-items: center;
  width: 90%;
  margin: auto;
}

header .logo {
  font-size: 20px;
  font-weight: bold;
}

header nav ul {
  list-style: none;
  display: flex;
  gap: 20px;
}

header nav a {
  color: #fff;
  text-decoration: none;
  font-weight: bold;
}

header nav a:hover {
  color: #f39c12;
}

/* ====== HERO ====== */
.hero {
  height: 100vh;
  background: url('../img/bg.jpg') no-repeat center center/cover;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  color: #fff;
  padding: 0 20px;
}

.hero h2 {
  font-size: 2.5rem;
  margin-bottom: 15px;
}

.hero .btn {
  display: inline-block;
  padding: 10px 20px;
  background: #f39c12;
  color: #fff;
  border-radius: 5px;
  text-decoration: none;
  margin-top: 10px;
}

.hero .btn:hover {
  background: #d35400;
}

/* ====== SECTIONS ====== */
.section {
  padding: 80px 20px;
  width: 90%;
  margin: auto;
}

.section h2 {
  text-align: center;
  margin-bottom: 20px;
  font-size: 2rem;
}

.bg-light {
  background: #f4f4f4;
}

/* ====== CARDS ====== */
.services-grid, .projects-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 20px;
  margin-top: 30px;
}

.card {
  background: #fff;
  padding: 20px;
  border-radius: 10px;
  box-shadow: 0px 2px 5px rgba(0,0,0,0.1);
  text-align: center;
}

/* ====== FOOTER ====== */
footer {
  background: #111;
  color: #fff;
  text-align: center;
  padding: 20px 0;
}

/assets
   /css/style.css
   /img/ (logos, photos de projets, arrière-plans)
   /js/script.js (facultatif)
/index.html        → Accueil
/about.html        → À propos
/services.html     → Services
/projects.html     → Projets
/contact.html      → Contact

<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Contact - TRESTON HUBERLUS</title>
  <link rel="stylesheet" href="assets/css/style.css">
</head>
<body>
  <header>
    <div class="container">
      <h1 class="logo">TRESTON HUBERLUS</h1>
      <nav>
        <ul>
          <li><a href="index.html">Accueil</a></li>
          <li><a href="about.html">À propos</a></li>
          <li><a href="services.html">Services</a></li>
          <li><a href="projects.html">Projets</a></li>
          <li><a href="contact.html" class="active">Contact</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <section class="section bg-light">
    <div class="container">
      <h2>Contactez-nous</h2>
      <p><strong>Email :</strong> contact@treston-huberlus.com</p>
      <p><strong>Téléphone :</strong> +243 859 105 718 / +243 811 431 518</p>
      <p><strong>Adresse :</strong> 08, Avenue Esanga, Quartier CPA Mushie, Localité de Mbudi,<br>
        Commune de Mont-Ngafula, Kinshasa 1, R.D. Congo</p>
    </div>
  </section>

  <footer>
    <div class="container">
      <p>&copy; 2025 TRESTON HUBERLUS Invest & Co., Ltd.</p>
    </div>
  </footer>
</body>
</html>

https://tresorcrispin74-web.github.io/treston-huberlus-site/

http://tresorcrispin74-web.github.io/nom-du-depot

https://tresorcrispin74-web.github.io/treston-huberlus-site/
<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>TRESTON HUBERLUS Invest & Co.,Ltd</title>
  <!-- Tailwind CSS -->
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gray-50 text-gray-800 font-sans">

  <!-- Header -->
  <header class="bg-white shadow-md p-4 flex justify-between items-center">
    <img src="logo.png" alt="Logo" class="h-12">
    <div>
      <button onclick="switchLang('fr')" class="px-2">FR</button>
      <button onclick="switchLang('en')" class="px-2">EN</button>
    </div>
  </header>

  <!-- Hero -->
  <section class="bg-gradient-to-r from-blue-900 to-green-700 text-white text-center h-screen flex flex-col justify-center items-center">
    <h1 class="text-4xl md:text-6xl font-bold">TRESTON HUBERLUS Invest & Co.,Ltd</h1>
    <p class="mt-4 text-lg md:text-2xl">Durabilité • Innovation • Fiabilité • Croissance</p>
    <a href="#services" class="mt-6 bg-white text-blue-900 px-6 py-3 rounded-lg shadow-lg font-semibold hover:bg-gray-200">Nos Services</a>
  </section>

  <!-- Sections dynamiques -->
  <main class="max-w-5xl mx-auto p-6 space-y-8">
    <h1 id="title" class="text-3xl font-bold text-blue-900"></h1>

    <section>
      <h2 id="legal" class="text-2xl font-semibold text-green-700"></h2>
      <div id="legalText" class="space-y-2"></div>
    </section>

    <section>
      <h2 id="privacy" class="text-2xl font-semibold text-green-700"></h2>
      <div id="privacyText" class="space-y-2"></div>
    </section>
  </main>

  <!-- Script multilingue -->
  <script>
    const translations = {
      fr: {
        title: "Mentions Légales",
        legal: "Informations Légales",
        legalText: `
          <p>TRESTON HUBERLUS Invest & Co.,Ltd est une entreprise spécialisée dans l’immobilier, la construction et les travaux publics.</p>
          <p>Nous respectons toutes les lois applicables en matière de protection des données.</p>
        `,
        privacy: "Politique de Confidentialité",
        privacyText: `
          <p>Aucune donnée n’est partagée avec des tiers sans votre consentement.</p>
          <p>Vous avez le droit d’accéder, de corriger et de supprimer vos données.</p>
        `
      },
      en: {
        title: "Legal Notices",
        legal: "Legal Information",
        legalText: `
          <p>TRESTON HUBERLUS Invest & Co.,Ltd is a company specialized in real estate, construction, and public works.</p>
          <p>We comply with all applicable data protection laws.</p>
        `,
        privacy: "Privacy Policy",
        privacyText: `
          <p>No data is shared with third parties without your consent.</p>
          <p>You have the right to access, correct, and delete your data.</p>
        `
      }
    };

    function switchLang(lang) {
      const t = translations[lang];
      document.getElementById("title").innerText = t.title;
      document.getElementById("legal").innerText = t.legal;
      document.getElementById("legalText").innerHTML = t.legalText;
      document.getElementById("privacy").innerText = t.privacy;
      document.getElementById("privacyText").innerHTML = t.privacyText;
    }

    window.onload = () => switchLang("fr");
  </script>
</body>
</html>
<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>TRESTON HUBERLUS Invest & Co., Ltd</title>
  <link rel="stylesheet" href="assets/css/style.css">
</head>
<body>

  <!-- Header -->
  <header>
    <div class="logo">TRESTON HUBERLUS</div>
    <nav>
      <a href="index.html">Accueil</a>
      <a href="about.html">À propos</a>
      <a href="services.html">Services</a>
      <a href="projects.html">Projets</a>
      <a href="contact.html">Contact</a>
    </nav>
  </header>

  <!-- Hero -->
  <section class="hero">
    <h1>TRESTON HUBERLUS Invest & Co., Ltd</h1>
    <p>Durabilité • Innovation • Fiabilité • Croissance</p>
    <a href="#services" class="btn btn-primary">Nos Services</a>
    <a href="#contact" class="btn btn-secondary">Demander un devis</a>
  </section>

  <!-- Footer -->
  <footer>
    © 2025 TRESTON HUBERLUS Invest & Co., Ltd. Tous droits réservés.
  </footer>

</body>
</html>