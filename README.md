# AmazonWS
Cuenta UDEMY: https://www.udemy.com/course/amazon-web-services-aws-v/

AMAZON ws


Cursos desarrollados:
AWS Foundations: Securing Your AWS Cloud
Este tiene una serie de subcursos que hacen parte de la seguridad ...
Intentar buscar los cursos en español


QUIZ SECURITY FUNDAMENTALS(SECRURITY FUNDAMENTALS):
How can AWS CloudFormation be used in an incident response solution?
Deploying pre-configured instances for forensics analysis


Which AWS service feature helps secure your Amazon VPC resources by providing isolation at the instance level?
Security groups

Which statement is true when describing your AWS account root user credentials?
They provide unrestricted access to your AWS account resources.

Which AWS services below can be used in tandem to help protect against DDoS attacks? Select THREE.
Amazon Route 53
Amazon CloudFront
AWS Shield

Which of the statements below provides an example of how AWS helps customers meet their security and compliance needs?
AWS assists customers in integrating their existing control frameworks.

Which statement is true regarding Amazon S3 default (SSE-S3) server-side encryption?
Amazon S3 generates and manages the encryption keys.

Which statement below is performed by AWS as an example regarding security OF the cloud?
Decommissioning storage devices according to NIST 800-88

Which AWS services/features can be used to provide data protection at rest and in transit? Select THREE.
AWS KMS
VPN connectivity
AWS Certificate Manager

Which AWS service manages authentication from social sign-in providers for mobile applications?
Amazon Cognito

Which statement is true regarding the AWS Well-Architected Tool?
It provides information on potential risks in your workload.

Which feature helps secure your Amazon VPC resources by providing isolation at the subnet level?
VPN connectivity

What can be used to troubleshoot network issues, including traffic going into and out of your instances?
VPC flow logs


Where can you find account activity information on API calls performed via the AWS Management Console or the AWS CLI?
AWS CloudTrail logs

Which statement is true regarding Amazon S3 default (SSE-S3) server-side encryption?
Amazon S3 generates and manages the encryption keys.

How can AWS CloudFormation be used in an incident response solution?
Deploying pre-configured instances for forensics analysis

Which statement is true when describing your AWS account root user credentials?
They provide unrestricted access to your AWS account resources.

What type of AWS credentials is required to SSH directly into an Amazon EC2 instance?
EC2 key pairs

Which statements below correctly describe the AWS global infrastructure? Select TWO.
Availability Zones consist of one or more data centers.
Regions have geographically dispersed Availability Zones.

Which AWS services/features can be used to provide data protection at rest and in transit? Select THREE.
AWS Certificate Manager
AWS KMS
VPN connectivity

Which of the statements below provides an example of how AWS helps customers meet their security and compliance needs?
AWS assists customers in integrating their existing control frameworks.

PREGUNTAS COMO TIPO PERSONALES:

What is your primary objective(s) for using AWS Skill Builder? (Select all that apply)
Learn more about new AWS products and services

Which of the following statements best describes your knowledge of Amazon Web Services (AWS) products and services?
I know basic concepts and can work with 1 or 2 services

Which of the following best describes your current role?
Full-stack Developer


EXAM READINESS: AWS CERTIFIED SECURITY SPECIALTY
SAMPLE QUIESTION(S)
Your company is serving content through a CloudFront distribution. Your IR team wants to review data to identify possible indicators of compromise or anomalous events.  In particular, they are looking for source IP address, the original request, the referrer, and protocol information.

SAMPLE QUIESTION(S)
Where should they look for this data?
CloudFront access logs for the distribution

SAMPLE QUIESTION(S)You are the security administrator at BigPhoneCompany, the national telecommunications carrier. You want to be able to automate isolation of specific instances in several public subnets that contain EC2 instances.

SAMPLE QUIESTION(S)What is the simplest way to do this?
Create a lambda function that modifies the security ...

SAMPLE QUIESTION(S)You need to create a logging strategy for your company’s accounts. The logging data must be kept secure and be readily usable for 90 days. After 90 days, the log probably will not be required, but must still be retained for compliance for 10 years.

(SAMPLE)What solution ensures that your logs are securely retained for the entirety of the required duration in the most cost-effective manner?
Send all logs to a central logging account Amazon S3 bucket. Ensure that the bucket is protected with a bucket policy ...deniying all other access ... automaticall moves the data to amazon s3 glacier ...

SAMPLE
Your company needs to monitor active traffic within their AWS environment. They would like to do full packet analysis of traffic to/from specific EC2 instances.
What is the easiest way to do this ?
Use an AMI from AWS Marketplace ...

Your company has created a centralized logging account where all AWS CloudWatch and AWS CloudTrail logs are delivered. You've created a new account using AWS CloudFormation. In this account, you’ve built a Lambda function to stream the generated logs and send them to your logging account's S3 bucket.

 When completing a test run of your Lambda function, a 403 error is returned. What change will quickly resolve this issue without sacrificing security best practices?
Change ...

A recent security review discovered that your company’s ecommerce site accepts an SSL session with a non-compliant cipher.
You must prevent this specific cipher from being used to secure a client’s session when communicating to and from the elastic load balancer.
 What step should you take?
 Create a custom

You are responding to a DDoS attack on your company’s application. The application is composed of a dynamic website running on EC2 instances behind a CloudFront distribution.
The attack is being launched from a large number of IP addresses across many different countries. The attack is targeting valid URI, but seems to have a common misspelling in the query strings that were passed.
 What quick solution could you implement to block this attack?
Write an AWS WAF ACL matching ...

Your company has a public-facing three-tiered application that uses ALB in front of the presentation layer and a second ALB connecting the presentation to the application layer.
The application is being targeted by a variant of a sophisticated SQL injection attack. The attacks are coming from blocks of IP addresses that are in use by existing legitimate customers.
 What is the easiest way to protect your application?
Block the attack by implementing AWS WAF

Your company, BigBank, has set up automated penetration testing and vulnerability analysis from servers under their control (on EC2 instances). This is working well, but you notice that it is causing excessive numbers of alarms in Amazon GuardDuty.
 What is the simplest way to hide these false positives?
Allocate an elastic ip  address for the EC2 instances an then update the trusted IP address list in guardDuty

You are building a mobile app for consumers to post images online. You will be storing the images in Amazon S3. You want to implement user authentication cheaply and simply.
Which one of these options allows you to build a photo-sharing application that meets cost and effort requirements?
Build the application using amazon cognito and web identity

You are the security architect at BigPharma and you are concerned about infrastructure security for EC2 instances. In particular, you know that your company developers will want to make API requests from those instances.
 What should you recommend as a best practice?
Dev should use IAM roles to grant permisions to EC2 ... they should create multiple re-usable roles ...

A corporate web application is deployed within an Amazon Virtual Private Cloud (Amazon VPC) and is connected to the corporate data center via an iPsec VPN. The application must authenticate against the on-premises LDAP server. After authentication, each logged-in user can only access an S3 keyspace specific to that user.
 Which approaches can fulfill these goals? (Select 2)
 The aplication autenticates against LDAP and retrieves
 Develop and identify broker that autenticate against LDAP


Your organization has hundreds of developers, testers and QA staff. You are about to begin using AWS on a large scale for the first time. You want to integrate with your existing identity management system running on Microsoft Active Directory, because your organization is a power user of Active Directory.
 How should you manage your AWS identities in the simplest manner?
USE -- CONECTOR

You have a client whose application creates extremely sensitive data from user input. This data needs to be securely transmitted to a data store and requires end-to-end encryption with controlled access to the sensitive data.
Which of the following options offer the most data protection while still making the data available to authenticated users?
uPLOAD THE DATA AMAZON S3 AND MAKE

When using an encrypted file system to protect your data at rest, what steps are required to ensure that you protect your data and metadata in the most cost-effective and simple manner? (Select 2)
Create an amazon elastic ...
Create a cloudwatch alarm to detect unencrypted file sistems.

You have been tasked with creating a strategy to enforce encryption of your data in transit.
What can you do to ensure that your data is protected in transit and not sent plaintext?
Enable HTTPS

QUIZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZZ
An application running on an Amazon Elastic Compute Cloud (Amazon EC2) instance must use user credentials to access a database. The developer has stored those secrets in the AWS Systems Manager Parameter Store using the default AWS Key Management Service (AWS KMS) customer master key. 
Which steps allow the application to access the secrets via the API?  (Select TWO.) 
aDD THE PERMISION TO READDDDD ....
ADD THE PERMISION TO USE THE AWS KMS KEY TO DECRYPT TO THE ECS INSTANCE ROLE

