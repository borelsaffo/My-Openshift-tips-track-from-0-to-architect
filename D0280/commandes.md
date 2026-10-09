#
14  

oc whoami 
   15  ls ~/.kube/config
   16  ls ~/.kube
   17  oc login -u developer https://api.lab.example.com:6443
   18  cat .kube/config 
   19  oc whoami 
   20  oc whoami --show-console 
   21  oc whoami 
   22  oc login --token sha256~8MCRs6VpvzYiaknVEAU8dtIccHZenIPtk41g4QITjlE --server https://api.lab.example.com:6443
   23  oc whoami 
   24  cat .kube/config 
   25  oc logout 
   26  cat .kube/config 
   27  oc login -u developer 
   28  oc whoami 
   29  rm -rf .kube/config 
   30  oc whoami 
   31  oc login --web https://api.lab.example.com
   32  oc login --web https://api.lab.example.com:6443
   33  oc whoami 
   34  cat .kube/config 
   35  oc logout 
   36  cat .kube/config 
   37  ls .auth/
   38  cat .auth/lab-kubeconfig | less
   39  cp -v .auth/lab-kubeconfig .kube/config 
   40  oc whoami 
   41  oc logout 
   42  cat .kube/config | less
   43  env | grep KUBECONFIG
   44  rm -r .kube/config 
   45  oc whoami
