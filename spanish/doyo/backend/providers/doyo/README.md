# Doyo
Doyo ofrece una serie de funciones básicas que normalmente es mejor que se ejecuten en un servidor. Por ejemplo, si queremos obtener la fecha actual, no conviene fiarse de la fecha configurada en el dispositivo donde se ejecuta una app, sino utilizar la fecha real que se puede obtener en el servidor.
<br>
<br>
  
# Métodos
<br>
<br>

## random.pin
Genera un pin numérico aleatorio con el número de dígitos dado.
<br>
<br>
    
**Parámetros:**  
<br>
| key  | Descripción |
| ------------- | ------------- |
| digits | Número de dígitos que debe tener el PIN |
<br>
<br>
  
  
## timestamp
Devuelve el timestamp del servidor, que es el número de segundos transcurridos desde el 1 de Enero de 1970.
<br>
<br>

**Parámetros:**  
No requiere parámetros.
<br>
<br>
  
**Ejemplo:**  
<br>

    {
        "provider": "doyo",
        "method": "timestamp"
    }

<br>
<br>
  
## timestamp.format
Devuelve la fecha actual del servidor con el formato especificado.
<br>
<br>
  
**Parámetros:**  
<br>
| key  | Descripción |
| ------------- | ------------- |
| format | Formato en el que se quiere obtener la fecha, basado en SimpleDateFormat |
<br>
<br>
  
## timestamp.milliseconds
Devuelve el timestamp del servidor, pero medido en milésimas de segundo
<br>
<br>
  
**Parámetros:**  
No requiere parámetros.
<br>
<br>
  
**Ejemplo:**  
<br>

    {
        "provider": "doyo",
        "method": "timestamp.milliseconds"
    }
    
<br>
<br>
  
## uuid
Devuelve un identificador único universal (UUID)
<br>
<br>
  
**Parámetros:**  
No requiere parámetros.
<br>
<br>
  
**Ejemplo:**  
<br>

    {
        "provider": "doyo",
        "method": "uuid"
    }
    
<br>
<br>
  