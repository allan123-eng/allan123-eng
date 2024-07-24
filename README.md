<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<title>TULIPÁN</title>
<link href="jquery-mobile/jquery.mobile.theme-1.0.min.css" rel="stylesheet" type="text/css"/>
<link href="jquery-mobile/jquery.mobile.structure-1.0.min.css" rel="stylesheet" type="text/css"/>
<style>
body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f9;
    margin: 0;
    padding: 0;
}

#page {
    text-align: center;
}

.header {
    background-color: #6a1b9a;
    color: white;
    padding: 20px 0;
}

.header h1 {
    margin: 0;
    font-size: 2.5em;
}

ul {
    list-style-type: none;
    padding: 0;
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 10px;
}

ul li {
    margin: 10px 0;
}

ul li a {
    display: block;
    padding: 15px 20px;
    background-color: #4caf50;
    color: white;
    text-decoration: none;
    border-radius: 5px;
    transition: background-color 0.3s, transform 0.2s;
    box-shadow: 0 2px 4px rgba(0,0,0,0.1);
}

ul li a:hover {
    background-color: #45a049;
    transform: scale(1.05);
}

.page-content {
    padding: 20px;
    max-width: 800px;
    margin: auto;
}

.page-content img {
    max-width: 100%;
    height: auto;
    border-radius: 10px;
    box-shadow: 0 4px 6px rgba(0,0,0,0.1);
}

.footer {
    background-color: #6a1b9a;
    color: white;
    text-align: center;
    padding: 10px 0;
    position: fixed;
    bottom: 0;
    width: 100%;
}

.back-button {
    display: block;
    text-align: center;
    padding: 10px 20px;
    margin: 20px auto;
    background-color: #6a1b9a;
    color: white;
    text-decoration: none;
    border-radius: 5px;
    transition: background-color 0.3s, transform 0.2s;
    box-shadow: 0 2px 4px rgba(0,0,0,0.1);
}

.back-button:hover {
    background-color: #5a1390;
    transform: scale(1.05);
}

h2 {
    font-size: 1.5em;
    color: #333;
    text-align: center;
    margin-bottom: 20px;
}

p {
    text-align: justify;
    line-height: 1.6;
    color: #666;
}
</style>
<script src="jquery-mobile/jquery-1.6.4.min.js" type="text/javascript"></script>
<script src="jquery-mobile/jquery.mobile-1.0.min.js" type="text/javascript"></script>
</head>
<body>

<div data-role="page" id="page">
    <div class="header">
        <h1>TULIPÁN</h1>
    </div>
    <div class="page-content">
        <div align="center">
            <img src="imagenes/todo.png" width="626" height="289" alt="Tulipán">
        </div>
        <ul data-role="listview">
            <li><a href="#page2">ORIGEN DE SU NOMBRE</a></li>
            <li><a href="#page3">HISTORIA</a></li>
            <li><a href="#page4">CARACTERÍSTICAS Y TIPOS</a></li>
            <li><a href="#page5">USOS MEDICINALES DE LOS TULIPANES</a></li>
            <li><a href="#page6">CUIDADOS BÁSICOS DE LOS TULIPANES</a></li>
            <li><a href="#page7">CURIOSIDADES DE LOS TULIPANES</a></li>
        </ul>
    </div>
    <div class="footer">
        <h4>TULIPÁN</h4>
    </div>
</div>

<div data-role="page" id="page2">
    <div class="header">
        <h1>ORIGEN DE SU NOMBRE</h1>
    </div>
    <div class="page-content">
        <h2>Origen del nombre de los Tulipanes</h2>
        <p>La palabra "Tulipán" proviene de la palabra turca "tülbend". No obstante, esta palabra no hace referencia a una flor, sino a los turbantes. Dice la historia en 1554 el embajador austriaco Ogier Ghislain de Busbecq, vio una flor que no conocía en el turbante de un forastero. Busbecq, que también tenía conocimientos de botánica y escribía al respecto, pidió ayuda a su traductor para que le conociera el nombre de la belleza que observaba. La situación se convirtió en anecdótica cuando el hombre que poseía la flor, pensando que le preguntaban por su turbante, respondió con el nombre de la prenda que tenía en su cabeza.</p>
        <p>Así, de un momento a otro, Ogier Ghislain de Busbecq terminó pensando que el nombre de la planta era "tulipán", estableciéndose así el nombre de esta flor en Europa.</p>
        <img src="imagenes/historia.png" width="200" height="200" alt="Origen del nombre de los Tulipanes">
    </div>
    <a href="#page" class="back-button">Volver</a>
</div>

