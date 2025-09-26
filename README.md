# Material
* En las presentaciones se encuentran los enlaces para poder acceder a la documentacion tanto del Framework NIST como los Controles del CIS.
* Ademas de porporcionar un enlace en el cual se puede abordar con mas detalle la implementacion de los controles CIS en una organizacion.


#### Curso proporcionado por el profesor Ledezma
https://www.netacad.com/courses/ethical-hacker?courseLang=es-XL&instance_id=e2bf3893-44f9-43be-8c2f-a4c58b7dc9c9

# Wazuh

https://wazuh.com/
* Cada grupo debe instalar 1 servidor Wazuh.
* Recuerden que al finalizar la instalacion de Wazuh, el terminal les proporcionara un usuario y contrase;a, por favor guardar bien la contrase;a.
* En caso de que al intentar ingresar a la url de su Wazuh les aparezca **Wazuh dashboard server is not ready yet** ingresen los siguientes comandos en el terminal (con modo root):
  * ```systemctl start wazuh-manager```
  * ```systemctl start wazuh-dashboard```
  * ```systemctl start wazuh-indexter```
* El jueves 02 se definiran los dispositivos en el cual se instalaran los agentes que se conectaran a sus servidores.
