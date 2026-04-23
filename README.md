# avallecillo.github.io
Personal web page of Antonio Vallecillo
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Antonio Vallecillo — Home Page</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;600&family=Source+Serif+4:ital,wght@0,300;0,400;1,300&display=swap" rel="stylesheet">
  <style>
    :root {
      --ink:       #1a1a2e;
      --muted:     #4a4a6a;
      --accent:    #b5451b;
      --accent2:   #2c6e8a;
      --rule:      #d8d0c4;
      --bg:        #faf8f4;
      --card:      #ffffff;
      --serif:     'Source Serif 4', Georgia, serif;
      --display:   'Playfair Display', Georgia, serif;
    }

    *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

    body {
      background: var(--bg);
      color: var(--ink);
      font-family: var(--serif);
      font-size: 17px;
      line-height: 1.75;
      font-weight: 300;
    }

    /* ── TOP RULE ── */
    .top-rule {
      height: 5px;
      background: linear-gradient(90deg, var(--accent) 0%, var(--accent2) 100%);
    }

    /* ── HEADER ── */
    header {
      max-width: 900px;
      margin: 0 auto;
      padding: 3rem 2rem 2rem;
      display: grid;
      grid-template-columns: auto 1fr auto;
      gap: 2rem;
      align-items: start;
    }

    .photo img {
      width: 160px;
      height: 200px;
      object-fit: cover;
      object-position: top;
      border-radius: 3px;
      box-shadow: 4px 6px 20px rgba(0,0,0,.15);
      display: block;
    }

    .identity h1 {
      font-family: var(--display);
      font-size: 2.4rem;
      font-weight: 600;
      letter-spacing: -.01em;
      color: var(--ink);
      line-height: 1.1;
      margin-bottom: .35rem;
    }

    .identity .affil {
      font-size: .95rem;
      color: var(--muted);
      line-height: 1.6;
    }

    .identity .affil a {
      color: var(--accent2);
      text-decoration: none;
    }
    .identity .affil a:hover { text-decoration: underline; }

    .identity .links {
      margin-top: 1rem;
      display: flex;
      flex-direction: column;
      gap: .3rem;
      font-size: .9rem;
    }

    .identity .links a {
      color: var(--muted);
      text-decoration: none;
      display: flex;
      align-items: center;
      gap: .4rem;
    }
    .identity .links a:hover { color: var(--accent); }

    .identity .links .icon {
      width: 18px;
      height: 18px;
      flex-shrink: 0;
      opacity: .7;
    }

    .logos {
      display: flex;
      flex-direction: column;
      gap: .8rem;
      align-items: flex-end;
      padding-top: .3rem;
    }
    .logos img {
      max-height: 40px;
      max-width: 130px;
      object-fit: contain;
      opacity: .85;
    }
    .logos img:hover { opacity: 1; }

    /* ── DIVIDER ── */
    .divider {
      max-width: 900px;
      margin: 0 auto;
      padding: 0 2rem;
    }
    .divider hr {
      border: none;
      border-top: 1px solid var(--rule);
      margin: .5rem 0 2rem;
    }

    /* ── MAIN ── */
    main {
      max-width: 900px;
      margin: 0 auto;
      padding: 0 2rem 4rem;
    }

    /* ── SECTIONS ── */
    section {
      margin-bottom: 2.5rem;
    }

    section h2 {
      font-family: var(--display);
      font-size: 1.25rem;
      font-weight: 600;
      color: var(--ink);
      margin-bottom: .75rem;
      padding-bottom: .35rem;
      border-bottom: 1px solid var(--rule);
      display: flex;
      align-items: center;
      gap: .5rem;
    }

    section h2 .dot {
      display: inline-block;
      width: 7px;
      height: 7px;
      background: var(--accent);
      border-radius: 50%;
      flex-shrink: 0;
    }

    p { margin-bottom: .9rem; }
    p:last-child { margin-bottom: 0; }

    a { color: var(--accent2); text-decoration: none; }
    a:hover { text-decoration: underline; color: var(--accent); }

    ul {
      padding-left: 1.4rem;
      margin-bottom: .5rem;
    }
    ul li { margin-bottom: .3rem; }
    ul ul { margin-top: .2rem; margin-bottom: .2rem; }

    /* ── AWARD HIGHLIGHT ── */
    .award-box {
      background: linear-gradient(135deg, #fff8f5 0%, #f5f0ff 100%);
      border-left: 3px solid var(--accent);
      padding: .85rem 1.1rem;
      border-radius: 0 4px 4px 0;
      margin: .8rem 0 1rem;
      font-size: .95rem;
    }

    /* ── FURTHER INFO GRID ── */
    .ids-grid {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: .25rem .5rem;
      font-size: .92rem;
    }

    /* ── FOOTER ── */
    footer {
      border-top: 1px solid var(--rule);
      text-align: center;
      padding: 1.5rem 2rem;
      font-size: .82rem;
      color: var(--muted);
    }

    /* ── RESPONSIVE ── */
    @media (max-width: 680px) {
      header {
        grid-template-columns: 1fr;
        gap: 1.2rem;
      }
      .photo img { width: 120px; height: 150px; }
      .logos { flex-direction: row; flex-wrap: wrap; justify-content: flex-start; align-items: center; }
      .ids-grid { grid-template-columns: 1fr; }
    }
  </style>
</head>
<body>

<div class="top-rule"></div>

<!-- ══════════════ HEADER ══════════════ -->
<header>
  <div class="photo">
    <img src="AVallecillo-2024-escalera2.jpg" alt="Antonio Vallecillo">
  </div>

  <div class="identity">
    <h1>Antonio Vallecillo</h1>
    <p class="affil">
      <a href="http://www.uma.es" target="_blank">Universidad de Málaga</a><br>
      <a href="http://www.lcc.uma.es" target="_blank">Dept. Lenguajes y Ciencias de la Computación</a><br>
      <a href="http://www.informatica.uma.es/" target="_blank">ETSI Informática</a>, Campus de Teatinos.<br>
      Bulevar Louis Pasteur, 35 · 29071 <a href="http://en.wikipedia.org/wiki/M%C3%A1laga" target="_blank">Málaga</a>, Spain
      &nbsp;<a href="http://maps.google.es/maps/ms?ie=UTF8&hl=es&msa=0&ll=36.717318,-4.477937&spn=0.017923,0.037251&t=h&z=15&msid=111919763757071472280.000451625a7012a74efb1" target="_blank">[map]</a>
    </p>
    <div class="links">
      <a href="mailto:av@uma.es">
        <!-- email icon -->
        <svg class="icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.6"><rect x="2" y="4" width="20" height="16" rx="2"/><path d="M2 7l10 7 10-7"/></svg>
        av@uma.es
      </a>
      <a href="http://twitter.com/AVallecillo" target="_blank">
        <svg class="icon" viewBox="0 0 24 24" fill="currentColor"><path d="M18.244 2.25h3.308l-7.227 8.26 8.502 11.24H16.17l-5.214-6.817L4.99 21.75H1.68l7.73-8.835L1.254 2.25H8.08l4.713 6.231zm-1.161 17.52h1.833L7.084 4.126H5.117z"/></svg>
        @AVallecillo
      </a>
      <a href="https://www.linkedin.com/in/avallecillo" target="_blank">
        <svg class="icon" viewBox="0 0 24 24" fill="currentColor"><path d="M20.447 20.452h-3.554v-5.569c0-1.328-.027-3.037-1.852-3.037-1.853 0-2.136 1.445-2.136 2.939v5.667H9.351V9h3.414v1.561h.046c.477-.9 1.637-1.85 3.37-1.85 3.601 0 4.267 2.37 4.267 5.455v6.286zM5.337 7.433a2.062 2.062 0 01-2.063-2.065 2.064 2.064 0 112.063 2.065zm1.782 13.019H3.555V9h3.564v11.452zM22.225 0H1.771C.792 0 0 .774 0 1.729v20.542C0 23.227.792 24 1.771 24h20.451C23.2 24 24 23.227 24 22.271V1.729C24 .774 23.2 0 22.222 0h.003z"/></svg>
        LinkedIn · AVallecillo
      </a>
      <a href="http://orcid.org/0000-0002-8139-9986" target="_blank">
        <svg class="icon" viewBox="0 0 24 24" fill="currentColor"><path d="M12 0C5.372 0 0 5.372 0 12s5.372 12 12 12 12-5.372 12-12S18.628 0 12 0zm-1.374 4.494h2.748v1.375h-2.748V4.494zm0 3.75h2.748v11.512h-2.748V8.244zm5.25 0h2.75v1.67h.036c.382-.724 1.318-1.67 2.714-1.67.094 0 .188.002.28.008v2.76a5.69 5.69 0 00-.416-.016c-1.554 0-2.364.834-2.364 2.836v5.924h-2.75V8.244z" opacity=".01"/><circle cx="12" cy="12" r="11" fill="none" stroke="currentColor" stroke-width="1.5"/><text x="12" y="16" text-anchor="middle" font-size="8" font-weight="bold" fill="currentColor">iD</text></svg>
        ORCID: 0000-0002-8139-9986
      </a>
      <a href="https://whereby.com/avallecillo" target="_blank">
        <svg class="icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.6"><path d="M15 10l4.553-2.07A1 1 0 0121 8.82v6.36a1 1 0 01-1.447.89L15 14M3 8a2 2 0 012-2h10a2 2 0 012 2v8a2 2 0 01-2 2H5a2 2 0 01-2-2V8z"/></svg>
        whereby.com/avallecillo
      </a>
    </div>
  </div>

  <div class="logos">
    <a href="http://www.gisum.uma.es/" target="_blank"><img src="logos/logoGisum.png" alt="GISUM"></a>
    <a href="http://itis.uma.es/" target="_blank"><img src="logos/LogoITIStransp.png" alt="ITIS"></a>
    <a href="http://atenea.lcc.uma.es" target="_blank"><img src="logos/AteneaLogo.png" alt="Atenea"></a>
    <a href="http://www.sosym.org/" target="_blank"><img src="http://www.sosym.org/banner/sosymed.jpg" alt="SoSyM Editor"></a>
    <a href="http://www.jot.fm/" target="_blank"><img src="logos/JOT-banner-editor.png" alt="JOT Editor"></a>
    <a href="https://www.springer.com/journal/12599" target="_blank"><img src="logos/bise_logo2.PNG" alt="BISE"></a>
  </div>
</header>

<div class="divider"><hr></div>

<!-- ══════════════ MAIN ══════════════ -->
<main>

  <!-- SHORT BIO -->
  <section>
    <h2><span class="dot"></span>Short Bio</h2>
    <p>
      Antonio Vallecillo is a retired Full Professor of Software Engineering at the University of Málaga.
      His research interests include model-based software engineering (MBSE), open distributed processing
      (<a href="http://www.rm-odp.net" target="_blank">ODP</a>), software quality, and uncertainty quantification.
      From 1986 to 1995 he worked in the computer industry at Fujitsu and ICL. In 1996 he joined
      the University of Málaga, where he has since conducted research on software modeling and analysis.
    </p>
    <p>
      He has been involved in standardization activities within AENOR, ISO, ITU-T and the OMG, and served as
      the Spanish representative at <a href="http://www.jtc1-sc7.org/" target="_blank">IFIP TC2</a> and
      <a href="http://www.jtc1-sc7.org/" target="_blank">ISO SC7</a>, co-editing ISO/IEC 19793 (UML4ODP)
      and the revised version of RM-ODP (ISO/IEC 10746-2/3). He led the AEN/CTN 71 Working Group on
      Techniques for the Specification of IT Systems (GT19) at UNE, and was a certified Technical Expert at
      <a href="https://www.enac.es/" target="_blank">ENAC</a> (Entidad de Acreditación Nacional).
    </p>
    <p>
      He has organized several international conferences, including ECOOP 2002, TOOLS 2010, MODELS 2013,
      ECOOP 2017 and <a href="https://2020.congresocedi.es/" target="_blank">CEDI 20/21</a>, and has served as
      PC Chair for ICSOC, TOOLS, ICMT, ECMFA, QoSA and QUATIC. He has been a member of the editorial boards of
      <a href="http://www.sosym.org" target="_blank">SoSyM</a>,
      <a href="https://www.springer.com/journal/12599" target="_blank">BISE</a> and
      <a href="http://www.jot.fm" target="_blank">JOT</a>. He served as Vice-President for Postgraduate and
      Doctoral Studies at the University of Málaga (2012–2016), and as President of the Spanish Society on
      Software Engineering (<a href="http://www.sistedes.es" target="_blank">SISTEDES</a>) (2014–2018).
      From 2017 to March 2020 he coordinated the <em>Computer Science and Information Technologies</em> (INF)
      subarea of the Spanish Research Agency
      (<a href="http://www.idi.mineco.gob.es/portal/site/MICINN/menuitem.8d78849a34f1cd28d0c9d910026041a0/?vgnextoid=664cfb7e04195510VgnVCM1000001d04140aRCRD" target="_blank">AEI</a>),
      and has been an assessor for the Australian Research Council
      (<a href="http://www.arc.gov.au/" target="_blank">ARC</a>) since 2013. From 2020 to 2023 he was
      Vice-President of the Spanish Society on Informatics (<a href="http://www.scie.es" target="_blank">SCIE</a>).
      He is a Senior Member of <a href="https://www.acm.org/" target="_blank">ACM</a>, an
      <a href="https://www.aaia-ai.org/" target="_blank">AAIA</a> Fellow, and a member of the
      <a href="https://www.ae-info.org/ae/Member/Vallecillo_Antonio" target="_blank">Academia Europæa</a>.
    </p>

    <div class="award-box">
      🏆 Recipient of the <strong>2024 National Informatics Award "José García Santesmases"</strong>,
      granted by <a href="http://www.scie.es" target="_blank">SCIE</a> and the
      <a href="https://www.fbbva.es/noticias/premios-informatica-scie-fundacion-bbva-2024/" target="_blank">BBVA Foundation</a>,
      for his professional career.
    </div>

    <p>
      He had the honor of having the <a href="http://www.jot.fm" target="_blank">JOT</a> journal dedicate a
      <a href="https://www.jot.fm/contents/issue_2022_04.html" target="_blank">special issue on the occasion of
      his 60th birthday</a>, and the <a href="http://www.sosym.org" target="_blank">SoSyM</a> journal publish a
      special issue on
      <a href="https://link.springer.com/journal/10270/volumes-and-issues/24-3" target="_blank">uncertainty,
      modeling, CPSs and AI</a> in his honor.
    </p>
  </section>

  <!-- PUBLICATIONS -->
  <section>
    <h2><span class="dot"></span>Publications</h2>
    <ul>
      <li>For a complete list of publications, see his entries at:
        <a href="https://www.scopus.com/authid/detail.uri?authorId=57212671717" target="_blank">Scopus</a>,
        <a href="http://www.informatik.uni-trier.de/%7Eley/db/indices/a-tree/v/Vallecillo:Antonio.html" target="_blank">DBLP</a>,
        <a href="http://scholar.google.com/citations?user=yiijLskAAAAJ" target="_blank">Google Scholar</a>,
        <a href="https://www.semanticscholar.org/author/Antonio-Vallecillo/46434062" target="_blank">Semantic Scholar</a>,
        <a href="https://www.webofscience.com/wos/author/record/407403,44643621" target="_blank">WOS</a>,
        <a href="http://academic.research.microsoft.com/Author/449499/antonio-vallecillo" target="_blank">Microsoft Academic Search</a>,
        <a href="http://portal.acm.org/results.cfm?coll=portal&dl=ACM&query=Antonio+Vallecillo&short=1" target="_blank">ACM DL</a>,
        <a href="https://www.lens.org/lens/orcid/0000-0002-8139-9986/scholar" target="_blank">Lens</a>, or
        <a href="http://arnetminer.org/person/antonio-vallecillo-393999.html#.T6GbGKt-dbE" target="_blank">ArnetMiner</a>.
      </li>
      <li>Books:
        <ul>
          <li>"<a href="http://theodpbook.lcc.uma.es/" target="_blank">Building Enterprise Systems with ODP: An Introduction to Open Distributed Processing</a>", Chapman &amp; Hall/CRC Press, 2012.</li>
          <li>"<a href="http://www.ra-ma.es/libros/DESARROLLO-DE-SOFTWARE-DIRIGIDO-POR-MODELOS-CONCE%0APTOS-METODOS-Y-HERRAMIENTAS/82019/978-84-9964-215-4" target="_blank">Desarrollo de Software Dirigido por Modelos: Conceptos, Métodos y Herramientas</a>", RA-MA, 2013 (<a href="http://www.lcc.uma.es/~av/Publicaciones/12/LibroDSDM.pdf" target="_blank">PDF</a>).</li>
          <li>"<a href="http://www.lcc.uma.es/~av/Libro/" target="_blank">Técnicas de Diseño de Algoritmos</a>", SPICUM, 2000.</li>
        </ul>
      </li>
    </ul>
  </section>

  <!-- RESEARCH PROJECTS, TOOLS AND TALKS -->
  <section>
    <h2><span class="dot"></span>Research Projects, Tools &amp; Talks</h2>
    <ul>
      <li><strong>Recent Research Projects</strong>
        <ul>
          <li><a href="http://atenea.lcc.uma.es/projects/IPSCA" target="_blank">Including people in smart city applications</a>. PID2021-125527NB-I00. 1/9/2022 – 31/8/2026.</li>
          <li><a href="http://atenea.lcc.uma.es/projects/SoCUS" target="_blank">Social Computing for Urban Sustainability</a>. TED2021-130523B-I00. 1/12/2022 – 1/12/2024.</li>
          <li><a href="http://atenea.lcc.uma.es/projects/COSCA" target="_blank">Digital Avatars: A Framework for Collaborative Social Computing Applications</a>. PGC2018-094905-B-I00. 1/1/2019 – 30/9/2022.</li>
          <li><a href="http://atenea.lcc.uma.es/projects/MBT-I4A" target="_blank">Automated Model-Based Testing of Industry 4.0 Applications</a>. P20-00067-FR. 5/10/2021 – 31/3/2023.</li>
          <li>(For a complete list of research projects, see his <a href="personal/CV-AVallecillo.pdf" target="_blank">CV</a>.)</li>
        </ul>
      </li>
      <li><strong>Tools:</strong> For information about tools and resources produced by the research group, visit the <a href="http://atenea.lcc.uma.es" target="_blank">Atenea</a> website.</li>
      <li><strong>Talks:</strong> Slides of recent talks are available at <a href="https://www.slideshare.net/avallecillo" target="_blank">Slideshare</a>.</li>
    </ul>
  </section>

  <!-- FURTHER INFO -->
  <section>
    <h2><span class="dot"></span>Further Info</h2>
    <div class="ids-grid">
      <div>ORCID: <a href="http://orcid.org/0000-0002-8139-9986" target="_blank">0000-0002-8139-9986</a></div>
      <div>Scopus ID: <a href="https://www.scopus.com/authid/detail.uri?authorId=57212671717" target="_blank">57212671717</a></div>
      <div>ResearcherID: <a href="http://www.researcherid.com/rid/B-1884-2014" target="_blank">B-1884-2014</a></div>
      <div>Iralis: <a href="http://www.iralis.org/?q=node%2F10&paso=10&id=4953" target="_blank">ESINF4953</a></div>
      <div>Lens: <a href="https://www.lens.org/lens/orcid/0000-0002-8139-9986/scholar" target="_blank">0000-0002-8139-9986</a></div>
    </div>
    <ul style="margin-top: 1rem;">
      <li>CV (<a href="personal/CVA-AVallecillo-EN.pdf" target="_blank">Short version, in English</a>)</li>
      <li>CV (<a href="personal/CV-AVallecillo.pdf" target="_blank">Full version, in Spanish</a>)</li>
    </ul>
  </section>

  <!-- ABOUT MÁLAGA -->
  <section>
    <h2><span class="dot"></span>About the City and the University of Málaga</h2>
    <ul>
      <li>
        <a href="http://www.infouma.uma.es/noticias/index.php?option=com_content&task=view&id=197&Itemid=50" target="_blank">Discover the University of Málaga</a> (video) ·
        <a href="https://www.youtube.com/watch?v=9Na4yYZH2Hg" target="_blank">Have a look at Málaga</a> (video) ·
        <a href="https://www.youtube.com/watch?v=z_IyaKCij1c" target="_blank">We are from Málaga</a> (video) ·
        <a href="https://youtu.be/Wn20LXi1rsw" target="_blank">Málaga time lapse</a> (video) ·
        <a href="download/Malaga-Navidad2021.mp4" target="_blank">Xmas in Málaga</a> (video)
      </li>
    </ul>
  </section>

</main>

<footer>
  <p>Antonio Vallecillo · Universidad de Málaga · <a href="mailto:av@uma.es">av@uma.es</a></p>
</footer>

</body>
</html>

