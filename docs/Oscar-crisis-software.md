# Análisis: El caso Therac-25

## ¿Qué fue el Therac-25?

El Therac-25 era una máquina de radioterapia, fabricada en los años 80 por la empresa canadiense AECL, que se usaba en hospitales para tratar a pacientes con cáncer. El problema fue que, a diferencia de los modelos anteriores, esta versión quitó los seguros físicos (de hardware) y dejó toda la seguridad del equipo en manos del software. Ahí empezó todo.

## ¿Qué pasó?

El software tenía un error de programación conocido como "condición de carrera": si el operador escribía los datos muy rápido y luego los corregía, el sistema se confundía y podía llegar a aplicar una dosis de radiación miles de veces mayor a la que debía. Para colmo, cuando algo fallaba, la máquina solo mostraba un código de error genérico, sin explicar qué tan grave era el problema. Y cuando empezaron a llegar reportes de que algo andaba mal, la empresa tardó en tomarlo en serio, incluso llegaron a decir que era imposible que la máquina causara una sobredosis.

## Las consecuencias

Entre 1985 y 1987 hubo al menos seis accidentes graves en hospitales de Estados Unidos y Canadá. Varios pacientes sufrieron quemaduras severas, y se estima que al menos tres personas murieron por estas fallas.

## Consecuencias legales... o la falta de ellas

A pesar de las muertes y los daños permanentes que sufrieron los pacientes, nunca hubo un proceso penal contra AECL ni contra los responsables del software. Las familias afectadas presentaron demandas civiles, pero la mayoría de estos casos se resolvieron con acuerdos económicos fuera de los tribunales, sin que se abriera una investigación penal formal. Nadie fue procesado ni encarcelado por lo ocurrido. La triste realidad es que, más allá de las indemnizaciones, no hubo una pena que cumplir, y las muertes y los daños ocasionados quedaron prácticamente impunes.

## Por qué importa este caso

El Therac-25 se volvió un ejemplo clásico en la enseñanza de Ingeniería de Software porque muestra algo muy fuerte: un error de programación, si no se prueba bien, puede costar vidas. No es solo cuestión de que un proyecto se atrase o cueste más de lo esperado, como en otros casos de la Crisis del Software; acá lo que estaba en juego era la seguridad de las personas. Este caso ayudó a que la industria empezara a tomarse mucho más en serio las pruebas de software, sobre todo en sistemas médicos o críticos, donde un fallo puede tener consecuencias reales y graves.

---
**Autor:** Oscar
**Tema:** Crisis del Software - Semana 2 (Caso Therac-25)