# PODS

controlplane ~ ➜  history
    1  kubectl get pods
    3  kubectl get ns
    4  alias k="kubectl"
    5  k get pods

  # 6  k create pod --image=nginx

    7  kubectl create --help
    8  kubectl run nginx --image=nginx
   10  k get pods
   13  k describe po nginx
   14  k describe po newpods-w747p
   15  k get po
   16  k decribe po newpods-cmgsd
   18  k get po
   21  k describe po webapp
   23  k get pods
   24  kubectl delete po webapp
   25  k get po

  # 26  kubectl run po redis --image=redis
  # 28  k delete redis
  # 29  k delete po redis
  # 30  k delete pods redis

   31  k get pods
   34  k delete pods po
   35  k run redis --image=redis123
   36  k delete pods po
   38  k run redis --image=redis123 --dry-run=client -oyaml > redis-definition.yaml
   39  kubectl create -f redis-definition.yaml
   40  k get pods
   41  k decribe po redis
   42  k describe po redis
   43  k get pods
   44  k edit -f redis-definition.yaml (Alternatif çözüm alt 2 satır)
   ### kubectl edit pod redis
   ### kubectl apply -f redis-definition.yaml 
   47  k get pods
   48  history


# REPLICASETS


   kubectl delete replicaset <replicaset-name>
   kubectl delete -f <file-name>.yaml
   kubectl delete replicaset replicaset-1 replicaset-2




    1  k get po
    1  alias k="kubectl"
    2  alias kgp="kubectl get pods"
    4  alias kgp="kubectl get pods"
    5  alis kgn="kubectl get nod"
    6  alias kgn="kubectl get nod"
    7  alias kd="kubectl describe"
    4  alias kdp="kubectl describe pods"
    5  k get replicaset
    8  kubectl describe replicaset
   11  kubectl get replicaset
   12  kgp
   13  kdp new-replica-set-tptgh
   14  kgp
   15  kubectl delete po new-replica-set-cxd48
   16  kgp
   17  pwd
   19  kubectl create -f /root/replicaset-definition-1.yaml 
   20  kubectl create -f replicaset-definition-1.yaml 
   21  kubectl edit -f replicaset-definition-1.yaml 
   25  k get ns
   26  pwd
   30  kubectl explain replicaset | grep VERSION
   31  kubectl create -f /root/replicaset-definition-1.yaml
   33  kubectl explain replicaset
   35  ls
   36  pwd
   37  vi replicaset-definition-1.yaml 
   38  cat replicaset-definition-1.yaml 
   39  kubectl create -f replicaset-definition-1.yaml 
   40  kubectl get replicaset
   41  vi replicaset-definition-2.yaml 
   42  cat replicaset-definition-1.yaml
   43  cat replicaset-definition-2.yaml 
   44  kubectl create -f replicaset-definition-2.yaml 
   45  vi replicaset-definition-2.yaml 
   46  kubectl create -f replicaset-definition-2.yaml 
   47  kubectl get replicaset
   60  k delete --all pods
   48  kubectl delete replicaset replicaset-1,replicaset-2
   49  kubectl delete replicaset replicaset-1
   50  kubectl delete replicaset replicaset-2
   51  kubectl get replicaset
   52  kubectl get po
   53  kubectl get replicaset
   54  cat new-replica-set
   55  ls
   56  kubectl describe replicaset new-replica-set
   57  kubectl edit replicaset new-replica-set
   58  kubectl get replicaset
   59  kuebctl get po
   60  kgp
   69  k edit replicaset new-replica-set
   70  k get replicaset
   71  kubectl scale --replicas=2 new-replica-set
   72  kubectl scale --replicas=2 replicaset/new-replica-set
   73  k get replicaset
   74  k get rep
   75  k get replica
   76  k get rp
   77  k get rs
   78  history
