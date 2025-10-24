# COMPLETAR  
Comparando sus conocimientos antes de hacer la práctica con sus conocimientos después de hacer la tarea, explicar los principales aprendizajes logrados para beneficio de su formación profesional.  
Si solucionó un problema presentado al realizar la práctica también se debe documentar.

La limitación de recursos es algo de suma importancia en la virtualización de sistemas, pues realmente los recursos de hardware son limitados en la mayoría de casos y eso afecta al host. Una gran ventaja de docker es que de por si ya son entornos optimizados, a diferencia de las maquinas virtuales, pero aún así docker permite limitar los recursos de hardware para tener mayor eficiencia al momento de crear contenedores. Por lo que permite llevar un mayor control sobre lo que estamos utilizando. 

Otro punto importante es tener la capacidad de utilizar los dockerfile estos realmente facilitan la creación de imágenes y contenedores, pues se puede personalizar las imágenes y tenerlas listas para cuando las necesitemos. Realmente una gran ventaja.

Un problema que ocurrió fue en el apartado de dockerfile, pues se pedía ejecutar el dockerfile pero este dió un erro y eso se debía a que la imágen utilizada de base (Centos 7) ya no estaba disponible debido a que cumplió con su vida útil, entonces se busco otras alternativas como lo fue la utilización de otra imágen (RockyLinux 8) que levante el servicio que se requería para la práctica.
