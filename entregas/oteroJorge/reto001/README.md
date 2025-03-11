# Legibilidad

| Asignatura | Enlace al repo | Reto|
|------------|---------------|------|
| Progra 1  | [Repositorio](https://github.com/Jorgeog25/prg1-22-23.git) | [Reto](https://github.com/Jorgeog25/prg1-22-23/blob/main/retos/entregas/jorgeOtero/retoCaracol/retoExtendidoCoches.java)
| Progra 2  | [Repositorio](https://github.com/Jorgeog25/progra2-22-23.git) | [Reto](https://github.com/Jorgeog25/progra2-22-23/tree/EX003Inheritance/ejercicios/entregas/jorgeOtero/EX003Inheritance)|
| EDA 1     | [Repositorio](https://github.com/Jorgeog25/23-24-eda1.git) | [Reto](https://github.com/Jorgeog25/23-24-eda1/tree/main/entregas/oteroJorge/Carrefour)|
| EDA 2     | [Repositorio](https://github.com/Jorgeog25/23-24-eda2.git) |

## 1. Nombres no descriptivos o ambiguos
| **Proyecto**      | **Archivo**              | **Líneas**  | **Elementos Afectados**              | **Recomendación**                                         |
|-------------------|--------------------------|-------------|--------------------------------------|-----------------------------------------------------------|
| Reto Caracol| [retoExtendidoCoches.java](https://github.com/Jorgeog25/prg1-22-23/blob/main/retos/entregas/jorgeOtero/retoCaracol/retoExtendidoCoches.java)| [6](https://github.com/Jorgeog25/prg1-22-23/blob/935e987fe1892c1e8d767eb2d09d667c63a2e8c0/retos/entregas/jorgeOtero/retoCaracol/retoExtendidoCoches.java#L6)| `subir` |  `metrosSubidos` |
| EX003Inheritance| [UserManager.java](https://github.com/Jorgeog25/progra2-22-23/blob/EX003Inheritance/ejercicios/entregas/jorgeOtero/EX003Inheritance/src/main/UserManager.java)|[10](https://github.com/Jorgeog25/progra2-22-23/blob/42ea7efa590e527e3e9ddbb8b754f31dd10f25d5/ejercicios/entregas/jorgeOtero/EX003Inheritance/src/main/UserManager.java#L10)| `userAdmin`| `isAdmin`|
| Carrefour| [GenerarCliente](https://github.com/Jorgeog25/23-24-eda1/blob/main/entregas/oteroJorge/Carrefour/src/core/GenerarCliente.java)||Nombre de la clase| `GeneradorCliente.java`|

## 2. Uso de Nombres Inconsistentes

| **Proyecto**      | **Archivo**              | **Líneas**  | **Elementos Afectados**              | **Recomendación**                                         |
|-------------------|--------------------------|-------------|--------------------------------------|-----------------------------------------------------------|
| Reto Caracol| [retoExtendidoCoches.java](https://github.com/Jorgeog25/prg1-22-23/blob/main/retos/entregas/jorgeOtero/retoCaracol/retoExtendidoCoches.java)| [5](https://github.com/Jorgeog25/prg1-22-23/blob/935e987fe1892c1e8d767eb2d09d667c63a2e8c0/retos/entregas/jorgeOtero/retoCaracol/retoExtendidoCoches.java#L5) y [26](https://github.com/Jorgeog25/prg1-22-23/blob/935e987fe1892c1e8d767eb2d09d667c63a2e8c0/retos/entregas/jorgeOtero/retoCaracol/retoExtendidoCoches.java#L26)| `coche` | Usar `probabilidadDeslizar`|
| EX003Inheritance| [Options.java](https://github.com/Jorgeog25/progra2-22-23/blob/EX003Inheritance/ejercicios/entregas/jorgeOtero/EX003Inheritance/src/main/Options.java)| [5-7](https://github.com/Jorgeog25/progra2-22-23/blob/42ea7efa590e527e3e9ddbb8b754f31dd10f25d5/ejercicios/entregas/jorgeOtero/EX003Inheritance/src/main/Options.java#L5)|`capacity`, `size` y `defaultSelection`| `maxItems`, `currentSize` y `selectedIndex`|
|Carrefour| [ColaClientes.java](https://github.com/Jorgeog25/23-24-eda1/blob/main/entregas/oteroJorge/Carrefour/src/core/ColaClientes.java)|[16](https://github.com/Jorgeog25/23-24-eda1/blob/b287e5eb8cff654aeb7819908fc59a2994a7868b/entregas/oteroJorge/Carrefour/src/core/ColaClientes.java#L16)|`obtenerSiguienteCliente`| Separar en `borrarCliente` y `obtenerSiguienteCliente`|

## 3. Problemas de Sintaxis 
| **Proyecto**      | **Archivo**              | **Líneas**  | **Elementos Afectados**              | **Recomendación**                                         |
|-------------------|--------------------------|-------------|--------------------------------------|-----------------------------------------------------------|
| Reto Caracol| [retoExtendidoCoches.java](https://github.com/Jorgeog25/prg1-22-23/blob/main/retos/entregas/jorgeOtero/retoCaracol/retoExtendidoCoches.java)| [47](https://github.com/Jorgeog25/prg1-22-23/blob/935e987fe1892c1e8d767eb2d09d667c63a2e8c0/retos/entregas/jorgeOtero/retoCaracol/retoExtendidoCoches.java#L47) | `for (int j = 0; j <= dimension; j = j + 1)`| `for (int j = 0; j <= dimension; j = j + 1){}`|
|EX003Inheritance| [Admin.java](https://github.com/Jorgeog25/progra2-22-23/blob/EX003Inheritance/ejercicios/entregas/jorgeOtero/EX003Inheritance/src/main/Admin.java)| [4](https://github.com/Jorgeog25/progra2-22-23/blob/42ea7efa590e527e3e9ddbb8b754f31dd10f25d5/ejercicios/entregas/jorgeOtero/EX003Inheritance/src/main/Admin.java#L4) y [9](https://github.com/Jorgeog25/progra2-22-23/blob/42ea7efa590e527e3e9ddbb8b754f31dd10f25d5/ejercicios/entregas/jorgeOtero/EX003Inheritance/src/main/Admin.java#L9)| `isAdmin`| La variable booleana nombrarla `adminRole`|
|Carrefour|



## 4. Métodos Repetitivos 
| **Proyecto**      | **Archivo**              | **Líneas**  | **Elementos Afectados**              | **Recomendación**                                         |
|-------------------|--------------------------|-------------|--------------------------------------|-----------------------------------------------------------|
| Reto Caracol| [retoExtendidoCoches.java](https://github.com/Jorgeog25/prg1-22-23/blob/main/retos/entregas/jorgeOtero/retoCaracol/retoExtendidoCoches.java)|
|EX003Inheritance| [Manager.java](https://github.com/Jorgeog25/progra2-22-23/blob/EX003Inheritance/ejercicios/entregas/jorgeOtero/EX003Inheritance/src/main/Manager.java) y [Options.java](https://github.com/Jorgeog25/progra2-22-23/blob/EX003Inheritance/ejercicios/entregas/jorgeOtero/EX003Inheritance/src/main/Options.java)| [24](https://github.com/Jorgeog25/progra2-22-23/blob/42ea7efa590e527e3e9ddbb8b754f31dd10f25d5/ejercicios/entregas/jorgeOtero/EX003Inheritance/src/main/Manager.java#L24 ) y [23](https://github.com/Jorgeog25/progra2-22-23/blob/42ea7efa590e527e3e9ddbb8b754f31dd10f25d5/ejercicios/entregas/jorgeOtero/EX003Inheritance/src/main/Options.java#L23) respectivamente| Metodo `add`| Crear clase abstracta|
|Carrefour| [GenericList.java](https://github.com/Jorgeog25/23-24-eda1/blob/main/entregas/oteroJorge/Carrefour/src/generica/GenericList.java#L22)|[22](https://github.com/Jorgeog25/23-24-eda1/blob/b287e5eb8cff654aeb7819908fc59a2994a7868b/entregas/oteroJorge/Carrefour/src/generica/GenericList.java#L22)| `return this.size() > 0 ? false : true;`| `return this.size() == 0;`|




## 5. Código no DRY (Don't Repeat Yourself)
| **Proyecto**      | **Archivo**              | **Líneas**  | **Elementos Afectados**              | **Recomendación**                                         |
|-------------------|--------------------------|-------------|--------------------------------------|-----------------------------------------------------------|
| Reto Caracol| [retoExtendidoCoches.java](https://github.com/Jorgeog25/prg1-22-23/blob/main/retos/entregas/jorgeOtero/retoCaracol/retoExtendidoCoches.java)| [17-25](https://github.com/Jorgeog25/prg1-22-23/blob/935e987fe1892c1e8d767eb2d09d667c63a2e8c0/retos/entregas/jorgeOtero/retoCaracol/retoExtendidoCoches.java#L18) | Repetición del calculo del metodo subir | Extraerlo en un metodo externo|
|EX003Inheritance| [User.java](https://github.com/Jorgeog25/progra2-22-23/blob/EX003Inheritance/ejercicios/entregas/jorgeOtero/EX003Inheritance/src/main/User.java)|[16-32](https://github.com/Jorgeog25/progra2-22-23/blob/42ea7efa590e527e3e9ddbb8b754f31dd10f25d5/ejercicios/entregas/jorgeOtero/EX003Inheritance/src/main/User.java#L16)| Ambos contructores | Llamar desde el contructor con parametros al vacio `public User() {this("user", "password", "User");}`|
| Carrefour | [CentroComercial.java](https://github.com/Jorgeog25/23-24-eda1/blob/main/entregas/oteroJorge/Carrefour/src/core/CentroComercial.java)| [25-51](https://github.com/Jorgeog25/23-24-eda1/blob/b287e5eb8cff654aeb7819908fc59a2994a7868b/entregas/oteroJorge/Carrefour/src/core/CentroComercial.java#L25)| `System.out.println("MINUTO " + i + " - " + "LLega un cliente nuevo" + " - " + "En Cola: " + clientes.size());`| Sacarlo a otro método porque se vuelve a usar|

## 6. Falta de encapsulación 
| **Proyecto**      | **Archivo**              | **Líneas**  | **Elementos Afectados**              | **Recomendación**                                         |
|-------------------|--------------------------|-------------|--------------------------------------|-----------------------------------------------------------|
| Reto Caracol| [retoExtendidoCoches.java](https://github.com/Jorgeog25/prg1-22-23/blob/main/retos/entregas/jorgeOtero/retoCaracol/retoExtendidoCoches.java)|
|EX003Inheritance| [Manager.java](https://github.com/Jorgeog25/progra2-22-23/blob/EX003Inheritance/ejercicios/entregas/jorgeOtero/EX003Inheritance/src/main/Manager.java)|[10](https://github.com/Jorgeog25/progra2-22-23/blob/42ea7efa590e527e3e9ddbb8b754f31dd10f25d5/ejercicios/entregas/jorgeOtero/EX003Inheritance/src/main/Manager.java#L10)| `public selectedOption`| Hacerlo privado|
|Carrefour| 

