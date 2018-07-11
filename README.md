# hygieia-k8s-cluster
  Hygieia Dashboard Clusterized on Kubernetes

# Mainteners
 - [Júlio Pedrosa](https://github.com/japm94)

# Description
 ![Image](https://github.com/ahlp/catalog-service/blob/master/csd-base-description.jpg)
 - [Tech Report](https://github.com/ahlp/catalog-service/blob/master/doc/Tech_Report.pdf)
## Hygieia UI
 - A UI (Interface do usuário) é o front-end do Hygieia e contém todos os elementos da interface gráfica do usuário (GUI) para exibição pelos usuários. É aqui que os usuários também podem configurar o painel.
## Hygieia API
 - A Hygieia API contêm todos os serviços típicos da API REST que funcionam com os dados do sistema de origem (coletados por tarefas de serviço) e a Internet. As APIs de auditoria da Hygieia são uma coleção de terminais da API que servem para auditar dados de CI / CD coletados pelos coletores da Hygieia. 
## k8s PODS
 - Collectors (Coletores e/ou plugins) e demais microserviços implantados em PODs
## Persistence
 - Persistence Volume Claim, onde é feito mount para o armazenamento do MongoDB
## DevOps Tools
 - Essa camada envolve a grande quantidade de ferramentas de DevOps em um pipeline de CI / CD. No diagrama, Phabricator, Jenkins, Sonar e Nexus são listados como exemplos.
 
# Deploy

## How To
    
    cd hygieia-k8s/
    kubectl create -f ./

# Dependencies
 - https://www.docker.com/
 - https://kubernetes.io/
