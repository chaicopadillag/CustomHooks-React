# useFetch Get

Un ejemplo sencillo de uso.

```
const URL_API = `https://ruta-api/key=d5d5s2f6d1?search=1`;

//Retorna un objeto

const {data: json,loading: false,error: null } = useFetch(URL_API);

```

**_Ó De manera desestructurado_**

```
const {data } = useFetch(URL_API);

```
