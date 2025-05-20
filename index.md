# MapleRaiders Bot

<div id="content-es" style="display: none;">
  <h2>👾 Bienvenido a MapleRaiders</h2>
  <p>Este bot de Discord te permite organizar <strong>raids de jefes (bosses)</strong> en MapleStory de forma rápida, ordenada y automatizada.</p>

  <h3>📌 Comando principal</h3>
  <ul>
    <li><code>/boss</code> — Programa una raid especificando el boss, dificultad, fecha y hora. Crea un canal y rol temporales.</li>
    <li>Los participantes confirman con botones interactivos.</li>
    <li>El organizador puede cancelar la raid en cualquier momento.</li>
  </ul>

  <h3>⚙️ Configuración</h3>
  <ul>
    <li><code>/bosscfg</code> — Permite al administrador configurar el idioma, la categoría donde se crean los canales y los roles con permiso para usar <code>/boss</code>.</li>
  </ul>

  <h3>💬 Idiomas disponibles</h3>
  <ul>
    <li>Español 🇪🇸</li>
    <li>Inglés 🇺🇸</li>
  </ul>

  <h3>📎 Ejemplo</h3>
  <pre><code>/boss boss:Will difficulty:Normal date:05-20 hour:18:30 confirmations:6 reminder_hours:2</code></pre>

  <p>Este comando creará un canal privado y asignará roles temporales a quienes confirmen.</p>

  <p>🔒 Solo los administradores pueden acceder a la configuración.</p>
</div>

<div id="content-en" style="display: none;">
  <h2>👾 Welcome to MapleRaiders</h2>
  <p>This Discord bot helps you organize <strong>MapleStory boss raids</strong> in a fast, clean, and automated way.</p>

  <h3>📌 Main command</h3>
  <ul>
    <li><code>/boss</code> — Schedules a raid by specifying the boss, difficulty, date and time. It auto-creates a channel and temporary role.</li>
    <li>Participants confirm with interactive buttons.</li>
    <li>The organizer can cancel the raid at any time.</li>
  </ul>

  <h3>⚙️ Configuration</h3>
  <ul>
    <li><code>/bosscfg</code> — Allows server admins to set the language, raid category, and roles allowed to use <code>/boss</code>.</li>
  </ul>

  <h3>💬 Supported Languages</h3>
  <ul>
    <li>Spanish 🇪🇸</li>
    <li>English 🇺🇸</li>
  </ul>

  <h3>📎 Example</h3>
  <pre><code>/boss boss:Will difficulty:Normal date:05-20 hour:18:30 confirmations:6 reminder_hours:2</code></pre>

  <p>This command creates a private channel and assigns temporary roles to confirmed users.</p>

  <p>🔒 Only administrators can access the configuration command.</p>
</div>

<script>
  const lang = navigator.language || navigator.userLanguage;
  if (lang.startsWith("es")) {
    document.getElementById("content-es").style.display = "block";
  } else {
    document.getElementById("content-en").style.display = "block";
  }
</script>
