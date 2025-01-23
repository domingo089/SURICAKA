Cómo instalar y Configurar SURICATA en Ubuntu. 

Te explicamos paso a paso cómo puedes instalar SURICATA en Ubuntu, y configurar SURICATA en UBUNTU paso a paso desde la terminal usando comandos:

sudo apt install suricata (Comando para instalar Suricata)
sudo systemctl status suricata (Validar el estado de Suricata)
sudo systemctl start suricata (Comando para ejecutar en caso de error al instalar Suricata)
sudo nano /etc/suricata/suricata.yaml (Comando para acceder al archivo de configuración de Suricata)
sudo suricata-update -o /etc/suricata/rules (Comando para actualizar las reglas de Suricata)
sudo suricata-update list-sources (Comando para listar sets de reglas disponibles)
sudo suricata-update enable-source tgreen/hunting (Comando para agregar una regla)
sudo suricata-update -o /etc/suricata/rules (Comando para actualizar de nueo las reglas)
sudo suricata -T -c /etc/suricata/suricata.yaml -v (Comando para validar la configuración de Suricata)
curl http://testmynids.org/uid/index.html (Comando para validar el funcionamiento HTTP)
sudo apt install curl (Comando para ejecutar en caso de no contar con CURL)
grep 2100948 /var/log/suricata/fast.log (Comando grep para validar si existen entradas)

