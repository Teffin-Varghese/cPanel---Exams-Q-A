# cPanel---Exams-Q-A
cPanel Professional Certification (CPP) &amp; cPanel &amp; WHM Administrator Certification (CWA) &amp; cPanel &amp; WHM System Administrator I Certification (CWSA-1) &amp; cPanel &amp; WHM Sales Professional (CPSP) (Q &amp; A)

#1, Nameserver address record setup in modern installations of cPanel & WHM, both within the Basic WHM Setup and Edit Reseller Nameservers and Privileges interfaces, provide support for certain DNS records associated which of the following types of hostnames?
#ANS: Hostnames that resolve to AAAA records.

#2, Within which of the following WHM interfaces would you enter the default nameservers for accounts that a reseller creates?
#ANS: WHM Home >> Resellers >> Edit Reseller Nameservers and Privileges

#3, Within which of the following WHM interfaces would you select the nameserver software that you wish to use?
#ANS: WHM Home >> Service Configuration >> Nameserver Selection

#4, In which of the following WHM interfaces would you enter the default nameservers for accounts that root creates?
#ANS: WHM Home >> Server Configuration >> Basic cPanel & WHM Setup.

#5, Within which of the following WHM interfaces would you be able to add SPF and DKIM records to an account?
#ANS: WHM Home >> Account Functions >> Modify Account

#6, Diego is a web designer who operates his own cPanel & WHM server. He wants to create a test subdomain for one of his clients and upload some web content to it so that he can share a "beta" (non-production) version of the site to his client.
Which of the following interfaces should he start with, in order to accomplish this?
#ANS: cPanel » Domains » Subdomains

#7, Which of the following options best describes the term recursive, in the context of DNS?
#ANS: A recursive nameserver can resolve non-local domains

#8, Within which of the following WHM interfaces can you globally enable DKIM and SPF for all accounts?
#ANS: DNS Functions >> Enable DKIM/SPF Globally

#9, Which of the following options indicates what the abbreviation TTL stands for, in the context of DNS?
#ANS: Time To Live; indicating how long a resource record should be cached.

#10, SPF and DKIM are resource records that help reduce which of the following?
#ANS: Spoofing and unauthorized senders.

#11, Which of the following options most accurately describes the interface or interfaces that you would utilize to create reverse DNS zones from within WHM?
#ANS: WHM Home » DNS Functions » Add a DNS Zone, and then WHM Home » DNS Functions » Edit DNS Zone.

#12, To add a PTR record that points the IP address 192.168.0.4 to mail.example.com, which zone would you modify?
#ANS: 0.168.192.in-addr.arpa

#13, Within which of the following WHM interfaces would you be able to add SPF and DKIM records to an account?
#ANS: WHM Home >> Account Functions >> Modify Account

#14, Which of the following statements best describes the term resolver?
#ANS: A nameserver that can resolve non-local domains.

#15, Which of the following options accurately indicate a task that can be performed from within the WHM interface?
#ANS: Change an MX record.

#16, Nameserver address record setup in modern installations of cPanel & WHM, both within the Basic WHM Setup and Edit Reseller Nameservers and Privileges interfaces, provide support for certain DNS records associated which of the following types of hostnames?
#ANS: Hostnames that resolve to AAAA records.

#17, Which of the following statements accurately describe a situation in which DNS zone templates would be useful, in a cPanel & WHM environment?
#ANS: Any time that similar customizations are needed across all hosted accounts.

#18, Of the following nameserver software options available in a cPanel & WHM environment, which is described as having the following major strengths?
Very high performance.
Low memory footprint.
#ANS: PowerDNS

#19, Yudith runs a small web-hosting company. She has added and removed several zones manually but has accidentally deleted a zone belonging to a cPanel account. Fortunately, this zone did not contain any custom records.
Given the situation, which of the following WHM interfaces should she utilize to re-create the zone?
#ANS: WHM » DNS Functions » Add a DNS Zone.

#20, Given the selection of nameserver software options available in a cPanel & WHM interface, which of the choices below have a major weakness that can be described as having a considerably extended initial zone loading time, if the server contains a very large quantity of zones?
#ANS: BIND/named

#21, If you have one DNSONLY server and three full cPanel & WHM servers, which of the following is recommended as the optimal cluster configuration, given this scenario?
#ANS: The cPanel & WHM servers should be set to push to the DNS Only server, which should not send updates back to the cPanel & WHM Servers.

#22, Which of the following best describes one of the primary, intended purposes of a DNSOnly server?
#ANS: Providing a means of establishing DNS redundancy in a cluster configuration.

#23, Which of the following types of DNS cluster synchronization found in WHM can be best described as the copying of one updated zone file to the current server, based on the value you provide as the domain you wish to synchronize?
#ANS: Synchronize one zone to this server only.

#24, cPanel offers a DNSOnly installation specifically for the purpose of using with a standard cPanel & WHM environment in a DNS cluster configuration. Which of the following is the standard license cost associated with DNSOnly?
#ANS: Free

#25, After performing an installation of cPanel & WHM on a fresh environment, what is the initial, default state of DNS clustering?
#ANS: DNS clustering is initially disabled, and must be manually enabled.

#26, Which of the following types of DNS cluster synchronization found in the WHM interface can be accurately described as the copying of all updated versions of local zone files from other servers in the cluster to this server?
#ANS: Synchronize all zones to this server only.

#27, By default, cPanel creates SPF records in which of the following modes?
#ANS: Testing mode (non-production)

#28, Given the following options, which indicates the ideal source from which you should obtain your server's resolver IP addresses?
#ANS: Your hosting provider or data center.

#29, Which of the following most accurately describes what happens when a domain with two NS records in its zone is queried?
#ANS: Both records are returned.

