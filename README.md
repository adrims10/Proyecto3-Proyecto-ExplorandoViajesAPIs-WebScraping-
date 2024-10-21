![OIP](https://github.com/user-attachments/assets/1534bc19-9221-40a8-9ead-aeca1e9e0d19)
# Proyecto3-Proyecto-ExplorandoViajesAPIs-WebScraping-


Bienvenidos! 

# *Es un placer recibirlos*


# 📝 En que consiste:

¡Bienvenidos al proyecto de planificación de vacaciones! Este proyecto tiene como objetivo ayudar a organizar unas vacaciones para dos personas, utilizando técnicas de web scraping y APIs para recopilar información sobre vuelos, hoteles y actividades.

# Descripción

En este proyecto, se han scrapeado dos páginas web para obtener datos sobre actividades cercanas a los lugares y para obtener precios sobre alquieres de motos en estos mismos lugares . Además, se han utilizado dos APIs para recoger la informacion de los vuelos y los hoteles.


## 🗂️ Estructura del Proyecto
Hemos creado un entorno llamado Webscraping para el siguiente proyecto.

        ├── notebooks/           # Notebooks de Jupyter con los codigos en bruto y posibles pruebas
        ├── src/                 # Scripts de procesamiento y modelado
        ├─  Datos                # Datos, donde estaran los archivos csv que se han obtenido
        ├── README.md            # Descripción del proyecto
      
## 🛠️ Instalación y Requisitos
        Este proyecto usa Python 3.12.6.
        Se ha importado la libreria random.
        Se ha importado la libreria BeautifulSoup
        Se ha importado la libreria requests
        Se ha importado la libreria  pandas 
        Se ha importado la libreria numpy 
        Se ha importado la libreri sleep
        Se ha importado la libreria webdriver  
        Se ha importado la libreria ChromeDriverManager 
        Se ha importado la libreria Keys  
        Se ha importado la libreria Select  
        Se ha importado la libreria WebDriverWait
        Se ha importado la libreria expected_conditions as EC
        Se ha importado la libreria NoSuchElementException 
        Se ha importado la libreria re
        Se ha importado la libreria sys
        Se ha importado la libreria os
        Se ha importado la libreria  dotenv 


# 📝APIS:
    API SkiScrapper
    API Tripadvisor

# 📝Webs:
    https://civitatis.com/
    https://motoshare.es
 
 
- **Historia**:
Nos hemos definido como una pequeña empresa dedicada a organizar vacaciones peculiares. Como fundadores, disfrutamos hacer las cosas de forma espontánea, por lo que ofrecemos planes de un máximo de tres días.

¿Y qué tiene de peculiar un plan de tres días organizados? Ofrecemos a nuestros clientes la oportunidad de vivir el día a día de la ciudad que visitan. Con actividades diarias múltiples y a buen precio, permitimos que los viajeros recorran los lugares a su propio ritmo, ya sea a pie, en coche o en moto. Les brindamos pequeñas guías para que descubran por sí mismos dónde comer o disfrutar, asegurando una experiencia auténtica y personalizada.

Esta semana hemos tenido variedad de clientes:

*Parejas en busca de escapadas románticas*: Novios o parejas casadas que buscan un viaje especial para celebrar aniversarios, lunas de miel o simplemente para escapar de la rutina.

*Viajeros aventureros en solitario*: Personas que disfrutan explorando el mundo por su cuenta y están en busca de aventuras emocionantes, como senderismo, buceo, o viajes de mochilero.

*Grupos de amigos en busca de diversión:* Grupos de amigos que desean disfrutar juntos de unas vacaciones llenas de diversión y emoción, como surf, rafting, y una vibrante vida nocturna.

*Viajeros sostenibles y eco-conscientes*: Personas comprometidas con el turismo responsable y el cuidado del medio ambiente. Les interesan actividades como el ecoturismo, voluntariado ambiental y estancias en alojamientos ecológicos.

Todos estos residentes en Madrid Capital.

# *¿Que le hemos ofrecido?*

Hemos planteado dos destinos totalmente diferentes, Asturias y Malaga para asi desconectar del estres de la capital.
Para malaga hemos obtenido hoteles dentro de malaga capital y los vuelos de ida y vuelta. Pero aqui ofrecemos una variedad y es un listado con informacion de alquileres de todo tipos de motos para asi poder recorrer los pueblos de los alrededores y poder difrutar de las actividades variadas que tambien les vamos a proporcionar..

Para Asturias hemos obtenido hoteles y los vuelos de ida y vuelta. Aqui pensamos que la mejor opcion es caminar a las actividades proporcionadas debido a la posibilidad del disfrute del paisaje en Asturias.

**Resultados , Conclusiones**

Al analizar la calidad de los hoteles recolectados en nuestra muestra, encontramos que es similar en ambas ciudades, aunque con Asturias ligeramente por debajo. Dado que Asturias es una zona predominantemente rural, esta diferencia no resulta significativa.

En cuanto a los precios, los hoteles en Asturias presentan tarifas medias mas bajas. 

Observamos que el principal proveedor de hoteles en ambas ciudades es Booking. Sin embargo, en Asturias, la proporción de usuarios que eligen este servicio es superior. Teniendo en cuenta que los clientes prefieren Booking por la facilidad de sus servicios, esto sugiere que esta plataforma es más valorada en Asturias.

En conclusión, a pesar de que la satisfacción con los hoteles en Asturias es algo menor, el costo medio de hospedaje es más bajo. Esto hace que, en general, sea más favorable planificar un viaje a Asturias, donde la relación calidad-precio puede resultar más atractiva. Además, dado que Booking es el proveedor predominante, su uso ofrece una mayor seguridad a los usuarios.

En cuanto a las actividades, se observa que en Málaga los precios son considerablemente más altos. Si los clientes buscan un viaje con precios mínimos, apenas hay diferencias entre los destinos. Sin embargo, para aquellos que deseen una experiencia más alto nivel, las variaciones de precio son notables.

Incluso al eliminar la experiencia de "moto" en Málaga, la comparación entre las dos ciudades no muestra cambios significativos en la oferta. Para aquellos que busquen una experiencia media, Málaga resulta ser más cara en comparación con Asturias. Del mismo modo, si el cliente desea algo más común, los precios en Málaga también son más elevados.

Finalmente, al analizar las medias y las modas, constatamos que las medias son representativas, aunque la recopilación de datos en este caso es limitada. Además, al observar la inclusión de la moto en los paquetes, notamos que su impacto es mínimo, ya que los precios permanecen similares en ambas ciudades.


- **Próximos Pasos**

Los próximos pasos a seguir serían la escalabilidad de los scrapers y el estudio de APIs, lo que nos permitirá analizar más datos en nuestros estudios y llegar a más clientes. 📈

Podríamos investigar o escrapear alguna API para ofrecer también servicios de alquiler de coches. 🚗 Además, podríamos entrar en el mercado con recomendaciones sobre el tipo de equipamiento de moto que necesita el cliente para la ruta, brindando así ese servicio adicional. 🏍️

Sabemos que esta estrategia es fácilmente escalable y, con tres o cuatro ajustes, podríamos alcanzar grandes objetivos. 🌟


 

![OIP](https://github.com/user-attachments/assets/a3261f22-9193-45df-bf33-14a396dfd988)
