<template>
  <div class="book-container">
    <h1 class="main-title">Introducción a los algoritmos</h1>
    
    <div class="content">
      <h2 class="chapter-title">¿Que es un algoritmo?</h2>
      <p>
      Un algoritmo es un conjunto ordenado, finito y preciso de instrucciones que describen paso a paso cómo resolver un problema o realizar una tarea específica. Estas instrucciones deben seguir una secuencia lógica, donde cada paso depende del anterior, y siempre conducen a un resultado.
      </p>
      <p>
        En esencia, un algoritmo funciona como una guía de acción: recibe ciertos datos de entrada (o incluso ninguno), los procesa siguiendo reglas claras y produce una salida. Esta idea es muy similar a una receta de cocina, donde los ingredientes representan los datos y la preparación corresponde al conjunto de pasos que deben ejecutarse en un orden estricto para obtener el resultado esperado.
      </p>

      <p>
        La palabra algoritmo se deriva del nombre de Abū ‘Abd Allāh Muḥammad ibn Mūsā al-Khwārizmī. Los europeos occidentales aprendieron a realizar operaciones aritméticas con los números hindú-arábigos y el sistema de numeración decimal a partir de una traducción latina del siglo XII de uno de los libros de al-Khwārizmī (la traducción latina se realizó aproximadamente 300 años después de que al-Khwārizmī escribiera el libro original en árabe; el original actualmente se encuentra perdido). Cabe destacar que la palabra álgebra también se deriva del título de otro de los libros de al-Khwārizmī.  
      </p>

      <hr class="divider">

      <h3 class="section-title">Características de un algoritmo</h3>
      <p>
        Para que un algoritmo sea considerado correcto, debe cumplir ciertas propiedades fundamentales:
      </p>
      <ul>
        <li><strong>Definición (Definiteness):</strong> Cada paso debe estar definido con precisión. Las acciones realizadas en cada paso deben especificarse de manera inequívoca..</li>
        <li><strong>Efectividad (Effectiveness):</strong> Cada paso debe ser lo suficientemente básico como para poder ejecutarse de forma exacta y en un tiempo finito.</li>
        <li><strong>Finitud (Finiteness):</strong> El proceso debe finalizar después de un número finito de pasos (aunque dicho número puede ser un número natural muy grande).</li>
        <li><strong>Entrada (Input):</strong> Se toman cero o más valores de entrada de un conjunto específico. Las entradas pueden introducirse antes del paso inicial del algoritmo o de forma dinámica antes de cualquier paso posterior.</li>
        <li><strong>Salida (Output):</strong> El algoritmo produce una o más salidas que tienen una relación específica con las entradas. Además, el algoritmo debe producir las salidas correctas para cada conjunto de entradas.</li>
      </ul>

      <hr class="divider">

      <h3 class="section-title">Videos Relacionados</h3>
      <div class="video-grid">
        <a href="https://youtu.be/qluHZ1sV0I0?si=n35I6eY-k4MuABIi" target="_blank" class="video-card">
          <div class="thumbnail-wrapper">
            <img src="https://img.youtube.com/vi/qluHZ1sV0I0/hqdefault.jpg" class="thumbnail" alt="Miniatura">
            <div class="play-overlay"></div>
          </div>
          <p class="video-title">Tu cerebro puede hacer algoritmos - David J. Malan</p>
        </a>
        <a href="https://youtu.be/CN-UiM3of0E?si=4IO0g_yINBBp9OZW" target="_blank" class="video-card">
          <div class="thumbnail-wrapper">
            <img src="https://img.youtube.com/vi/CN-UiM3of0E/hqdefault.jpg" class="thumbnail" alt="Miniatura">
            <div class="play-overlay"></div>
          </div>
          <p class="video-title">Discrete Math 3.1.1 Algorithms and Their Properties</p>
        </a>
      </div>
    </div>
  </div>
</template>

<style scoped>
.book-container {
  max-width: 800px;
  margin: 0 auto;
  padding: 2rem;
  font-family: 'Georgia', serif;
  color: #2c3e50;
  line-height: 1.8;
  background-color: #fff;
  text-align: justify;
}

.main-title {
  font-size: 3rem;
  text-align: center;
  margin-bottom: 3rem;
  font-weight: bold;
  border-bottom: 2px solid #eaeaea;
  padding-bottom: 1rem;
}

.chapter-title {
  font-size: 2rem;
  margin-top: 2.5rem;
  margin-bottom: 1rem;
  color: #34495e;
}

.section-title {
  font-size: 1.5rem;
  margin-top: 2rem;
  margin-bottom: 0.8rem;
  color: #34495e;
  font-style: italic;
}

p {
  font-size: 1.125rem;
  margin-bottom: 1.5rem;
}

ul {
  list-style-type: disc;
  padding-left: 2rem;
  margin-bottom: 1.5rem;
}

li {
  font-size: 1.125rem;
  margin-bottom: 0.5rem;
}

.divider {
  border: 0;
  border-top: 1px solid #eaeaea;
  margin: 2rem 0;
}

.video-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 1.5rem;
  margin-top: 1.5rem;
}

.video-card {
  display: flex;
  flex-direction: column;
  gap: 0.5rem;
  cursor: pointer;
  transition: transform 0.2s ease;
  text-decoration: none;
  color: inherit;
}

.video-card:hover {
  transform: translateY(-4px);
}

.thumbnail-wrapper {
  position: relative;
  aspect-ratio: 16/9;
  border-radius: 8px;
  overflow: hidden;
  border: 1px solid #ddd;
}

.thumbnail {
  width: 100%;
  height: 100%;
  object-fit: cover;
  display: block;
}

.play-overlay {
  position: absolute;
  inset: 0;
  display: flex;
  align-items: center;
  justify-content: center;
  background-color: rgba(0, 0, 0, 0.1);
  transition: background-color 0.2s;
}

.video-card:hover .play-overlay {
  background-color: rgba(0, 0, 0, 0.3);
}

.video-title {
  font-size: 1rem;
  font-weight: bold;
  margin: 0;
  line-height: 1.2;
  text-align: left;
}
</style>
