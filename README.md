<div class="skill-row">
        <div class="skill-icon c3">SY</div>
        <div class="skill-text"><b>Systems &amp; Infrastructure:</b> Comfortable across databases, networking, and deployment — thinking in full systems, not just screens.</div>
      </div>

      <div class="terminal">
        <div class="term-bar"><span></span><span></span><span></span></div>
        <div class="term-body">
          <span class="k">const</span> engineer = {<br>
          &nbsp;&nbsp;name: <span class="s">"Noura Al-Qathami"</span>,<br>
          &nbsp;&nbsp;role: <span class="s">"Full-Stack / Full-System Engineer"</span>,<br>
          &nbsp;&nbsp;status: <span class="c">"welcoming you"</span><span class="cursor"></span><br>
          };
        </div>
      </div>
    </div>
  </div>

  <div class="footer-note">DESIGNED FOR NOURA · ENGINEERING PORTFOLIO</div>

</div>

<script>
  const lines = [
    "function buildSystem(idea) {","  const arch = design(idea);","  return deploy(arch);","}",
    "class API extends Server {","  handle(req, res) { ... }","}",
    "SELECT * FROM projects","WHERE status = 'shipped';",
    "git commit -m 'ship it'","npm run build","docker compose up -d",
    "const db = connect(config);","export default App;",
    "if (bug) { fix(bug); test(); }","async function sync() { await queue.flush(); }"
  ];
  let out = [];
  for(let i=0;i<26;i++){ out.push(lines[Math.floor(Math.random()*lines.length)]); }
  document.getElementById('codeVeil').textContent = out.join("\n");
</script>
</body>
</html>
