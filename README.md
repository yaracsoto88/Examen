# Examen
## Examen 1 de entornos 

### PARTE A
Una vez creado, abriremos Git CMD para empezar a escribir comandos. Entraremos a la dirección donde encontraremos la práctica a realizar, es decir la carpeta de git que está dentro de documentos, usando el comando cd.

![image](https://user-images.githubusercontent.com/114931679/205108621-a35407cd-eb27-4383-9647-1276cc448b0e.png)

Dentro de la carpeta, copiaremos la url correspondiente para clonar nuestro repositorio creado anteriormente. Usaremos el comando  ```git clone```
Se crea el directorio .git oculto

![image](https://user-images.githubusercontent.com/114931679/205109804-52d9f1c7-402f-4514-9d84-1c739c81078d.png)

Entramos al repositorio con el comando ```cd``` y reinicializamos con ```git init```
![image](https://user-images.githubusercontent.com/114931679/205110481-ebea8a2f-6572-4e19-a99f-2fb83abefd62.png)

Y ahora añado un archivo .txt con el comando ```git add```

![image](https://user-images.githubusercontent.com/114931679/205111804-8ed12b39-5baa-483c-b305-4dccd69124b2.png)

Ahora registraremos un cambio en el historial mediante ```git commit```

![image](https://user-images.githubusercontent.com/114931679/205112194-bd8756d1-dfb8-4b63-8f48-b3a99179707f.png)

Guardaremos los cambios. Es necesario permitirle el acceso. Con el comando ```git push origin main``` nos redirige a la página de github para iniciar sesión y guardar los cambios en el repositorio main. Y con el comando ```git pull origin main``` llevaremos los cambios a la copia local.

![image](https://user-images.githubusercontent.com/114931679/205112442-60a05aa6-d99b-48a1-8e9f-5e588c59dbb3.png)


Si entramos a nuestro repositorio en GitHub, se visualizará así:

![image](https://user-images.githubusercontent.com/114931679/205112661-369c38eb-6d5d-48fa-8aa6-ea8678cb5bc4.png)

Crearé otro archivo clase.txt para practicar hacer cambios y volver al estado original del archivo con el comando ```git checkout nombre-de-archivo```

![image](https://user-images.githubusercontent.com/114931679/205113195-50e754b6-0301-4f31-81d2-507532d8b314.png)


Ya aparece en el repositorio GitHub.

![image](https://user-images.githubusercontent.com/114931679/205113257-77a582b5-80a0-4888-a9ae-ae54b3a73c41.png)

Abro el archivo hago un par de cambios (añado "gato" y guardo):

![image](https://user-images.githubusercontent.com/114931679/205113477-5e88142c-a05e-4508-8ef9-0b5dd23bee92.png)

A continuación, ejecuto el comando ```git checkout```

![image](https://user-images.githubusercontent.com/114931679/205113777-10d7c4a2-9e0c-4649-aed1-cbbd7f4aafd8.png)

Y vuelvo a entrar para chequear que los cambios se han deshecho.

![image](https://user-images.githubusercontent.com/114931679/205113874-6fc329cf-7716-426f-8b00-4f17e5111c78.png)

Se ha cambiado con éxito.


### PARTE B
Lo primero que haré será actualizar la rama main, con ```git pull origin main```

![image](https://user-images.githubusercontent.com/114931679/205115638-a311d065-c04f-4a58-83b8-07e04638e373.png)

Ejecutaremos el comando ```git log –oneline –all``` para visualizar los commits hechos

![image](https://user-images.githubusercontent.com/114931679/205115861-f0851467-4a1a-44f6-ba1e-cfb8f811aad3.png)

Ahora podremos ver mediante type README.md el archivo correspondiente de la Parte A. En vez de “cat” ejecutaremos “type” ya que éste está registrado como comando en CMD.

![image](https://user-images.githubusercontent.com/114931679/205116062-b62819b0-606f-4a05-b472-40e9b626c761.png)

Nos movemos al primer commit realizado mediante ```git checkout```

![image](https://user-images.githubusercontent.com/114931679/205116551-2283fdfa-18bf-44aa-8a4d-2cb6679ce1e7.png)

Ahora volvemos a usar type README.md Nos muestra únicamente la primera línea del archivo de la primera practica

![image](https://user-images.githubusercontent.com/114931679/205116678-86cd258e-35a0-4edd-b923-da93e5f0b97a.png)

Y si nos fijamos, podemos ver que la referencia HEAD apunta al primer commit, el mismo en el que le hemos pedido que nos lea la primera línea.

![image](https://user-images.githubusercontent.com/114931679/205116810-498994c3-361d-4c47-a240-d496555c39bb.png)


A continuación, nos moveremos al primer commit mediante ```git checkout origin/main```,  comprobando a su vez que HEAD está en el sitio correspondiente.
Debería estar en el commit a donde nos hemos movido. 

![image](https://user-images.githubusercontent.com/114931679/205119304-6eff6343-86a1-477c-982b-4f68c7b863a9.png)




### PARTE C

#### Directorio de trabajo (Working directory): El directorio de trabajo es un directorio que contiene los archivos con los que trabajamos en un momento determinado en Git. Mientras cambiamos de rama, por ejemplo de la rama main a la master, dichos archivos podrán ser editados o eliminados. 
#### Área de preparación (Staging area): El área de preparación es el lugar donde se rastrean y se guardan los cambios, es decir los commits, que hacemos en los archivos con los que trabajamos. 
#### Repositorio local (Directorio .git): Es el directorio donde hacemos los cambios locales, por lo general este repositorio se encuentra en nuestro ordenador. 







