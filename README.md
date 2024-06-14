# Repo de Trabajo Final Modbus_TCP

## Uso del repositorio

Por ahora el pre-commit está desactivado 14-06-24

Este repositorio utiliza [pre-commit](https://pre-commit.com) para validaciones de formato. Para trabajar con el mismo usted debería tener instalado:

1. pre-commit (https://pre-commit.com/#install)

GA: En Ubuntu sudo apt install pre-commit

Después de clonar el repositorio usted debería ejecutar el siguiente comando:

GA: esto es para los hooks adentro del repositorio

```
pre-commit install
```

Para generar la documentación del proyecto se utiliza el siguiente comando:

```
make doc

```

Para compilar el proyecto se utiliza el siguiente comando:

```
make all

```

## License

This work is distributed under the terms of the [MIT](https://spdx.org/licenses/MIT.html) license.
