# Emergency Information

|Document|Control|
|---|---|
| Compiled by | *Your name* |
| Version | 0.0.0 |
| Last review | *Today's date* |
| Next review | *Date one year from now* |

## Summary

This Emergency Information pack is intended to provide you with all the information you need in the event I become incapacitated or have an untimely (or timely) demise.

Most login details and credentials can be found in my password manager. Details of how to access the password manager are provided below. You may need to use a hardware security key.

## Technology

### Password Manager

*Name of password manager*

*URL if hosted somewhere*

*Tell people how they can access your password manager. You may need to tell them how to perform an emergency recovery with the password manager's recovery kit or legacy access process. You may need to tell them where to find a hardware security key.*

### Hardware Security Keys

*Give details about any hardware security keys you hold, where those keys are, and any passcodes associated with them (or where to find the passcodes)*

*If you have named your keys, give the names along with a brief description (e.g. if they are Yubikeys and what connector they have).*

### TOTP / Authenticators

*Give details of any TOTP or authenticators you use to provide one time passcodes. What are the names of the applications, what devices are they on, and how can they be accessed?*

### Domains

*Give details of where your domains are registered and which domains are most critical for keeping the lights on for things that need to stay on once you are gone.*

#### *Domain name*

|Service|Provider|
|---|---|
|Registrar|*Name and/or URL*|
|Nameserver Host|*Name and/or URL*|
|Email Hosting|*Name and/or URL*|
|Website Hosting|*Name and/or URL*|

*Why is this domain critical? What is it running and who for? For example it may be for your primary email address or it may be providing email hosting for members of your family. What will stop working if the domain or it's services go away?*

### Email

|||
|---|---|
|Hosting Provider|*Name and/or URL*|
|Admin URL|*URL*|
|Paid service?|*Yes/No and details of payment frequency and method of payment*|
|Admin account|*Username/Email address*|
|Email address|*Email address*|

*Document anything important about this email account / system - is it just for you or are others using it?*

### Websites

|||
|---|---|
|Website|*URL or other identifier*|
|Hosting Provider|*Name and/or URL*|
|Admin URL|*URL*|
|Paid service?|*Yes/No and details of payment frequency and method of payment*|
|Admin account|*Username/Email address*|


*What websites are critical and must not die with you? Is there anyone who can take over the running of the website? Perhaps it just needs a graceful shutdown. Where is the source code and how would someone find out how to build it?*

### Apple iCloud / Google Account / Microsoft Account

*Duplicate this section as needed*

|||
|---|---|
|Account|*Email address*|

*Most people are going to have either an iCloud or Android account of some description. Provide details of username or email address. If there is family sharing or subscriptions that may be affected by this account being closed, give details. You may have digital assets such as photographs, videos, or other data in your iCloud or Google account - give details, especially for family photographs that your relatives may want to keep*

*Apple provides a Digital Legacy Recovery Contact process that allows you to nominate a person who can access your stuff after your death. Consider nominating someone and then give details on who that person is and where to find the recovery key*

*Google has an Inactive Account Manager that acts as a dead-man's switch - consider enabling it and then give details of how this is set up. Note that this isn't available for Workspace accounts*

*If you are using Google Workspace then give details on how that is set up, with what domain(s), and who else has an account. Could someone take over the Workspace account and if so how?*

### Computers & Laptops

*Give details of what computers and laptops you have and which one you consider to be your main computer. If you have more than one main computer, what stuff is on each one (e.g. photos) that people may need to be able to access.*

*What username(s) do you use and how can someone login? Give directions that allow discovery of your password and any other authentication method that might be needed*

### Mobile Phone

*You may have data on your phone that only exists on your phone - is this data someone needs to be able to access (e.g. photos) and if so how? Does your phone have a password or passcode that they will need. What apps would be relevant?*

### Photographs

*Give details on how photos, especially family photos, can be accessed. Are they in a folder on your computer, or in an application such as Apple Photos. Maybe you kept everything online in Google Photos or Flickr.*

### Documentation

*You may keep documents (both electronic or scanned) in a directory or document management or notes system (such as Evernote, OneNote, Joplin, etc.) Examples of documentation might include contracts, bills, legal paperwork, tax paperwork, government paperwork, etc. Provide details of where this documentation is kept and the account details to access the documentation. *

### Journals and Writing

*You may be a writer or kept a journal or diary. Where can your family find this? Was it in an app or just a set of files somewhere?*

### Source Code

*App developer? Where is your source code? Could someone take on maintenance of a project - if so who?*

### Backup

*Give details of your data backup arrangements. Did you rsync to a hard drive or NAS? Perhaps you use an online service such as BackBlaze or CrashPlan? How can your family find your backups? Are there passwords, phrases, or other forms of encryption they will need to get through? Does anyone else's computer(s) get backed up on your account? Is there a subscription that needs to be paid?*

### Home Network

#### Servers

I run a number of servers on my home network, providing services to the house.

*Do you use an internal domain name? If so what?*

##### *Server name / FQDN*

*Repeat as needed*

|||
|---|---|
|Hostname|*hostname*|
|IP addresses|*List of statically assigned IP addresses*|
|vLAN|*List of vlans*|
|Location|*Where in your house is this machine and how can it be identified? If virtual what host is it on?*|
|OS|*What operating system and major version number?*|
|Make|*What make is it - a Raspberry Pi or perhaps a DEC?*|
|Services|*What is this server doing - what services is it providing to the network*|

*Give details of any special configuration that may need to be known. My assumption is that a reasonably competent technical person will need to figure things out, but at least give them a hand if you have configured things in a non-standard way.*

