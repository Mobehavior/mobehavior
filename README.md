## Hi there 👋

<!--
**Mobehavior/mobehavior** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Mo Behavior Therapy</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet" />
  <style>
    body {
      position: relative;

      transition: background-image 1.5s ease-in-out;

      animation: changeBackground 30s infinite ease-in-out;

      background-image: url('https://images.unsplash.com/photo-1607746882042-944635dfe10e?fit=crop&w=1600&q=80');
      background-size: cover;
      background-attachment: fixed;
      background-position: center;
      backdrop-filter: brightness(0.97);

      margin: 0;
      font-family: 'Poppins', sans-serif;
      background: #f7faff;
      color: #333;
    }
    header {
      background-color: #114b8a;
      color: white;
      padding: 1.2rem 2rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
      position: sticky;
      top: 0;
      z-index: 1000;
    }
    header h1 {
      font-size: 1.8rem;
    }
    nav a {
      color: white;
      text-decoration: none;
      margin-left: 2rem;
      font-weight: 500;
      transition: color 0.3s;
    }
    nav a:hover {
      color: #ffcb05;
    }
    .hero {
      background: linear-gradient(to right, #66c2ff, #a2d2ff);
      padding: 6rem 2rem;
      text-align: center;
      color: white;
    }
    .hero h2 {
      font-size: 2.8rem;
      margin-bottom: 1rem;
    }
    .hero p {
      font-size: 1.2rem;
      margin-bottom: 2rem;
    }
    .cta-button {
      background-color: #ffcb05;
      color: #114b8a;
      font-weight: bold;
      border: none;
      padding: 1rem 2rem;
      font-size: 1rem;
      border-radius: 50px;
      cursor: pointer;
      transition: background 0.3s;
    }
    .cta-button:hover {
      background-color: #ffc107;
    }
    section {
      background-color: rgba(255, 255, 255, 0.95);
      border-radius: 16px;
      box-shadow: 0 8px 16px rgba(0,0,0,0.05);

      padding: 4rem 2rem;
      max-width: 1200px;
      margin: auto;
    }
    section h2 {
      text-align: center;
      font-size: 2.2rem;
      margin-bottom: 2rem;
      color: #114b8a;
    }
    .puzzle-button {
      background: #007bff;
      color: white;
      border: none;
      padding: 0.8rem 1.5rem;
      border-radius: 30px;
      margin: 0.5rem;
      cursor: pointer;
      font-weight: 500;
      box-shadow: 0 4px 8px rgba(0, 123, 255, 0.2);
      transition: background 0.3s;
    }
    .puzzle-button:hover {
      background: #0056b3;
    }
    .team-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 2rem;
      margin-top: 2rem;
    }
    .team-member {
    transition: transform 0.3s ease, box-shadow 0.3s ease;
      background: white;
      padding: 1.5rem;
      border-radius: 12px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.05);
      text-align: center;
    }
    .team-member:hover {
    transform: translateY(-10px);
    box-shadow: 0 8px 20px rgba(0,0,0,0.1);
  }

  .team-member h3 {
      margin-bottom: 0.5rem;
      color: #114b8a;
    }
    form {
      background: white;
      padding: 2rem;
      border-radius: 12px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.05);
      max-width: 600px;
      margin: 2rem auto;
    }
    form input, form textarea {
      width: 100%;
      padding: 0.8rem;
      margin: 0.5rem 0;
      border: 1px solid #ccc;
      border-radius: 8px;
    }
    form button {
      background: #114b8a;
      color: white;
      padding: 0.8rem 2rem;
      border: none;
      border-radius: 8px;
      font-size: 1rem;
      cursor: pointer;
    }
    footer {
      background: #114b8a;
      color: white;
      text-align: center;
      padding: 2rem 1rem;
      margin-top: 4rem;
    }
    @media (max-width: 768px) {
  nav#main-nav {
    animation: slideDown 0.4s ease;
    box-shadow: 0 4px 12px rgba(0,0,0,0.2);
  }
  #menu-toggle {
    display: block;
  }
  nav#main-nav {
    display: none;
    flex-direction: column;
    align-items: center;
    background-color: #114b8a;
    width: 100%;
  }
  nav#main-nav a {
    margin: 1rem 0;
  }
  .hero h2 {
    font-size: 2rem;
  }
  .hero p {
    font-size: 1rem;
  }
  .cta-button {
    font-size: 0.9rem;
    padding: 0.8rem 1.5rem;
  }
  .puzzle-button {
    padding: 0.6rem 1.2rem;
    font-size: 0.9rem;
  }
  .team-grid {
    grid-template-columns: 1fr;
  }
  form {
    padding: 1.5rem;
  }
  section {
    padding: 2rem 1rem;
  }
      header {
        flex-direction: column;
        text-align: center;
      }
      nav {
        margin-top: 1rem;
      }
    }
    details {
    background: #fff;
    border-radius: 8px;
    padding: 1rem;
    margin-bottom: 1rem;
    box-shadow: 0 2px 6px rgba(0, 0, 0, 0.05);
    transition: all 0.3s ease;
  }
  details[open] summary {
    color: #114b8a;
    font-weight: bold;
  }
  summary {
    cursor: pointer;
    font-size: 1rem;
    transition: color 0.3s ease;
  }
  summary:hover {
    color: #007bff;
  }
  #seguros img {
    max-width: 150px;
    height: auto;
    transition: transform 0.3s ease;
  }
  #seguros img:hover {
    transform: scale(1.05);
  }
  @keyframes bounce {
    0% { transform: translateY(0); }
    100% { transform: translateY(-10px); }
  }
