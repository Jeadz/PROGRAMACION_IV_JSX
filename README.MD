# TRABAJO JSX 
## EJERCICIO # 1
## Código JavaScript

### Importo las librerías de React
```javascript
<script src="https://unpkg.com/react@16/umd/react.development.js"></script>
<script src="https://unpkg.com/react-dom@16/umd/react-dom.development.js"></script>
<script src="https://unpkg.com/babel-standalone@6/babel.min.js"></script>
```
### Creación de la variable "data", para guardar los datos del primer ejercicio
```javascript
const data = {
  titulo: "Plato de la semana",
  subtitle1:  "Berenjenas fritas",
  parrafo1: "Comensales: 4 personas",
  parrafo2: "Tiempo de preparación: 10 minutos",
  parrafo3: "Tiempo de cocción: 12 minutos",
  parrafo4: "Ingredientes:",
  ingrediente1:  "4 berenjenas.",
  ingrediente2:  "Sal.",
  ingrediente3:  "Pimienta.",
  ingrediente4:  "4 cucharadas de harina y aceite.",
  parrafo5:  "Preparación:",
  preparacion1:  "Lavar las berenjenas.",
  preparacion2:  "Cortarlas en rodajas.",
  preparacion3:  "Espolvorearlas con sal.",
  preparacion4:  "Dejar que suelten el agua durante 30 minutos.",
  preparacion5:  "Enharizarlas, ponerlas a freir durante 5 minutos en aceite bien caliente.",
}
```
### Creación de la variable element para imprimir los datos con formato JSX 
```javascript
const element = (
  <div>
    <h1>{data.titulo}</h1>
    <h2>{data.subtitle1}</h2>
    <p>{data.parrafo1}</p>
    <p>{data.parrafo2}</p>
    <p>{data.parrafo3}</p>
    <p>{data.parrafo4}</p>
    <p>
      {data.ingrediente1}<br/>
      {data.ingrediente2}<br/>
      {data.ingrediente3}<br/>
      {data.ingrediente4}
    </p>
    <p>{data.parrafo5}</p>
    <p>
      {data.preparacion1}<br/>
      {data.preparacion2}<br/>
      {data.preparacion3}<br/>
      {data.preparacion4}<br/>
      {data.preparacion5}
    </p>
    
  </div>
);
```
### Por último se pinta el documento JSX
```javascript
ReactDOM.render(
  element,// estructura jsx para pintar
  document.getElementById('root')// elemento donde se pintara
);
```

### Salida del ejercicio 1:
![Image text](img/ejercicio1.png)


# EJERCICIO 2
### Importo las librerías de React
```javascript
<script src="https://unpkg.com/react@16/umd/react.development.js"></script>
<script src="https://unpkg.com/react-dom@16/umd/react-dom.development.js"></script>
<script src="https://unpkg.com/babel-standalone@6/babel.min.js"></script>
```
### Creación de la variable 'data' para guardar los datos del ejercicio 
```javascript
const data = {
    titulo: "Página incial de Juan Tuesta",
    parrafo1: "Bienvenidos a mi página persoanl. Soy un alumno de la Universidad de Deusto y esta es mi página inicial, con la lista de mis enlaces favoritos y otra información de interés",
    titulo2: "Enlaces favoritos:",
    lista1: "Internet",
    lista2: "Google",
    lista3: "Aldea global",
    lista4: "Manual de HTML",
    parrafo2: "Juan Tuesta, Universidad de Deusto, marzo 2002.",
}
```
### Creación de la variable 'element' para dar formato JSX y HTML
```javascript
const element = (
    <div>
        <h1>{data.titulo}</h1>
        <p>{data.parrafo1}</p>
        <h2>{data.titulo2}</h2>
        <ol>
            <li>{data.lista1}</li>
            <li>{data.lista2}</li>
            <li>{data.lista3}</li>
            <li>{data.lista4}</li>
        </ol>
        <p><i>{data.parrafo2}</i></p>
    </div>
);
```
### Salida Ejercicio 2
![Image text](img/ejercicio2.png)

