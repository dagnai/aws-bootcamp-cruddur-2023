# Week 0 — Billing and Architecture

## Required Homework/Tasks


Added the below code to .gitpod.yml - commit (bf02d65).
```
    init: |
      cd /workspace
      curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip"
      unzip awscliv2.zip
      sudo ./aws/install
      cd $THEIA_WORKSPACE_ROOT
```

### AWS Billing Alarm

![image](https://user-images.githubusercontent.com/87647221/219954174-be4939dd-6153-4342-a2ad-60486178e8d2.png)

alarm-config.json:
![image](https://user-images.githubusercontent.com/87647221/219954321-5d8eab8a-00b6-4f95-b28c-171749c18fee.png)


### AWS Budget

![image](https://user-images.githubusercontent.com/87647221/219954121-8a60e705-10e8-4d6e-a7d1-eb4f071964e6.png)

Budget:
![image](https://user-images.githubusercontent.com/87647221/219954336-d938786a-f10e-4332-ae9c-afbe2c7dc308.png)

Notification:
![image](https://user-images.githubusercontent.com/87647221/219954345-9498c9f8-6b40-43c1-b064-ba74f44b6bb2.png)

### LucidCharts:

1. Logical Diagram:
![image](https://user-images.githubusercontent.com/87647221/219954469-e5a04def-d534-4cb5-a862-81c6784f3bd6.png)
https://lucid.app/lucidchart/607864f3-ef6d-48fd-a8e2-14f96c5add5f/edit?viewport_loc=-398%2C41%2C2560%2C1360%2C0_0&invitationId=inv_e3ec777d-a6b7-450c-94a7-60503c193b31

2. Conceptual Diagram
![image](https://user-images.githubusercontent.com/87647221/219954489-fdff47a2-17bf-40a0-95d6-cf2762c24c89.png)
https://lucid.app/lucidchart/91dca104-c1c0-486f-865b-d5a4fcdf556c/edit?viewport_loc=-1838%2C-203%2C2560%2C1360%2C0_0&invitationId=inv_5a77139b-9083-47cf-888f-8a01a787ae17
