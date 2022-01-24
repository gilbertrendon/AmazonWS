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



























