<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Lycée Privé KENNTNIS (LPK) – Enseignement Général, Technique & Professionnel</title>
  <meta name="description" content="Lycée Privé KENNTNIS – Établissement d'excellence à Bobo-Dioulasso. Formations générales, techniques et professionnelles. Année 2026-2027." />
  <meta property="og:title" content="Lycée Privé KENNTNIS (LPK)" />
  <meta property="og:description" content="Excellence académique, technique et professionnelle au service de votre réussite." />
  <meta name="theme-color" content="#0D47A1" />
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;500;600;700;800;900&display=swap" rel="stylesheet" />
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css" />
  <style>
    /* ===== RESET & BASE ===== */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    html {
      scroll-behavior: smooth;
    }
    body {
      font-family: 'Montserrat', sans-serif;
      background: #f5f7fa;
      color: #1e1e2a;
      line-height: 1.6;
    }
    a {
      text-decoration: none;
      color: inherit;
    }
    ul {
      list-style: none;
    }
    .container {
      max-width: 1200px;
      margin: 0 auto;
      padding: 0 24px;
    }
    :root {
      --bleu: #0D47A1;
      --bleu-clair: #1565C0;
      --rouge: #C62828;
      --rouge-clair: #E53935;
      --blanc: #ffffff;
      --gris-clair: #f5f7fa;
      --gris-border: #e9ecf0;
      --ombre: 0 10px 30px rgba(0, 0, 0, 0.06);
      --ombre-hover: 0 20px 40px rgba(0, 0, 0, 0.10);
      --transition: all 0.3s cubic-bezier(0.25, 0.46, 0.45, 0.94);
    }

    .btn {
      display: inline-block;
      background: var(--bleu);
      color: #fff;
      padding: 14px 34px;
      border-radius: 60px;
      font-weight: 700;
      font-size: 1rem;
      border: none;
      cursor: pointer;
      transition: var(--transition);
      box-shadow: 0 4px 14px rgba(13, 71, 161, 0.30);
      text-align: center;
      letter-spacing: 0.3px;
    }
    .btn:hover {
      background: #0a2f6a;
      transform: translateY(-3px);
      box-shadow: 0 10px 25px rgba(13, 71, 161, 0.35);
    }
    .btn-rouge {
      background: var(--rouge);
      box-shadow: 0 4px 14px rgba(198, 40, 40, 0.30);
    }
    .btn-rouge:hover {
      background: #9e1a1a;
      box-shadow: 0 10px 25px rgba(198, 40, 40, 0.35);
    }
    .btn-outline {
      background: transparent;
      color: var(--bleu);
      border: 2px solid var(--bleu);
      box-shadow: none;
    }
    .btn-outline:hover {
      background: var(--bleu);
      color: #fff;
      transform: translateY(-3px);
      box-shadow: 0 10px 25px rgba(13, 71, 161, 0.20);
    }
    .section-title {
      font-size: 2.4rem;
      font-weight: 800;
      color: var(--bleu);
      margin-bottom: 0.5rem;
      text-align: center;
      letter-spacing: -0.5px;
    }
    .section-subtitle {
      text-align: center;
      color: #5a5a7a;
      margin-bottom: 3rem;
      font-size: 1.1rem;
      font-weight: 400;
    }
    .section-badge {
      display: inline-block;
      background: rgba(13, 71, 161, 0.10);
      color: var(--bleu);
      font-size: 0.75rem;
      font-weight: 700;
      padding: 6px 18px;
      border-radius: 40px;
      text-transform: uppercase;
      letter-spacing: 0.8px;
      margin-bottom: 0.8rem;
    }

    /* ===== NAVIGATION ===== */
    .navbar {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      background: rgba(255, 255, 255, 0.97);
      backdrop-filter: blur(12px);
      box-shadow: 0 2px 20px rgba(0, 0, 0, 0.06);
      z-index: 999;
      padding: 10px 0;
      transition: var(--transition);
    }
    .navbar .container {
      display: flex;
      align-items: center;
      justify-content: space-between;
      flex-wrap: wrap;
    }
    .nav-logo {
      display: flex;
      align-items: center;
      gap: 12px;
    }
    .logo-icon {
      width: 44px;
      height: 44px;
      background: linear-gradient(135deg, var(--bleu), var(--bleu-clair));
      border-radius: 14px;
      display: flex;
      align-items: center;
      justify-content: center;
      color: #fff;
      font-weight: 900;
      font-size: 1.3rem;
      box-shadow: 0 4px 10px rgba(13, 71, 161, 0.25);
      position: relative;
    }
    .logo-icon::after {
      content: '';
      position: absolute;
      top: -4px;
      right: -4px;
      width: 16px;
      height: 16px;
      background: var(--rouge);
      border-radius: 50%;
      border: 2px solid #fff;
    }
    .logo-text {
      font-size: 1.4rem;
      font-weight: 900;
      color: var(--bleu);
      line-height: 1.1;
    }
    .logo-text span {
      color: var(--rouge);
    }
    .logo-text small {
      display: block;
      font-size: 0.55rem;
      font-weight: 500;
      color: #777;
      letter-spacing: 0.5px;
      margin-top: -2px;
    }
    .nav-menu {
      display: flex;
      align-items: center;
      gap: 1.6rem;
    }
    .nav-menu a {
      font-weight: 600;
      font-size: 0.9rem;
      color: #2d2d3f;
      transition: var(--transition);
      position: relative;
    }
    .nav-menu a:hover {
      color: var(--bleu);
    }
    .nav-menu a::after {
      content: '';
      position: absolute;
      bottom: -4px;
      left: 0;
      width: 0;
      height: 2.5px;
      background: var(--rouge);
      transition: var(--transition);
      border-radius: 4px;
    }
    .nav-menu a:hover::after {
      width: 100%;
    }
    .nav-btn-inscrire {
      background: var(--rouge);
      color: #fff !important;
      padding: 8px 24px;
      border-radius: 40px;
      font-weight: 700;
      box-shadow: 0 4px 12px rgba(198, 40, 40, 0.25);
    }
    .nav-btn-inscrire:hover {
      background: #9e1a1a;
      transform: scale(1.03);
    }
    .nav-btn-inscrire::after {
      display: none !important;
    }
    .nav-toggle {
      display: none;
      font-size: 1.6rem;
      color: var(--bleu);
      cursor: pointer;
    }

    /* ===== HERO ===== */
    .hero {
      margin-top: 74px;
      min-height: 85vh;
      background: linear-gradient(145deg, #0a2a5e 0%, #0D47A1 50%, #1565C0 100%);
      display: flex;
      align-items: center;
      position: relative;
      overflow: hidden;
      padding: 40px 0;
    }
    .hero::before {
      content: '';
      position: absolute;
      top: -30%;
      right: -10%;
      width: 60%;
      height: 120%;
      background: radial-gradient(ellipse, rgba(255, 255, 255, 0.06) 0%, transparent 70%);
      pointer-events: none;
    }
    .hero::after {
      content: '';
      position: absolute;
      bottom: -20%;
      left: -10%;
      width: 50%;
      height: 80%;
      background: radial-gradient(ellipse, rgba(255, 255, 255, 0.04) 0%, transparent 70%);
      pointer-events: none;
    }
    .hero-content {
      position: relative;
      z-index: 2;
      max-width: 720px;
    }
    .hero-content .year-badge {
      display: inline-block;
      background: rgba(255, 255, 255, 0.15);
      backdrop-filter: blur(6px);
      padding: 6px 20px;
      border-radius: 40px;
      font-size: 0.8rem;
      font-weight: 600;
      color: #ffd54f;
      letter-spacing: 0.5px;
      margin-bottom: 1rem;
      border: 1px solid rgba(255, 255, 255, 0.10);
    }
    .hero-content h1 {
      font-size: 3.6rem;
      font-weight: 900;
      line-height: 1.15;
      margin-bottom: 0.3rem;
      color: #fff;
    }
    .hero-content h1 span {
      color: #ffd54f;
    }
    .hero-content .sous-titre {
      font-size: 1.4rem;
      font-weight: 500;
      color: rgba(255, 255, 255, 0.90);
      margin-bottom: 0.8rem;
    }
    .hero-content p {
      font-size: 1.1rem;
      color: rgba(255, 255, 255, 0.85);
      margin: 1.2rem 0 2.2rem;
      max-width: 540px;
      line-height: 1.7;
    }
    .hero-buttons {
      display: flex;
      flex-wrap: wrap;
      gap: 1rem;
    }
    .hero-buttons .btn {
      min-width: 200px;
    }
    .hero-stats {
      display: flex;
      gap: 2.5rem;
      margin-top: 2.8rem;
      color: rgba(255, 255, 255, 0.80);
    }
    .hero-stats .stat {
      display: flex;
      flex-direction: column;
    }
    .hero-stats .stat .number {
      font-size: 1.8rem;
      font-weight: 800;
      color: #fff;
    }
    .hero-stats .stat .label {
      font-size: 0.8rem;
      text-transform: uppercase;
      letter-spacing: 0.5px;
      opacity: 0.7;
    }

    /* ===== SECTIONS GÉNÉRALES ===== */
    section {
      padding: 80px 0;
    }
    section.alt-bg {
      background: var(--gris-clair);
    }

    /* ===== POURQUOI NOUS CHOISIR ===== */
    .why-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 2rem;
    }
    .why-card {
      background: #fff;
      padding: 30px 20px;
      border-radius: 24px;
      text-align: center;
      box-shadow: var(--ombre);
      transition: var(--transition);
      border-bottom: 4px solid transparent;
    }
    .why-card:hover {
      transform: translateY(-12px);
      border-bottom-color: var(--rouge);
      box-shadow: var(--ombre-hover);
    }
    .why-card i {
      font-size: 2.6rem;
      background: linear-gradient(135deg, var(--bleu), var(--bleu-clair));
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      margin-bottom: 0.8rem;
    }
    .why-card h4 {
      font-size: 1rem;
      font-weight: 700;
      color: #1e1e2a;
    }

    /* ===== FORMATIONS ===== */
    .formations-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
      gap: 2.5rem;
    }
    .formation-card {
      background: #fff;
      border-radius: 28px;
      overflow: hidden;
      box-shadow: var(--ombre);
      transition: var(--transition);
    }
    .formation-card:hover {
      transform: translateY(-10px);
      box-shadow: var(--ombre-hover);
    }
    .formation-header {
      height: 140px;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      color: #fff;
      font-size: 2.8rem;
      font-weight: 700;
      gap: 6px;
    }
    .formation-header span {
      font-size: 0.9rem;
      font-weight: 500;
      opacity: 0.9;
    }
    .formation-header.general {
      background: linear-gradient(135deg, #0D47A1, #1e88e5);
    }
    .formation-header.technique {
      background: linear-gradient(135deg, #b71c1c, #e53935);
    }
    .formation-header.professionnel {
      background: linear-gradient(135deg, #1b5e20, #43a047);
    }
    .formation-body {
      padding: 28px 26px 32px;
    }
    .formation-body h3 {
      font-size: 1.5rem;
      color: var(--bleu);
      margin-bottom: 0.3rem;
    }
    .formation-body .badge {
      display: inline-block;
      background: var(--rouge);
      color: #fff;
      font-size: 0.65rem;
      font-weight: 700;
      padding: 4px 14px;
      border-radius: 30px;
      text-transform: uppercase;
      letter-spacing: 0.5px;
      margin-bottom: 0.8rem;
    }
    .formation-body ul {
      margin: 0.8rem 0 1.2rem;
      padding-left: 1.4rem;
      list-style: disc;
      color: #333;
    }
    .formation-body ul li {
      margin-bottom: 4px;
      font-size: 0.95rem;
    }
    .formation-body .avantages {
      background: var(--gris-clair);
      padding: 14px 18px;
      border-radius: 16px;
      margin-top: 0.8rem;
      font-size: 0.9rem;
      display: flex;
      flex-wrap: wrap;
      gap: 6px 16px;
    }
    .formation-body .avantages i {
      color: var(--bleu);
      margin-right: 4px;
    }

    /* ===== ADMISSIONS ===== */
    .admissions-pieces {
      background: #fff;
      border-radius: 28px;
      padding: 44px 48px;
      box-shadow: var(--ombre);
      max-width: 820px;
      margin: 0 auto 2.5rem;
    }
    .admissions-pieces ul {
      list-style: disc;
      padding-left: 1.8rem;
      font-size: 1.05rem;
      line-height: 2.2;
    }
    .admissions-pieces ul li strong {
      color: var(--bleu);
    }
    .admissions-btn-wrap {
      text-align: center;
    }

    /* ===== À PROPOS ===== */
    .apropos-grid {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 3.5rem;
      align-items: start;
    }
    .apropos-text p {
      font-size: 1.05rem;
      margin-bottom: 1.5rem;
      color: #2d2d3f;
    }
    .valeurs-list {
      display: flex;
      flex-wrap: wrap;
      gap: 10px;
      margin-top: 1rem;
    }
    .valeurs-list span {
      background: var(--bleu);
      color: #fff;
      padding: 6px 20px;
      border-radius: 40px;
      font-weight: 600;
      font-size: 0.8rem;
      letter-spacing: 0.3px;
    }
    .engagements-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(140px, 1fr));
      gap: 1.2rem;
      margin-top: 1.5rem;
    }
    .engagements-grid .item {
      background: #fff;
      padding: 18px 12px;
      border-radius: 18px;
      text-align: center;
      box-shadow: var(--ombre);
      font-weight: 600;
      font-size: 0.9rem;
      transition: var(--transition);
      color: #1e1e2a;
    }
    .engagements-grid .item:hover {
      background: var(--bleu);
      color: #fff;
      transform: scale(1.03);
    }
    .enseignants-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(170px, 1fr));
      gap: 2rem;
      margin-top: 2.5rem;
    }
    .enseignant-card {
      background: #fff;
      border-radius: 24px;
      padding: 30px 16px;
      text-align: center;
      box-shadow: var(--ombre);
      transition: var(--transition);
      border-top: 4px solid var(--rouge);
    }
    .enseignant-card:hover {
      transform: translateY(-8px);
      box-shadow: var(--ombre-hover);
    }
    .enseignant-card i {
      font-size: 2.8rem;
      color: var(--bleu);
      margin-bottom: 0.5rem;
    }
    .enseignant-card h4 {
      font-weight: 700;
      font-size: 1rem;
      color: #1e1e2a;
    }
    .enseignant-card p {
      font-size: 0.8rem;
      color: #777;
    }

    /* ===== GALERIE ===== */
    .galerie-filtres {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 0.8rem;
      margin-bottom: 2.5rem;
    }
    .galerie-filtres button {
      background: #fff;
      border: none;
      padding: 8px 24px;
      border-radius: 40px;
      font-weight: 600;
      font-size: 0.8rem;
      box-shadow: var(--ombre);
      cursor: pointer;
      transition: var(--transition);
      color: #2d2d3f;
    }
    .galerie-filtres button.active,
    .galerie-filtres button:hover {
      background: var(--bleu);
      color: #fff;
    }
    .galerie-grid {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
      gap: 1.5rem;
    }
    .galerie-item {
      border-radius: 22px;
      box-shadow: var(--ombre);
      aspect-ratio: 1/1;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      color: #fff;
      font-size: 1rem;
      font-weight: 600;
      transition: var(--transition);
      padding: 16px;
      text-align: center;
    }
    .galerie-item:hover {
      transform: scale(1.04);
      box-shadow: var(--ombre-hover);
    }
    .galerie-item i {
      font-size: 3rem;
      margin-bottom: 0.6rem;
      opacity: 0.9;
    }
    .galerie-item[data-cat="salle"] {
      background: linear-gradient(135deg, #0D47A1, #42A5F5);
    }
    .galerie-item[data-cat="tp"] {
      background: linear-gradient(135deg, #b71c1c, #ef5350);
    }
    .galerie-item[data-cat="labo"] {
      background: linear-gradient(135deg, #1b5e20, #66BB6A);
    }
    .galerie-item[data-cat="eleves"] {
      background: linear-gradient(135deg, #e65100, #FFB74D);
    }
    .galerie-item[data-cat="activites"] {
      background: linear-gradient(135deg, #4a148c, #AB47BC);
    }
    .galerie-item[data-cat="examens"] {
      background: linear-gradient(135deg, #00695C, #26A69A);
    }
    .galerie-item[data-cat="diplomes"] {
      background: linear-gradient(135deg, #3e2723, #8D6E63);
    }
    .galerie-item[data-cat="culture"] {
      background: linear-gradient(135deg, #bf360c, #FF7043);
    }

    /* ===== ACTUALITÉS ===== */
    .actus-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
      gap: 2rem;
    }
    .actus-card {
      background: #fff;
      border-radius: 24px;
      padding: 28px;
      box-shadow: var(--ombre);
      transition: var(--transition);
    }
    .actus-card:hover {
      transform: translateY(-8px);
      box-shadow: var(--ombre-hover);
    }
    .actus-card .date {
      color: var(--rouge);
      font-weight: 700;
      font-size: 0.8rem;
      text-transform: uppercase;
      letter-spacing: 0.5px;
    }
    .actus-card h4 {
      margin: 0.6rem 0 0.3rem;
      color: var(--bleu);
      font-size: 1.2rem;
    }
    .actus-card p {
      color: #555;
      font-size: 0.95rem;
    }

    /* ===== CONTACT ===== */
    .contact-wrap {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 3rem;
    }
    .contact-form input,
    .contact-form textarea {
      width: 100%;
      padding: 15px 20px;
      border: 2px solid var(--gris-border);
      border-radius: 16px;
      font-family: inherit;
      font-size: 1rem;
      margin-bottom: 1rem;
      transition: var(--transition);
      background: #fff;
    }
    .contact-form input:focus,
    .contact-form textarea:focus {
      border-color: var(--bleu);
      outline: none;
      box-shadow: 0 0 0 4px rgba(13, 71, 161, 0.08);
    }
    .contact-form textarea {
      min-height: 140px;
      resize: vertical;
    }
    .contact-infos {
      background: #fff;
      padding: 36px 32px;
      border-radius: 28px;
      box-shadow: var(--ombre);
    }
    .contact-infos p {
      margin-bottom: 0.9rem;
      display: flex;
      align-items: center;
      gap: 14px;
      font-size: 0.95rem;
    }
    .contact-infos i {
      width: 28px;
      color: var(--bleu);
      font-size: 1.2rem;
      text-align: center;
    }
    .map-placeholder {
      margin-top: 2rem;
      background: linear-gradient(135deg, #e8ecf0, #d5dae0);
      border-radius: 20px;
      height: 180px;
      display: flex;
      align-items: center;
      justify-content: center;
      color: #555;
      font-weight: 500;
      font-size: 0.95rem;
      gap: 10px;
    }

    /* ===== BOUTONS FLOTTANTS ===== */
    .floating-buttons {
      position: fixed;
      bottom: 28px;
      right: 28px;
      display: flex;
      flex-direction: column;
      gap: 14px;
      z-index: 999;
    }
    .floating-buttons a {
      display: flex;
      align-items: center;
      justify-content: center;
      width: 60px;
      height: 60px;
      border-radius: 50%;
      background: var(--bleu);
      color: #fff;
      font-size: 1.8rem;
      box-shadow: 0 8px 25px rgba(0, 0, 0, 0.18);
      transition: var(--transition);
    }
    .floating-buttons a:hover {
      transform: scale(1.08);
    }
    .floating-buttons .whatsapp {
      background: #25D366;
    }

    /* ===== BACK TO TOP ===== */
    .back-top {
      position: fixed;
      bottom: 120px;
      right: 34px;
      background: var(--bleu);
      color: #fff;
      width: 46px;
      height: 46px;
      border-radius: 50%;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 1.2rem;
      box-shadow: var(--ombre);
      opacity: 0;
      visibility: hidden;
      transition: var(--transition);
      z-index: 99;
    }
    .back-top.visible {
      opacity: 1;
      visibility: visible;
    }
    .back-top:hover {
      background: var(--rouge);
    }

    /* ===== FOOTER ===== */
    .footer {
      background: #0a1a2e;
      color: #c8d0dc;
      padding: 60px 0 24px;
    }
    .footer-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 2.5rem;
      margin-bottom: 2.5rem;
    }
    .footer-grid h4 {
      color: #fff;
      margin-bottom: 1.2rem;
      font-size: 1.05rem;
      font-weight: 700;
    }
    .footer-grid p,
    .footer-grid a {
      font-size: 0.9rem;
      line-height: 2.2;
      color: #b0bccf;
      transition: var(--transition);
    }
    .footer-grid a:hover {
      color: #fff;
    }
    .footer-grid .footer-logo {
      display: flex;
      align-items: center;
      gap: 12px;
      margin-bottom: 0.8rem;
    }
    .footer-grid .footer-logo .logo-icon {
      width: 40px;
      height: 40px;
      font-size: 1.1rem;
    }
    .footer-grid .footer-logo .logo-text {
      font-size: 1.2rem;
      color: #fff;
    }
    .footer-grid .footer-logo .logo-text small {
      color: #8899b0;
    }
    .footer-social a {
      display: inline-block;
      margin-right: 14px;
      font-size: 1.2rem;
      color: #b0bccf;
      transition: var(--transition);
    }
    .footer-social a:hover {
      color: #fff;
      transform: translateY(-2px);
    }
    .footer-bottom {
      border-top: 1px solid #1e3150;
      padding-top: 1.8rem;
      text-align: center;
      font-size: 0.85rem;
      color: #8899b0;
    }
    .footer-bottom a {
      color: #ffd54f;
    }

    /* ===== RESPONSIVE ===== */
    @media (max-width: 992px) {
      .apropos-grid {
        grid-template-columns: 1fr;
      }
      .contact-wrap {
        grid-template-columns: 1fr;
      }
    }
    @media (max-width: 768px) {
      .nav-menu {
        display: none;
        flex-direction: column;
        width: 100%;
        background: #fff;
        padding: 1.2rem 0;
        box-shadow: 0 16px 40px rgba(0, 0, 0, 0.08);
        border-radius: 0 0 20px 20px;
      }
      .nav-menu.open {
        display: flex;
      }
      .nav-toggle {
        display: block;
      }
      .hero-content h1 {
        font-size: 2.4rem;
      }
      .hero-content .sous-titre {
        font-size: 1.1rem;
      }
      .hero-stats {
        flex-wrap: wrap;
        gap: 1.5rem;
      }
      .section-title {
        font-size: 2rem;
      }
      .admissions-pieces {
        padding: 28px 24px;
      }
      .floating-buttons a {
        width: 52px;
        height: 52px;
        font-size: 1.5rem;
      }
    }
    @media (max-width: 480px) {
      .hero {
        min-height: 70vh;
      }
      .hero-content h1 {
        font-size: 1.9rem;
      }
      .btn {
        padding: 12px 24px;
        font-size: 0.9rem;
      }
      .formations-grid {
        grid-template-columns: 1fr;
      }
      .galerie-grid {
        grid-template-columns: repeat(auto-fill, minmax(150px, 1fr));
      }
    }

    /* ===== REVEAL ===== */
    .reveal {
      opacity: 0;
      transform: translateY(40px);
      transition: all 0.8s cubic-bezier(0.2, 0.9, 0.3, 1);
    }
    .reveal.active {
      opacity: 1;
      transform: translateY(0);
    }
  </style>
</head>
<body>

  <!-- ===== NAVIGATION ===== -->
  <nav class="navbar" id="navbar">
    <div class="container">
      <div class="nav-logo">
        <div class="logo-icon">LPK</div>
        <div class="logo-text">
          KENNTNIS <span>▪</span>
          <small>Lycée Privé Conventionné</small>
        </div>
      </div>
      <div class="nav-toggle" id="navToggle"><i class="fas fa-bars"></i></div>
      <ul class="nav-menu" id="navMenu">
        <li><a href="#accueil">Accueil</a></li>
        <li><a href="#formations">Formations</a></li>
        <li><a href="#admissions">Admissions</a></li>
        <li><a href="#apropos">À propos</a></li>
        <li><a href="#galerie">Galerie</a></li>
        <li><a href="#actualites">Actualités</a></li>
        <li><a href="#contact">Contact</a></li>
        <li><a href="#admissions" class="nav-btn-inscrire">S'inscrire</a></li>
      </ul>
    </div>
  </nav>

  <!-- ===== HERO ===== -->
  <section class="hero" id="accueil">
    <div class="container">
      <div class="hero-content">
        <div class="year-badge"><i class="fas fa-calendar-alt"></i> Année scolaire 2026 – 2027</div>
        <h1>Lycée Privé <span>KENNTNIS</span></h1>
        <p class="sous-titre">Établissement Privé Conventionné d'Enseignement Général, Technique &amp; Professionnel</p>
        <p>Préparez votre avenir grâce à un enseignement d'excellence, un encadrement rigoureux et des formations adaptées aux exigences du supérieur et du monde professionnel.</p>
        <div class="hero-buttons">
          <a href="#formations" class="btn">Découvrir nos formations</a>
          <a href="#admissions" class="btn btn-rouge">S'inscrire maintenant</a>
        </div>
        <div class="hero-stats">
          <div class="stat"><span class="number">10+</span><span class="label">Filières</span></div>
          <div class="stat"><span class="number">95%</span><span class="label">Réussite aux examens</span></div>
          <div class="stat"><span class="number">50+</span><span class="label">Enseignants expérimentés</span></div>
        </div>
      </div>
    </div>
  </section>

  <!-- ===== POURQUOI NOUS CHOISIR ===== -->
  <section id="pourquoi" class="alt-bg">
    <div class="container">
      <div class="section-badge reveal">Nos atouts</div>
      <h2 class="section-title reveal">Pourquoi choisir le LPK ?</h2>
      <p class="section-subtitle reveal">Des valeurs et des engagements qui font la différence</p>
      <div class="why-grid">
        <div class="why-card reveal"><i class="fas fa-chart-line"></i><h4>Évaluations régulières</h4></div>
        <div class="why-card reveal"><i class="fas fa-users-cog"></i><h4>Travaux dirigés</h4></div>
        <div class="why-card reveal"><i class="fas fa-tools"></i><h4>Travaux pratiques toute l'année</h4></div>
        <div class="why-card reveal"><i class="fas fa-chalkboard-teacher"></i><h4>Enseignants expérimentés</h4></div>
        <div class="why-card reveal"><i class="fas fa-hand-holding-heart"></i><h4>Accompagnement des classes d'examen</h4></div>
        <div class="why-card reveal"><i class="fas fa-file-invoice"></i><h4>Frais de dossiers aux examens pris en charge</h4></div>
        <div class="why-card reveal"><i class="fas fa-user-graduate"></i><h4>Encadrement personnalisé</h4></div>
        <div class="why-card reveal"><i class="fas fa-building"></i><h4>Cadre d'apprentissage moderne</h4></div>
        <div class="why-card reveal"><i class="fas fa-trophy"></i><h4>Excellents résultats scolaires</h4></div>
      </div>
    </div>
  </section>

  <!-- ===== NOS FORMATIONS ===== -->
  <section id="formations">
    <div class="container">
      <div class="section-badge reveal">Parcours</div>
      <h2 class="section-title reveal">Nos formations</h2>
      <p class="section-subtitle reveal">Des parcours général, technique et professionnel pour votre réussite</p>
      <div class="formations-grid">
        <!-- Général -->
        <div class="formation-card reveal">
          <div class="formation-header general"><i class="fas fa-graduation-cap"></i><span>Général</span></div>
          <div class="formation-body">
            <span class="badge">Général</span>
            <h3>Enseignement Général</h3>
            <p>Formation de qualité pour réussir le BEPC et le Baccalauréat avec un suivi rigoureux.</p>
            <ul>
              <li><strong>Post-primaire :</strong> 6e, 5e, 4e, 3e</li>
              <li><strong>Secondaire :</strong> Seconde, 1ère A/D, Terminale A/D</li>
            </ul>
            <div class="avantages">
              <span><i class="fas fa-check-circle"></i> Évaluations régulières</span>
              <span><i class="fas fa-check-circle"></i> Travaux dirigés</span>
              <span><i class="fas fa-check-circle"></i> Préparation intensive</span>
              <span><i class="fas fa-check-circle"></i> Frais BEPC pris en charge</span>
            </div>
          </div>
        </div>
        <!-- Technique -->
        <div class="formation-card reveal">
          <div class="formation-header technique"><i class="fas fa-microchip"></i><span>Technique</span></div>
          <div class="formation-body">
            <span class="badge">Technique (LPTIC-B)</span>
            <h3>Enseignement Technique</h3>
            <p>Formation tertiaire et industrielle alliant théorie et pratique.</p>
            <ul>
              <li><strong>Tertiaire :</strong> 2nde AB3, ACC, 1ère G2, Terminale G2</li>
              <li><strong>Industriel :</strong> Génie Civil, Électrotechnique, Maintenance Industrielle, Électronique</li>
              <li>Terminales F2 et F3</li>
            </ul>
            <div class="avantages">
              <span><i class="fas fa-check-circle"></i> TP toute l'année</span>
              <span><i class="fas fa-check-circle"></i> Ateliers équipés</span>
              <span><i class="fas fa-check-circle"></i> Encadrement professionnel</span>
            </div>
          </div>
        </div>
        <!-- Professionnel -->
        <div class="formation-card reveal">
          <div class="formation-header professionnel"><i class="fas fa-briefcase"></i><span>Professionnel</span></div>
          <div class="formation-body">
            <span class="badge">Professionnel</span>
            <h3>Enseignement Professionnel</h3>
            <p>Formation pratique pour une insertion rapide dans le monde du travail.</p>
            <ul>
              <li><strong>Bac Pro :</strong> Maintenance Industrielle, Génie Civil, Électrotechnique</li>
            </ul>
            <div class="avantages">
              <span><i class="fas fa-check-circle"></i> TP toute l'année</span>
              <span><i class="fas fa-check-circle"></i> Ateliers équipés</span>
              <span><i class="fas fa-check-circle"></i> Formation adaptée au marché</span>
            </div>
          </div>
        </div>
      </div>
      <p style="text-align:center;margin-top:2.5rem;font-weight:600;color:var(--bleu);font-size:1.1rem;">
        <i class="fas fa-calendar-alt"></i> Année scolaire 2026 – 2027
      </p>
    </div>
  </section>

  <!-- ===== ADMISSIONS ===== -->
  <section id="admissions" class="alt-bg">
    <div class="container">
      <div class="section-badge reveal">Inscription</div>
      <h2 class="section-title reveal">Admissions 2026-2027</h2>
      <p class="section-subtitle reveal">Conditions d'inscription – Pièces à fournir</p>
      <div class="admissions-pieces reveal">
        <ul>
          <li><strong>Fiche d'inscription</strong> disponible à l'établissement</li>
          <li><strong>Photocopie de l'extrait de naissance</strong> ou jugement supplétif</li>
          <li><strong>Bulletin de notes</strong> de la dernière classe fréquentée</li>
          <li><strong>Quitus de sortie</strong></li>
          <li><strong>Photocopie du CEP</strong> pour l'entrée en 6ème</li>
          <li><strong>Photocopie du BEPC</strong> pour l'entrée en Seconde</li>
        </ul>
      </div>
      <div class="admissions-btn-wrap reveal">
        <a href="#" class="btn btn-rouge" style="font-size:1.15rem;padding:16px 52px;"><i class="fas fa-pen"></i> Commencer mon inscription</a>
      </div>
    </div>
  </section>

  <!-- ===== À PROPOS ===== -->
  <section id="apropos">
    <div class="container">
      <div class="section-badge reveal">Qui sommes-nous ?</div>
      <h2 class="section-title reveal">À propos du LPK</h2>
      <div class="apropos-grid">
        <div class="apropos-text reveal">
          <p>Le <strong>Lycée Privé KENNTNIS</strong> est un établissement privé conventionné situé à Bobo-Dioulasso. Il a pour mission d'offrir un enseignement de qualité dans les domaines général, technique et professionnel afin de former des citoyens compétents, responsables et capables de relever les défis du monde moderne.</p>
          <p><strong>Nos valeurs :</strong></p>
          <div class="valeurs-list">
            <span>Excellence</span><span>Discipline</span><span>Travail</span><span>Respect</span>
            <span>Responsabilité</span><span>Intégrité</span><span>Innovation</span><span>Réussite</span>
          </div>
        </div>
        <div class="reveal">
          <h3 style="color:var(--bleu);margin-bottom:1.2rem;font-size:1.4rem;">Nos engagements</h3>
          <div class="engagements-grid">
            <div class="item">Réussite scolaire</div>
            <div class="item">Formation technique de qualité</div>
            <div class="item">Insertion professionnelle</div>
            <div class="item">Encadrement personnalisé</div>
            <div class="item">Enseignants expérimentés</div>
            <div class="item">Travaux pratiques</div>
            <div class="item">Préparation aux examens</div>
            <div class="item">Éducation citoyenne</div>
          </div>
        </div>
      </div>
      <!-- Enseignants -->
      <div style="margin-top:3.5rem;">
        <h3 class="section-title reveal" style="font-size:1.8rem;">Nos enseignants</h3>
        <p class="section-subtitle reveal">Un corps professoral expérimenté provenant des meilleurs établissements</p>
        <div class="enseignants-grid">
          <div class="enseignant-card reveal"><i class="fas fa-user-tie"></i><h4>LOC</h4><p>Lycée Ouaga</p></div>
          <div class="enseignant-card reveal"><i class="fas fa-user-tie"></i><h4>LMVTD</h4><p>Lycée Moderne</p></div>
          <div class="enseignant-card reveal"><i class="fas fa-user-tie"></i><h4>Mollo Sanou</h4><p>Enseignant expert</p></div>
          <div class="enseignant-card reveal"><i class="fas fa-user-tie"></i><h4>Lycée Scientifique</h4><p>Excellence scientifique</p></div>
          <div class="enseignant-card reveal"><i class="fas fa-user-tie"></i><h4>Lycées des Arrondissements</h4><p>Expérience terrain</p></div>
        </div>
      </div>
    </div>
  </section>

  <!-- ===== GALERIE ===== -->
  <section id="galerie" class="alt-bg">
    <div class="container">
      <div class="section-badge reveal">Visuels</div>
      <h2 class="section-title reveal">Galerie</h2>
      <p class="section-subtitle reveal">Découvrez notre environnement d'apprentissage</p>
      <div class="galerie-filtres reveal">
        <button class="active" data-filter="all">Toutes</button>
        <button data-filter="salle">Salles de classe</button>
        <button data-filter="tp">Travaux pratiques</button>
        <button data-filter="labo">Laboratoires</button>
        <button data-filter="eleves">Élèves</button>
        <button data-filter="activites">Activités</button>
        <button data-filter="examens">Examens</button>
        <button data-filter="diplomes">Remises de diplômes</button>
        <button data-filter="culture">Journées culturelles</button>
      </div>
      <div class="galerie-grid" id="galerieGrid">
        <div class="galerie-item" data-cat="salle"><i class="fas fa-chalkboard"></i><span>Salle de classe</span></div>
        <div class="galerie-item" data-cat="tp"><i class="fas fa-tools"></i><span>TP</span></div>
        <div class="galerie-item" data-cat="labo"><i class="fas fa-flask"></i><span>Laboratoire</span></div>
        <div class="galerie-item" data-cat="eleves"><i class="fas fa-user-graduate"></i><span>Élèves</span></div>
        <div class="galerie-item" data-cat="activites"><i class="fas fa-futbol"></i><span>Activités</span></div>
        <div class="galerie-item" data-cat="examens"><i class="fas fa-pencil-alt"></i><span>Examens</span></div>
        <div class="galerie-item" data-cat="diplomes"><i class="fas fa-award"></i><span>Diplômes</span></div>
        <div class="galerie-item" data-cat="culture"><i class="fas fa-music"></i><span>Culture</span></div>
        <div class="galerie-item" data-cat="salle"><i class="fas fa-door-open"></i><span>Espaces</span></div>
      </div>
    </div>
  </section>

  <!-- ===== ACTUALITÉS ===== -->
  <section id="actualites">
    <div class="container">
      <div class="section-badge reveal">Actualités</div>
      <h2 class="section-title reveal">Actualités</h2>
      <p class="section-subtitle reveal">Les événements marquants du LPK</p>
      <div class="actus-grid">
        <div class="actus-card reveal"><span class="date">Octobre 2026</span><h4>Rentrée scolaire 2026-2027</h4><p>Accueil des élèves dans de nouvelles conditions.</p></div>
        <div class="actus-card reveal"><span class="date">Juillet 2027</span><h4>Résultats des examens</h4><p>Félicitations à nos lauréats du BEPC et du Bac.</p></div>
        <div class="actus-card reveal"><span class="date">Mars 2027</span><h4>Journées portes ouvertes</h4><p>Découvrez nos filières et rencontrez nos équipes.</p></div>
        <div class="actus-card reveal"><span class="date">Avril 2027</span><h4>Concours d'excellence</h4><p>Récompense des meilleurs élèves de l'établissement.</p></div>
        <div class="actus-card reveal"><span class="date">Mai 2027</span><h4>Activités sportives</h4><p>Tournoi inter-classes et compétitions.</p></div>
        <div class="actus-card reveal"><span class="date">Juin 2027</span><h4>Conférences éducatives</h4><p>Thèmes : orientation, métiers, avenir.</p></div>
      </div>
    </div>
  </section>

  <!-- ===== CONTACT ===== -->
  <section id="contact" class="alt-bg">
    <div class="container">
      <div class="section-badge reveal">Nous écrire</div>
      <h2 class="section-title reveal">Contact</h2>
      <p class="section-subtitle reveal">Nous sommes à votre écoute</p>
      <div class="contact-wrap">
        <div class="reveal">
          <form class="contact-form" id="contactForm">
            <input type="text" placeholder="Nom" required />
            <input type="text" placeholder="Prénom" required />
            <input type="tel" placeholder="Téléphone" required />
            <input type="email" placeholder="Email" required />
            <input type="text" placeholder="Sujet" />
            <textarea placeholder="Votre message..." required></textarea>
            <button type="submit" class="btn" style="width:100%;"><i class="fas fa-paper-plane"></i> Envoyer le message</button>
          </form>
        </div>
        <div class="contact-infos reveal">
          <p><i class="fas fa-map-marker-alt"></i> Réserve Zone Artisanale, Secteur 24, à 100 m au Sud du CSPS, Bobo-Dioulasso, Burkina Faso</p>
          <p><i class="fas fa-phone-alt"></i> +226 20 97 25 35</p>
          <p><i class="fas fa-phone-alt"></i> +226 76 61 17 46</p>
          <p><i class="fas fa-phone-alt"></i> +226 71 53 39 02</p>
          <p><i class="fas fa-phone-alt"></i> +226 78 94 33 78</p>
          <p><i class="fas fa-envelope"></i> contact@lpk-bf.com</p>
          <p><i class="fas fa-clock"></i> Lun–Ven 07h30–17h30 · Sam 08h–12h · Dim fermé</p>
          <div class="map-placeholder"><i class="fas fa-map" style="margin-right:8px;"></i> Google Maps – Emplacement du LPK</div>
        </div>
      </div>
    </div>
  </section>

  <!-- ===== BOUTONS FLOTTANTS ===== -->
  <div class="floating-buttons">
    <a href="tel:+22620972535" aria-label="Appeler"><i class="fas fa-phone"></i></a>
    <a href="https://wa.me/22676611746" target="_blank" class="whatsapp" aria-label="WhatsApp"><i class="fab fa-whatsapp"></i></a>
  </div>

  <!-- ===== BACK TO TOP ===== -->
  <a href="#" class="back-top" id="backTop"><i class="fas fa-arrow-up"></i></a>

  <!-- ===== FOOTER ===== -->
  <footer class="footer">
    <div class="container">
      <div class="footer-grid">
        <div>
          <div class="footer-logo">
            <div class="logo-icon">LPK</div>
            <div class="logo-text">
              KENNTNIS <span>▪</span>
              <small>Lycée Privé Conventionné</small>
            </div>
          </div>
          <p>Réserve Zone Artisanale, Secteur 24, Bobo-Dioulasso</p>
          <p><i class="fas fa-phone" style="width:20px;"></i> +226 20 97 25 35</p>
          <p><i class="fas fa-envelope" style="width:20px;"></i> contact@lpk-bf.com</p>
          <div class="footer-social" style="margin-top:0.8rem;">
            <a href="#"><i class="fab fa-facebook-f"></i></a>
            <a href="#"><i class="fab fa-whatsapp"></i></a>
            <a href="#"><i class="fab fa-youtube"></i></a>
          </div>
        </div>
        <div>
          <h4>Navigation</h4>
          <a href="#accueil">Accueil</a><br />
          <a href="#formations">Nos Formations</a><br />
          <a href="#admissions">Admissions</a><br />
          <a href="#apropos">À propos</a><br />
          <a href="#galerie">Galerie</a><br />
          <a href="#actualites">Actualités</a><br />
          <a href="#contact">Contact</a>
        </div>
        <div>
          <h4>Liens utiles</h4>
          <a href="#admissions">Inscription</a><br />
          <a href="#">Mentions légales</a><br />
          <a href="#">Politique de confidentialité</a><br />
          <a href="#">Plan du site</a>
        </div>
        <div>
          <h4>Année scolaire</h4>
          <p style="font-weight:700;color:#ffd54f;">2026 – 2027</p>
          <p style="margin-top:0.5rem;">Bonne et heureuse année scolaire à tous !</p>
        </div>
      </div>
      <div class="footer-bottom">
        © 2027 Lycée Privé KENNTNIS (LPK) – Tous droits réservés.<br />
        Développé par Digital Leaders Academy.
      </div>
    </div>
  </footer>

  <!-- ===== JAVASCRIPT ===== -->
  <script>
    (function() {
      // Menu mobile
      const toggle = document.getElementById('navToggle');
      const menu = document.getElementById('navMenu');
      toggle.addEventListener('click', () => { menu.classList.toggle('open'); });
      document.querySelectorAll('.nav-menu a').forEach(link => {
        link.addEventListener('click', () => { menu.classList.remove('open'); });
      });

      // Sticky navbar & back-top
      window.addEventListener('scroll', () => {
        const nav = document.getElementById('navbar');
        nav.style.boxShadow = window.scrollY > 50 ? '0 4px 25px rgba(0,0,0,0.10)' : '0 2px 20px rgba(0,0,0,0.06)';
        const back = document.getElementById('backTop');
        if (window.scrollY > 400) back.classList.add('visible');
        else back.classList.remove('visible');
      });

      // Scroll reveal
      const reveals = document.querySelectorAll('.reveal');
      const observer = new IntersectionObserver((entries) => {
        entries.forEach(entry => { if (entry.isIntersecting) entry.target.classList.add('active'); });
      }, { threshold: 0.12 });
      reveals.forEach(el => observer.observe(el));

      // Galerie filtres
      const filterBtns = document.querySelectorAll('.galerie-filtres button');
      const items = document.querySelectorAll('.galerie-item');
      filterBtns.forEach(btn => {
        btn.addEventListener('click', () => {
          filterBtns.forEach(b => b.classList.remove('active'));
          btn.classList.add('active');
          const filter = btn.dataset.filter;
          items.forEach(item => {
            item.style.display = (filter === 'all' || item.dataset.cat === filter) ? 'flex' : 'none';
          });
        });
      });

      // Formulaire contact
      document.getElementById('contactForm').addEventListener('submit', function(e) {
        e.preventDefault();
        alert('✅ Votre message a été envoyé avec succès ! (Simulation)');
        this.reset();
      });
    })();
  </script>
</body>
</html>
