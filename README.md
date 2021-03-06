# Multiplexer-Display-7-Segments---Arduino---PCF8574-Remote-8-Bit-I-O-Expander-for-I2C-Bus

Design of a 7-segment Multiplexer with Arduino, which can display integer, floating numbers. The multiplexer works as follows:       
    * The digital ports connect to the common displays, which will activate the corresponding digit to display on the display.                 * By I2C communication with the PCF8574 Expander, the segments of the displays are connected and controlled. 
The library provides flexibility at the time of circuit design, allowing to make the following configurations:       
    * Configure the number of displays that will be connected to the Arduino.       
    * Configure the type of display to be used, either common anode or common status.      
    * Declare the digital ports for the displays to be used, allowing them to be ordered to the user's needs.  
    
 -------------------------------------------------------------------------------------------------------------------------------- 
 Diseño de un Multiplexor de 7 Segmentos con Arduino, el cual puede mostrar numeros de tipo entero y flotante. El multiplexor funciona de la siguiente manera:       
    * Los puertos digitales se conectan a los comunes de los displays, los cuales activaran el digito correspondiente a mostrar en el display.       
    * Mediante comunicacion I2C con el Expansor PCF8574 se conectan y controlan los segmentos de los displays.  
 La libreria brinda flexibilidad al momento del diseño del circuito, permitiendo realizar las siguientes configuraciones:       
    * Configurar la cantidad de displays que se conectaran al arduino.      
    * Configurar el tipo de display que se usara, ya sea de anodo comun o de catodo comun.      
    * Declarar los puertos digitales para los displays a utilizar, permitiendo ordenarlos a las necesidades del usuario.
