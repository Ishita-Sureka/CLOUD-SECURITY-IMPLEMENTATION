# CLOUD-SECURITY-IMPLEMENTATION

# CLOUD-STORAGE-SETUP

**COMPANY**:CODTECH IT SOLUTIONS

**NAME**:ISHITA SUREKA

**INTERN ID**:CT08IXT

**DOMAIN**:CLOUD COMPUTING

**BATCH DURATION**: December 30th, 2024 to January 30th, 2025

**MENTOR NAME**: NEELA SANTOSH

**DESCRIPTION OF TASK**:In this task, I was assigned to implement IAM policies, secure storage, and data encryption on a cloud platform to ensure the protection of sensitive resources and data. The first step was creating IAM (Identity and Access Management) policies to manage access to resources. IAM policies define the permissions granted to users, groups, or roles, determining what actions they can perform on cloud resources. I created a custom IAM policy for Amazon S3, specifying actions such as s3:ListBucket, s3:GetObject, s3:PutObject, and s3:DeleteObject. These permissions allowed the user to list, upload, download, and delete objects in a specific S3 bucket. Once the policy was created, I attached it to an existing IAM user, which granted them the necessary permissions to interact with the bucket. This approach followed the principle of least privilege, ensuring the user had only the permissions required to perform their tasks.

The next step was securing the storage environment by configuring access controls on the Amazon S3 bucket. Amazon S3 is a scalable and durable cloud storage service, widely used for storing data. I ensured that only the IAM user with the appropriate policy attached could interact with the objects stored in the S3 bucket. By configuring access controls, I restricted unauthorized users from accessing the stored data, thus improving security. Additionally, I enabled versioning for the S3 bucket to allow for the recovery of previous object versions. Versioning ensures that if an object is accidentally deleted or overwritten, earlier versions can be restored, providing additional protection for critical data.

The final step involved implementing data encryption to protect sensitive information. Encryption is an essential element of data security, ensuring that sensitive data remains confidential, even if it is accessed by unauthorized parties. To protect the data at rest, I enabled Server-Side Encryption (SSE) for the S3 bucket, using SSE-S3 as the encryption method. SSE-S3 automatically encrypts objects using the AES-256 encryption algorithm before they are stored in the bucket. This process is seamless and does not require any manual intervention. When the data is uploaded, it is automatically encrypted, and when accessed, it is decrypted for authorized users.

By enabling data encryption, I ensured that the data stored in the S3 bucket was protected from unauthorized access, even if someone gained access to the storage. This measure ensures that sensitive information, such as personal or financial data, remains secure. Additionally, encryption also helps with compliance to industry standards and regulations that mandate the protection of sensitive data.

In conclusion, I successfully implemented IAM policies, secured storage, and applied data encryption on the cloud platform to protect sensitive data. The IAM policies allowed for fine-grained control over user access, ensuring that only authorized users could access the resources. Securing storage with Amazon S3 and enabling versioning added an additional layer of protection, allowing data recovery in case of accidental deletion. Data encryption ensured that all data at rest was protected and confidential. These steps collectively contributed to enhancing the overall security of the cloud environment, ensuring compliance with security standards.

**OUTPUT OF TASK**:

