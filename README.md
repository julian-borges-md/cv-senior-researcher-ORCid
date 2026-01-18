<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Julian Y. V. Borges, MD, MS | Researcher CV (ORCID)</title>
  <meta name="viewport" content="width=device-width, initial-scale=1" />

  <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Julian Y. V. Borges, MD, MS | Researcher CV (ORCID)</title>
  <meta name="viewport" content="width=device-width, initial-scale=1" />

  <!-- Optional Google Font -->
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700;800&display=swap" rel="stylesheet">

  <style>
    :root {
      font-size: 16px;
      line-height: 1.6;
      font-family: 'Inter', system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
      color: #1f2937;
      background: linear-gradient(135deg, #f9fafb, #e5e7eb);
      -webkit-font-smoothing: antialiased;
    }

    body {
      margin: 0;
      padding: 0;
      background-attachment: fixed;
      background-size: cover;
    }

    .page {
      max-width: 1120px;
      margin: 2.5rem auto;
      padding: 2.5rem;
      background: rgba(255, 255, 255, 0.88);
      backdrop-filter: blur(12px);
      box-shadow: 0 12px 40px rgba(0, 0, 0, 0.08);
      border-radius: 1rem;
      transition: all 0.3s ease-in-out;
    }

    h1, h2, h3, h4 {
      color: #111827;
      margin-top: 0;
    }

    h1 {
      font-size: 2.1rem;
      letter-spacing: 0.02em;
      text-transform: uppercase;
      margin-bottom: 0.35rem;
      font-weight: 800;
    }

    h2 {
      font-size: 1.4rem;
      margin-top: 2.2rem;
      padding-bottom: 0.4rem;
      border-bottom: 2px solid #e5e7eb;
      font-weight: 700;
    }

    h3 {
      font-size: 1.05rem;
      margin-bottom: 0.25rem;
    }

    p {
      margin: 0.5rem 0;
    }

    .muted {
      color: #6b7280;
      font-size: 0.95rem;
    }

    .small {
      font-size: 0.92rem;
    }

    .header {
      border-bottom: 2px solid #e5e7eb;
      padding-bottom: 1rem;
      margin-bottom: 1rem;
      display: flex;
      flex-wrap: wrap;
      gap: 1.5rem;
      align-items: flex-start;
    }

    .header-left { flex: 1 1 780px; min-width: 320px; }
    .header-identity {
      display: flex;
      gap: 1.25rem;
      align-items: flex-start;
    }

    .header-identity-text {
      display: flex;
      flex-direction: column;
      min-width: 0;
    }

    .profile-photo {
      width: auto;
      height: 100%;
      min-height: 176px;
      max-height: 240px;
      aspect-ratio: 3 / 4;
      object-fit: cover;
      border-radius: 0.75rem;
      border: 2px solid #e5e7eb;
      background: #ffffff;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.05);
      flex: 0 0 auto;
      margin-top: 10px;
      transition: transform 0.3s;
    }

    .profile-photo:hover {
      transform: scale(1.03);
    }

    .tagline {
      font-weight: 700;
      color: #374151;
      margin-top: 0.4rem;
    }

    .tertiary {
      color: #6b7280;
      font-size: 0.95rem;
      margin-top: 0.15rem;
    }

    .badge-row {
      display: flex;
      flex-wrap: wrap;
      gap: 0.5rem;
      margin-top: 0.75rem;
      align-items: center;
    }

    .badge {
      display: inline-flex;
      align-items: center;
      gap: 0.45rem;
      background: #eef2ff;
      border: 1px solid #c7d2fe;
      border-radius: 999px;
      padding: 0.3rem 0.85rem;
      font-size: 0.85rem;
      color: #4338ca;
      text-decoration: none;
      white-space: nowrap;
      line-height: 1;
      transition: all 0.2s ease-in-out;
      box-shadow: 0 2px 6px rgba(0, 0, 0, 0.04);
    }

    .badge:hover {
      background: #e0e7ff;
      transform: translateY(-2px) scale(1.03);
      box-shadow: 0 8px 16px rgba(0, 0, 0, 0.08);
    }

    .badge-icon {
      width: 0.95rem;
      height: 0.95rem;
      display: inline-block;
      vertical-align: middle;
      flex: 0 0 auto;
    }

    .contact-wide,
    .keywords-frame,
    .kpi {
      border: 1px solid #e5e7eb;
      border-radius: 0.9rem;
      padding: 1rem;
      background: rgba(255, 255, 255, 0.96);
      box-shadow: 0 2px 10px rgba(0, 0, 0, 0.05);
    }

    .pill-list {
      display: flex;
      flex-wrap: wrap;
      gap: 0.5rem;
      list-style: none;
      margin: 0;
      padding: 0;
    }

    .pill-list li {
      background: #f3f4f6;
      border: 1px solid #e5e7eb;
      padding: 0.3rem 0.85rem;
      border-radius: 999px;
      font-size: 0.85rem;
      color: #1f2937;
      box-shadow: inset 0 1px 2px rgba(0, 0, 0, 0.03);
    }

    .card {
      border: 1px solid #e5e7eb;
      border-radius: 0.9rem;
      padding: 1.2rem;
      background: rgba(255, 255, 255, 0.93);
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.04);
      transition: transform 0.25s ease;
    }

    .card:hover {
      transform: translateY(-4px);
    }

    .grid-2,
    .grid-3 {
      display: grid;
      gap: 0.9rem;
      margin-top: 0.9rem;
    }

    .grid-2 {
      grid-template-columns: 1fr 1fr;
    }

    .grid-3 {
      grid-template-columns: 1fr 1fr 1fr;
    }

    @media (max-width: 980px) {
      .grid-3 { grid-template-columns: 1fr; }
      .grid-2 { grid-template-columns: 1fr; }
    }

    @media (max-width: 720px) {
      .header-identity { flex-direction: column; align-items: flex-start; }
      .profile-photo {
        width: 160px;
        height: auto;
        margin-top: 0;
      }
    }

    .item {
      margin-bottom: 1rem;
    }

    .item-header {
      display: flex;
      justify-content: space-between;
      flex-wrap: wrap;
      gap: 0.35rem;
      align-items: baseline;
    }

    .item-title {
      font-weight: 800;
    }

    .item-meta {
      font-size: 0.92rem;
      color: #6b7280;
    }

    ul {
      margin-top: 0.4rem;
      padding-left: 1.1rem;
    }

    li {
      margin-bottom: 0.35rem;
    }

    a {
      color: #2563eb;
      transition: all 0.2s ease;
    }

    a:hover {
      text-decoration: underline;
      color: #1e40af;
      transform: translateY(-1px);
    }

    a:focus-visible {
      outline: 3px solid rgba(37, 99, 235, 0.3);
      outline-offset: 3px;
    }

    .subheading {
      font-weight: 800;
      margin-top: 1rem;
      margin-bottom: 0.35rem;
    }

    @media print {
      :root { background: #ffffff; }
      .page {
        box-shadow: none;
        margin: 0;
        border-radius: 0;
        max-width: none;
        padding: 0.75in;
      }
      a { color: #111827; text-decoration: none; }
      .badge { border: 1px solid #d1d5db; background: #ffffff; color: #111827; box-shadow: none; }
      .kpi { background: #ffffff; }
    }
  </style>
</head>

<body>
  <main class="page">
    <!-- 👇 YOUR ENTIRE ORIGINAL BODY STARTS HERE AND IS PRESERVED UNCHANGED -->
    <!-- Copy from <header> to </main> from your original code -->

</head>

<body>
  <main class="page">

    <!-- TOP ROW: PHOTO + IDENTITY -->
    <header class="header">
      <div class="header-left">
        <div class="header-identity">
          <img src="assets/profile.jpg" alt="Julian Y. V. Borges" class="profile-photo" />

          <div class="header-identity-text">
            <h1>Julian Y. V. Borges, MD, MS</h1>
            <div class="tagline">Clinician Scientist | Clinical Informatics | Responsible Clinical AI | Genomics</div>
            <div class="tertiary">Clinical Research · Medical Informatics · AI Governance</div>

            <p class="muted small">
              I connect clinical medicine, artificial intelligence, and genomic science to build data driven systems that advance precision endocrinology and enable safer,
              more effective clinical decision making. My work focuses on research, informatics, and digital health infrastructure that bridges clinical knowledge with academic
              investigation and real world deployment.
            </p>

            <div class="badge-row" aria-label="Key identity links">
              <a class="badge" href="https://orcid.org/0009-0001-9929-3135" target="_blank" rel="noopener">ORCID</a>

              <a class="badge" href="https://www.linkedin.com/in/julian-borges-md/" target="_blank" rel="noopener" aria-label="LinkedIn">
                <svg class="badge-icon" viewBox="0 0 24 24" aria-hidden="true" focusable="false">
                  <path fill="currentColor" d="M20.447 20.452h-3.554v-5.569c0-1.328-.027-3.037-1.852-3.037-1.853 0-2.136 1.445-2.136 2.939v5.667H9.351V9h3.414v1.561h.046c.476-.9 1.637-1.85 3.368-1.85 3.6 0 4.266 2.368 4.266 5.455v6.286zM5.337 7.433A2.062 2.062 0 0 1 3.27 5.37c0-1.14.925-2.067 2.067-2.067 1.141 0 2.066.926 2.066 2.067 0 1.141-.925 2.063-2.066 2.063zM6.814 20.452H3.861V9h2.953v11.452zM22.225 0H1.771C.792 0 0 .774 0 1.729v20.542C0 23.227.792 24 1.771 24h20.451C23.2 24 24 23.227 24 22.271V1.729C24 .774 23.2 0 22.222 0h.003z"/>
                </svg>
              </a>

              <a class="badge" href="https://github.com/julian-borges-md" target="_blank" rel="noopener">GitHub</a>

              <a class="badge" href="https://x.com/julianborgesmd" target="_blank" rel="noopener" aria-label="X">
                <svg class="badge-icon" viewBox="0 0 24 24" aria-hidden="true" focusable="false">
                  <path fill="currentColor" d="M18.9 2H22l-6.8 7.8L23.2 22h-6.7l-5.2-6.5L5.7 22H2.6l7.4-8.5L1 2h6.8l4.7 6.1L18.9 2zm-1.2 18h1.7L7.1 3.9H5.3L17.7 20z"></path>
                </svg>
              </a>

              <a class="badge" href="https://dataverse.harvard.edu/dataverse/julian_borges" target="_blank" rel="noopener">Harvard Dataverse</a>
            </div>

            <!-- KEYWORDS: full width visible frame, below contact block -->
          </div>
        </div>
      </div>
    </header>

    <!-- FULL WIDTH CONTACT BOX -->
    <div class="contact-wide" aria-label="Contact and identifiers">
      <div class="contact-wide-grid">
        <div class="contact-wide-item">
          <div class="label">Countries</div>
          <div class="value">United States, Brazil</div>
        </div>

        <div class="contact-wide-item">
          <div class="label">Primary email</div>
          <div class="value">
            <a href="mailto:fxmedbrasil@gmail.com">fxmedbrasil@gmail.com</a>
          </div>
        </div>

        <div class="contact-wide-item">
          <div class="label">Other IDs</div>
          <div class="value">
            <div class="small">
              Scopus Author ID:
              <a href="http://www.scopus.com/inward/authorDetails.url?authorID=59247184100&partnerID=MN8TOARS" target="_blank" rel="noopener">59247184100</a>
            </div>
            <div class="small">
              SciProfiles:
              <a href="https://sciprofiles.com/profile/3701785" target="_blank" rel="noopener">3701785</a>
            </div>
            <div class="small">
              ResearcherID:
              <a href="https://www.webofscience.com/wos/author/record/KVZ-2689-2024" target="_blank" rel="noopener">KVZ-2689-2024</a>
            </div>
          </div>
        </div>

        <div class="contact-wide-item">
          <div class="label">Core methods and tooling</div>
          <div class="value">Python, R, Stata, SQL</div>
        </div>
      </div>
    </div>

    <!-- FULL WIDTH KEYWORDS BOX (VISIBLE FRAME, HORIZONTAL) -->
    <div class="keywords-frame" aria-label="Keywords">
      <ul class="pill-list">
        <li>Artificial Intelligence</li>
        <li>Machine Learning</li>
        <li>Deep Learning</li>
        <li>AI Governance</li>
        <li>Digital Transformations</li>
        <li>Digital Health</li>
        <li>Cardio Endocrinology</li>
        <li>Molecular Endocrinology</li>
        <li>Circulatory Physiology</li>
        <li>Endothelial Dysfunction</li>
        <li>Vasculature Pathophysiology</li>
      </ul>
    </div>

    <section>
      <h2>Research and Leadership Summary</h2>
      <div class="card">
        <p>
          I am a clinician scientist and endocrinologist with more than 23 years of experience at the intersection of medicine, data science, and translational research.
          As Founder and CEO of FXMEDUS LLC, I lead initiatives integrating health informatics, computational biology, and artificial intelligence to design scalable solutions
          for metabolic and aging related diseases. Flagship platforms such as MitoCoreX and DrugSynthAI apply multi agent architectures, reinforcement learning, and in silico
          experimentation for compound generation, biomarker discovery, and mitochondrial therapeutics research.
        </p>

        <div class="grid-2" aria-label="Research focus">
          <div class="kpi">
            <div class="kpi-title">Clinical AI governance and reproducibility</div>
            <div class="kpi-text">Auditability, evaluation discipline, data governance, and interoperability oriented infrastructure for safer translation to care.</div>
          </div>
          <div class="kpi">
            <div class="kpi-title">Genomics and precision endocrinology</div>
            <div class="kpi-text">Translational inference with large scale omics, causal confounding awareness, and clinically actionable evidence framing.</div>
          </div>
        </div>
      </div>
    </section>

    <section>
      <h2>Employment</h2>
      <div class="card">
        <div class="item">
          <div class="item-header">
            <div class="item-title">FxMEDUS LLC | Founder, CEO, Chief Scientist</div>
            <div class="item-meta">North Miami, Florida, United States | 2024 to present</div>
          </div>
          <p class="small muted">Digital transformation, digital health, clinical informatics research.</p>
        </div>

        <div class="item">
          <div class="item-header">
            <div class="item-title">Afya Medical Post Graduation Institute | Associate Professor of Medicine</div>
            <div class="item-meta">Goiânia, Goiás, Brazil | 2022 to present</div>
          </div>
          <p class="small muted">Endocrinology, diabetes, and metabolism.</p>
        </div>

        <div class="item" style="margin-bottom:0;">
          <div class="item-header">
            <div class="item-title">FxMED, Medicina Funcional | Staff Physician and Medical Director</div>
            <div class="item-meta">Goiânia, Goiás, Brazil | 2011 to present</div>
          </div>
          <p class="small muted">Endocrinology and clinical nutrition.</p>
        </div>
      </div>
    </section>

    <section>
      <h2>Education and Qualifications</h2>
      <div class="grid-2">
        <div class="card">
          <div class="subheading">Graduate and Certificate Training</div>
          <ul>
            <li>Boston University | MS Health Informatics (Data Analytics) candidate | 2025 to 2027</li>
            <li>Harvard Medical School | Global Clinical Scholars Research Training, Genetic Epidemiology elective (GCSRT)| 2024 to 2025</li>
            <li>UC San Diego | Drug discovery, development, and product management specialization | 2025</li>
            <li>Northeastern University | Health informatics for healthcare professionals certificate | 2025</li>
            <li>Johns Hopkins | Clinical informatics specialization | 2025</li>
            <li>Johns Hopkins | Bioinformatics, Python for genomic data science certificate | 2025</li>
            <li>NIH OCRECO | Principles and Practices of Clinical Pharmacology (IPCP)| 2025</li>
            <li>NIH OCRECO | Principles and Practices of Clinical Research (IPCR)| 2024</li>
            <li>HarvardX via edX | AI and machine learning with R and Python, statistics and R, Python for research | 2024</li>
            <li>Pontifícia Universidade Católica de Goiás | Medical genetics masters program | 2015 to 2016</li>
          </ul>
        </div>

        <div class="card">
          <div class="subheading">Medical Training and Board Certification</div>
          <ul>
            <li>Centro Universitário Serra dos Órgãos | Doctor of Medicine MD | 1996 to 2002</li>
            <li>Endocrinology, diabetes and metabolism | Board certification (SBEM/CFM/AMB) | 2014</li>
            <li>Clinical nutrition and nutrology | Board certification (ABRAN/CFM/AMB)| 2013 to 2014</li>
            <li>Nutrology fellowship | 2012 to 2013</li>
            <li>Endocrinology fellowship | 2011 to 2013</li>
            <li>Medical biochemistry postgraduate program | 2006 to 2008</li>
            <li>Exercise and sports medicine postgraduate program | 2003</li>
          </ul>

          <div class="subheading">Invited positions and distinctions</div>
          <ul>
            <li>Academic Editor | PLOS Digital Health | 2025 to present</li>
            <li>Editor in Chief | International Journal of Epidemiology and Public Health Research | 2024 to present</li>
            <li>Board certification in endocrinology and diabetes | distinction | 2014</li>
            <li>Board certification in clinical nutrition | distinction | 2013</li>
          </ul>
        </div>
      </div>
    </section>

    <section>
      <h2>Membership and Service</h2>
      <div class="card">
        <ul>
          <li>American Physician Scientists Association | full member | 2024 to present</li>
          <li>American Medical Informatics Association | member, clinical informatics | 2024 to present</li>
          <li>American Medical Association | member | 2023 to present</li>
          <li>Endocrine Society | full member | 2022 to present</li>
          <li>American Society for Nutrition | full member | 2014 to present</li>
          <li>ACSM | full member | 2010 to present</li>
        </ul>
      </div>
    </section>

    <section>
      <h2>Selected Publications and Research Artifacts</h2>
      <div class="card">
        <p class="muted small" style="margin-top:0;">
          This section is formatted for quick scanning by recruiters, collaborators, and review committees. Each link opens in a new tab.
        </p>

        <ul>
          <li>
            Auditing Shortcut Learning and Misclassification in AI Based Breast Cancer Genomic Subtyping (2026).
            <a href="https://doi.org/10.1093/jamiaopen/ooaf177" target="_blank" rel="noopener">DOI:10.1093/jamiaopen/ooaf177</a>
            <span class="muted small"> | Harvard Dataverse: </span>
            <a href="https://doi.org/10.7910/dvn/baljnt" target="_blank" rel="noopener">DOI:10.7910/dvn/baljnt</a>
          </li>

          <li>
            Multi Arm Bandit Governance for Clinical AI (software, Zenodo, 2026).
            <a href="https://doi.org/10.5281/zenodo.18248285" target="_blank" rel="noopener">DOI:10.5281/zenodo.18248285</a>
          </li>

          <li>
            Functional Foods and Nutraceuticals: Definitions and Health Benefits (book, 2025).
            <a href="https://doi.org/10.54448/MSP.978-65-983826-2-9" target="_blank" rel="noopener">DOI:10.54448/MSP.978-65-983826-2-9</a>
          </li>

          <li>
            Advancing Deep Learning Insights for Identifying Heart Disease in Diabetic Patients: A Data Mining Approach Using Logistic Regression and Random Forests (SSRN, 2025).
            <a href="https://doi.org/10.2139/ssrn.5091734" target="_blank" rel="noopener">DOI:10.2139/ssrn.5091734</a>
          </li>

          <li>
            Impact of Renal Function and Symptom Burden on Digoxin Efficacy and Safety: A Post Hoc Subgroup Analysis of the DIG Trial (Harvard Dataverse, dataset, 2025).
            <a href="https://doi.org/10.7910/dvn/zhyhy5" target="_blank" rel="noopener">DOI:10.7910/dvn/zhyhy5</a>
          </li>

          <li>
            Neuroplasticity Alterations Induced by Isotretinoin Use in RARA Gene Polymorphism is Associated with Increased Risk of Depression and Suicidal Ideation (systematic review and meta analysis, 2024).
            <a href="https://doi.org/10.47363/JPSRR/2024(6)173" target="_blank" rel="noopener">DOI:10.47363/JPSRR/2024(6)173</a>
          </li>

          <li>
            Oral Testosterone Therapy in Hypogonadal Men: A Comprehensive Systematic Review and Meta Analysis (2024).
            <a href="https://doi.org/10.1101/2024.09.22.24314162" target="_blank" rel="noopener">DOI:10.1101/2024.09.22.24314162</a>
            <span class="muted small"> | </span>
            <a href="https://doi.org/10.54178/jsedmv6i3001" target="_blank" rel="noopener">DOI:10.54178/jsedmv6i3001</a>
          </li>

          <li>
            Translational Cardiology: Coenzyme Q10 Role as a Potential Therapeutic Agent for Cardiovascular Disease (2024).
            <a href="https://doi.org/10.33140/tmoa.02.01.04" target="_blank" rel="noopener">DOI:10.33140/tmoa.02.01.04</a>
          </li>

          <li>
            The Inverse Association between Testosterone Replacement Therapy and Cardiovascular Disease Risk (2024).
            <a href="https://doi.org/10.1101/2024.06.21.24309326" target="_blank" rel="noopener">DOI:10.1101/2024.06.21.24309326</a>
            <span class="muted small"> | </span>
            <a href="https://doi.org/10.31579/2834-796x/073" target="_blank" rel="noopener">DOI:10.31579/2834-796x/073</a>
          </li>

          <li>
            Challenging the Salt Paradigm: Dietary Sodium Impact on Cardiovascular Risk (2024).
            <a href="https://doi.org/10.34297/AJBSR.2024.23.003132" target="_blank" rel="noopener">DOI:10.34297/AJBSR.2024.23.003132</a>
          </li>

          <li>
            Erectile Dysfunction as a Novel Biomarker for Cardiometabolic Vascular Disease Risk in the Aging Male (2024).
            <a href="https://doi.org/10.1101/2024.07.06.24310031" target="_blank" rel="noopener">DOI:10.1101/2024.07.06.24310031</a>
            <span class="muted small"> | </span>
            <a href="https://doi.org/10.33140/ajun.06.01.06" target="_blank" rel="noopener">DOI:10.33140/ajun.06.01.06</a>
          </li>

          <li>
            A Machine Learning Framework for Early Detection of Cardiovascular Risk Using Diabetes Related Indicators (2024).
            <a href="https://doi.org/10.21203/rs.3.rs-4971115/v1" target="_blank" rel="noopener">DOI:10.21203/rs.3.rs-4971115/v1</a>
          </li>

          <li>
            Mitigating the Opioid Epidemic: The Role of Cannabinoids in Chronic Pain Management (2024).
            <a href="https://doi.org/10.1101/2024.07.14.24310378" target="_blank" rel="noopener">DOI:10.1101/2024.07.14.24310378</a>
            <span class="muted small"> | </span>
            <a href="https://doi.org/10.33140/JAPM.09.03.05" target="_blank" rel="noopener">DOI:10.33140/JAPM.09.03.05</a>
          </li>

          <li>
            Trends in Sudden Cardiac Death in Pilots (2011 to 2023) (2024).
            <a href="https://doi.org/10.1101/2024.06.29.24309708" target="_blank" rel="noopener">DOI:10.1101/2024.06.29.24309708</a>
            <span class="muted small"> | </span>
            <a href="https://doi.org/10.33140/IJPMC.02.02.04" target="_blank" rel="noopener">DOI:10.33140/IJPMC.02.02.04</a>
          </li>

          <li>
            Artificial Intelligence in Pain Management: Advancing Translational Science in Digital Health Research from Bench to Bedside (2024).
            <a href="https://doi.org/10.33140/AMLAI.05.03.04" target="_blank" rel="noopener">DOI:10.33140/AMLAI.05.03.04</a>
          </li>

          <li>
            Emerging Digital Health Interventions Toward Cardiovascular Care: Key Insights for 2025 (2024).
            <a href="https://doi.org/10.2139/ssrn.4981082" target="_blank" rel="noopener">DOI:10.2139/ssrn.4981082</a>
          </li>

          <li>
            Erectile Dysfunction and Cardiovascular Disease Risk: Updated 2024 systematic review meta analysis (2024).
            <a href="https://doi.org/10.21203/rs.3.rs-4681079/v1" target="_blank" rel="noopener">DOI:10.21203/rs.3.rs-4681079/v1</a>
          </li>

          <li>
            Innovative E Health Technologies for Cardiovascular Disease Treatment: 2024 updated systematic review and meta analysis (2024).
            <a href="https://doi.org/10.1101/2024.06.29.24309706" target="_blank" rel="noopener">DOI:10.1101/2024.06.29.24309706</a>
          </li>

          <li>
            Major clinical outcomes and discussions of religiosity spirituality in patients with palliative care and nutrology therapy (2024).
            <a href="https://doi.org/10.54448/IJN24409" target="_blank" rel="noopener">DOI:10.54448/IJN24409</a>
          </li>

          <li>
            Precision Medicine in Cardiology: Biomarkers in coronary artery disease prevention, thematic review (2024).
            <a href="https://doi.org/10.1101/2024.07.01.24309804" target="_blank" rel="noopener">DOI:10.1101/2024.07.01.24309804</a>
            <span class="muted small"> | </span>
            <a href="https://doi.org/10.26502/FCCM.92920395" target="_blank" rel="noopener">DOI:10.26502/FCCM.92920395</a>
          </li>

          <li>
            The Inverse Association between Potassium Intake and Cardiovascular Disease Risk (2024).
            <a href="https://doi.org/10.21203/RS.3.RS-4699824/V1" target="_blank" rel="noopener">DOI:10.21203/RS.3.RS-4699824/V1</a>
          </li>

          <li>
            Thromboembolic Risk and Testosterone Replacement Therapy: Debunking myths and clarifying evidence (2024).
            <a href="https://doi.org/10.21203/RS.3.RS-5134020/V1" target="_blank" rel="noopener">DOI:10.21203/RS.3.RS-5134020/V1</a>
          </li>
        </ul>

        <p class="muted small" style="margin-bottom:0;">
          Peer review activity (summary): PLOS Digital Health (36), European Journal of Preventive Cardiology (7), European Heart Journal (2), Diabetes and Metabolic Syndrome (2), Nature Reviews (1), Journal of Advances in Medicine and Medical Research (1).
        </p>
      </div>
    </section>

    <section class="section two-column">
      <div>
        <h2>Editorial Roles and Peer Review</h2>
        <div class="card">
          <div class="subheading">Editorial Roles</div>
          <ul>
            <li>Academic Editor, PLOS Digital Health</li>
            <li>Editorial Board Member, International Journal of Diabetes and Endocrinology</li>
            <li>Editorial Board Member, International Journal of Epidemiology and Public Health Research</li>
          </ul>

          <div class="subheading">Peer Review</div>
          <p class="small">
            Reviewer for journals including PLOS Digital Health, European Heart Journal Digital Health, NaTure Reviews and European Journal of Preventive Cardiology, focused on clinical research rigor, digital health translation, and clinical analytics integrity.
          </p>
        </div>
      </div>

      <div>
        <h2>Research Portfolio Themes</h2>
        <div class="card">
          <ul>
            <li>Clinical research infrastructure and governance models enabling safe translation to care</li>
            <li>Clinical AI governance, auditability, and deployment safety in real clinical environments</li>
            <li>Applied analytics for cardiometabolic risk stratification and outcomes measurement</li>
            <li>Genomic epidemiology and bioinformatics for translational inference and precision prevention</li>
          </ul>

          <div class="subheading">MitoCoreX Project, Principal Investigator</div>
          <p class="small">
            AI enabled discovery and development platform designed to optimize mitochondrial function through genomics aware targeting, multi agent systems, and in silico validation for aging related disease, neurodegeneration, and metabolic performance.
          </p>
        </div>
      </div>
    </section>

    <section class="section">
      <h2>Professional Affiliations</h2>
      <div class="card">
        <ul>
          <li>American Medical Informatics Association (AMIA)</li>
          <li>American Medical Association (AMA)</li>
          <li>Endocrine Society</li>
          <li>American Society for Nutrition (ASN)</li>
          <li>American College of Sports Medicine (ACSM)</li>
          <li>American Physician Scientists Association (APSA)</li>
          <li>American College of Physicians (ACP)</li>
          <li>Brazilian Society of Endocrinology and Metabolism (SBEM)</li>
          <li>Brazilian Medical Nutrition Association (ABRAN)</li>
          <li>Brazilian Society of Sports Medicine (SBME)</li>
        </ul>
      </div>
    </section>

    <section class="section">
      <h2>Clinical Imaging Training</h2>
      <div class="card">
        <p class="small">
          Completed structured programs in obstetric, transvaginal, internal medicine, and musculoskeletal ultrasound at FÉRTILE Diagnósticos,
          an accredited SBUS teaching center in Goiânia, Brazil, including more than three hundred hours of theoretical and hands on training across obstetric,
          gynecologic, abdominal, and musculoskeletal imaging.
        </p>
      </div>
    </section>

    <section class="section">
      <h2>Contact and Executive Collaboration</h2>
      <div class="card">
        <p><strong>Email:</strong> <a href="mailto:jyborges@bu.edu">jyborges@bu.edu</a></p>
        <p><strong>Phone:</strong> +1 617 895 8403</p>
        <p class="muted small">
          Open to full time senior clinical research leadership roles focused on clinical trial expansion, translational infrastructure, investigator enablement, and research enterprise growth across Northern New England.
        </p>
      </div>
    </section>

  </main>
</body>
</html>
