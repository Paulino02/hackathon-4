## Execução do ReplicaSet
![alt text](imagem.png)
## Exclusão de um dos pods e auto-healing
![alt text](imagem1.png)
## "auto-healing" ou "autorepair"
No contexto do Kubernetes, quando um pod é excluído manualmente e isso quebra o estado desejado definido pelo replicaset, o controlador do replicaset detecta essa discrepância e automaticamente cria um novo pod para substituí-lo, restaurando assim o estado desejado. Isso faz parte do mecanismo de garantia de estado desejado do Kubernetes.