A company is using AWS CloudTrail to log all AWS API activity for all Regions in all of its accounts. The chief information security officer has asked the team to take additional steps to protect the integrity of the log files. 
Which steps will protect the log files from unintentional changes?  (Select TWO.)
Create an amazon s3 bucket in a dedicated log acountf and grant the others account writeonly access. deliver all log files from every account to the s3 bucket
Enable cloud trial log file integrity validation

A company requires that data stored in AWS be encrypted at rest. Which approaches best achieve this requirement?  (Select TWO.)
when storing data in amazon ebs, encrypt
when storing data in amazon s3, enable

A company is deploying a new web application on AWS. Based on the company's other web applications, it anticipates being the target of frequent distributed denial of service (DDoS) attacks. 
usae an aplication load balancer and autoscaling group to scale and absorb application layer trafic
use amazon cloudfront to prevent malicius traffic from reaching the application

A security engineer must ensure the monitoring of all infrastructure launched in the company AWS account for deviation from compliance rules. Specifically, the engineer must ensure that all EC2 instances launch from a specific list of Amazon Machine Images (AMIs) and that all attached Amazon EBS volumes are encrypted. The security engineer must terminate infrastructure that is not in compliance. 
What are the best solutions to ensure compliance rules are enforced? (Select TWO.)
triger and aws lambda function forom a schedule cloudwatch event that terminates non compliant infrastructure
monitor compliance with aws config rules trigered by configuratioon changes

A company currently has an Amazon S3 bucket hosted in an AWS account. The bucket holds information that a partner account needs to access. What are the most secure ways to allow the partner account to access the S3 bucket in the AWS account?  (Select TWO.)
ensure that the parter sus an eternakl id and tehe makes the request
provide an amazon resources name for the role to the partner account

A company has mandated that all calls to the AWS KMS service be recorded. How can this task be achieved?
enable trails in aws cloudtrail

A company has enabled automatic key rotation for an existing customer master key (CMK) where the customer manages the backing key, when is the CMK rotated?
After 1 year

An AWS Lambda function reads metadata from an Amazon S3 object and stores the metadata in an Amazon DynamoDB table. Storing an object within the S3 bucket triggers the function. How should a company give the Lambda function access to the DynamoDB table?
create an IAM role with permision to write to the dynamoDb table associate that role with the lambda function

A company has an EC2 instance set up in a test environment in AWS. The developer installed the required application and then promoted the server to a production environment. The IT security team has advised that there may be traffic flowing in from an unknown IP address to port 22. 
How can the developer immediately mitigate this situation without impacting the application?
Renmove the rule for incoming traffic on port 22 for the security gropup

Each day, a security team must brief the chief information security officer with a report about which of hundreds of Amazon EC2 instances and on-premises servers lack the latest security patches. The security team must bring all instances and servers into compliance within 24 hours so they do not show up on the next day’s report. 
How can the security team fulfill these requirements?
use aw sistem manager patch to generate the report and install the misins patches on all instances of servers

A company is hosting a website that must be accessible to users for HTTPS traffic. Port 22 should be open for administrative purposes. Which security group configurations are the MOST secure but still functional to support these requirements?  (Select TWO.)
port 443 coming from 0.0.0.0/0
por t22 coming from 10.0.0.0/16


A company has defined a number of Amazon EC2 instances over a period of 6 months. The company wants to know if any of the security groups allow unrestricted access to a resource. Which option best accomplishes this requirement?
use aws trusted advisror to see wich securioty groups have compromides adcess

A company wants to have a secure way of generating, storing, and managing cryptographic keys. The company also wants to have exclusive access for the keys. Which option can the company use for this purpose?
use aws cloudhsm

CURSO # 2
Migrating Your Application to AWS

¿Qué servicio o característica de AWS se utilizará para conceder permisos temporales a un recurso?
AWS Identity and Access Management 角色

¿Qué opción ayuda a los clientes a administrar y controlar de forma centralizada la facturación, el acceso, la conformidad, la seguridad y los recursos compartidos en sus cuentas de AWS?
AWS Organizations

Una forma de garantizar que la cuenta raíz sea muy segura es evitar el uso de la cuenta raíz para las operaciones diarias. ¿Cuáles son los otros tres métodos? (Seleccione tres.) ）
Usar una contraseña segura
Habilitar la autenticación multifactor
Usa la dirección de correo electrónico de tu empresa


¿Cuál es la segmentación lógica de la VPC utilizada para colocar recursos informáticos y de otro tipo para la aplicación?
Subred


¿Cómo se aseguran los desarrolladores de aplicaciones de que sus aplicaciones son de alta disponibilidad?
Crear subredes en al menos dos zonas de disponibilidad


¿Qué características actúan como un firewall virtual para controlar el tráfico entrante y saliente para las instancias que ejecutan aplicaciones? (Seleccione ambos.) ）
Grupos de seguridad
Listas de control de acceso a la red (ACL de red)


¿Cuáles son las ventajas de utilizar Amazon EC2 con cargas de trabajo de aplicaciones? (Seleccione tres.) ）
Escale hacia arriba o hacia abajo de manera eficiente
Pagar solo por el uso
Elija un sistema operativo familiar

¿Qué opción de compra de Amazon EC2 es la mejor para las cargas de trabajo máximas porque permite a los clientes pagar por la capacidad informática cada hora sin tener que firmar un contrato a largo plazo?
Instancias bajo demanda

¿Qué tipos de espacio de almacenamiento están disponibles al migrar aplicaciones? (Seleccione tres.) ）
Almacenamiento en bloque

Almacenamiento de objetos

Almacenamiento compartido de archivos

¿Qué clase de almacenamiento de Amazon Simple Storage Service (Amazon S3) optimiza los costos de almacenamiento al mover automáticamente objetos entre los niveles de almacenamiento S3 Standard y S3 Standard–IA cuando cambian los patrones de acceso?
Amazon S3 Intelligent Tiering(Organización en niveles inteligente de Amazon S3)

Amazon Simple Storage Service (Amazon S3) implementa la seguridad de forma predeterminada. AWS Identity and Access Management (IAM) es una forma de conceder acceso. ¿De qué otra manera implementa Amazon S3 la seguridad? (Seleccione ambos.) ）
Listas de control de acceso
Política de bucket

¿Cuáles son los tres principales beneficios de Amazon Aurora? (Seleccione tres.) ）
Totalmente administrado por Amazon RDS
Rendimiento
Alta disponibilidad y durabilidad

¿Qué servicios administrados de AWS ejecutan bases de datos relacionales, como MySQL, Oracle o SQL Server?
Amazon RDS

¿Cuál es la forma más común de reemplazar la base de datos host?
Ejecución de la base de datos en una instancia Amazon EC2

¿Qué tareas automatiza AWS Elastic Beanstalk por usted? (Seleccione tres.) ）
Infraestructura aprovisionada
Implemente su aplicación
Configurar y administrar el equilibrio de carga y el escalado automático

¿Cómo se me cobra por el uso en AWS Elastic Beanstalk?
No hay cargos adicionales por usar Elastic Beanstalk

La infraestructura como código proporciona coherencia de configuración y ayuda a los clientes a implementar entornos complejos. ¿Qué otros beneficios hay de la infraestructura como código? (Seleccione tres.) ）
Proporcione una limpieza eficiente cuando sea necesario

Proporcionar una única fuente de confianza para implementar toda la pila

Versionar la infraestructura y las aplicaciones juntas

¿Cuál es el nombre de este servicio de AWS que proporciona un lenguaje común para modelar y aprovisionar una colección de recursos de AWS de forma automatizada y segura?
AWS CloudFormation

AWS Quick Starts ayuda a los clientes a implementar de manera eficiente tecnologías populares en AWS. ¿Qué otras ventajas tiene AWS Quick Starts? (Seleccione tres.) ）
Simplifique cientos de procedimientos manuales en unos pocos pasos
Incluye la plantilla de AWS CloudFormation para implementar
Utilice las prácticas recomendadas de AWS para la seguridad y la alta disponibilidad

APAREAMIENTO
AWS SaaS Factory - La ubicación de todo el software como servicio en AWS
Programa de socios de APN - Programas que ayudan a los socios de AWS a crear, promocionar y vender productos basados en AWS
AWS TechShift - Una serie de talleres y recursos para migrar y modernizar aplicaciones

