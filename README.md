## manualTesting

Paso 1. Clonar el repositorio:

## Backend API

# Acceder y seguir los pasos del manual

   ```bash
   git clone https://github.com/Vhenrry/apiProductosTest.git
   ```
*Seguir el manual de configuracion

# Instala las dependencias

   ```bash
   npm install
   ```

# Ejecutar el comando

   ```bash
   npm run start
   ```

Paso 2. Clonar el repositorio:

## Frontend

# Acceder y seguir los pasos del manual

   ```bash
   git clone https://github.com/Vhenrry/final_proyec.git
   ```

*Seguir el manual de configuracion

# Instala las dependencias

   ```bash
   npm install
   ```

# Ejecutar el proyecto

   ```bash
   npm start dev
   ```

## Inplementacion de cypress abrir para ejecutar los ejercicios

   ```bash
   npx cypress open
   ```

## Automatización de Flujos Críticos

1. Login
   Autologin.spec.cy.ts

2. Crear Producto
   CrearProducto.spec.cy.ts
3. Editar Producto
   EditarProducto.spec.cy.ts

4. Eliminar Producto
   EliminarProducto.spec.cy.ts

5. Crear, Verificar y eliminar un producto
   VerificacionProductoYeliminacion.spec.cy.ts

## Automatización de Flujos alternos

1. Crear Producto
   LoginFail.spec.cy.ts

2. Crear producto sin precio sale error se corrige se verifica y se elimina
   ErrorCrearProducto.spec.cy.ts
3. Creacion doble de un producto se requiere correccion
   Autologin.spec.cy.ts
