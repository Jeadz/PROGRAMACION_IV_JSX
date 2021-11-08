# TRABAJO REACT.JS 
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
