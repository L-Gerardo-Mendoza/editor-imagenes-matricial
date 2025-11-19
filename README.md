🧮 Álgebra – Práctica 1
Luis Gerardo Sánchez Mendoza – 1B

📘 Descripción

Proyecto de álgebra donde resuelvo ejercicios fundamentales utilizando JavaScript.
Incluye operaciones básicas, condicionales, funciones, arreglos y matrices, junto con pruebas automatizadas.
Este repositorio demuestra dominio de lógica, estructuras de datos y fundamentos matemáticos aplicados a programación.

🎯 Objetivos logrados

Declaración correcta de variables
Uso de operadores matemáticos
Implementación de condicionales
Bucles y funciones
Manipulación de arrays
Trabajo con matrices bidimensionales
Pruebas automatizadas con Jest
Control de versiones con Git

📊 Progreso de la Práctica
Sección	Descripción	Puntos	Estado
1	Variables y operaciones básicas	10 pts	✔️
2	Condicionales	15 pts	✔️
3	Funciones y bucles	20 pts	✔️
4	Arrays	25 pts	✔️
5	Matrices	30 pts	✔️
⭐ Total: 100 / 100 — Excelente

🚀 Uso del Proyecto
git clone https://github.com/tu-usuario/tu-repo.git
cd tu-repo
npm install
npm test

🧠 Ejemplo de Código
function transponer(matriz) {
  const filas = matriz.length;
  const columnas = matriz[0].length;
  const transpuesta = [];

  for (let j = 0; j < columnas; j++) {
    const fila = [];
    for (let i = 0; i < filas; i++) {
      fila.push(matriz[i][j]);
    }
    transpuesta.push(fila);
  }
  return transpuesta;

}
📚 Recursos
MDN JavaScript
JavaScript.info
StackOverflow
Guía del docente / estudiante

✨ Sobre mí
Luis Gerardo Sánchez Mendoza
Grupo 1B – Álgebra
En constante aprendizaje.

⭐ Licencia
Proyecto académico – Licencia MIT.