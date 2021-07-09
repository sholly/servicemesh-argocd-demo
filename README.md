# Deploying Service Mesh applications with ArgoCD

Service mesh applications can be deployed just as easily as any other application.  ArgoCD
will apply the service mesh CustomResourceDefinitions just like regular Openshift objects.  
One must make sure that the deployed namespace has been added to the Service Mesh Member Roll.
Once done, simply open your ArgoCD console, use branch 'main', use the 'deploy' folder, and deploy the application. 