#30, When you use the supported 1:1 NAT setup in WHM, the List Accounts interface in WHM will display which of the following values in each accounts' listed IP address column?
#ANS: The public IP address.

#31, Within which of the following WHM interfaces would you perform a graceful restart of the nameserver software?
#ANS: WHM Home >> Restart Services >> DNS Server

#32, Which of the following options best describes the behavior that occurs when a zone contains no MX records?
#ANS: The A record is used to determine where mail should be sent.

#33, Which of the following query returns the IP addresses of the nameservers for the IP address 10.9.8.7?
#ANS: dig -x 8.9.10.in-addr.arpa

#34, Which of the following statements most accurately describes the term clustering, in the context of a server hosting environment?
#ANS: Two or more servers that all serve the same purpose configured in a distributed, connected environment

#35, Which of the following types of tables can you repair using the Repair a MySQL Database interface, found in WHM?
#ANS: MyISAM

#36, Which of the following describes a term that indicates a trait of the object described by the table, or can be otherwise referenced as a table column?
#ANS: Field

#37, Which of the following terms can be described as the way that permissions are handled inside a MySQL or MariaDB database?
#ANS: Grants

#38, Which of the following actions can you perform directly from within the WHM interface, without using phpMyAdmin?
#ANS: Change a database user's password.

#39, Given the following options, which accurately describe a feature specific to the MyISAM storage engine?
#ANS: MyISAM has repair capabilities that allow you to perform the REPAIR query, either directly or from the WHM interface, on tables that may have corrupted data or indexes.

#40, Which of the following MySQL storage engines is the native default (native to MySQL - not necessarily in cPanel & WHM) engine used by MySQL versions 5.5.5 and above?
#ANS: InnoDB

#41, Which of the following MySQL/MariaDB-related terms can be accurately described as the language used to add, remove, and view data in a database?
#ANS: SQL

#42, Which of the following best describes the role of the MySQL root password in a cPanel & WHM environment?
#ANS: A password that is primarily handled via automated means by cPanel & WHM back-end services, and can be reset as needed.

#43, Which of the following columns, found in the WHM Home >> SQL Services >> Show MySQL Processes interface, indicate the actual query being executed by the indicated process?
#ANS: info

#44, The WHM Home >> SQL Services >> Manage Database Users interface in WHM can be used for which of the following purposes?
#ANS: Rename existing database users.

#45, Ananya has a website that writes data into a MySQL database. She was mail-bombed, and as a result, has gone over the quota that was set for her account by the WHM server administrator. Which of the following best describes what happens to her website now?
#ANS: It continues operating normally, and no production impact is seen.

#46, Which of the following details about the remote server would you need to know, if you wanted to set up a new remote MySQL profile in WHM?
#ANS: Remote SSH port

#47, In modern versions of cPanel & WHM, what benefits can database prefixing, enabled from the SQL tab of the Tweak Settings interface in WHM, provide?
#ANS: Primarily cosmetic; helps server administrators identify database ownership, as well as providing auto-grouping in the phpMyAdmin interface.

#48, MySQL Profiles can be used to set up what kind of relationship between servers?
#ANS: 1-to-1 (1:1) only

#49, Given the following options, which of these indicate the correct amount of characters that a MySQL 4.1 password hash is composed of, before being updated to the current standard of 41 character-hashes?
#ANS: 16 characters.

#50, Which of the following options describes the best way to import a SQL dump into a PostgreSQL databases via the WHM interface?
#ANS: There are no features in WHM that provide this capability; it must be performed from the command-line.

#51, The WHM Home >> SQL Services >> Additional Access Hosts interface creates server-level grants that are similar to the grants that can be created in which of the following cPanel account-level Interfaces?
#ANS: cPanel Home >> Databases >> Remote MySQL

#52, Which of the following options describes an actual benefit of utilizing remote MySQL capabilities using the MySQL Profiles feature in WHM?
#ANS: Remote MySQL servers can reduce load on the WHM Server.

#53, Which of the following WHM interfaces would you use to configure a cPanel & WHM server to utilize a remote MySQL® server environment to handle its database operations?
#ANS: Manage MySQL® Profiles

#54, Given the options below, which of these accurately indicate a point during WHM user interactions which triggers the system to create grants for all pre-existing cPanel accounts, based on the configurations set within the Additional MySQL Access Hosts interface?
#ANS: When the user clicks the link at the bottom of the Additional MySQL Access Hosts interface labeled "click here".

#55, When using a cPanel & WHM environment, remote MySQL capabilities should be set up via the MySQL Profiles interface in WHM at which of the following stages of a server's operations?
#ANS: After installation, but before beginning to create production accounts on the server.

#56, As of cPanel & WHM 60, what is the minimum version of MySQL that can be running on a remote server, in order for it to be used in a Remote MySQL Profile?
#ANS: 5.5

#57, Which of the following is one of the most common causes of MySQL upgrade failures?
#ANS: The my.cnf file contains a number of non-default customizations that have not been verified prior to upgrading.
#ANS: Aborting the upgrade, intentionally or otherwise, part-way through the procedure.

#58, In a cPanel & WHM environment, which of the following MySQL storage engines is set as the default?
#ANS: MyISAM

#59, Which of the following database-related term can be defined as the marking of a table or row so that only one process can access it a time?
#ANS: Locking.

#60, Which of the following definitions best describes InnoDB's data dictionary component?
#ANS: A part of the InnoDB storage engine that uses metadata to map structural information to the file it’s stored in.

#61, In a cPanel & WHM environment running EasyApache 4, which of the following RPMs would provide PHP 5.6 to the account?
#ANS: ea-php56

