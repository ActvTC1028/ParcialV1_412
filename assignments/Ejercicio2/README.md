![Tec de Monterrey](../../images/logotecmty.png)
# Ejercicio 2 del examen parcial AD2021
Ciclos - Cuántos pares e impares recibes

Escribe un programa que reciba números positivos o negativos (considera el 0 como positivo) y vaya contando aquellos números que son pares y vaya sumando los impares.

El programa deberá preguntar cuántos números va a recibir, si la cantidad de números es 0 o menor deberá mandar el mensaje *La cantidad de números debe ser mayor a 0* de lo contrario recibe esa cantidad de números y al terminar de recibirlos debe mostrar el mensaje de cuántos pares recibió además de la suma de los impares (ve los ejemplos).

En el ejemplo, observa que la solicitud de los números está numerada (Número 1: , Número 2, etc...) Así debe ser el mensaje de ingreso de datos.

Modifica el programa que se encuentra en la carpeta `src` que se llama
`exercise.py` y que contiene el siguiente código:

```python
def main():
    #escribe todo tu código abajo de esta línea, no es necesario una función

if __name__ == '__main__':
    main()
```

**Ejemplo de corrida:**

```
Cantidad de números: 5
Número 1: 2
Número 2: -3
Número 3: 0
Número 4: 12
Número 5: 150
Pares: 4
Suma de impares: -3
```
**Otro ejemplo**
```
Cantidad de números: 0
La cantidad de números debe ser mayor a 0
```

**Nota:** Por favor no quites nada de lo que ya tienes, simplemente agrega el código 
necesario dentro de la función main. 
`if __name__ == '__main__':` debe quedarse en tu código para que las pruebas puedan 
ejecutarse adecuadamente.

Una vez que termines tu actividad, si te da tiempo prueba con
`pytest`, si no, simplemente súbela a tu repositorio en GitHub, con el proceso de commit + push.
Debe ser enviada antes de las 11:00 hrs. que se cierra el ejercicio.
