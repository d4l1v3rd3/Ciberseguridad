Traducción e implementación de https://gist.github.com/hackermondev/45a3cdfa52246f1d1201c1e8cdef6117

# Cloudfare

Como todos sabemos Cloudfare es uno de los CDN más populares del mercado (Content Delivery Network). 

Una de las características mas utilizadas de Cloudfare es el almacenamiento en cache. Normalmente en su cache se almacena contenido como imagenes, videos, etc.. En los mismos datacenters, para reducir carga del servidor y no imacte en la web.

https://developers.cloudflare.com/cache/

![image](https://github.com/user-attachments/assets/080f4abc-c535-4d61-9ddf-568ed916a8ce)

Cuando un dispositivo manda una consulta a un recurso esto se cachea, Cloudfare devuelve el recurso de su datacenter, si esta disponible. De lo contrario, obtiene el recurso del servidor de origen, lo almacena en caché localmente y luego lo devuelve.

Cloudflare tiene una amplia presencia global, con cientos de centros de datos en 330 ciudades en más de 120 países, aproximadamente un 273 % más de centros de datos que Google. En la región este de EE. UU., por ejemplo, el centro de datos más cercano a mí está a menos de 160 kilómetros. Si vives en un país desarrollado, es muy probable que el centro de datos más cercano a ti esté a menos de 320 kilómetros de ti.

