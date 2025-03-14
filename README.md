# Repositorio2: Plataforma Web de Cifrados (César, Vigenère, DES, AES)
Un proyecto diseñado para proporcionar una página web interactiva donde los usuarios puedan cifrar y descifrar mensajes utilizando diferentes algoritmos de criptografía clásica y moderna: César, Vigenère, DES y AES.
Esta herramienta está pensada para estudiantes, entusiastas y profesionales que deseen experimentar, aprender y entender cómo funcionan los diferentes métodos de cifrado de forma práctica y visual.
Objetivo del Proyecto
- Permitir a los usuarios cifrar y descifrar mensajes fácilmente desde una página web.
- Enseñar el funcionamiento de diferentes algoritmos de cifrado.
- Proporcionar una herramienta educativa y didáctica, sin necesidad de instalar software adicional.

Cifrados disponibles
- César: Desplaza cada letra del mensaje una cantidad fija de posiciones.
- Vigenère: Usa una palabra clave para cifrar mediante desplazamientos variables.
- DES: Cifrado por bloques simétrico, seguro para aplicaciones controladas.
- AES: Estándar moderno de cifrado avanzado por bloques, muy seguro.

Requisitos:
- Descargar el repositorio
- Entra en la carpeta del proyecto
- Levanta un servidor local (puedes usar VSCode Live Server o Python):
- Con Python 3.x: python -m http.server
- Abre el navegador y entra en: http://localhost:8000

Instrucciones para trabajar con los cifrados
1. Abrir la página
Al abrir index.html, verás una interfaz simple e intuitiva con las siguientes secciones:
- Selector de Algoritmo: Escoge entre César, Vigenère, DES o AES.
- Área de Texto: Para escribir el mensaje a cifrar o descifrar.
- Campo de Clave: Introduce la clave requerida según el cifrado.
- Botón de Cifrar: Para obtener el mensaje cifrado.
- Botón de Descifrar: Para obtener el mensaje original.
  
2. Ingresar datos
- Escribe tu mensaje en el cuadro de texto.
- Especifica la clave (número o palabra, según el cifrado).
  
3. Cifrar o descifrar
- Haz clic en Cifrar para ver el texto cifrado.
- Haz clic en Descifrar para recuperar el texto original.

4. Resultado
El resultado se mostrará al instante en la pantalla.

Tecnologías utilizadas
- HTML: Para la estructura del sitio web.
- CSS: Para el diseño y estilos visuales.
- JavaScript: Lógica de los cifrados y la interacción con el usuario.

Ejemplo de uso (Cifrado César)
Mensaje: CASA
Clave: 3
Resultado Cifrado: ECUC
Resultado Descifrado: CASA

¿Para quién es este proyecto?
- Estudiantes de ciberseguridad y criptografía.
- Profesores que buscan una herramienta práctica para enseñar cifrados.
- Cualquier persona interesada en proteger información o entender cómo funcionan los algoritmos de cifrado.
