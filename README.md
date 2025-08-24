# ArbolBinario

Implementación de un árbol binario en JavaScript.

## Descripción

Este proyecto proporciona una estructura de datos de árbol binario, con operaciones básicas como inserción, búsqueda y recorrido. Puede ser utilizado como base para estructuras más complejas como árboles binarios de búsqueda, AVL, etc.

## Instalación

Clona este repositorio:

```bash
git clone https://github.com/rbxus8/ArbolBinario.git
```

Navega al directorio:

```bash
cd ArbolBinario
```

## Uso

Ejemplo básico de uso:

```js
const { ArbolBinario } = require('./ArbolBinario');

// Crear un nuevo árbol binario
const arbol = new ArbolBinario();

// Insertar elementos
arbol.insertar(10);
arbol.insertar(5);
arbol.insertar(15);

// Buscar un elemento
const encontrado = arbol.buscar(5);

// Recorrido en orden
arbol.recorrerInOrden((valor) => {
  console.log(valor);
});
```

## Funcionalidades

- Inserción de nodos
- Búsqueda de valores
- Recorridos (inOrden, preOrden, postOrden)

## Contribución

¡Las contribuciones son bienvenidas! Por favor, abre un Issue o Pull Request para sugerencias o mejoras.