#62, In modern installations of cPanel & WHM, when selecting DSO from the EasyApache 4 interface without mod_ruid2 or mpm_itk, what recommendation will be displayed to you automatically, directly from within the EasyApache 4 interface?
#ANS: PHP DSO runs as the nobody user by default. In a shared hosting environment, this is a security issue.

#63, Which of the following options accurately describes an action that can be performed from within WHM's EasyApache 4 interface?
#ANS: Install new PHP extensions for use in your active Apache/PHP environment.

#64, In addition to increasing the speed of the build process, which of the following options describes another reason that EasyApache 4 provides an improvement over EasyApache 3?
#ANS: Reduced chances of critical Apache failures.

#65, Which of the following options best describes one of the most notable behaviors that separate the DSO handler from other PHP handlers available in a cPanel & WHM environment?
#ANS: DSO does not create new "php" processes to handle requests, but instead works internally with Apache, spawning from the parent httpd process.

#66, Which of the following options accurately indicates the file syntax that can be seen within downloaded EasyApache 4 profiles?
#ANS: JSON

#67, In modern installations of cPanel & WHM, how is the PHP version determined for newly created accounts, when System PHP-FPM status is set to ON?
#ANS: It is set to the same value as the system default.

#68, Which of the following Apache modules are core to Apache and can be disabled, but cannot be removed using the EasyApache 4 interface?
#ANS: mod_userdir

#69, Of the following options, which of these handlers operate in a non-persistent state, requiring the creation of new PHP processes each time something is executed?
#ANS: suPHP

#70, Which of the following options best describes the procedure needed to enable the BlueHost SymLink Protection Patch?
#ANS: Toggle the corresponding option found in WHM's Apache Configuration's Global Configuration interface.

#71, Which of the following PHP handlers can only be used on one PHP version at a time?
#ANS: DSO

#72, Which of the following accurately indicates the user that processes created for the DSO handler are owned by?
#ANS: nobody user

#73, You're operating in a PHP 5.6 environment and using DSO as your PHP handler. You've created a .user.ini file in your website's public_html folder, but are not seeing your changes reflected.
Of the following choices, which of these most accurately describes the issue that is occurring here?
#ANS: An .htaccess file stored in public_html should be used instead, containing the appropriate syntax for declaring PHP values.

#74, Which of the following options describes the appropriate method needed to enable PHP-FPM from within the WHM interface?
#ANS: PHP-FPM is enabled via WHM's MultiPHP Manager interface.

#75, Which of the following options best describes the method you would use to install the PHP-FPM software, within a cPanel & WHM environment?
#ANS: PHP-FPM appears under the PHP Extensions stage of the EasyApache 4 profile customization walkthrough.

#76, Which of the following options describes an action that can be performed from within WHM's MultiPHP Manager interface?
#ANS: You can turn on PHP-FPM, per-virtual host, from this interface.

#77, Which of the following statements accurately describes how processes are handled during PHP requests when DSO is in use as the PHP handler?
#ANS: PHP handling operates internally by Apache's own processes.

#78, Given the following options, select the components or component combinations that would provide standard per-user process ownership for handling PHP content.
#ANS: suPHP (mod_suphp) OR Ruid2 (mod_ruid2) OR PHP-FPM

#79, If a user wants to utilize the system default version of PHP, which of the following selections would they enable for their account?
#ANS: inherit

#80, When operating in a cPanel & WHM environment, which of the following files are used by the system to define the PHP configuration?
#ANS: /etc/apache2/conf.d/php.conf

#81, When operating in a cPanel & WHM environment running EasyApache 4, within which of the following WHM interfaces can you adjust the server's default PHP version?
#ANS: This can be adjusted from within WHM's MultiPHP Manager interface.

#82, Which of the following types of packages does EasyApache 4 rely on to install modules and extensions, when provisioning an EasyApache 4 profile?
#ANS: RPM packages.

#83, In modern installations of cPanel & WHM, EasyApache 4 will allow you to install which of the following versions of Apache?
#ANS: Apache 2.4

#84, Which of the following options accurately describe an action that can be performed from within WHM's EasyApache 4 interface?
#ANS: Change the MPM that is used in your Apache installation.

#85, In a cPanel & WHM environment operating with EasyApache 4, an EasyApache profile is defined as which of the following?
#ANS: A collection of packages that can be provisioned.

#86, Which of the following EasyApache 4 profile actions can you perform from WHM's EasyApache 4 interface, in modern installations of cPanel & WHM?
#ANS: Upload a profile file from your file system or via a URL.

#87, Which of the following options is NOT a real Multi-Processing Module (MPM) available for installation within WHM's EasyApache 4 interface?
#ANS: Postfork

#90, In computing terms, a service is:
#ANS: software that runs in the background and provides specific functionality

#91, When you cannot decrypt using the same key you encrypted with, but instead with its unique counterpart, it's referred to as what type of encryption?
#ANS: Asymmetric

#92, When using an Organization Validated Certificate, which of the following statements accurately describes how the browser will indicate this in its address bar?
#ANS: Only a padlock indicating a valid SSL certificate.

#93, An SSL certificate for *.cpanel.com can be used on which of the following domains: (Select all that apply.)
#ANS: store.cpanel.com & www.cpanel.com

#94, Which level of validation gets you a "green bar" in the browser?
#ANS: Extended Validation

#95, True/False: Purchasing anything other than a single domain or a domain validated certificate is a scam.
#ANS: False

#96, Which of the following indicates the maximum number of APNs that should be used per-server, in a cPanel & WHM environment?
#ANS: 1

#97, When SNI is in use, which items are used to determine which virtual host to return? (Select all that apply)
#ANS: requested hostname & the IP address the client connected to

