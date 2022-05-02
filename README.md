# Módulo 6: Django

***Liliana Garmendia***

La aplicación labtienda  consta de una landing page del laboratorio, y además permite iniciar sesión o crear una cuenta. Si inicias sesión tienes acceso a ver la lista de clientes, agregar nuevos clientes mediante formulario de registro.
Además tiene restringido el acceso a páginas usando los decoradores @login_required y @staff_member_required, este último usado para restringir el acceso a ver la lista de clientes y agregar nuevos clientes.