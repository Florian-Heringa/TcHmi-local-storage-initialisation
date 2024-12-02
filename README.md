# (TcHmi) Local Storage Initialisation

The TwinCAT HMI allows the use of internal parameters to store setup information on the client side. Usually persitent data should be stored on the server, if it is necessary that it it shared between instances. However, when data needs to be unique per client, this can be achieved with internal variables.

Internal variables make use of the browser local storage. For more details, please read the provided file in this repository: `LocalStorageInit - Instructions.pdf`.

In this example the local storage is used to initialise a specific page to show whenever the system is started.