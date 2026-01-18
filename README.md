<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Julian Y. V. Borges, MD, MS | Researcher CV (ORCID)</title>
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700;800&display=swap" rel="stylesheet">

  <style>
    :root {
      font-size: 16px;
      line-height: 1.6;
      font-family: 'Inter', system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
      color: #111827;
      background-color: #f9fafb;
      --primary: #2563eb;
      --text-muted: #6b7280;
      --bg-light: #ffffff;
      --border: #e5e7eb;
      --radius: 0.75rem;
      --shadow-lg: 0 10px 25px rgba(0, 0, 0, 0.08);
      --shadow-md: 0 4px 10px rgba(0, 0, 0, 0.05);
    }

    body {
      margin: 0;
      padding: 0;
      background: var(--background);
      -webkit-font-smoothing: antialiased;
    }

    .page {
      max-width: 1120px;
      margin: 2rem auto;
      padding: 2rem;
      background: var(--bg-light);
      border-radius: var(--radius);
      box-shadow: var(--shadow-lg);
      transition: box-shadow 0.3s ease;
    }

    .page:hover {
      box-shadow: 0 14px 35px rgba(0, 0, 0, 0.09);
    }

    h1, h2, h3, h4 {
      color: #1f2937;
      margin-top: 0;
    }

    h1 {
      font-size: 2rem;
      text-transform: uppercase;
      margin-bottom: 0.3rem;
      letter-spacing: 0.05em;
    }

    h2 {
      font-size: 1.4rem;
      border-bottom: 2px solid var(--border);
      padding-bottom: 0.5rem;
      margin-top: 2rem;
    }

    h3 {
      font-size: 1.05rem;
      margin-bottom: 0.3rem;
    }

    p, li {
      font-size: 1rem;
      color: #374151;
    }

    ul {
      padding-left: 1.25rem;
      margin: 0.5rem 0;
    }

    .muted {
      color: var(--text-muted);
    }

    .small {
      font-size: 0.92rem;
    }

    .header {
      display: flex;
      flex-wrap: wrap;
      justify-content: space-between;
      align-items: flex-start;
      gap: 1.25rem;
      padding-bottom: 1rem;
      margin-bottom: 1.25rem;
      border-bottom: 2px solid var(--border);
    }

    .header-left {
      flex: 1 1 780px;
      min-width: 320px;
    }

    .header-identity {
      display: flex;
      gap: 1rem;
      align-items: flex-start;
    }

    .header-identity-text {
      display: flex;
      flex-direction: column;
      min-width: 0;
    }

    .profile-photo {
      border-radius: var(--radius);
      object-fit: cover;
      max-height: 240px;
      aspect-ratio: 3/4;
      border: 1px solid var(--border);
      background: #fff;
      box-shadow: var(--shadow-md);
    }

    .tagline {
      margin-top: 0.2rem;
      font-weight: 600;
      color: #1e293b;
    }

    .tertiary {
      margin-top: 0.15rem;
      color: var(--text-muted);
      font-size: 0.95rem;
    }

    .badge-row {
      display: flex;
      flex-wrap: wrap;
      gap: 0.5rem;
      margin-top: 0.75rem;
    }

    .badge {
      display: inline-flex;
      align-items: center;
      gap: 0.4rem;
      background: #eef2ff;
      border: 1px solid #dbeafe;
      color: #3730a3;
      padding: 0.35rem 0.75rem;
      font-size: 0.85rem;
      border-radius: 999px;
      transition: all 0.2s ease;
    }

    .badge:hover {
      background: #e0e7ff;
      transform: translateY(-1px);
      box-shadow: 0 4px 10px rgba(37, 99, 235, 0.15);
    }

    .badge-icon {
      width: 1rem;
      height: 1rem;
      flex-shrink: 0;
    }

    .contact-wide, .keywords-frame, .card, .kpi {
      background: var(--bg-light);
      border: 1px solid var(--border);
      border-radius: var(--radius);
      padding: 1rem;
      margin-bottom: 1.5rem;
      box-shadow: var(--shadow-md);
    }

    .contact-wide-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 1rem;
    }

    .contact-wide-item .label {
      font-size: 0.92rem;
      color: var(--text-muted);
      font-weight: 600;
    }

    .contact-wide-item .value {
      margin-top: 0.15rem;
    }

    .pill-list {
      display: flex;
      flex-wrap: wrap;
      gap: 0.5rem;
      list-style: none;
      padding: 0;
      margin: 0;
    }

    .pill-list li {
      background: #f3f4f6;
      border-radius: 999px;
      padding: 0.35rem 0.75rem;
      font-size: 0.85rem;
      border: 1px solid var(--border);
      color: #1f2937;
    }

    .grid-2, .grid-3 {
      display: grid;
      gap: 1rem;
    }

    .grid-2 {
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    }

    .grid-3 {
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    }

    .item {
      margin-bottom: 1.25rem;
    }

    .item-header {
      display: flex;
      justify-content: space-between;
      flex-wrap: wrap;
      gap: 0.5rem;
      align-items: baseline;
    }

    .item-title {
      font-weight: 700;
      font-size: 1rem;
    }

    .item-meta {
      font-size: 0.9rem;
      color: var(--text-muted);
    }

    .kpi {
      background: #f9fafb;
      padding: 1rem;
    }

    .kpi-title {
      font-weight: 700;
      margin-bottom: 0.25rem;
      color: #111827;
    }

    .kpi-text {
      font-size: 0.95rem;
      color: #374151;
    }

    a {
      color: var(--primary);
      text-decoration: none;
      transition: all 0.2s ease;
    }

    a:hover {
      text-decoration: underline;
      transform: translateY(-1px);
    }

    a:focus-visible {
      outline: 3px solid rgba(37, 99, 235, 0.4);
      outline-offset: 3px;
      border-radius: 0.4rem;
    }

    @media (max-width: 720px) {
      .header-identity {
        flex-direction: column;
        align-items: flex-start;
      }

      .profile-photo {
        width: 160px;
        height: auto;
        margin-top: 0;
      }
    }

    @media print {
      :root {
        background: white;
      }

      .page {
        box-shadow: none;
        margin: 0;
        padding: 0.75in;
        border-radius: 0;
        max-width: none;
      }

      .badge {
        background: white;
        color: black;
        border: 1px solid #d1d5db;
        box-shadow: none;
      }

      a {
        color: black;
        text-decoration: none;
      }
    }
  </style>
</head>

<body>
  <main class="page">
    <!-- ✅ Your full HTML content from your previous message goes here -->
    <!-- I've already reviewed the HTML you posted and it's solid — no change needed -->
    <!-- Just keep the entire <body> content as-is -->
  </main>
</body>
</html>
