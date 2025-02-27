# 1- Diseño Modular vs. "Monolítico"

Si React se basa en la división por componentes, ¿qué desventajas encuentras cuando se crea la interfaz de manera "monolítica" (un solo archivo de gran tamaño) y por qué crees que esa práctica sigue siendo habitual en algunos proyectos?

- **Dificultad de Mantenimiento:** Un archivo extenso se vuelve complicado de leer y entender. (V)
- **Reutilización Limitada:** Si una funcionalidad se repite, es necesario copiar y pegar código en lugar de reutilizar componentes. (V)
- **Menor Escalabilidad:** A medida que el proyecto crece, el código monolítico se vuelve más difícil de manejar. (V)
- **Problemas de Rendimiento:** Un solo archivo grande implica que todo el código se debe cargar de una vez, lo que puede afectar el rendimiento. (V)
- **Menor Colaboración:** Con componentes separados, es más fácil que diferentes personas trabajen en distintas partes sin interferencias. (V)

## 2- JSX y Legibilidad

¿Puede la mezcla de JavaScript y sintaxis similar a HTML terminar haciendo el código más difícil de entender en grandes equipos de trabajo? Piensa en cómo abordarías la necesidad de uniformidad y "estilo" de código con un equipo amplio.

Sin buenas prácticas puede volverse caótico en equipos grandes. La clave está en mantener el código modular, bien formateado con estructuras de carpeta o convenciones claras para que sea comprensible y fácil de mantener. (V)

## 3- El Papel de la Abstracción

¿Hasta qué punto la arquitectura basada en componentes favorece o entorpece la comprensión del "flujo general" de la aplicación? ¿Podría un exceso de "componentes pequeños" complicar la mantención en lugar de facilitarla?

La arquitectura por componentes mejora la organización, pero demasiados componentes pequeños pueden fragmentar el flujo y dificultar la comprensión del código. (I)

## 4- Performance y Client-Side Rendering

¿Crees que delegar el renderizado al navegador siempre dará una experiencia de usuario óptima? Imagina escenarios de conexión inestable o dispositivos menos potentes: ¿cómo podría verse afectada la aplicación en estos casos?

CSR depende del dispositivo y la conexión. En hardware débil o redes inestables, la carga inicial puede ser lenta, afectando la experiencia del usuario. (V)

## 5- SEO y CSR

CSR puede afectar negativamente el SEO, ya que los motores de búsqueda pueden no indexar bien el contenido generado en el cliente. Técnicas como SSR (Next.js) o prerendering ayudan a mitigar esto. (V)

## 6- Bundlers: Beneficio o Complejidad Extra

Al empaquetar y minificar el código, se gana en velocidad de carga, pero se aumenta la complejidad en la configuración. ¿Crees que el uso de bundlers vale la pena en proyectos pequeños? ¿En qué momento se vuelven esenciales?

En proyectos pequeños, un bundler puede ser innecesario. Se vuelve esencial cuando hay múltiples dependencias, optimización de assets y necesidad de mejorar el rendimiento. (I)

## 7- Ventaja Competitiva de React

React no es el único framework/librería que implementa arquitectura de componentes (por ejemplo, Vue, Angular o Svelte). ¿Por qué crees que, aun así, React conserva una gran popularidad en el mercado laboral?

React sigue siendo popular por su ecosistema maduro, comunidad activa, flexibilidad y demanda en el mercado laboral, a pesar de la competencia con Vue, Angular y Svelte. (V)

## 8- Mantenimiento a Largo Plazo

¿En qué punto la modularidad de componentes deja de ser un beneficio y puede generar confusión o duplicidad de esfuerzos? Piensa en ejemplos donde la repetición excesiva de patrones podría no ser óptima.

La modularidad excesiva puede generar componentes redundantes o sobreingeniería. Definir patrones claros evita duplicación innecesaria y mejora la mantenibilidad. (V)

## 9- Rol de la IA en la Creación de Componentes

¿Qué implicaciones tiene el utilizar herramientas de IA (ChatGPT, Claude AI, GitHub Copilot) para generar componentes de React? ¿Hasta dónde se puede delegar la creación y mantenimiento de componentes sin perder la comprensión y control del proyecto?

IA puede acelerar el desarrollo, pero confiar demasiado en ella sin revisar el código puede generar problemas de calidad y comprensión a largo plazo. Lo ideal es usarla como apoyo, no como reemplazo del pensamiento crítico. (V)
