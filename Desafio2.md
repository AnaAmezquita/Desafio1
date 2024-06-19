#DESAFIO 2

/* 1. Pregunta al usuario qué día de la semana es. Si la respuesta es "Sábado" o "Domingo", muestra "¡Buen fin de semana!". De lo contrario, muestra "¡Buena semana!". */

let DiadelaSemana = prompt('¿Qué día de la semana es?');
if (DiadelaSemana == Sábado || DiadelaSemana ==Domingo) {
    alert('¡Buen fin de semana!)
} else {
    alert('¡Buena semana!');
}

/* 2. Verifica si un número ingresado por el usuario es positivo o negativo. Muestra una alerta informativa. */
let numero = prompt('Ingresa un numero: ');

if(numero > 0) {
    alert('El número es positivo.');
} else if (numero < 0) {
    alert('El número es negativo.');
} else {
    alert('El número es cero.');
}

/* 3.Crea un sistema de puntuación para un juego. Si la puntuación es mayor o igual a 100, muestra "¡Felicidades, has ganado!". En caso contrario, muestra "Intentalo nuevamente para ganar.". */

let puntuacion = 101
if(puntuacion > 100) {
   alert('¡Felicidades, has ganado!');
} else {
   alert('Inténtalo nuevamente para ganar');
}

/* 4. Crea un mensaje que informe al usuario sobre el saldo de su cuenta, utilizando un template string para incluir el valor del saldo. */

let SaldoCuenta = 150
alert(`Tu saldo de cuenta es: ${SaldoCuenta}`);

/* 5. Pide al usuario que ingrese su nombre mediante un prompt. Luego, muestra una alerta de bienvenida usando ese nombre. */

let NombreUsuario = prompt('Ingresa tu nombre.')
alert(`Bienvendid@, ${NombreUsuario}`);
