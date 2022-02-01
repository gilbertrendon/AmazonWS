# AmazonWS
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
