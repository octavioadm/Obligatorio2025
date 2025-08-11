1- Que es Ansible? Mencione dos actividades que se pueden hacer con Ansible
2- Que es un playbook de Ansible?
3- Que informacion contiene un inventario de Ansible
4- Explique que es un modulo de Ansible y de un ejemplo
5- Que ventajas tiene Ansible sobre otros metodos de automatizacion?

1)_ Ansible es una herramienta de automatizacion de codigo abierto. Es multiplataforma, lo que permite 
automatizar diversas tareas utilizando scripts sencillos y legibles llamados playbooks.
Algunos de los casos mas comunes de uso son:
	- Administrar y mantener la configuracion del sistema
	- Implementacion software

2)_ Los playbooks son archivos con extencion .yaml o .yml de automatizacion que Ansible utiliza para 
ejecutar determinadas tareas de uno o varios nodos de un inventario.

3)_ El inventario de Ansible es un archivo que centraliza los diferentes nodos de la red, como tambien
su ubicacion. Tambien permite crear grupos de nodos, lo que facilita la gestion y automatizacion 
permitiendo ejecutar tareas de manera mas eficiente.

4)_ Un modulo de Ansible es un componente que realiza tareas especificas en los nodos.
Existen multiples modulos dependiendo la tarea que se quiera realizar, a su vez se puede invocar un unico modulo 
con una tarea especifica o varios diferentes en un mismo playbook.

5)_ A diferencia de otros metodos de automatizacion, Ansible se destaca por:
	- no requerir la instalacion de agentes en los equipos a gestionar.
	- Facilidad de aprendizaje ya que utiliza YAML para definir las tareas
	- Contiene una documentacion amplia y con ejemplos claros
	- Reduccion de costos al ser de codigo abierto no requiere licencia como otras herramientas propietarias
	- Integracion con sistema de gestion de versiones como Git.	
