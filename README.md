    1  curl -fsSL https://get.docker.com -o get-docker.sh
    2  sudo sh get-docker.sh
    3  curl -Lo ./kind https://kind.sigs.k8s.io/dl/v0.14.0/kind-linux-amd64
    4  mv ./kind /usr/lib/kind
    5  chmod +x /usr/lib/kind
    6  kind 
    7  curl -Lo ./kind https://kind.sigs.k8s.io/dl/v0.14.0/kind-linux-amd64
    8  mv ./kind /usr/bin/kind
    9  chmod +x  /usr/bin/kind
   10  kind 
   11  kind create cluster --name kcluster --image kindest/node:v1.29.1
   12  systemctl start docker
   13  systemctl enable docker
   14  kind create cluster
   15  kind get clusters
   16  kind get pods
   17  kubectl get pod
   18  kind get clusters
   19  kind delete cluster kcluster
   20  kind delete cluster --name  kcluster
   21  kind create cluster --name kcluster --image kindest/node:v1.
   22  kind create cluster
   23  kind get clusters
   24  kind create cluster
   25  kind delete cluster --name  kind
   26  kind create cluster
   27  curl -O https://s3.us-west-2.amazonaws.com/amazon-eks/1.29.6/2024-07-12/bin/darwin/amd64/kubectl
   28  ll
   29  mv kubectl /usr/bin/kubectl
   30  chmod +x /usr/bin/kubectl
   31  kubectl get pod
   32  ll
   33  kubectl
   34  curl -O https://s3.us-west-2.amazonaws.com/amazon-eks/1.29.6/2024-07-12/bin/linux/amd64/kubectl
   35  mv kubectl /usr/bin/kubectl 
   36  chmod +x /usr/bin/kubectl
   37  kubectl
   38  kubectl getpods
   39  kubectl get pods
   40  kubectl get pod
   41  kind get clusters
   42  kind delete cluster --name  kind
   43  kind create cluster --name kcluster --image kindest/node:v1.29.1
   44  kind get clusters
   45  kubectl cluster-info --context kind-kcluster
   46  kubectl get nodes
   47  cls
   48  lcear
   49  clkear
   50  clear
   51  kind get cluster
   52  kind get clusters
   53  kubectl cluster-info --context kind-kcluster
   54  kubectl get node
   55  kubectl get nodes
   56  kubectl run nginx --image=nginx
   57  kubectl get pods
   58  kubectl get pods --wide
   59  kubectl get pods --e
   60  kubectl get pods -w
   61  kubectl get pods -o
   62  kubectl get pods -W
   63  kubectl get pods -w
   64  kubectl get node
   65  kubectl get nodes
   66  kubectl get pods
   67  kubectl run sainginx --image=nginx
   68  kubectl get nodes
   69  kubectl get pods
   70  kubectl get pods -o wide
   71  root@ip-172-31-18-251:~# kubectl get pods -o wide
   72  NAME       READY   STATUS    RESTARTS   AGE     IP           NODE                     NOMINATED NODE   READINESS GATES
   73  nginx      1/1     Running   0          5m22s   10.244.0.5   kcluster-control-plane   <none>           <none>
   74  sainginx   1/1     Running   0          49s     10.244.0.6   kcluster-control-plane   <none>           <none>
   75  root@ip-172-31-18-251:~#
   76  root@ip-172-31-18-251:~# kubectl get pods -o wide
   77  curl http://10.244.0.6:
   78  curl http://10.244.0.6
   79  curl http://10.244.0.6:80
   80  kubectl run -it busybox --image busybox --sh
   81  kubectl run -it busybox --image busybox -- sh
   82  wget
   83  wget http://10.244.0.6:80
   84  root@ip-172-31-18-251:~# kubectl get pods -o wide
   85  kubectl get pods -o wide
   86  mkdir customize
   87  cd customize/
   88  vi deploy-ng.yaml
   89  vi cluster-ip.yaml
   90  ls
   91  cat cluster-ip.yaml 
   92  cat deploy-ng.yaml 
   93  pwd
   94  kubectl apply -f .
   95  kubectl get deployments
   96  kubectl get deploy,rs,po,svc
   97  kubectl delete pod --all
   98  kubectl get pods
   99  kubectl get deploy,rs,po,svc
  100  curl 10.96.44.30
  101  ssh 10.96.44.30
  102  ll
  103  vi kustomize.yaml
  104  ll
  105  vi kustomization.yaml
  106  vi kustomization.yaml 
  107  ll
  108  mv deploy-ng.yaml deploy.yaml
  109  mv cluster-ip.yaml service.yaml
  110  vi kustomization.yaml 
  111  ls -ltr
  112  cat kustomization.yaml
  113  vi kustomization.yaml 
  114  kubctl apply -f k
  115  kubctl apply -f kustomization.yaml 
  116  kubctl apply -f ./kustomization.yaml 
  117  kubectl apply -f ./kustomization.yaml 
  118  vi config.properties
  119  cat config.properties 
  120  truncate -s 0 kustomization.yaml 
  121  vi kustomization.yaml 
  122  kubectl apply -f ./kustomization.yaml 
  123  ll
  124  vi kustomization.yaml 
  125  kubectl apply -f ./kustomization.yaml 
  126  vi kustomization.yaml 
  127  kubectl apply -f ./kustomization.yaml 
  128  vi kustomization.yaml 
  129  kubectl apply -f ./kustomization.yaml 
  130  kubectl apply -f ./kustomization.yaml  --dry-run=client
  131  kubectl apply -k ./kustomization.yaml 
  132  kubectl kustomization.yaml 
  133  kubectl ./kustomization.yaml 
  134  kubectl kustomize .
  135  vi kustomization.yaml 
  136  kubectl kustomize .
  137  kubectl get pods
  138  kubectl get deploy,rs,po,svc
  139  cat config.properties 
  140  cat kustomization.yaml 
  141  kubectl get pods -A
  142  kubectl apply -k ./kustomization.yaml 
  143  kubectl apply -k .
  144  kubectl get pods -A
  145  kubectl get all
  146  vi kustomization.yaml 
  147  kubectl get all --show-labels
  148  cat kustomization.yaml 
  149  vi kustomization.yaml 
  150  kubectl apply -k .
  151  vi kustomization.yaml 
  152  kubectl apply -k .
  153  vi kustomization.yaml 
  154  kubectl apply -k .
  155  kubectl apply -k kustomization.yaml 
  156  vi kustomization.yaml 
  157  kubectl apply -k kustomization.yaml 
  158  kubectl apply -k .
  159  kubectl delete -k .
  160  kubectl get all --show-labels
  161  mkdir base
  162  ll
  163  mv *.y* base/
  164  ll
  165  mv config.properties base/
  166  kubectl get all --show-labels
  167  lsb
  168  ls base/
  169  mkdir overlays
  170  mkdir dev
  171  mkdir prod
  172  ll
  173  mv dev overlays/
  174  mv prod overlays/
  175  cd overlays/dev/
  176  ll
  177  vi kustomization.yaml
  178  kubectl apply -k .
  179  vi kustomization.yaml
  180  kubectl apply kutomize .
  181  kubectl apply kustomize .
  182  kubectl apply kustomize 
  183  kubectl apply kustomize kustomization.yaml 
  184  kubectl apply -k .
  185  kubectl create ns dev
  186  kubectl apply -k .
  187  kubectl all
  188  kubectl --all
  189  kubectl -all
  190  kubectl create ns prod
  191  kubectl get --all
  192  kubectl get -all
  193  kubectl get all --show-labels
  194  kubectl get all --show-labels --show-namespae
  195  kubectl get all --show-labels --show-namespace
  196  kubectl get --help
  197  kubectl get all -A
  198  kubectl get rc/web service/frontend pods/web-pod-13je7
  199  kubectl get rc/web 
  200  kubectl get all --show-labels --show-namespace
  201  kubectl get all --show-labels --a
  202  kubectl get all --show-labels -k
  203  kubectl get all --show-labels --k
  204  kubectl get all --show-labels --all-namespaces
  205  kubectl get all --show-labels -l
  206  kubectl get all  -l
  207  kubectl get all  -l dev
  208  kubectl get all  -L dev
  209  kubectl get all  -L dev -o
  210  kubectl get all  -L dev -o wide
  211  vi kustomization.yaml 
  212  ll
  213  ll ,,.,.
  214  ll ../../
  215  ll ../../base/
  216  vi kustomization.yaml 
  217  kubectl apply -k .
  218  ll ../../
  219  ll ../../base/
  220  vi kustomization.yaml 
  221  kubectl apply -k .
  222  vi kustomization.yaml 
  223  kubectl apply -k .
  224  vi kustomization.yaml 
  225  kubectl apply -k .
  226  cat kustomization.yaml 
  227  vi kustomization.yaml 
  228  cat ../../base/deploy.yaml 
  229  vi cp ../../base/deploy.yaml .
  230  s
  231  ls
  232  rm 1
  233  vi deploy.yaml 
  234  vi kustomization.yaml 
  235  vi deploy.yaml 
  236  cat deploy.yaml 
  237  vi kustomization.yaml 
  238  kubectl apply -k .
  239  vi kustomization.yaml 
  240  kubectl apply -k .
  241  vi kustomization.yaml 
  242  kubectl apply -k .
  243  vi kustomization.yaml 
  244  kubectl apply -k .
  245  vi kustomization.yaml 
  246  kubectl apply -k .
  247  ll ../../base/
  248  ll
  249  cat ../../base/kustomization.yaml 
  250  cat kustomization.yaml 
  251  ll
  252  cp kustomization.yaml kustomization.yaml.1
  253  vi kustomization.yaml
  254  ll
  255  kubectl apply -k .
  256  vi kustomization.yaml
  257  cat deploy.yaml 
  258  cat ../../base/kustomization.yaml 
  259  kubectl -version
  260  kubectl --version
  261  kc version
  262  kubectl version
  263  vi kustomization.yaml
  264  cat ../../base/kustomization.yaml 
  265  kubectl apply -k .
  266  cat kustomization.yaml
  267  vi kustomization.yaml
  268  cd ..~
  269  ll
  270  cd ..
  271  rm -rf prod
  272  cp -f dev prod
  273  cp -avf dev prod
  274  cd prod
  275  ls
  276  rm kustomization.yaml.1 
  277  vi kustomization.yaml 
  278  ls -ltr
  279  vi deploy.yaml 
  280  kubectl appl -k .
  281  kubectl apply -k .
  282  kubectl get all
  283  kubectl get all --show-labels
  284  kubectl get pods
  285  kubectl get all -n prod
  286  cat ../../base/config.properties 
  287  vi ../../base/config.properties 
  288  kubectl apply -k .
  289  cat ../../base/kustomization.yaml 
  290  kubevtl get cm
  291  kubectl get cm
  292  kubectl apply -f ../../base/config.properties 
  293  cd
  294  cp customize/base/config.properties .
  295  cp customize/base/config.properties config.properties 
  296  kubectl apply -f c
  297  kubectl apply -f .
  298  cp config.properties config.yml
  299  rm config.
  300  rm config.yml 
  301  ll
  302  cd customize/
  303  ll
  304  rm 1
  305  cd overlays/prod/
  306  kubectl apply -f .
  307  ll
  308  kubectl apply kf .
  309  kubectl apply -k .
  310  clear
  311  cat ../../base/config.properties 
  312  cat ../../base/kustomization.yaml 
  313  vi ../../base/kustomization.yaml 
  314  mv ../../base/config.properties .
  315  vi kustomization.yaml 
  316  kubectl apply -k .
  317  kubectl describe cm
  318  kubectl describe cm config.properties 
  319  cat config.properties 
  320  cat kustomization.yaml 
  321  kubectl describe cm saikustom-map 
  322  kubectl describe cm saikustom-map -n prod
  323  cls
  324  clear
  325  kubectl describe cm saikustom-map -n prod
  326  kubectl get all --show-labels
  327  kubectl get all --show-labels -n prod
  328  clear
  329  kubectl get all --show-labels -n prod
  330  kubectl describe cm saikustom-map -n prod
  331  vi config.properties 
  332  kubectl apply -k .
  333  kubectl describe cm saikustom-map -n prod
  334  kubectl get all --show-labels -n prod
  335  cd .ssh/
  336  ll
  337  ssh-keygen
  338  cat id_rsa.pub 
  339  cd
  340  mkdir sai
  341  cd sai/
  342  ll
  343  cd GitFlux/
  344  ll
  345  touch README.md
  346  git add .
  347  git commit -m "updated ReadMe"
  348  git push
  349  kubectl get pods
  350  kubectl get nodes
  351  kubectl get pods --wide
  352  node
  353  mkdir repositories
  354  cd repositories/
  355  ll
  356  mkdir saiapp
  357  cd saiapp/
  358  mkdir -p src deploy
  359  cd src/
  360  vi app.py
  361  vi docker
  362  mv docker dockerfile
  363  cd ..
  364  mkdir -p deploy
  365  cd deploy/
  366  ll
  367  vi configmap.yaml
  368  rm 1 
  369  vi deployment.yaml
  370  vi configmap.yaml 
  371  vi deployment.yaml 
  372  vi service.yaml
  373  vi service.yaml 
  374  cat service.yaml 
  375  cat deployment.yaml 
  376  cd ..
  377  git add . | git commit -m "Updated init"| git push
  378  ls
  379  cd repositories/
  380  git add . | git commit -m "Updated init"| git push
  381  ll
  382  cd 
  383  cd sai/GitFlux/repositories/saiapp/
  384  ll
  385  cd deploy/
  386  ll
  387  cat service.yaml 
  388  grep master *
  389  grep master  ../src/
  390  grep master  ../src/*
  391  cd ..
  392  ll
  393  cd ..
  394  ll
  395  mkdir infra-repo
  396  ll infra-repo
  397  cd infra-repo
  398  cd ..
  399  mc saiapp sai-app-1
  400  mv saiapp sai-app-1
  401  cd infra-repo/
  402  tree
  403  vi gitrepository.yaml
  404  tree 
  405  apt update -y
  406  apt  install tree
  407  tree
  408  mv gitrepository.yaml sai-app-1.yaml
  409  cd ..
  410  tree
  411  rm sai-app-1/deploy/1
  412  cd infra-repo/
  413  mkdir apps
  414  cp sai-app-1.yaml apps/
  415  rm sai-app-1.yaml 
  416  ll
  417  cd apps/
  418  ll
  419  mkdir  sai-app-1
  420  cd sai-app-1/
  421  mv ../sai-app-1.yaml  .
  422  mv sai-app-1.yaml gitrepository.yaml
  423  cat gitrepository.yaml 
  424  vi kustomization.yaml
  425  cd ..
  426  cd sai-app-1/deploy/
  427  pwd
  428  cd .././
  429  cd ..
  430  cd infra-repo/apps/sai-app-1/
  431  ll
  432  vi kustomization.yaml
  433  ll
  434  cat gitrepository.yaml 
  435  cd ..
  436  ll
  437  cat infra-repo/apps/sai-app-1/gitrepository.yaml 
  438  cat infra-repo/apps/sai-app-1/kustomization.yaml 
  439  pwd
  440  ll
  441  ll sai-app-1/
  442  kubectl get-resources
  443  kubectl --get-resources
  444  kubectl --get resources
  445  kubectl api-resources
  446  kubectl api-resources -n prod
  447  ll
  448  cat infra-repo/apps/sai-app-1/gitrepository.yaml 
  449  cat infra-repo/apps/sai-app-1/kustomization.yaml 
  450  vi infra-repo/apps/sai-app-1/kustomization.yaml 
  451  ll
  452  rm 1
  453  vi infra-repo/apps/sai-app-1/kustomization.yaml 
  454  ll
  455  ll infra-repo/
  456  cat infra-repo/apps/sai-app-1/l
  457  cat infra-repo/apps/sai-app-1/kustomization.yaml 
  458  ll ~
  459  ll ~/sai/GitFlux/./repositories/sai-app-1/deploy
  460  ll
  461  ls -la
  462  cd ..
  463  git add . | git commit -m "Updated init"| git push
  464  ls
  465  git add .
  466  git status
  467  git push
  468  git add . | git commit -m "Updated init"| git push
  469  tree
  470  git status
  471  cat repositories/sai-app-1/src/dockerfile 
  472  vit repositories/sai-app-1/src/dockerfile 
  473  vi repositories/sai-app-1/src/dockerfile 
  474  tree
  475  vi repositories/sai-app-1/src/dockerfile 
  476  ll repositories/sai-app-1/
  477  ll repositories/sai-app-1/src/
  478  git add . | git commit -m "Updated init"| git push
  479  git push
  480  ll
  481  . <(flux completion bash)
  482  curl -s https://fluxcd.io/install.sh | sudo bash
  483  ll
  484  ls -la
  485  ls
  486  flux 
  487  ll
  488  git add .
  489  git status
  490  . <(flux completion bash)
  491  history
  492  ll
  493  history > README.md 
  494  git add .
  495  git status
  496  git add . | git commit -m "Updated init"| git push
  497  git puhs
  498  git push
  499  flux check --a
  500  flux check --pre
  501  export GITHUB_TOKEN=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
  502  ll
  503  cd repositories/infra-repo/
  504  ll
  505  mkdir clusters
  506  cd clusters/
  507  mkdir dev-clusters
  508  cd dev-clusters/
  509  pwd
  510  flux bootstrap github   --token-auth   --owner=saiprakashp   --repository=GitFlux   --branch=main   --path=GitFlux/repositories/infra-repo/clusters/dev-clusters   --personal
  511  flux check
  512  kubectl -n flux-system
  513  kubectl -n flux-system get gitrepository
  514  kubectl -n flux-system get customization
  515  kubectl -n flux-system get kustomization
  516  ls
  517  .gitkeep
  518  touch .gitkeep
  519  cd ..
  520  cd repositories/infra-repo/
  521  ll
  522  cd clusters/
  523  ll
  524  cd dev-clusters/
  525  ll
  526  flex uninstall
  527  flux uninstall
  528  l
  529  ll
  530  curl -s https://fluxcd.io/install.sh | sudo bash
  531  . <(flux completion bash)
  532  ll
  533  flux check --pre
  534  ll
  535  cd ..
  536  git add .
  537  git commit -m "updated"
  538  git push
  539  git pull
  540  git branch
  541  git add .
  542  git commit -m "updated"
  543  git pull
  544  ll
  545  ll repositories/
  546  ll repositories/infra-repo/
  547  ll repositories/infra-repo/clusters/
  548  git add .
  549  git commit -m "updated"
  550  git push
  551  flux bootstrap github   --token-auth   --owner=saiprakashp   --repository=GitFlux   --branch=main   --path=GitFlux/repositories/infra-repo/clusters/dev-clusters   --personal
  552  flux check 
  553  \
  554  git puhs
  555  git status
  556  fir add .
  557  gir add .
  558  git add .
  559  git status
  560  flux uninstall
  561  ll
  562  rm -rf GitFlux/
  563  gir add .
  564  git add .
  565  git commit -m "updated"
  566  git push
  567  flux bootstrap github   --token-auth   --owner=saiprakashp   --repository=GitFlux   --branch=main   --path=repositories/infra-repo/clusters/dev-clusters   --personal
  568  flux status
  569  flux check
  570  history
  571  kubectl -n flux-syste, get kustomzation
  572  kubectl -n flux-syste, get kustomization
  573  kubectl -n flux-system get kustomization
  574  kubectl -n flux-system get gitrepository
  575  kubectl get pods
  576  cd repositories/sai-app-1/
  577  ;;
  578  ll
  579  cd src/
  580  ll
  581  docket build -t sai-app-1
  582  docker build -t sai-app-1
  583  docker build -t sai-app-1:0.0.1
  584  docker build -t sai-app-1:0.0.1 .
  585  cat dockerfile 
  586  cat ../deploy/deployment.yaml 
  587  docker images
  588  cat ../deploy/deployment.yaml 
  589  king load docker-image -image sai-app-1:0.0.1 --name kcluster
  590  kind load docker-image -image sai-app-1:0.0.1 --name kcluster
  591  kind load docker-image sai-app-1:0.0.1 --name kcluster
  592  king imag earchive
  593  king image-archive
  594  kind image-archive
  595  king help
  596  kind help
  597  kind get
  598  kind load -h
  599  kind load image-archive
  600  kind load image-archive  sai-app-1:0.0.1
  601  kind load image-archiv
  602  kind load image-archive
  603  kind get clusters
  604  kind get kubeconfig --name  kcluster-control-plane
  605  kind get kubeconfig --name  kcluster
  606  kind get kubeconfig --name  kcluster | grep image
  607  kind get kubeconfig --name  kcluster | grep images
  608  kubectl run -it --rm --image=docker:latest bash --command="docker images"
  609  docker exec -it $(kind get clusters | head -1)-control-plane crictl images
  610  kubectl get pods
  611  kubectl get pod
  612  dc ../deploy/
  613  de ../deploy/
  614  ll
  615  vi ../deploy/deployment.yaml 
  616  docker exec -it $(kind get clusters | head -1)-control-plane crictl images
  617  docker build -t sai-app-1:0.0.1 .
  618  kind load image-archive  sai-app-1:0.0.1
  619  kind load docker-image -image sai-app-1:0.0.1 --name kcluster
  620  kind load docker-image sai-app-1:0.0.1 --name kcluster
  621  flux reconcile kustomization podinfo --with-source
  622  kubectl get pods
  623  docker build -t sai-app-1:0.0.1 .
  624  kubectl get pod
  625  kubectl run -it --rm --image=docker:latest bash --command="docker images"
  626  docker exec -it ${CLUSTER_NAME}-control-plane crictl images
  627  docker exec -it $(kind get clusters | head -1)-control-plane crictl images
  628  cd ../
  629  cd ../infra-repo/
  630  ll
  631  cd apps/
  632  ll
  633  cd sai-app-1/
  634  ll
  635  kubectl apply -f .
  636  ll
  637  watch -n 1
  638  watch -n 1 kubectl
  639  watch -n 1 kubectl -all
  640  watch -n 1 kubectl all
  641  kubectl get all
  642  watch -n -1 kubectl get all
  643  kubectl port-forward svc service/sai-app-1
  644  kubectl port-forward service/sai-app-1 80:80
  645  cd ..
  646  cd..
  647  cd ..
  648  ll
  649  echo history > README.md 
  650  git add .
  651  git status
  652  git commit -m "updated"
  653  git push
  654  git pull
  655  git push
  656  echo $history > README.md 
  657  cat README.md 
  658  history > README.md 
