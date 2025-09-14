<!doctype html>
<html lang="es">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Segundo Mundo | Klezmer</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600&display=swap" rel="stylesheet">
  <style>
    :root {
      --bg: #ffffff;
      --card-bg: #f8f9fa;
      --text: #212529;
      --muted: #6c757d;
      --btn-bg: #343a40;
      --btn-hover: #495057;
      --btn-text: #ffffff;
    }
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }
    body {
      background-color: var(--bg);
      color: var(--text);
      font-family: 'Inter', sans-serif;
      display: flex;
      justify-content: center;
      align-items: flex-start;
      min-height: 100vh;
      padding: 20px;
    }
    .card {
      width: 100%;
      max-width: 420px;
      background-color: var(--card-bg);
      border-radius: 12px;
      padding: 24px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.1);
      text-align: center;
    }
    .avatar {
      width: 100px;
      height: 100px;
      border-radius: 50%;
      overflow: hidden;
      margin: 0 auto 16px;
      background-color: #ddd;
    }
    .avatar img {
      width: 100%;
      height: 100%;
      object-fit: cover;
    }
    h1 {
      font-size: 24px;
      margin-bottom: 8px;
      font-weight: 600;
    }
    p.bio {
      font-size: 16px;
      color: var(--muted);
      margin-bottom: 24px;
    }
    .links {
      display: flex;
      flex-direction: column;
      gap: 12px;
    }
    .links a {
      display: block;
      padding: 12px;
      background-color: var(--btn-bg);
      color: var(--btn-text);
      text-decoration: none;
      border-radius: 8px;
      font-weight: 500;
      transition: background-color 0.2s ease;
    }
    .links a:hover {
      background-color: var(--btn-hover);
    }
    .socials {
      display: flex;
      justify-content: center;
      gap: 12px;
      margin-top: 24px;
    }
    .socials a {
      color: var(--muted);
      text-decoration: none;
      font-size: 20px;
    }
    /* Video embebido estilo */
    .video-wrap {
      margin: 24px 0;
      position: relative;
      padding-bottom: 56.25%; /* 16:9 */
      height: 0;
      overflow: hidden;
      border-radius: 8px;
    }
    .video-wrap iframe, .video-wrap video {
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
    }
    @media (max-width: 480px) {
      .card {
        padding: 16px;
      }
      h1 {
        font-size: 20px;
      }
      p.bio {
        font-size: 14px;
      }
    }
  </style>
</head>
<body>
  <div class="card">
    <!-- Avatar si lo tenés, si no dejá este div vacío o pon otra imagen -->
    <div class="avatar">
      <
