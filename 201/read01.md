# Introducción a la Web Moderna

## 1. ¿Qué roles desempeñan los clientes y los servidores en el funcionamiento de la web?

- **Clientes:**  
  Son computadoras que acceden a páginas web, sitios o aplicaciones. Cuando un usuario accede a una página web, el navegador del cliente descarga una copia de la página web desde el servidor y la muestra en el navegador del usuario.

- **Servidores:**  
  Son computadoras que almacenan páginas web, sitios o aplicaciones. Cuando un cliente quiere acceder a una página web, el servidor envía una copia de la página al dispositivo cliente para que sea mostrada en el navegador.

---

## 2. ¿Cómo se realiza la comunicación entre un navegador y un servidor al acceder a un sitio web?

1. **Solicitud del recurso:**  
   El usuario ingresa una URL; el navegador la traduce en una solicitud HTTP.

2. **Resolución DNS:**  
   El dominio se convierte en una dirección IP mediante un servidor DNS.

3. **Conexión:**  
   Se establece una conexión TCP (o TLS para HTTPS) entre el navegador y el servidor.

4. **Solicitud HTTP:**  
   El navegador envía una petición al servidor con detalles como el método (`GET` o `POST`) y encabezados.

5. **Respuesta HTTP:**  
   El servidor procesa la solicitud y responde con un código de estado, encabezados y el contenido solicitado.

6. **Renderización:**  
   El navegador interpreta el contenido (HTML, CSS, JS) y muestra la página al usuario.

7. **Solicitudes adicionales:**  
   Si se necesitan más recursos (imágenes, estilos, scripts), se realizan nuevas solicitudes al servidor.

**Este proceso asegura que los datos viajen de forma organizada entre el cliente y el servidor para mostrar la web correctamente.**

---

## 3. ¿Cuáles son las principales ventajas de utilizar un IDE en la nube en comparación con un IDE local?

- **Facilidad de uso:** Acceso a proyectos desde cualquier lugar sin necesidad de instalar software.  
- **Acceso a recursos remotos:** Integración con bases de datos, servidores web, etc.  
- **Escalabilidad:** Ajuste de recursos como CPU, memoria o almacenamiento según sea necesario.  
- **Actualización automática:** Siempre se tienen las últimas herramientas y parches.  
- **Seguridad:** Protección de proyectos sin depender de la seguridad del equipo local.  
- **Flexibilidad:** Permite trabajar en diferentes dispositivos sin preocupaciones por configuración.  
- **Costos:** Reduce los gastos en hardware al usar infraestructura en la nube.

---

## 4. ¿Qué funciones automatizadas comunes se encuentran en la mayoría de los IDE, y por qué son importantes para los desarrolladores?

- **Autocompletado:** Acelera la escritura y reduce errores tipográficos.  
- **Resaltado de sintaxis:** Mejora la legibilidad e identifica errores visualmente.  
- **Detección de errores (Linting):** Localiza problemas en tiempo real.  
- **Depuración:** Permite ejecutar el código paso a paso para encontrar fallos.  
- **Refactorización:** Reorganiza código sin alterar su funcionalidad.  
- **Integración con Git:** Gestiona cambios y colaboraciones directamente.  
- **Generadores de código:** Automatizan la creación de estructuras repetitivas.  
- **Terminal integrada:** Ejecuta comandos sin salir del IDE.  
- **Gestión de dependencias:** Simplifica la instalación y actualización de bibliotecas.  
- **Pruebas automatizadas:** Ejecuta pruebas directamente para asegurar calidad.  
- **Soporte multilenguaje:** Facilita trabajar con varios lenguajes en un solo entorno.  
- **Navegación avanzada:** Permite localizar referencias y archivos rápidamente.  
- **Simulación:** Prueba aplicaciones en entornos simulados.

**Estas funciones mejoran la productividad, reducen errores y optimizan flujos de trabajo, permitiendo a los desarrolladores enfocarse en resolver problemas complejos y mantener un código de calidad.**