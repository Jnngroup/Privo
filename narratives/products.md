name: Products and Services Narrative
acronym: PSN
majorRevisions:
  - date: Jun 1 2018
    comment: Initial document
---

# Products Narratives

# Products

## AMAZON WEB SERVICES CONSULTING

AWS is the largest cloud computing provider in the world, larger than the next 14 cloud providers combined. Theyoffer the ability to rent computing capacity by the hour so businesses can avoid the capital expenditures of acquiring and maintaining their own IT infrastructure. AWS offers a wide range of managed IT infrastructure services such as Route 53, their managed DNS service; S3 their managed object stored service; and EC2, there managed compute capacity service. Thousands of businesses migrate workloads from on premise servers to AWS every week. PRIVO IT, LLC provides consulting services to businesses to help them plan and manage the migration to AWS.
Managing the migration requires a deep knowledge of traditional, on premise IT infrastructure combined with a deep knowledge of the AWS platform which is a completely new architecture. Once the customer’s workloads have been migrated to AWS, we offer on-going maintenance, monitoring, and security services for their AWS infrastructure.


## MANAGED SERVICE PROVIDER

For our MSP business, we provide help desk services and IT infrastructure support for local, Boston Area businesses. For most of our MSP customers we are their entire IT department, handling everything from end-user support to managing their servers and networking equipment, to helping them make strategic IT decisions such as budgeting and disaster recovery planning. Most of our support is provided remotely by telephone, leveraging our LabTech agent to connect to customer computers remotely.

### Architecture

For AWS customers, PRIVO IT, LLC provides support and security for the IT infrastructure (computers, storage, databases, and networking), operating systems, data backups, and identity and access management. PRIVO IT, LLC implements the IT security policy which is set by the customer. PRIVO IT, LLC advises clients during quarterly business meetings of areas in which we believe their security policy is falling short, but ultimately determines which security controls are implemented. In addition, since PRIVO IT, LLC provides only limited support for applications, customers are responsible for securing the data stored in their applications. Furthermore, customers are responsible for securing and maintaining data, managing users, and determining who is authorized.

The System is comprised of the following components:

      i. infrastructure
      i. Software
      i. People
      i. Procedures
      i. Data

The following sections of this description define each of these five components comprising the System.

    *Infrastructure*

      The physical structures, IT, and other hardware (for example, facilities, computers, equipment, mobile devices, and telecommunications networks).

      The IT infrastructure listed below is used by Privo employees to provide our AWS and MSP consulting services.

      1. Company Laptops: Each employee has a company-issued laptop running Windows 10, MAC OS X, or Linux Fedora used for day-to-day performance of their job duties.

      AWS: The following components comprise the AWS infrastructure is used for providing services.

      NOTE: This AWS infrastructure is not directly used by clients, it is only used by employees for providing services to clients.

          2. Privo IT Website: The Privo website (http://privoit.com) is a promotional website only and contains
      no sensitive or login capability for clients.

          2. Management Server: Windows Server 2012 R2 server running various tools such as WatchGuardSystem Manager, PuTTY telnet client, and VPN clients to serve as a central connecting point for employees who need access to tools. Employees can log into the system via Remote Desktop Connection (after connecting to the VPN) and access these software tools, and connect to client on premise servers via site-to-site VPNs.

          2. DC01: This Active Directory (AD) server authenticates users when they log in to their laptops, and it automatically updates their Google Apps for Work password.

          2. DC02: This AD server is a backup of DC01.

          2. VPN01: This server runs OpenVPN and provides secure remote access to our AWS infrastructure.

      1. Mobile Devices: Each employee has a personal mobile smart phone with access to company email and Google drive files. Phones are either iOS or Android operating systems that are encrypted. The phone is used for two factor authentication.

      1. Corporate Office: We have physical office space at 400 West Cummings Park, Suite 3250 in Woburn MA, 01801 appropriate person, and recorded by asset. appropriate person, and recorded by asset.

    *Software*

      The application programs and IT system software that supports application programs (operating systems, middleware, and utilities).

      1. ConnectWise Professional Services Automation (PSA) Tool: ConnectWise is the main platform for
      tracking support tickets, projects, change management, inventory, and billing. This software is offered as a Software-as-a-Service (SaaS) product from ConnectWise and is hosted in AWS.
          2. Support tickets: All support tickets received via email, phone or web are tracked in this system.

          2. Project Management: All consulting projects are managed in the PSA to track time, tasks and progress.

          2. Change Management: Changes to customer’s infrastructure are recorded in the system, approved by the appropriate person, and recorded by asset.

          2. Inventory: All customer infrastructure components (Computers, Switches, Routers, Firewalls, etc.) are tracked in ConnectWise.

          2. Billing: ConnectWise keeps track of all customer contracts and it automatically updates invoice totals based on the number of assets managed.

      1. LabTech: LabTech is a remote monitoring and management (RMM) platform used to proactively manage and automate our customer’s managed devices. This service is offered as a Software-as-a-
      Service (SaaS) product from LabTech and is hosted in AWS. LabTech handles the following items:

          2. Proactive Monitoring: Each managed asset has a LabTech agent installed that checks into the LabTech server and reports back on its health. Once an issue has been detected by the agent, a support ticket is automatically opened in ConnectWise and the support team is alerted.

          2. Proactive Maintenance: The agent is responsible for running regular proactive maintenance tasks such as patch management, system optimizations, and executing self-healing scripts.

          2. Remote Control: LabTech gives us the ability to remotely connect to customer computers and servers to work on support requests. Each remote connection is logged in LabTech.

          2. Google Apps for Work: Google Apps for Work is our provider for email, calendaring, instant messaging, intranet, and cloud file storage.

          2. Slack: Communications platform among employees for sharing information about clients, AWS, security, sales, company announcements, and person-to-person direct chat messages.

          2. Virtru: End-to-end email encryption solution for Google Apps.

          2. LastPass: LastPass is an online password vault. All credentials for internal and customer accounts are encrypted locally and stored in LastPass.

          2. Duo 2 Factor Authentication: Duo is a solution that offers 2 factor authentication (2FA) for services that contain sensitive information. It is used for logging in to LastPass, AWS, The PRIVO IT, LLC Management server, Google Apps for Work, the VPN at AWS.

    *People*

    PRIVO IT, LLC’s organizational structure provides the overall framework for planning, directing, and controlling operations. Personnel and business functions are separated into departments according to job responsibilities. The structure provides defined responsibilities and lines of authority for reporting and communication. The assignment of roles and responsibilities within the various departments provide effective segregation of duties.


    *Procedures*

    PRIVO IT, LLC has documented policies and procedures to support the operations and controls over its AWS and MSP managed by PRIVO IT, LLC. Specific examples of the relevant policies and procedures include the following:

        1. Incident response
        1. Network security
        1. encryption
        1. Policy management and communication
        1. Physical security administration
        1. Network device maintenance
        1. Customer implementation

    *Data*

    PRIVO IT, LLC does not control customer-specific hardware, operating systems, databases, applications, or any other content loaded on the customer’s hardware. PRIVO IT, LLC does access customer’s systems when there is a request by the customers. All work that is done is logged and backed up for the customers to review.

### Security Considerations

Specific security considerations for product 1. Refer to policies, procedures here.

# References

## Narratives

List relevant narratives, probably including
Organizational Narrative
Security Narrative
System Narrative

## Policies

List relevant policies, probably including
Application Security Policy
Datacenter Policy
Log Management Policy
Password Policy
Security Incident Response Policy
Risk Assessment Policy

## Procedures

List relevant procedures, probably including access review, patching, alert monitoring, log review, pen testing
