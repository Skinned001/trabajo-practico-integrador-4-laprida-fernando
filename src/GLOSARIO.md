TypeScript (TS):	Superconjunto de JavaScript que añade tipado estático opcional para mejor detección de errores y escalabilidad.	 Ejemplo = let mensaje: string = "Hola";

Tipado Estático:	Asignación y verificación de tipos de datos (string, number, boolean) en el tiempo de desarrollo.	Ejemplo = let edad: number = 30;

Transpilación:	Proceso de convertir el código TS a JavaScript puro para su ejecución.	Ejemplo = npx tsc (Comando)

Enum:	Conjunto de constantes con nombre que mejoran la legibilidad.	Ejemplo = enum Estado { OK, ERROR }

Union Types: Permite que una variable acepte uno de varios tipos definidos (separados por `	`).

Tipo any:	Desactiva la verificación de tipos; debe evitarse para mantener el tipado estático. Ejemplo = let valor: any = 10;