#98, The first time you install a newly signed certificate purchased from a third party, you should install it by
#ANS: copy/pasting the certificate from the vendor to the certificate box on WHM Home » SSL/TLS » Install an SSL Certificate on a Domain.

#99, True/False: You should always use a shared secret when creating a certificate, key, and CSR.
#ANS: False

#100, True/False: A larger key is more secure, but takes more resources to process each new SSL request.
#ANS: True

#101, You can add or remove SNI from the mail services on which page?
#ANS: WHM Home » SSL/TLS » Manage SSL Hosts

#102, This image, shown below, from a browser's address bar represents which of the following types of certificate validation?
#ANS: Extended Validation

#103, Which of the following services are NOT usable with WHM's Service SNI feature?
#ANS: mysql

#104, In a cPanel & WHM environment, which of the following indicates the frequency that AutoSSL polls for pending certificates?
#ANS: Every 5 minutes the first day, every hour the second day, and once a day after that.

#105, Of the following options, which accurately indicates the maximum length of the commonName field, found in SSL certificates?
#ANS: 64 bytes

#106, Which of the following causes an insecure content on a secure page warning?
#ANS: visiting a site with some images loaded with http instead of https

#107, Why might a site look different when viewed with HTTPS rather than with HTTP?
#ANS: the site does not have its own SSL certificate, so Apache displays a different site on that IP address that does have a certificate.

#108, Which of the following causes a hostname mismatch warning? (Select all that apply)
#ANS: visiting www.domain.com for a site whose certificate is for domain.com
#visiting a site on a shared IP address that does not have SSL enabled using https://

#109, The most common cause of the self-signed warning is
#ANS: a missing or incomplete CA bundle

#110, True/False: By default, AutoSSL will not change or impact any certificates that were manually installed outside of AutoSSL.
#ANS: True

#111, True/False: Setting a user to "Enable AutoSSL" does not override feature list settings applied for that user account.
#ANS: False

#112, When using WHM links that direct you to the cPanel Store for purchases (such as for SSL certificates or KernelCare), issues with the store or cart system that are handled server-side are often logged to which of the following log files?
#ANS: /usr/local/cpanel/logs/error_log

#113, When a certificate issued by AutoSSL is going to imminently expire, which of the following does AutoSSL do?
#ANS: Automatically replaces them with an updated certificate, when AutoSSL runs its certificate checks.

#114, With AutoSSL enabled, what type of certificate are your websites automatically secured with?
#ANS: Domain-Validated (DV)

#115, Which of the following indicates the maximum number of APNs that should be used per-server, in a cPanel & WHM environment?
#ANS:1

#116, Within which of the following cPanel & WHM user interfaces can you manage Domain TLS?
#ANS: None of these.

#117, Which of the following does a self-signed certificate put you at risk of?
#ANS: Man-in-the-middle attack

#118, Which of the following does a web client check when receiving a certificate from a webserver? (Select all that apply)
#ANS: the expiration date is after the current date
#the connected hostname is covered by the certificate
#the certificate was issued by an authority that the browser trusts

#119, The Tweak Setting "Always Redirect to SSL" redirects which method of logging in?
#ANS: /cpanel, /webmail, /whm URLs

#120, Which of the following can cause an expired certificate warning?
#ANS: the wrong date on the client computer

#121, Which services are SSL-capable? (Select all that apply)
#ANS: FTP & webmail & WebDisk

#122, How do you remove an SSL certificate from a domain
#ANS: click on the trash can icon in the Actions column next to the desired domain where they are listed on the page WHM Home » SSL/TLS » Install an SSL Certificate

#123, Less severe issues with an SSL certificate are found by [clicking on the broken lock image in the address bar] , while more serious errors prevent you from [visiting the page] .

#124, Encryption is
#ANS: Disguising data using mathematical functions

#125, How often does AutoSSL perform a certificate check, if the age of the certificate request is less than one day?
#ANS: Once every five minutes

#126, In computing terms, the "root" of something is:
#ANS: the start of something

#127, Which of the following are real types of certificates? (Select all that apply)
#ANS: DV & EV

#128, Where can you see the next scheduled AutoSSL check time?
#ANS: In the Manage AutoSSL home interface within WHM

#129, What is a regular expression?
#ANS:  A string of text used to describe a pattern match.

#130, True/False: The Logging phase of an HTTP transaction still allows ModSecurity to perform connection filtering/blocking changes instructed by rules.
#ANS: False.

#131, What file format is required for the Favicon?
#ANS: ICO

#132, When the Help Link field is defined, roughly where in the cPanel account interface does a "Help" link appear?
#ANS: In the footer.

#133, What is the interface path where you can find the Customization section within WHM?
#ANS: Home >> cPanel >> Customization

#134, TRUE/FALSE: When you define value in the Company Name field of the Customization interface, it will display the value as header text in the top bar of the cPanel account interface.
#ANS: True

#135, What needs to be appended to a URL in order to retrieve the Public Contact information JSON data?
#ANS: cgi-sys/contact_details.cgi

#136, TRUE/FALSE: When a Company Logo image is provided, it will be displayed along with the text defined in the Company Name field, within the top bar of the cPanel account interface.
#ANS: False.

#137, TRUE/FALSE: Only the Company Name value defined in the Public Contact tab of the Customization interface will be accessible to the public - not the Company Name value defined in the Customize Branding tab.
#ANS: True.

#138, Do you remember what file format is used for custom styles, when uploading or downloading them from the Customize Style tab of the Customization interface?
#ANS: Gunzip.tar

#139, In which WHM interface can you configure the forwarders for the root, cpanel, and nobody mail accounts?
#ANS: WHM Home » Server Contacts » Edit System Mail Preferences

#140, If there is a long delay indicated when an email is being sent, the Mailer Daemon will send a warning message to which of the following destinations?
#ANS: The email's sender.