@keyframes changeBackground {
  0% {
    background-image: url('https://images.unsplash.com/photo-1607746882042-944635dfe10e?fit=crop&w=1600&q=80');
  }
  33% {
    background-image: url('https://images.unsplash.com/photo-1509817316-86660f17b5c4?fit=crop&w=1600&q=80');
  }
  66% {
    background-image: url('https://images.unsplash.com/photo-1607746881985-38b8c5c8c4fb?fit=crop&w=1600&q=80');
  }
  100% {
    background-image: url('https://images.unsplash.com/photo-1607746882042-944635dfe10e?fit=crop&w=1600&q=80');
  }
}
  .overlay {
    content: "";
    position: fixed;
    top: 0;
    left: 0;
    width: 100vw;
    height: 100vh;
    background: rgba(0, 0, 0, 0.3);
    backdrop-filter: blur(3px);
    z-index: -1;
  }
  .fade-in {
    opacity: 0;
    transform: translateY(30px);
    animation: fadeInUp 1s ease forwards;
  }
  @keyframes fadeInUp {
    to {
      opacity: 1;
      transform: translateY(0);
    }
  }
  .fade-in {
    opacity: 0;
    transform: translateY(30px);
    transition: opacity 1s ease, transform 1s ease;
  }
  .fade-in-visible {
    opacity: 1;
    transform: translateY(0);
  }
@keyframes slideDown {
  0% {
    opacity: 0;
    transform: translateY(-10px);
  }
  100% {
    opacity: 1;
    transform: translateY(0);
  }
}
  .nav-overlay {
    position: fixed;
    top: 0;
    left: 0;
    width: 100vw;
    height: 100vh;
    background: rgba(0, 0, 0, 0.4);
    z-index: 999;
    display: none;
  }
