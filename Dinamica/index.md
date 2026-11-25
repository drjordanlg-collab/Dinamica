<!-- Carga de fuente oficial de Ubuntu y soporte para fórmulas LaTeX (MathJax) -->
<link href="https://googleapis.com" rel="stylesheet">
<script>
  MathJax = {
    tex: {
      inlineMath: [['$', '$'], ['\\(', '\\)']],
      displayMath: [['$$', '$$'], ['\\[', '\\]']]
    }
  };
</script>
<script id="MathJax-script" async src="https://jsdelivr.net"></script>

<style>
  body {
    background-color: #F7F7F7;
    font-family: 'Ubuntu', -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
    color: #333333;
    margin: 0;
    padding: 30px 15px;
  }

  /* Contenedor principal estilo Ubuntu */
  .ubuntu-card {
    background: linear-gradient(135deg, #300A24 0%, #5E2750 100%);
    color: #FFFFFF;
    max-width: 850px;
    margin: 0 auto;
    padding: 40px;
    border-radius: 12px;
    box-shadow: 0 12px 28px rgba(48, 10, 36, 0.3);
    border-top: 6px solid #E95420;
  }

  .ubuntu-card h1 {
    color: #FFFFFF;
    border-bottom: 2px solid #E95420;
    padding-bottom: 12px;
    margin-top: 0;
    font-size: 2.2em;
  }

  .ubuntu-card h2 {
    color: #E95420;
    margin-top: 30px;
    font-size: 1.5em;
  }

  /* Cuadrícula de 2 columnas para los subtemas */
  .temas-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 16px;
    margin-top: 20px;
  }

  .tema-box {
    background-color: rgba(255, 255, 255, 0.08);
    border-left: 4px solid #E95420;
    padding: 18px 20px;
    border-radius: 0 8px 8px 0;
    transition: transform 0.2s ease, background-color 0.2s ease;
  }

  .tema-box:hover {
    background-color: rgba(255, 255, 255, 0.14);
    transform: translateX(4px);
  }

  .tema-box a {
    color: #FF8E66;
    text-decoration: none;
    font-weight: bold;
    font-size: 1.15em;
    display: block;
    margin-bottom: 6px;
  }

  .tema-box a:hover {
    color: #FFFFFF;
    text-decoration: underline;
  }

  .tema-box p {
    margin: 0;
    color: #E0E0E0;
    font-size: 0.92em;
    line-height: 1.4;
  }

  .formula-badge {
    display: inline-block;
    margin-top: 10px;
    padding: 4px 10px;
    background-color: rgba(0, 0, 0, 0.3);
    border-radius: 4px;
    font-size: 0.85em;
    color: #FFFFFF;
  }
</style>

<div class="ubuntu-card" markdown="1">

# ⚙️ Dinámica

Apuntes interactivos, deducciones matemáticas y ejercicios resueltos de mecánica clásica.

## 📐 Módulo 1: Cinemática

<div class="temas-grid">

  <div class="tema-box">
    <a href="./mru.html">1. MRU</a>
    <p>Movimiento Rectilíneo Uniforme. Análisis de desplazamiento a velocidad constante.</p>
    <span class="formula-badge">$x = x_0 + v \cdot t$</span>
  </div>

  <div class="tema-box">
    <a href="./mrua.html">2. MRUA</a>
    <p>Movimiento Rectilíneo Uniformemente Acelerado y ecuaciones horarias.</p>
    <span class="formula-badge">$x = x_0 + v_0 t + \frac{1}{2}a t^2$</span>
  </div>

  <div class="tema-box">
    <a href="./caida-libre.html">3. Caída Libre</a>
    <p>Movimiento vertical bajo la influencia exclusiva de la gravedad terrestre.</p>
    <span class="formula-badge">$v_f^2 = v_0^2 - 2g\Delta y$</span>
  </div>

  <div class="tema-box">
    <a href="./tiro-parabolico.html">4. Tiro Parabólico</a>
    <p>Composición de movimientos en dos dimensiones: alcance máximo y altura.</p>
    <span class="formula-badge">$y(x) = x\tan\theta - \frac{g x^2}{2v_0^2\cos^2\theta}$</span>
  </div>

  <div class="tema-box">
    <a href="./movimiento-circular.html">5. Movimiento Circular</a>
    <p>Cinemática angular, velocidad tangencial y aceleración centrípeta.</p>
    <span class="formula-badge">$a_c = \omega^2 r = \frac{v^2}{r}$</span>
  </div>

  <div class="tema-box">
    <a href="./aceleracion-variable.html">6. Aceleración Variable</a>
    <p>Análisis diferencial e integral de la posición, velocidad y aceleración.</p>
    <span class="formula-badge">$a = \frac{dv}{dt} = v\frac{dv}{ds}$</span>
  </div>

</div>

</div>
