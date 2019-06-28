# argo
See [Simplify and Automate Deployments Using GitOps with IBM Multicloud Manager 3.1.2](https://www.ibm.com/cloud/blog/simplify-and-automate-deployments-using-gitops-with-ibm-multicloud-manager-3-1-2)

![Argo Settings](images/2019/06/argo-settings.png)
![Connect Repository](images/2019/06/connect-repository.png)
![Connected Repository](images/2019/06/connected-repository.png)
![Select your Git Repository](images/2019/06/select-your-git-repository.png)
![aaa](images/2019/06/aaa.png)
![bbb](images/2019/06/bbb.png)
![Create and application](images/2019/06/create-and-application.png)

Download the argo CLI

wget https://169.50.59.138:31411/download/argocd-linux-amd64 --no-check-certificate
--2019-06-28 12:37:58--  https://169.50.59.138:314

![ArgoCD Server Service](images/2019/06/argocd-server-service.png)
![Server Service details](images/2019/06/server-service-details.png)
![Click on https link](images/2019/06/click-on-https-link.png)

```
root@mcm32master:/export/MultiCloudManager/argo# wget https://169.50.59.138:31411/download/argocd-linux-amd64 --no-check-certificate
--2019-06-28 12:37:58--  https://169.50.59.138:31411/download/argocd-linux-amd64
Connecting to 169.50.59.138:31411... connected.
WARNING: cannot verify 169.50.59.138's certificate, issued by ‘O=Argo CD’:
  Self-signed certificate encountered.
    WARNING: certificate common name ‘’ doesn't match requested host name ‘169.50.59.138’.
HTTP request sent, awaiting response... 200 OK
Length: 51780643 (49M) [application/octet-stream]
Saving to: ‘argocd-linux-amd64’

argocd-linux-amd64                           100%[============================================================================================>]  49.38M  29.4MB/s    in 1.7s    

2019-06-28 12:38:00 (29.4 MB/s) - ‘argocd-linux-amd64’ saved [51780643/51780643]
```
