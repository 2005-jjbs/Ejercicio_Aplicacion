# CU01 – Completar Registro de Usuario

Actor: Usuario recién autenticado

## Guion (Curso normal de eventos)

1. El usuario ingresa al sistema utilizando sus credenciales institucionales.
2. El sistema detecta que es el primer ingreso del usuario.
3. El sistema redirige automáticamente al formulario de registro complementario.
4. El usuario selecciona su tipo de vinculación (estudiante, profesor, administrativo).
5. El usuario selecciona su facultad o departamento.
6. El usuario ingresa su número de identificación.
7. El usuario ingresa su número de teléfono.
8. El usuario acepta los términos y condiciones.
9. El sistema valida que todos los campos obligatorios estén diligenciados y cumplan las reglas establecidas.
10. Si la información es correcta, el sistema guarda los datos en el perfil del usuario.
11. El sistema redirige al usuario al dashboard principal.

---

## Excepciones (Caminos alternos)

**E1 – Usuario ya tiene registro complementario**  
2.1. El sistema redirige al dashboard principal sin mostrar el formulario.  
2.2. Termina.

**E2 – Campos obligatorios incompletos**  
9.1. El sistema muestra un mensaje indicando qué campo falta por completar.  
9.2. El sistema no permite continuar.  
9.3. Termina.

**E3 – Datos inválidos (formato o tipo incorrecto)**  
9.1. El sistema resalta el campo inválido y muestra un mensaje de corrección.  
9.2. El flujo continúa cuando el usuario corrige el dato.

---

## Postcondición

- El usuario queda con un perfil completamente registrado y habilitado para usar el Marketplace.

> [Regresar al diagrama](../casos-de-uso.md)
