# LaboratorioFront
## Comando para ejecutar laboratorio
```bash
sudo docker build -t front .
sudo docker run -p 3000:80 -e PORT=3000 -e HOST=0.0.0.0 -d --restart unless-stopped --name miFront -it front
``` 
