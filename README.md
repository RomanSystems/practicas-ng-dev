# PROYECTOS

Labrotario de practicas full stack - dev frontend\
Para probar cada proyecto se debe clonar el repositorio actual con
```bash
git clone https://github.com/RomanSystems/practicas-ng-dev.git
```

Una vez clonado, debemos ir al proyecto
```bash
cd to-do-list
```

Actualizar los repositorios anclados
```shell
git submodule update --init --recursive
```

![proyectos.png](miscelanius/proyectos.png)

# Cambio de manejador de paquetes de npm a bun
![package-manager.png](miscelanius/package-manager.png)

Instalar bun (si fuese necesario ir a su página oficial)
```shell 
# En MacOs / Linux
curl -fsSL https://bun.sh/install | bash
```

```shell 
# En windows
powershell -c "irm bun.sh/install.ps1|iex"
```

# Instalar el node_modules
```shell
bun install
```

# Iniciar proyecto
```shell
bun start
```

Resultado

TODO LIST
![to-do.png](miscelanius/to-do.png)

CATALOG PRODUCT
![catalog-product.png](miscelanius/catalog-product.png)

MY BLOG
![my-blog.png](miscelanius/my-blog.png)