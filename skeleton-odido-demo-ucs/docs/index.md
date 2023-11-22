BWCE Documentation for: ${{ values.name }}
-------

${{ values.description }}

This BWCE Project does following usecases :
===========================

- JMS:
    - How to connect to JMS Server from BWCE using inbuilt connector? Perform Clinet - Service operation.
    - How to implement Asynchronous Request/Reply (client/server) implementation using BWCE.
- RDS:
    - Connecting and getting data from RDS Instance (Maria DB)
    - Transactional behavior: It demonstrate JDBC transaction behavior with connecting to RDS instance and performing duplicate record with insert operations.
- Java:
    - How to work with External Java jars/classes/methods? How to use externally build java method through referencing jar file in BWCE application.
    - How to pass input data from different activities (JDBC query) to Java Method available as a Jar/class.
- Rounting:
    - How to create Condition based transitional routing process that evaluates path based on HTTP headers.
    - How to use Dynamic routing based on HTTP headers? With one single process manage multiple routes based on evaluated condition
- SFTP:
    - Connect with external SFTP Server, retrive a large configured csv file and store it locally on filesystem
- File Processing:
    - Get a file retrieved from sFTP server and process it in chunks/batches to better performance.
- Confidentiality:
    - Obfuscation: mask the specified field, string using BWCE confidentially plugin
    - Encryption: perform a encryption of incoming data and store hat in file locally on filesystem.
    - Decryption: perform the decryption operation on the file created in above step and show the data. 

