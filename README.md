# exchange-Bitcash
exchange Bitcash
Un intercambio de criptomonedas es una plataforma que permite a los usuarios comprar/vender una variedad de tokens. Es como una bolsa de valores, pero en lugar de acciones, compras o vendes criptomonedas. En este artículo, le mostraremos cómo crear un intercambio de criptomonedas de este tipo desde cero.

Tipos
Cryptocurrency exchange type
El primer paso para iniciar su propio exchange de criptomonedas es elegir el tipo de plataforma comercial que planea construir. Esto es importante, ya que el mecanismo para el exchange de criptomonedas, la forma en que se almacenan, la gestión de la liquidez, la capacidad de negociar fiat y otras funciones dependen de la elección de la plataforma.

Intercambios centralizados (CEX). El tipo más común de plataformas comerciales, cuya característica principal es la presencia de un operador centralizado responsable de la seguridad, las actualizaciones y la funcionalidad del intercambio. Las principales ventajas de las plataformas centralizadas son la velocidad de las criptotransacciones y la ausencia de problemas de liquidez. El principal punto débil es la seguridad, ya que los intercambios centralizados almacenan los fondos de los usuarios en sus billeteras que, como muestra la práctica, a menudo son pirateadas.

Los intercambios centralizados tienen un conjunto diferente de características que le darán la oportunidad de ganar más. En el último artículo, puede leer más sobre modelos de negocio y un plan de negocios.

Tipos un exchange centralizados:

Negociación al contado. Los usuarios negocian sus propios fondos en la plataforma. El propietario de la plataforma criptográfica gana con la tarifa.

Comercio con margen. El usuario tiene la oportunidad de pedir prestado para operar. Como regla general, el préstamo puede ser de x2 a x5 de su depósito. El propietario de la plataforma gana con las tarifas comerciales, los intereses por el uso de un préstamo y la liquidación de los fondos de los usuarios.

Derivados. El usuario puede ingresar posiciones con un apalancamiento de hasta x100. Altos riesgos dan grandes ganancias. Pero según las estadísticas, solo el 2% de los usuarios gana con esta herramienta. Todos los demás pierden su dinero. Los fondos liquidados se transfieren a la plataforma.

Centralized exchanges (CEX)
Exchanges descentralizados (DEX). Dichas plataformas reúnen a vendedores y compradores de criptomonedas, dándoles la capacidad de intercambiar activos automáticamente sin la participación de intermediarios para validar la transacción. El papel de garante de la transacción lo asumen los contratos inteligentes de la plataforma, que operan sobre la base de software de código abierto. Este mecanismo le permite ahorrar en comisiones (no es necesario pagar intermediarios) y aumentar el nivel de seguridad (el intercambio no tiene acceso al dinero y las claves privadas de los usuarios). Antes de iniciar una plataforma criptográfica, debe saber que en dichos intercambios, la falta de moderación de terceros traslada toda la responsabilidad por los errores a los propios usuarios.

Decentralized exchanges
Intercambios punto a punto (P2P). Estos son esencialmente tableros de mensajes en línea para comprar/vender criptomonedas. Los usuarios ingresan a la plataforma, buscan una contraparte con una oferta de suministro (denominación, monto, tasa, método de transferencia) y lo contactan para acordar un intercambio. Puede comprar una cripta de esta manera utilizando dinero fiduciario, oro o bienes ordinarios, según lo acuerden las partes. En este caso, la transacción se puede realizar tanto en línea como en persona.

P2P exchanges
Intercambiadores instantáneos. Las plataformas que actúan como un punto de intercambio regular son muy fáciles de usar. Todo lo que el usuario debe hacer es abrir una orden comercial y se ejecutará instantáneamente. Esto es posible porque dichos sitios actúan como intermediarios que brindan acceso a la liquidez de muchos intercambios. La velocidad del enemigo de la tarifa es un aumento en el número de intermediarios, lo que conduce a comisiones más altas y una disminución en el nivel de seguridad.

Instant exchangers
También en el mercado, puede encontrar plataformas híbridas que combinan las propiedades de los exchanges centralizados y descentralizados. Por ejemplo, un servicio puede ser operado por operadores externos y dar a los comerciantes más control sobre sus fondos. Los pedidos y las transacciones en dichos intercambios de cifrado se cifran, fijan en el tiempo y se almacenan en la cadena de bloques, y la aprobación de pedidos se realiza fuera de la cadena de bloques en un nodo de terceros.

Por lo tanto, si desea crear un sitio web de intercambio de cifrado, debe comprender qué tipo de plataforma desea crear y cuántos ingresos puede generarle. Recomiendo prestar atención al comercio de derivados (futuros), ya que este tipo de plataforma genera los ingresos máximos.