<div data-role="page" id="page3">
    <div class="header">
        <h1>HISTORIA</h1>
    </div>
    <div class="page-content">
        <h2>Historia de los Tulipanes</h2>
        <p>Durante muchos años se pensó que los tulipanes eran originarios de Medio Oriente, aunque sus primeras descripciones bajo el nombre usado actualmente se encontraban en Europa del Sur y China. Estudios actuales han permitido reconocer que su origen se sitúa en las montañas y estepas de Kazajistán, Irán y Afganistán; zona desde la cual la planta fue llevada hacia el gigante asiático y Europa.</p>
        <p>Historia de los Tulipanes Su cultivo ornamental inició su auge en el siglo XI, en Anatolia, en donde los Turcos hicieron uso de esta flor para adornar sus jardines y mostrar la belleza que poseían. También era común ver estas flores adornando las casas, las pinturas y todo el arte en general de este pueblo.</p>
        <p>Fueron los viajeros y comerciantes quienes llevaron los tulipanes a otras partes del mundo, extendiéndose durante la Edad Moderna hacia el norte de Europa. En la actualidad, es símbolo de los Países Bajos, Irán y Turquía.</p>
        <p>Holanda se posiciona como uno de los países que ha hecho historia con esta flor luego de que en 1593 el botánico Carolus Clusius ingresara los tulipanes a este territorio para realizar estudios e investigaciones médicas. La belleza de la flor terminó convenciendo a la clase alta y en cuestión de unas décadas el tulipán se volvió infaltable de jardines y centros de recreo. Este boom por la flor originó la llamada “Tulipomanía”, el alza excesiva del precio de esta flor debido a la especulación. Este cambio impidió que la flor pudiera seguir siendo comercializada y muchas personas acabaron con enormes pérdidas de dinero.</p>
        <p>En la actualidad, el tulipán es considerado una de las flores más requeridas en el mundo, además de ser usada también en numerosas investigaciones para el reforzamiento de la especie.</p>
        <img src="imagenes/amarillo.png" width="559" height="175" alt="Historia de los Tulipanes">
    </div>
    <a href="#page" class="back-button">Volver</a>
</div>

<div data-role="page" id="page4">
    <div class="header">
        <h1>CARACTERÍSTICAS Y TIPOS</h1>
    </div>
    <div class="page-content">
        <h2>Características y Tipos de los Tulipanes</h2>
        <p>Los tulipanes son fáciles de reconocer por sus características bulbosas. La flor posee un bulbo truncado basal cubierto por una túnica pilosa por dentro. Los pétalos se alzan y por lo general se encuentran acuminados (cerrados hacia adentro). El tallo muy pocas veces es ramificado y las hojas son basales (cerca al tallo), caulinares, espaciadas o lanceoladas (semi aplanadas). Con respecto al tallo, este es largo y sin mayores variaciones, llegando a alcanzar fácilmente los 20 centímetros, aunque hay registros de que puede llegar a medir 70 centímetros.</p>
        <p>El color de los tulipanes es muy variado, existiendo colores sólidos, bicolores y multicolores. Además, presentan una textura muy suave y una flor de muy buena calidad. Entre sus principales características podemos destacar:</p>
        <ul>
            <li>Son plantas de fácil cultivo, requerimiento básico y muy duraderas.</li>
            <li>Su floración puede extenderse entre los 20 a 30 días, dependiendo de la temporada.</li>
            <li>En general, la floración de los tulipanes puede observarse desde la primavera hasta el verano.</li>
        </ul>
        <p>Entre los tipos de tulipanes, entre los más conocidos se encuentran los llamados tulipanes dobles (que presentan flores con pétalos adicionales, lo que lo hace más voluptuoso), los tulipanes "Flor de Lirio" (curvilíneos y vistosos), los tulipanes con flecos (con seis hojas y un corte diferente), los tulipanes papagayo (de forma irregular, curva y con manchas) y los tulipanes de color sólido, considerados la variedad más hermosa, con un color de base y uno de contraste.</p>
        <img src="imagenes/tulipanes.png" width="502" height="197" alt="Tipos de Tulipanes">
    </div>
    <a href="#page" class="back-button">Volver</a>
</div>

<div data-role="page" id="page5">
    <div class="header">
        <h1>USOS MEDICINALES DE LOS TULIPANES</h1>
    </div>
    <div class="page-content">
        <h2>Usos Medicinales de los Tulipanes</h2>
        <p>En Europa, el tulipán no solo alcanzó fama como flor decorativa, sino también como analgésico en caso de dolencias estomacales. Usos medicinales de los Tulipanes, Por ejemplo, el té de las hojas de tulipán es reconocido como un potente laxante en caso de dolores del vientre. Se recomienda especialmente a las mujeres, sin que esto deje de lado el cuidado médico especializado. Las semillas del tulipán, principalmente de su variante conocida como "Rosa de china", son usadas para combatir el mal aliento. Solo basta con masticarlas. Otro uso señala que al hacer cataplasmas con ellas se puede tratar las irritaciones de la piel. En el caso de la raíz, esta es utilizada para elaborar baños para el cabello, mejorando su aspecto y su salud. Por último, también se dice que la infusión de esta flor puede aumentar el deseo sexual, por lo cual algunos lo usan como vigorizante antes de las relaciones. Cabe recordar que el uso de las plantas como medicina para tratar diversos males no debe reemplazar la consulta a un médico. La medicina natural puede ser un apoyo para el tratamiento de diversos males sin reemplazar la labor especializada de quienes estudiaron para poder salvar vidas.</p>
    </div>
    <a href="#page" class="back-button">Volver</a>
