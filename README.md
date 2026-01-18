<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Julian Y. V. Borges, MD, MS — Senior Director Clinical Research CV</title>
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <style>
    :root {
      font-size: 16px;
      line-height: 1.5;
      font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
      color: #111827;
      background-color: #f3f4f6;
    }

    body { margin: 0; padding: 0; }

    .page {
      max-width: 1040px;
      margin: 2rem auto;
      padding: 2rem;
      background: #ffffff;
      box-shadow: 0 10px 25px rgba(0, 0, 0, 0.08);
      border-radius: 0.75rem;
    }

    h1, h2, h3, h4 { margin-top: 0; color: #111827; }

    h1 {
      font-size: 2rem;
      letter-spacing: 0.03em;
      text-transform: uppercase;
      margin-bottom: 0.25rem;
    }

    h2 {
      font-size: 1.35rem;
      margin-top: 2rem;
      border-bottom: 2px solid #e5e7eb;
      padding-bottom: 0.4rem;
    }

    h3 {
      font-size: 1.05rem;
      margin-bottom: 0.2rem;
    }

    p { margin: 0.5rem 0; }

    .muted { color: #6b7280; font-size: 0.95rem; }
    .small { font-size: 0.92rem; }

    .header {
      display: flex;
      flex-wrap: wrap;
      justify-content: space-between;
      gap: 1rem;
      border-bottom: 2px solid #e5e7eb;
      padding-bottom: 1rem;
      margin-bottom: 1.5rem;
    }

    .header-left { min-width: 260px; }

    .header-right {
      min-width: 260px;
      text-align: left;
      font-size: 0.95rem;
    }

    .tagline {
      margin-top: 0.25rem;
      font-weight: 600;
      color: #374151;
    }

    /* --- FIXED: profile photo sizing, pulled down, and badge alignment --- */
    .header-identity {
      display: flex;
      align-items: flex-start; /* prevents vertical stretch misalignment */
      gap: 1rem;
    }

    .header-identity-text {
      display: flex;
      flex-direction: column;
      min-width: 0;
    }

    .profile-photo {
      width: 170px;           /* consistent portrait size */
      height: 226px;          /* 3:4 ratio */
      object-fit: cover;
      border-radius: 0.75rem;
      border: 1px solid #e5e7eb;
      background: #ffffff;
      flex: 0 0 auto;

      /* pulls the image down so it is not too high */
      margin-top: 1.1rem;
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
      align-items: center;       /* ensures icons and text align vertically */
      justify-content: center;
      gap: 0.4rem;
      background: #eef2ff;
      border: 1px solid #e0e7ff;
      border-radius: 999px;
      padding: 0.25rem 0.75rem;
      font-size: 0.85rem;
      line-height: 1;            /* critical: prevents baseline drift */
      color: #3730a3;
      text-decoration: none;
      white-space: nowrap;
    }

    .badge svg {
      width: 0.95rem;
      height: 0.95rem;
      display: inline-block;
      flex: 0 0 auto;
    }

    .badge-x-icon,
    .badge-in-icon {
      margin-right: 0;           /* remove legacy spacing that caused drift */
      vertical-align: middle;
    }
    /* --- END FIXED --- */

    .section { margin-top: 1.5rem; }

    .two-column {
      display: grid;
      grid-template-columns: 1.15fr 0.85fr;
      gap: 1.5rem;
      margin-top: 1.25rem;
    }

    @media (max-width: 900px) {
      .two-column { grid-template-columns: 1fr; }
      .header-right { text-align: left; }

      .profile-photo {
        width: 150px;
        height: 200px;
        margin-top: 0.9rem;
      }
    }

    @media (max-width: 600px) {
      .header-identity {
        flex-direction: column;
        align-items: flex-start;
      }
      .profile-photo {
        width: 160px;
        height: 214px;
        margin-top: 0;
      }
    }

    .card {
      border: 1px solid #e5e7eb;
      border-radius: 0.75rem;
      padding: 1rem;
      background: #ffffff;
    }

    .pill-list {
      display: flex;
      flex-wrap: wrap;
      gap: 0.5rem;
      margin: 0.75rem 0 0;
      padding: 0;
      list-style: none;
    }

    .pill-list li {
      background: #f9fafb;
      border-radius: 999px;
      padding: 0.25rem 0.75rem;
      font-size: 0.85rem;
      color: #111827;
      border: 1px solid #e5e7eb;
    }

    .item { margin-bottom: 1rem; }

    .item-header {
      display: flex;
      justify-content: space-between;
      flex-wrap: wrap;
      gap: 0.25rem;
    }

    .item-title { font-weight: 700; }

    .item-meta { font-size: 0.92rem; color: #6b7280; }

    ul { margin-top: 0.4rem; padding-left: 1.1rem; }
    li { margin-bottom: 0.35rem; }

    /* Animation applied to all links including publications */
    a { color: #2563eb; text-decoration: none; }

    a,
    .badge {
      transition: transform 160ms ease, box-shadow 160ms ease, background-color 160ms ease, color 160ms ease, opacity 160ms ease;
      will-change: transform;
    }

    a:hover {
      text-decoration: underline;
      transform: translateY(-1px);
    }

    a:active {
      transform: translateY(0px);
      opacity: 0.95;
    }

    a:focus-visible {
      outline: 3px solid rgba(37, 99, 235, 0.35);
      outline-offset: 3px;
      border-radius: 0.4rem;
    }

    .badge:hover {
      transform: translateY(-1px) scale(1.04);
      box-shadow: 0 10px 18px rgba(17, 24, 39, 0.10);
      background: #e0e7ff;
      text-decoration: none;
    }

    .badge:active {
      transform: translateY(0px) scale(0.99);
      box-shadow: 0 6px 10px rgba(17, 24, 39, 0.08);
    }

    @media (prefers-reduced-motion: reduce) {
      a, .badge { transition: none !important; }
      a:hover, .badge:hover { transform: none !important; box-shadow: none !important; }
    }

    .code-link {
      font-family: ui-monospace, SFMonoRegular, Menlo, Monaco, Consolas, "Liberation Mono", "Courier New", monospace;
      font-size: 0.9rem;
    }

    .subheading { font-weight: 700; margin-top: 1rem; margin-bottom: 0.35rem; }

    .kpi-grid {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 0.75rem;
      margin-top: 0.75rem;
    }

    @media (max-width: 700px) {
      .kpi-grid { grid-template-columns: 1fr; }
    }

    .kpi {
      border: 1px solid #e5e7eb;
      border-radius: 0.75rem;
      padding: 0.85rem;
      background: #f9fafb;
    }

    .kpi .kpi-title { font-weight: 700; margin-bottom: 0.15rem; }
    .kpi .kpi-text { color: #374151; font-size: 0.95rem; }

    .full-width { width: 100%; }

    .tech-grid-full {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 0.75rem;
      margin-top: 0.75rem;
    }

    @media (max-width: 900px) {
      .tech-grid-full { grid-template-columns: 1fr; }
    }

    .tech-card {
      border: 1px solid #e5e7eb;
      border-radius: 0.75rem;
      padding: 0.95rem;
      background: #f9fafb;
      height: 100%;
    }

    .tech-title { font-weight: 800; margin-bottom: 0.25rem; }
    .tech-text { color: #374151; font-size: 0.95rem; }

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
      .tech-card { background: #ffffff; }
      .profile-photo { box-shadow: none; }
    }
  </style>
</head>

<body>
  <main class="page">
    <header class="header">
      <div class="header-left">
        <div class="header-identity">
          <img src="assets/profile.jpg" alt="Julian Y. V. Borges, MD, MS" class="profile-photo" />
          <div class="header-identity-text">
            <h1>Julian Y. V. Borges, MD, MS</h1>
            <div class="tagline">Senior Director Clinical Research Candidate, Clinical Informatics and Translational Infrastructure</div>
            <p class="muted small">
              Physician scientist and senior research leader bridging clinical departments, clinical trials operations, and research infrastructure.
              Focus on clinical enterprise alignment, investigator enablement, governance, data strategy, and industry partnerships to expand trials and translational impact.
            </p>

            <div class="badge-row" aria-label="Profile links">
              <a class="badge" href="https://doi.org/10.1093/jamiaopen/ooaf177" target="_blank" rel="noopener">JAMIA Open</a>
              <a class="badge" href="https://doi.org/10.5281/zenodo.18248286" target="_blank" rel="noopener">Zenodo</a>
              <a class="badge" href="https://orcid.org/0009-0001-9929-3135" target="_blank" rel="noopener">ORCID</a>

              <a class="badge" href="https://x.com/julianborgesmd" target="_blank" rel="noopener" aria-label="X profile">
                <svg class="badge-x-icon" viewBox="0 0 24 24" aria-hidden="true" focusable="false">
                  <path fill="currentColor" d="M18.9 2H22l-6.8 7.8L23.2 22h-6.7l-5.2-6.5L5.7 22H2.6l7.4-8.5L1 2h6.8l4.7 6.1L18.9 2zm-1.2 18h1.7L7.1 3.9H5.3L17.7 20z"></path>
                </svg>
              </a>

              <a class="badge" href="https://www.linkedin.com/in/julian-borges-md/" target="_blank" rel="noopener" aria-label="LinkedIn profile">
                <svg class="badge-in-icon" viewBox="0 0 24 24" aria-hidden="true" focusable="false">
                  <path fill="currentColor" d="M20.447 20.452h-3.554v-5.569c0-1.328-.027-3.037-1.852-3.037-1.853 0-2.136 1.445-2.136 2.939v5.667H9.351V9h3.414v1.561h.046c.476-.9 1.637-1.85 3.368-1.85 3.6 0 4.266 2.368 4.266 5.455v6.286zM5.337 7.433A2.062 2.062 0 0 1 3.27 5.37c0-1.14.925-2.067 2.067-2.067 1.141 0 2.066.926 2.066 2.067 0 1.141-.925 2.063-2.066 2.063zM6.814 20.452H3.861V9h2.953v11.452zM22.225 0H1.771C.792 0 0 .774 0 1.729v20.542C0 23.227.792 24 1.771 24h20.451C23.2 24 24 23.227 24 22.271V1.729C24 .774 23.2 0 22.222 0h.003z"/>
                </svg>
                in/julian-borges-md
              </a>
            </div>
          </div>
        </div>
      </div>

      <div class="header-right" aria-label="Contact information">
        <div>Boston Area, Massachusetts</div>
        <div>Phone: +1 617 895 8403</div>
        <div>Email: <a href="mailto:jyborges@bu.edu">jyborges@bu.edu</a></div>
        <div class="code-link" style="margin-top:0.5rem;">
          GitHub:
          <a href="https://github.com/julian-borges-md" target="_blank" rel="noopener">julian-borges-md</a>
        </div>
        <div class="code-link">
          LinkedIn:
          <a href="https://www.linkedin.com/in/julian-borges-md/" target="_blank" rel="noopener">julian-borges-md</a>
        </div>
        <div class="small" style="margin-top:0.25rem;">
          ORCID: 0009 0001 9929 3135
        </div>
        <div class="small muted" style="margin-top:0.35rem;">
          Interested in full time senior clinical research leadership roles including Scarborough, Maine and greater Northern New England.
        </div>
      </div>
    </header>

    <section class="section">
      <h2>Executive Summary</h2>
      <div class="card">
        <p>
          Senior physician investigator and informatics leader with a practice grounded track record delivering clinical research enablement,
          clinical informatics implementation, and governance grade analytics in real clinical environments. Operates at the interface of clinical
          departments, research operations, and data and analytics, aligning service line priorities with trial execution capabilities, investigator
          support, and scalable infrastructure. Strength includes building programs that clinicians will adopt, sponsors will trust, and research
          leadership can scale across departments with clear policies, oversight, and measurable performance.
        </p>
        <p class="muted small">
          Target role: Senior Director of Clinical Research overseeing enterprise clinical research growth, clinical department liaison, clinical trials expansion,
          industry partnership development, research data governance, and translational infrastructure planning including NIH infrastructure programs.
        </p>

        <div class="kpi-grid" aria-label="Leadership value highlights">
          <div class="kpi">
            <div class="kpi-title">Clinical Research Enterprise Growth</div>
            <div class="kpi-text">Service line engagement, trial portfolio expansion, clinician participation models, operational enablement, performance reporting.</div>
          </div>
          <div class="kpi">
            <div class="kpi-title">NIH Infrastructure Readiness</div>
            <div class="kpi-text">Familiarity with IDeA CTR style infrastructure, pilot programs, junior investigator support, renewal planning, deliverables governance.</div>
          </div>
          <div class="kpi">
            <div class="kpi-title">Regulatory and Human Subjects Protection</div>
            <div class="kpi-text">Research integrity orientation, protocol discipline, IRB aligned workflows, consent and data governance, audit readiness culture.</div>
          </div>
          <div class="kpi">
            <div class="kpi-title">Industry Partnerships and Data Governance</div>
            <div class="kpi-text">Sponsor facing communication, operational transparency, evidence generation, policy development, analytics governance and measurement.</div>
          </div>
        </div>
      </div>
    </section>

    <section class="section">
      <h2>MaineHealth Senior Director Clinical Research Alignment</h2>
      <div class="card">
        <ul>
          <li><strong>Clinical department liaison:</strong> experience translating clinical priorities into structured research and informatics workflows that clinicians can adopt, with clear accountability and operational feasibility.</li>
          <li><strong>Expand clinical trial activity across service lines:</strong> builds engagement models, standardized intake and feasibility processes, and measurement dashboards to broaden participation and reduce friction to trial execution.</li>
          <li><strong>Research infrastructure and grant operations:</strong> familiar with NIH infrastructure program expectations including governance, deliverables tracking, pilot program structure, and junior investigator enablement.</li>
          <li><strong>Industry sponsor partnerships:</strong> sponsor facing communication style, evidence orientation, and governance narratives suitable for regulated environments and contract driven collaborations.</li>
          <li><strong>Data governance and policy:</strong> designs audit ready data flows, decision logging, and analytics policy structures to support research integrity, reproducibility, and long term program scaling.</li>
          <li><strong>Equity and access:</strong> operational approach to broad participation in research through workflow design, service line integration, and transparent inclusion metrics.</li>
        </ul>
        <p class="muted small" style="margin-top:0.75rem;">
          Note: CV emphasizes infrastructure building, service line integration, governance, and execution systems aligned to a clinical research enterprise.
        </p>
      </div>
    </section>

    <section class="section two-column">
      <div>
        <h2>Leadership Domains</h2>
        <div class="card">
          <ul>
            <li><strong>Clinical research leadership:</strong> clinical department engagement, trial enablement workflows, investigator support models, research operations alignment.</li>
            <li><strong>Translational infrastructure:</strong> program planning, core service integration, biobank and lab interface design, data and analytics enablement.</li>
            <li><strong>Clinical informatics:</strong> workflow redesign, structured data strategy, longitudinal capture, clinical adoption and usability improvement.</li>
            <li><strong>Governance and policy:</strong> research data governance, audit readiness, monitoring plans, quality and integrity frameworks.</li>
            <li><strong>Analytics for operations:</strong> performance measurement, feasibility and recruitment indicators, portfolio monitoring, reporting to leadership and sponsors.</li>
          </ul>
        </div>

        <h2 style="margin-top:1.5rem;">Core Skills</h2>
        <ul class="pill-list" aria-label="Core skills">
          <li>Clinical Trials Enablement</li>
          <li>Clinical Research Operations</li>
          <li>Service Line Integration</li>
          <li>Investigator Support</li>
          <li>Regulatory Literacy</li>
          <li>Human Subjects Protection</li>
          <li>IRB Aligned Workflows</li>
          <li>Industry Partnerships</li>
          <li>Data Governance</li>
          <li>Policy Development</li>
          <li>Clinical Informatics</li>
          <li>EHR Workflow Design</li>
          <li>Longitudinal Data Modeling</li>
          <li>Real World Evidence</li>
          <li>Observational Methods</li>
          <li>Research Reproducibility</li>
          <li>Executive Communication</li>
          <li>Cross Functional Leadership</li>
        </ul>
      </div>

      <div>
        <h2>Clinical Research and Infrastructure Focus</h2>
        <div class="card">
          <div class="subheading">NIH Infrastructure Familiarity</div>
          <ul>
            <li>IDeA CTR concepts, infrastructure governance, deliverables orientation</li>
            <li>Pilot program structure and review processes</li>
            <li>Junior investigator enablement and mentorship systems</li>
            <li>Renewal planning mindset including measurable outcomes and sustainability</li>
          </ul>

          <div class="subheading">Operational Interfaces</div>
          <ul>
            <li>Clinical trials office collaboration patterns and standardization</li>
            <li>Biobank, sample workflows, and lab and testing integration planning</li>
            <li>Research data strategy, cohort definition, and analytics governance</li>
            <li>Sponsor readiness documentation and evidence narratives</li>
          </ul>
        </div>

        <h2 style="margin-top:1.5rem;">Spoken Languages</h2>
        <div class="card">
          <ul>
            <li>Portuguese: Native</li>
            <li>English: Professional proficiency</li>
            <li>Spanish: Intermediate</li>
            <li>French: Intermediate</li>
            <li>German: Basic</li>
          </ul>
        </div>
      </div>
    </section>

    <section class="section full-width">
      <h2>Technical Skills</h2>
      <div class="card">
        <p class="small">
          I routinely apply programming and statistical languages to support clinical informatics implementation, data modeling, and applied clinical analytics.
          My primary languages include Python, R, and Stata, selected based on the analytic task, dataset structure, and reporting requirements.
        </p>

        <div class="tech-grid-full" aria-label="Technical skills grid">
          <div class="tech-card">
            <div class="tech-title">Python</div>
            <div class="tech-text">
              Development of analytics pipelines, data processing and automation, machine learning model development and evaluation, and reproducible workflow execution for clinical and operational datasets.
              Applied to operational reporting, governance monitoring, and research enablement datasets.
            </div>
          </div>

          <div class="tech-card">
            <div class="tech-title">R</div>
            <div class="tech-text">
              Statistical modeling, epidemiology focused analyses, reproducible research workflows, and generation of publication ready tables and figures.
              Used to produce defensible analysis outputs for clinical research and leadership reporting.
            </div>
          </div>

          <div class="tech-card">
            <div class="tech-title">Stata</div>
            <div class="tech-text">
              Observational study analytics, cohort and outcomes analyses, regression modeling, and clinical research focused reporting workflows commonly used in medical and public health research settings.
              Supports rapid, transparent analysis for investigator support.
            </div>
          </div>

          <div class="tech-card">
            <div class="tech-title">SQL</div>
            <div class="tech-text">
              Data extraction, cohort definition, longitudinal dataset assembly, and construction of analysis ready tables supporting governance, evidence generation, and operational monitoring.
              Enables repeatable portfolio metrics and recruitment tracking foundations.
            </div>
          </div>
        </div>

        <p class="small" style="margin-top:0.75rem;">
          These languages support end to end clinical research enablement, including structured dataset creation, data quality checks, analytics monitoring,
          feasibility measurement, and evidence generation to support clinical trial growth and translational infrastructure.
        </p>
      </div>
    </section>

    <section class="section">
      <h2>Selected Executive Impact</h2>

      <div class="item">
        <div class="item-header">
          <div>
            <div class="item-title">Clinical Informatics Consultant and Practice Transformation Lead</div>
            <div class="item-meta">Independent Consulting · 2019 to Present</div>
          </div>
        </div>
        <ul>
          <li>Led applied clinical informatics initiatives translating clinical operations into structured workflows and analyzable data assets that support research readiness and quality improvement.</li>
          <li>Designed and implemented EHR workflows, data capture strategies, and longitudinal datasets enabling decision support, operational efficiency, and evidence generation.</li>
          <li>Integrated patient generated health data and remote monitoring signals into clinical documentation and analytic pipelines, enabling continuous care and research relevant outcomes tracking.</li>
          <li>Built analytics pipelines and risk stratification methods to improve clinical insight, operational visibility, and outcome focused reporting suitable for leadership communication.</li>
          <li>Delivered end to end ownership from requirements to implementation, evaluation, and iterative improvement within clinical settings and consulting engagements.</li>
        </ul>
      </div>

      <div class="item">
        <div class="item-header">
          <div>
            <div class="item-title">Clinical AI Governance and Safety Lead</div>
            <div class="item-meta">Remote · Healthtech and Academic Collaborations · 2022 to Present</div>
          </div>
        </div>
        <ul>
          <li>Designed governance frameworks for clinical analytics and AI use emphasizing auditability, safety tradeoffs, and accountability, aligned with real clinical workflows.</li>
          <li>Executed audits identifying shortcut learning and clinically relevant failure modes in models trained on real clinical data, with emphasis on integrity, reproducibility, and risk controls.</li>
          <li>Developed adaptive model selection approaches using sequential decision methods, contributing infrastructure concepts transferable to clinical research operations and monitoring.</li>
          <li>Produced reusable artifacts and analytic workflows supporting transparent evaluation, decision logging, and post deployment monitoring suitable for regulated environments.</li>
          <li>Partnered across clinical, data science, and engineering stakeholders to align system behavior with workflow constraints and safety requirements.</li>
        </ul>
      </div>

      <div class="item">
        <div class="item-header">
          <div>
            <div class="item-title">Healthcare Business Advisor, Digital Health and AI Governance</div>
            <div class="item-meta">FxMEDUS, United States and Brazil · 2024 to Present</div>
          </div>
          <div class="item-meta">
            <a href="https://www.fxmedus.com" target="_blank" rel="noopener">fxmedus.com</a>
          </div>
        </div>
        <ul>
          <li>Advises organizations on governance, evaluation, and oversight for clinical analytics and decision support, with a focus on operationalization and adoption by clinical teams.</li>
          <li>Defines safety narratives, monitoring plans, and evidence strategies suitable for enterprise adoption, sponsor discussions, and regulated environments.</li>
          <li>Builds reproducible pipelines and reporting structures enabling scalable performance measurement and governance operations that can support trial enablement metrics.</li>
        </ul>
      </div>
    </section>

    <section class="section two-column">
      <div>
        <h2>Education</h2>

        <div class="item">
          <div class="item-header">
            <div class="item-title">MS in Health Informatics, Data Analytics</div>
            <div class="item-meta">Boston University Metropolitan College · 2025 to 2027</div>
          </div>
        </div>

        <div class="item">
          <div class="item-header">
            <div class="item-title">Global Clinical Scholars Research Training</div>
            <div class="item-meta">Harvard Medical School · 2024 to 2025</div>
          </div>
          <p class="muted small">Advanced epidemiology and public health with concentration in genetic epidemiology, translational research framing, and rigorous clinical research methods.</p>
        </div>

        <div class="item">
          <div class="item-header">
            <div class="item-title">MD, Doctor of Medicine</div>
            <div class="item-meta">Serra dos Órgãos School of Medicine, Rio de Janeiro · 1996 to 2002</div>
          </div>
        </div>

        <p class="muted small">
          Additional postgraduate training includes Medical Genetics, Medical Nutrition, Endocrinology and Metabolism,
          Medical Biochemistry, Exercise and Sports Medicine, and certificates in clinical research, machine learning,
          and genomic data science.
        </p>
      </div>

      <div>
        <h2>Clinical Foundation</h2>
        <div class="card">
          <ul>
            <li>Endocrinology and cardiometabolic prevention expertise applied to research prioritization and clinical program alignment.</li>
            <li>Fluency translating clinical risk into measurable outcomes, operational metrics, and governance controls.</li>
            <li>Experience bridging clinical operations, research protocols, and analytic execution with clear stakeholder communication.</li>
          </ul>
        </div>

        <h2 style="margin-top:1.5rem;">Board and Advisory</h2>
        <div class="card">
          <ul>
            <li>Board advisor role, American company (invited)</li>
          </ul>
          <p class="muted small">
            Focus on executive alignment, governance, and scalable clinical analytics infrastructure supporting adoption and trust.
          </p>
        </div>
      </div>
    </section>

    <section class="section">
      <h2>Selected Publications and Research Artifacts</h2>
      <div class="card">
        <ul>
          <li>
            Borges J.Y.V. (2026) Auditing Shortcut Learning in AI based Breast Cancer Genomic Subtyping. JAMIA Open.
            <a href="https://doi.org/10.1093/jamiaopen/ooaf177" target="_blank" rel="noopener">DOI:10.1093/jamiaopen/ooaf177</a>
          </li>
          <li>
            Borges J.Y.V. Machine Learning Insights for Cardiovascular Risk Prediction in Diabetic Patients: Emphasis on Renal and Cardiac Markers Using Random Forests. Submitted (MCP AIH).
          </li>
          <li>
            Borges, Julian. Multi Arm Bandit Governance for Clinical AI. Zenodo, January 14, 2026.
            <a href="https://doi.org/10.5281/zenodo.18248286" target="_blank" rel="noopener">DOI:10.5281/zenodo.18248286</a>
          </li>
          <li>
            Borges J.Y.V., Borges, Julian (2026) Adaptive FHIR Native AI Governance for Clinical Decision Support. Forthcoming.
          </li>
          <li>
            Borges J.Y.V. Innovative E Health Technologies for CVD Treatment. Medical Devices &amp; Surgical Technology Week.
            <a href="https://doi.org/10.1101/2024.06.29.24309706" target="_blank" rel="noopener">DOI:10.1101/2024.06.29.24309706</a>
          </li>
          <li>
            Borges J.Y.V. Artificial Intelligence in Pain Management: Advancing Translational Science in Digital Health Research from Bench to Bedside. Advances in Machine Learning &amp; Artificial Intelligence.
            <a href="https://doi.org/10.33140/amlai.05.03.04" target="_blank" rel="noopener">DOI:10.33140/amlai.05.03.04</a>
          </li>
          <li>
            Borges J.Y.V. Precision Medicine in Cardiology: An Evolving Understanding of Biomarkers in Coronary Artery Disease Prevention. Cardiology and Cardiovascular Medicine, 8(4).
            <a href="https://doi.org/10.26502/fccm.92920395" target="_blank" rel="noopener">DOI:10.26502/fccm.92920395</a>
          </li>
        </ul>
        <p class="muted small">
          Research positioning emphasizes deployable governance infrastructure, reproducibility, and executive grade evidence suitable for clinical adoption, sponsor confidence, and long term program growth.
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
            Reviewer for journals including PLOS Digital Health, European Heart Journal Digital Health, and European Journal of Preventive Cardiology, focused on clinical research rigor, digital health translation, and clinical analytics integrity.
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
          <li>American Medical Informatics Association</li>
          <li>American Medical Association</li>
          <li>Endocrine Society</li>
          <li>American Society for Nutrition</li>
          <li>American College of Sports Medicine</li>
          <li>American Physician Scientists Association</li>
          <li>American College of Physicians</li>
          <li>Brazilian Society of Endocrinology and Metabolism</li>
          <li>Brazilian Medical Nutrition Association</li>
          <li>Brazilian Society of Sports Medicine</li>
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
