# Modelado de Comportamiento en Sistemas de E-commerce

# 

# **1\. Investigación** 

El proceso modelado representa el flujo de compra en un sistema de e-commerce.

 El usuario selecciona productos, realiza el pago y el sistema valida la información de compra.  
 Se utilizan Decision Nodes para determinar si el pago fue aprobado o rechazado y mediante Fork Nodes, el sistema ejecuta procesos paralelos como la actualización del inventario y el envío de la confirmación por correo.

En omg

Dentro de la página:

* sección **“Specification Documents”**  
* documento oficial PDF de UML 2.5.1.

La especificación oficial define los diagramas de actividad y sus nodos de control.  
 En UML 2.5.1:

* los **Decision Nodes** sirven para seleccionar un único flujo entre varias alternativas, \-pág 432  
* los **Fork Nodes** permiten dividir el flujo en varios procesos paralelos.-pág 430

**En IBM:** 

**La diferencia principal es:**

* **Decision Node** → solo se elige un camino.  
* **Fork Node** → se ejecutan varios caminos simultáneamente.

**En paradigm:**

* el **Decision Node** se usa para bifurcar el flujo según condiciones;  
* el **Fork Node** se utiliza para representar concurrencia o paralelismo.  
  —------------------------------------------------------------------------------------------------  
  **Se utilizaron Fork Nodes** porque después de aprobar el pago, el sistema debe ejecutar simultáneamente varias tareas independientes, como actualizar el inventario y enviar la confirmación al cliente.

   **Los Decision Nodes** se emplearon para modelar condiciones lógicas, como la validación del pago, donde únicamente puede continuar un flujo dependiendo del resultado obtenido.


  

**Webgrafía:**

\[1\] Object Management Group, “OMG Unified Modeling Language (OMG UML), Version 2.5.1,” Dec. 2017\. \[Online\]. Disponible: [https://www.omg.org/spec/UML/](https://www.omg.org/spec/UML/)\[Accedido: 12-May-2026\].

\[2\] IBM, “Control nodes in UML activity diagrams.” \[Online\].Disponible:[https://www.ibm.com/docs/en/rhapsody/9.0.1?topic=diagrams-uml-activity](https://www.ibm.com/docs/en/rhapsody/9.0.1?topic=diagrams-uml-activity) \[Accessed: 12-May-2026\].

\[3\] Visual Paradigm, “Decision Node vs Fork Node in Activity Diagram.” \[Online\]. Disponible[https://www.visual-paradigm.com/guide/uml/what-is-activity-diagram/](https://www.visual-paradigm.com/guide/uml/what-is-activity-diagram/):. \[Accedido: 12-May-2026\].

