---
layout: default
title: Riesgos Físicos y Ergonómicos
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
  .btn-nav.siguiente { background-color: #0366d6; } /* Azul porque la parte 2 también es tuya */
</style>

<div markdown="1">

<div class="retraso-1" markdown="1">

# 1. Riesgos Físicos y Ergonómicos en Informática

<div class="mini-indice">
  <h4>Navegación rápida:</h4>
  <ul>
    <li><a href="#introduccion">1.1. ¿Qué es la Ergonomía?</a></li>
    <li><a href="#tme">1.2. Trastornos Musculoesqueléticos (TME)</a></li>
    <li><a href="#visual">1.3. Fatiga Visual y PVD</a></li>
    <li><a href="#sedentarismo">1.4. El riesgo del sedentarismo</a></li>
  </ul>
</div>

<div id="introduccion" class="seccion-contenido" markdown="1">

## 1.1. ¿Qué es la Ergonomía?

<div class="caja-azul">
  A menudo se piensa que el trabajo informático es "seguro" porque no implica levantar cargas pesadas ni manejar maquinaria peligrosa. Sin embargo, el trabajo prolongado en oficinas genera riesgos físicos silenciosos pero muy dañinos. Aquí es donde entra la <strong>Ergonomía</strong>: la ciencia que adapta el puesto de trabajo a las características físicas y psicológicas del trabajador.
</div>

Un puesto informático mal diseñado obliga al trabajador a adoptar posturas forzadas que, mantenidas durante 8 horas al día, acaban provocando lesiones crónicas.

<img src="https://images.unsplash.com/photo-1497215842964-222b430dc094?q=80&w=800&auto=format&fit=crop" class="img-estilo" alt="Persona trabajando en un escritorio con ordenador">

</div>

</div>

<div id="tme" class="retraso-2 seccion-contenido" markdown="1">

## 1.2. Trastornos Musculoesqueléticos (TME)

Los TME son el problema de salud laboral más común en Europa. En el sector informático, se producen por la repetición constante de micromovimientos (como hacer clic o teclear) y por mantener posturas estáticas (el cuello doblado hacia la pantalla).

Los más frecuentes son:

<div class="grid-detalles" markdown="1">

<div class="tarjeta-detalle" markdown="1">
### ✋ Síndrome del Túnel Carpiano
Es la lesión "estrella" de los informáticos. Se produce por la presión sobre el nervio mediano en la muñeca debido a una mala posición al usar el ratón o el teclado. Causa dolor, hormigueo y pérdida de fuerza en la mano.
</div>

<div class="tarjeta-detalle" markdown="1">
### 🦒 Cervicalgia (Dolor de cuello)
Ocurre cuando el monitor está demasiado bajo o demasiado alto. El trabajador se ve obligado a inclinar la cabeza hacia adelante, sobrecargando los músculos de la nuca y los hombros (postura de "cuello de tortuga").
</div>

<div class="tarjeta-detalle" markdown="1">
### 🪑 Lumbalgia (Dolor de espalda baja)
Deriva del uso de sillas no ergonómicas, sentarse en el borde del asiento o no tener los pies bien apoyados en el suelo. La columna pierde su curvatura natural y los discos vertebrales sufren una presión excesiva.
</div>

</div>

<img src="https://images.unsplash.com/photo-1522881115286-9b5ca3157580?q=80&w=800&auto=format&fit=crop" class="img-estilo" alt="Primer plano de manos tecleando">

</div>

<div id="visual" class="retraso-3 seccion-contenido" markdown="1">

## 1.3. Fatiga Visual y el uso de PVD

El trabajo con **PVD (Pantallas de Visualización de Datos)** somete a los ojos a un esfuerzo continuo. A diferencia de leer un libro de papel, mirar una pantalla implica lidiar con el brillo, el contraste, los reflejos y el parpadeo de la luz.

<div class="destacado-texto">
  Dato clave: Normalmente parpadeamos unas 15-20 veces por minuto. Sin embargo, cuando miramos fijamente una pantalla, la frecuencia de parpadeo cae a solo 5-7 veces por minuto. Esto provoca sequedad ocular casi inmediata.
</div>

**Síntomas principales de la fatiga visual:**
* Sensación de arenilla o ardor en los ojos.
* Visión borrosa temporal tras muchas horas de código.
* Dolores de cabeza (cefaleas) en la zona frontal, a menudo causados por el esfuerzo extra para enfocar letras pequeñas o por reflejos en la pantalla provocados por ventanas cercanas.

</div>

<div id="sedentarismo" class="retraso-4 seccion-contenido" markdown="1">

## 1.4. El riesgo del sedentarismo

El cuerpo humano está diseñado para moverse. Trabajar en informática suele implicar un grado de sedentarismo extremo. 

Estar sentado durante periodos prolongados ralentiza el metabolismo y dificulta el retorno venoso (la sangre tiene problemas para subir desde las piernas hasta el corazón), lo que puede generar:
* Piernas hinchadas y aparición de varices.
* Aumento del riesgo de obesidad y enfermedades cardiovasculares.
* Mayor propensión a la diabetes tipo 2.

*Nota: En el apartado 4 (Medidas de Prevención) de nuestro compañero Daniel, veremos cómo combatir todos estos riesgos físicos mediante pausas activas, mobiliario ergonómico y ajustes de pantalla.*

---

<div class="nav-botones">
  <a href="index.html" class="btn-nav volver">🏠 Volver al Índice</a>
  <a href="riesgos-entorno.html" class="btn-nav siguiente">Siguiente: Riesgos del entorno ➡️</a>
</div>

</div>
</div>
