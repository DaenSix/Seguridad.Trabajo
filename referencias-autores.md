---
layout: default
title: Referencias y Autores
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

  /* --- CAJA TEMÁTICA GRIS (Trabajo Conjunto) --- */
  .caja-gris {
    background: linear-gradient(135deg, #f5f5f5 0%, #e0e0e0 100%);
    border-left: 6px solid #9b9b9b;
    padding: 20px;
    margin: 20px 0;
    border-radius: 8px;
    color: #424242;
    box-shadow: 0 4px 10px rgba(0,0,0,0.05);
    font-size: 1.1em;
    line-height: 1.6;
  }

  /* --- LISTA DE REFERENCIAS --- */
  .lista-referencias {
    background: #ffffff;
    border: 1px solid #e1e4e8;
    padding: 25px 40px;
    border-radius: 8px;
    box-shadow: 0 2px 5px rgba(0,0,0,0.03);
    margin: 20px 0;
  }
  .lista-referencias li {
    margin-bottom: 12px;
    color: #444d56;
    line-height: 1.5;
  }
  .lista-referencias a {
    color: #00695c;
    text-decoration: none;
    font-weight: bold;
  }
  .lista-referencias a:hover {
    text-decoration: underline;
  }

  /* --- TARJETAS DE AUTORES (GRID Y COLORES) --- */
  .grid-autores {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 20px;
    margin: 25px 0;
  }
  .tarjeta-autor {
    background: #ffffff;
    border: 1px solid #e1e4e8;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 2px 5px rgba(0,0,0,0.03);
    transition: transform 0.3s;
  }
  .tarjeta-autor:hover {
    transform: translateY(-5px);
    box-shadow: 0 8px 15px rgba(0,0,0,0.1);
  }
  .tarjeta-autor h3 {
    margin-top: 0;
    padding-bottom: 10px;
    border-bottom: 1px solid #eaecef;
  }
  
  /* Colores específicos para cada autor (Joaquín Azul, Daniel Naranja) */
  .borde-joaquin { border-top: 5px solid #0366d6; }
  .borde-joaquin h3 { color: #0366d6; }
  
  .borde-daniel { border-top: 5px solid #f57c00; }
  .borde-daniel h3 { color: #f57c00; }

  /* --- BOTONES DE NAVEGACIÓN INFERIOR --- */
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
  .btn-nav.anterior { background-color: #f57c00; } /* Naranja porque viene de la parte de Daniel */
</style>

<div markdown="1">

<div class="retraso-1" markdown="1">

# Referencias y Autores

<div class="caja-gris">
  Para llevar a cabo este proyecto sobre Seguridad en el Trabajo Informático nos hemos organizado en un equipo de dos personas. Hemos buscado información en fuentes oficiales de salud laboral y hemos utilizado herramientas colaborativas para montar y diseñar esta página web.
</div>

</div>

<div class="retraso-2" markdown="1">

## Referencias y Herramientas utilizadas

A continuación, detallamos de dónde hemos extraído la información técnica y qué recursos hemos usado para darle forma al trabajo:

<div class="lista-referencias" markdown="1">

* **Búsqueda de normativa:** Documentación del **INSST** (Instituto Nacional de Seguridad y Salud en el Trabajo) sobre riesgos en oficinas y uso de Pantallas de Visualización de Datos (PVD).
* **Imágenes ilustrativas:** Fotografías libres de derechos obtenidas de la plataforma [Unsplash](https://unsplash.com/) para garantizar un aspecto profesional y legal.
* **Uso de Inteligencia Artificial:** Tal y como se permitía en las bases del proyecto, hemos utilizado **ChatGPT** para estructurar la información, corregir la redacción y generar las animaciones CSS avanzadas de la web.
* **Plataforma de trabajo:** Repositorio colaborativo creado en **GitHub** y web publicada a través de **GitHub Pages**.

</div>

</div>

<div class="retraso-3" markdown="1">

## Equipo de Trabajo

Este proyecto ha sido desarrollado cumpliendo el requisito de trabajo colaborativo al **50%**. Así es como nos hemos dividido las tareas de investigación y desarrollo web:

<div class="grid-autores" markdown="1">

<div class="tarjeta-autor borde-joaquin" markdown="1">
### Joaquín (@daensix)
* Creación del repositorio, configuración del layout base y montaje del menú de navegación lateral.
* Investigación y redacción del **Punto 1** (Riesgos físicos y ergonómicos).
* Investigación y redacción del **Punto 2** (Riesgos del entorno y eléctricos).
</div>

<div class="tarjeta-autor borde-daniel" markdown="1">
### Daniel (@dmarsue242)
* Investigación y redacción del **Punto 3** (Riesgos psicosociales: Estrés, Burnout).
* Investigación y redacción del **Punto 4** (Medidas de prevención y salud laboral).
* Revisión de los criterios de la rúbrica y aportación de soluciones ergonómicas.
</div>

</div>

*Nota: La auditoría del diseño, la recopilación de este apartado de referencias y la publicación final de la web ha sido un trabajo conjunto de ambos miembros.*

</div>

<div class="retraso-4" markdown="1">

---

<div class="nav-botones">
  <a href="prevencion.html" class="btn-nav anterior">⬅️ Anterior: Medidas de prevención</a>
  <a href="index.html" class="btn-nav volver">🏠 Volver al Índice Principal</a>
</div>

</div>
</div>