#141, Which of the following options accurately describes the behavior of an open relay server?
#ANS: An open relay server does not require you to authenticate.

#142, José sends an email message to Maria. If the system cannot deliver the message, José will get a notification from which of the following sources?
#ANS: The mailer daemon.

#143, Which of the following options best indicate a legitimate reason that would describe why you would want to configure the forwarder address fields within the WHM Home » Server Contacts » Edit System Mail Preferences interface?
#ANS: To prevent emails destined for "root" from getting frozen within the mail queue.

#144, Which of the following actions can you perform in the WHM Home » Email » Mail Queue Manager interface?
#ANS: Delete a particular message permanently so that is not delivered.

#145, Within which of the following WHM interfaces can you enable additional ports for Exim to listen for SMTP connections on?
#ANS: WHM Home » Service Configuration » Service Manager

#146, Which of the following methods best indicate the recommended approach for backing up, restoring or resetting the system's Exim configuration?
#ANS: Use the corresponding functions found within the Exim Configuration Manager interface, in WHM.

#147, Which of the following options found in the Exim Configuration Manager - Basic Editor interface in WHM can best be described as the option that allows you to edit the list of IP addresses that the system excludes ONLY from SMTP sender verification checks?
#ANS: Sender verification bypass IP addresses

#148, Which of the following options found in the Exim Configuration Manager - Basic Editor interface in WHM can best be described as enabling the contacting of the sender's mail server to see if the sender exists?
#ANS: Sender Verification Callouts

#149, Which of the following options found in the Exim Configuration Manager - Basic Editor interface in WHM can best be described as enabling the checking of DNS resolution to see if the sender's domain exists?
#ANS: Sender Verification

#150, Which of the following tools may help you to resolve issues indicated by the time moved backwards warning?
#ANS: The "ntp" tool.

#151, Given the following options, which describe an actual reason that the system may place a message into the Exim queue?
#ANS: The load average on the server is above the delivery threshold.

#152, Which of the following actions can you perform in the WHM Home » Email » Mail Queue Manager interface?
#ANS: Delete a particular message permanently so that is not delivered.

#153, Given the following options, which describe an actual reason that the system may place a message into the Exim queue?
#ANS: There are DNS issues preventing Exim from finding the remote mail server.

#154, If there is a long delay indicated when an email is being sent, the Mailer Daemon will send a warning message to which of the following destinations?
#ANS: The email's sender.

#155, Which of the following options best describes the term email reputation?
#ANS: It is a calculation of the likelihood of a message being spam based on other messages sent from the same server.

#156, Which of the following options found in the Exim Configuration Manager - Basic Editor interface in WHM can best be described as enabling the checking of DNS resolution to see if the sender's domain exists?
#ANS: Sender Verification

#157, Which of the following options best indicate the typical delivery failure rate that a spamming email account will report, if examining from the Mail Delivery Reports interface found in WHM?
#ANS: The account will have a high failure rate.

#158, If the mail server defers a message, what did it actually do to the message?
#ANS: Delayed it.

#159, You can use the Exim Configuration Manager - Basic Editor to configure Exim to deliver mail without scanning messages based on which of the following criteria?
#ANS: When the message is over a certain size.

#160, If you suspect that mail has not been delivered because the user is over their quota, in which of the following WHM interfaces might you look to confirm why the message was not delivered?
#ANS: WHM Home » Email » Mail Delivery Reports

#161, cPanel & WHM allows you to choose whether mail should be held in the queue or returned to sender when the recipient's mailbox meets which of the following criteria?
#ANS: Exceeds its assigned quota.

#162, When mail is delivered to "/dev/null”, which of the following statements accurately indicate what happens to the message?
#ANS: The message has been permanently deleted.

#163, All mail from a specific user is neither delivered to the inbox nor bounced. When you check the WHM Home » Email » Mail Delivery Reports interface, you see a funnel-shaped icon next to the message.
Which of the following options best describes what this probably indicates?
#ANS: The message was likely caught in a user-level filter and deleted.

#164, Given the following options, which accurately describes the behavior of the Mail Troubleshooter interface, found in WHM?
#ANS: It does not send an actual test message, but simulates sending one.

#165, All mail from a specific user is neither delivered to the inbox nor bounced.
When you check the WHM Home » Email » Mail Delivery Reports interface, you see a green checkmark icon next to the message. Which of the following options best describes what this indicates?
#ANS: That the message was delivered successfully to a folder other than the inbox.

#166, If there is a long delay indicated when an email is being sent, the Mailer Daemon will send a warning message to which of the following destinations?
#ANS: The email's sender

#167, Which of the following options describes one of the commonly known characteristics, though are not always indicative, of an average spam email message?
#ANS: The message contains an attachment.

#168, Which of the following Mail interfaces in WHM can provide you with a historical snapshot of the mail queue?
#ANS: Mail Queue History

#169, Which of the following options best describes what is indicated by the act of a mail server "relaying" its mail?
#ANS: It is sending mail on behalf of unauthenticated users.

#170, Which of the following describes what is indicated by the use of the virtual_user router during a message's delivery, as seen in the exim logs?
#ANS: The message was delivered to an email account created in the cPanel interface.

#171, Which of the following Exim log entries would indicate that mail was deleted due to a filter?
#ANS: 1YO6bD-000871-1j => /dev/null <test@cptest.test> R=virtual_user_filter T=**bypassed**

#172, Given two cPanel servers exchanging email, which of the following would appear in both messages' headers, but would not appear in the Exim logs on either the sending or the receiving server?
#ANS: Exim ID

#173, In an Exim log entry, the cwd value indicates which of the following?
#ANS: The directory that triggered the delivery of the message.

