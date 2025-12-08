<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>License &amp; Commons Intent | Gofu Commons</title>
  <meta name="viewport" content="width=device-width, initial-scale=1" />

  <style>
    :root {
      --bg: #050505;
      --bg-alt: #111111;
      --text: #f5f5f5;
      --muted: #c0c0c0;
      --accent: #ffffff;
      --accent-soft: #dddddd;
      --accent-border: #333333;
      --max-width: 800px;
    }

    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      background-color: var(--bg);
      color: var(--text);
      font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI",
        Roboto, sans-serif;
      line-height: 1.6;
    }

    a {
      color: var(--accent);
      text-decoration: none;
    }

    a:hover {
      text-decoration: underline;
    }

    /* Top navigation */
    .nav {
      position: sticky;
      top: 0;
      z-index: 10;
      background: linear-gradient(to bottom, #000000, #050505);
      border-bottom: 1px solid var(--accent-border);
    }

    .nav-inner {
      max-width: var(--max-width);
      margin: 0 auto;
      padding: 0.75rem 1rem;
      display: flex;
      align-items: center;
      justify-content: space-between;
      gap: 1rem;
    }

    .brand {
      font-weight: 600;
      letter-spacing: 0.03em;
      text-transform: uppercase;
      font-size: 0.85rem;
      color: var(--accent-soft);
      white-space: nowrap;
    }

    .nav-links {
      display: flex;
      flex-wrap: wrap;
      gap: 0.75rem;
      font-size: 0.85rem;
    }

    .nav-links a {
      padding-bottom: 0.1rem;
      border-bottom: 1px solid transparent;
    }

    .nav-links a.active {
      border-bottom-color: var(--accent-soft);
    }

    /* Page layout */
    main {
      max-width: var(--max-width);
      margin: 0 auto;
      padding: 2rem 1rem 3rem 1rem;
    }

    h1, h2 {
      font-weight: 600;
      letter-spacing: 0.02em;
    }

    h1 {
      font-size: 1.8rem;
      margin-bottom: 0.5rem;
    }

    .subtitle {
      font-size: 0.95rem;
      color: var(--muted);
      margin-bottom: 2rem;
    }

    h2 {
      font-size: 1.2rem;
      margin-top: 1.8rem;
      margin-bottom: 0.6rem;
    }

    p {
      margin-bottom: 0.9rem;
      font-size: 0.96rem;
    }

    ul {
      margin: 0.5rem 0 1rem 1.3rem;
      font-size: 0.95rem;
    }

    li {
      margin-bottom: 0.4rem;
    }

    .section-card {
      background: var(--bg-alt);
      border: 1px solid var(--accent-border);
      border-radius: 0.75rem;
      padding: 1.1rem 1rem;
      margin-top: 0.8rem;
    }

    .note {
      font-size: 0.85rem;
      color: var(--muted);
      margin-top: 1.2rem;
      border-top: 1px solid var(--accent-border);
      padding-top: 0.75rem;
    }

    @media (max-width: 600px) {
      main {
        padding-top: 1.6rem;
      }
    }
  </style>
</head>
<body>
  <!-- Top navigation -->
  <header class="nav">
    <div class="nav-inner">
      <a href="index.html" class="brand">Gofu Commons</a>
      <nav class="nav-links">
        <a href="index.html">Home</a>
        <a href="why-gofu.html">Why Gofu?</a>
        <a href="make-gofu.html">Make Gofu</a>
        <a href="license.html" class="active">License</a>
      </nav>
    </div>
  </header>

  <!-- Page content -->
  <main>
    <h1>License &amp; Commons Intent</h1>
    <p class="subtitle">
      Gofu is not a product to be owned. It is a practice to be shared.
    </p>

    <section>
      <h2>CC0 1.0 Universal (Public Domain Dedication)</h2>
      <div class="section-card">
        <p>
          Unless otherwise noted, all text, recipes, and materials in this
          repository are dedicated to the public domain under
          <strong>CC0 1.0 Universal</strong>.
        </p>
        <p>
          In practical terms, this means:
        </p>
        <ul>
          <li>You may copy, modify, distribute, and use the material, including for commercial purposes.</li>
          <li>No permission is required.</li>
          <li>No attribution is legally required.</li>
        </ul>
        <p>
          The goal is to let Gofu travel freely: into home kitchens, school kitchens,
          community kitchens, and relief efforts — without legal friction.
        </p>
        <p class="note">
          For full legal language, see:
          <a href="https://creativecommons.org/publicdomain/zero/1.0/">
            https://creativecommons.org/publicdomain/zero/1.0/
          </a>
        </p>
      </div>
    </section>

    <section>
      <h2>Why this choice?</h2>
      <p>
        Many of the communities that might benefit from Gofu the most are also the
        ones least able to navigate licensing complexity, legal counsel, or
        permission requests. CC0 removes as many barriers as possible.
      </p>
      <p>
        By placing this work in the public domain, we affirm a simple principle:
        <strong>everyone has a right to accessible, nourishing food practices that
        can be learned, adapted, and passed on.</strong>
      </p>
    </section>

    <section>
      <h2>Attribution (optional, but appreciated)</h2>
      <div class="section-card">
        <p>
          While attribution is not required under CC0, it can still be a powerful
          way to honor the lineage and help others find their way back to the
          commons.
        </p>
        <p>
          If you choose to credit this work, a simple line such as the following is
          more than enough:
        </p>
        <p><em>
          “Based on the Gofu Commons project (public domain, CC0 1.0).”
        </em></p>
        <p>
          You are also welcome to name your own variations and branches. New names,
          new stories, and new local practices are part of how a living commons grows.
        </p>
      </div>
    </section>

    <section>
      <h2>Responsibility &amp; care</h2>
      <p>
        Freedom does not remove responsibility. Anyone using or adapting Gofu
        methods is responsible for:
      </p>
      <ul>
        <li>following basic food safety practices,</li>
        <li>respecting local health guidelines,</li>
        <li>being honest about what is experimental or untested,</li>
        <li>and caring for the people they feed.</li>
      </ul>

      <p class="note">
        If you carry Gofu into vulnerable settings (shelters, relief kitchens,
        schools, elder care, etc.), please do so with thoughtful testing, local
        collaboration, and clear communication.
      </p>
    </section>
  </main>
</body>
</html>
