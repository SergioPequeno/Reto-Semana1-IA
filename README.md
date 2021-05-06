# Reto-Semana1-IA

# Conceptos

## ¿Que es la nube? ##

"La nube" hace referencia a los servidores a los que se accede a través de Internet, y al software y bases de datos que se ejecutan en esos servidores. Los servidores de la nube están ubicados en centros de datos por todo el mundo. Mediante el uso de la computación en nube, no es necesario que los usuarios y empresas gestionen los servidores físicos por sí mismos ni que ejecuten aplicaciones de software en sus propios ordenadores.

![image](https://user-images.githubusercontent.com/83681168/117230376-92ada600-ade2-11eb-81ec-239fbc8a2649.png)


## ¿Cómo funciona la computación en nube?

La computación en nube es posible gracias a una tecnología conocida como virtualización. La virtualización permite la creación de un ordenador virtual, simulado y digital que se comporta como si fuera un ordenador físico con su propio hardware. El término técnico para este ordenador es máquina virtual. Cuando se implementan de forma correcta, las máquinas virtuales en la misma máquina host están separadas entre ellas, así que no interactúan entre sí, y los archivos y las aplicaciones de una máquina virtual no son visibles para las otras máquinas virtuales, a pesar de estar ubicadas en la misma máquina física.
Las máquinas virtuales también hacen un uso más eficiente del hardware en el que están alojadas. Al ejecutar muchas máquinas virtuales al mismo tiempo, un servidor se transforma en muchos servidores, y un centro de datos se transforma en una gran cantidad de centros de datos, que tienen la capacidad de servir a muchas organizaciones.

## ¿Cuáles son los principales modelos de servicio de la computación en nube?
**Software como servicio (SaaS):** | **Plataforma como servicio (PaaS):** | **Infraestructura como servicio (IaaS):** | **Función como servicio (FaaS):** |
------------ | ------------- | ------------ | ------------- |
en lugar de que los usuarios instalen una aplicación en su dispositivo, las aplicaciones de SaaS se alojan en servidores en la nube y los usuarios pueden acceder a ellas a través de Internet. El SaaS es como alquilar una casa: el arrendador sigue siendo el propietario de la casa, pero el arrendatario tiene derecho a usarla como si fuera suya. Ejemplos de aplicaciones de SaaS incluyen Salesforce, MailChimp y Slack. | en este modelo, las empresas no pagan por las aplicaciones alojadas, sino que pagan por lo que necesitan para desarrollar sus propias aplicaciones. Los proveedores de PaaS proporcionan todo lo necesario para crear una aplicación, incluyendo herramientas de desarrollo, infraestructura y sistemas operativos, todo a través de Internet. El PaaS se puede comparar con alquilar todas las herramientas y equipamiento necesarios para construir una casa, en lugar de alquilar la casa en sí. Algunos ejemplos de PaaS incluyen Heroku y Microsoft Azure.| en este modelo, una empresa alquila los servidores y el almacenamiento que necesita de un proveedor de nube. Luego, utilizan esa infraestructura en la nube para desarrollar sus aplicaciones. IaaS es como una empresa que alquila un terreno en el que se puede construir lo que se quiera, pero tienen que proporcionar su propio equipamiento y materiales de construcción. Los proveedores de IaaS incluyen DigitalOcean, Google Compute Engine y OpenStack. |  FaaS, también conocida como computación sin servidor, divide las aplicaciones en la nube en componentes todavía más pequeños que solo se ejecutan cuando son necesarios. Imagínate que fuera posible alquilar una casa por partes: por ejemplo, el arrendatario solo paga por el comedor a la hora de la cena, el dormitorio a la hora de dormir, el comedor cuando ve la TV, y cuando no esté usando ninguna de ellas, no tendrán que pagar el alquiler de las mismas. | 

![image](https://user-images.githubusercontent.com/83681168/117231066-09976e80-ade4-11eb-8c17-8a5b6e2f2b57.png)

## ¿Cuáles son los diferentes tipos de implementación en nube?

A diferencia de los modelos discutidos anteriormente, que definen cómo se ofrecen los servicios a través de la nube, estos tipos de implementación en la nube dependen de la ubicación de los servidores y de quién los gestiona.

Las implementaciones en la nube más habituales son:

_**Nube privada:]**_ una nube privada es un servidor, centro de datos o red distribuida que está al servicio de una única organización.
_**Nube pública:**_ una nube pública es un servicio gestionado por un proveedor externo que puede incluir servidores en uno o varios centros de datos. A diferencia de una nube privada, las nubes públicas las comparten muchas organizaciones. Con el uso de máquinas virtuales, diferentes empresas pueden compartir los servidores individuales, una situación que se conoce como "tenencia múltiple", ya que varios arrendatarios alquilan espacio en el servidor dentro del mismo servidor.
_**Nube híbrida:**_ las implementaciones de nube híbrida combinan nubes públicas y privadas, e incluso pueden incluir servidores heredados en las instalaciones. Una organización puede utilizar su nube privada para algunos servicios y la nube pública para otros, o puede usar la nube pública como copia de seguridad de su nube privada.
_**Multinube:**_ la multinube es un tipo de implementación en la nube que implica el uso de varias nubes públicas. En otras palabras, una organización con una implementación de multinube alquila servidores y servicios virtuales de varios proveedores externos; para continuar con la anterior analogía, esto sería como alquilar varias parcelas adyacentes de diferentes propietarios. Las implementaciones de multinube también pueden ser una nube híbrida y viceversa.