¿Dónde puedo encontrar AWS Cost Explorer, AWS Budgets o el panel de administración de costos y facturación?es decir, la ubicación del servicio
Vaya a la página de inicio de AWS Cost Management,
O seleccione Buscar servicio y escriba presupuestos, facturación o explorador de costos.
es decir, la ubicación del servicio

¿Qué servicio o característica se puede utilizar para administrar y controlar de forma centralizada la facturación, el acceso, la conformidad, la seguridad y los recursos compartidos en la cuenta de AWS de su empresa?
????

CURSO SIGUIENTE-SYSTEMS OPERATOR:

change management- Accessing or affecting any changes in a customer's managed environment
continuity management - Providing backups using standard, existing functionality at predetermined intervals
security and acces management - Configuring anti-malware protection and intrusion detection/prevention systems
patch management - Applying and installing updates to Amazon EC2 instances for supported operating systems

You can register or transfer both top-level and second-level domains with Amazon Route 53.
True

wich of the f0llowing is valid route 53 record?
example.com CNAME cassic 1234567.us-east-1elb.amazonaws.co0m.
example.com CNAME(Alias) cassic 1234567.us-east-1elb.amazonaws.co0m.
sub.example.com CNAME cassic 1234567.us-east-1elb.amazonaws.co0m.(CORRECT)

you can configure TTL value for Alias records
true

weighted- route traffic to multiple resouces in specified proportions
geolocation-route traffic based on location
geoproximity-route traffic based on location of resources or shift traffic from one location to another
simple-single recources that performs given function for domain
latency route traffic to the region that proviodes the best latency
multivalue answer responds to DNS queries with up to heiogt healty records selected at random
failover - configure active-passive failover

you can only create route policies for a records
false

endpoint- specific healt checks require you to configure hostname and path
true

object storage - a flat structure where data is hld in a bucket
block storage whre data is writen as individual pieces to a storage device
file storage is a hierarchy of directories and subdirectories

Amazon S3 tags are key value pairs that apply to a whole bucket or to individual objects to help with identification, searches, and data classification.


What is the size limit of an object uploaded via the AWS Management console?
160gb

What is the data consistency model for Amazon S3 storage request?
Strong read-after-write consistency

True or False: The AWS Snow Family of edge computing only allows uploads using online internet access?
False

Which type of policy includes the principal statement in the JSON file?
Bucket Policy

server side encryption, encrypts an object before saving it to disk and decrypts it when you download the object.


What is a data lake?
A centralized repository that allows you to migrate, store, and manage all structured and unstructured data at unlimited scale.

Which style of URL lists the bucket name first, and makes the URL more user friendly and easy to read?
Virtual hosted-style URLs

What is the upload limit of an object when using the AWS Management Console?
160 GB

How can you organize your objects to mimic a folder hierarchy?
Use prefixes and delimiters to group items.

What is the definition of object based storage?
Object storage is a method of storing files in a flat address space based on attributes and metadata. 

True or False: The Block Public Access feature is enabled by default?
True

True or False:  Bucket names can contain upper case letters.
False

True or False: Amazon S3 is a file based storage platform?
False

How many buckets can you create in a single AWS account?
100


Which of the following formats are supported for inventory report output files?
Comma-separated values (CSV)
Apache optimized row columnar (ORC)
Apache Parquet (Parquet)

Which actions MUST be allowed for the bucket containing the manifest?
GetObject
GetBucketLocation

Which actions MUST be allowed for the source bucket?
GetObject
GetObjectTagging
GetObjectAcl

Which actions MUST be allowed for the destination bucket?
PutObject
PutObjectTagging
PutObjectAcl

Which actions MUST be allowed for the bucket that the completion report will be written to?
PutObject
GetBucketLocation

QUIZ
Cost allocation tags used_______ specifically for billing and tracking your AWS costs on a detailed level.

Amazon S3 Lifecycle rules transition data between storage classes. Which is NOT a supported transition?
S3 Glacier  to S3 Standard


Which storage classes are best suited for long-term object retention of cold data? (Select TWO.)
Amazon Glacier Deep Archive
Amazon Glacier

What is Amazon S3 Glacier provisioned capacity?
Allows you to pay an upfront fee to ensure retrieval capacity for expedited retrievals.

What can Amazon S3 Storage Class Analysis help you determine about your data?
Data access patterns over a period of time

What is a multi-part upload?
A single large object uploaded in pieces using parallel uploads.

The AWS Storage Gateway is made up of three separate offerings - File, Volume, and ____________Gateway.
Tape 

What is the correct retrieval time for restoring objects from Amazon S3 Glacier? (Select THREE.)
Bulk (12 hours)
Expedited (1–5 mins)
Standard (3–5 hours)

What are the benefits provided by Amazon S3 Storage Lens? (Choose THREE.)
No performance impact
Produces actionable recommendations to help improve cost-efficiency and apply data protection best practices.
Provides a single view of object storage usage and activity

Incomplete multipart uploads occupy storage space and can incur storage charges. Which element allow you to set a maximum number of days for a multipart upload to remain in progress? 
AbortIncompleteMultipartUpload

Which two items are types of cost allocation tags? (Select TWO.)
User-defined
AWS generated

Which statement best describes the storage class analysis feature?
Analyzes storage access patterns and transitions data to the correct storage class.

What is the data retrieval time for Amazon S3 Standard?

Immediate

What happens to your data if you are using S3 One Zone-IA and the AZ in which you store your data is lost?
Without the AZ, you cannot access your data.

Which of the following access patterns works best with  S3 Intelligent-Tiering?
Unknown access patterns
Unpredictable access patterns

True or False: S3 Glacier Deep Archive storage class data can be retrieved in 3-5 minutes.
False

QUIZ:
True or False: You must choose one storage class for all your data.
False

How many object tags can you associate with each piece of data?
10

Which storage class can hold frequently accessed object? (Choose TWO.)
Amazon S3 Standard
Amazon S3 Intelligent Tiering

Which storage class can hold archived data? (Choose TWO.)
Amazon S3 Glacier
Amazon S3 Glacier Deep Archive


With Amazon S3 Infrequently Accessed Storage class, what happens to an object that is less than 128 KB?
You are charged for 128 KB.

Object tags are ______________ pairs that help organize your data.
key-value

True or False:  There is no data loss with S3 One Zone-IA if the AZ is lost.
False

Which statement best describes the storage class analysis feature?
Analyzes storage access patterns and transitions data to the correct storage class.

What is the data retrieval time for Amazon S3 Standard?
inmediate


In which situations are you most likely to benefit from using multipart uploads? (Select TWO.)
You upload large objects over a spotty network, such as a mobile network.
Your object size reaches 100 MB.

A team of developers is looking for a simple way to integrate multipart uploads into their existing applications. They do not require any advanced functionality, such as pausing and resuming uploads. Which tool would best meet their requirements?
AWS SDKs (high-level API)

What is an upload ID? 
It’s a unique identifier for your multipart upload. You must include this value whenever you upload parts, list the parts, complete an upload, or stop an upload.

A team of storage engineers need to configure a CloudFront distribution to restrict access to an S3 bucket so that users can access objects only through the distribution. The distribution will use an S3 REST API endpoint as the origin. How can they achieve this?
Create an OAI and update the bucket’s policy to grant read permissions to it.

Which IAM permission allows a user to check whether a bucket has Transfer Acceleration enabled?
s3:GetBucketAccelerateConfiguration

You receive an error message when enabling Transfer Acceleration on a bucket called sales.reports.bucket. You are using the console to do this. What is causing the problem?
Transfer Acceleration does not support buckets with periods (.) in their names.




QUIZ
Which tools will allow you to log object-level operations in your Amazon S3 buckets? (Select TWO)
AWS CloudTrail
Server access logging

What tool lets you send an Amazon SNS notification or invoke an AWS Lambda function based on your AWS CloudTrail logs?
Amazon CloudWatch

Which logging tool guarantees log delivery?
AWS CloudTrail

Which tools check if your Amazon S3 buckets allow public read access? (Select THREE)
AWS Config
AWS IAM Access Analyzer
AWS Trusted Advisor

When Access Analyzer findings show an unintended permission and you fix it, what status does the finding display?
Resolved

Which tool checks that your logging is enabled for Amazon S3 buckets? (Select TWO)
AWS Config
AWS Trusted Advisor

Which tool lets you analyze your server access logs to find insights?
Amazon Athena

-----------------------------------------
subcategory - advanced stacks components
action - create
item - ec2stack
category - deplyment

What two options could you use to share the AWS CloudFormation template in the RFC creation process?
public s3 url
pre-signed s3 url