</style>
<script async src="https://www.googletagmanager.com/gtag/js?id=G-XXXXXXXXXX"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'G-XXXXXXXXXX');
</script>
</head>
<body>
  <div class="nav-overlay" id="navOverlay" onclick="closeMenu()"></div>
  <div class="overlay"></div>
  <header style="justify-content: flex-start; gap: 1rem;">
  <a href="#" style="display: flex; align-items: center;"><img src="https://drive.google.com/uc?export=view&id=1ZA3MY7PsvQUMA3ae3YSFnrs21ZmxrAXz" alt="Mo Behavior Therapy Logo" style="height: 60px; margin-right: 1rem; max-width: 180px;"></a>
  <h1>Mo Behavior Therapy</h1>
  <button id="menu-toggle" style="background:none; border:none; color:white; font-size:1.8rem; display:none; cursor:pointer;">☰</button>
  <nav id="main-nav">
      <a href="#nosotros">Nosotros</a>
      <a href="#faq">FAQ</a>
      <a href="#seguros">Seguros</a>
      <a href="#servicios">Servicios</a>
      <a href="#equipo">Equipo</a>
      <a href="#contacto">Contacto</a>
    </nav>
  </header>

  <section class="hero fade-in">
    <h2>Transformando Vidas a Través del ABA</h2>
    <p>Apoyando a niños con autismo y sus familias con compasión y ciencia.</p>
    <a href="#contacto" class="cta-button">Solicita una Consulta Gratuita</a>
  </section>

  <section id="nosotros" class="fade-in" style="background-image: url('https://images.unsplash.com/photo-1589820296154-3a7b636b8a1c?fit=crop&w=1600&q=80'); background-size: cover; background-position: center; background-repeat: no-repeat; background-blend-mode: overlay; background-color: rgba(255,255,255,0.85); background-attachment: fixed;">
    <h2>Sobre Nosotros</h2>
    <p style="text-align: center; max-width: 800px; margin: auto;">En Mo Behavior Therapy, estamos comprometidos con el crecimiento y bienestar de cada niño. Utilizamos los principios del Análisis de Comportamiento Aplicado (ABA) para brindar intervenciones personalizadas, eficaces y humanas.</p>
  </section>

  <section id="servicios" class="fade-in" style="background-image: url('https://images.unsplash.com/photo-1607746881905-065f8cbf45f1?fit=crop&w=1600&q=80'); background-size: cover; background-position: center; background-repeat: no-repeat; background-blend-mode: overlay; background-color: rgba(255,255,255,0.95);">
  <h2>Servicios</h2>
  <div style="display: flex; flex-wrap: wrap; justify-content: center; gap: 1.5rem;">
    <button class="puzzle-button" onclick="toggleInfo('evaluacion')">🧩 Evaluación ABA</button>
    <button class="puzzle-button" onclick="toggleInfo('intervencion')">🧩 Intervención Temprana</button>
    <button class="puzzle-button" onclick="toggleInfo('padres')">🧩 Entrenamiento para Padres</button>
    <button class="puzzle-button" onclick="toggleInfo('apoyo')">🧩 Apoyo Conductual</button>
  </div>
  <div id="servicios-descripcion" style="margin-top: 2rem; max-width: 800px; margin-inline: auto;">
    <div id="evaluacion" class="servicio-info" style="display:none;">
      <img src="https://cdn-icons-png.flaticon.com/512/3135/3135715.png" alt="Evaluación ABA" style="width:80px; margin-bottom: 1rem; animation: bounce 1s infinite alternate;">
      <h3>Evaluación ABA</h3>
      <p>Evaluamos las fortalezas y necesidades del niño mediante observaciones, entrevistas y herramientas estandarizadas. A partir de esto, creamos un plan de intervención individualizado.</p>
    </div>
    <div id="intervencion" class="servicio-info" style="display:none;">
      <img src="https://cdn-icons-png.flaticon.com/512/3448/3448440.png" alt="Intervención Temprana" style="width:80px; margin-bottom: 1rem; animation: bounce 1s infinite alternate;">
      <h3>Intervención Temprana</h3>
      <p>Enfocada en niños pequeños para fomentar habilidades del lenguaje, sociales y cognitivas. Las sesiones se diseñan para ser lúdicas y efectivas.</p>
    </div>
    <div id="padres" class="servicio-info" style="display:none;">
      <img src="https://cdn-icons-png.flaticon.com/512/2995/2995368.png" alt="Entrenamiento para Padres" style="width:80px; margin-bottom: 1rem; animation: bounce 1s infinite alternate;">
      <h3>Entrenamiento para Padres</h3>
      <p>Brindamos a los padres estrategias prácticas y personalizadas para continuar el progreso en casa, asegurando coherencia entre ambientes.</p>
    </div>
    <div id="apoyo" class="servicio-info" style="display:none;">
      <img src="https://cdn-icons-png.flaticon.com/512/4014/4014485.png" alt="Apoyo Conductual" style="width:80px; margin-bottom: 1rem; animation: bounce 1s infinite alternate;">
      <h3>Apoyo Conductual</h3>
      <p>Intervenciones en el hogar o escuela para reducir conductas desafiantes y fomentar habilidades adaptativas en contextos reales.</p>
    </div>
  </div>
