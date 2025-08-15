# Beer-Game-Beta
Beer Game - Juego de Supply Chain con las reglas básicas del MIT.
# Beer Game Beta

Beer Game Beta es una implementación interactiva del famoso **Beer Distribution Game**, diseñado para simular la dinámica de la cadena de suministro y el **efecto látigo** (*bullwhip effect*). Este proyecto permite a los jugadores asumir distintos roles dentro de la cadena y tomar decisiones de pedidos semana a semana.

## 🎯 Objetivo

El objetivo principal del juego es **minimizar los costos** manteniendo un equilibrio adecuado de inventario mientras se satisfacen los pedidos del cliente. Los jugadores deben tomar decisiones basadas en información parcial y gestionar retrasos en la cadena.

## 🚀 Características

- Selección de rol: Minorista, Mayorista, Distribuidor o Productor.
- Simulación de demanda con posibilidad de agregar ruido aleatorio.
- Métricas visibles en todo momento:
  - Demanda del cliente
  - Pedidos entrantes (1 y 2 semanas)
  - Posición de inventario
- Bots que simulan los otros eslabones de la cadena.
- Gráfica de desempeño colocada sobre el historial.
- Botón **Deshacer** para revertir la última acción.
- Tooltips informativos sobre métricas clave.

## 📂 Estructura del Proyecto

```
beer-game-practice/
│
├── index.html      # Código principal (HTML, CSS, JS embebido)
└── README.md       # Este archivo
```

## 🛠️ Tecnologías

- **HTML5** para la estructura.
- **CSS3** para el estilo y diseño responsive.
- **JavaScript** para la lógica del juego.
- **Chart.js** para la visualización de datos.

## 📦 Instalación y Uso

1. Clona este repositorio:
   ```bash
   git clone https://github.com/<luijansuarez>/beer-game-beta.git
   ```
2. Abre el archivo `index.html` en tu navegador.
3. Selecciona tu rol y comienza a jugar.

## 📖 Contexto Educativo

El **Beer Game** fue desarrollado originalmente en la década de 1960 en el MIT Sloan School of Management para enseñar principios de la dinámica de sistemas. Es ampliamente utilizado para demostrar cómo las decisiones locales y la falta de información global pueden provocar el **efecto látigo** en la cadena de suministro.

## 📜 Licencia

Este proyecto está bajo la licencia MIT. Puedes usarlo, modificarlo y distribuirlo libremente citando la fuente.

---

✍️ Desarrollado por [Luis Suarez Ciniglio](https://www.linkedin.com/in/luijansuarez/)