------------------------------------------------------------------
wwich of the following are initial sync steps?
booting
creating
creating

what is the minimum RAm requirement for the cloudendure failback client?
4gb

what settings can you edit after performing the prepare for failback action?
failback settiong and back to normal settiogs

how can you remove source machines form tge eloucendure user console?
deleting them from the machine actions menu

cloudendure allows you to rep´licate source workloads to wich target infractructure?
specific aws regions

what is the final step of failback?
returnuing the machines to normal operation

what status indicators, for the source machine, must you verify before you start the failover?(choose three)
status is target mechine can be launched
Disaster Recovery lifecycle is tested recently

which of the following tecnologies does cloudendure utilize to enable organizationgs to migrate even the most complex wokloads to aws without down time, disruption, or data loss?
continous block-level replication, automatic machine conversion, and application stack orchestration

when can you initiate the prepare for failback action?
once all the source machines in the project have launched target machines

what sorurce and target environments allow you to perform a fully orchestrated faiback thourhh the cloudEndure user console?
vcenter or aws to aws

what mensaje is displayed at the completion of the cloudendure agent isntalallation?
isntallation finished succesfully

where in the cloudendure user console do you neded to enter tyou generated iam informatioon?
credentials

what are the roles of the cloudendure replication server?
receive the continous block level changes from the cloud endure agents.
take snapshots of the replicated disks

when is the best time tio conduct disaster recovering testing?
periodically

what do you neeed to do to install the cloud endure agent on a linux machine?
run the download and executable commands
c
why are the recovery points important?
they allow you to pick the exact snapshots of your machines that you want to failover to

what source and target environments can you use to perform a faiback with the aid of the cloudendure faiback client?
other infrastructure to aws

what can you use to manage large workloads?
recovery plans
how dows cliudendure disaster recovery oprepare you for faiback?
reversing the directory of data replication from the target machine back to the source machine

where can you locate the machione ID of the cource machine?
machine details-source

what aws identity and access management aiam credentials do you need to configure your cloudendure project?
acces key and secret access key

wich recovery point should be selected whrn performing a fully orchestrated fauklback?
te lastes recovery pont

what needs to be entered into the clouyd endure failbacj client?
disk maping
installation token
source machine id

how can you contact support?
through the aws support center

what action do you need to perform independentenly outside the cloudendure console during a failover process?
redirect traffic from the ´primary site to the disaster recovery site

what si the set of instructions that specify how a target machine(replicated isntance) should be launched called?
is not diagram



Given the following support ticket, how would you improve it?



------

We tried to launch a stack, but it's failing due to an error. Why is this error occurring? We wanted to deploy the stack in our production virtual private cloud (VPC). This is critical for us. (Select THREE.)

Specify which stack had the error, preferably by providing the Amazon Resource Name (ARN).

Provide context about what task you were attempting to accomplish.


Specify the Region where you were trying the operation.

---------------------------------------------------
Developer learning plan

Why is .NET Core the future of the .NET platform?
.NET Core is the recommended path for moving to .NET 5.

Identity Services - Grants the right access to the right people at the right time
Compute services - Provides virtual server hosting, container management, and serverless computing
Monitoring and auditing services - Provides application and infrastructure performance tracking and status details
Storage and database services - Allows for the storage, archiving, and retrieval of information

AWS SDK for .NEt - Makes calling an AWS service as simple as calling a method on an object
AWS Tools for PowerShell - Enables you to control AWS services from the command line
AWS CDK for .NET - Enables you to define your cloud infrastructure as code
AWS Toolkit for Visual Studio - Provides an explorer view of a number of AWS services and several easy-to-use wizards


What is an advantage of hosting .NET applications on AWS?
Provides fully featured services with deep functionalities


Enter a question title here...
Choice 1

An application developer wants to host a .NET application in a containerized environment but does not want to manage the infrastructure. Which AWS compute service fits their needs?
AWS Fargate

Which AWS service automatically handles capacity provisioning, load balancing, automatic scaling, and application health monitoring of compute instances running your .NET application?
AWS Elastic Beanstalk

Which database option is most suitable for a developer who needs a key-value NoSQL database for their .NET application?
Amazon DynamoDB

Which database engine is supported by Amazon Relational Database Service (Amazon RDS)?
Microsoft SQL Server

Which service is used to enable fine-grained access control for users accessing your .NET applications and AWS resources?
AWS Identity and Access Management (IAM)

An application developer recently deployed their .NET application to the AWS Cloud. They now want to provide users with a sign-in using social identity providers such as Google, Amazon, or Facebook. Which AWS service should they use?
Amazon Cognito

Which of these is an AWS extension for a .NET developer tool?
AWS Toolkit for Visual Studio

Which developer tool enables .NET developers to provision their cloud infrastructure through .NET code?
AWS Cloud Development Kit (AWS CDK)


what is the diference between containers and virtual machines?
Containers share the underlying host system´s OS kernel

Which of the following is true about Docker?
Creates container images that can be modified by running containers
Leverages file system layesrs to be lightweight and fast

which of the following is NOT TRUE of microservices architectures?
Require taht all aplications be developed in the same programing languaje

which of the following can be public or private storage for docker images?
Registry

which type of workload would be best to deploy as a service rather than a task?
long running applications

in which task launch type is the infrastructure that supports your containers completely manage by AWS as a service?
Fargate

which ECS task placement strategy minimizes the number of instances in use?
binpack


how do task placement strategies and task placement constraints affect how task are placed tasks on instances?
both strategies are best effort; contraints are binding

which aws service facilitates service discovery through dns in a microservices architecture?
amazon route53

how can access to a secret in secrets manager be controlled?
each task can have its own IAM role with a policy attached
Apolicy can be attached directly to the secret

what is the basic unit of deployment in kubernetes?
pods

what is kubernetes service?
a logical collection of pods  and means to access them

what form of kubernetes does eks support?
native, upstream kubernetes

which components are always managed by EKS?
the kubernetes control plane

what type of service can be accesed from outside the cluster?
nodeport and loadbalancer

how are secrets in secrets manager usually accessed?
through system manager parameter store

what is the recommended method to update EKS worked nodes to a new version of kubernetes?
Replace the nodes with the new AMI and migrate your pods to the new group

------------------------------------------------------------------------------------------
Which of these are recommendations for structuring your Lambda functions? Select all that apply.
separate busines logic from the handler method
minimize the dependencies

Which of these are recommendations for managing serverless applications? Select all that apply.
use a serveless application framework
use a sam template to deploy your serveless applications rather than creating a template in aws cloudformation

Which of these are recommendations for organizing your code repository for serverless applications? Select all that apply.
organize your functions into services, and give each service one deployment template and one code repository

Which of these are recommendations for structuring your development environment for serverless?
create separate aws accounts for each developer if you have management proceses in place to handle it 
separate your production and non production

Which of these are recommendations for managing serverless applications? Select all that apply.
Use a serveless aplication framework
Use a SAM template to deply your serveless applications rather than creting a template in AWS CloudFormation

Which of these are recommendations for organizing your code repository for serverless applications? Select all that apply.
Organize your functions into servicews, and give each service one deployment template and one code repository

Which of these are recommendations for structuring your development environment for serverless?
Create separate aws accounts for each developer if you have management proceses in place to handle it.
separate your production adn non-production environments into different accounts.

Which of these is an appropriate reason to use custom mocks? 
you are tring to test an application that relies on multiple services interacting with each other.

Which of these is an option for debugging your serverless applications?
use your ide debugger on the docker container provided by sam cli

What types of  potential cost savings should you evaluate when comparing serverless vs. server-based design? Select all that apply.
reduce cost of idle server capacity
benefit of shifting operational engineering focus to task better differentiate the bussiness
faster time to market

Which of these statements are true with respect to severless architectures? Select all that apply.
api can use many aws services as lambda event sources, including amazon api gateway, amazon s3, amazon alexa, and amazon sqs
it is a best practice to desingn independent, higly cohesive, and decouopled lambda functions that connect other managed services together.

pywren_______is an open source project that allows you to do extremely high throughput computing jobs using AWS Lambda as the compute engine behind the scenes.

Which of these reflect best practices for serverless development environments and deployment processes? Select all that apply.
give each developer sandbox environment where they can experiment
create independent demo environments for feature branches
automate your build  and deploy process
leverage deployment and appliocation management tools within the community

Which of these are Lambda features that support Serverless Development? Select all that apply.
lets you run code without provisioning or managing servers
triggers on your behalf in response to events
scales automatically
provides built in monitoring and logging

