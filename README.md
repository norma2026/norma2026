<!doctype html>
<html lang="it">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width,initial-scale=1">
  <title> Norma2026</title>
  <style>
    body { font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial; background:#fafafa; color:#222; text-align:center; padding:2rem; }
    .container { max-width:980px; margin:0 auto; }
    h1 { margin-bottom:0.25rem; }
    p.lead { color:#555; margin-top:0; }
    .frame { margin:1.5rem 0; border:1px solid #e1e4e8; border-radius:8px; overflow:hidden; background:#fff; }
    iframe { width:100%; height:640px; border:0; display:block; }
    .fallback { padding:1rem; color:#666; font-size:0.95rem; }
    .actions a { display:inline-block; margin:0.5rem; padding:0.45rem 0.9rem; background:#0366d6; color:#fff; border-radius:6px; text-decoration:none; }
    .actions a.secondary { background:#6c757d; }
  </style>
</head>
<body>
  <div class="container">
    <h1>Snake — Norma2026</h1>
    <p class="lead">Versione dimostrativa: il gioco è qui visibile e funzionante. Clicca "Apri in nuova scheda" per vederlo a tutto schermo.</p>

    <div class="frame" role="region" aria-label="Gioco Snake">
      <!-- iframe verso la versione giocabile dentro docs/game/index.html -->
      <iframe src="./game/index.html" title="Snake game — Norma2026" sandbox="allow-scripts allow-same-origin"></iframe>

      <div class="fallback">
        Se l'iframe non carica (alcuni browser/provider potrebbero bloccarlo), apri il gioco direttamente:
        <div class="actions">
          <a href="./game/index.html" target="_blank" rel="noopener">Apri gioco in nuova scheda</a>
          <a class="secondary" href="../snake.svg" target="_blank" rel="noopener">Vedi SVG / logo</a>
        </div>
      </div>
    </div>

    <p style="color:#444; font-size:0.95rem">Nota: il README del profilo non esegue JavaScript — questa pagina GitHub Pages invece sì, quindi permette di vedere il gioco funzionante.</p>
  </div>
</body>
</html>