# EJERCICIO 3
### Importo las librerías de React
```javascript
<script src="https://unpkg.com/react@16/umd/react.development.js"></script>
<script src="https://unpkg.com/react-dom@16/umd/react-dom.development.js"></script>
<script src="https://unpkg.com/babel-standalone@6/babel.min.js"></script>
```
### Creación de la variable 'data' para guardar los datos del ejercicio 
```javascript
const data = {
    titulo: "Página incial de Juan Tuesta",
    parrafo1: "Bienvenidos a mi página persoanl. Soy un alumno de la Universidad de Deusto y esta es mi página inicial, con la lista de mis enlaces favoritos y otra información de interés",
    titulo2: "Enlaces favoritos:",
    lista1: "Internet",
    lista2: "Google",
    lista3: "Aldea global",
    lista4: "Manual de HTML",
    parrafo2: "Juan Tuesta, Universidad de Deusto, marzo 2002.",
}
```
### Creación de la variable 'element' para dar formato JSX y HTML
```javascript
const element = (
    <div>
        <h1>{data.titulo}</h1>
        <p>{data.parrafo1}</p>
        <h2>{data.titulo2}</h2>
        <ol>
            <li>{data.lista1}</li>
            <a href=""><li>{data.lista2}</li></a>
            <li>{data.lista3}</li>
            <a href=""><li>{data.lista4}</li></a>
        </ol>
        <p><i>{data.parrafo2}</i></p>
    </div>
);
```
### Salida Ejercicio 3
![Image text](img/ejercicio3.png)

# EJERCICIO 4
### Importo las librerías de React
```javascript
<script src="https://unpkg.com/react@16/umd/react.development.js"></script>
<script src="https://unpkg.com/react-dom@16/umd/react-dom.development.js"></script>
<script src="https://unpkg.com/babel-standalone@6/babel.min.js"></script>
```
### Creación de la variable 'data' para guardar los datos del ejercicio 
```javascript
const data = {
    titulo: "Página incial de Juan Tuesta",
    parrafo1: "Bienvenidos a mi página persoanl. Soy un alumno de la Universidad de Deusto y esta es mi página inicial, con la lista de mis enlaces favoritos y otra información de interés",
    titulo2: "Enlaces favoritos:",
    favorito1: "Páginas personales",
    listafav1: "Charkes F. Golfarb",
    listafav2: "Lou Burnard",
    listafav3: "Tim Berners-Lee",
    favorito2: "Páginas de referencia",
    favorito3: "Portales",
    favorito4: "Medios de comunicación",
    parrafo2: "Juan Tuesta, Universidad de Deusto, marzo 2002.",
}
```
### Creación de la variable 'element' para dar formato JSX y HTML
```javascript
const element = (
    <div>
        <h1>{data.titulo}</h1>
        <p>{data.parrafo1}</p>
        <h2>{data.titulo2}</h2>
        <ol>
            <li>{data.favorito1}
                <ul>
                    <li>{data.listafav1}</li>
                    <li>{data.listafav2}</li>
                    <li>{data.listafav3}</li>
                </ul>
            </li>
            <li>{data.favorito2}</li>
            <li>{data.favorito3}</li>
            <li>{data.favorito4}</li>
        </ol>
        <p><i>{data.parrafo2}</i></p>
    </div>
);
```
### Salida Ejercicio 4
![Image text](img/ejercicio4.png)