What IAM entities must be included in an execution role for a Lambda function to interact with other services? Select all that apply.
iam policity that defines the actions that can be taken
trust policy that grants "assumeRole" permission to Lambda

Which of these describe a resource policy? Select all that apply.
can give amazon s3 permission to trigger a lambda function
cant grant access to the lambda function across aws accounts
determined who is allowed in

Which of the following statements are true? Select all that apply.
amazon s3 triggers lambda via asyncronous push
amazon api gateway triggers lambda syncronously
if lambda is unable to invoke a function trigerred by a message in an SQS queue, the fallen invoque will go to the DLQ(if one is configured)

Place the Lambda lifecycle steps into the correct order, assuming it begins with a cold start followed by a warm start.
event source triggers a lambda function that has not been invoked in a while
launch container, download code, and initialize runtime
initialize function dependencies then execute code
event source triggers an invocation of lambda function that has recently been invoked
thaw container then execute code

entry point that aws lambda calls to execute your lambda function - handler method
property for remainning execution time until function will be terminated - getRemaining TimeInMillis
Object with information about about the event that triggered the lambda function - event object
generated by aws, provides metadata about the execution - context object

Authoring using the AWS Management Console is best for:
simple one-function applications with no custom libraries; experimentation

You've been asked to troubleshoot a Lambda function that is in production. You've been told that it runs for 5 minutes, and you've been asked to  reduce its duration to save on billable costs. Which of these actions would you take? (Select all that apply.)
confirm wheter 5 minutes is the typical duration through production monitoring
test at higher memory configurations and compare the duration and cost at each configuration
chechk to see if there are sdk components in the deployment package that arent necessary

You may want to set a concurrency limit (or reserve) on a function in order to: Select all that apply.
manage cost 
regulate how long it takes you to process a batch of events
match it with a downstream resource
handle anticipated peaks

In a stream-based polling event, the number of concurrent executions will equal:
the number of active shards

cloudformation template - like a house blue print, lets you treat infracstructure as code
SAM CLI - tool for local testing and debuging of serveless aplications
SAM template - streamlined cloudformation template for serveless aplication
deploy - SAM cli command for deploying a SAM template
Serveless application repository - used to share a find serveles applications

Which of the following statements are true? (Select all that apply).
when you create a lambda function, there is only one version: the latest version
versioning is an option you can enable for you lambda functions
you can reference any versions with alias
you can reference a version or alias in the arn

review metrics on invocations. errors and trottling for a lambda function - amazon cloudwatch
audit actions made against your applications - aws cloudtrail
review trail details about an invocation to identify potential bottlenecks - aws x ray
manually review errors for lambda invocations that failed and must be addressed

--------------------------------------------------------------------------------------

Which of these are features of Amazon API Gateway? (Select all that apply).
allows to you run multiple versions of an api
incorporates a cloudfront distribution
providesw built in cloudwatch monitoring
allows you to generate sdks

regional endpoint - provides lower latency for applications that invoke your api within the same region
private endpoint - request are only routable within a single vpc that you control
edge optimized endpoint - deploys a fully managed cloudfront distribution

cognito  authorizer - after a user is autenticated agaisnt the user pool, they obtain an OIDC token
IAM autorizer all requests are required to be signed using aws sig v4 
Lambda autorizer api gateway supplies an atorization token to a lambda function

YOU CAN THROTTLE APIS WITH USAGE PLANS 
THE METHOD BY WICH LIMITS ARE MEASURED AND THROTTLED IS BASED ON THE TOKEN BUCKET ALGORITHM
YOU CAN OVERRIDE DEFAULT STAGE LEVEL THROTTLING

---IDEATON
WICH APPLICATION in ultimatix is currently being promoted to organize ideaton?
prime,knome,knowmax,none

you are about to launch one ideaton in prime. the evaluation criteria´s are (1) innovative -weightage - 0.4 (2)replicability -
what will be weigtage for third attribute "feasibility"
0.5, 3, 0.3, 0.2

what are three phases of ideaton as per current framework?
preideaton,ideaton,postideaton-ideaton,customerdemo,implementation-captureidea,evaluate,reward-none

implementation and bussiness value delivery is part of wich phase of ideaton
pre ideaton,ideaton, postideaton, none

which application in ultimatix is used to report bussiness value deilvery based on implementation of ideas?
primeevent,impact,knowmax,pwb

who will be able to evaluate ideas generated in ideaton and provide rating
jury, organizers, sponsor, none

------------------------------------------------------------------------------------
Cognito authorizer - After a user is authenticated against the user pool, they obtain an OIDC token.
IAM authorizer - All requests are required to be signed using AWS Sig v4.
Lambda authorizer - API Gateway supplies an authorization token to a Lambda function.

you can throttle apis with usage plans
the method by wich limits are measured and throtled is based on the token bucket algorithm
you can override default stage level throttling

you can grant permision to invoke an api with execute-api
you can grant permision to manage an api with apigateway
resource policies can restrict access by account

if you choose to configure resource as a proxy, it will automatically create a special http method called any
integration options include lambda function http endpoint aws service mock vpc link

a stage is a snapshot of the api and represents a unique identifier for a version of a deployed api
caching and usage plans are set at the stage level
you can use stage variables in conjunction with aws lambda aliases to support safe and flexible deployments
you can use stages with canarydeployments to test new versions

What does this section of a SAM template do?
AWSTemplateFomatVersion: '2010-09-09'
Transform: AWS::Serverless-2016-10-31
Tells CloudFormation that this is a SAM template

Which of these appears to be the root cause?
Throttling on the method at the stage level

What appears to be the root cause?
Resource policy associated with this API prevent access.

-----------------------------------------------------------------
AMAZON DYNAMO DB FOR SERVELESS ARCHITECTURES
Which of the following are true of DynamoDB tables? (Select THREE.)
All items must have a partition key. The unique primatry key inlcudes a partition key and optional sort key.
Read and write capacity are managed independently.
Tables can scale to any data volume.

Which of the following workload characteristics might be a good fit for DynamoDB? (Select THREE)
The data is "hot" - serving real-time, transactional, operational, interactive uses.
The data must be stored in a higly available, durable, and highly scalable manner.
The session states for your application need to be stored off your instances.


One basic factor for success with DynamoDB is: (Select ONE.)
choose a high cardinality partition key for even item and request distribution

Which statements about consistency are true? 
DynamoDb acelerator dax passes strongly consistent reads throug but does not cache them
strongly  consistent reads can be made via a vpc endpoint
local and global secondary indexes both support eventually consistent reads
you can make two eventually  consistent reads(each up to 4kb) for one rcu
al succesful writes are redundanttly stored and durable -  there is no eventual or strong consistency choice to be made for writes

Local secondary indexes can only be defined at the time of base table creation – they cannot be deleted without deleting the base table. True or false?
true


Time-To-Live (TTL) can be used to have DynamoDB delete expired items from a table without being charged for WCU consumption. When you set an attribute for use by TTL, what is the value you should set for that attribute to result in expiry?
the epoc timestap(with unit se3conds ) after wich the item can be removed.

Which of the following statements about DynamoDB streams is false?
Dynamodb streams can be used to audit read activity for a table.

Optimistic concurrency control in DynamoDB provides a form of locking. Which is the correct description of the mechanism?
Read, transform, conditionally write, retry as required.

Which of the following is a commonly recommended serverless pattern for aging out DynamoDB data to a cold storage tier?
Enable dynamodb streams and use ttl to expire older items. a lambda function is trigered on the change and writes the deleted item data into s3 via kinesis firehose

Which of the following are parameters to DynamoDB Auto Scaling? (Select all that apply)
minimum capacity
maximum capacity
target utilization

The business has asked you to build a résumé submission service to connect to their job listing webpage. The service needs to integrate with their legacy system to match the submissions to existing candidates. Very high bursts of traffic are expected when a new job is posted, and you don't control the UI layer.  The order in which the resumes are processed is not critical. What serverless patterns make the most sense? Select THREE.
Use an SQS queue to receive and respond to requests coming through API Gateway.
Use a standard SQS queue as an event source for Lambda.
Use a Lambda function to initiate a Step Functions flow that orchestrates the integration with the legacy system.

You have an internal service and need to minimize calls between client and service. - Trusted webhooks
You want a two-way, persistent connection between the client and the backing service. - WebSockets with API Gateway
You want to implement a serverless approach with minimal rework to existing services. - Client polling
You have an app with rapidly changing, high volumes of data. - WebSockets with AWS AppSync

