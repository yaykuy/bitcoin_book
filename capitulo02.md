# Capitulo II: Bitcoin: Qué es y como funciona
##1. Que es bitcoin

Bitcoin es una moneda digital peer-to-peer (par a par o, simplemente, de punto a punto), de código abierto, que no depende de una autoridad central. Entre muchas otras cosas, lo que hace el bitcoin ser único es el hecho de él ser el primer sistema de pagamentos global totalmente descentralizado. Aunque a la primera vista pueda parecer complicado, los conceptos fundamentales no son difíciles de comprender.


### Visión general

 Hasta la invención del Bitcoin, en 2008, por un programador no identificado conocido solo por el nombre Satoshi Nakamoto, transacciones online siempre requirieron un tercer intermediario de confianza. Por ejemplo, si Maria quisiera enviar  100 u.m. a Juan por medio de la internet, ella tendría que depender de servicios de terceros como Paypal o Mastercard. Intermediarios como el paypal mantiene un registro de los saldos en las cuentas de los clientes.  Cuando Maria envía 100 u.m a Juan, el Paypal debita la cuantía de su cuenta, abonándola en la cuenta de Juan. Sin intermediarios , un dinero digital podría ser gasto dos veces. Imagine que no haya intermediarios con registros históricos, y que el dinero digital sea simplemente un archivo de la computadora. Maria podría enviar a Juan 100 u.m. simplemente anexando el archivo de dinero en una mensaje. Pero así como ocurre con un e-mail, enviar un archivo como anexo no lo remueve de la computadora originadora de la mensaje electrónica. Maria retendría la copia del archivo después de enviarlo anexado a mensaje. De esta forma, ella podría fácilmente enviar las mismas 100 u.m a Marcos. En la ciencia de la computación, esto es conocido como el problema de ‘gasto doble’, y, hasta el advenimiento del Bitcoin, esta cuestión solamente podría ser solucionada por medio de un tercer de confianza que empleara un registro histórico de transacciones.

 La invención del Bitcoin es revolucionaria porque es la primera vez que el problema del gasto doble puede ser resuelto sin la necesidad de un tercer; bitcoin lo hace distribuyendo el imprescindible registro histórico a todos los usuarios del sistema vía una red peer-to-peer. Todas las transacciones que ocurren en la economía bitcoin son registradas en una especie de libro mayor2 publico y distribuido llamado de blockchain (corriente de bloque, o simplemente un registro publico, conteniendo el 

[Nota del autor]: Este segundo capitulo es una traducción de la obra de Jerry Brito y Andrea Castillo, “Bitcoin: A Primer for Policymakers” (Arlington, VA: Mercatus Center at George Mason University, 2013). La sección final sobre regulación fue reducida visando adecuarla al publico brasileño.
2 Libro mayor es el nombre dado por los profesionales de contabilidad al agrupamiento de los registros contables de una empresa que usa el método de las partidas dobradas. En él es posible visualizar todas las transacciones ocurridas en dado periodo de operación de una empresa.


histórico de todas las transacciones realizadas. Nuevas transacciones son verificadas contra el blockchain de modo a asegurar que los mismos bitcoins3 no hayan sido previamente gastos, eliminando así el problema de gasto doble. La red global peer-to-
peer, compuesta de millares de usuarios, se transforman el proprio intermediario; Maria y Juan pueden transacionar sin el Paypal.

 Es importante notar que las transacciones en la red Bitcoin no son denominadas en dólares, euros o reales, como son en el Paypal o mastercard; son denominadas en bitcoins. Esto vuelve el sistema Bitcoin no solo una red de pagamentos descentralizada, pero también una moneda virtual. El valor de la moneda no deriva del oro o de algún decreto del gobierno, pero del valor que las personas le atribuyen. El valor en reales de un bitcoin es determinado en un mercado abierto, de la misma forma que son establecidas las tasas de cambio entre diferentes monedas mundiales.

 
### Como funciona
Hasta ahora discutimos que es bitcoin: una red de pagamentos peer-to-peer y una moneda virtual que opera, esencialmente, como el dinero online. Miremos ahora como es su funcionamiento.

 Las transacciones son verificadas, y el gasto doble es prevenido, por  medio de un uso inteligente de la criptografía de clave publica. Tal mecanismo exige que a cada usuario sean atribuidas dos ‘claves’, una privada, que es mantenida en secreto, como una seña, y otra publica, que puede ser compartida con todos. Cuando Maria decide transferir bitcoins a Juan, ella crea una mensaje, llamada de ‘transacción’, que contiene la clave publica de Juan, firmando con la clave privada. Mirando la clave publica de Maria, cualquier uno puede verificar que la transacción fue de hecho firmada con su clave privada, siendo, así, un cambio autentico, y que Juan es el nuevo propietario de los fundos. La transacción – es por tanto una transferencia de propiedad de los bitcoins – es registrada, carimbada con fecha y hora y expuesta en un “bloque” del blockchain ( el gran banco de datos, o libro mayor de la red bitcoin). La criptografía de clave publica garante que todas las computadoras en la red tengan un registro constantemente actualizado y verificado de todas las transacciones dentro de la red Bitcoin, lo que impide el gasto doble y cualquier tipo de fraude.

 ¿Pero que significa cuando decimos que “la red” verifica las transacciones y las reconcilia con el registro publico? ¿Y como exactamente son creados y introducidos nuevos bitcoins en la oferta monetaria? Como vimos, porque el bitcoin es una red peer- 

3 Cuando nos referimos al sistema, a la red o al proyecto Bitcoin, usamos siempre inicial mayúscula. No obstante, cuando hacemos referencia a las unidades monetarias bitcoins, utilizamos la palabra con letra minúscula.

to-peer, no hay una autoridad central encargada ni de crear unidades monetarias ni de verificar las transacciones. Esta red depende de los usuarios que proveen la fuerza computacional para realizar los registros y las reconciliaciones de las transacciones. Eses usuarios son llamados de “minero”4, a medida que millares de computadoras dispersas resuelven problemas matemáticos complexos que verifican las transacciones en el blockchain. Como un analista afirmó,
   
       La real minería de bitcoins es puramente un proceso matemático. Una 
       analogía útil es la procura de números primos: acostumbraba ser 
       relativamente fácil hallar los menores (Erastostenes, en la Grecia 
       antigua, produjo el primer algoritmo para encontrarlo). Pero a medida
       que ellos eran encontrados, se volvía más difícil encontrar los
       mayores. Hoy en día, investigadores usan computadoras avanzadas 
       de alto desempeño para encontrarlos, y sus hazañas son observadas 
       por la comunidad de la matemática (por ejemplo, la Universidad de 
       Tennesse mantiene una lista de los 5000 mayores).

       En el caso de Bitcoin, la busca no es, en realidad, por números primos,
       pero por encontrar la secuencia de datos (llamada de “bloque”) que 
       produce cierto patrón cuando el algoritmo “hash” del bitcoin es 
       aplicado a los datos. Cuando una combinación ocurre, el minero 
       obtiene un premio de bitcoins (y también una tasa de servicio,
       en bitcoins, en el caso de lo mismo bloque haber sido usado para
       verificar una transacción). El tamaño del premio es reducido al 
       paso que los bitcoins son minados.
 
       La dificultad de la busca también aumenta, haciendo con que sea
       computacionalmente más difícil encontrar una combinación. Eses
       dos efectos combinados acaban por reducir a lo largo del tiempo la 
       tasa de producción de una mercancía como el oro. En un momento
       futuro, nuevos bitcoins no serán producidos, y el único incentivo a
       los mineros serán las tasas de servicios por la verificación de 
       transacciones5.


 El protocolo, por tanto, fue proyectado de tal forma que cada minero contribuye con la fuerza de procesamiento de su computadora con vistas a la sustentación de infraestructura necesaria para mantener y autenticar la red de la moneda digital. Mineros son 

4 Mineros tienden a ser entusiastas de la computación comunes, pero a medida que la minaría se vuelve más difícil y cara, la actividad será, probablemente, profesionalizada. Para mayores informaciones, ver LIU, Alec. A Guide To Bitcoin Mining. Motherhood, 2013. Disponible en: <http://motherbord.vice.com/blog/a-guide-to-bitcoin-mining-why-someone-bought-a-1500-bitcoin-miner-on-ebay-for-20600>  Acceso en:10 dec. 2013
5 TINDELL, Ken. Geeks Love the Bitcoin Phenomenon Like They Loved The Internet in 1995. Business Insider, 5 abr. 2013. Disponible en: http://www.businessinsider.com/how-bitcoins-are-mined-and-used-2013-4  Acceso en: 10 dec. 2013.

premiados con bitcoins recién-creados por contribuir con fuerza de procesamiento para mantener la red y por verificar las transacciones en el blockchain. Y a medida que más 
capacidad computacional es dedicada a minería, el protocolo incrementa la dificultad
del problema matemático, asegurando que bitcoins sean siempre minados a una tasa previsible y limitada.

 Ese proceso de minería de bitcoins no continuará indefinidamente. El bitcoin fue proyectado de modo a reproducir la extracción de oro u otro metal precioso de la Terra – solamente un numero limitado y previamente conocido de bitcoins podrá ser minado.
La cuantidad arbitraria escogida como limite fue de 21 millones de bitcoins. Se estima que los mineros recogerán el ultimo “satoshi”, o 0,00000001 de un bitcoin, en el año de 2140. Si la potencia de minaría total escalar a un nivel bastante elevado, la dificultad de minar bitcoins aumentará tanto que encontrar el ultimo “satoshi” será un destajo digital considerablemente desafiador. Una vez que el ultimo “satoshi” tenga sido minado, los mineros que direccionan su potencia de procesamiento al acto de verificación de las transacciones serán recompensados con tasas de servicio, en vez de nuevos bitcoins minados. Eso garante que los mineros todavía tengan un incentivo de mantener la red operando después de la extracción del ultimo bitcoin.




###  El uso de pseudónimo 


 Mucha atención mediática es dada al supuesto anonimato que la moneda digital permite a sus usuarios. Esa idea, no obstante, deriva de un erróneo entendimiento del bitcoin. Porque las transacciones online hasta hoy necesitaron de un tercer intermediario, ellas no fueron anónimas. El PayPal, por ejemplo, tiene un registro de todas las veces que Maria envió dinero a Juan. Y porque las cuentas en el PayPal de Maria y de Juan son amarradas a sus cuentas bancarias, sus identidades son probablemente sabidas. En contraste, si Maria entregó a Juan 100 reales en dinero, no hay intermediario ni registro de la transacción. Y si Maria y Juan no conocen un a otro, podemos decir que la transacción es completamente anónima. 

 El bitcoin se encaja en algún punto entre eses dos extremos. Por un lado, bitcoins son como dinero vivo, en el sentido de que, cuando Maria envía bitcoins a Juan, ella no más los posee, y el sí, y no hay ningún tercer intermediario entre ellos que conoce sus respectivas identidades. Por otro lado, y diferentemente del dinero vivo, el hecho de que la transacción ocurrió entre dos claves publicas, en tal día y hora, con cierta cuantidad, además de otras informaciones, es registrado en el blockchain. En realidad, cualquier y toda transacción ya efectuada en la historia de la economía bitcoin puede ser vista en el blockchain.

  Mientras las claves publicas de todas las transacciones – también conocidas como “dirección bitcoin”6- son registradas en el blockchain, tales claves no son vinculadas a identidad de nadie. Pero, si la identidad de una persona estuviera asociada a una clave publica, podríamos escudriñar las transacciones en el blockchain y fácilmente ver todas las transacciones asociadas a esa clave. De esta forma,  aunque bitcoin sea bastante semejante al dinero vivo, en que las partes pueden hacer transacciones sin revelar sus identidades a un tercer o entre sí, y también distinto del dinero vivo, pues todas las transacciones de y para una dirección bitcoin cualquier pueden ser rastreada. En este sentido, bitcoin no garante el anonimato, pero permite el uso del pseudónimo.

 Vincular una identidad del mundo real a una dirección bitcoin no es tan difícil cuanto se pueda imaginar. Para empezar, la identidad de una persona ( o pelo menos información de identificación, como una dirección IP) es frecuentemente registrada cuando alguien realiza una transacción de bitcoin en una página web o cambia dólares por bitcoins en una casa de cambio de bitcoins. Para aumentar las chances de mantener el pseudónimo, sería necesario emplear softwares de anonimato como Tor, y tener el cuidado de nunca hacer transacción con una dirección bitcoin en el cual podría ser rastreada la identidad del usuario.

 Por fin, es también posible recoger identidades simplemente mirando el blockchain. Un estudio descubrió que técnicas de agrupación basadas en comportamiento podrían revelar las identidades de 40% de los usuarios de bitcoin en un experimento simulado. Una pesquisa más antigua de las propiedades estadísticas del grafico de transacciones del bitcoin mostró como una analice pasiva de la red con las herramientas apropiadas puede revelar la actividad financiera y las identidades de los usuarios de Bitcoin.

 Ya una analice reciente de las propiedades estadísticas del grafico de transacciones de bitcoins recogió resultados similares al de un banco de datos más amplios. Una otra analice de grafico de transacciones de bitcoins reiteró que observadores usando “fusión de entidad”7 pueden notar patrones estructurales en el comportamiento del usuario, enfatizando que ese “es un de los desafíos más importantes al anonimato del Bitcoin”.8 No obstante, usuarios de bitcoin desfrutan de un nivel mucho mayor de privacidad de que los usuarios de servicios tradicionales de transferencia digital, los cuales necesitan fornecer información personal detallada a terceros intermediarios que facilitan el cambio financiero.


6 Bitcoin wiki “Address”. Disponible en: http://en.bitcoins.it/wiki/Address Acceso en: 30 mar. 2013
7 Fusión de entidad es el proceso de observar dos o más claves publicas usadas como un input a una transacción al mismo tiempo. Así, mismo que un usuario tenga diversas claves publicas distintas, una observador puede gradualmente vincularlas y remover el ostensivo anonimato esperado de múltiplas claves publicas
8 OBER, KATZNBEISSER y HAMACHER. Structure and Anonimity of  the Bitcoin Transaction Graph. Future Intent 5, no.2, 2013. Disponible en: http://www.mdpi.com/1999-5903/5/2/237 Acceso en: 10 dec. 2013.




 Aunque Bitcoin sea frecuentemente referido como una moneda “anónima”, en realidad, es bastante difícil permanecer anónimo en la red Bitcoin. Pseudónimos ligados a transacciones protocoladas en el registro publico pueden ser identificados años después de la realización de un cambio. Una vez que intermediarios de bitcoin9 estén completamente en día con las regulaciones requeridas a intermediarios financiero 
tradicionales, el anonimato será menos garantido, porque de los intermediarios de Bitcoin será exigido colectar datos personales de sus clientes.




##2. Beneficios del Bitcoin

 La primera pregunta que muchas personas hacen cuando aprenden sobre Bitcoin es: ¿por qué yo usaría bitcoins cuando puedo usar reales (o dólares)? Bitcoin aun es una moneda nueva y flotante que no es acepta por muchos comerciantes, volviendo sus usos cuasi experimentales. Para entender mejor el bitcoin, ayuda si pensamos que él no es necesariamente un sustituto a las monedas tradicionales, pero sí un nuevo sistema de pagamentos.


### Menores costos de transacción 
 Porque no hay un tercer intermediario, las transacciones de Bitcoin son substancialmente más baratas y rápidas que las hechas por redes de pagamentos tradicionales. Y porque las transacciones son más baratas, el Bitcoin hace con que micropago y sus innovaciones sean posibles. Adicionalmente, el Bitcoin es una gran promesa de una forma de reducir los costos de transacción a los pequeños comerciantes y remesas de dineros globales, aliviar  la pobreza global por el facilitado acceso al capital, proteger individuos contra controles de capitales y censura, garantir privacidad financiera a grupos oprimidos y estimular la innovación (dentro y arriba del protocolo Bitcoin). Por otro lado, la naturaleza descentralizada del bitcoin también presenta oportunidades al crimen. El desafío, entonces, es desarrollar procesos que reduzcan las oportunidades para criminalidad mientras se mantienen los beneficios que Bitcoin ofrece.

 En primer lugar, Bitcoin es atractivo a pequeñas empresas de márgenes apretadas que procuran formas de reducir sus costos de transacción en la conducción de sus negocios. 

9 Como ejemplos de intermediarios de Bitcoin, tenemos las casas de cambio que facilitan la compra y venta entre monedas fiduciarias y bitcoins. En Brasil, tales casas ya solicitan una cuantidad de informaciones personales que puede desagradar a muchos usuarios.
Tarjetas de crédito expandieron de forma considerable la facilidad de hacer transacciones, pero su uso viene acompañado de pesados costos a los comerciantes. Negocios que desean ofrecer a sus clientes la opción de pagamento con tarjetas de crédito necesitan, primero, contactar una cuenta con las empresas de tarjetas. Dependiendo de los términos de acuerdo con cada empresa, los comerciantes tienen que pagar una variedad de tasas de autorización, tasas de transacción, tasas de extracto, etc. Esas tasas rápidamente se acumulan y aumentan significativamente el costo de los negocios. Mientras tanto, si un comerciante rechaza aceptar pagamentos con tarjetas de crédito, puede perder un número considerable de sus ventas a clientes que prefieren el uso de tal comodidad. 

 Como el Bitcoin facilita transacción directas sin un tercer, ele remueve cobranzas costosas que acompañan las transacciones con tarjeta de crédito. El Founders Fund, un fundo de venture capital  encabezado por Peter Thiel, de PayPal y Facebook, recientemente invirtió 3 millones de dólares en la compañía de procesamiento de pagamentos BitPay, a causa de la habilidad del servicio en reducir los costos en el comercio online internacional. De hecho, pequeños negocios ya empezaron a aceptar bitcoins como una forma de evitar los costos de operar con empresas de tarjeta de crédito. Otros adoptaron la moneda por su velocidad y eficiencia en facilitar las transacciones. El Bitcoin probablemente continuará a reducir los costos de transacciones de las empresas que lo aceptan a medida que más y más personas lo adopten.

 Aceptar pagamentos con tarjetas de crédito también sujeta a las empresas al riesgo de fraude de extorno de pagamentos (charge-black fraud). Hace mucho tiempo que comerciantes han sido infestados por extornos fraudulentos, o reversiones de pagamentos iniciados por clientes, basados en el falso pretexto de que el producto no fue entregue10. Comerciantes, por tanto, pueden perder el pagamento por el ítem vendido, además del propio ítem, y aún tendrán de pagar una tasa por el extorno. Como un sistema de pagamentos no reversible, el Bitcoin elimina la “fraude amigable” acarreada por el malo uso de extornos de consumidores. A los pequeños negocios, eso puede ser fundamental.

 Les gusta a los consumidores los extornos, no obstante, porque el sistema los protege de errores de comerciantes, inescrupulosos o no. Consumidores pueden también gozar de los otros beneficios que las tarjetas de crédito ofrecen. Y muchos consumidores y comerciantes probablemente prefirieron atenerse a los servicios tradicionales de tarjeta de crédito, mismo con la disponibilidad de pagamentos por la red Bitcoin. Aún así, la ampliación del abanico de opciones de pagamento beneficiaría a todos los gustos. 

 Aquellos que quieren la protección e las regalías del uso de la tarjeta de crédito pueden 


10 MALTBY, Emily. Chargebacks Create Business Headaches. Wall Street Journal, 10 feb. 2011. Disponible en: http://online.wsj.com/article/SB10001424052748704698004
continuar a operar así, mismo que eso signifique pagar un poco más. Aquellos más sensibles al precio o a privacidad pueden usar bitcoins. No tener que pagar tasas a las compañías de tarjetas de crédito significa que los comerciantes pueden repasar las economías a los precios finales al consumidor. Exactamente en este modelo de negocios trabaja la tienda Bitcoin Store, que vende millares de electrónicos con grandes descuentos, aceptando como pagamento solamente bitcoins11.

 Como un accesible sistema de transferencia de fundos, Bitcoin también es una gran promesa al futuro de las remesas de dinero de bajo costo. En 2012, inmigrantes de países desarrollados enviaron al menos 401 billones de dólares en remesas a sus parientes viviendo en países en desarrollo12. Se estima que la cuantidad de remesas aumente para 515 billones de dólares hacia 201513. La mayor parte de estas remesas es enviada usando servicios tradicionales como Western Union o MoneyGram, que cobran tasas pesadas , además de demorar diversos días laborables para concluir la transferencia de los fundos. En el primer trimestre de 2013, la tasa media por el servicio giró en torno a 9%14. En contraste, las tasas de transacciones en la red Bitcoin tienden a ser menos de 0,0005 BTC15, o 1% de la transacción. Esa oportunidad emprendedora de mejorar las transferencias del dinero tiene atraído grandes nombres del universo de inversionistas de venture capital. Hasta mismo el MoneyGram y el Western Union están analizando si integran el bitcoin a su modelo de negocios. El bitcoin permite remesas baratas y instantáneas, y la reducción de costo de estas remesas a los consumidores puede ser considerable.

### Potencial arma contra la pobreza y la opresión

 Bitcoin también tiene el potencial de mejorar la cualidad de vida de los más pobres en el mundo. Aumentar el acceso a servicios financieros básicos es una técnica antipobreza promisora16. De acuerdo con estimativas, 64% de las personas viviendo en países en desarrollo tienen parco acceso a eses servicios, quizás porque sea bastante costoso a instituciones financieras tradicionales servir a las áreas pobres y rurales17. 


11  El mismo Samsung Galaxy Note que se vende por US$779 en Amazon más publicación es vendido en la Bitcoin Store por meros US$480,25. De esta forma, Bitcoin ofrece más opiciones de bajo costo a consumidores y pequeñas empresas sin remover la opción de uso de tarjeta de crédito de aquellos que lo prefieren. BUTERIN, Vitalik. Bitcoin Store Opens All Your e Electronics  Cheaper with Bitcoins. Bitcoin Magazine, 5 nov. 2012. Disponible en: http://bitcoinmagazine.com/bitcoin-store-opens-all-your-electronics-cheaper-with-bitcoins/ Acceso en: 10 dec. 2013.
12  WorlD Bank Payment Systems Development Group. Remittance Prices Worldwide: An Analysis of Trends in the Average Total Cost of Migrant Remittance Services, Washington, DC, World Bank, 2013. Disponible en: http://remittanceprices.worldbank.org/~/media/FPDKM/Remittances/Documents/RemittancePriceWorldwide-Analysis-Mar2013.pdf>. Acceso en: 11 dec. 2013.
13  Ibid.
14  Ibid.
15  Bitcoin wiki “Transaction fees”. Disponible en: <http://en.bitcoin.it/wiki/Transaction_fees>. Acceso en: 11 dec. 2013. PAUL, Andrew. Is Bitcoin the Next Generation of Online Payments? Yahoo! Small Business Advisor, 24 may. 2013. Disponible en: http://smallbusiness.yahoo.com/advisor/bitcoin-next-generation-payments-213922448--finance.html Acceso en: 11 dec. 2013.
16  YUNUS, Muhammad. Banker to the Poor: Micro-lending and the Battle against World Poverty. New York: Public Affairs, 2003.
17  PINAR ARDIC, HEIMANN y MYLENKO. Access to Financial Services and the Financial Inclusion Agenda around the World. Policy Research Working Paper, World Bank Financial and Private Sector Development Consultative Group to Assist the Poor,2011. Disponible en: http://openknowledge.worldbank.org/bitstream/handle/10986/3310/WPS5537.pdf Acceso en: 12 dec. 2013
 Por causa de los obstáculos al desarrollo de servicios bancarios tradicionales en áreas pobres, personas en países en desarrollo tienen recurrido a los servicios bancarios vía red de telefonía móvil para hacer frente a las necesidades financieras. El sistema cerrado de pagamentos por celular M-Pesa ha sido particularmente exitoso en países como Kenia, Tanzania y Afganistán18. Emprendedores ya están se moviendo hacia a ese modelo; el servicio de monedero de Bitcoin Kipochi recientemente desarrolló un producto que permite al usuario del M-Pesa cambiar bitcoins19. Servicios bancarios por celular en países en desarrollo pueden ser ampliados por la adopción del Bitcoin. Como un sistema abierto de pagamentos, el Bitcoin fornece a las personas en eses locales acceso barato a servicios financieros, en una escala global.

 El bitcoin puede también propiciar alivio a las personas viviendo en naciones con controles de capitales bastante estrictos. El número total de bitcoins que pueden ser minados es limitado y no puede ser manipulado. No hay autoridad central que pueda reverter transacciones y impedir el cambio de bitcoins entre países. El bitcoin, de esta forma, proporciona una válvula de escape para personas que anhelan una alternativa a la moneda depreciada de su país o a mercados de capitales estrangulados. Ya hay casos de personas recorriendo al Bitcoin para se evadir de los efectos dañosos de los controles de capitales y de la mala gestión de bancos centrales. Algunos argentinos, por ejemplo, adoptaron el Bitcoin en respuesta al doble fardo del país, tasas de inflaciones de más de 25% al año y rigorosos controles de capitales20. La demanda por bitcoins es tan grande en Argentina que una popular casa de cambio está planeando abrir un escritorio en su país21. El uso de bitcoins en aquel país continua creciendo por causa de la pésima injerencia estatal en el ámbito monetario.

 Individuos en situaciones de opresión o emergencia también pueden beneficiarse de la privacidad financiera que el bitcoin proporciona. Hay muchas razones legitimas por las cuales personas buscan privacidad en sus transacciones financieras. Esposas huyendo de parejas abusivas necesitan de alguna forma de discretamente gastar su dinero sin ser rastreadas. Personas procurando servicios de salud contrariados desean privacidad de familiares, empleadores y otros que pueden juzgar sus decisiones. Experiencias recientes con gobiernos despóticos sugieren que ciudadanos oprimidos se beneficiaron altamente de la posibilidad de realizar transacciones privadas, libres de las garras de tiranos. El Bitcoin ofrece algo de privacidad como la que tiene sido tradicionalmente permitida por el uso de dinero vivo – con la conveniencia adicional de transferencia digital.

18   FONG, Jeff. How Bitcoin Could Help the World’s Poorest People. PolicyMic,
mai. 2013. Disponible en: http://www,policymic.com/articles/41561/bitcoin-price-2013-how-bitcoin-could-help-the-world-s-poorest-people. Acceso en: 12 dec. 2013.
19  SPAVEN, Emily. Kipochi launches M-Pesa Integrated Bitcoin Wallet In Africa. CoinDesk, 19 jul. 2013. Disponible en: http://www.coindesk.com/kipochi-launches-m-pesa-integrated-bitcoin-wallet-in-africa/ . Acceso en 12 dec. 2013.
20  MATONIS, Jon.Bitcoin’s Promise in Argentina. Forbes, 27 abr. 2013. Disponible en: http://www.forbes.com/sites/jonmatonis/2013/04/27/bitcoins-promise-in-argentina/. Acceso en: 12 dec. 2013.
21  RUSSO, Camila. Bitcoin Dreams Endure to Savers Crushed by CPI: Argentina
Credit. Bloomberg, 16 abr. 2013. Disponible en: http://www.bloomberg.com/news/2013-04-16/bitcoin-dreams-endure-to-savers-crushed=by-cpi-argentina-credit-html. Acceso en: 12 dec. 2013.

### Estimulo a innovación financiera

 
 Una de las aplicaciones más promisoras del Bitcoin es como una plataforma a innovación financiera. El protocolo de Bitcoin contiene el modelo de referencia digital para una cuantidad de servicios financieros y legales útiles que programadores pueden desarrollar fácilmente. Como bitcoins son, en su cerne, simplemente paquete de datos, ellos pueden ser usados para transferir no solamente monedas, pero también acciones de empresas, apuestas y informaciones delicadas22. Algunos de los atributos que están embutidos en el protocolo del Bitcoin incluyen micropago, mediaciones de litigios, contactos de garantía y propiedad inteligente23. Eses atributos permitirían el fácil desarrollo de servicios de traducciones vía internet, procesamiento instantáneo de transacciones pequeñas (como mediación automática de acceso Wi-Fi) y servicios de crowdfunding24.

 Adicionalmente, programadores pueden desarrollar protocolos alternativos encima del protocolo del Bitcoin de la misma forma que la web y el correo electrónico operan en el protocolo de la internet TCP/IP. Un programador ya propuso una nueva camada de protocolo para agregar al protocolo del bitcoin y así perfeccionar la estabilidad y seguridad de la red25. Otro creó un servicio de escribano digital para almacenar anónimamente y con seguridad una “prueba de existencia” para documentos privados, encima del protocolo del Bitcoin26. Otros, aún, adoptaron el modelo Bitcoin como forma de cifrar comunicaciones de correo electrónico27. Un grupo de desarrolladores esbozó un protocolo aditivo que mejorará la privacidad de la red28. El Bitcoin es, por tanto, la fundación sobre la cual otras camadas de funcionalidad pueden ser construidas. El


22   BRITO, Jerry. The Top 3 Things I Learned at the Bitcoin Conference. Reasons,
20 may. 2013. Disponible en: http://reason.com/archives/2013/05/20the-top-3-things-i-learned-at-the-bitcoi. Acceso en: 12 dec. 2013.
23   HEARN, Mike.Bitcoin 2012 London: Mike Hearn. YouTube video, 28:19,
publicado por “QueuePolitely,” 27 set. 2012. Disponible en: http://www.youtube.com/watch?v=mD4L7xDNCmA. Acceso en: 13 dec. 2013. Propiedad inteligente (Smart Property) es un concepto para controlar propiedad de un ítem por medio de acuerdos hechos en el blockchain del Bitcoin. La propiedad inteligente permite que las personas intercambien propiedades de un producto o servicio una vez que una condición es atingida usando la criptografía. Aunque la propiedad inteligente sea aún teórica, los mecanismos básicos ya están incorporados a los protocolos del Bitcoin. Ver Bitcoin wiki “Smart Property”. Disponible en http://en.bitcoin.it/wiki/Smart_Property. Acceso en: 13 dec. 2013.
24   El financiamiento colectivo (crowdfunding) consiste en la obtención de capital para iniciativas de interesse colectivo por medio de la agregación de múltiplas fuentes de financiamiento, en general, personas físicas interesadas en la iniciativa. El término es mucha veces usado para describir específicamente acciones en la internet con el objetivo de arrecadar dinero para artistas, periodismo ciudadano, pequeños negocios y startups, campañas políticas, iniciativas de software libre, filantropía y ayuda a regiones atingidas por desastres, entre otras.
25   WILLETT,J.R. The Second Bitcoin Whitepaper, White paper, 2013. Disponible en: https://sites.google.com/site/2ndbtcwpaper/2ndBitcoinWhitepaper.pdf. Acceso en: 13 dec. 2013.
26  KIRK, Jeremy. Could the Bitcoin Network Be Used as an Ultrasecure NotaryService? Computerworld, 23 may. 2013. Disponible en: http://www.computerworld.com/s/article/9239513/Could_the_Bitcoin_network_be_used_as_an_ultrasecure_notary_service_. Acceso en: 13 dec. 2013.
27 WARREN, Jonathan. Bitmessage: A Peer-to-Peer Message Authentication and Delivery System, White paper, 27 nov. 2012. Disponible en: http://bitmessage.org?bitmessage.pdf. Acceso en: 13 dec. 2013.
28   MIERS, Ian et al. Zerocoin: Anonymous Distributed E-Cash from Bitcoin, working page, the Johns Hopkins University Department of Computer Science,
Baltimore, MD, 203, Disponible en: http://spar.isi.jhu.edu/~mgreen/ZerocoinOakland.pdf. Acceso en: 13 dec. 2013.



proyecto Bticoin puede ser más bien imaginado como un proceso de experimentación financiera y comunicativa. Los elaboradores de políticas publicas deben tener cuidado para que sus directivas no supriman las innovaciones promisoras en desarrollo dentro y  
sobre el novato protocolo.



## 3. Desafíos del Bitcoin

 A pesar de los beneficios que él presenta, el Bitcoin tiene algunas desventajas que usuarios en potencial deben tomar en consideración. Hubo significativa volatilidad en el precio a lo largo de su existencia. Nuevos usuarios corren el riesgo de no proteger debidamente sus monederos o de, aun, accidentalmente borrar sus bitcoins si no tener cautela. Adicionalmente, hay preocupaciones sobre si hackers pueden de alguna forma comprometer la economía Bitcoin.


 Volatilidad

 El bitcoin fue expuesto a por lo menos cinco ajustes de precio significativos desde 201129. Eses ajustes se asemejan a burbujas especulativas tradicionales; coberturas de la imprenta optimistas en exceso provocan ondas de inversionistas novatos a presionar hacia arriba el precio de bitcoin30. La exuberancia, entonces, atinge un punto de inflexión, y el precio finalmente despeña. Nuevos entrantes ávidos por participar corren el riesgo de sobrevalorar la moneda y perder dinero en una caída abrupta. El valor flotante del bitcoin hace con que muchos observadores permanezcan céticos cuanto al futuro de la moneda.

 ¿Será que esa volatilidad predice el fin del bitcoin? Algunos analistas piensan que sí31. Otros sugieren que esas flotaciones acaban por realizar testes de estrés a la moneda y pueden, por fin, disminuir en frecuencia a medida que mecanismos para contrabalancear la volatilidad se desarrollan32. Si bitcoins son usados solamente como reserva de valor o unidad de cuenta, la volatilidad podría de hecho amenazar su futuro. 

29  LEE, Tomothy B. An Illustrated History of Bitcoins Crashes, Forbes, 11 abr. 2013. Disponible en: http://www.forbers.com/sites/timothylee/2013/04/11/an-illustrated-history-of-bitcoins-crashes/. Acceso en: 13 dec. 2013.
30  SALMON, Felix. The Bitcoin Bubble and the Future of Currency, Medium, 2 abr. 2013. Disponible en: http://medium.com/money-banking/2b5ef79482cb. Acceso en: 13 dec. 2013.
31  FARREL, Maureen. Strategist Predicts End of Bitcoins, CNNMoney, 14 may. 2013. Disponible en: http://money.cnn.com/2013/05/14/investing/bremmer-bitcoin/index.html. Acceso en: 13 dec. 2013.
32   GURRI, Adam. Bitcoins, Free Banking, and the Optional Cause. Ümlaut, 6 may. 2013. Disponible en: http://theumalaut.com/2013/05/06/bitoicns-free-banking-and-the-optional-clause/. Acceso en: 13 dec. 2013.

 No hace sentido administrar las finanzas de un negocio o guardar las economías en bitcoins si el precio oscila desenfrenada y imprevisiblemente. Cuando el Bitcoin es 
empleado como un medio de cambio, mientras tanto, la volatilidad no es un problema tan grande. Comerciantes pueden determinar el valor de sus productos en términos de moneda tradicional y aceptar el equivalente en bitcoins. Clientes que adquieren bitcoins para realizar solamente una compra no se importan con el cambio mañana; ellos solamente se preocupan con que el Bitoicn reduzca costos de transacciones en el presente. La utilidad del Bitcoin como medio de cambio podría explicar porque la moneda se ha vuelto popular entre comerciantes, a pesar de la volatilidad de su precio33. Es posible que el valor de bitcoins venga a presentar una menor volatilidad mientras que más personas se familiarizan con su tecnología y desarrollen expectativas realistas acerca de su futuro.



###  Violación de seguridad


 Como una moneda digital, el Bitcoin presenta algunos desafíos de seguridad específicos34. Si las personas no son cuidadosas, ellas pueden inadvertidamente borrar o perder sus bitcoins. Una vez que el archivo digital esté perdido, el dinero está perdido, de la misma forma con dinero vivo en papel. Si las personas no protegen sus direcciones bitcoin, ellas pueden estar más sujetas al robo. Los monederos de bitcoin ahora pueden ser protegidas por criptografía, pero los usuarios deben seleccionar la activación de la criptografía. Si un usuario no cifra a su monedero, los bitcoins pueden ser robados por malware35. Las casas de cambio de bitcoin también enfrentan complicaciones de seguridad; hackers hurtaron 24 mil BTC (entonces valorados en 250 mil dolares) de una casa de cambio llamada Bitfloor en 201236, y hubo una serie de ataques DDoS (distributed denial-of-service) contra la más popular casa de cambio, Mt.Gox, en 201337. ( La Bitfloor finalmente repagó los fundos robados a los clientes, y la Mt.Gox se recuperó de tales ataques). Obviamente, muchos de los riesgos de seguridad afrontados por el Bitcoin son similares a aquellos con los cuales monedas tradicionales también se 



33   Hoy servicios como ese aceptan el riesgo inherente a la volatilidad y aún así mantienen bajas tasas. Si ese modelo será sustentable en largo plazo, es algo inconcluyente.
34   La mayoría de los desafíos de seguridad está relacionada a los servicios de monederos y a las casas de cambio. El protocolo en sí ha probado considerablemente resistente a hackers y riesgos de seguridad. El renombrado investigador de seguridad Dan Kaminsky trató. Pero fracasó, hackear el protocolo Bitcoinen 2011. KAMINSKY, Dan. I Tried Hacking Bitcoin and I Failed, Business Insider, 12 abr. 2013. Disponible en: http://www.businessinsider.com/dan-kaminsky-highlights-flaws-bitcoins-2013-4. Acceso en: 13 dec. 2013.
35   El término malware es proveniente del ingles malicious software; es un software destinado a se infiltrar en un sistema de computadora ajeno de forma ilícita, con el intuito de causar algún daño, alteraciones o robo de informaciones (confidenciales o no).
36   COLDEWEY, Devin. $250,000 Worth of Bitcoins Stolen in Net Heist, NBC News, 5 set. 2012. Disponible en: http;//www.nbcnews.com/technology/250-000-worth-bitcoins-stolen-net-heist-980871. Acceso en: 14 dec. 2013.
37   KELLY, Meghan. Fool Me Once: Bitcoin Exchange Mt.Gox Falls after Third
DDoS Attack This Month, VentureBeat, 21 abr. 2013. Disponible en: http://venturebeat.com/2013/04/21/mt-gox-ddos/. Acceso en: 14 dec 2013.

 
enfrentan. Dinero de papel pueden ser destruidas o perdidas, información financiera 
personal puede ser robada y usada por criminosos y bancos pueden ser asaltados o blancos de ataques DDoS. Los Usuarios de Bitcoin deberían aprender sobre y como prepararse contra riesgos de seguridad, de la misma forma que lo hacen con otras actividades financieras.



### Uso para fines criminosos


 
 También hay razones para las preocupaciones de los políticos cuanto a algunas de las aplicaciones no intencionadas del Bitcoin. Porque el bitcoin permite el uso de pseudónimos, políticos y periodistas tienen cuestionado si criminosos pueden usarlo para lavado de dinero o para aceptar pagamentos de venda de productos y servicios ilícitos. De hecho, y como el dinero vivo, él puede ser usado tanto para el bien cuanto para el mal.  Un ejemplo notorio es el caso del sitio web de mercado negro en deep web38  conocido como Silk Road39. Ese sitio web se aprovechaba de la red para anonimato Tor y de la naturaleza de usar pseudónimo en el Bitcoin para fornecer un vasto mercado digital en que se podría encomendar drogas por correo, además de otros productos lícitos y ilícitos. Aunque los administradores del Silk Road no permitieran el cambio de ningún producto que resultara de fraude o daño, como tarjetas de crédito robados o fotos de exploración del menores, era permitido a los comerciantes vender productos ilegales, como documentos de identidad falsos y droga ilícitas. El hecho de usarse pseudónimo en el Bitcoin permitia que compradores adquirieran profuctos ilegales online, de la misma forma que el dinero ha sido tradicionalmente usado para facilitar compras ilícitas personalmente. Un estudio estimó que el total de transacciones mensales en el Silk Road alcance aproximadamente 1,2 millones de dolares40. Pero el mercado de Bitcoins acumuló 770 millones de dólares en transacciones durante junio de 2013; vendas en el Silk Road, por tanto, constituían una cuasi insignificante parcela del total de la economía Bitcoin41.

38   Wikipedia “Deep Web”. Disponible en http://e.wikipedia.org/wiki/Deep_Web. Acceso en: 30 jul. 2013.
39   El sitio web Silk Road fue cerrado por las autoridades americanas al final de 2013, pero la asociación del Bitcoin al uso para fines criminosos es algo recurrente. Eso nos remete a un punto fundamental: el Bitcoin es una tecnología y, por tanto, no es buena ni mala. Es neutra. El crimen está en la acción del infractor, jamás en la tecnología empleada para tal. El Bitcoin, o cualquier otra forma de dinero, puede ser usado para el bien o para el mal. Además de eso, la compra y venta de drogas, dependiendo del país, ya es algo normal y perfectamente licito. Eso quiere decir que la prohibición de las drogas es una cuestión política que independe por completo del Bitcoin. Además, la experiencia sugiere que la guerra a las drogas es mucho más nefasta que cualquier consecuencia derivada de su uso por ciudadanos honestos.
40   CHRISTIN, Nicolas. Traveling the Silk Road: A Measurament Analysis of a Large Anonymous Online Marketplace, Carnegie Mellon CyLab Technical Reports: CMU-CyLab-12-018, 30 jul. 2012 (actualizado en 28 nov. 2012). Disponible en: http://www.cylab.cmu.edu/files/pdfs/tech_reports/CMUCyLab12018.pdf. Acceso en: 14 dec. 2013.
41   BRITO, Jerry, National Review Gets Bitcoin Very Wrong, Technology Liberation Front, 20 jun. 2013. Disponible en: http://techliberation.com/2013/06/20/national-review-gets-bitcoin-very-wrong/. Acceso en: 14 dec. 2013.
 La asociación del Silk Road con el Bticoin manchó su reputación. En la secuencia de la publicación de un artigo sobre el Silk Road en 2011, los senadores norte-americanos Charles Shumer y Joe Manchin enviaron una carta al promotor-general Eric Holder y al administrador del Drug Enforcement Administration, Michelle Leonhart, pidiendo por una caza al Silk Road, al software de anonimato Tor y al Bitcoin42.

 Otra preocupación es que el Bitcoin sea usado para lavado de dinero para el financiamiento del terrorismo y trafico de productos ilegales. A pesar de esas inquietudes ser, en este momento, más teórica que empíricas, el Bitcoin podría de hecho ser una opción a aquellos que desean mover dinero sucio discretamente. Preocupaciones con el potencial del Bitcoin ser usado para lavado de dinero fueron atizadas después del Liberty Reserve, un servicio privado y centralizado de moneda digital con sed en la Costa Rica, haber sido encerrado por las autoridades a causa de alegaciones de lavado de dinero43.

 Aunque el Liberty Reserve y el Bitcoin parezcan similares porque ambos ofrecen monedas digitales, hay diferencias importante entre los dos. El Liberty Reserve era un servicio de divisas centralizado, creado y perteneciente a una empresa privada, supuestamente con el expreso propósito de facilitar el lavado de dinero; el Bitcoin no. Las transacciones dentro de la economía del Libert Reserve no eran transparentes. El Bitcoin, por otro lado, es una moneda descentralizada abierta que fornece un registro publico de todas las transacciones. Lavadores de dinero pueden tratar de proteger sus direcciones de Bitcoin y sus identidades, pero sus registros de transacciones serán siempre públicos y accesibles a cualquier momento por las autoridades. Lavar dinero por medio de Bitcoin, entonces, puede ser visto como un destajo mucho más arriscado  que usar un sistema centralizado como el Libety Reserve. Además, diversas casas de cambio de bitcoins han tomado las medidas necesarias para estar al día con las regulaciones y exigencias de las autoridades en que corresponde al combate al lavado de dinero44. La combinación de un sistema de registro publico (o libro mayor del Bitcoin, o el blockchain) con la cooperación de las casas de cambio en la colecta de informaciones de los usuarios hará del bitcoin una vía relativamente menos atractiva a los lavadores de dinero.

 También es importante notar que muchas de las potenciales desventajas del Bitcoin son las mismas afrontadas por el tradicional dinero vivo; este ha sido históricamente el vehículo escogido por traficantes y lavadores de dinero, pero políticos jamás seriamente considerarían proscribir el dinero vivo. A medida que los reguladores comiencen a contemplar el Bitcoin, ellos deberían ser cautelosos con los peligros de la regulación 


42  WOLF, Brett. Senators Seek Crackdown on ‘Bitcoin’ Currency, Reuters, 8 jun. 2011. Disponible en: http://www.reuters.com/article/2011/06/08/us-financial-bitcoins-idUSTRE7573T320110608. Acceso en: 14 dec. 2013.
43   Liberty Reserve Digital Money Service Forced Online, BBC News – Technology , 27 may. 2013. Disponible en: http://bbc.co.uk/news/technology-22680297. Acceso en: 14 dec. 2013.
44  SPARSHOTT, Jeffrey. Bitcoin Exchange Makes Apparent Move to Play bu U.S. Money-Laundering Rules, Wall Street Journal, 28 Jun. 2013. Disponible en: http://online.wsj.com/article/SB1000142412788732873904578574000957464468.html. Acceso en: 14 dec. 2013.

excesiva. En el peor de los casos, los reguladores podrían impedir que los negocios legítimos se beneficien de la red Bitcoin sin imponer ningún obstáculo al uso de Bitcoin
por traficantes o lavadores de dinero. Si las casas de cambio son sobrecargadas por la regulación y encierran sus actividades, por ejemplo, traficantes y afines aún así podrían poner dinero en la red, pagando una persona con dinero vivo para que esta les transfiera sus bitcoins. En este caso, transacciones benéficas son imposibilitadas por regulación excesiva, mientras las actividades-blanco continúan a ocurrir.





## 4. Regulación y Legislación
 

 Las leyes y regulaciones actuales no prevén una tecnología como el Bitcoin, lo que resulta en algunas zonas legales cenicientas. Eso ocurre porque el bitcoin no se encaja en definiciones reglamentares existentes de la moneda u otros instrumentos financieros o instituciones, dificultando saber cuales leyes se aplican a él y de cual manera.

 El bitcoin tiene las propiedades de un sistema electrónico de pagamentos, una moneda y una mercancía, entre otras. De esta forma, estará sin duda sujeto al escrutinio de diversos reguladores. Varios países están actualmente debatiendo el Bitcoin en nivel gubernamental. Algunos ya emitieron pareceres o pronunciamientos  oficiales, estableciendo directrices, orientaciones, etc. Algunos con una postura neutra, otros de manera más cautelosa.

 Aunque no sea el foco de este libro averiguar cual es el tratamiento legal adecuado, es oportuno afirmar que las cuestiones legales por supuesto afectarán la manera como el bitcoin se desarrolla alrededor del mundo. En países desarrollados, las incertezas sobre como el bitcoin será regulado poco a poco se disuelven.

 Pero en pleno año de 2014, aún hay cuestiones a ser consideradas por las autoridades. En Brasil, nada en especifico concerniente al Bitcoin fue emitido por los órganos reguladores45. Por ser un mercado independiente y de rápido crecimiento, podemos esperar por novedades en el ámbito legal próximamente.






45   La excepción fue un caso, en julio de 2012, interpelado por la Comisión de Valores Mobiliarios (CVM), al impedir y multar un ciudadano no registrado en la autarquía de ofertar públicamente un vehículo de inversiones en bitcoins. Mientras tanto, no hubo cualquier juicio de valor referente al Bitcoin en sí, solo el hecho que constituía una oferta de inversión irregular en territorio nacional. Disponible en: http://www.cvm.gov.br/port/infos/comunicado-deliberacao%20680.asp. 