</div>

<div data-role="page" id="page6">
    <div class="header">
        <h1>CUIDADOS BÁSICOS DE LOS TULIPANES</h1>
    </div>
    <div class="page-content">
        <h2>Cuidados Básicos de los Tulipanes</h2>
        <p>El tulipán es una flor altamente comercial, pero muchos se animan a cultivarla en sus jardines. Sin embargo, requiere de cuidados especiales y de bastante dedicación. Para iniciarte en su cultivo puedes comprar los bulbos de la flor, los mismos que se venden en florerías o en centros especializados. Es importante que revises bien tu adquisición para asegurarte que no tenga hongos o estén secos. El tamaño del bulbo también dará una idea de cuán grande puede llegar a ser la flor.</p>
        <p>El siguiente paso es guardar el bulbo de tulipán en un lugar fresco hasta el momento de su plantación. Lo ideal es que no sean expuestos al sol directo, pero que tampoco estén en un frío extremo. Este proceso de conservación del bulbo es importante porque permite que la flor sea plantada en la mejor época del año para este fin, otoño, y así no sufra las inclemencias del clima en su crecimiento. Ya en otoño, se recomienda buscar un suelo ligero que pueda retener la humedad, sin llegar a inundarse. No los plantes en donde les dé luz solar directa porque eso puede estropear el florecimiento. El proceso para plantarlo es sencillo: luego de preparar el suelo, se planta el bulbo a una profundidad de 25 centímetros y luego se cubre con tierra. La punta del bulbo debe quedar hacia arriba y los bulbos deben estar al menos a 10 centímetros de distancia unos de otros. Pueden ser plantados también en macetas que tengan como mínimo 15 centímetros de diámetro. Ahora viene lo más importante: el riego y el cuidado. El tulipán requiere tierra húmeda sin que ésta esté inundada. Además, la tierra no debe estar excesivamente fría. Tampoco se recomienda poner fertilizantes cuando ya está plantado el bulbo. Si quieres hacer uso de abono, debes preparar la tierra antes de todo. Por lo general, estas flores solo necesitan los nutrientes del suelo. Si tienes tus tulipanes al aire libre evita que estos sean afectados por el aire frío directo. Si los tienes en maceta, puedes llevarlos dentro de casa cuando la planta ya tenga casi 8 centímetros. Cuando el tulipán está un poco más grande puedes agregarle un poco de fertilizante para plantas con flor. Esto le dará fortaleza. Cosecha tus tulipanes con cuidado. Recuerda que se recomienda cortarlos siempre en ángulos de 45 grados. Los bulbos del tulipán pueden darte hasta tres tandas de flores, pero es recomendable desenterrarlos y cambiarlos cada año. Si tus tulipanes se han marchitado, se recomienda recortarlos desde la base para dejar que la flor se renueve.</p>
        <img src="imagenes/rosa.png" width="395" height="145" alt="Cuidados Básicos de los Tulipanes">
        <img src="imagenes/morado.png" width="406" height="144" alt="Cuidados Básicos de los Tulipanes">
    </div>
    <a href="#page" class="back-button">Volver</a>
</div>

<div data-role="page" id="page7">
    <div class="header">
        <h1>CURIOSIDADES DE LOS TULIPANES</h1>
    </div>
    <div class="page-content">
        <h2>Curiosidades de los Tulipanes</h2>
        <p>Los tulipanes son la tercera flor más vendida en el mundo, siendo especialmente requerida para regalo por su elegancia. Durante el siglo XVII, los artistas optaron por usar estas flores para acompañar los bodegones en sus pinturas. En la actualidad es común verlas en los cuadros. Los cambios de tonalidades que ha sufrido el tulipán en los últimos años fueron producto de un virus que hizo surgir nuevas variedades y colores. El mal se mantuvo bajo control y finalmente llegó a ser aprovechado por los cultivadores. A diferencia de muchas flores, los tulipanes siguen creciendo aun cuando están cortados. Así que si te regalan un ramo, puedes ver esta maravilla. Por lo general, los tulipanes tienen una flor por tallo, pero se ha documentado también el florecimiento de hasta cuatro tulipanes de un mismo tallo. El tulipán es el símbolo del amante perfecto, de la pasión y el romanticismo, según la cultura popular. Las ardillas y los conejos pueden llegar a comer tulipanes, convirtiéndose en un peligro para los cultivos de esta flor.</p>
    </div>
    <a href="#page" class="back-button">Volver</a>
</div>

</body>
</html>
