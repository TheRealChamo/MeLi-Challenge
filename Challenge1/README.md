# MeLi - Challenge #

Dado un archivo CSV conteniendo nombre, apellido y correo electrónico de usuarios, desarrollar un sistema que lo lea y cree cuentas y password en OpenLDAP. La password deben ser del tipo random y debe ser enviada, junto con el nombre de usuario, por correo electrónico.

Al ingresar el usuario, se le debe solicitar cambio de contraseña. El estado de todos los usuarios debe ser guardado en una base de datos MySQL o MongoDB junto con su password almacenada en forma segura.