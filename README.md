# Descripci�n de la implementaci�n

Se utiliza Maven y Java 1.8 para la implementaci�n, adem�s de las siguientes librer�as:

- gson-2.8.6
- Generador_Datos_Desafio_Tres-1.0.0

# Compilar y ejecutar el proyecto

Para compilar el proyecto se requiere Java y Maven instalado.
Ingresar al directorio *Desafio_Tres* ejecutar el siguiente comando *maven*

```bash
mvn clean package
```

Luego de compilar el proyecto ingresar al directorio *target* ejecutar el siguiente comando *java*

```bash
java -cp ufs-faltantes.jar:lib/* com.github.maraya.ufs.UfsFaltantes
```

Si se requiere que la salida sea a un archivo, ejecutar:

```bash
java -cp ufs-faltantes.jar:lib/* com.github.maraya.ufs.UfsFaltantes > archivo.txt
```