Which of these scenarios points to using the claim check pattern?
You have an API endpoint connected to an SQS queue that clients use to post high-resolution video files for processing by a Lambda function.

Select the scenarios where you might select Kinesis Data Firehose for data processing. Select THREE.
You want to ingest a very high volume of data and store it to Amazon Redshift.
You want to ingest a very high volume of data, transform its format, and store it to Amazon S3.
You want to simplify retry handling on streaming data, and order of records in the stream is not critical.

You're setting up an Amazon SQS queue as an event source to a Lambda function that takes an average of 3 minutes to process each message. Select the most appropriate configuration options as a starting point. Select THREE.
Set the batch size to 4 or lower.
Set the visibility timeout on the queue to 6x the function timeout.
Configure a dead-letter queue.

Which of these statements about AWS Step Functions States Language are true?
Task and Parallel states can have a field named Retry. An individual retrier represents a certain number of retries.
You can use a Retry or Catch field to handle timeouts.
The Amazon States Language defines a set of built-in strings that name well-known errors, all beginning with the States. prefix.
The reserved name States.ALL is a wildcard that matches any error name.

Subsegments - You need a more granular breakout of the work done in a request to resolve the issue.
Service graph - Customers have reported issues using a service, and you need a quick sense of status.
Annotations - You want to be able to group traces across application operations to compare performance.
Traces - You've identified failures at an integration point and want to review individual requests.

Migration questions to answer:
"Let's talk about where we want to be as a development organization next year and the skills we need our developers to grow to get there."
"Let's look at what it would take to adopt a 'serverless first' strategy for new features only."
"Do we have any 'low-hanging fruit' like cron jobs or workers listening to a queue that we could experiment with?"
"Who owns the data and who uses it?"

Spiky, unpredictable compute workload -  AWS Lambda
Horizontal scaling and millisecond response times for transactional data - Amazon DynamoDB
Read transactional data from a DynamoDB table and index it to other data stores - Amazon DynamoDB Streams
Lift and shift an existing application to serverless with minimal rework - AWS Fargate
Sub-millisecond read and write latencies for a gaming leaderboard - Amazon ElastiCache for Redis
Model state changes to transactional records in a cryptographically provable manner - Amazon QLDB

Your service uses an SNS topic called "Profiles," which is used to notify customer service when a customer updates details on their website profile. Customer service wants to provide a personalized follow-up for customers based on whether they select a preference for delivery or pick-up service. What approach would you recommend to process each of these preference updates differently?
Modify the existing Lambda function that publishes the Profile topic to include attributes for delivery preference and pickup preference. Use SNS filtering to determine which subscribers get those messages.

Which of these statements about serverless scaling are true? Select all that apply.
With serverless, you don’t have to set up Auto Scaling groups and subnets, because you’re using managed services that have built-in horizontal scaling, security, and high availability.
You need to evaluate trade-offs across the architecture; look at service limits end to end to identify potential bottlenecks; and balance performance requirements, costs, and business impact.
For asynchronous sources, concurrency is measured as average function duration * request rate. For streaming invocations, there is a limit of one concurrent invocation per shard.

You recently deployed the serverless order processing service into production, and monitoring reveals failures on a Lambda function that integrates with a slow-running query on the backend that can't keep up with the request volume. What might be an option that you could implement from API Gateway?
Use throttling on the API method.

After someone made an update to an SQS source queue attached to a Lambda function, which was also updated, you got a report of an increased number of messages hitting the dead-letter queue. Which of these might be the cause? Select THREE.
Concurrency limit on the function changed from 10 to 4.
Batch size * average message processing time > 15 minutes.
There is increased traffic, and the rate of errors is a proportional increase.

Which of the following statements reflect recommended approaches? Select TWO.
DynamoDB on-demand mode is a good fit if you have to track the cost of individual transactions.
Provisioned capacity may be the better choice if you have a very consistent, predictable workload.

Both Step Functions and Amazon SNS can help you to scale your serverless applications. Which of these describe guidelines for using these services to support scaling your application? Select THREE.
Use wait states and callbacks in Step Functions to reduce costs when your workflow has to wait on other tasks to complete.
End a Step Functions activity that is stuck waiting on a response when something has failed with TimeoutSeconds.
Use AWS Event Fork Pipeline applications to deploy pre-built applications that use SNS to execute common tasks in parallel.

Which of these is an advantage to using Kinesis Data Streams enhanced fan-out?
It gives more bandwidth to multiple consumers of the same stream.

Which of these is NOT a recommendation for testing serverless applications?
Iterate on your testing until you get an error-free result at your estimated peak load.


AWS IAM - An admin wants to limit the actions a Lambda function can take on a DynamoDB table.
AWS Lambda authorizer - A developer wants to secure their API using custom business logic.
AWS Systems Manager Parameter Store - A team wants to share secrets across their Lambda functions in a single AWS account.
AWS WAF - A security team wants to block traffic to their website that originates from Russia.
AWS Secrets Manager - A security expert wants to share sensitive information across multiple AWS accounts.
Amazon Cognito - A website wants to allow users to sign in through a third-party application.

X-Ray - A developer is investigating higher than normal latency for requests to one of their APIs.
CloudWatch Logs Insights - A team wants to search and query the logs for their API.
CloudWatch Logs - An engineer wants to see in plaintext what parameters are being passed into a function.
CloudWatch metrics - A developer needs to check how many times a Lambda function has been invoked.


Your IT department has concerns about giving each of your developers their own AWS account and permission to make code updates. Which of the following suggestions is not a valid response to the stated concern?
Can we maintain a 2-year history of API activity? 
CloudTrail will automatically maintain a complete history of events for the account and write them to an S3 bucket for analysis.


Your company is developing a serverless banking application. The company is about to release a new feature, allowing users to chat with a representative inside of the app. Your manager asks you to make sure that the new feature is delivered as seamlessly as possible.
Which of the following choices will help your team deploy this new code successfully? (Select all that apply)



Audit changes by monitoring AWS CloudTrail and Lambda CloudWatch metrics.
Have the ability to halt or roll back bad deployments.
Deploy changes through a planned and automated process.

SAM template - AWS CloudFormation compatible template using shorthand syntax
SAM package - Creates a deployment package for your template
SAM deploy - Deploys your template into an AWS CloudFormation stack
SAM CLI - Allows you to test your code and emulate the Lambda environment locally

Pulling configuration data from Parameter Store may incrase latency when you call your Lambda function. How can you reduce this latency, while maintaining security best practices?
Pull configuration data from Parameter Store and store it in a global variable. Allow function code to check if you need to pull or update the parameter.

Alarms - Helpful to trigger the rollback process
Deployment preferences - This is where you choose whether you want a canary, linear, or all-at-once deployment
Hooks - Sanity checks to test and perform actions against your code
Post-traffic hook - Executed after traffic shift
Pre-traffic hook - Executed before the alias can accept traffic

Your team is developing a serverless dating application for dogs. Your manager asks you to architect a CI/CD pipeline for all new updates to the application to go through, making sure there are no Amazon EC2 instances hosting them.
Which AWS services do you use to help architect the pipeline? - Use CodeCommit for version control, CodeDeploy to deploy the application, and CodePipeline to trigger the deployment once a developer pushes to CodeCommit.

PRACTICE TEST:
A team of developers created a serverless, distributed application on AWS. For custom business logic and application code, they're using Lambda. They're using API Gateway in front of their Lambda endpoints and using Amazon S3 as the storage system for their data. The team wants to deploy a new version of their application but needs the ability to roll back automatically if a resource isn't properly built out.
How can the team best meet this requirement?  
Use the AWS Serverless Application Model to define the latest version of the application.

A development team has just finished migrating a stable application to Lambda. They're now looking to release a patch version of their application in a safe and gradual manner. The team is planning on sending 10 percent of traffic to the patch version for 30 minutes before directing all of the traffic to the new function.
Which of the following strategies could the team use to test out their new feature? Select TWO.
Use the SAM to configure a Canary10Percent30Minutes deployment preference.
Enable traffic shifting for an alias using the Lambda API.

The command SAM ____deploy____ will deploy your SAM template. 

A developer is creating a distributed, serverless application, made up of Lambda functions, APIs, DynamoDB tables, and Amazon S3 buckets. Lately, the developer has been noticing an increase in latency when performing certain API calls.
What AWS service or feature might help them troubleshoot the performance issue? 
Use X-Ray to dig into the appropriate trace segments.

