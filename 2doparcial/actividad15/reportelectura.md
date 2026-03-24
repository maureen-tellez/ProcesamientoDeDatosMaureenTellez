## 1.1 La naturaleza como optimizadora

La naturaleza ha sido reconocida históricamente como un sistema capaz de generar 
soluciones óptimas. Leonardo Da Vinci ya señalaba que ningún invento humano podría 
superar la perfección y simplicidad de los que produce la naturaleza.

Los seres vivos son el resultado de miles de generaciones de pequeños ajustes 
acumulados. Los individuos menos aptos perecen, mientras que los mejor adaptados 
sobreviven y transmiten sus características — esto es la **selección natural** 
descrita por Darwin.

Esta cualidad optimizadora de la naturaleza inspiró a científicos como:
- **Rechenberg (1965):** propuso las *estrategias evolutivas* para optimizar 
  funciones de varias variables.
- **Fogel, Owens y Walsh (1966):** desarrollaron la *programación evolutiva*.
- **John Holland (años 60):** desarrolló los **algoritmos genéticos (AGs)** en 
  la Universidad de Michigan, buscando modelar formalmente la adaptación en 
  sistemas naturales y artificiales.

Hoy los AGs son ampliamente usados como métodos de búsqueda y optimización, 
con aplicaciones en *machine learning* e inteligencia artificial.

## 1.2 Un poco de biología

Para entender los algoritmos genéticos es necesario conocer los mecanismos 
biológicos que simulan.

### Conceptos clave:

| Término biológico | Descripción | Analogía en AG |
 
| **Fenotipo** | Características observables del individuo | Solución decodificada |
| **Genotipo / Genoma** | Información genética completa | Cromosoma / código genético |
| **Gen** | Subcadena de nucleótidos que codifica una proteína | Posición en el cromosoma |
| **Alelo** | Valor que posee un gen | Valor de un bit o carácter |
| **Cromosoma** | Molécula de ADN con la información hereditaria | Individuo en la población |
| **Mutación** | Error en la replicación del ADN | Cambio aleatorio en un gen |
| **Meiosis** | División celular para reproducción | Operador de cruza |

### Proceso de reproducción (Meiosis):
1. Se duplican los cromosomas del padre y la madre.
2. Los cromosomas se **cruzan** (crossover) intercambiando segmentos.
3. Se generan 4 células haploides con combinaciones nuevas.

### Mutación:
La **ADN-polimerasa** replica los cromosomas, pero ocasionalmente comete errores. 
Aunque la mayoría de mutaciones son desfavorables, algunas otorgan ventajas 
al individuo, las cuales se transmiten a sus descendientes — dando un pequeño 
paso evolutivo.