# EJERCIO 5  
### Importo las librerías de React
```javascript
<script src="https://unpkg.com/react@16/umd/react.development.js"></script>
<script src="https://unpkg.com/react-dom@16/umd/react-dom.development.js"></script>
<script src="https://unpkg.com/babel-standalone@6/babel.min.js"></script>
```
### Creación de la variable 'data' para guardar los datos de los 'enlaces favoritos' del ejercicio 
```javascript
const data = {
    titulo: "Página incial de Juan Tuesta",
    parrafo1: "Bienvenidos a mi página persoanl. Soy un alumno de la Universidad de Deusto y esta es mi página inicial, con la lista de mis enlaces favoritos y otra información de interés",
    titulo2: "Enlaces favoritos:",
    favorito1: "Páginas personales",
    favorito2: "Páginas de referencia",
    favorito3: "Portales",
    favorito4: "Publicaciones",
    parrafo2: "Juan Tuesta, Universidad de Deusto, marzo 2002.",
}
```
### Creación de la variable 'dataPersonales' para guardar los datos de  'Personales' del ejercicio 
```javascript
const dataPersonales = {
    titulo1: "Documentalistas",
    subtitulo1: "Charkes F. Golfarb",
    subtitulo2: "Lou Burnard",
    subtitulo3: "Tim Berners-Lee",
    titulo2: "Historiadores",
    titulo3: "Lingüistas",
    titulo4: "Traductores",
}
```
### Creación de la variable 'dataReferencia' para guardar los datos de 'Referencia' del ejercicio 
```javascript
const dataReferencia = {
    titulo1: "Bibliotecas universitarias",
    titulo2: "Centros de documentación",
    titulo3: "Museos de arte contemporáneo",
    titulo4: "Medios de comunicación",
}
```
### Creación de la variable 'dataPortales' para guardar los datos de 'Portales' del ejercicio 
```javascript
const dataPortales = {
    titulo1: "Inicia",
    titulo2: "Telépolis",
    titulo3: "Ciudades",
    titulo4: "Terra",
}
```
### Creación de la variable 'dataPublicaciones' para guardar los datos de 'Publicaciones' del ejercicio 
```javascript
const dataPublicaciones = {
    titulo1: "Ciberp@ís",
    titulo2: "Diario Tecnologías de la Información",
    titulo3: "The Standard",
    titulo4: "Infoworld",
    titulo5: "Wired",
}
```
### Creación de la variable 'element' para pintar los datos con la estructura JSX y HTML
```javascript
const element = (
    //Este div se encarga de mostrar la información de "Enlaces"
    <div id="inicio">
        <h1>{data.titulo}</h1>
        <p>{data.parrafo1}</p>
        <h2>{data.titulo2}</h2>
        <ol>
            <a href = ""><li>{data.favorito1}</li></a>
            <li>{data.favorito2}</li>
            <li>{data.favorito3}</li>
            <li>{data.favorito4}</li>
        </ol>
        <hr/>
        <h2>{data.favorito1}</h2>
        <div id="personales">
            <ol>
                <li>{dataPersonales.titulo1}
                    <ul>
                        <li>{dataPersonales.subtitulo1}</li>
                        <li>{dataPersonales.subtitulo2}</li>
                        <li>{dataPersonales.subtitulo3}</li>
                    </ul>
                </li>
                <li>{dataPersonales.titulo2}</li>
                <li>{dataPersonales.titulo3}</li>
                <li>{dataPersonales.titulo4}</li>
            </ol>
            <hr/>
        </div>
        <div id= "referencia">
            <h2>{data.favorito2}</h2>
            <ol>
                <li>{dataReferencia.titulo1}</li>
                <li>{dataReferencia.titulo2}</li>
                <li>{dataReferencia.titulo3}</li>
                <li>{dataReferencia.titulo4}</li>
            </ol>
            <hr/>
        </div>
        <div>
            <h2>{data.favorito3}</h2>
            <ol>
                <li>{dataPortales.titulo1}</li>
                <li>{dataPortales.titulo2}</li>
                <li>{dataPortales.titulo3}</li>
                <li>{dataPortales.titulo4}</li>
            </ol>
        </div>
        <hr/>
        <div>
            <h2>{data.favorito4}</h2>
            <ol>
                <li>{dataPublicaciones.titulo1}</li>
                <li>{dataPublicaciones.titulo2}</li>
                <li>{dataPublicaciones.titulo3}</li>
                <li>{dataPublicaciones.titulo4}</li>
                <li>{dataPublicaciones.titulo5}</li>
            </ol>
            <hr/>
        </div>
        <p><i>{data.parrafo2}</i></p>
    </div>    
);
```
### Salida Ejercicio 5

![Image text](img/ejercicio5-1.png)


# EJERCICIO 6
### Importo las librerías de React
```javascript
<script src="https://unpkg.com/react@16/umd/react.development.js"></script>
<script src="https://unpkg.com/react-dom@16/umd/react-dom.development.js"></script>
<script src="https://unpkg.com/babel-standalone@6/babel.min.js"></script>
```
### Creación de la variable 'data' para guardar los datos del,  ejercicio 
```javascript
const data = {
    titulo: "El Noticiero Next University",
    subtitulo1: "Programas de Tecnología",
    subtitulo2: "Desarrollador Web",
    parrafo1:  <p><b><i>Next University</i></b> lanza su programa
            de formacón <b>"Desarrollador Web"</b> con la 
            finalidad de capacitar a personas en las tendencias
            actuales sobre tecnologías, en el caso de desarrollo web,
            se basa en temas relacionados a la implementación de Front-Ent 
            con tecnologías y Frameworksm tales como: <i>HTML5,CSS,JavaScript,
            Boostrap, entre otros.</i></p>,
    subtitulo3: "Android",
    parrafo2: <p>En <b><i>Next University</i></b> te ofrecemos
        el programa <b>Android</b> que te da las herramientas 
        necesarias para diseñar e implementar aplicaciones
        Android para dispositivos móviles, partiendo de un conocimiento
        básico de <i>Java</i>, utilizando el entorno
        de desarrollo <i>Android Studio</i>. Aprenderás los
        aspectos fundamentales para crear aplicaciones Android interactivas,
        dinámicas y exitosas utilizando técnicas para el manejo de los recursos,
        datos, segundos planos, localización, sensores, animaciones,gráficos, 
        multimedia y monetización.</p>,
    titulo2: "Programa de Negocio",
    subtitulo4: "Mercadeo Digital",
    parrafo3:<p><b><i>Next University</i></b> coloca a tu disposición
        de programa <b>"Mercadeo Digital"</b>. Sabías que... Mercadeo Digital
        o Digital Marketing es mucho más que hacer y publicar anuncios.
        Se trata del consumidor y la estrategia de negocio.
        Estos son los puntos de partida para que cualquier acción de mercadeo Digital
        <i>sea exitosa y optimice la inversión</i>.
        Este certificado, es un  programa completo y práctico que permite
        entender al consumidor, la industria, la competencia y los retos del 
        negocio propio: para crear e implementar estrategias a la medida e diferentes
        plataformas y medios digitales. Por supuesto, monitoreando los resultados
        para tomar decisiones en tiempo real </p> ,
}
```
### Creación de la variable 'element' para pintar los datos con la estructura JSX y HTML
```javascript
const element = (
    <div>
        <h1>{data.titulo}</h1>
        <h2>{data.subtitulo1}</h2>
        <h3>{data.subtitulo2}</h3>
        {data.parrafo1}
        <h3>{data.subtitulo3}</h3>
        {data.parrafo2}
        <h2>{data.titulo2}</h2>
        <h3>{data.subtitulo4}</h3>
        {data.parrafo3}
    </div>
);
```
### Pinto los datos en la pantalla con ReactDOM.render();
```javascript
ReactDOM.render(
    element,
    document.getElementById('root')
    );
```