A Lambda function must access a database using a connection string and a regularly rotated password. These items must be stored securely and cannot be hardcoded inside of the application.
Which of the following AWS services can help accomplish this? Select TWO.
AWS KMS
AWS Systems Manager Parameter Store

A developer is investigating performance issues in an application. The developer finds that one of the Node.js Lambda functions is a bottleneck and performing poorly compared to the other functions.
Which of the following will not help the developer increase the performance of the function?
All of the answers may help increase the performance of the function.

Which of the following are true about Amazon SQS and Lambda? Select TWO.
If a Lambda function returns errors when processing messages, Lambda decreases the number of processes polling the queue.
Lambda has a default of 5 parallel processes to get things off of a queue.

True or false? With Kinesis Data Streams, there are no error handling configurations  built-in to the service.
False

A team of developers has an application that currently runs off of Docker. You recently read about serverless technologies, which aim to remove infrastructure management burden. When you bring this up with your team, they retort that the application "just can't do serverless." The team states that they don't want to have to rewrite the application and don't think that their long-running tasks are suitable for serverless.
Which service provides the least infrastructure management burden on the developers but still meets the team's requirements?
AWS Fargatef


A company is building an ecommerce application with an ordering workflow. When an order is placed, they need to communicate status back to the calling client. They need a pattern that reduces the number of API calls required and lets the client filter out data that it doesn't need.
Which of the following patterns for communicating status updates would be the best option?
WebSockets with AWS AppSync

A company owns an ecommerce website that sells dog pajamas. Whenever an order is placed for a product, the company would like to send an email alert to the customer and at the same time, process the order and update the inventory database. After a popular talk show host talked about the website, the company is having issues processing orders as they're coming in. They often create duplicate orders for their customers.
Which of the following architectures would meet the company's requirements and create a better customer experience?
Use the SNS fan-out pattern. When the order is placed, send a message to the SNS topic, with customer email addresses and an  FIFO SQS queue as the subscribers. Use Lambda to poll the queue, filter the message, and update the database.

Your Lambda function is not processing Kinesis Data Streams records in a timely manner, and the IteratorAge metric is increasing on your Lambda dashboard.
What is the best strategy for dealing with this?
Reshard to increase the number of shards in your stream.

A company is designing a Step Functions workflow, made up of a series of Lambda functions and a DynamoDB table. The application seems to have a very consistent, predictable workload, and the cost is high. You have been hired to analyze their application architecture and give cost-saving recommendations.
Which of the following options may lower the cost of their architecture? (Select THREE)
Use wait states and callbacks in Step Functions.
Use AWS Lambda Power Tuning.
Use provisioned capacity for DynamoDB.

A team of developers noticed that one of their Lambda functions keeps failing. One of the team members wonders why the service did not retry the request.
Which of the following could explain why the function was not retried?
The team is using a synchronous event source to invoke their function, which has no built-in retries for a failed or throttled request.

-------------------------------------------------------------------------------------------------------------------------------------------

Select the answer that best describes DevOps:
DevOps is the combination of cultural philosophies, practices, and tools that increases an organization’s ability to deliver applications and services at high velocity.

Which of the following best describes the challenges associated with traditional software development methods?
Traditional software development methods often involve monolithic architectures that are difficult to update and deploy, development methods that are not iterative, and have long release cycles.

Your management team has decided that they want to move from their current traditional software development model and adopt a DevOps model. What changes will they need to implement to move to DevOps?
Moving to DevOps requires a cultural shift, implementing DevOps practices, and using the right tools to automate processes.

Your manager is concerned about moving to DevOps because he believes that all existing tools will need to be replaced with AWS tools. What can you tell him to alleviate his concerns?
Tell your manager that DevOps is a methodology and not an AWS product. Let him know that only tools that are not optimized to work in a DevOps environment should be replaced. AWS has great tools, but also supports tools from many industry-leading vendors.

Which monitoring and observability service would be most useful for debugging and tracing distributed applications, such as those built using a microservices architecture? (Select the best answer.)
AWS X-Ray

You are part of a DevOps team that is planning to set up, patch, and maintain the build server software. Your team does not want to own the managing of or building of hardware or software. You want a tool that automatically scales to meet your build volume, immediately processes each build you submit, and can run separate builds concurrently. Which one of the following services will provide the team with the functionality needed?

You are part of a DevOps team that is planning to set up, patch, and maintain the build server software. Your team does not want to own the managing of or building of hardware or software. You want a tool that automatically scales to meet your build volume, immediately processes each build you submit, and can run separate builds concurrently. Which one of the following services will provide the team with the functionality needed?
AWS CodeBuild

Your company is a global IT enterprise that recently adopted DevOps. Your team has chosen AWS CodeDeploy as a deployment tool to handle application deployments. Which of the following features makes it a right choice for automation?  (Select FOUR.)
It can deploy to on-premises and Amazon EC2 instances
You can extend deployments to multiple regions.
You can perform zero-downtime deployments.
It works with a variety of configuration management, continuous integration, source control, and deployment systems.

What are the main benefits of implementing DevOps? (Select SIX)
Increased speed
Improved collaboration
Improved security
Rapid delivery
Scale quickly
Reliably deliver quality applications


Your customer has decided to adopt DevOps. Their DevOps team is choosing the right tools for the source control process. They would like to know how AWS CodeCommit differs from other Git-based source control systems. What will you tell them to help them understand the differences? (Select FOUR)
There is no need to host, maintain, and backup your own source control servers.
It automatically encrypts your files in transit and at rest.
It is built on highly available, redundant, and durable AWS services.
It increases the speed and frequency of your development lifecycle by keeping repositories close to your builds.

Your IT enterprise has recently adopted DevOps and wants to automate their software delivery process. You want to model the full release process for building your code, deploying to pre-production environments, testing your application, and releasing it to production. Which one of the following AWS services will enhance your ability to further integrate with other AWS and third-party products?
AWS CodePipeline

in aws wich secutiry aspects are the customers reponsibility

--------------------------------------------------------------------------------------------------
Networking Learning Plan

ns1.amazonaws.com is the autoritatuve name server of the amazonas.com domain where should the glue records be created

in the hosted zone of com. TLD


DIG IS A COMMAND LINE UTILITY THAT´S USEFUL IN TROUBLESHOOTING MANY COMMON DNS RESOLUTION ISSUES(TRUE)

Configuring and deploying amazon vpc with multiple subnets

What is the maximum number of AWS Regions in which an Amazon Virtual Private Cloud (Amazon VPC) can be deployed?
1

Is the following statement correct: To ensure high availability, you should make your subnets span across more than one Availability Zone (make them Multi-AZ).
No, because it is not possible to make a subnet Multi-AZ.


True or False: The Amazon Virtual Private Cloud (Amazon VPC) is where all Amazon web Services (AWS) resources are launched.
False

In order for resources in your public subnet to reach the internet, they need to be provided with what kind of target? 
Internet gateway

---------------------------------------------------------------------------------------------------------------------------------------------
AWS Identity and Access Management (IAM)

Security group - Ensure that only instances from your IP address can access a specific Amazon EC2 instance
AWS Identity and Access Management (IAM)- Giving your admin permission to create new subnets
VPC Flow Logs- Tracing network activity to a specific IP address
Amazon CloudWatch - Detecting that the database is suddenly experiencing extremely high read rates
Network Access Control List (network ACL) - Keeping all instances in your mail server subnet from reaching your database subnet


True or False: Since Amazon VPC is highly available by default, there's no need to provide a second set of resources in a second subnet. If the resources in one subnet fail, it automatically fails over to a new subnet.
False

What would you need to configure a second subnet with to maximize the availability of resources?
Availability Zone

True or False: Each subnet needs its own separate route table.
FALSE

You can use Elastic Load Balancing to provide which of these for your infrastructure:
Traffic management between resources in different subnets
Automatic failover from unhealthy connections to healthy ones
Automatic registration of new healthy instances to your load balancer

Stateful is allowing traffic in and the response out automatically.
Stateless is allowing traffic in and the response blocked from leaving unless explicitly permitted by a rule. (Select TWO.)
Security groups are stateful.
Network Access Control Lists (network ACLs) are stateless.

How many Availability Zones can you use in one Amazon VPC?
Up to as many Availability Zones as are in that AWS Region.

For which of the following is a default route table provided automatically? (Select TWO):
Each Amazon VPC you create
Each subnet you create

What is the standard default address range used to route all outbound traffic to an Amazon Virtual Private Cloud (Amazon VPC) internet gateway?
: 0.0.0.0/0

