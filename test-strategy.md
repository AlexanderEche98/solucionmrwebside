# Como tester, encontré y solucioné los siguientes errores en el código HTML y JavaScript:
Encontré un error en el generador de números aleatorios, ya que solo generaba números del 1 al 10 en lugar de 1 al 100. Para corregir esto, ajusté la generación de números aleatorios para que esté en el rango correcto de 1 al 100.

Descubrí que el juego estaba configurado para permitir solo 5 intentos en lugar de los 10 especificados en la descripción del juego. Para solucionarlo, modifiqué la variable ATTEMPTS para que tenga el valor de 10, permitiendo así el número correcto de intentos.

Identifiqué un problema en el campo de entrada, donde no se realizaba una validación adecuada del valor ingresado. No se verificaba si el valor no era un número o estaba fuera del rango válido (1-100), lo que podría causar problemas en el juego. Para resolver esto, implementé una validación que verifica si el valor ingresado no es numérico, está fuera del rango válido o no es un número entero. Si se cumple alguna de estas condiciones, se muestra una alerta y se borra el campo de entrada.

En el código, encontré un error en el selector del elemento con la clase lowOrHi. No se incluyó el punto delante del nombre de clase, lo que provocaba que el selector no funcionara correctamente. Para solucionarlo, agregué el punto delante del nombre de clase en el selector para lowOrHi, asegurando que funcione como se espera.

Observé que el evento click en el botón de envío no estaba vinculado correctamente a la función checkGuess. El nombre de la función en el método addEventListener no coincidía, lo que causaba que la función no se ejecutara al hacer clic en el botón. Para remediarlo, corregí el nombre de la función addEventListener y vinculé correctamente el evento click a la función checkGuess.

También noté un problema similar en el evento click del botón de reinicio. El nombre de la función en el método addEventListener no estaba escrito correctamente, lo que provocaba que la función resetGame no se llamara cuando se hacía clic en el botón. Para solucionarlo, ajusté el nombre de la función addEventListener y vinculé adecuadamente el evento click a la función resetGame.

Por ultimo solo cambie color del mensaje incorrecto de naranja a negro 