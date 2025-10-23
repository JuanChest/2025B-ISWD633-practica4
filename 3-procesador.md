# Limitar uso de procesador
Limitar la cantidad de núcleos de CPU:
```
--cpus=<número de núcleos>
```

Asignar núcleos de CPU específicos:
```
--cpuset-cpus=<lista de núcleos>
```

**¿Como saber el numero de procesadores virtuales que tiene una máquina?**

En windows la manera más sencilla de verificar el número de procesadores virtuales, lógicos o hilos, es ingresando al administrador de tareas y en la pestaña de Rendimiento sse puede ver la utilización de los recursos de la computadora, entre ellos el del procesador que se muestra detalles como justamente el número de procesadores virtuales.

<img width="281" height="206" alt="image" src="https://github.com/user-attachments/assets/8e05a5f3-2cea-4f6c-ae2a-38b7603cf2fb" />

## COMPLETAR

## Ejemplos
_Puedes copiar y ejecutar directamente cada uno de los comandos_

Limitar el uso de CPU a 1.5 núcleos
```
docker run -d --name server-nginx --cpus="1.5" nginx:alpine
```

Restringir el contenedor para que use los núcleos de CPU 0 a 2:
```
docker run -d --name server-nginx --cpuset-cpus="0-2" nginx:alpine
```

Restringir el contenedor para que use los núcleos de CPU 1 y 3:
```
docker run -d --name server-nginx --cpuset-cpus="1,3" nginx:alpine
```
