<h1>README - Cálculo de intereses en Plazo Fijo</h1>

<p>Este es un script en Python que permite calcular los intereses ganados en una inversión a plazo fijo, ya sea con una tasa de interés simple o compuesto.</p>

<h2>Librerías utilizadas</h2>

<p>El script utiliza dos librerías de Python:</p>

<ul>
  <li>NumPy: para realizar cálculos matemáticos con mayor facilidad y rapidez.</li>
  <li>Matplotlib: para generar gráficos que muestran la evolución de los intereses en el tiempo.</li>
</ul>

<h2>Inputs del usuario</h2>

<p>El usuario debe ingresar los siguientes datos:</p>

<ul>
  <li>Capital inicial: la cantidad de dinero que se invertirá al inicio.</li>
  <li>Tasa de interés anual: el porcentaje de interés que se ganará por año.</li>
  <li>Plazo: la cantidad de meses durante los cuales se mantendrá la inversión.</li>
</ul>

<h2>Cálculo de intereses</h2>

<p>El script calcula los intereses en base a la tasa de interés mensual, la cual se obtiene dividiendo la tasa de interés anual entre 12.</p>

<p>Luego, se calculan los intereses para el caso de interés simple y compuesto.</p>

<ul>
  <li>Interés simple: se calcula la ganancia que se obtiene sobre el capital inicial en cada mes, sin reinvertir los intereses ganados en los meses anteriores.</li>
  <li>Interés compuesto: se calcula la ganancia que se obtiene sobre el capital inicial en cada mes, reinvirtiendo los intereses ganados en los meses anteriores.</li>
</ul>

<h2>Gráficos</h2>

<p>El script genera un gráfico que muestra la evolución de los intereses en el tiempo para ambos casos (interés simple e interés compuesto), permitiendo visualizar de manera clara la diferencia entre ambos.</p>

<h2>Resultados finales</h2>

<p>Finalmente, el script imprime los resultados finales:</p>

<ul>
  <li>El resultado bruto para el caso de interés simple, es decir, la cantidad total de dinero que se habrá ganado al final del plazo.</li>
  <li>El resultado bruto para el caso de interés compuesto, es decir, la cantidad total de dinero que se habrá ganado al final del plazo, considerando la reinversión de los intereses ganados.</li>
  <li>El porcentaje adicional de ganancia obtenido al elegir la opción de interés compuesto en lugar de interés simple.</li>
</ul>

<p>Es importante destacar que los resultados son brutos, es decir, no se han considerado posibles impuestos o comisiones que puedan aplicarse a la inversión.</p>