</section>
<script>
  function toggleInfo(id) {
    const sections = document.querySelectorAll('.servicio-info');
    sections.forEach(sec => sec.style.display = 'none');
    document.getElementById(id).style.display = 'block';
  }
  const observer = new IntersectionObserver((entries) => {
    entries.forEach(entry => {
      if (entry.isIntersecting) {
        entry.target.classList.add('fade-in-visible');
        observer.unobserve(entry.target);
      }
    });
  }, { threshold: 0.1 });

  document.querySelectorAll('.fade-in').forEach(section => {
    observer.observe(section);
  });
document.getElementById('menu-toggle').addEventListener('click', () => {
  const nav = document.getElementById('main-nav');
  const overlay = document.getElementById('navOverlay');
  const isOpen = nav.style.display === 'flex';
  nav.style.display = isOpen ? 'none' : 'flex';
  overlay.style.display = isOpen ? 'none' : 'block';
});
function closeMenu() {
  document.getElementById('main-nav').style.display = 'none';
  document.getElementById('navOverlay').style.display = 'none';
}
</script>

  <section id="equipo" class="fade-in" style="background-image: url('https://images.unsplash.com/photo-1588072432836-e10032774350?fit=crop&w=1600&q=80'); background-size: cover; background-position: center; background-repeat: no-repeat; background-blend-mode: overlay; background-color: rgba(255,255,255,0.95);">
    <h2>Nuestro Equipo</h2>
    <div class="team-grid">
      <div class="team-member">
        <h3>Mauricio Garcia</h3>
        <p>Fundador y Analista de Comportamiento</p>
        <p>Más de 10 años de experiencia en ABA, liderazgo y formación de terapeutas.</p>
      </div>
      <div class="team-member">
        <h3>Laura Pérez</h3>
        <p>BCBA – Supervisora Clínica</p>
        <p>Especialista en intervención temprana y apoyo familiar continuo.</p>
      </div>
      <div class="team-member">
        <h3>Carlos Ramírez</h3>
        <p>RBT – Terapeuta Conductual</p>
        <p>Ayuda a los niños a desarrollar habilidades sociales y comunicativas.</p>
      </div>
    </div>
  </section>

  <section id="contacto" class="fade-in">
    <h2>Contáctanos</h2>
    <p style="text-align: center;">Dirección: 130 South Indian River Drive, Suite 237, Fort Pierce, FL, 34950<br>
    Teléfono: +1 (305) 795-0600<br>
    Email: mobehavior@mobehaviortherapy.com</p>
    <form>
      <input type="text" placeholder="Nombre" required />
      <input type="email" placeholder="Correo Electrónico" required />
      <input type="tel" placeholder="Teléfono" />
      <input type="text" placeholder="Asunto" />
      <textarea placeholder="Mensaje" rows="4"></textarea>
      <button type="submit">Enviar Mensaje</button>
    </form>
  </section>

  <section id="faq" class="fade-in">
    <h2>Preguntas Frecuentes (FAQ)</h2>
    <div style="max-width: 800px; margin: auto;">
      <details><summary><strong>¿Qué es la terapia ABA?</strong></summary><p>ABA (Análisis de Comportamiento Aplicado) es una terapia basada en la ciencia del comportamiento que enseña habilidades y reduce conductas problemáticas.</p></details>
      <details><summary><strong>¿Para quién está dirigida la terapia ABA?</strong></summary><p>Principalmente para niños con trastornos del espectro autista, aunque también es útil en otras condiciones del desarrollo.</p></details>
      <details><summary><strong>¿Cómo se inicia un tratamiento ABA?</strong></summary><p>Se comienza con una evaluación funcional del comportamiento, seguida por la creación de un plan individualizado.</p></details>
      <details><summary><strong>¿Dónde se brinda la terapia ABA?</strong></summary><p>Puede realizarse en el hogar, la escuela, o en nuestra clínica según las necesidades del niño.</p></details>
      <details><summary><strong>¿Quiénes brindan la terapia?</strong></summary><p>BCBAs (Analistas de Comportamiento Certificados) y RBTs (Técnicos Registrados en Comportamiento).</p></details>
      <details><summary><strong>¿Cuánto dura la terapia ABA?</strong></summary><p>Depende del caso, pero muchas veces se recomienda un mínimo de 10 a 20 horas semanales.</p></details>
      <details><summary><strong>¿La terapia ABA está cubierta por seguros?</strong></summary><p>Sí, aceptamos múltiples planes de seguro que cubren ABA. Ver la sección de aseguradoras.</p></details>
      <details><summary><strong>¿Cómo involucran a los padres en el tratamiento?</strong></summary><p>Ofrecemos entrenamiento continuo para padres y cuidadores como parte integral del proceso.</p></details>
      <details><summary><strong>¿Qué resultados se pueden esperar?</strong></summary><p>Mejoras en habilidades comunicativas, sociales, académicas y reducción de conductas desafiantes.</p></details>
      <details><summary><strong>¿Qué diferencia a Mo Behavior Therapy?</strong></summary><p>Nuestro enfoque personalizado, trato humano y experiencia clínica nos distingue.</p></details>
    </div>
  </section>

  <section id="seguros" class="fade-in">
    <h2>Aseguradoras Aceptadas</h2>
    <div style="display: flex; flex-wrap: wrap; justify-content: center; gap: 2rem; align-items: center; margin-top: 2rem;">
      <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/4/4f/Aetna_logo.svg/200px-Aetna_logo.svg.png" alt="Aetna" height="50">
      <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/67/Humana_logo.svg/200px-Humana_logo.svg.png" alt="Humana" height="50">
      <img src="https://upload.wikimedia.org/wikipedia/en/thumb/1/1d/Community_Care_Plan_logo.png/200px-Community_Care_Plan_logo.png" alt="Community Care Plan" height="50">
      <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/3c/Sunshine_Health_logo.png/200px-Sunshine_Health_logo.png" alt="Sunshine Health" height="50">
      <img src="https://upload.wikimedia.org/wikipedia/en/thumb/3/33/CMS_logo.svg/200px-CMS_logo.svg.png" alt="CMS" height="50">
      <img src="https://upload.wikimedia.org/wikipedia/en/thumb/9/9e/Simply_Healthcare_Plans_logo.png/200px-Simply_Healthcare_Plans_logo.png" alt="Simply" height="50">
    </div>
  </section>

  <footer>
    <div style="margin-bottom: 1rem;">
      <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3522.9847378822584!2d-80.3250003!3d27.4475824!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x88ded2ee2bd5a78d%3A0x3d78cda4ab8415a!2s130%20S%20Indian%20River%20Dr%20%23237%2C%20Fort%20Pierce%2C%20FL%2034950%2C%20USA!5e0!3m2!1sen!2sus!4v1713214000000!5m2!1sen!2sus" width="100%" height="250" style="border:0; border-radius: 8px;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
    </div>
    <div style="margin-bottom: 1rem;">
      <a href="https://www.facebook.com/mobehaviortherapy" target="_blank" style="margin: 0 10px;"><img src="https://cdn-icons-png.flaticon.com/512/733/733547.png" alt="Facebook" width="30"></a>
      <a href="https://www.instagram.com/mobehaviortherapy" target="_blank" style="margin: 0 10px;"><img src="https://cdn-icons-png.flaticon.com/512/733/733558.png" alt="Instagram" width="30"></a>
      <a href="https://www.linkedin.com/company/mobehaviortherapy" target="_blank" style="margin: 0 10px;"><img src="https://cdn-icons-png.flaticon.com/512/733/733561.png" alt="LinkedIn" width="30"></a>
    </div>
    <p>&copy; 2025 Mo Behavior Therapy. Todos los derechos reservados.</p>
  </footer>
</body>
</html>

