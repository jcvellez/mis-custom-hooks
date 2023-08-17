#useFetch Hook

Ejemplo de un uso:
```
    const url='endpoint de una api';
    const{
        data: null,
        loading: true,
        error: null
        } = useFetch(url); 
```

useFetch() //recibe un url por defecto