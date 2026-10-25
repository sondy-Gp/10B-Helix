
<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="theme-color" content="#0b1020">

    <title>10b Klassengruppe | Unser Klassenportal</title>
    <meta name="description"
          content="Das digitale Klassenportal der 10b – Hausaufgaben, Termine, Materialien und mehr.">

    <style>
        /* =========================================
           1. GRUNDEINSTELLUNGEN
        ========================================= */

        :root {
            --bg: #0b1020;
            --surface: rgba(255, 255, 255, 0.055);
            --surface-hover: rgba(255, 255, 255, 0.09);
            --border: rgba(255, 255, 255, 0.09);
            --text: #f4f6ff;
            --muted: #929bb5;
            --accent: #8b7cff;
            --accent-2: #4cc9f0;
            --radius: 22px;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        html {
            scroll-behavior: smooth;
        }

        body {
            min-height: 100vh;
            font-family: Inter, "Segoe UI", Arial, sans-serif;
            color: var(--text);
            background:
                radial-gradient(ellipse at 10% 0%,
                    rgba(105, 84, 255, 0.15), transparent 40%),
                radial-gradient(ellipse at 90% 30%,
                    rgba(42, 172, 222, 0.08), transparent 35%),
                var(--bg);
            overflow-x: hidden;
        }

        body.modal-open {
            overflow: hidden;
        }

        button, a {
            font: inherit;
        }

        button {
            color: inherit;
        }

        button:focus-visible,
        a:focus-visible {
            outline: 2px solid var(--accent-2);
            outline-offset: 4px;
        }

        /* =========================================
           2. LOADING SCREEN
        ========================================= */

        #preloader {
            position: fixed;
            inset: 0;
            z-index: 1000;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            gap: 20px;
            background: #080c18;
            transition: opacity 0.65s ease, visibility 0.65s ease;
        }

        #preloader.hide {
            opacity: 0;
            visibility: hidden;
            pointer-events: none;
        }

        .loader-logo {
            display: grid;
            place-items: center;
            width: 78px;
            height: 78px;
            border: 1px solid rgba(139, 124, 255, 0.5);
            border-radius: 25px;
            background: linear-gradient(135deg, #8b7cff, #4cc9f0);
            color: #fff;
            font-size: 28px;
            font-weight: 900;
            box-shadow: 0 0 55px rgba(139, 124, 255, 0.25);
            animation: float 2s ease-in-out infinite;
        }

        .loader-welcome {
            font-size: clamp(30px, 6vw, 46px);
            font-weight: 800;
            letter-spacing: -1.5px;
            opacity: 0;
            transform: translateY(12px);
            animation: welcomeIn 0.8s 0.25s forwards;
        }

        .loader-welcome span {
            color: var(--accent);
        }

        .loader-caption {
            color: var(--muted);
            font-size: 13px;
            letter-spacing: 2px;
            text-transform: uppercase;
        }

        .loader-track {
            width: 150px;
            height: 3px;
            overflow: hidden;
            border-radius: 10px;
            background: #202740;
        }

        .loader-progress {
            width: 40%;
            height: 100%;
            border-radius: inherit;
            background: linear-gradient(90deg, var(--accent), var(--accent-2));
            animation: loading 1.4s ease-in-out infinite;
        }

        @keyframes welcomeIn {
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        @keyframes loading {
            from { transform: translateX(-120%); }
            to { transform: translateX(380%); }
        }

        @keyframes float {
            0%, 100% { transform: translateY(0); }
            50% { transform: translateY(-7px); }
        }

        /* =========================================
           3. LAYOUT
        ========================================= */

        .container {
            width: min(1120px, calc(100% - 40px));
            margin-inline: auto;
        }

        .site-header {
            padding-top: 28px;
        }

        .navbar {
            display: flex;
            align-items: center;
            justify-content: space-between;
            gap: 18px;
            padding: 14px 18px;
            border: 1px solid var(--border);
            border-radius: 18px;
            background: rgba(13, 19, 37, 0.72);
            backdrop-filter: blur(18px);
        }

        .brand {
            display: flex;
            align-items: center;
            gap: 12px;
            min-width: 0;
        }

        .brand-icon {
            display: grid;
            place-items: center;
            flex-shrink: 0;
            width: 44px;
            height: 44px;
            border-radius: 14px;
            background: linear-gradient(135deg, #8b7cff, #4cc9f0);
            color: white;
            font-size: 16px;
            font-weight: 900;
        }

        .brand-name {
            font-size: 16px;
            font-weight: 800;
            letter-spacing: -0.4px;
        }

        .brand-subtitle {
            margin-top: 4px;
            color: var(--muted);
            font-size: 11px;
        }

        .nav-status {
            display: flex;
            align-items: center;
            gap: 8px;
            padding: 9px 12px;
            border: 1px solid var(--border);
            border-radius: 999px;
            color: #b9c4d9;
            font-size: 12px;
            white-space: nowrap;
        }

        .status-dot {
            width: 7px;
            height: 7px;
            border-radius: 50%;
            background: #f5c66b;
            box-shadow: 0 0 10px rgba(245, 198, 107, 0.4);
        }

        /* =========================================
           4. HERO-BEREICH
        ========================================= */

        .hero {
            position: relative;
            padding: 76px 0 48px;
            text-align: center;
        }

        .hero-badge {
            display: inline-flex;
            align-items: center;
            gap: 8px;
            padding: 8px 13px;
            border: 1px solid rgba(139, 124, 255, 0.25);
            border-radius: 999px;
            background: rgba(139, 124, 255, 0.08);
            color: #c2baff;
            font-size: 12px;
            font-weight: 600;
        }

        .hero h1 {
            margin-top: 23px;
            font-size: clamp(38px, 7vw, 70px);
            line-height: 1.08;
            letter-spacing: -3px;
            font-weight: 900;
        }

        .gradient-text {
            color: transparent;
            background: linear-gradient(100deg, #a99dff, #62d6f6);
            background-clip: text;
            -webkit-background-clip: text;
        }

        .hero-description {
            max-width: 530px;
            margin: 20px auto 0;
            color: var(--muted);
            font-size: 15px;
            line-height: 1.8;
        }

        .hero-bottom {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 10px;
            margin-top: 26px;
        }

        .hero-chip {
            padding: 9px 13px;
            border: 1px solid var(--border);
            border-radius: 12px;
            background: rgba(255, 255, 255, 0.025);
            color: #c0c8dc;
            font-size: 12px;
        }

        /* =========================================
           5. BEREICHE UND KARTEN
        ========================================= */

        .section-heading {
            display: flex;
            align-items: flex-end;
            justify-content: space-between;
            gap: 20px;
            margin-bottom: 22px;
        }

        .eyebrow {
            margin-bottom: 9px;
            color: var(--accent-2);
            font-size: 11px;
            font-weight: 800;
            letter-spacing: 2px;
            text-transform: uppercase;
        }

        .section-heading h2 {
            font-size: clamp(24px, 4vw, 32px);
            letter-spacing: -1px;
        }

        .section-heading p {
            margin-top: 8px;
            color: var(--muted);
            font-size: 13px;
            line-height: 1.6;
        }

        .section-count {
            color: var(--muted);
            font-size: 12px;
            white-space: nowrap;
        }

        .cards-grid {
            display: grid;
            grid-template-columns: repeat(3, minmax(0, 1fr));
            gap: 16px;
        }

        .section-card {
            position: relative;
            display: flex;
            flex-direction: column;
            align-items: flex-start;
            min-height: 220px;
            padding: 23px;
            overflow: hidden;
            border: 1px solid var(--border);
            border-radius: var(--radius);
            background: var(--surface);
            text-align: left;
            cursor: pointer;
            transition:
                transform 0.25s ease,
                border-color 0.25s ease,
                background 0.25s ease,
                box-shadow 0.25s ease;
        }

        .section-card::before {
            position: absolute;
            top: -55px;
            right: -55px;
            width: 130px;
            height: 130px;
            border-radius: 50%;
            background: var(--card-glow, rgba(139, 124, 255, 0.12));
            filter: blur(35px);
            content: "";
            pointer-events: none;
            transition: opacity 0.25s ease;
        }

        .section-card:hover {
            transform: translateY(-5px);
            border-color: rgba(139, 124, 255, 0.45);
            background: var(--surface-hover);
            box-shadow: 0 16px 40px rgba(0, 0, 0, 0.15);
        }

        .section-card:active {
            transform: scale(0.985);
        }

        .card-icon {
            display: grid;
            place-items: center;
            width: 49px;
            height: 49px;
            border: 1px solid rgba(255, 255, 255, 0.09);
            border-radius: 16px;
            background: var(--icon-bg, rgba(139, 124, 255, 0.12));
            font-size: 23px;
        }

        .card-title {
            margin-top: 21px;
            font-size: 17px;
            font-weight: 750;
            letter-spacing: -0.3px;
        }

        .card-description {
            margin-top: 8px;
            color: var(--muted);
            font-size: 12px;
            line-height: 1.7;
        }

        .card-footer {
            display: flex;
            align-items: center;
            justify-content: space-between;
            width: 100%;
            gap: 10px;
            margin-top: auto;
            padding-top: 22px;
        }

        .coming-tag {
            padding: 6px 9px;
            border: 1px solid rgba(245, 198, 107, 0.15);
            border-radius: 8px;
            background: rgba(245, 198, 107, 0.07);
            color: #e9c984;
            font-size: 10px;
            font-weight: 700;
        }

        .card-arrow {
            color: #9da8c1;
            font-size: 20px;
            transition: transform 0.2s ease;
        }

        .section-card:hover .card-arrow {
            transform: translateX(4px);
        }

        /* Unterschiedliche Akzentfarben */

        .card-homework {
            --card-glow: rgba(139, 124, 255, 0.19);
            --icon-bg: rgba(139, 124, 255, 0.13);
        }

        .card-missed {
            --card-glow: rgba(77, 201, 240, 0.17);
            --icon-bg: rgba(77, 201, 240, 0.12);
        }

        .card-dates {
            --card-glow: rgba(255, 171, 100, 0.16);
            --icon-bg: rgba(255, 171, 100, 0.12);
        }

        .card-contacts {
            --card-glow: rgba(255, 120, 171, 0.15);
            --icon-bg: rgba(255, 120, 171, 0.11);
        }

        .card-materials {
            --card-glow: rgba(102, 224, 174, 0.15);
            --icon-bg: rgba(102, 224, 174, 0.11);
        }

        .card-news {
            --card-glow: rgba(255, 215, 100, 0.15);
            --icon-bg: rgba(255, 215, 100, 0.11);
        }

        .card-mensa {
            --card-glow: rgba(255, 145, 105, 0.16);
            --icon-bg: rgba(255, 145, 105, 0.11);
        }

        /* =========================================
           6. INFO-BEREICH
        ========================================= */

        .info-banner {
            display: flex;
            align-items: center;
            gap: 18px;
            margin-top: 32px;
            padding: 22px;
            border: 1px solid rgba(139, 124, 255, 0.18);
            border-radius: 20px;
            background: linear-gradient(
                110deg,
                rgba(139, 124, 255, 0.09),
                rgba(76, 201, 240, 0.035)
            );
        }

        .info-icon {
            display: grid;
            place-items: center;
            flex-shrink: 0;
            width: 46px;
            height: 46px;
            border-radius: 14px;
            background: rgba(139, 124, 255, 0.12);
            font-size: 21px;
        }

        .info-banner h3 {
            font-size: 14px;
        }

        .info-banner p {
            margin-top: 6px;
            color: var(--muted);
            font-size: 12px;
            line-height: 1.7;
        }

        /* =========================================
           7. FOOTER
        ========================================= */

        .site-footer {
            display: flex;
            align-items: center;
            justify-content: space-between;
            flex-wrap: wrap;
            gap: 14px;
            margin-top: 70px;
            padding: 23px 0 30px;
            border-top: 1px solid var(--border);
            color: var(--muted);
            font-size: 11px;
        }

        .footer-brand {
            color: #d6dbec;
            font-weight: 700;
        }

        .footer-note {
            line-height: 1.7;
        }

        /* =========================================
           8. MODALES FENSTER
        ========================================= */

        .modal-overlay {
            position: fixed;
            inset: 0;
            z-index: 2000;
            display: flex;
            align-items: center;
            justify-content: center;
            padding: 20px;
            background: rgba(3, 6, 16, 0.78);
            backdrop-filter: blur(12px);
            opacity: 0;
            visibility: hidden;
            transition: opacity 0.25s ease, visibility 0.25s ease;
        }

        .modal-overlay.active {
            opacity: 1;
            visibility: visible;
        }

        .modal {
            position: relative;
            width: min(100%, 420px);
            padding: 35px 28px 28px;
            border: 1px solid rgba(255, 255, 255, 0.12);
            border-radius: 26px;
            background:
                radial-gradient(
                    circle at 50% 0%,
                    rgba(139, 124, 255, 0.17),
                    transparent 55%
                ),
                #11182a;
            text-align: center;
            box-shadow: 0 30px 100px rgba(0, 0, 0, 0.45);
            transform: translateY(16px) scale(0.97);
            transition: transform 0.3s cubic-bezier(.2, .8, .2, 1);
        }

        .modal-overlay.active .modal {
            transform: translateY(0) scale(1);
        }

        .modal-close {
            position: absolute;
            top: 14px;
            right: 14px;
            display: grid;
            place-items: center;
            width: 35px;
            height: 35px;
            border: 1px solid var(--border);
            border-radius: 11px;
            background: rgba(255, 255, 255, 0.04);
            color: #aeb8cf;
            font-size: 20px;
            cursor: pointer;
            transition: background 0.2s ease;
        }

        .modal-close:hover {
            background: rgba(255, 255, 255, 0.1);
        }

        .modal-emoji {
            display: grid;
            place-items: center;
            width: 76px;
            height: 76px;
            margin: 0 auto 23px;
            border: 1px solid rgba(139, 124, 255, 0.2);
            border-radius: 24px;
            background: rgba(139, 124, 255, 0.11);
            font-size: 35px;
            animation: float 2.5s ease-in-out infinite;
        }

        .modal h2 {
            font-size: 27px;
            letter-spacing: -0.8px;
        }

        .modal p {
            margin-top: 14px;
            color: var(--muted);
            font-size: 13px;
            line-height: 1.9;
        }

        .modal-highlight {
            color: #c4baff;
            font-weight: 700;
        }

        .modal-button {
            width: 100%;
            margin-top: 25px;
            padding: 14px 18px;
            border: 0;
            border-radius: 13px;
            background: linear-gradient(100deg, #8b7cff, #6c8cff);
            color: white;
            font-size: 13px;
            font-weight: 750;
            cursor: pointer;
            box-shadow: 0 8px 24px rgba(108, 124, 255, 0.18);
            transition: filter 0.2s ease, transform 0.2s ease;
        }

        .modal-button:hover {
            filter: brightness(1.12);
        }

        .modal-button:active {
            transform: scale(0.98);
        }

        /* =========================================
           9. RESPONSIVES DESIGN
        ========================================= */

        @media (max-width: 850px) {
            .cards-grid {
                grid-template-columns: repeat(2, minmax(0, 1fr));
            }

            .hero {
                padding-top: 62px;
            }
        }

        @media (max-width: 520px) {
            .container {
                width: calc(100% - 28px);
            }

            .site-header {
                padding-top: 14px;
            }

            .navbar {
                padding: 12px;
            }

            .brand {
                gap: 9px;
            }

            .brand-icon {
                width: 39px;
                height: 39px;
                border-radius: 12px;
            }

            .brand-name {
                font-size: 14px;
            }

            .brand-subtitle {
                font-size: 10px;
            }

            .nav-status {
                gap: 6px;
                padding: 8px 9px;
                font-size: 10px;
            }

            .hero {
                padding: 56px 0 42px;
            }

            .hero h1 {
                letter-spacing: -1.8px;
            }

            .hero-description {
                font-size: 13px;
            }

            .section-heading {
                align-items: flex-start;
            }

            .section-count {
                padding-top: 3px;
                font-size: 10px;
            }

            .cards-grid {
                gap: 11px;
            }

            .section-card {
                min-height: 211px;
                padding: 15px;
                border-radius: 18px;
            }

            .card-icon {
                width: 43px;
                height: 43px;
                border-radius: 13px;
                font-size: 21px;
            }

            .card-title {
                margin-top: 17px;
                font-size: 14px;
                line-height: 1.4;
            }

            .card-description {
                font-size: 11px;
            }

            .coming-tag {
                padding: 5px 6px;
                font-size: 9px;
            }

            .card-footer {
                padding-top: 17px;
            }

            .info-banner {
                align-items: flex-start;
                padding: 17px;
            }

            .site-footer {
                margin-top: 45px;
            }

            .modal {
                padding: 32px 22px 23px;
            }
        }

        @media (prefers-reduced-motion: reduce) {
            *, *::before, *::after {
                scroll-behavior: auto !important;
                animation-duration: 0.01ms !important;
                animation-iteration-count: 1 !important;
                transition-duration: 0.01ms !important;
            }
        }
    </style>
</head>

<body>

    <!-- =========================================
         LOADING SCREEN
    ========================================== -->

    <div id="preloader" aria-label="Seite wird geladen">
        <div class="loader-logo">10b</div>
        <div class="loader-welcome">
            <span>Willkommen</span>
        </div>
        <div class="loader-caption">Deine Klasse. Dein Portal.</div>
        <div class="loader-track">
            <div class="loader-progress"></div>
        </div>
    </div>

    <!-- =========================================
         HEADER
    ========================================== -->

    <header class="site-header container">
        <nav class="navbar" aria-label="Hauptnavigation">

            <div class="brand">
                <div class="brand-icon" aria-hidden="true">10b</div>

                <div>
                    <div class="brand-name">10b Klassengruppe</div>
                    <div class="brand-subtitle">Das digitale Klassenportal</div>
                </div>
            </div>

            <div class="nav-status">
                <span class="status-dot"></span>
                <span>In Entwicklung</span>
            </div>

        </nav>
    </header>

    <!-- =========================================
         MAIN CONTENT
    ========================================== -->

    <main class="container">

        <!-- Begrüßung -->

        <section class="hero">
            <div class="hero-badge">
                <span>✦</span>
                <span>WILLKOMMEN IM KLASSENPORTAL</span>
            </div>

            <h1>
                Alles für deine<br>
                <span class="gradient-text">10b.</span>
            </h1>

            <p class="hero-description">
                Hausaufgaben, Termine und Materialien – alles an einem Ort.
                Einfacher lernen, besser organisiert sein und nichts mehr verpassen.
            </p>

            <div class="hero-bottom">
                <div class="hero-chip">📚 Lernen</div>
                <div class="hero-chip">📅 Organisieren</div>
                <div class="hero-chip">🤝 Zusammenhalten</div>
            </div>
        </section>

        <!-- Kartenübersicht -->

        <section id="bereiche" aria-labelledby="bereiche-title">

            <div class="section-heading">
                <div>
                    <div class="eyebrow">DEIN ÜBERBLICK</div>
                    <h2 id="bereiche-title">Alle Bereiche</h2>
                    <p>Wähle einen Bereich aus, um mehr zu erfahren.</p>
                </div>

                <div class="section-count">07 BEREICHE</div>
            </div>

            <div class="cards-grid">

                <!-- 1. Hausaufgaben -->
                <button class="section-card card-homework"
                        type="button"
                        data-title="Hausaufgaben"
                        data-emoji="📚">
                    <div class="card-icon">📚</div>
                    <div class="card-title">Hausaufgaben</div>
                    <div class="card-description">
                        Aufgaben, Abgaben und alles, was du bis zur nächsten
                        Stunde erledigen musst.
                    </div>
                    <div class="card-footer">
                        <span class="coming-tag">COMING SOON</span>
                        <span class="card-arrow" aria-hidden="true">↗</span>
                    </div>
                </button>

                <!-- 2. Verpasster Unterricht -->
                <button class="section-card card-missed"
                        type="button"
                        data-title="Was habe ich verpasst?"
                        data-emoji="🤒">
                    <div class="card-icon">🤒</div>
                    <div class="card-title">Was habe ich verpasst?</div>
                    <div class="card-description">
                        Unterrichtsstoff, Notizen und Aufgaben für alle,
                        die einmal gefehlt haben.
                    </div>
                    <div class="card-footer">
                        <span class="coming-tag">COMING SOON</span>
                        <span class="card-arrow" aria-hidden="true">↗</span>
                    </div>
                </button>

                <!-- 3. Termine und Klassenarbeiten -->
                <button class="section-card card-dates"
                        type="button"
                        data-title="Termine & Arbeiten"
                        data-emoji="📅">
                    <div class="card-icon">📅</div>
                    <div class="card-title">Termine & Arbeiten</div>
                    <div class="card-description">
                        Klassenarbeiten, Tests, Abgaben und wichtige
                        Termine immer im Blick.
                    </div>
                    <div class="card-footer">
                        <span class="coming-tag">COMING SOON</span>
                        <span class="card-arrow" aria-hidden="true">↗</span>
                    </div>
                </button>

                <!-- 4. Klassenliste und Kontakte -->
                <button class="section-card card-contacts"
                        type="button"
                        data-title="Klassenliste / Kontakte"
                        data-emoji="👥">
                    <div class="card-icon">👥</div>
                    <div class="card-title">Klassenliste / Kontakte</div>
                    <div class="card-description">
                        Wichtige schulische Kontakte und Ansprechpartner
                        auf einen Blick.
                    </div>
                    <div class="card-footer">
                        <span class="coming-tag">COMING SOON</span>
                        <span class="card-arrow" aria-hidden="true">↗</span>
                    </div>
                </button>

                <!-- 5. Materialien und Links -->
                <button class="section-card card-materials"
                        type="button"
                        data-title="Materialien & Links"
                        data-emoji="📁">
                    <div class="card-icon">📁</div>
                    <div class="card-title">Materialien & Links</div>
                    <div class="card-description">
                        Lernzettel, Präsentationen, hilfreiche Websites
                        und Unterrichtsmaterialien.
                    </div>
                    <div class="card-footer">
                        <span class="coming-tag">COMING SOON</span>
                        <span class="card-arrow" aria-hidden="true">↗</span>
                    </div>
                </button>

                <!-- 6. Ankündigungen -->
                <button class="section-card card-news"
                        type="button"
                        data-title="Ankündigungen"
                        data-emoji="📢">
                    <div class="card-icon">📢</div>
                    <div class="card-title">Ankündigungen</div>
                    <div class="card-description">
                        Wichtige Informationen, Änderungen und Neuigkeiten
                        rund um unsere Klasse.
                    </div>
                    <div class="card-footer">
                        <span class="coming-tag">COMING SOON</span>
                        <span class="card-arrow" aria-hidden="true">↗</span>
                    </div>
                </button>

                <!-- 7. Mensa und Pausenaufsicht -->
                <button class="section-card card-mensa"
                        type="button"
                        data-title="Mensa & Pausenaufsicht"
                        data-emoji="🍕">
                    <div class="card-icon">🍕</div>
                    <div class="card-title">Mensa & Pausenaufsicht</div>
                    <div class="card-description">
                        Informationen zum Mensaessen und zu den
                        eingeteilten Pausendiensten.
                    </div>
                    <div class="card-footer">
                        <span class="coming-tag">COMING SOON</span>
                        <span class="card-arrow" aria-hidden="true">↗</span>
                    </div>
                </button>

            </div>
        </section>

        <!-- Hinweis zum aktuellen Entwicklungsstand -->

        <section class="info-banner" aria-label="Entwicklungsstatus">
            <div class="info-icon">🚀</div>

            <div>
                <h3>Wir arbeiten daran!</h3>
                <p>
                    Das Klassenportal befindet sich noch in der Entwicklung.
                    Die einzelnen Bereiche werden nach und nach freigeschaltet.
                    Schau später wieder vorbei!
                </p>
            </div>
        </section>

    </main>

    <!-- =========================================
         FOOTER
    ========================================== -->

    <footer class="container site-footer">
        <div>
            <div class="footer-brand">10b Klassengruppe</div>
            <div class="footer-note" style="margin-top: 5px;">
                Gemeinsam lernen. Gemeinsam wachsen.
            </div>
        </div>

        <div class="footer-note">
            © <span id="current-year"></span> · Ein Projekt unserer Klasse
        </div>
    </footer>

    <!-- =========================================
         COMING SOON MODAL
    ========================================== -->

    <div class="modal-overlay"
         id="coming-soon-modal"
         role="presentation"
         aria-hidden="true">

        <div class="modal"
             role="dialog"
             aria-modal="true"
             aria-labelledby="modal-title"
             aria-describedby="modal-description">

            <button class="modal-close"
                    id="modal-close"
                    type="button"
                    aria-label="Fenster schließen">×</button>

            <div class="modal-emoji" id="modal-emoji">🚀</div>

            <h2 id="modal-title">Coming Soon!</h2>

            <p id="modal-description">
                <span class="modal-highlight">
                    Dieser Bereich befindet sich noch in Entwicklung 🚀
                </span>
                <br><br>
                Wir arbeiten daran, diesen Bereich bald verfügbar zu machen.
                Schau einfach später wieder vorbei!
            </p>

            <button class="modal-button"
                    id="modal-ok"
                    type="button">
                Alles klar!
            </button>

        </div>
    </div>

    <script>
        /* =========================================
           1. PRELOADER
           Die Seite wird nach ca. 1,8 Sekunden eingeblendet.
        ========================================== */

        const preloader = document.getElementById("preloader");

        window.addEventListener("load", () => {
            setTimeout(() => {
                preloader.classList.add("hide");
            }, 1800);
        });

        /* =========================================
           2. AKTUELLES JAHR IM FOOTER
        ========================================== */

        document.getElementById("current-year").textContent =
            new Date().getFullYear();

        /* =========================================
           3. MODAL-STEUERUNG
        ========================================== */

        const modal = document.getElementById("coming-soon-modal");
        const modalTitle = document.getElementById("modal-title");
        const modalEmoji = document.getElementById("modal-emoji");
        const closeButton = document.getElementById("modal-close");
        const okButton = document.getElementById("modal-ok");

        // Speichert das Element, das vor dem Öffnen fokussiert war.
        let lastFocusedElement = null;

        // Öffnet das Fenster für den ausgewählten Bereich.
        function openModal(title, emoji) {
            lastFocusedElement = document.activeElement;

            modalTitle.textContent = "Coming Soon!";
            modalEmoji.textContent = emoji || "🚀";

            // Der Bereichsname wird sicher als Text eingefügt.
            // Es wird kein HTML aus Benutzereingaben ausgeführt.
            modal.querySelector(".modal-highlight").textContent =
                "Dieser Bereich befindet sich noch in Entwicklung 🚀";

            modal.classList.add("active");
            modal.setAttribute("aria-hidden", "false");
            document.body.classList.add("modal-open");

            closeButton.focus();
        }

        // Schließt das Fenster und stellt den Fokus wieder her.
        function closeModal() {
            modal.classList.remove("active");
            modal.setAttribute("aria-hidden", "true");
            document.body.classList.remove("modal-open");

            if (lastFocusedElement) {
                lastFocusedElement.focus();
            }
        }

        /* =========================================
           4. ALLE KARTEN AKTIVIEREN
           Jede Karte öffnet dasselbe Coming-Soon-Fenster.
        ========================================== */

        const cards = document.querySelectorAll(".section-card");

        cards.forEach((card) => {
            card.addEventListener("click", () => {
                openModal(
                    card.dataset.title,
                    card.dataset.emoji
                );
            });
        });

        /* =========================================
           5. MODAL SCHLIESSEN
        ========================================== */

        closeButton.addEventListener("click", closeModal);
        okButton.addEventListener("click", closeModal);

        // Klick auf den dunklen Hintergrund schließt das Fenster.
        modal.addEventListener("click", (event) => {
            if (event.target === modal) {
                closeModal();
            }
        });

        // Escape schließt das Fenster ebenfalls.
        document.addEventListener("keydown", (event) => {
            if (
                event.key === "Escape" &&
                modal.classList.contains("active")
            ) {
                closeModal();
            }
        });
    </script>

</body>
</html>
