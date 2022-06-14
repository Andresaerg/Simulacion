
Desarrollar una aplicación que permita resolver el problema del EBRIO, puede ser programada en cualquier lenguaje de programación o herramienta
informatica que este a su disposición. Se debera remitir el codigo fuente y un archivo ejecutable de la misma.

Supongamos que un ebrio está parado en una esquina, cuando decide caminar para que le pase el efecto “ya ustedes saben cuál”.
Supongamos que existe una probabilidad igual de que se dirija al norte, sur, este u oeste al llegar a cada esquina. Si camina 10 calles,
¿Cuál es la probabilidad de que termine su recorrido a dos calles de donde lo empezó?
El proyecto es Grupal maximo 2 integrantes, quien lo desee realizar solo o en pareja no hay ningún problema.


// Datos utilizados en el diseño de la simulación: 
// Norte, Sur, Este, Wester = 1/4 para c/u, es decir = 0.25; en rands
// sería para Norte = 0-24 ; Este = 25-49; Sur = 50-74; Wester = 75-99.
// Posteriormente hacer la función caminar para mostrar el recorrido, luego
// ejecutar varios intentos estilo "Monte Carlo" y así obtener la probabilidad variable en función a los recorridos
// la probabilidad fija sería en base a las posibles combinaciones en el plano X,Y; "nPc": P = 4 / nPc + 1 (punto de origen).