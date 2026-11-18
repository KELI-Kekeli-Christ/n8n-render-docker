<p align="center">
  <a href="README.md">English</a>
  &nbsp;·&nbsp;
  <a href="README.fr.md">Français</a>
  &nbsp;·&nbsp;
  <a href="README.es.md"><b>Español</b></a>
</p>

# n8n-render (modo fácil)

Fork de [antoineDsh/n8n-render-lamachine](https://github.com/antoineDsh/n8n-render-lamachine).

Archivos: `Dockerfile`, `render.yaml`, `README.md`.

Desplegar n8n en render.com:

1. Pulsar el botón Render del README en inglés
2. Elegir un nombre de blueprint, por ejemplo « n8n »
3. Pulsar « Create New Ressources »
4. Aplicar
5. Ir a Dashboard > n8n (nombre del servicio) > Environment
6. Copiar la URL (enlace violeta de la cabecera)
7. Pegar esa URL como valor de `WEBHOOK_URL`
8. Esperar un minuto a que se actualice
9. La instancia está lista

El README en inglés indica que la instancia es gratis 90 días y después cuesta 7 $/mes por la base de datos. Lo firma Antoine Deschamps para La Machine.