#174, Which of the following Actions in a cPanel email filter will result in an incoming message being rejected without sending any notifications?
#ANS: Discard Message

#175, A particular type of email filter is stored in the /etc/vfilters/ directory. Which of the following types of filters are these?
#ANS: Account-level email filters.

#176, Of the following mailbox formats, which of these are supported for use in cPanel & WHM environments?
#ANS: mdbox & Maildir

#177, When using Maildir, the "cur" folder contains which of the following items?
#ANS: Mail that HAS been read.

#178, Which of the following best describes the role of the exim -bt command?
#ANS: Prints the path that the message will take when Exim attempts delivery to a specified address.

#179, Which of the following best describes the role of the exim -bpc command?
#ANS: Prints the number of messages in the mail queue.

#180, What is the role of the -f flag when used with the exiqgrep utility?
#ANS: Select messages by sender address.

#181, What is the role of the -y flag when used with the exiqgrep utility?
#ANS: Messages newer than the number of seconds given.

#182, After a domain is updated at the registrar, where does the registrar then send that domain's record data?
#ANS: To the TLD nameserver.

#183, What does the acronym TLD represent, as in for a "TLD nameserver"?
#ANS: Top-level Domain

#184, Which of the following nameserver applications does not load all of its DNS zones upon startup?
#ANS: MyDNS

#185, Which of the following situations can cause very extended start-up and load times, when running the BIND/named nameserver software?
#ANS: Using a very large quantity of zone files.

#186, When a remote mail exchanger handles a domain's mail, which of the following files must include the domain?
#ANS: /etc/remotedomains

#187, In a cPanel & WHM server, which of the following would allow you to select another DNS server application from the command line?
#ANS: setupnameserver

#188, Which of the following commands can you use to set up SPF from the command-line, in a cPanel & WHM environment?
#ANS: /usr/local/cpanel/bin/spf_installer

#189, Which of the following is the default path for the BIND/named configuration file?
#ANS: /etc/named.conf

#190, On a cPanel & WHM environment, the system stores the private/public keys for DKIM in which of the following paths?
#ANS: /var/cpanel/domain_keys

#192, Which of the following situations can cause very extended start-up and load times, when running the BIND/named nameserver software?
#ANS: Using a very large quantity of zone files.

#193, Which of the following command-line tools can be used to list running processes in a Linux environment?
#ANS: PS

#194, If named fails to start due to a configuration error, which of the following commands would be the most helpful for you to run?
#ANS: named-checkconf

#195, In a cPanel & WHM environment, DNS zone files can be found in which of the following folders?
#ANS: /var/named

#196, By default in a cPanel & WHM environment, the system logs cluster-related messages into which of the following log files?
#ANS: /usr/local/cpanel/logs/dnsadmin_log

#197, Which section of the named.conf file controls BIND/named's listening port?
#ANS: options

#198, When operating within a cPanel & WHM server, which of the following indicates the best method to restart the DNS server from the command line?
#ANS: /scripts/restartsrv_named

#199, Which of the following DNS-related command-line utilities would provide you with similar results to those given by the dig utility, and is used for essentially the same purposes?
#ANS: nslookup

#200, In which of the following configuration files would you enable debug logging for BIND/named?
#ANS: /etc/named.conf

#201, What does the acronym ACL represent, in the context of a BIND/named configuration (among other contexts)?
#ANS:  Access Control List

#202, To ensure that the internet sees the changes that you make DNS zone file manually, which of the following components of a DNS zone should you update?
#ANS: The serial number.

#203, In a cPanel & WHM environment, you will find zone files stored in /var/named when using which of the following namesever software?
#ANS: All of these. (MyDNS,BIND/named,PowerDNS)

#204, After you make a number of zone file changes in different zones, if you want to ensure that caching nameservers know to load the new information from your server, which of the following, single procedures can you perform to accomplish this?
#ANS: Batch Zone Update

#205, To retrieve the IPv6 record of a domain, you would query for which of the following records in a domain?
#ANS: AAAA

#206, After you update a zone's serial number (or any other record), which of the following commands can you execute to ensure that your local nameserver has been updated to use the new zone data?
#ANS: rndc reload

#207, Which of the following is one method that you can use, within the WHM interface, to repair a malformed DNS zone using a zone template?
#ANS: Reset a DNS Zone

#208, When you see a "rndc reload: connection refused" error, which of the following commands should you run first?
#ANS: /scripts/fixrndc

#209, A default cPanel & WHM environment configures a custom logging channel, default_log, to log to which of the following paths?
#ANS: /var/log/named/named.log

#210, By default, which of these logging categories are routed into the default_log channel, in a BIND/named DNS server configuration?
#ANS: general

#211, In a BIND/named configuration file, which of these logging categories encompasses all categories that have not already been explicitly configured to use another channel?
#ANS: default

#212, What does the Error logging severity imply, when referring to BIND/named logs?
#ANS: A problem has been encountered during BIND/named operations that may allow further operations to continue.

#213, In a cPanel & WHM environment, in order to define a range or subnet of IP addresses for the system to re-use in the named.conf file, you should create which of the following kinds of configuration objects?
#ANS: ACLs

#214, To force the local system to resolve a domain to a specific IP address, which of the following files would you modify to accomplish this?
#ANS: /etc/hosts

#215, Which of the following utilities can be used to administer a BIND/named server remotely?
#ANS: rndc

#216, By default, which of the following sections appear first in the named.conf file?
#ANS: key

#217, What portion of a DNS zone is used to inform other nameservers that a change to the zone has occurred?
#ANS: serial

#218, On a cPanel & WHM environment, the system stores DNS zone template files within which of the following paths?
#ANS: /var/cpanel/zonetemplates

