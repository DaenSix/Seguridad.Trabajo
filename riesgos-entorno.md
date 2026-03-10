---
layout: default
title: Riesgos del Entorno
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
    border-left: 5px solid #0366d6;
  }
  .mini-indice h4 { margin-top: 0; color: #24292e; font-size: 1.2em; }
  .mini-indice ul { list-style: none; padding-left: 0; }
  .mini-indice li { margin: 8px 0; }
  .mini-indice a { color: #0366d6; text-decoration: none; font-weight: 500; }
  .mini-indice a:hover { text-decoration: underline; color: #586069; }

  /* --- CAJA TEMÁTICA AZUL --- */
  .caja-azul {
    background: linear-gradient(135deg, #e3f2fd 0%, #bbdefb 100%);
    border-left: 6px solid #0366d6;
    padding: 25px;
    margin: 25px 0;
    border-radius: 10px;
    color: #0c2d48;
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
    border-top: 5px solid #0366d6;
    transition: all 0.3s ease;
  }
  .tarjeta-detalle:hover {
    transform: translateY(-5px);
    box-shadow: 0 8px 20px rgba(0,0,0,0.1);
  }
  .tarjeta-detalle h3 { margin-top: 0; color: #0366d6; }

  /* --- SECCIONES DE CONTENIDO --- */
  .seccion-contenido { margin-bottom: 50px; }
  .destacado-texto {
    background-color: #fff3cd;
    padding: 15px;
    border-radius: 6px;
    border-left: 4px solid #ffc107;
    margin: 20px 0;
    color: #856404;
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
  /* Colores según asignación de tareas */
  .btn-nav.anterior { background-color: #0366d6; } /* Joaquín (Azul) */
  .btn-nav.volver { background-color: #6a737d; }   /* General (Gris) */
  .btn-nav.siguiente { background-color: #f57c00; } /* Daniel (Naranja) */
</style>

<div markdown="1">

<div class="retraso-1" markdown="1">

# 2. Riesgos del Entorno: Electricidad y Condiciones Ambientales

<div class="mini-indice">
  <h4>Navegación rápida:</h4>
  <ul>
    <li><a href="#electricos">2.1. Riesgos Eléctricos y Cableado</a></li>
    <li><a href="#incendios">2.2. Peligro de Incendio y Sobrecalentamiento</a></li>
    <li><a href="#cpd">2.3. Ruido y Temperatura (Entorno CPD)</a></li>
    <li><a href="#iluminacion">2.4. Iluminación y Deslumbramientos</a></li>
  </ul>
</div>

<div id="electricos" class="seccion-contenido" markdown="1">

## 2.1. Riesgos Eléctricos y de Cableado

<div class="caja-azul">
  El entorno informático depende totalmente de la energía eléctrica. Ordenadores, monitores, impresoras, routers y servidores necesitan alimentación constante, lo que convierte a la oficina o sala técnica en una telaraña de cables si no se gestiona correctamente.
</div>

**Principales peligros:**
* **Contactos directos e indirectos:** Sufrir una descarga al tocar la carcasa metálica de una torre de PC mal aislada o al manipular cables pelados.
* **Sobrecarga de regletas (Enchufes en cascada):** Conectar varias regletas o "ladrones" unos a otros para conectar múltiples dispositivos (monitores dobles, cargadores, discos duros) supera la potencia máxima soportada por la toma de pared, derritiendo el plástico y provocando cortocircuitos.
* **Caídas al mismo nivel:** Los cables de red (Ethernet) o de alimentación sueltos por el suelo del pasillo son la causa número uno de tropiezos en oficinas técnicas.

<img src="https://images.unsplash.com/photo-1558494949-ef010cbdcc31?q=80&w=800&auto=format&fit=crop" class="img-estilo" alt="Cables de servidores desordenados">

</div>

</div>

<div id="incendios" class="retraso-2 seccion-contenido" markdown="1">

## 2.2. Peligro de Incendio y Sobrecalentamiento

Los equipos informáticos generan calor. Si la ventilación de una CPU está obstruida por polvo o porque el equipo está encajonado en un mueble sin flujo de aire, los componentes internos (especialmente procesador y fuente de alimentación) pueden alcanzar temperaturas críticas.

<div class="destacado-texto">
  <strong>⚠️ El riesgo oculto de las baterías:</strong> Los SAIs (Sistemas de Alimentación Ininterrumpida) y las baterías de litio hinchadas en ordenadores portátiles viejos pueden provocar incendios químicos si se perforan o se exponen a altas temperaturas.
</div>

</div>

<div id="cpd" class="retraso-3 seccion-contenido" markdown="1">

## 2.3. Ruido y Temperatura (El entorno de los Servidores)

Un administrador de sistemas o técnico de redes pasa mucho tiempo dentro del **CPD (Centro de Procesamiento de Datos)** o sala de servidores. Las condiciones en estas salas son extremas y representan un riesgo ambiental importante:

<div class="grid-detalles" markdown="1">

<div class="tarjeta-detalle" markdown="1">
### ❄️ Estrés Térmico (Frío extremo)
Para que los servidores no se quemen, los CPDs se mantienen a temperaturas muy bajas (entre 18ºC y 21ºC) mediante potentes sistemas de aire acondicionado. Entrar y salir de estas salas provoca fuertes contrastes térmicos en el cuerpo.
</div>

<div class="tarjeta-detalle" markdown="1">
### 🔊 Contaminación Acústica
Decenas o cientos de servidores encendidos a la vez, con sus ventiladores girando a miles de RPM para expulsar el calor, generan un ruido constante (zumbido de alta frecuencia). La exposición prolongada sin protección auditiva genera fatiga mental, estrés e incluso pérdida gradual de la audición.
</div>

</div>



*(El diseño de pasillos fríos y calientes ayuda a gestionar la temperatura, pero requiere que el técnico trabaje en zonas con potentes corrientes de aire).*

</div>

<div id="iluminacion" class="retraso-4 seccion-contenido" markdown="1">

## 2.4. Iluminación y Deslumbramientos

El último gran riesgo del entorno físico es la luz. Un entorno mal iluminado obliga al cristalino del ojo a forzar el enfoque. 
* **Falta de luz:** Causa tensión ocular y dolores de cabeza al leer código o documentación.
* **Luz excesiva o mal orientada:** Si hay una ventana justo detrás del monitor, se produce un fuerte contraste (deslumbramiento directo). Si la luz da contra la pantalla, genera reflejos que impiden ver bien, obligando al trabajador a adoptar posturas incómodas con el cuello para esquivar el brillo.

---

<div class="nav-botones">
  <a href="riesgos-fisicos.html" class="btn-nav anterior">⬅️ Anterior: Riesgos físicos</a>
  <a href="index.html" class="btn-nav volver">🏠 Índice Principal</a>
  <a href="riesgos-psicosociales.html" class="btn-nav siguiente">Siguiente: Riesgos Psicosociales ➡️</a>
</div>

</div>
</div>
