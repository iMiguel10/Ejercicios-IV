# Ejercicios Tema Introductorio
---

### 1. Consultar en el catálogo de alguna tienda de informática el precio de un ordenador tipo servidor y calcular su coste de amortización a cuatro y siete años. Consultar este artículo en Infoautónomos sobre el tema.

Un ordenador de tipo servidor está rondando el precio de unos 800€.  
Equipos para tratamiento de la información y sistemas y programas informáticos tienen un coeficiente de estimación del 26%.

Entonces:
    
* Coste amortización 4 años --> 832 €
* Coste amortización 7 años --> 1456 €
 
---


### 2. Usando las tablas de precios de servicios de alojamiento en Internet “clásicos”, es decir, que ofrezcan Virtual Private Servers o servidores físicos, y de proveedores de servicios en la nube, comparar el coste durante un año de un ordenador con un procesador estándar (escogerlo de forma que sea el mismo tipo de procesador en los dos vendedores) y con el resto de las características similares (tamaño de disco duro equivalente a transferencia de disco duro) en el caso de que la infraestructura comprada se usa sólo el 1% o el 10% del tiempo.

---

### 3. En general, cualquier ordenador con menos de 5 o 6 años tendrá estos flags. ¿Qué modelo de procesador es? ¿Qué aparece como salida de esa orden? Si usas una máquina virtual, ¿qué resultado da? ¿Y en una Raspberry Pi o, si tienes acceso, el procesador del móvil?

Orden: `egrep '^flags.*(vmx|svm)' /proc/cpuinfo`  
El procesador es:  Intel(R) Core(TM) i7-4720HQ CPU @ 2.60GHz  
![Salida de la orden](https://github.com/iMiguel10/Ejercicios-IV/blob/master/Ejercicios%20Tema%20Introductorio/Ejercicio3.PNG)

---

### 4.1. Comprobar si el núcleo instalado en tu ordenador contiene este módulo del kernel usando la orden kvm-ok.
 Si hago `kvm-ok` sale:  

> INFO: /dev/kvm does not exist  
> HINT:   sudo modprobe kvm_intel  
> INFO: For more detailed results, you should run this as root  
> HINT:   sudo /usr/sbin/kvm-ok  

Si hago esto `sudo modprobe kvm_intel` o `sudo /usr/sbin/kvm-ok`  :  
> modprobe: ERROR: ../libkmod/libkmod.c:586 kmod_search_moddep() could not open moddep file '/lib/modules/4.4.0-17134-Microsoft/modules.dep.bin'  
> modprobe: FATAL: Module kvm_intel not found in directory /lib/modules/4.4.0-17134-Microsoft
---