#219, Which of the following file names follows the naming convention for a BIND/named zone file?
#ANS: domain.net.db

#220, At which of the following stages of BIND/named DNS server operations might you encounter a zone or configuration syntax error?
#ANS: During startup.

#221, In a cPanel & WHM environment, DNS zone templates can be used to ensure which of the following?
#ANS: To standardize a set of zone records and structure that will be used for a large number of DNS zones.

#222, Which of the following utilities included with BIND/named can be used to troubleshoot malformed zone files?
#ANS: named-checkzone

#223, Which of the following is closest described as the structural metadata used to track objects like tables, indexes, and columns when using the InnoDB storage engine?
#ANS: Data dictionary

#224, Which of the following statements about InnoDB tablespaces are true?
#ANS: They can be stored individually within a database folder, or lumped together into the ibdata1 file.

#225, The following text is an example of which type of syntax, also found in some mapping-related files stored by cPanel in the file system?

MYSQL:
  animals:
    animals:
      - GRANT USAGE ON *.* TO 'animals'@'localhost' IDENTIFIED BY PASSWORD '*75FE48658430441870C524D7ECB8F71EADFAEFD1'
      - GRANT ALL PRIVILEGES ON `birds`.* TO 'animals'@'localhost'
      - GRANT ALL PRIVILEGES ON `animals\_fish`.* TO 'animals'@'localhost'
PGSQL: {}

#ANS: YAML

#226, Which of the following file extensions are associated specifically with MyISAM tables?
#ANS: .MYD

#227, Which of the following statements is not a legitimate SQL statement?
#ANS: copy

#228, Which of the following SQL statements can be used to provide descriptive information about databases, tables, columns, variables, or status information about the server?
#ANS: Show

#229, Which of the following SQL queries would be the most effective in identifying MySQL users that still have pre-4.1 passwords in use?
#ANS: SELECT DISTINCT user FROM user WHERE length(password) < 41;

#230, Which of the following statements are true about SQL usage in a MySQL server?
#ANS: It is NOT case sensitive.

#231, In a cPanel & WHM environment, which of the following describes the purpose of the files that exist within the /var/cpanel/databases directory?
#ANS: To store mapping information to help store data regarding association between cPanel accounts and databases.

#232, Of the following options, which would be the optimal way to resolve the issue that causes email notifications containing content similar that shown below?
##dbindex cache file is out of date
#ANS: Restore the file from an available backup.

#233, When looking at the following excerpt from the beginning of a SHOW GRANTS result, what do the wildcard asterisks represent in the *.* shown below?
##GRANT USAGE ON *.*
#ANS: [database].[table]

#234, Which of the following WHM interfaces updates the files in the /var/cpanel/databases directory?
#ANS: Database Map Tool

#235, How can you prevent cPanel & WHM from performing automated updates on the MySQL® or MariaDB server software?
#ANS: By using the update_local_rpm_version script.

#236, When should you make backups of your configuration files (or the my.cnf file in particular)?
#ANS: When changes are made to the configuration.

#237, If the MySQL processes are stopped using the kill -9 command, what can you expect to happen?
#ANS: The severed writes on the databases will increase risk of database corruption.

#238, Which of the following MySQL logs are not recommended to leave enabled on a production server?
#ANS: General query log: /var/lib/mysql/hostname.log

#239, Error messages in your database error logs that indicate invalid, missing or unexpected system tables can frequently be the result of which of the following issues?
#ANS: An incomplete (partial) upgrade.

#240, Which of the following files should you check if you receive an unknown variable error message during MySQL operation or service start-up?
#ANS: /etc/my.cnf

#241, Which of the following MySQL/MariaDB-related variables can be controlled via an option found within WHM's Tweak Setting interface?
#ANS: max_allowed_packet &  open_files_limit

#242, Which of the following is closest described as the structural metadata used to track objects like tables, indexes, and columns when using the InnoDB storage engine?
#ANS: Data dictionary

#243, If the backup directory is /backup, where would you find the compressed backup file of the full MySQL data directory?
#ANS: /backup/[date]/system/dirs/_var_lib_mysql.tar.gz

#244, You must stop the MySQL service in order to perform which of the following actions?
#ANS: Relocate or rename the data directory file in the MySQL data directory.

#245, Which of the following are utilities that you can use to try and repair a MySQL database while MySQL is running?
#ANS: The "mysqlcheck" command.

#246, Which of the following can be described as a calculated numerical value resulting from a pre-determined algorithm used to represent a set of data?
#ANS: Checksum

#247, Which of the following statements about ~/.my.cnf files can be considered to be true?
#ANS: .my.cnf files can be used by any user.

#248, Which of the following describes one of the important steps that should be taken after restoring a single database from a full cPanel backup, into a new database instance?
#ANS: Associate the database and the database user with the cPanel user using the Database Map Tool.

#249, Which of the following terms can be described as a special text string syntax used for describing a search pattern?
#ANS: Regular Expression

#250, When operating within a cPanel & WHM environment, which of these commands would display all available EasyApache 4 packages from within the server's command line?
#ANS: yum list "ea-*"

#251, In a cPanel & WHM environment, within which of the following parent directories would you find a subdirectory that includes EasyApache's templates and userdata information, stored by cPanel?
#ANS: /var/cpanel/

#252, Which of the following terms can be described as a special part of a process that shares resources with others in the same process, and can execute commands?
#ANS: Thread

#253, Which of the following items can be described as any of the three things listed below?
##A command line program for installing software.
##A file format used to package software.
##The individual packages created in that format.
#ANS: RPM

#254, Of the following, which of these options describe information that can be obtained by using the yum info command?
#ANS: The plugins currently being loaded by the yum application.

#255, Which of the following yum commands would remove, or uninstall, the mod_speling RPM?
#ANS: yum remove ea-apache24-mod_speling

