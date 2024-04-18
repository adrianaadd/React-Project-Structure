# React-Project-Structure

## ¿Cómo puedo crear mi proyecto React?

```bash
npm create vite@latest my-react-app -- --template react
```

| **File**       | **Description e instalación**                                             | **Uso**                                                                                                                             |
|----------------|----------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------|
| *Es7 + React*  | Nos permite ejecutar snippets muy útiles.                                 | Snippets para la estructura básica de un componente: `rfce`                                                                        |
| *Prettier*     | Ayuda a tener el código bien formateado.                                  | - Instalar extensión y añadir un archivo `.prettierrc` con la configuración:<br>`{"singleQuote": true, "semi": false}`              |
| *ESLint*       | ESLint se encarga de la calidad del código.<br><br>Nos avisará si tenemos variables sin usar, si usamos la sintaxis adecuada para exportar, etc. Puedes modificar sus reglas como prefieras. | - Instalar la extensión ESLint.<br>- Instalar la librería `eslint-config-prettier`.<br>- Añadir la siguiente configuración al archivo `eslintrc.cjs`:<br>`"eslintConfig": { "extends": [ "react-app", "react-app/jest", "prettier" ] }` |
| *Carpetas*     | -components<br>-page<br>-router                                                    |                                                                                                                                     |
| *React Router*  | Nos permite navegar entre rutas,personalizarlas,restringirlas,etc....                                 |  npm install react-router-dom@6                                                                      |
