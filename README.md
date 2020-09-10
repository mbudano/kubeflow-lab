# kubeflow-lab

Se genero el archivo kfctl_ibm.v1.1.0.yaml comentando la seccion que instala el istio-stack ya que utiliza istio 1.1 en lugar del 1.7 de IKS
Ademas se genero el archivo manifests-1.1-branch.tar.gz que sera utilizado en el deployment ya que se debe modificar las configuraciones de istio para que sea compatible con istio 1.6+
Leer el issue: https://github.com/kubeflow/kubeflow/issues/5070
El path modificado fue el: manifests-1.1-branch/istio/istio/base
