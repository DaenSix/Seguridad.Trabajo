---
layout: default
title: Medidas de Prevención
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

  .mini-indice {
    background: #ffffff;
    border: 1px solid #e1e4e8;
    padding: 20px;
    border-radius: 12px;
    margin-bottom: 30px;
    box-shadow: 0 4px 12px rgba(0,0,0,0.05);
    border-left: 5px solid #28a745;
  }

  .caja-azul {
    background: linear-gradient(135deg, #e6ffed 0%, #c3f0ca 100%);
    border-left: 6px solid #28a745;
    padding: 25px;
    margin: 25px 0;
    border-radius: 10px;
  }

  .img-estilo {
    border-radius: 12px;
    box-shadow: 0 10px 25px rgba(0,0,0,0.15);
    display: block;
    margin: 30px auto;
    max-width: 100%;
  }

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
  }

  .seccion-contenido { margin-bottom: 50px; }

  .destacado-texto {
    background-color: #fff3cd;
    padding: 15px;
    border-radius: 6px;
    border-left: 4px solid #ffc107;
    margin: 20px 0;
  }

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
  }

  .btn-nav.anterior { background-color: #0366d6; }
  .btn-nav.volver { background-color: #6a737d; }
  .btn-nav.siguiente { background-color: #f57c00; }
</style>

<div markdown="1">

<div class="retraso-1" markdown="1">

# 6. Medidas de Prevención en Entornos Informáticos

<div class="mini-indice">
  <h4>Navegación rápida:</h4>
  <ul>
    <li><a href="#generales">6.1. Prevención General</a></li>
    <li><a href="#ergonomia">6.2. Prevención Ergonómica</a></li>
    <li><a href="#ambiente">6.3. Prevención Ambiental</a></li>
    <li><a href="#psico">6.4. Prevención Psicosocial</a></li>
  </ul>
</div>

<div id="generales" class="seccion-contenido" markdown="1">

## 6.1. Prevención General

<div class="caja-azul">
  Las medidas de prevención permiten reducir riesgos en el entorno de trabajo informático, mejorando la seguridad y evitando accidentes.
</div>

**Principales medidas:**
* Mantener el espacio limpio y ordenado.
* Revisar cables y enchufes.
* No sobrecargar regletas.
* Apagar equipos correctamente.
* Conocer salidas de emergencia.

<img src="imagenes/foto1.jpg" class="img-estilo">

</div>

</div>

<div id="ergonomia" class="retraso-2 seccion-contenido" markdown="1">

## 6.2. Prevención Ergonómica

Una postura correcta evita lesiones físicas a largo plazo.

<div class="destacado-texto">
  💡 Ajustar silla y pantalla correctamente reduce dolores de espalda.
</div>

* Espalda recta y apoyada.  
* Pantalla a la altura de los ojos.  
* Brazos en ángulo de 90°.  
* Descansos frecuentes.

<img src="imagenes/foto2.jpg" class="img-estilo">

</div>

<div id="ambiente" class="retraso-3 seccion-contenido" markdown="1">

## 6.3. Prevención Ambiental

<div class="grid-detalles" markdown="1">

<div class="tarjeta-detalle" markdown="1">
### 💡 Iluminación
Evitar reflejos y usar luz natural.
</div>

<div class="tarjeta-detalle" markdown="1">
### 🌡️ Temperatura
Mantener entre 20ºC y 26ºC.
</div>

<div class="tarjeta-detalle" markdown="1">
### 🔊 Ruido
Reducir sonidos innecesarios.
</div>

</div>

<img src="imagenes/foto3.jpg" class="img-estilo">

</div>

<div id="psico" class="retraso-4 seccion-contenido" markdown="1">

## 6.4. Prevención Psicosocial

El bienestar mental es fundamental en el trabajo.

* Evitar el estrés.
* Fomentar el trabajo en equipo.
* Organizar tareas correctamente.

<div class="destacado-texto">
  ⚠️ Un mal ambiente laboral afecta a la salud y productividad.
</div>

<img src="imagenes/foto4.jpg" class="img-estilo">

</div>

---

<div class="nav-botones">
  <a href="riesgos-entorno.html" class="btn-nav anterior">⬅️ Anterior</a>
  <a href="index.html" class="btn-nav volver">🏠 Inicio</a>
  <a href="#" class="btn-nav siguiente">Siguiente ➡️</a>
</div>

</div>
</div>