### Salida Ejercicio 6
![Img text](img/ejercicio6-1.png)
![Img text](img/ejercicio6-2.png)

# EJERCICIO 7
### Importo las librerías de React
```javascript
<script src="https://unpkg.com/react@16/umd/react.development.js"></script>
<script src="https://unpkg.com/react-dom@16/umd/react-dom.development.js"></script>
<script src="https://unpkg.com/babel-standalone@6/babel.min.js"></script>
```
### Creación de la variable 'data' para guardar los datos del,  ejercicio 
```javascript
const data = {
    titulo: "Destinos Turísiticos",
    subtitulo1: "América",
    lista1: "Argentina",
    sublista1_1: "Buenos Aires",
    sublista1_2: "Bariloche",
    lista2:"Brasil",
    sublista2_1: "Rio de Janeiro",
    sublista2_2: "Brasilia",
    lista3: "Chile",
    sublista3_1: "Santiago",
    sublista3_2: "Valparaiso",
    lista4: "Colombia",
    sublista4_1: "Bogotá",
    sublista4_2: "Catagena de Indias",
    lista5: "Estados Unidos",
    sublista5_1: "New York",
    sublista5_2: "San Francisco",
    lista6: "México",
    sublista6_1: "Cancún",
    sublista6_2: "Acapulco",
    lista7: "Perú",
    sublista7_1: "Lima",
    sublista7_2: "Cuzco",
    lista8: "Venezuela",
    sublista8_1: "Magarita",
    sublista8_2: "Mérida",
}
```
### Creación de la variable 'element' para pintar los datos con la estructura JSX y HTML
```javascript
const element = (
    <div>
        <h1><b>{data.titulo}</b></h1>
        <h2><b>{data.subtitulo1}</b></h2>
        <ol>
            <b><li><h3>{data.lista1}</h3></li></b>
            <ol>
                <li><i>{data.sublista1_1}</i></li>
                <li><i>{data.sublista1_2}</i></li>
            </ol>
            <b><li><h3>{data.lista2}</h3></li></b>
            <ol>
                <li><i>{data.sublista2_1}</i></li>
                <li><i>{data.sublista2_2}</i></li>
            </ol>
            <b><li><h3>{data.lista3}</h3></li></b>
            <ol>
                <li><i>{data.sublista3_1}</i></li>
                <li><i>{data.sublista3_2}</i></li>
            </ol>
            <b><li><h3>{data.lista4}</h3></li></b>
            <ol>
                <li><i>{data.sublista4_1}</i></li>
                <li><i>{data.sublista4_2}</i></li>
            </ol>
            <b><li><h3>{data.lista5}</h3></li></b>
            <ol>
                <li><i>{data.sublista5_1}</i></li>
                <li><i>{data.sublista5_2}</i></li>
            </ol>
            <b><li><h3>{data.lista6}</h3></li></b>
            <ol>
                <li><i>{data.sublista6_1}</i></li>
                <li><i>{data.sublista6_2}</i></li>
            </ol>
            <b><li><h3>{data.lista7}</h3></li></b>
            <ol>
                <li><i>{data.sublista7_1}</i></li>
                <li><i>{data.sublista7_2}</i></li>
            </ol>
            <b><li><h3>{data.lista8}</h3></li></b>
            <ol>
                <li><i>{data.sublista8_1}</i></li>
                <li><i>{data.sublista8_2}</i></li>
            </ol>
        </ol>
        

    </div>
);
```
### Pinto los datos en la pantalla con ReactDOM.render();

```javascript
ReactDOM.render(
    element,
    document.getElementById('root')
    );
```
### Salida Ejercicio 7
![Img text](img/ejercicio7-1.png)
![Img text](img/ejercicio7-2.png)