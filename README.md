Integrating Design Patterns in a Project Scenario
  Tasks
    Design Problem Solving:
    Scenario Description: Participants are provided with a series of common software design challenges. They will need to choose appropriate design patterns to solve these specific problems effectively.
      Design Challenges:
        Global Configuration Management: 
        Design a system that ensures a single, globally accessible configuration object without access conflicts.

        Patrón Singleton
        Se aplica el patron singleton dando un ejemplo de configuración el creo se opto porque es el adecuado que emular un patron singleton.
<img width="523" alt="Captura de pantalla 2024-05-30 a la(s) 5 42 58 p m" src="https://github.com/KarlaPR10/Lab7/assets/138635602/97e505c1-02a7-417e-a120-da1e6d37bc05">

<img width="559" alt="Captura de pantalla 2024-05-30 a la(s) 6 00 47 p m" src="https://github.com/KarlaPR10/Lab7/assets/138635602/6e8aeb4a-da0a-4b26-8ec5-954ef98c9b70">

  Dynamic Object Creation Based on User Input: Implement a system to dynamically create various types of user interface elements based on user actions. 

  <img width="620" alt="Captura de pantalla 2024-05-30 a la(s) 7 02 05 p m" src="https://github.com/KarlaPR10/Lab7/assets/138635602/fabe8b59-1fbf-4c93-acff-25051e181e76">
<img width="765" alt="Captura de pantalla 2024-05-30 a la(s) 7 02 10 p m" src="https://github.com/KarlaPR10/Lab7/assets/138635602/a0a76bbd-87ca-4866-a5e7-cb4f6cd12e0a">

 State Change Notification Across System Components: Ensure components are notified about changes in the state of other parts without creating tight coupling.
              
    En este ejemplo, la clase Evento representa un evento que se puede publicar en el bus de eventos. La clase EventSubscriber representa un componente que puede suscribirse a eventos específicos. La clase Componente publica el evento en el bus de eventos cuando cambia su estado.Al utilizar este enfoque, los componentes pueden notificarse entre sí sobre cambios en su estado sin crear un acoplamiento estrecho entre ellos.

  <img width="941" alt="Captura de pantalla 2024-05-31 a la(s) 9 09 24 a m" src="https://github.com/KarlaPR10/Lab7/assets/138635602/b81daa45-360c-4eda-a2db-b91d7d13f44c">


 Efficient Management of Asynchronous Operations: Manage multiple asynchronous operations like API calls which need to be coordinated without blocking the main application workflow.
          
           En este ejemplo, creamos un grupo de subprocesos con 5 subprocesos utilizando el método Executors.newFixedThreadPool(5). Luego enviamos 10 solicitudes de API al grupo de subprocesos utilizando el método executor.submit(). Las solicitudes de API se ejecutan de forma simultánea y asincrónica, lo que permite que el flujo de trabajo de la aplicación principal continúe ejecutándose sin bloquearse.

 <img width="600" alt="Captura de pantalla 2024-05-31 a la(s) 9 35 54 a m" src="https://github.com/KarlaPR10/Lab7/assets/138635602/9884f5df-d379-4414-a5e9-fc04b18cc7ed">

     
