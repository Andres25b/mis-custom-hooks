# useForm Hook

Ejemplo de uso
```
    const initialForm = {
        nombre: '',
        age: 0,
        email: '',
    };
    
    const [values, handleInputChange, reset] = useForm(initialForm);
```