Cryptocurrency exchange from a scratch
Características
En el siguiente paso, debe decidir qué funcionalidad debe implementarse en su exchange de cifrado. Por lo general, se divide en tales módulos:

Autorización y verificación. El camino de un usuario común para operar en el intercambio comienza con el registro por correo electrónico o cuentas en las redes sociales y Google. Pero el registro en sí mismo no suele ser suficiente para comenzar a operar. Esto requiere identificación personal - verificación. Esta verificación es necesaria para garantizar la transparencia de las transacciones y minimizar la posibilidad de fraude, y también porque es requerida por los reguladores.

Motor de negociación de la plataforma. Es responsable de la funcionalidad básica de la plataforma de negociación. Por ejemplo, un motor comercial verifica el saldo en la billetera de un usuario para asegurarse de que tenga fondos suficientes para realizar una transacción. También compara órdenes comerciales y tarifas en tiempo real, realiza transacciones, procesa información sobre precios y comisiones, crea gráficos, etc.

How To Build A Crypto Exchange From Scratch
Interfaz comercial básica del intercambio de criptomonedas Binance
Interfaz de usuario. Dependiendo de la audiencia objetivo, la interfaz de usuario puede ser simple e intuitiva o relativamente compleja debido a los muchos indicadores, señales comerciales, gráficos personalizables y otras herramientas de un comerciante experimentado. En cualquier caso, el usuario debería poder realizar órdenes de compra y venta, y ver el libro de órdenes actual, las transacciones pasadas, los saldos, las estadísticas, etc. También debería poder personalizar todo esto por sí mismo.

Panel de administración de Exchange. La construcción de una plataforma de criptomonedas incluye el desarrollo del tablero. Tiene un panel para rastrear el estado actual del intercambio (tráfico, volumen de operaciones, número de transacciones, ingresos por comisiones), comerciantes, billeteras, transacciones y configuraciones. Además, se deben implementar herramientas para verificar usuarios, cambiar y eliminar contenido, prohibir y eliminar usuarios, cambiar comisiones, administrar programas de marketing y afiliados.

También será conveniente si tiene un sistema para verificar automáticamente a los usuarios por acciones "extrañas", como en Binance: si un comerciante hace algo comprometedor (extraño, inusual, claramente no autorizado), el sistema notificará al administrador e incluso puede congelar temporalmente operaciones en la cuenta comprometida y/o deshacer la última acción.

Cartera de criptomonedas. Si está desarrollando una plataforma centralizada, entonces necesita la funcionalidad de una billetera interna. Se necesita para un acceso más rápido al dinero, lo que agiliza y facilita el proceso, así como para asegurar la liquidez del intercambio. En el caso de los intercambios de criptomonedas descentralizados y de igual a igual, generalmente no hay necesidad de crear una billetera interna.

Piense en cómo los usuarios podrán reponer sus billeteras y retirar fondos de ellas a una tarjeta o su cuenta de criptomonedas. Por ejemplo, Coinbase permite a los comerciantes conectar su cuenta bancaria y transferir dólares hacia o desde una billetera fácilmente. Esta posibilidad se puede realizar tanto con la ayuda del retiro manual de fondos como a través de algoritmos automatizados / contratos inteligentes.

How To Build A Crypto Exchange From Scratch
Libro de pedidos en el intercambio de criptomonedas Coinbase
Libro de pedidos e historial de transacciones. Este es otro elemento importante que debe implementar al lanzar su propio exchange de criptomonedas. Un libro de órdenes es una lista de órdenes abiertas para comprar o vender una criptomoneda. El intercambio lo crea automáticamente, agrupa las órdenes de compra y venta de criptoactivos en listas separadas y las compara. Cuando un pedido encuentra una oferta que coincide con sus condiciones, el sistema cambia automáticamente y cierra el pedido. Una orden cerrada desaparece del libro de órdenes y pasa al historial de transacciones.

Herramientas analíticas para comerciantes. Tenga esto en cuenta al crear el sitio web. Esta funcionalidad ayudará a atraer comerciantes experimentados a la plataforma. Las herramientas analíticas le permiten recibir información adicional sobre el estado actual del mercado, predecir su movimiento, analizar tendencias, crear y probar estrategias comerciales. Al iniciar un intercambio de cifrado, debe decidir qué indicadores desea ver en su plataforma. Las opciones más populares (obligatorias) son:

