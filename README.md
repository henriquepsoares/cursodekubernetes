# ☸️ Introdução ao Kubernetes

![Kubernetes](https://upload.wikimedia.org/wikipedia/commons/3/39/Kubernetes_logo_without_workmark.svg)

O **Kubernetes (K8s)** é uma plataforma de **orquestração de contêineres** open source que automatiza a implantação, o dimensionamento e o gerenciamento de aplicações em contêineres. Ele é amplamente usado para gerenciar ambientes de microserviços em nuvem.

---

## 🚀 Vantagens do Kubernetes

- **Orquestração de containers**: Automatiza deploys, escala e gerenciamento de containers.  
- **Alta disponibilidade**: Detecta falhas e reinicia containers automaticamente.  
- **Escalabilidade**: Aumenta ou diminui recursos de forma automática.  
- **Portabilidade**: Funciona em qualquer ambiente que suporte containers.  
- **Comunidade ativa**: Suporte global e amplo ecossistema de ferramentas.

---

## 🐳 Conceitos principais

| Conceito        | Descrição                                               |
|-----------------|---------------------------------------------------------|
| **Pod**         | Unidade básica de execução no Kubernetes, pode conter um ou mais containers. |
| **Node**        | Máquina (física ou virtual) que executa pods.          |
| **Cluster**     | Conjunto de nodes gerenciados por um master control plane. |
| **Service**     | Expõe aplicações em pods para comunicação interna ou externa. |
| **Deployment**  | Gerencia a criação e atualização de pods de forma declarativa. |
| **Namespace**   | Agrupamento lógico de recursos para organização e isolamento. |

---

## 💡 Comandos básicos do Kubernetes (kubectl)

| Comando                       | Função                                           |
|--------------------------------|-------------------------------------------------|
| `kubectl get pods`            | Lista todos os pods no cluster                  |
| `kubectl describe pod <nome>` | Mostra detalhes de um pod                        |
| `kubectl logs <nome-pod>`     | Exibe logs de um pod                             |
| `kubectl apply -f arquivo.yaml` | Cria ou atualiza recursos a partir de um YAML |
| `kubectl delete -f arquivo.yaml` | Remove recursos a partir de um YAML           |
| `kubectl get nodes`           | Lista os nodes do cluster                        |
| `kubectl scale deployment <nome> --replicas=N` | Escala a quantidade de pods |

---

## 🌐 Arquitetura do Kubernetes

1. **Master / Control Plane**  
   - API Server, Scheduler, Controller Manager, etcd  

2. **Nodes / Worker Nodes**  
   - Kubelet, Kube-proxy, Pods com containers  

3. **Networking & Services**  
   - Comunicação entre pods, serviços e ingressos  

---

## 📚 Recursos para aprender Kubernetes

- [Documentação oficial](https://kubernetes.io/docs/)  
- [Kubernetes Basics Interactive Tutorial](https://kubernetes.io/docs/tutorials/kubernetes-basics/)  
- [Play with Kubernetes](https://labs.play-with-k8s.com/)  
- [The Illustrated Children's Guide to Kubernetes](https://www.cncf.io/phippy/)  

---

<p align="center">Feito com ❤️ para todos que querem dominar a orquestração de containers!</p>