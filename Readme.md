# Cross site scripting atack
*Noviembre 30 de 2022*, Ramón Peinado Ruiz



XSS o Cross-site scripting es un tipo de inyección la cual hace uso de scripts maliciosos*(malware basado en código)* que son inyectados en paginas webs de confianza.

Este tipo de ataque suele ser usado para robar información, secuestrar sesiones o comprometer el navegador.

<img src="/img/1ºimagenn.png" alt="1ºimagenn"  />

Podemos encontrarnos este tipo de ataque en dos formas distintas:

- Persistente: Consiste en insertar el script malicioso escrito en HTML en paginas *(con etiquetas como <script> o <iframe>)*  en webs donde haya vulnerabilidades para hacerlo. 

  <img src="/img/2ºimagenn.png" alt="2ºimagenn"  />

- Reflejada: Se trata de modificar valores que la web usa para pasar variables entre dos paginas, sin usar sesiones y se da cuando:

  - Hay un mensaje o una ruta en la URL del navegador (Mensaje de error...).

  - En una cookie.

    <img src="/img/3ºimagenn.png" alt="3ºimagenn"  />
