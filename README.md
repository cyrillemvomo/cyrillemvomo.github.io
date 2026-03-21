<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Cyrille Mvomo</title>
  <style>
    :root {
      --bg: #e9e9e9;
      --text: #000000;
      --accent: crimson;
    }

    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      background-color: var(--bg);
      color: var(--text);
      font-family: Arial, Helvetica, sans-serif;
    }

    a {
      color: var(--accent);
      text-decoration: underline;
    }

    .top-banner {
      width: 100%;
      padding: 14px 28px;
      display: flex;
      align-items: center;
      justify-content: flex-start;
      background-color: var(--bg);
    }

    .top-links {
      display: flex;
      align-items: center;
      gap: 12px;
      flex-wrap: wrap;
    }

    .icon-link {
      display: inline-flex;
      align-items: center;
      justify-content: center;
      text-decoration: none;
    }

    .icon-link img {
      width: 22px;
      height: 22px;
      display: block;
      filter: brightness(0);
      transition: filter 0.2s ease;
      cursor: pointer;
    }

    .icon-link:hover img {
      filter: brightness(0) saturate(100%) invert(17%) sepia(96%) saturate(4632%) hue-rotate(338deg) brightness(92%) contrast(94%);
    }

    .separator {
      font-size: 18px;
      line-height: 1;
      color: var(--text);
      user-select: none;
    }
  </style>
</head>
<body>
  <header class="top-banner">
    <nav class="top-links" aria-label="Social and contact links">
      <a class="icon-link" href="mailto:cyrille.mvomo@mail.mcgill.ca" aria-label="Email">
        <img src="INSERT-EMAIL-LOGO-LINK-HERE" alt="Email logo" />
      </a>

      <span class="separator">/</span>

      <a class="icon-link" href="https://www.linkedin.com/in/cyrille-mvomo" target="_blank" rel="noopener noreferrer" aria-label="LinkedIn">
        <img src="INSERT-LINKEDIN-LOGO-LINK-HERE" alt="LinkedIn logo" />
      </a>

      <span class="separator">/</span>

      <a class="icon-link" href="https://scholar.google.fr/citations?user=v-sf1K8AAAAJ&hl=fr&oi=ao" target="_blank" rel="noopener noreferrer" aria-label="Google Scholar">
        <img src="INSERT-GOOGLE-SCHOLAR-LOGO-LINK-HERE" alt="Google Scholar logo" />
      </a>

      <span class="separator">/</span>

      <a class="icon-link" href="https://github.com/cyrillemvomo" target="_blank" rel="noopener noreferrer" aria-label="GitHub">
        <img src="INSERT-GITHUB-LOGO-LINK-HERE" alt="GitHub logo" />
      </a>
    </nav>
  </header>
</body>
</html>
