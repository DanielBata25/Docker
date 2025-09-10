### 📌 Qué pasó con ese comando

## apt-get update -y → actualizó la lista de paquetes desde los repositorios de Ubuntu (noble = Ubuntu 24.04, tu caso).  
✅ Resultado esperado: ves muchos Get:... y Hit:..., eso significa que actualizó correctamente.  

## apt-get install -y curl wget ca-certificates gnupg lsb-release nginx → todavía está en proceso de descargar los paquetes en la captura. Va bajando desde archive.ubuntu.com y security.ubuntu.com.  

Esto instalará curl, wget, certificados, gnupg, lsb-release y nginx.  

Al final deberías ver algo como Setting up nginx ... o nginx installed successfully.  

👉 Hasta aquí todo está correcto.  

## Cuando termine la instalación, puedes verificar:  

curl --version  
wget --version  
nginx -v  

Eso te confirmará que quedaron instalados.  
