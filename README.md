# Petriflow application for road transport companies

## Description
The application purpose is to simplify company inter-processes and new inter-process functionality to be provided. The designed and implemented solution uses Petriflow technology. The process-driven application is divided into 3 entity and 5 functional processes. These processes are modeled by Petri nets and implemented by Petriflow language. The final product of our development process are XML files, which can be used in combination with the application engine to create a fully functional process-driven application.

#### Functionality
- Evidence of vehicles and their management
- Evidence of services and their management
- Evidence of tasks and their management
- Notifications of records


## Installation
Assume you have an instance of Netgrif Application Engine (NAE) running. A free instance can be found on demo.netgrif.com.

1. Replace group id with your group id in every process file. Search and replace `5faffef90a975a1b77c9b54a`. 
For example in [serviceConroller.xml](https://github.com/Retoocs/road_transport/blob/develop/processes/serviceController.xml):
    ```sh
    createCase("<your-group-id>_service")
    ```
    > Id of your group can be found in the NAE: **"Groupmanagement -> Group info"**
2. Import XML files. In the NAE click on **"Processes"** and on the lower right corner upload icon.
3. Add new group members and set their roles

## Usage
Public Netgrif Application Engine documentation can be found [here](https://netgrif.atlassian.net/wiki/spaces/NAE).
##### New user
1. Add dashboard by clicking on plus icon on upper right corner.
2. Start working

## Development
A public Petriflow documentation can be found [here](https://netgrif.atlassian.net/wiki/spaces/PF).

## License
MIT