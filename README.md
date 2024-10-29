# Caso práctico.

## Contexto.
El restaurante "Sabores del Mundo", es conocido por su auténtica cocina y su ambiente acogedor. Este restaurante lanzó un nuevo menú a principios de año y ha estado recopilando
información detallada sobre las transacciones de los clientes para identificar áreas de oportunidad y aprovechar al máximo sus datos para optimizar las ventas.

## Objetivo.
Identificar cuáles son los productos del menú que han tenido más éxito y cuales son los que menos han gustado a los clientes.

## Características de la base de datos.
En la siguiente imagen se muestra como se conforma la base de datos con la que se harán las consultas pertinentes para identificar áreas de oportunidad. 

![image](https://github.com/user-attachments/assets/8206b3ca-a98b-40c9-af53-c7e4f1d7bfc1)

## Desarrollo.
Se realizó la base de datos con el archivo create_restaurant_db.sql en pgAdmin.Dando como resultado la  tabla “menu_items” que da a conocer los productos del menú.
![image](https://github.com/user-attachments/assets/d16bb4fa-c6a2-4933-a87a-c7d541e2634b)

Así mismo la tabla “order_details” para conocer los datos que han sido recolectados dando como resultado una tabla más extensa pero se puso la siguiente imagnen para que se visualice la composición de la tabla. 
![image](https://github.com/user-attachments/assets/54999ce2-d78b-4781-b6c7-03892c6168af)

Posterior se hicieron diferentes consultas entre las más relevantes son: 
--¿Cuál es el artículo menos caro y el más caro en el menú?

![image](https://github.com/user-attachments/assets/4ed8fe63-ff39-40d6-b76a-dfbac112c7eb)

--¿Cuál es el precio promedio de los platos?

![image](https://github.com/user-attachments/assets/7fd919ad-9038-4deb-8622-2fc2fec0955d)

--¿Cuáles son los 5 pedidos que tuvieron el mayor número de artículos?
![image](https://github.com/user-attachments/assets/23276f71-fa70-4952-b039-2b937d03a87a)

Entre otras, con la finalidad de conocer ambas tablas y tener una noción de los datios en las mismas. Aunado ha eso se hizo una unión de ambas tablas para realizar asi el analisis. 
![image](https://github.com/user-attachments/assets/2192984f-2854-46ed-b908-65514640688d)
(Con la cantidad de datos se sabe que es mas grande pero esta imagen muestra parte de su estructura).

Las siguientes consultas se hiceron de esta unión (left join)

--¿Cuales fueron los platillos mas solicitados del menu?
![image](https://github.com/user-attachments/assets/23fb9b14-f1c4-4d87-b234-810406a40faf)

--¿A que categoria pertenecen los platilos mas pedidos?
![image](https://github.com/user-attachments/assets/7f8a2814-a5b0-44af-8a37-9e72d52a2921)

--¿En qué fechas se hicieron mas pedidos? 
![image](https://github.com/user-attachments/assets/5d52a832-cda4-44de-a6af-b4f14a51321b)

--¿En que fechas se hicieron pedidos de platillos mas caros?
![image](https://github.com/user-attachments/assets/9eca67a1-473b-4f66-ab32-cb2994d835d3)

## Conclusión


