<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 4


# Actividad: Crear una tabla HTML con información sobre productos.

Escribir una tabla HTML con 10 filas que muestre información sobre productos reales. La tabla debe tener las siguientes columnas:

- Código

- Nombre

- Descripción

- Precio

- Stock

- Fecha de creación



Además, combinar celdas en la tabla con los atributos rowspan y colspan, como se muestra en la siguiente imagen.


# Solución

## index

```html


<!DOCTYPE html>
<table border="1">
    <thead>
      <tr>
        <th rowspan="2">Cabecera</th>
        <th colspan="2">Columna 1</th>
      </tr>
      <tr>
        <th>Subcolumna 1</th>
        <th>Subcolumna 2</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td rowspan="2">Celda fusionada</td>
        <td>Contenido 1</td>
        <td rowspan="2">Celda fusionada</td>
      </tr>
      <tr>
        <td>Contenido 2</td>
      </tr>
      <tr>
        <td colspan="2">Totales</td>
        <td>Subtotal</td>
        <td>Impuestos</td>
      </tr>
    </tbody>
  </table>
```
## Tabla

``` html
<!DOCTYPE html>
<table border="1" cellpadding="10" cellspacing="5">
    <thead>
        <tr>
            <th>Codigo</th>
            <th>Nombre</th>
            <th>Descripción</th>
            <th>Precio</th>
            <th>Stock</th>
            <th>Fecha de creacion</th>
        </tr>
    </thead>

    <tbody>
        <tr>
            <td rowspan="2">0001</td>
            <td rowspan="2">iphone 14 Pro Max</td>
            <td>el iphone 14 Pro max es el smartphone mas potente</td>
            <td>4.899.000 COP</td>
            <td>10</td>
            <td>2022-09-21</td>
        </tr>
        <tr>
            <td>el iphone 14 Pro max esta disponible en 4 colore</td>
            <td>100</td>
             </tr>
        <tr>
            <td rowspan="2">0002</td>
            <td rowspan="2">MacBookProM2 Pro</td>
            <td>El MacBookProM2 es el nuevo portatil profesional</td>
            <td>10.499.000 COP</td>
            <td>10</td>
            <td>2023-06-06</td>
        </tr>
        <tr>
            <td>el iphone 14 Pro max esta disponible en 4 colores</td>
            <td>175</td> 
        </tr>
        <tr>
            <td rowspan="2">0003</td>
            <td rowspan="2">Nintendo Switch OLED</td>
            <td>La Nintendo Switch OLED es la versión anidada</td>
            <td>1.099.000 COP</td>
            <td>10</td>
            <td>2021-10-08</td>

        </tr>
        <tr>
            <td>La nintendo Switch OLED esta disponible en dos colores</td>
            <td>75</td> 

        </tr>
<tr>
<td rowspan="1">0004</td>
<td rowspan="1">Samsung S22</td>
<td rowspan="1">La mejor camara del mercado</td>
<td rowspan="1">2.500.000</td>
<td rowspan="1">150</td>
<td rowspan="1">01/09/2023</td>

</tr>

<tr>
    <td rowspan="1">0005</td>
    <td rowspan="1">Televisor Samsung 58 pulgadas oled</td>
    <td rowspan="1">Nueva pantalla, mejor resolucion</td>
    <td rowspan="1">1.900.000</td>
    <td rowspan="1">30</td>
    <td rowspan="1">01/09/2023</td>
    
    </tr>

    <tr>
        <td rowspan="1">0006</td>
        <td rowspan="1">Motorola edge30</td>
        <td rowspan="1">Lo nuevo en velocidad de procesador</td>
        <td rowspan="1">2.000.000</td>
        <td rowspan="1">50</td>
        <td rowspan="1">02/09/2023</td>
        
        </tr>

        <tr>
            <td rowspan="1">0007</td>
            <td rowspan="1">Samsung S22 ultra</td>
            <td rowspan="1">Todo en un celular</td>
            <td rowspan="1">3.500.000</td>
            <td rowspan="1">15</td>
            <td rowspan="1">03/09/2023</td>
            
            </tr>

            <tr>
                <td rowspan="1">0008</td>
                <td rowspan="1">Televisor lg 65 pulgadas</td>
                <td rowspan="1">Mejor definicion UHD 4K</td>
                <td rowspan="1">3.900.000</td>
                <td rowspan="1">25</td>
                <td rowspan="1">04/09/2023</td>
                
                </tr>

                <tr>
                    <td rowspan="1">0009</td>
                    <td rowspan="1">Portatil lenovo S145</td>
                    <td rowspan="1">Con procesador core i5</td>
                    <td rowspan="1">2.000.000</td>
                    <td rowspan="1">18</td>
                    <td rowspan="1">01/09/2023</td>
                    
                    </tr>

                    <tr>
                        <td rowspan="1">0010</td>
                        <td rowspan="1">Televisor Samsung 65 pulgadas</td>
                        <td rowspan="1">Pantalla de cristal liquido</td>
                        <td rowspan="1">4.500.000</td>
                        <td rowspan="1">10</td>
                        <td rowspan="1">04/09/2023</td>
                        
                        </tr>

    </tbody>
</table>
```