Classless Inter-Domain Routing (CIDR) blocks specified in route tables must be unique and cannot overlap.
False

Select all true statements. Elastic Load Balancing (ELB) ... (Select TWO.)
bvg              

Select all true statements. Elastic Load Balancing (ELB) ... (Select TWO.)
Is a managed service and is highly available by default.
Load balancers can be internet facing or internal facing.

Applications - Private with routes to the public subnet
Data - Private with NO routes to the public subnet
NAT solutions - Public

Assuming the choices on the left are your chosen Classless Inter-Domain Routing (CIDR) block sizes, match them to the appropriate subnet on the right based on the multi-tier Amazon VPC architecture from this course.
/20 - Private (Applications)
/21 - Private (Data)
/22 - Public

Which of these traffic patterns is correct for the multi-tier design pattern?
Internet gateway -> Application Load Balancer -> Applications -> Data -> Applications -> network address translation (NAT) solution -> internet gateway


14 de marzo 2022
lambda
function handler

sehablaunpocodelas respuestas comunes delos serviciosusando lamba(errorhandling )
lambda limits figura(limitslambda.png) 

ejemplito con lambda
https://sharablenotesandlinks.s3.us-east-1.amazonaws.com/lambda-demo.py?response-content-disposition=inline&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOb%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCmFwLXNvdXRoLTEiSDBGAiEA33JhaO0pTYLA%2FhamAjogalwYgMIKiv3Uesam8ftSq8kCIQDjdm54hPWKdPiWdWn9OnDfatufegrPR92xDRENrcNG5Cr7AghfEAMaDDIxMTM1Mzc4NDExOCIMdzg42GWeXYKFQzfbKtgCHYsDDhk4Gs98ikvqsDjW7gQ3wZLQpx9xG9S6k4YSQLqKWmq0sSxWGRuWLv9MpBtF8but7j%2BPMMt1JrRJX%2BHgEfYHCCD5thWJjsrnHCTiq58jheV1lG2tnta%2BGPk1MsH7OoMNHYnSAFiJt1EpWc3TH20g5J4FiVkWTT0xCb6qMZ24rsMlF%2Fb%2FEYRaEi1iar7DHo96fE%2BqN1Rentbo058ARGc0U%2BOr8%2BUbc%2BPt8XLpoHEOQBrxj0S0J8v7nbQ4IfYmmIj1iYFiKv%2BmQuIEahInuZrW8nNo35yFUeSmVuMytNPiX5C%2Bx%2BZt2TB%2FTELY4W5M%2Byvu8EgLqY6IHawo%2Fe%2BrR%2BunBQQ8FLP%2FBrDuOFR1RGqQGHadsyuSaTJNekShPldsOSPjipkqXt4WD%2FPkNZ18cVAy12zkRYMePu6QTVp0nTXxRcZ2LD2wIiAbHA%2FY%2BpDzqZnDdfnGIFgwp9K6kQY6sgIt93i6nI%2BHarPjoNFFWMYlnYgVoiCbyKkHUG0JpZ%2Be1y7DTQoJIu8p9v%2BGd0Bgx6N478mmKnX5f5B6YKzq0FGupY2LjWarAUlYueAahIbZZaU153osKCBifGXIEVEwg5bEMkRKKTfye4ZdRPdSOYixwc5gnigxFE8VOnqAcOrOml5TPGsnq%2F8Upc8u7KNke9cvQoLU43Us9aOe63%2FoiAeFL8LNbA3zJ7N0RNQbSPxL4Tix7Nqc62wh83aqIbaIzJipi5azc5zLacq52psAIt41GRaxbjftzISJNfYHwEpLuVCk8lz1ObWrP8U1YjnF8ue1qVCrTneTqfDWZmql37IgCLkteeBVGB4Qrfix6wTixrdfsXskOxk9IrbHV94rOynrGt36%2B3BjMTnxd3r5CP1cqrA%3D&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20220314T141556Z&X-Amz-SignedHeaders=host&X-Amz-Expires=900&X-Amz-Credential=ASIATCNNKZ43LF5PTTXG%2F20220314%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=30d11fed71eed471cef64033e680846e7d6d6d8de4d84da4818f94477f6289ca

Las guías están en Python 3.9

WebSocket
WebSocket es una tecnología que proporciona un canal de comunicación bidireccional y full-duplex sobre un único socket TCP. Está diseñada para ser implementada en navegadores y servidores web, pero puede utilizarse por cualquier aplicación cliente/servidor

Aquí se crean registrosen customer list:
https://tachyonknowledge.com/contact-us.html

15 marzo 2022
Greetings of the day folks! Today's Agenda:
Demo: Lambda and API Gateway Integration 

Lab# 5 

M#11 

Demo: SAM and Step Function 

Tachyon, the nextgen software products as a service. TacDev is responsible for all developments of the Tachyon. TacArc coordinates with TacDev and TacOps. Tachyon has all forms of data like its web styling and scripting, course catalogs, images and TOC, which may be static. Tachyon has time series data from its live sessions, videos and audios which has dynamic schemas. Tachyon has transactional data which maintains a strict schema. Tachyon would not be paying for any idle resources, therefore would use all serverless resources with proper orchestration and workflows. Tachyon architecture is highly decoupled and performant by using microservices and secure endpoints. Tachyon Data is secure while in transit, at rest and while in use. Tachyon is agile and cloud native (even its dev, test, stage and production workload runs on cloud/multi-cloud)! Tachyon Practices latest software design patterns and practices, it has hundreds of releases per day with proper customer feedback implementation. All Compliances are met in the CI/CD pipelines phases ...

Monolític@, microservicios, 

quiz of the day figura(Serveles-microservices-monolitic(oneServer).png)

crear una máquina de estados de función: https://docs.aws.amazon.com/step-functions/latest/dg/tutorial-state-machine-using-sam.html

16 de marzo
ya casi tenemos el examen
hablar para aplazarlo un poco(en caso de que sea demasiado pronto)

Hablamos de Amazon cognito
quiz cognito (quizcognito.png)

Se le trabaja a este lab: Developing on AWS - Lab 6 - Capstone - Complete the Application Build

Pool Id ap-southeast-1_5nqZSBhvi
Pool ARN arn:aws:cognito-idp:ap-southeast-1:765075024777:userpool/ap-southeast-1_5nqZSBhvi

quedé en la parte donde se abre cloud9

17 de marzo 2022
Q1. With respect to AWS certification exam, which module or topic we have to give more efforts as compared to others, which module will have more weightage and domain specific questions? 

Answer: 

Certification Related 

1. DVA C01 Links: AWS Certified Developer - Associate 
 
https://aws.amazon.com/certification/certified-developer-associate/ 
 
2. Sample Exam Questions 
 
https://d1.awsstatic.com/training-and-certification/docs-dev-associate/AWS-Certified-Developer-Associate_Sample-Questions.pdf 
 
3. AWS Certified Developer - Associate 
 
(DVA-C01) Examination Guide https://d1.awsstatic.com/training-and-certification/docs-dev-associate/AWS_Certified_Developer_Associate-Exam_Guide_EN_1.4.pdf 

Q2. Minnd Map (https://d1.awsstatic.com/training-and-certification/docs-dev-associate/AWS-Certified-Developer-Associate_Exam-Guide.pdf) 

**If you're reading after a gap!!! 

The Unlimited Mind: Master Critical Thinking, Make Smarter Decisions, Control Your Impulses 

Minnd Map  

2: Security 26% Domain – IAM, Cognito, ACM and ASM 

3: Development with AWS Services 30% Domain – Service Client, Resource APIs for C|S|N  

4: Refactoring 10% Domain – Caching, Dependency isolation 

1: Deployment 22% Domain – CI/CD 

5: Monitoring and Troubleshooting 12% Domain – CloudWatch and X-Ray 

***If you need some recommended books name, pl. let me know 

Q3. [8:50 PM] Mohd Ahmad (Guest) 

    Hellp SP, You said give your certification when you feel you are ready.....chow onc feel he or she is ready? like if we are able to score good marks in Test? 

Ans: Please join exam readiness workshops for developer associate, attempt practice exams for developer associate and attempt any assessment quizzes for developer associate before you plan to write the certification exam! 







QUIZ DEL DÍA(RELACIONADO CON TEMAS ANTERIORES) figura quizEnding.png


Hacer el lab de XRAYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYY

EN EL CORRÉO ESTÁ UN EXAMEN DE PRUEBA...














































































