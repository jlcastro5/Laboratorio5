# Informe Laboratorio 5
1. OBJETIVOS 

   Objetivo general
   * 

   Objetivos específicos
   
   
   * 
   
2. MARCO TEORICO

   ![]()

3. EXPLICACION DEL PROCEDIMIENTO
   
   ![](https://github.com/jlcastro5/Laboratorio5/blob/4a52e625462a077beefa5c8980c88b95151d153a/CircuitoEsquematico.PNG)
   
   Representamo el circutio en tinkercad con los correspondientes valores de cada resistencia y las respectivas fuentes de alimentacion para el circuito en este caso tenemos 2 fuentes de voltajes y nuestro circuito representado en protoboard queda de la siguiente manera mostrado en la Figura 1.
   
   ![](https://github.com/jlcastro5/Laboratorio5/blob/4a52e625462a077beefa5c8980c88b95151d153a/Protoboard.PNG)
   
   *Figura 1. Circuito en Tinkercad*
   
   Luego de colocar cada componente en nuestro protoboard colocamos 2 multimetros para medir el voltaje y la corriente que pasa por la resistecia 5 como se muestra en la figura 2.
   
   ![](https://github.com/jlcastro5/Laboratorio5/blob/4a52e625462a077beefa5c8980c88b95151d153a/Multimetro.PNG)
   
   *Figura 2. Colocacion de los multimetros en R5*
   
   Medicion del voltaje sin la resistencia 5, el cual el valor medido se muestra en la figura 3. y luego colocamos dicho valor en la tabla 1.
   
   ![](https://github.com/jlcastro5/Laboratorio5/blob/4a52e625462a077beefa5c8980c88b95151d153a/Voltaje.PNG)
   
   *Figura 3. Voltaje sin la resistencia R5*
   
   Ahora desconectamos las dos fuentes de alimentacion y realizamos un circutio cerrado para encontrar el valor de la resistencia, luego dicho valor colocamos en la tabla 1.
   ![](https://github.com/jlcastro5/Laboratorio5/blob/4a52e625462a077beefa5c8980c88b95151d153a/Resistencia.PNG)
   
   *Figura 4. Resistencia sin fuentes de voltajes*
   
   Luego simplificamos nuestro circuito, haciendo referencia a un circuito de thevenin el cual con los valores calculados en las imagenes anteriores podemos deducir el voltaje que pasa por R5 y su correspondiente corriente.
   
   ![](https://github.com/jlcastro5/Laboratorio5/blob/4a52e625462a077beefa5c8980c88b95151d153a/thevenin.PNG)
   
   *Figura 5. Circuito de thevenin en Tinkercad*
    
4. RESPUESTA A INTERROGANTES Y CALCULO DEL ERROR

   ![](https://github.com/jlcastro5/Laboratorio5/blob/4a52e625462a077beefa5c8980c88b95151d153a/CircuitoEsquematico.PNG)
   
   *Figura 6. Circuito esquematico*
   
   Para el siguiente analisis V2=0 para poder analizar y encontrar el primer voltaje de nuestro circuito de laboratorio el cual realizamos el siguiente procedimiento mostrado en la figura 7. Encontramos cada resistencia equivalente hasta encontrar y realizar un divisor de voltaje para encontrar la primera fuente.
   
   ![](https://github.com/jlcastro5/Laboratorio5/blob/90b65b0d93f936c448ac4c90a8b91cae7bd8aa7a/voltaje1.PNG)
   
   *Figura 7. Analisis cuando el voltaje V2=0*
   
   Ahora para encocntrar la otra fuente de voltaje tomamos el V1=0, para lo cual realizamosel mismo procedimiento de encontrar sus respectivas resistencia equivalentes mostrado en la figura 8. Para lo siguiente realizamos un divisor de voltaje y obtendremos V2.
   
   ![](https://github.com/jlcastro5/Laboratorio5/blob/90b65b0d93f936c448ac4c90a8b91cae7bd8aa7a/voltaje2.PNG)
   
   *Figura 8. Analisis cuando el voltaje V1=0*
   
   Realizamos la suma correspondiente entre las dos fuentes encontradas y con lo que obtendremos el voltaje thevenin.
   
   ![](https://github.com/jlcastro5/Laboratorio5/blob/90b65b0d93f936c448ac4c90a8b91cae7bd8aa7a/voltajethevenin.PNG)
   
   *Figura 9. Voltaje thevenin*
   
   Ahora realizamos un procedimiento para encontrar la resistencia de thevenin, analizamos nuestro circuito original
    
   ![](https://github.com/jlcastro5/Laboratorio5/blob/4a52e625462a077beefa5c8980c88b95151d153a/CircuitoEsquematico.PNG)
   
   *Figura 10. Circuito esquematico*
   
   Luego de haber analizado y tomando en cuenta que la resistencia del voltaje es 0 lo cual cada voltaje se cortocircuita, con lo que podemos realizar una simplificacion de resistencia de todo  nuestro circuito aplicando el procedimiento de thevenin como se ve en la figura 11. Una vez obtenido el valor colocamos en la tabla 1.
   
   ![](https://github.com/jlcastro5/Laboratorio5/blob/90b65b0d93f936c448ac4c90a8b91cae7bd8aa7a/ResistenciaThevenin.PNG) 
   
   *Figura 11. Resistencia Thevenin*
   
   Ahora debemos encontrar la corriente que pasa por la resistencia R5 teniendo en cuenta que tenemos tres mallas el cual en este caso voy a utilizar el analisis de malla para encontrar la corriente que pasa por R5
   
   Dibujamos nuestras respectivas corrientes, extramos cada dato para encontrar las ecuaciones correspondientes, luego colocamos en nuestra calculadora para encontrar los valores de las 3 corrientes en este casa la corriente que nos importa es de I3. Para lo cual el valor obtenido lo colocamos en la tabla 2.
   
   ![](https://github.com/jlcastro5/Laboratorio5/blob/90b65b0d93f936c448ac4c90a8b91cae7bd8aa7a/CircuitoOriginal.PNG)
   
   *Figura 12. Analisis de mallas*
   
   Realizamos el circuito esquematico de thevenin para obtener el valor de la corriente y voltaje en la resistencia 5 para lo cual mostrado en la figura 13. Realizamos una suma de resistencia y luego realizamos la ley de ohm para encontrar la corriente total, tomando encuenta que en un circuito en serie, luego reemplazamos el valor de la corriente obtenida para ver el valor del voltaje en la resitencia 5, y una vez obtenido los valores colocamos en la tabla 2.
   
   ![](https://github.com/jlcastro5/Laboratorio5/blob/f51cc14a4a081223eba42339d110e77875b2834e/CircuitoThevenin.PNG)
   
   *Figura 13. Circuito esquematico de thevenin*
   
   Tablas de valores obtenidos 
   
   ![](https://github.com/jlcastro5/Laboratorio5/blob/f51cc14a4a081223eba42339d110e77875b2834e/Tabla1.PNG)
   
   *Tabla 1. valores de voltaje y resistencia thevenin*
   
   ![](https://github.com/jlcastro5/Laboratorio5/blob/f51cc14a4a081223eba42339d110e77875b2834e/Tabla2.PNG)
   
   *Tabla 2. Valores de voltaje y corriente con la R5*
   
   Calculo de error
   
   Los valores de calculo de error de cada valor encontrado en nuestro circuito y informe el cual son voltajes y resistencia de thevenin y por otro lado la corriente y voltaje tanto de nuestro circuito original y thevenin
   
   ![](https://github.com/jlcastro5/Laboratorio5/blob/f51cc14a4a081223eba42339d110e77875b2834e/CalculoError.PNG)
   
   *Figura 14. Calculo de errores*
   

  
5. VIDEO

   


6. CONCLUSIONES

      * 	


7. BIBLIOGRAFÍA 

   Floyd,T. L. (2007). Principios de circuitos electricos. Mexico: Octava Edicion.
   Charles K & Sadiku M. (2006).Fundamentos de Circuitos eléctricos: Tercera Edición.
