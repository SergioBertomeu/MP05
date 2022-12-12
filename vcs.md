# Control de versions a IntelliJ:

IntelliJ té un control de versions integrat i, a més, deixa integrar-ne altres com GitHub.

## Control a IntelliJ


## Integració amb GitHub:

Per integrar IntelliJ amb GitHub hem de seguir els següents passos:

1. Crear un Token a GitHub, a [https://github.com/settings/tokens](https://github.com/settings/tokens).

Heu de seleccionar gist i repo al crear el token i possar-li un nom, **copieu el codi**.

![image](https://user-images.githubusercontent.com/110727546/207140573-c9b7e253-d63f-4184-8b4a-87bd9bb3be3d.png)

2. Afegir el nostre compte de Github a IntelliJ, a File->Settings->Version Control->GitHub

![image](https://user-images.githubusercontent.com/110727546/207140191-d0a6fb77-832e-4fdb-8895-62442507f467.png)

Aquí afegim el nostre mail i el Token que hem generat abans.

3. A la web de GitHub creem un repositori nou i copiem la seva URL HTTPS. 

![image](https://user-images.githubusercontent.com/110727546/207141982-b5a57486-d79b-4434-9926-4d6c78d8b824.png)

4. Ara a VCS->Git->Push definim origen amb la URL anterior:

![image](https://user-images.githubusercontent.com/110727546/207142395-bb0a2245-c814-49c7-9192-380e2b128f61.png)


![image](https://user-images.githubusercontent.com/110727546/207142260-4080a46d-dd6e-404c-81bd-c47b83065969.png)


Ara al menu de Git podrem fer les comandes típiques de Git des de IntelliJ: Commit, Comparar amb el repositori, mostrar historial, fer push, pulls, etc...



