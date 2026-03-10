---
layout: default
title: Riesgos Psicosociales en Informática
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
    border-left: 5px solid #6366f1;
  }
  .mini-indice h4 { margin-top: 0; color: #24292e; font-size: 1.2em; }
  .mini-indice ul { list-style: none; padding-left: 0; }
  .mini-indice li { margin: 8px 0; }
  .mini-indice a { color: #6366f1; text-decoration: none; font-weight: 500; }
  .mini-indice a:hover { text-decoration: underline; color: #586069; }

  /* --- CAJA TEMÁTICA AZUL --- */
  .caja-azul {
    background: linear-gradient(135deg, #f5f3ff 0%, #ddd6fe 100%);
    border-left: 6px solid #6366f1;
    padding: 25px;
    margin: 25px 0;
    border-radius: 10px;
    color: #2e1065;
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
    border-top: 5px solid #6366f1;
    transition: all 0.3s ease;
  }
  .tarjeta-detalle:hover {
    transform: translateY(-5px);
    box-shadow: 0 8px 20px rgba(0,0,0,0.1);
  }
  .tarjeta-detalle h3 { margin-top: 0; color: #4338ca; }

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
  .btn-nav.volver { background-color: #6a737d; }
  .btn-nav.siguiente { background-color: #6366f1; }
</style>

<div markdown="1">

<div class="retraso-1" markdown="1">

# 1. Riesgos Psicosociales en el Entorno Informático

<div class="mini-indice">
  <h4>Navegación rápida:</h4>
  <ul>
    <li><a href="#introduccion">1.1. El Impacto de la Carga Mental</a></li>
    <li><a href="#riesgos-clave">1.2. Principales Riesgos: Tecnoestrés y Burnout</a></li>
    <li><a href="#aislamiento">1.3. Aislamiento y Teletrabajo</a></li>
    <li><a href="#obsolescencia">1.4. Obsolescencia y Actualización</a></li>
  </ul>
</div>

<div id="introduccion" class="seccion-contenido" markdown="1">

## 1.1. El Impacto de la Carga Mental

<div class="caja-azul">
  A diferencia de otros sectores, en informática el mayor desgaste no es físico, sino cognitivo. El proceso constante de <strong>depuración de errores (debugging)</strong> y la resolución de problemas lógicos generan una fatiga mental invisible pero persistente.
</div>

Un entorno con plazos de entrega poco realistas y falta de apoyo técnico directo acaba derivando en problemas de ansiedad y estrés crónico que afectan la productividad.

</div>

</div>

<div id="riesgos-clave" class="retraso-2 seccion-contenido" markdown="1">

## 1.2. Principales Riesgos: Tecnoestrés y Burnout

En informática, la velocidad de los proyectos y la carga informativa son los principales disparadores de patologías mentales.

<img src="riesgo.jpeg" class="img-estilo" alt="Imagen representativa de riesgo psicosocial y estrés">

Los riesgos más frecuentes son:

<div class="grid-detalles" markdown="1">

<div class="tarjeta-detalle" markdown="1">
### 🔋 Tecnoestrés
Es la ansiedad generada por la obligación de estar "siempre conectado" o el miedo a no dominar las herramientas digitales necesarias para el proyecto actual.
</div>

<div class="tarjeta-detalle" markdown="1">
### 🔥 Burnout (Agotamiento)
Agotamiento emocional profundo debido a la resolución constante de problemas críticos bajo presión y plazos de entrega (Deadlines) agresivos.
</div>

<div class="tarjeta-detalle" markdown="1">
### 📧 Fatiga Informativa
Ocurre por la sobreexposición a datos. El flujo ininterrumpido de notificaciones e información impide el foco, aumentando la frustración.
</div>

</div>

</div>

<div id="aislamiento" class="retraso-3 seccion-contenido" markdown="1">

## 1.3. Aislamiento y Teletrabajo

El teletrabajo es la norma en el sector IT, pero si no se gestiona bien, puede convertirse en un riesgo psicosocial grave.

<div class="destacado-texto">
  Dato clave: El aislamiento técnico ocurre cuando un profesional no tiene apoyo social en su equipo, generando una sensación de soledad ante el código.
</div>

**Efectos del aislamiento:**
* Pérdida de los límites entre la vida personal y laboral.
* Dificultad para recibir feedback constructivo.
* Desvinculación emocional con los objetivos de la empresa.

</div>

<div id="obsolescencia" class="retraso-4 seccion-contenido" markdown="1">

## 1.4. Obsolescencia y Actualización

El sector IT obliga al informático a un estado de **autoaprendizaje permanente**, lo que genera una presión constante por la vigencia profesional.

Este requerimiento genera:
* Miedo a quedar fuera del mercado si no se aprende la última tecnología.
* Inversión de tiempo personal excesivo en formación.
* Ansiedad competitiva.

---

<div class="nav-botones">
  <a href="index.html" class="btn-nav volver">🏠 Volver al Índice</a>
  <a href="medidas-prevencion.html" class="btn-nav siguiente">Siguiente: Prevención</a>
</div>

</div>