Índice de Fuerza Relativa (RSI), que muestra la fuerza de la tendencia y la probabilidad de su cambio. Funciona de manera simple: el sistema mide la magnitud de los cambios de precios recientes y muestra la tasa de cambio de precios.
Promedio móvil (MA). Otro indicador importante que ayuda a identificar tendencias al mostrar el precio promedio para un período seleccionado.
Convergencia/Divergencia de la media móvil (MACD). Se utiliza para evaluar y predecir las fluctuaciones de precios.
Notificaciones push y alertas. Le permite mantenerse en contacto con los usuarios, informándoles sobre eventos importantes en el intercambio: acciones, noticias, aplicaciones especiales, actualizaciones, etc. Además, las alertas también se pueden integrar en el comercio para mostrar notificaciones a los comerciantes sobre cambios en la tasa de seleccionados negociar pares, cambios de tendencia, notificar un indicador importante o cerrar una operación. Pero hay un punto. No olvide permitir que los usuarios elijan qué notificaciones quieren activar. Las alertas deben ser útiles y personalizables, no obligatorias y molestas.

Características de seguridad. Uno de los principales problemas del mercado de criptomonedas es la baja seguridad de los intercambios de criptomonedas. No pasa un año sin noticias de otro hack de cualquier intercambio. Los más ruidosos son: Mt. Gox - $450 millones, Bitfinex - $65 millones, Bithumb - $58 millones, Binance - $40,5 millones.

Por lo tanto, al crear su propia plataforma comercial, debe hacer todo lo posible para proteger los datos y el dinero de sus usuarios, especialmente si desea crear un intercambio de criptomonedas centralizado. Esto es lo que ayudará:

Protección contra denegación de servicio (DoS).
Protección de parámetros HTTP contra la contaminación.
Protección contra denegación de servicio distribuida (DDoS).
Protección contra la falsificación de solicitudes del lado del servidor (SSRF).
Protección contra la falsificación de solicitudes entre sitios (CSRF).
Autenticación de dos factores y HTTPS.
Autenticación biométrica.
Cifrado de datos.
Inyección SQL.
Cumplimiento de KYC, KYT, AML. Si desea trabajar en los mercados estadounidense, europeo y otros, donde los intercambios están sujetos a mayores requisitos para combatir el lavado de dinero y el financiamiento del terrorismo, entonces debe implementar lo siguiente procedimientos y estándares en su plataforma de negociación:

KYC — Conozca a su cliente. Cada usuario tendrá que pasar por una identificación personal de la persona. Por supuesto, puede recopilar documentos de usuario de forma independiente y realizar procedimientos de identificación utilizando bases de datos (PEP, listas de sanciones, etc.). Pero, ¿por qué molestarse cuando puede usar servicios listos para usar que hacen que sea fácil y rentable implementar procesos de verificación como Sumsub, Trulioo o Veriff.
KYT — Conozca su transacción. Prescribe a los intercambios criptográficos la obligación de verificar de qué fuentes se toman los tokens de los usuarios y bloquear las transacciones de fuentes sospechosas. Aquí tampoco puedes reinventar la rueda, sino usar un servicio externo, por ejemplo, Traceer .
Cumplimiento con AML. De acuerdo con la ley de EE. UU., el estado del intercambio de criptomonedas debe tener un oficial certificado contra el lavado de dinero que sea responsable de rastrear transacciones sospechosas y enviar SAR (Informes de actividades sospechosas) a las autoridades de supervisión financiera. Este empleado debe tener un título en finanzas y un certificado emitido por el ICA o ACAMS.
Gestión de liquidez. Los comerciantes necesitan un intercambio que les permita intercambiar fácilmente un activo por otro en poco tiempo. Esto solo es posible si el sitio tiene suficiente liquidez: órdenes de compra o venta de criptomonedas para completar la transacción a un precio razonable. Puede proporcionar liquidez mediante:

Creador de mercado externo. Implica un acuerdo con proveedores de liquidez que normalmente comercian simultáneamente en muchos lugares diferentes y pueden proporcionar la liquidez necesaria para un intercambio de criptomonedas al realizar transacciones en otras plataformas comerciales.
Creación de un mercado entre intercambios. Esta estrategia también implica la cooperación con un creador de mercado, pero en este caso, usted entra en un acuerdo directamente con el operador de un intercambio externo, y no con un tercero.
Extracción de liquidez. Este método está más asociado con las comunidades descentralizadas, ya que recompensa a los usuarios por ayudar a asegurar la liquidez. La opción más simple: el usuario deposita dinero en la cuenta de intercambio y una vez al mes o al año recibe una recompensa en forma de un porcentaje de su contribución.
Arquitectura
Arquitectura un exchange. Este concepto generalmente se refiere a la estructura de la plataforma, que ayuda a definir de forma lógica y visual la relación y la forma de interacción entre todos los componentes del intercambio: la pantalla de inicio de sesión, el motor comercial, la interfaz de usuario, las funciones de seguridad. , API, bases de datos, etc. Aquí hay un ejemplo de una arquitectura de este tipo:

