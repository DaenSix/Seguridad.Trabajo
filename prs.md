---
layout: default
title: Prevención de Riesgos Psicosociales
---

<style>
  /* --- ANIMACIONES EN CASCADA --- */
  @keyframes fadeInUp {
    0% { opacity: 0; transform: translateY(20px); }
    100% { opacity: 1; transform: translateY(0); }
  }
  .retraso-1 { animation: fadeInUp 0.8s ease-out forwards; }
  .retraso-2 { opacity: 0; animation: fadeInUp 0.8s ease-out 0.2s forwards; }
  .retraso-3 { opacity: 0; animation: fadeInUp 0.8s ease-out 0.4s forwards; }
  .retraso-4 { opacity: 0; animation: fadeInUp 0.8s ease-out 0.6s forwards; }

  /* --- MINI ÍNDICE INTERNO --- */
  .mini-indice {
    background: #ffffff;
    border: 1px solid #e1e4e8;
    padding: 20px;
    border-radius: 12px;
    margin-bottom: 30px;
    box-shadow: 0 4px 12px rgba(0,0,0,0.05);
    border-left: 5px solid #28a745;
  }
  .mini-indice h4 { margin-top: 0; color: #24292e; font-size: 1.2em; }
  .mini-indice ul { list-style: none; padding-left: 0; }
  .mini-indice li { margin: 8px 0; }
  .mini-indice a { color: #28a745; text-decoration: none; font-weight: 500; }
  .mini-indice a:hover { text-decoration: underline; color: #586069; }

  /* --- CAJA TEMÁTICA VERDE (Prevención) --- */
  .caja-verde {
    background: linear-gradient(135deg, #e8f5e9 0%, #c8e6c9 100%);
    border-left: 6px solid #28a745;
    padding: 25px;
    margin: 25px 0;
    border-radius: 10px;
    color: #1b5e20;
    line-height: 1.7;
    font-size: 1.1em;
  }

  /* --- ESTILO DE IMÁGENES --- */
  .img-estilo {
    border-radius: 12px;
    box-shadow: 0 10px 25px rgba(0,0,0,0.15);
    display: block;
    margin: 30px auto;
    max-width: 100%;
    height: auto;
    transition: transform 0.3s ease;
  }
  .img-estilo:hover {
    transform: scale(1.02);
  }

  /* --- GRID DE TARJETAS --- */
  .grid-detalles {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 20px;
    margin: 30px 0;
  }
  .tarjeta-detalle {
    background: #ffffff;
    border: 1px solid #d1d5da;
    padding: 20px;
    border-radius: 10px;
    border-top: 5px solid #28a745;
    transition: all 0.3s ease;
  }
  .tarjeta-detalle:hover {
    transform: translateY(-5px);
    box-shadow: 0 8px 20px rgba(0,0,0,0.1);
  }
  .tarjeta-detalle h3 { margin-top: 0; color: #218838; }

  /* --- SECCIONES DE CONTENIDO --- */
  .seccion-contenido { margin-bottom: 50px; }
  .destacado-texto {
    background-color: #f8f9fa;
    padding: 15px;
    border-radius: 6px;
    border-left: 4px solid #586069;
    margin: 20px 0;
    font-style: italic;
  }

  /* --- BOTONES DE NAVEGACIÓN --- */
  .nav-botones {
    display: flex;
    justify-content: space-between;
    flex-wrap: wrap;
    gap: 15px;
    margin-top: 50px;
    border-top: 2px solid #eaecef;
    padding-top: 30px;
  }
  .btn-nav {
    flex: 1;
    min-width: 160px;
    padding: 14px 20px;
    color: white !important;
    text-decoration: none;
    border-radius: 8px;
    font-weight: bold;
    text-align: center;
    transition: all 0.3s cubic-bezier(0.175, 0.885, 0.32, 1.275);
    box-shadow: 0 4px 6px rgba(0,0,0,0.1);
  }
  .btn-nav:hover {
    transform: translateY(-3px);
    box-shadow: 0 8px 15px rgba(0,0,0,0.2);
    filter: brightness(1.1);
  }
  .btn-nav.volver { background-color: #6a737d; }
  .btn-nav.siguiente { background-color: #28a745; }
</style>

<div markdown="1">

<div class="retraso-1" markdown="1">

# 4. Prevención de Riesgos Psicosociales en IT

<div class="mini-indice">
  <h4>Estrategias preventivas:</h4>
  <ul>
    <li><a href="#organizacion">4.1. Organización y Planificación</a></li>
    <li><a href="#desconexion">4.2. Desconexión Digital</a></li>
    <li><a href="#apoyo-social">4.3. Fomento del Apoyo Social</a></li>
    <li><a href="#pausas-mentales">4.4. Higiene Mental y Pausas</a></li>
  </ul>
</div>

<div id="organizacion" class="seccion-contenido" markdown="1">

## 4.1. Organización y Planificación

<div class="caja-verde">
  La mejor defensa contra el estrés informático es una organización sólida. Para prevenir el burnout, es vital que las <strong>estimaciones de tiempo</strong> sean realistas y contemplen márgenes para la resolución de errores inesperados (bugs), evitando así las jornadas interminables al final de cada Sprint.
</div>

Utilizar metodologías ágiles de forma saludable ayuda a que la carga de trabajo sea predecible y manejable para el equipo de desarrollo.

</div>

</div>

<div id="desconexion" class="retraso-2 seccion-contenido" markdown="1">

## 4.2. Desconexión Digital y Medidas de Control

Para evitar el tecnoestrés, el profesional debe ser capaz de separar su entorno digital laboral del personal.

<img src="prevencion.jpeg" class="img-estilo" alt="Imagen representativa de prevención y seguridad digital">

Medidas fundamentales para el bienestar:

<div class="grid-detalles" markdown="1">

<div class="tarjeta-detalle" markdown="1">
### 📵 Desconexión Real
Apagar las notificaciones de herramientas de trabajo (Slack, Jira, Teams) una vez finalizada la jornada laboral para permitir que el cerebro descanse del estado de alerta técnica.
</div>

<div class="tarjeta-detalle" markdown="1">
### ⏱️ Gestión del Tiempo
Evitar el multitasking extremo. Centrarse en una sola tarea técnica compleja a la vez reduce la carga cognitiva y minimiza la sensación de agobio informativo.
</div>

<div class="tarjeta-detalle" markdown="1">
### 📚 Formación Protegida
Integrar las horas de estudio de nuevas tecnologías dentro de la jornada laboral oficial, evitando que el autoaprendizaje se convierta en una carga de tiempo personal.
</div>

</div>

</div>

<div id="apoyo-social" class="retraso-3 seccion-contenido" markdown="1">

## 4.3. Fomento del Apoyo Social

El trabajo del informático no debe ser solitario. La interacción es clave para prevenir el aislamiento digital.

<div class="destacado-texto">
  Dato clave: Implementar dinámicas como el "Pair Programming" o revisiones de código grupales no solo mejora la calidad del software, sino que reduce drásticamente el estrés al compartir la responsabilidad técnica.
</div>

**Beneficios del apoyo de equipo:**
* Validación del trabajo por parte de pares técnicos.
* Resolución colaborativa de problemas complejos que parecen imposibles en solitario.
* Mayor sentimiento de pertenencia a la empresa, incluso en remoto.

</div>

<div id="pausas-mentales" class="retraso-4 seccion-contenido" markdown="1">

## 4.4. Higiene Mental y Pausas

Tan importante como el mobiliario ergonómico es la ergonomía mental. El cerebro informático necesita "reiniciarse".

Realizar pausas mentales breves ayuda a:
* Mantener la capacidad de resolución de problemas lógicos.
* Reducir la irritabilidad causada por la fatiga informativa.
* Evitar la visión de túnel cuando un error de código no se soluciona.

---

<div class="nav-botones">
  <a href="riesgos-psicosociales.html" class="btn-nav volver">⬅️ Riesgos Psicosociales</a>
  <a href="referencias-autores.html" class="btn-nav siguiente">Referencias y Autores</a>
</div>

</div>
