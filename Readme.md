Los archivos a verificar se colocan dentro de la carpeta "files", se modifica el archivo input, con los hashes previos y el nombre de los ficheros a verificar.

Por ultimo se lanza el script check.sh y de encontrar algun inconveniente, levanta una alarma:

md5sum: WARNING: 1 computed checksum did NOT match


para este ejercicio en particular, el único archivo modificado fue : "log.txt", los otros archivos, poseen el mismo hash, previo a la intrusión