Cómo construir Un intercambio criptográfico desde cero
Arquitectura del intercambio de criptomonedas híbrido Qurrex
Pila de tecnología. Es un conjunto de herramientas de desarrollo como lenguajes de programación, librerías, frameworks, sistemas de gestión de bases de datos, compiladores, APIs, etc., para la creación del backend y frontend de la plataforma. En el caso de crear un intercambio de criptomonedas, puede verse así:

Development of cryptocurrency exchange
Crear un exchange de criptomonedas
Un intercambio de criptomonedas debe lanzarse solo a través de un desarrollo personalizado, ya que solo de esta manera puede garantizar la calidad y seguridad adecuadas del software. Puede crear un intercambio de cifrado basado en soluciones listas para usar (scripts), pero, por regla general, son creados por aficionados y/o conllevan el riesgo de que haya muchos agujeros de seguridad en el código, creados a propósito o por descuido. Teniendo en cuenta la situación con hacks tan frecuentes de los intercambios de criptomonedas, no vale la pena correr el riesgo.

Después de elegir una empresa desarrolladora, el proceso de creación de una plataforma de negociación de criptomonedas será el siguiente:

Firma de un contrato. Usted y la empresa desarrolladora discuten el concepto general del intercambio de criptomonedas, sobre la base del cual se crea la descripción técnica del proyecto. Después de eso, acuerda el tiempo, costo, KPI, canales de comunicación y firma un acuerdo de cooperación.
Prototipado de la plataforma. En la siguiente etapa, el diseñador, el analista comercial y/o el cliente crean un marco para el diseño del intercambio de criptomonedas, que luego se analiza y lleva a un estado ideal.
Creación del diseño de la interfaz. Además, basándose en el wireframe, los diseñadores desarrollan un diseño y/o prototipo de la interfaz de la plataforma, que muestra cómo se verá para los comerciantes y administradores.
Codificación directa. Después de crear el diseño, éste y la descripción técnica se entregan a los programadores que implementan todo esto en el código. Los desarrolladores front-end, back-end, blockchain y móviles son los responsables de esto.
Prueba del producto. Casi inmediatamente después del comienzo de la codificación, los ingenieros de control de calidad se ponen manos a la obra, revisan el código nuevo en busca de errores, y así sucesivamente hasta que se escribe el software. Otras pruebas se llevan a cabo en paralelo.
Implementación y soporte. Una vez que el software de intercambio de criptomonedas está listo para su lanzamiento, se lanza una campaña de marketing para atraer comerciantes. La plataforma se agrega a los listados de empresas y redes sociales.
El costo de un intercambio de cifrado
El costo de desarrollar un intercambio de cifrado depende en gran medida de los módulos y funciones que quieras integrar. Un intercambio al contado es el intercambio más simple para los usuarios y el desarrollo. Las funciones básicas de intercambio, una cuenta de usuario y un pequeño panel de administración no requieren mucho tiempo y su coste oscilará entre $20.000 y $30.000. Tenga en cuenta que algunos intercambios al contado pueden costar más si desea implementar integración de billetera fría, liquidez parcial o total, antiphishing, una gran cantidad de monedas, etc.

El costo del comercio de margen requiere mucho más esfuerzo para desarrollarse. La capacidad de operar con apalancamiento aumentará el valor del intercambio de cifrado de $30 000 a $50 000. Como regla general, necesitaremos de 2 a 3 meses para la codificación.

Desarrollar la función de futuros es uno de los más complejos y lleva más tiempo implementarlo. El coste de una plataforma de este tipo oscila entre $60 000 y $150 000. Eso sí, si necesitas integrar más funciones, el precio puede aumentar significativamente.

También debemos mencionar el costo de desarrollar una plataforma DEX. Normalmente, el precio de estos proyectos oscilará entre 40.000 y 80.000 dólares y requerirá entre 2 y 3 meses de trabajo.

Nuestra experiencia
Merehead ha estado desarrollando plataformas de criptomonedas desde 2018. Durante este período, desarrollamos proyectos basados en arquitectura monolítica y de microservicios, centros de ganancias escalables y simples. Realizamos intercambios de criptomonedas dex, spot y de margen, implementamos por separado futuros, opciones, liquidez parcial o total.

Nuestra experiencia incluye más de 20 proyectos y no todos tuvieron éxito. Hemos adquirido mucha experiencia y ahora utilizamos las mejores soluciones en desarrollo. A continuación puede ver ejemplos de algunos de nuestros intercambios de cifrado.






Si desea lanzar un intercambio de cifrado pero no sabe por dónde empezar o qué módulos integrar, nuestros expertos le asesorarán y le brindarán una propuesta de desarrollo detallada.
