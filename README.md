## **EASY-WORK1**
### Curso: Gestión de la Configuración
### Docente: Lenis Rossi Wong Portillo

**Grupo 3**

#### Integrantes:

|    Apellidos     |       Nombres      |     Codigo     |
| ---------------- | ------------------ | -------------- |
| Diaz Pillaca     | Sebastian Alexis   |   20200259     |
| Diaz Pinedo      | Jordan Antony      |   14200187     |
| Mauricio Montes  | Jorge Luis         |   20200048     |
| Perez Sotomayor  | Alejandro Nicolás  |   20200280     |
| Saenz Cuevas     | Leonardo Rodolfo   |   20200026     |
| Tambillo Borja   | Mauro Junior       |   20200295     |
| Wong Gómez       | Carlos Augusto     |   14160018     |

# Flujo de trabajo

1. Cada colaborador del proyecto contara con su propia rama, creada usando sus dos apellidos juntos y en minuscula.
2. Cada colaborador deberá fusionar **master** a su respectiva rama personal, para así poder trabajar de forma colaborativa la parte que le corresponda.

	#### Pasos por linea de comando:
		# Cambiarse a la rama master y realizar un pull para actualizarla.
		git switch master
		git pull origin master
		
		# Regresar a su rama de trabajo personal.
		git switch nombreDeSuRama
		
		# Fusionar master a su rama personal.
		git merge master
		 
3. Pasos para guardar sus cambios en su rama

	#### Pasos por linea de comando:
		# Incluir cambios en el siguiente commit
		git add .
	
		# Guardar los cambios en el repositorio local
		git commit -m "descripción del cambio"

		* Guardar los cambios en el repositorio remoto
		git push 
		
4. Por ultimo deberá fusionar nuevamente los cambios de su rama personal a la rama **master**
	#### Pasos por linea de comando:
		# Posicionarse en la rama master
		git fetch
		git pull origin master
		git merge NombreDeSuRama	
