﻿# Practica 1
## Creación de una pagina web desde Azure con WordPress
Primero me dirigí a la Marketplace del portal de Azure, ahí busque "WordPress"
![Marketplace de Azure](\img\1.png)
Después cree el recurso
![Creación de WordPress](img\2.png)
Selecciono mi suscripción de "Azure for Students", cree un grupo de recursos llamado "Sesion2-Practica1". Para la región seleccione South Central US para tener baja latencia, ya que es la región más cercana a mi, el nombre de la instancia puse el que yo quería, que fue "Practica1WP"
![Creación de WordPress en App Service](img\3.png)
Y después de revisarlo, lo cree, y visite el grupo de recursos
![Grupo de recursos creado](img\4.png)
Y la pagina web, quedo así, ese es el estilo predeterminado, supongo por que yo no programe nada de HTML ni CSS
![WordPress pagina default](img\5.png)
Después detuve el proceso de la base de datos para que no se cobrara el costo por tener activa instancia
![DataBase](img\6.png)
Cuándo el recurso se detiene, la pagina web deja de funcionar, y muestra el siguiente mensaje cuándo entras
![Error](img\7.png)
