# 20487D_MOD04_LAK_BlueYonderHotels

JOSE VICENTE TEJERO - 29/12/2020

RESUMEN

# Module 4: Extending ASP.NET Core HTTP Services
# Lab: Customizing the ASP.NET Core Pipeline

Use Dependency Injection to Get a Repository Object
Implement the interface on the repository
Register the repository object in the ASP.NET Core Dependency Injection mechanism
Change the controller’s constructor to request an injected repository

Create a Cache Filter
Create an action filter for cache headers
Add the cache filter to several actions
Test cacheable and non-cacheable actions from a browser

Create a Debugging Middleware
Write server and debug information to response headers
Create the IApplicationBuilder helper class
Register the middleware to the ASP.NET Core pipeline
Test the new middleware from a browser

PROBLEMAS
No
**20487D_MOD04_LAK**

 

**# Module 4: Extending ASP.NET Core HTTP Services**

 

\# Lab: Customizing the ASP.NET Core Pipeline

 

![img](clip_image002.png)

 

Levantamos el servicio:

![img](clip_image004.png)

 

Vemos http content:

 

![img](clip_image006.png)

 

Como en la última práctica, no me funciona el comando Invoke para consultar la disponibilidad:

![img](clip_image008.png)

 

No obstante, el servicio funciona como se puede comprobar en el navegador:

![img](clip_image010.png)

Para borrar una reserva, sí funciona el comando invoke:

 

![img](clip_image012.png)

Repetimos el comando para verificar que la lista de habitaciones no ha cambiado.

![img](clip_image014.png)

 

 

**Exercise 3: Create a Debugging Middleware**

**Task 5: Test the new middleware from a browser**

 

**![img](clip_image016.png)**

 

**![img](clip_image018.png)**
