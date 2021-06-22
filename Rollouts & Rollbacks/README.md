kubectl create  deployment nginx --image=nginx:1.11-alpine --replicas=3 

kubectl set image deployment/nginx nginx=nginx:1.13-alpine --record

kubectl rollout undo deployment/nginx-app

