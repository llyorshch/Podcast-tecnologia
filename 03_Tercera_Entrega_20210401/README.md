# Tercera entrega

## Ideas para las noticias

### Google y [el cambio de estrategia para eliminar el uso de cookies de terceros](https://blog.google/products/ads-commerce/a-more-privacy-first-web/)

En Google le están viendo las orejitas al lobo con el tema de la privacidad. Otros navegadores como Safari o Firefox están mucho más comprometidos y de hecho su uso está creciendo.

En Google quieren pasar a que se emplee [FLoC](https://github.com/WICG/floc), que en pocas palabras, sirve para que sea el navegador el que lleve el control de lo que estás navegando y por tanto, segmentarte en grupos de interés que pueden ser usados para que los anunciantes te muestren lo que te interesa. O sea, que te espíe el navegador en lugar de 1000 webs. Parece un avance pero la cosa no está del todo clara...

### [Spring Native Beta](https://spring.io/blog/2021/03/11/announcing-spring-native-beta) 🎉 🥳 🎊

Por fin, Spring anuncia la beta del proyecto de Spring para crear (fácilmente) aplicaciones nativas.

Básicamente, metes una dependencia en tu proyecto Spring Boot y ¡Boom! Tienes una aplicación Nativa con GraalVM

¿Es esto el fin de Quarkus y Micronaut? Seguramente, no, pero no les va a ayudar mucho. Si Spring reduce la fricción de convertir una aplicación Spring Boot en una aplicación nativa, ya hay un motivo menos para cambiar. 

### NFTs. Hype, Smart contracts & money laundry.

Los NFTs han saltado a los medios por [la venta de un JPG por cerca de $70M](https://www.nytimes.com/2021/03/11/arts/design/nft-auction-christies-beeple.html)

Pero lo interesante es el nuevo escenario que plantea. Arte que incluye reglas digitales que establecen quien es el propietario, por cuanta manos ha pasado y qué pasa en cada transacción, incluyendo acciones como que el artista original reciba parte de la venta o que pasado un tiempo la obra pase al dominio público.

Aunque pueda parecer que esto es el fin del blanqueo de dinero en el mercado del arte, al tratarse de criptomoneda... no está nada claro que esto vaya a ser así. Pero es un empiece.

### BIG Fail con la protección antiminería de NVidia

[Se les ha "escapado" un driver beta sin el limitador](https://www.theverge.com/2021/3/15/22331537/nvidia-rtx-3060-ethereum-cryptocurrency-mining) 🤦‍♂️🤦‍♂️🤦‍♂️

Pero eso no es lo más fuerte... [con un terminador HDMI el limitador no se activa](https://www.tomshardware.com/news/cryptominers-fool-nvidia-anti-mining-limited-hdmi-dummy-plug) 🤦‍♂️🤦‍♂️🤦‍♂️🤦‍♂️🤦‍♂️🤦‍♂️🤦‍♂️

En fin, esto no iba a solucionar nada así que si ha fallado lo único que se ha echado a perder (un poquito más) es la credibilidad de la marca

El gran problema de abastecimiento va a seguir siendo que los fabricantes de chips no dan abasto por la ENORME demanda que hay que nadie supo prever. PREVISIÓN PEREGRINA TOTALMENTE INNECESARIA: Nos queda un año hasta que los stocks vuelvan a la normalidad.

## Tema principal - Flowable

- ¿Qué es Flowable? Como si se lo explicaras a tus padres.
- ¿Qué sentido tiene todo esto? Dicho de otra manera, ¿Qué hace que trabajar con Flowable tenga sentido?
- ¿Qué tipos de proyectos hacemos con Flowable? ¿Y qué tipo de proyectos hacen otros (OSS o no)?
- Vale, todo esto mola mucho pero, ¿por donde empiezo?
  - Entra en la web y echa un vistazo, tanto a la parte [OSS](https://flowable.com/open-source/) como a la parte [Enterprise](https://flowable.com).
  - [Bájate el código](https://github.com/flowable/flowable-engine)
  - Date de alta en los foros y echa un vistazo [OSS](https://forum.flowable.org) y [Enterprise](https://forum.flowable.com)
  - Échale un vistazo al [blog](https://blog.flowable.org) Tiene entradas muy interesantes como el [Instant gratifiation](https://blog.flowable.org/2020/10/07/flowable-6-instant-gratification/) para empezar a modelar y [una guía para hacer una app con Spring Boot desde cero](https://blog.flowable.org/2018/12/19/building-your-own-flowable-spring-boot-application/)
  - Si quieres empezar a trastear rápidamente, puedes usar nuesto [Initialzr](https://initializr.flowable.io). Es un proyecto que mantiene el equipo de soluciones con el que puedes generar un proyecto rápidamente. Si eliges como tipo de proyecto "Flowable Core" se genera un proyecto 100% OSS. Los otros dos tipos de proyecto requieren tener acceso a los repositorios privados de Flowable. En cualquier caso, está bien para ver qué pinta tiene un proyecto de Flowable típico (que es básicamente un proyecto Spring Boot con las dependencias de Flowable.)