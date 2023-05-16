# spring-gumball

## CI workflow

First successful CI build:
![image](https://github.com/AlpyneDreams/spring-gumball/assets/3376691/7965573d-0530-4230-8220-11e8120b3faa)

Logs of CI build part 1:
![image](https://github.com/AlpyneDreams/spring-gumball/assets/3376691/24a7cddd-9f57-4c37-98b4-ab5ef7100eb7)

Logs of CI build part 2:
![image](https://github.com/AlpyneDreams/spring-gumball/assets/3376691/155cc790-4c40-49de-9aff-fa20516aa84c)

## CD workflow

Creating Kubernetes Cluster: (this process takes 5-10 mins)
![image](https://github.com/AlpyneDreams/spring-gumball/assets/3376691/e04a3857-a601-49b9-a27d-27e4052eae8f)

Step 2/3:
![image](https://github.com/AlpyneDreams/spring-gumball/assets/3376691/6e595caf-4d90-4e7d-a9d0-9fae115ede3a)

Step 3/3:
![image](https://github.com/AlpyneDreams/spring-gumball/assets/3376691/531002e5-23f3-4cd5-9860-4aac5cb7a2ee)

Enabling the APIs: (it was already enabled)
![image](https://github.com/AlpyneDreams/spring-gumball/assets/3376691/adfbbffa-d40e-4aae-a1ed-e212a96a206e)

Enabling the IAM API:
![image](https://github.com/AlpyneDreams/spring-gumball/assets/3376691/1e19ae2c-31ba-4367-92e8-ffc4431dbcd0)

After clicking on Enable:
![image](https://github.com/AlpyneDreams/spring-gumball/assets/3376691/224daff1-4e5b-4a9f-a526-a31c5c41a3bd)

Enabling the container and kubernetes APIs:
![image](https://github.com/AlpyneDreams/spring-gumball/assets/3376691/17effb4c-1b4f-4d53-8740-afbd61a9ed68)

Creating service account:
![image](https://github.com/AlpyneDreams/spring-gumball/assets/3376691/66c6f727-f0bf-450e-937a-4be2f2c43020)

After creating service account:
![image](https://github.com/AlpyneDreams/spring-gumball/assets/3376691/8dbb2373-a3a0-4b51-a452-83e9887eaa29)

Add roles to service account:
![image](https://github.com/AlpyneDreams/spring-gumball/assets/3376691/95b64f4e-c3ab-4470-9418-a2253e951014)

Create new key:
![image](https://github.com/AlpyneDreams/spring-gumball/assets/3376691/d29b3711-702c-44a1-bd6d-99ade24b99ea)

Add secrets to GitHub:
![image](https://github.com/AlpyneDreams/spring-gumball/assets/3376691/8c43e3cd-b494-4f20-9c34-cb20bdf17368)

Adding gke action: (see .github/workflows/gke.yml)

Creating a new release:
![image](https://github.com/AlpyneDreams/spring-gumball/assets/3376691/a2c505b0-d6bb-4191-85a2-39929213244f)

CD action:
![image](https://github.com/AlpyneDreams/spring-gumball/assets/3376691/ef56054b-8ea9-4842-a79a-c6568440120c)

CD deployment in GKE:
![image](https://github.com/AlpyneDreams/spring-gumball/assets/3376691/c5021c85-8bdf-4c20-a994-76b19d27a059)

CD service in GKE:
![image](https://github.com/AlpyneDreams/spring-gumball/assets/3376691/54952d4d-2695-49f9-bbe8-d44bac827ad1)

GKE ingress:
![image](https://github.com/AlpyneDreams/spring-gumball/assets/3376691/2a8e417c-bb04-45ff-b910-aee78a1789b4)

Deployed website:
![image](https://github.com/AlpyneDreams/spring-gumball/assets/3376691/8d943d2c-dcb4-491e-8b17-6e3dbf9afade)

