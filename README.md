# DB2_Docker

1)create Docker container

docker run -itd --name mydb2 --privileged=true -p 50002:50000 -e LICENSE=accept -e DB2INST1_PASSWORD=testdb -e DBNAME=testdb  ibmcom/db2


![image](https://github.com/user-attachments/assets/7a679a57-2983-4ccf-a8ce-c530c29a449b)


2)enter shell of container
docker exec -it fc27f8127e83a53a77221dc1aed309d9f0ebb841a27f2f2c9a3487de29acee40 bash
