# TASK 1:-

![image](https://github.com/user-attachments/assets/6109f60e-283e-42bd-af97-3ce8bfb44772)


#### 1-

![1](https://github.com/user-attachments/assets/e14eb82d-05dc-4a68-a1a8-cdec371a930c)

#### 2-

![2](https://github.com/user-attachments/assets/65a45db1-f5cf-4159-bb60-820d32651a45)


#### 3-

![3](https://github.com/user-attachments/assets/ddda3d8c-2317-4c9d-9785-fdbfc7804592)



# TASK 2:-


## 2.1
![4](https://github.com/user-attachments/assets/673f328d-8f31-4198-9ee9-c0be99007305)


![5](https://github.com/user-attachments/assets/22d16ee4-0ec2-4eba-a429-f8c70d5ff11b)


## 2.2

![6](https://github.com/user-attachments/assets/47fbc829-a4aa-450d-97ef-8d13bb635b34)

![7](https://github.com/user-attachments/assets/a9872293-7d88-45ff-8ee8-d12556cbc2ce)






# TASK 3: Customize Nginx in a Docker Container and Push to Docker Hub

## Description

#### 1-Pull the official Nginx image from Docker Hub.
#### 2-Run an Nginx container in detached mode.
#### 3-Install Vim inside the running container using apt.
#### 4-Edit the default index.html file to display our name ("Mohamed Ashraf").
#### 5-Commit the modified container to create a new custom image.
#### 6-Tag the image with two different versions (v1 and latest).
#### 7-Push the custom image to Docker Hub under the repository mohamedashrf/nginx-custom


![task1](https://github.com/user-attachments/assets/e94f42d3-3cc5-4192-a0b2-89b82c798be4)


![task2](https://github.com/user-attachments/assets/7dfc7839-1020-45f8-8345-c0bf589b2e6d)


![task3](https://github.com/user-attachments/assets/23f86ede-8735-485e-9cc6-305f4bf7e904)


![task4](https://github.com/user-attachments/assets/216d9338-7371-4fd6-a398-9e63e08ffcb1)


![task5](https://github.com/user-attachments/assets/f36f5f79-2e46-4468-ab54-3260033d39ff)


![task 6](https://github.com/user-attachments/assets/e46f9425-f017-4af4-aa17-2ce2346c4e4f)





## Flowchart


```mermaid
graph TD;
    A[Pull Nginx Image] --> B[Run Container my_nginx];
    B --> C[Access Container with Bash];
    C --> D[Install Vim using apt];
    D --> E[Edit index.html in /usr/share/nginx/html];
    E --> F[Exit Container];
    F --> G[Commit Changes to New Image];
    G --> H[Tag the Image as v1 and latest];
    H --> I[Login to Docker Hub];
    I --> J[Push Image to Docker Hub];
    J --> K[Process Complete];  
    K --> A;  %% This ensures a proper loop without a direct link error






