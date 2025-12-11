<!--
Landing page prêt à l'emploi pour vendre le livre "Apprendre HTML et CSS"
Fichier : LandingPage_Apprendre_HTML_CSS.html
Auteur : Oumar Konè
Instructions :
 - Remplace les liens PAYPAL_LINK, GUMROAD_LINK et SAMPLE_PDF par tes propres URL.
 - Pour activer un paiement PayPal, suis les instructions PayPal ou colle le lien Gumroad.
 - Héberge ce fichier (avec le PDF de l'extrait) sur ton site ou Netlify/GitHub Pages.
-->

<!doctype html>
<html lang="fr">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Apprendre HTML & CSS — Livre par Oumar Konè</title>
  <meta name="description" content="Apprenez à créer des sites web modernes avec HTML & CSS. Guide pas à pas + projets pratiques. Auteur : Oumar Konè (Ségou, Mali).">
  <!-- Favicons simples -->
  <link rel="icon" href="data:;base64,iVBORw0KGgo=">
  <link rel="stylesheet" href="style.css">
  <!-- Styles: moderne, responsive, accessible -->
</head>
<body>
  <main class="wrap" role="main">
    <!-- HERO -->
    <section class="hero" aria-labelledby="titre">
      <div class="hero-grid">
        <div>
          <h1 id="titre">Apprendre HTML & CSS<br><span class="small">De l’initiation aux projets pratiques</span></h1>
          <p class="subtitle">Un guide pas à pas pour débutants : structure, styles, responsive et projets réels. Comprend des exercices et un extrait gratuit.</p>

          <div class="cta-row" role="region" aria-label="Appels à l'action">
            <!-- BUTTON: Acheter (Gumroad example) -->
            <a class="btn btn-primary" href="https://gumroad.com/l/YOUR_GUMROAD_ID" target="_blank" rel="noopener noreferrer" aria-label="Acheter le livre sur Gumroad">
              Acheter maintenant — <span class="price">7,99 €</span>
            </a>

            <!-- BUTTON: Acheter via PayPal (instructions placeholder) -->
            <a class="btn btn-outline" href="#buy-paypal" aria-label="Acheter via PayPal">
              Acheter via PayPal
            </a>

            <!-- BUTTON: Télécharger extrait gratuit -->
            <a class="btn" href="doc/Apprendre_HTML_CSS_extrait.pdf" download aria-label="Télécharger un extrait gratuit">
              Télécharger l'extrait (Chapitre 1)
            </a>
          </div>

          <div class="cards">
            <div class="card">
              <div class="feature">
                <div class="badge">01</div>
                <div>
                  <h3>Pour qui ?</h3>
                  <p class="small">Débutants, enseignants, étudiants et toute personne souhaitant créer son premier site web.</p>
                </div>
              </div>
            </div>

            <div class="card">
              <div class="feature">
                <div class="badge">02</div>
                <div>
                  <h3>Ce que vous apprendrez</h3>
                  <p class="small">HTML de base, formulaires, CSS moderne, Flexbox, Grid, responsive design et projets pratiques.</p>
                </div>
              </div>
            </div>

            <div class="card">
              <div class="feature">
                <div class="badge">03</div>
                <div>
                  <h3>Format</h3>
                  <p class="small">PDF (téléchargeable) – option future : EPUB / impression à la demande.</p>
                </div>
              </div>
            </div>
          </div>

          <!-- Social proof small -->
          <p class="small" style="margin-top:12px">Contact : <a href="mailto:konnehamara980@gmail.com">konnehamara980@gmail.com</a> • Téléphone : +223 79 96 61 83</p>

        </div>

        <aside aria-label="Visuel du livre" style="display:flex;align-items:center;justify-content:center">
          <div style="width:220px;">
            <!-- Mockup: simple CSS-based cover -->
            <div style="border-radius:12px;overflow:hidden;box-shadow:0 12px 30px rgba(2,6,23,0.6);background:linear-gradient(180deg,#6ee7b7,#8b5cf6);padding:20px;color:#071224;text-align:center">
              <section class="cover">
                <img src="ima/Capture d'écran 2025-09-16 051851.png" alt="Couverture du livre">
                <h2 style="margin:6px 0 0 0;font-size:20px">Apprendre</h2>
                <h1 style="margin:4px 0 8px 0;font-size:18px;letter-spacing:0.6px">HTML & CSS</h1>
                <p><strong>Auteur :</strong> Oumar Konè</p>
              </section>
            </div>
            <div style="margin-top:14px;text-align:center">
              <div style="display:inline-block;padding:10px 14px;background:rgba(255,255,255,0.04);border-radius:10px">Prix : <strong>7,99 €</strong></div>
            </div>
          </div>
        </aside>

      </div>
    </section>

    <!-- Preview + Purchase details -->
    <section class="two-col" aria-labelledby="details">
      <div>
        <div class="preview">
          <h3 id="details">Aperçu (extrait de code)</h3>
          <pre>&lt;<span class="kou">!-- Exemple : structure de base --</span>&gt;
&lt;<span class="kou1">!DOCTYPE</span> <span class="kou2">html</span>&gt;
&lt;<span class="kou1">html</span> <span class="kou4">lang=</span><span class="kou3">"fr"</span>&gt;
  &lt;<span class="kou1">head</span>&gt;
    &lt;<span class="kou1">meta</span> <span class="kou4">charset=</span><span class="kou3">"UTF-8"</span>&gt;
    &lt;<span class="kou1">meta</span> <span class="kou2">name=</span>"viewport" <span class="kou4">content=</span>"width<span class="kou4">=device</span>-<br>    ,initial-<span class="kou4">scale=1</span>"&gt;
    &lt;<span class="kou1">title</span>&gt;Ma page&lt;<span class="kou1">/title</span>&gt;
  &lt;<span class="kou1">/head</span>&gt;
  &lt;<span class="kou1">body</span>&gt;
    &lt;<span class="kou1">h1</span>&gt;Bonjour&lt;<span class="kou1">/h1</span>&gt;
    &lt;<span class="kou1">p</span>&gt;Bienvenue sur ma première page web.&lt;<span class="kou1">/p</span>&gt;
  &lt;<span class="kou1">/body</span>&gt;
&lt;<span class="kou1">/html</span>&gt;
</pre>
        </div>

        <div class="testimonials" aria-label="Avis lecteurs">
          <div class="quote">
            <strong>"Clair et pratique."</strong>
            <div class="small">— Fatou, étudiante en informatique</div>
          </div>
          <div class="quote">
            <strong>"Parfait pour débuter."</strong>
            <div class="small">— Ibrahim, formateur</div>
          </div>
        </div>
      </div>

      <aside>
        <div class="card" style="position:sticky;top:24px">
          <h3>Acheter / Télécharger</h3>
          <p class="small">Choisis ta méthode de paiement :</p>

          <!-- Payment options (placeholders) -->
          <div style="display:flex;flex-direction:column;gap:8px;margin-top:8px">
            <!-- Gumroad -->
            <a class="btn btn-primary" href="https://gumroad.com/l/YOUR_GUMROAD_ID" target="_blank" rel="noopener noreferrer">Acheter (Gumroad) — 7,99 €</a>

            <!-- PayPal: si tu utilises PayPal 'Buy now' link, place it here -->
            <form action="https://www.paypal.com/cgi-bin/webscr" method="post" target="_blank" id="buy-paypal">
              <!-- Exemple rapide : remplace BUSINESS et ITEM_NAME et AMOUNT -->
              <input type="hidden" name="cmd" value="_xclick">
              <input type="hidden" name="business" value="YOUR_PAYPAL_EMAIL">
              <input type="hidden" name="item_name" value="Apprendre HTML & CSS - PDF">
              <input type="hidden" name="amount" value="7.99">
              <input type="hidden" name="currency_code" value="EUR">
              <button class="btn btn-outline" type="submit">Acheter (PayPal)</button>
            </form>

            <!-- Direct download (after payment) : mettre le lien sécurisé ici -->
            <a class="btn" href="doc/Apprendre_HTML_CSS_extrait.pdf" download>Télécharger l'extrait</a>

            <!-- Contact & licence -->
            <p class="small" style="margin-top:10px">Contact pour les commandes en gros ou questions : <a href="mailto:konnehamara980@gmail.com">konnehamara980@gmail.com</a></p>
          </div>
        </div>

        <div class="card" style="margin-top:14px">
          <h3>Ce que contient le livre</h3>
          <ul class="small">
            <li>Chapitres 1–7 : HTML et CSS</li>
            <li>Partie 3 : 3 projets pratiques (page perso, carte de visite, portfolio)</li>
            <li>Exercices et solutions</li>
            <li>Ressources et liens pour aller plus loin</li>
          </ul>
        </div>
      </aside>
    </section>

    <footer>
      © 2025 • Oumar Konè • Ségou, Mali • <a href="mailto:konnehamara980@gmail.com">konnehamara980@gmail.com</a>
    </footer>
  </main>

  <!-- Petit script: Remplacer les liens par tes vrais liens, vérifier forms -->
  <script>
    // NOTE pour l'auteur : Remplace YOUR_GUMROAD_ID et YOUR_PAYPAL_EMAIL
    // Exemple Gumroad : https://gumroad.com/l/TON_ID
    // Si tu veux un mode 'livraison automatique' après paiement, utilise Gumroad ou PayPal IPN / webhooks.

    // Simple analytics hint (non intrusif) : envoi d'un event console (optionnel)
    document.querySelectorAll('.btn-primary').forEach(btn=>btn.addEventListener('click',()=>console.log('achat_click')));
  </script>
</body>
</html>