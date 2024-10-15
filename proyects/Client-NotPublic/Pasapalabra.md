[↩ Volver al listado de trabajos](https://github.com/FunkyoEnma#proyectos-realizados-y-en-proceso)

# Descripción [![](https://img.shields.io/badge/-python-3776AB?logo=python&logoColor=white&style=flat)](https://github.com/search?q=+language%3APython++org%3AFunkyoEnma+&type=repositories) [![](https://img.shields.io/badge/-qt-41CD52?logo=qt&logoColor=white&style=flat)](https://github.com/search?q=+language%3APython++org%3AFunkyoEnma+&type=repositories)

Programa para eventos de pasapalabra desarrollado con python, consta de dos partes: 

- Una aplicación de ventana que controla los valores
- Dos paginas para usar como fuente de navegador en el O.B.S.

**Version:** 1.1.0
**Binario del programa:** Este no será liberado hasta que el cliente lo autorice
**Codigo fuente:** Este no será liberado hasta que el cliente lo autorice
**Cliente:** Anonimo por el momento

# Fuentes de navegador

- **Ruleta de letras:** Muestra las letras en forma de ruleta, se selecciona la letra actual, se puede mover hacia adelante y hacia atrás y se puede marcar como correcta o incorrecta
  ![image](https://github.com/user-attachments/assets/ef6b1901-d525-4496-92b6-97f79cfc2a17)

- **Ahorcado:** Muestra un "ahorcado" con base en los errores cometidos hasta un máximo de 7
  
  | 5 Errores | 7 Errores |
  |----|-----|
  | ![image](https://github.com/user-attachments/assets/d91a6a70-a7c6-4ea9-959b-5fb07515409c) | ![image](https://github.com/user-attachments/assets/0073b875-56b1-4c61-903e-abe52c40c826) |

# Configuración

Ventana de configuración, aqui se puede modificar la tecla para reiniciar y la tecla para cada opción (Anterior, Siguiente, Ok, Error) y los colores de OK y de ERROR

![image](https://github.com/user-attachments/assets/d904ded3-2656-465a-824b-a818dce3d206)

La configuración se guarda en '~\\.FunkyoEnmaDev\pasaPalabra', sin envargo se recomienda no cambiarla directamente dentro de está ya que las teclas se guardan en su valor númerico para pyqt

# Errores conocidos
Estos errores etán programados para corrección en las siguientes versiones de arreglos de erores

- ⭐ Si se cambia la configuración y se intenta reiniciar se estanca en reload...
- En caso de no tener una tecla seleccionada en la configuración en vez de none aparece color0
- La applicación no viene con configuraciónes default para las teclas