#256, When administering a server running cPanel & WHM, which of the following commands contains the appropriate paths and arguments needed to install an EasyApache 4 profile from the command-line?
#ANS: /usr/local/bin/ea_install_profile --install /etc/cpanel/ea4/profiles/cpanel/default.json

#257, Which of the following options describes the best way for you to enable the experimental repository for EasyApache 4, when operating within a cPanel & WHM environment?
#ANS: Perform the following command from the command-line, as root or equivalent: yum install ea4-experimental

#258, Which of the following yum commands will install the EasyApache 4 mod_speling RPM?
#ANS: yum install ea-apache24-mod_speling

#259, How does the /usr/local/bin/php executable know which version of PHP it should be using?
#ANS: The .htaccess file, if it exists, is referenced in order to determine this.

#260, Which of the following components can be described as a specific SAPI that provides functionality in a module that behaves as if it had been compiled into Apache itself, handling appropriate requests without producing new, non-Apache processes?
#ANS: DSO

#261, In a cPanel & WHM environment, if you select PHP 5.6 as the default PHP version, then from which of the following paths will the php.ini file be loaded?
#ANS: /opt/cpanel/ea-php56/root/etc/php.ini

#262, If, from the command line of a server running cPanel & WHM, you run the rebuild_phpconf command with an appropriate action, then include the --errors option, which of the following will happen?
#ANS: It outputs any errors in the rebuild process to the screen (sends to STDERR and log file).

#263, How does the scl command know which version of PHP it should use?
#ANS: You provide the PHP version as a command-line argument.

#264, Which of the following options best describes the yellow-highlighted portion of the Apache access log entry shown below?
##127.0.0.1 - frank [10/Oct/2000:13:55:36 -0700] "GET /apache_pb.gif HTTP/1.0" 200 2326
#ANS: The HTTP status code & The IP address of the requestor.

#265, Referencing the Apache error log entry shown below, which of the following options best describes the yellow-highlighted portion of the log entry (take note of the specifically-highlighted word)?
##[Fri Sep 09 10:42:29.902022 2011] [core:error] [pid 35708:tid 4328636416] [client 72.15.99.187] File does not exist: /usr/local/apache2/htdocs/favicon.ico
#ANS: The name of the Apache module that triggered the error.

#266, If a file or directory in a path being served by Apache contains incorrect permissions or uses improper user/group ownership values, which of the following HTTP status codes might you see in the Apache logs if a client were to request one of the affected paths?
#ANS: 403

#267, Which of the following best describes the difference between a process and a thread?
#ANS: Processes can contain multiple threads, and the threads contained in the process share its resources.

#268, In a cPanel & WHM environment, which of the following paths contain each installed version's PHP configuration files (php.ini), used by MultiPHP? ("##" representing the PHP version, in the options below)
#ANS: /opt/cpanel/ea-php##

#269, In a cPanel & WHM environment, which of the following paths are used to store Apache's primary PHP configuration file ( php.conf) ?
#ANS: /etc/apache2/conf.d/

#270, Referencing the Apache error log entry shown below, which of the following options best describes the yellow-highlighted portion of the log entry?
##[Fri Sep 09 10:42:29.902022 2011] [core:error] [pid 35708:tid 4328636416] [client 72.15.99.187] File does not exist: /usr/local/apache2/htdocs/favicon.ico
#ANS: The inbound IP address of the node that requested the item that caused the error message.

#271, Which of the following options could be described as a repository for PHP extensions?
#ANS: pecl

#272, In a server running cPanel & WHM, how can you create a new EasyApache 4 profile from within the server's command-line?
#ANS: In the file system, make a copy of an existing profile's file, edit it with any desired changes, then save the new file.

#273, Which of the following terms can best be described as the destination where a process can write normal output to, usually being to the terminal, server console ("screen"), unless redirected?
#ANS: STDOUT

#274, SpamAssassin obtains its final probability score for a message through which of the following methods?
#ANS: It adds together the score results from each triggered rule.

#275, Which options must you pass to the sa-learn program if you want it to update the Bayesian database with information from a mailbox?
#ANS: --spam/--ham

#276, Which of the following terms is used, particularly in spam-training applications, to describe the opposite of spam, meaning legitimate, solicited messages that are not considered spam?
#ANS: Ham

#277, Given the following options, which of these indicate one of the paths within which you can find SpamAssassin rulesets stored?
#ANS: ~/.spamassassin/

#288, Which of the following applications can be described as a program used during service checks to ensure that spamd is operational?
#ANS: spamc

#290, Which of the following options best defines a poisoned bayesian database?
#ANS: It has been populated with an excessive amount of false positives.

#291, How many messages does SpamAssassin's Bayesian filter need to process before it can start scoring mail?
#ANS: 200 good samples, and 200 bad samples.

#292, If the Scan outgoing messages for spam and reject based on defined Apache SpamAssassin™ score setting (formerly known as Apache SpamAssassin reject spam score threshold), within the Exim Configuration Manager - Basic Editor interface in WHM, contains a value, at what point during an email transaction is the message actually scanned to enforce this threshold?
#ANS: During the SMTP transaction with the message's origin server.

#293, Assume the host environment is a default cPanel & WHM installation. Based on the log entry shown below, identify from the options available which log file that this entry would be found in:
##spamd: identified spam (108.6/5.0) for cars:501 in 1.4 seconds, 407 bytes
#ANS: The /var/log/maillog file.

#294, Assume the host environment is a default cPanel & WHM installation. Based on the log entry shown below, identify - from the options available - which log file that this entry would be found in:
##spam acl condition: error reading from spamd socket: Connection timed out
#ANS: /var/log/exim_paniclog
