# Architecture Openshift

l'architecture en terme de composant est la meme, il y'a juste un composant nouveau
sur le plan de control: on a toujours
 - l'API server
 - l'etcd
 - controller manager
 - openshift controller manager : qui gère et fourni des ressources spécifique openshift (comme des routes, prjet, operateurs...)
   
Sur les worker node : on a toujours
  - kubelet : l'agent 
  - kubeproxy : pour l'activation de la couche reseau


#



#



#  openshift controller manager

docs archi
lien vers docs
lab archi: 
    -
    -
    -
    -
<img width="1484" height="15828" alt="image" src="https://github.com/user-attachments/assets/b1c2fd91-8e6d-442e-8d3c-dbe1717ab512" />

    
