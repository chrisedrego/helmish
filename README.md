# helmish
Everything about Helmish (Helm)

- Helm is package manager for Kubernetes
- When building up and application it involves alot of interdependent components which contain separate yaml files which contain information about the same, 
- You can bundle all the dependencies together in a helm chart which contains everything in a sort of package
- Helm is part of Kubernetes and funded by Cloud Native Foundation
- All major programming language have a package manager which is responsible for the maintenance , creation of the packages in the application.
- Helm is used to Install Software, Automatically Install Software Dependencies, upgrade 
- helm provides the command line tool called as "helm"

- Helm basically has the two components
    - helm CLI which is used to send request
    - tiller which is a server side component.

- Tiller keeps on listening to the request from the Helm for any request and then goes ahead and process the request.
- helm as we already know is package manager, the package in helm is called a chart.

- Chart can be termed as bundle that contains the components which are present.


- Chart contains the below stuff:
    - charts/
    - templates/


- Each Directory has use case:
    - charts: 
        - Manually has the dependencies laid out
    
    - chart.yaml
        - contains the details of name, version and other details of the charts
    - requirments.yaml
        - contains the charts depedencies
        