#### Broadband ISP

*How does broadband arrive at your house and get to the Router/Gateway? Do you have statically assigned IP addresses or ranges?*

#### Router / Internet Gateway

|||
|---|---|
|Hostname|*hostname*|
|IP addresses|*List of statically assigned IP addresses*|
|vLAN|*List of vlans*|
|Location|*Where in your house is this machine and how can it be identified? If virtual what host is it on?*|
|OS|*What operating system and major version number?*|
|Make|*What make is it - Cisco? Unifi? Juniper?*|
|Services|*What is this server doing - what services is it providing to the network*|
|Admin account|*Name of admin account*|
|Admin URL|*URL for web based administration*|

#### WiFi

|WiFi Network|Description|
|---|---|
|*Network name*|*What is this network used for? Does it default to a particular vLAN?*|

Passwords & keys for these networks can be found in my password manager.

*Give details of where the access points are located and how they tie into your overall home network. Is your gateway the controller or is there another controller somewhere with different credentials and admin URL?*

#### vLANs

*Give details of any vLANs you are running in your house. What are they called and what connects where and why?*

#### IPv6

*IPv4 is easy - but IPv6 may need more explanation depending on how you are allocated addresses and how you are using it internally in your home.*

#### DNS

*Running your own DNS servers at home? How are they set up, what servers are they running on?*

#### *Anything Else?*

*Are there any other services or infrastructure systems that need detailing. For example you may have a NAS or some other exotic kit. What needs to stay up if you are gone?*

### IoT & 'Smart' Devices

*Is there anything special about your IoT devices that someone would need to know? For example do they connect to an IoT vLAN? Are there any exceptions to this?*

#### Lights

*Do you have smart lights? What controls them and is there any admin account? Where is the controller located in the house?*

#### Other Smart Devices

*What other smart devices would someone need to know about, such as:*

- Smart Speakers
- Smoke Alarms
- Heating / HVAC
- Home automation

## Finances & Banking

*List all your financial details, including:*

- Financial planner
- Accountant
- Bank accounts
- Pensions
- Investments
- Crypto currency

*I focused on detailing organisation names, sort codes & account numbers, named contacts, where to find login information*

*I also detailed the purpose for each account and the kinds of transactions that it was used for, for example:*

- Where is my salary paid?
- Which accounts contain savings?
- Which accounts have standing orders or direct debits


## Insurance

### Home Insurance (Buildings & Contents)

|||
|---|---|
|Provider|*Name of provider*|
|Policy Number|*Policy or account number*|
|URL|*Website of provider*|
|Claims phone number|*Phone number to call in the event of a claim*|
|Broker|*Was this bought direct or do you use an insurance broker - if so who?*|

### Specialist Insurance

*For example bike, technology, photography, sole trader / small business*

|||
|---|---|
|Provider|*Name of provider*|
|Policy Number|*Policy or account number*|
|URL|*Website of provider*|
|Claims phone number|*Phone number to call in the event of a claim*|
|Broker|*Was this bought direct or do you use an insurance broker - if so who?*|

### Travel Insurance

|||
|---|---|
|Provider|*Name of provider*|
|Policy Number|*Policy or account number*|
|URL|*Website of provider*|
|Claims phone number|*Phone number to call in the event of a claim*|
|Broker|*Was this bought direct or do you use an insurance broker - if so who?*|

### Pet Insurance

|||
|---|---|
|Provider|*Name of provider*|
|Policy Number|*Policy or account number*|
|URL|*Website of provider*|
|Claims phone number|*Phone number to call in the event of a claim*|
|Broker|*Was this bought direct or do you use an insurance broker - if so who?*|

### Health Insurance

|||
|---|---|
|Provider|*Name of provider*|
|Policy Number|*Policy or account number*|
|URL|*Website of provider*|
|Claims phone number|*Phone number to call in the event of a claim*|
|Broker|*Was this bought direct or do you use an insurance broker - if so who?*|

## Employment

*Who are you employed by and how can they be contacted? Is there a named person who can be contacted or should any contact be directed to an HR team?*

*What is their phone number, address, and website?*

*Are you eligible for any relevant benefits such as death in service or private healthcare cover?*

## Mobile Phone

*Who is your mobile phone contract with, what is the account and phone number?*

*Is it a family account and if so who is impacted if the main account is closed?*

*Do you have any other sim cards in your phone such as a work provided sim? Is the phone itself provided by your employer?*

## Household & Utilities

### Electricity & Gas

|||
|---|---|
|Supplier|*Name of supplier*|
|Account Number|*Account number*|
|URL|*Website of the provider*|
|Payment|*What account is this paid from and how?*|

### Water

|||
|---|---|
|Supplier|*Name of supplier*|
|Account Number|*Account number*|
|URL|*Website of the provider*|
|Payment|*What account is this paid from and how?*|

### Broadband & Telephone

|||
|---|---|
|Supplier|*Name of supplier*|
|Account Number|*Account number*|
|URL|*Website of the provider*|
|Payment|*What account is this paid from and how?*|

### Council Tax

|||
|---|---|
|Supplier|*Name of supplier*|
|Account Number|*Account number*|
|URL|*Website of the provider*|
|Payment|*What account is this paid from and how?*|

### Anything else?

*Are there any other household services, especially on a regular subscription, that someone would need to know about?*

## Legal

*Do you have a lawyer? If so what company and contact details? Do they hold your will? If they don't hold your will, who does?*

## Pets

*Give details of any pets you have, where their vaccination records can be found and any identity chip or registration information.*

*How would someone distinguish between your pets if you have more than one?*

*What vet(s) are they registered with?*

