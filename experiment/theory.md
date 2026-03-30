Data encryption is a fundamental security mechanism used in database systems to protect sensitive information from unauthorized access. Encryption converts plaintext data into unreadable ciphertext using cryptographic algorithms and secret keys. Only authorized users with the appropriate decryption keys can access the original data, ensuring confidentiality and data protection.

In databases, encryption is mainly applied to **data at rest**, which refers to data stored on disks, backups, or database files. Protecting data at rest is essential to prevent data exposure in cases such as disk theft, unauthorized file access, or system compromise. Additionally, modern security practices involve securing **data-in-transit** (data being transferred over a network) and **data-in-use** (data actively being processed by the database or application).

#### **Column-Level Encryption**

Column-level encryption is a fine-grained encryption technique where specific columns containing sensitive information—such as passwords, credit card numbers, or personal identifiers—are encrypted individually. This method allows sensitive fields to remain protected while non-sensitive data remains readable. Encryption and decryption are performed using built-in or user-defined cryptographic functions during data insertion and retrieval, providing flexibility and strong security control.

#### **Transparent Data Encryption (TDE)**

Transparent Data Encryption (TDE) is a storage-level encryption mechanism that automatically encrypts the entire database, including data files, log files, and backups. TDE works transparently for applications, meaning encryption and decryption occur automatically without requiring changes to application code. It protects data at the storage level and is effective against physical theft or unauthorized access to database files.

#### **Encryption and Decryption of Sensitive Data**

Sensitive data such as passwords and credit card numbers must be encrypted before storage and decrypted only when necessary for authorized operations. Databases provide built-in cryptographic functions and key management mechanisms to securely perform encryption and decryption processes. Proper key management is essential to maintain the effectiveness of encryption.
