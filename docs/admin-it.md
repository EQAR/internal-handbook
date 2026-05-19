# ICT Infrastructure

EQAR's information and communications technology (ICT) infrastructure consists of a suite of services facilitating the organisation's work. These are provided by virtual/cloud servers (VPS) and external service providers.

EQAR staff can find an internal portal with links to all relevant sites and services at: <https://appsrv.eqar.eu/>

## EQAR User

> **Relevant for:** staff, committee members, externals (e.g. project partners)

One single login/account is used for most EQAR-hosted services (e.g. NextCloud) and some external services. Your username is the first letter of your first name, followed by your lastname, all in small letters and without diacritics. For example, `jdoe` for John Doe.

You can manage your account and change your password at <https://accounts.eqar.eu/>.

### Reset Password

In order to activate your login, you will have to use the password reset function:

 1. Go to <https://accounts.eqar.eu/reset-password/>.

 1. Enter your username or the email address to which your account is linked.

 1. A link to reset your password will be sent by email. Use the link to set a new personal password.

If you forgot your password, use the same password reset function.

### Services

The EQAR user login is used for the following services:

- NextCloud <https://cloud.eqar.eu/>
- Slack <https://eqarworkspace.slack.com/>
- Zoom <https://eqar-eu.zoom.us/signin>
- WordPress admin <https://www.eqar.eu/edit/>
- Website analytics <https://analytics.eqar.eu/>
- Contact database <https://db.int.eqar.eu/>
- Limesurvey <https://survey.eqar.eu/admin/> (Authentication method: LDAP)
- Trello <https://trello.com/login>

The following acounts are _separate_, i.e. each have their own username/password:

- Email: your email account has a separate password, which can be changed through the [webmail interface](https://webmail.all-inkl.com/). The login name is your email address, `firstname.lastname@eqar.eu`
- DEQAR [backend](https://admin.deqar.eu/): your username for the DEQAR backend is separate.
- Laptop: since it is not always connected to the network, your login on the laptop is local and with a separate password. The username is your firstname, in small letters, e.g. `john` for John Doe.
- Personal accounts for [FCm Arrivon](https://www.arrivonbyfcm.be/prdtlc/home.do?country=BE&language=en&BV_UseBVCookie=no&company=eqarbe&siteKey=FCM%23BE) (travel booking).
- Shared accounts (one account used by all staff) are in use for [Formsite](https://fs1.formsite.com/form_app/FormSite?FormId=LoadLogin&Auto) and some other services.

## Video Conferences

> **Relevant for:** staff, committee members, externals (e.g. project partners)

EQAR uses [Zoom](https://eqar-eu.zoom.us/signin) for audio and video conferences.

As EQAR staff hosting a conference, you should log in with your EQAR user. Please share the meeting link and room ID with participants before the meeting.

As participant, you only need the link received from the EQAR staff member hosting the conference.

There are two ways to join a Zoom conference:

 1. **Using your computer audio and video** (recommended)

    This requires a stable internet connection, a functioning speaker/headphone and microphone.

    To join a Zoom conference, simply open the link that has been sent to you by the EQAR Secretariat.

    When using Zoom for the first time, you will have to download and install a small program, but this will not take long.

 2. **Dial in by phone**

    If you do not have a functioning speaker and microphone, or you cannot download any software to your computer, you can dial into the conference using a regular telephone. See the [list of dial-in number for various countries](https://zoom.us/zoomconference)

    In addition, you can join the conference using your web browser for viewing video or screen sharing. Use the link sent to you, cancel any download/installation  and click on the link "join from your browser".

## Cloud File Storage

> **Relevant for:** staff, committee members, externals (e.g. project partners)

All meeting documents etc. are posted on a cloud storage application, [NextCloud](https://www.nextcloud.com/), hosted on an EQAR server.

Login at: <https://cloud.eqar.eu/> (with your EQAR username/email and your EQAR password)

EQAR staff will see three group folders in their home folder:

1. **EQAR documents**: includes subfolders for different topics, projects and meeting documents;
2. **EQAR archive**: includes old EQAR documents that have been moved out of the synchronised EQAR\_DOC folder;
3. **EQAR media**: is for large files, such as meeting recordings, to exclude those from automatic synchronisation; this folder might be backed up less frequently.

EQAR committee members and externals will see the folder(s) of their committee/project in their home folder.

Folders outside the shared/group folders can be used for personal documents and are only accessible by you, unless shared with other users/groups or externals by link.

NextCloud includes two applications that allow collaborative text editing:

- The simple text editor (*New text document*) has only basic formatting, but is very performant. It is ideal for simple notes etc.

- The Collabora Online application (*New Document*, *New Spreadsheet*, *New Presentation*) is an on-line version of LibreOffice. It is not always most performant, but offers a more complete feature set.

### Nextcloud app and sync

> **Relevant for:** staff

EQAR staff can install the Nextcloud client app from the Managed Software Center and have selected folders from Nextcloud synchronised with a folder on their local disk. All EQAR laptops are configured to keep a local copy of the *EQAR documents* folder. This allows working on files with a locally installed applications and also offline, for example.

All changes made on your laptop are propagated to the file server and all other laptops immediately when on-line, or the next time you are connected to the internet and the VPN. Therefore, please mind the following:

* Files deleted (even if only moved to trash on your own computer) are irrevocably deleted from the server and other computers.

* When you move files, they are actually deleted and newly copied. That is, when you move a whole folder structure, with many subfolder and files in it, this causes a lot of traffic and calls for trouble. Thus, make sure to think of folder structures carefully from the very beginning, so that no large number of files need to be moved later on.

* Avoid opening and editing files concurrently with other users. While Nextcloud can detect two users changing having changed a file during an offline period (and then keeps both versions), this is not perfect and doesn't work if two people have the same file open while on-line; the latest to save will overwrite the other's changees. If several users need to work on one document simultaneously, use Collabora Online or the plain text editor of NextCloud with preference.

* To avoid excessive traffic, do not place very large files in *EQAR documents* but use the *EQAR media* folder instead.

## VPN

> **Relevant for:** staff

Some services are restricted and accessible only from EQAR's Virtual Private Network (VPN). The VPN establishes a secure, encrypted connection (called a tunnel) between your device and the EQAR network, so that all further connections to other devices on the EQAR network are secure.

The VPN solution used by EQAR is [WireGuard](https://www.wireguard.com/). The `EQAR-VPN` connection is pre-configured on your laptop and phone. It includes a personal cryptographic key that gives access to the network. If your device was stolen or someone gained unauthorized access to it, the key will be removed from the list of authorised keys and you receive a new key.

The software should be started automatically when you log in and can be configured to connect automatically when an internet link is available. You should leave WireGuard connected at all times.

## Email

> **Relevant for:** staff

The standard email client on the office computers and laptops is Apple Mail. You can use [Mozilla Thunderbird](https://www.thunderbird.net/) alternatively.

You will have two mailboxes pre-configured on your office computer or laptop: a personal one and a shared mailbox. Your personal email address is `firstname.lastname@eqar.eu`; the email addresses `info@eqar.eu` and `application@eqar.eu` arrive into the shared mailbox.

To access your emails from outside the office, you have two possibilities:

 1. **Webmail (by our hosting provider)**

    URL: <https://webmail.all-inkl.com/index.php>

    Login: `firstname.lastname@eqar.eu`

    Here, you can also change your email password, install spam filter and other custom filters to sort incoming mail to different folders automatically, and setup auto-reply messages.

 1. **Configuring your own email client at home (via IMAP)**

    You can access your emails from all typical email clients (Thunderbird, Outlook, Apple Mail, …) via IMAP. You should use IMAP with TLS/STARTTLS, so that your password and emails are transmitted via an encrypted connection. Some programmes will correctly auto-configure once you enter the email address, but otherwise use the following settings:

    Incoming server: `w00940ec.kasserver.com` (IMAP, port 143 & TLS)

    Outgoing server: `w00940ec.kasserver.com` (SMTP, port 587 & TLS)

    Your username is your email address for both, and the password is the same as for the other options.

## Slack

> **Relevant for:** staff, external partners

Slack is an instant-messaging service used for our daily communication, especially between colleagues when working remotely. Our Slack workspace also includes the external DEQAR software development team and some external project partners.

You can use Slack from your web browser or as an installed application. On the desktop, both options work fine; on your phone, you need to install the Slack App.

The Slack workspace is accessible at <https://eqarworkspace.slack.com/> (log in with your EQAR username and password).

## Trello

> **Relevant for:** staff

Trello is a web application for managing project and team collaboration. It is based on organising lists of cards, usually each representing a task or issue. The cards come with various features, such as checklists or deadlines.

Staff need to create a separate free account at Trello and will be added to the [EQAR team To-Do board](https://trello.com/b/o8vTcuF9/eqar-team-to-do).

The EQAR team board includes a common *Inbox*, where new tasks can be added if they still need to be assigned to someone. Next to it, the board has one list per staff member.

You should keep your list up-to-date to reflect your current tasks and priorities. When tasks are completed, you should archive the card.

## Contact Database

> **Relevant for:** staff

The Contact Database (DB) is used both as a shared address book for all sorts of contacts, but also to keep information on EQAR's official relationships (members, registered agencies) and formal interactions with them (applications, change reports, annual updates).

You can access the Contact DB at <https://db.app.eqar.eu/> (login with your EQAR username and password).

Data is stored in a number of **tables**, each row representing a record in a fixed format. The tables are linked with each other, i.e. a record in one table often refers to a corresponding record in a different table. You will find both one-to-one (e.g. an organisation may also be a registered agency or a member) or one-to-many (e.g. an organisation can have many contact persons, or a registered agency can have several substantive change reports).

When a record "belongs" to another record in another table, this link is usually shown as a drop-down box in the record data. When several records in another table (may) belong to a record, this you see buttons under *Related records* in the bottom of an edit window. In case of one-to-one relationships, corresponding records from different tables usually show together and can be edited together.

While you generally edit data in tables, **queries** represent different pre-defined views that show data from one or several tables. You cannot edit data in a query, but many queries show an edit button leading that opens the record in an underlying table (where one row in a query equates one record in a specific table).

The main functions for records or tables are:  
![Edit icon](img/db-icon-edit.png) **edit** record (in case of query, edits record in underlying table)  
![View icon](img/db-icon-view.png) **view** record (in read-only table or query)  
![Delete icon](img/db-icon-delete.png) **delete** record (in case of query, deletes record in underlying table)  
![New icon](img/db-icon-new.png) **create** new record  
![Download icon](img/db-icon-view.png) **download** current view as CSV file  
![Template icon](img/db-icon-template.png) **fill** template or existing document with record data (ODT files only)  

The **fill template** function is available both from the list and from an open record (small button next to unique ID of the record). You can upload a template document or an existing document to refresh data. The text of the document will not be changed, only field codes will be added/updated. This feature fills data from the current record and cascades two levels further to include "superior" records. The data is saved in document metadata and can be accessed as fields (menu: *Insert* &gt; *Field* &gt; *More fields...* or shortcut: &#8997;`F2`, tab *DocInformation*, entries under *Custom*).

With the **search box** on the main page, you can perform a quick search across most tables. This is the easiest way to check, for example, whether a person is already included in the contact DB.

The following overview of tables is organised to illustrate the main relations. Strictly speaking, there is no hierarchical order and there are several more relations between tables.

The column *Cardinality* describes how many of these records can exist, in relation to one record in the "parent" table:

* ** 0..1 ** none or one, e.g. an organisation may be an EQAR member, but does not have to be, and it can only once be a member
* ** 0..\* ** any number, e.g. there is not necessarily any Register Committee member with conflict of interest in a case, but there may be one or several
* ** 1..\* ** at least one, e.g. there is at least one application from an organisation that has applied for registration

| Table                                                                 | One record describes ...                                                                      | Cardinality   |
|-----------------------------------------------------------------------|-----------------------------------------------------------------------------------------------|:-------------:|
| **Organisations**                                                     | any kind of organisation that EQAR is in contact with                                         |               |
| &ndash;&nbsp;EQAR&nbsp;Members                                        | an organisation that is a member of EQAR                                                      | 0..1          |
| &ndash;&nbsp;Registered&nbsp;and&nbsp;applicant&nbsp;agencies         | an organisation that is a registered agency or that had applied for registration              | 0..1          |
| &ndash;&nbsp;&ndash;&nbsp;Applications                                | one application for registration or renewal of registration                                   | 1..\*         |
| &ndash;&nbsp;&ndash;&nbsp;&ndash;&nbsp;Panel&nbsp;members             | one external review panel member in that application                                          | 1..\*         |
| &ndash;&nbsp;&ndash;&nbsp;&ndash;&nbsp;Clarification&nbsp;requests    | one clarification request made in the context of an application                               | 0..\*         |
| &ndash;&nbsp;&ndash;&nbsp;&ndash;&nbsp;Conflicts&nbsp;of&nbsp;interest | one Register Committee member who declared conflict of interest for an application           | 0..\*        |
| &ndash;&nbsp;&ndash;&nbsp;Substantive&nbsp;Change&nbsp;Reports        | one Substantive Change Report by a registered agency                                          | 0..\*         |
| &ndash;&nbsp;&ndash;&nbsp;Annual&nbsp;updates                         | the number of EQA activities by one agency, of one type, in one country, in one year          | 0..\*         |
| &ndash;&nbsp;DEQAR&nbsp;CONNECT&nbsp;partners                         | an organisation that is a project partner in DEQAR CONNECT                                    | 0..1          |
| &ndash;&nbsp;DEQAR&nbsp;project&nbsp;partners                         | an organisation that was a partner in the 1st DEQAR project                                   | 0..1          |
| &ndash;&nbsp;Financial&nbsp;accounts&nbsp;(Octopus)                   | an organisation that has a supplier or client account in EQAR's accounting                    | 0..1          |
| **Persons**                                                           | any individual                                                                                |               |
| &ndash;&nbsp;Contact&nbsp;person                                      | a link of an individual to an organisation                                                    | 0..\*         |
| **Countries**                                                         | a country                                                                                     |               |
| **Organisation roles**                                                | a type of organisation                                                                        |               |

### Snapshot Backups

All files from Nextcloud are backed up to a second cloud storage (daily). The backup store retains snapshots from the last days. That is, if accidentally deleted or overwritten, a file can usually be retrieved, incl. possibly some previous versions if needed.

> **Please note**: only the cloud server is backed up, i.e. files saved in Nextcloud synced folders. Files saved on your local computer or laptop only are not backed up.

### Organising Files

#### General

As several people use the file shares in their work, please follow these general principles:

* Make sure to name and structure folders and files clearly and logically, so that others can find documents intuitively.

* Create folders and subfolders to make sure that the number of files in one folder doesn't grow excessively.

* Try to think ahead when creating folder structures and naming files, i.e. ask yourself which other files might end up in the same folder later. (This will avoid excessive moving later on.)

* Third-party documents (e.g. from meetings attended, etc.) should be saved in `eqar_doc` only when EQAR staff has worked on them, or if they are really essential for EQAR (`eqar_doc` is not a library, but for documents worked on by EQAR staff).

#### Versions

In order to ensure consistency and clarity, every document should normally only exist once in an editable format (i.e. OpenDocument or Microsoft office format). This should be the latest version.

Older version should generally not be edited, and hence be kept in PDF format if they need to be retained (e.g. in case of official documents). In that case, versions should be numbered for clarity.

When it is not really necessary, there is no need to retain old versions explicitly, as they could be retrieved from the backup if really needed.

In other words: as a rule, there should be one editable document without a version number, and there can be several PDFs, each with a version number.

The following would be a typical number of files for a formal document:

* `RC26_03_1_NewSpecialPolicy.odt`: latest version, editable
* `RC26_03_1_NewSpecialPolicy_v0_1.pdf`: version 0.1 – e.g. first draft
* `RC26_03_1_NewSpecialPolicy_v0_2.pdf`: version 0.2 – e.g. revised draft
* `RC26_03_1_NewSpecialPolicy_v1_0.pdf`: version 1.0 – (first) final
* `RC26_03_1_NewSpecialPolicy_v1_1.pdf`: version 1.1 – draft revision
* `RC26_03_1_NewSpecialPolicy_v2_0.pdf`: version 2.0 – (revised) final

If there are good reasons, you can always choose a different structre.

#### Naming

Official meeting documents should be named after a common format:

`BBn_ii_x_tttt...`

|       | |
|-------|-------------------------------------------------------|
| BB    | Statutory body (EB, GA, RC, AC)                       |
| n     | Number of the meeting (see folder names)              |
| ii    | Number of the item on the agenda, or M for minutes    |
| x     | Document number under this item (starting with 1)     |
| tt... | Description of the document (text)                    |

#### Directory structure

The following is the main structure of the `eqar_doc` share; the `eqar_archive` share mirrors that structure.

- **Administration**: documents on various administrative issues/topics

    - **Corporate Design**: information about the EQAR corporate design
    - **Fonts**: EQAR standard fonts for use in publications
    - **Logos**: EQAR logo in different versions, resolutions and file types; partner logos (E4); Commission logo; Bologna logo
    - **Membership**: memberships of EQAR in other organisations
    - **Moniteur Belge**: publications in the Belgian official gazette
    - **Office**: office rent etc.
    - **Printing**: stationery, business cards, etc. ready for printing as PDF
    - **Templates**: various templates for letters, standard documents, official documents, internal notes and presentations
    - **Trademark**: documents related to the registration of EQAR as a trademark
    - **Travel**: relating to contracts with the travel agency, insurances, etc.

- **Agencies**: everything related to applications and registered quality assurance agencies

    - **AGENGY-ACRONYM**: subfolder for each agency
        - **YYYY-MM_TYPE**: subfolders for applications, change reports, etc., with *YYYY-MM* being the submission date and *TYPE* being *Initial* application for inclusion, *Renewal* application, substantive *Change* report, third-party *Complaint* or *Extraordinary* review of registration

- **Correspondance**; general correspondence, unless it belongs somewhere else

    - **Annual Update**: annual surveys of registered agencies on their EQA activities
    - **EQAR Communication with NonMembers**: letters to non-member EHEA governments
    - **Incoming**: incoming letters, faxes, etc.
    - **Nominations**: invitations to nominate EB and RC members
    - **Signatures**: scanned signatures

- **Documents**: all sorts of documents that do not fit anywhere else, such as leaflets, papers, notes, etc.; larger publications (e.g. Annual Report, Guide for Applicants, Internal Handbook) have their own subfolder

    - **Articles**: articles written by EQAR staff for newsletters, publications, etc.
    - **BFUG Reports**: EQAR reports/updates prepared for the Bologna Follow-Up Group meetings
    - **CVs**: CVs of EQAR staff and committee members
    - **E4**: documents of E4 meetings
    - **EQAR Charts**: charts explaining EQAR, can be used for publications
    - **ESG Revision**: documents from the 2012-2015 ESG revision process
    - **External meetings**; key documents from external meetings/groups in which EQAR is represented
        - **GROUP/MEETING**: subfolders by different groups or meetings
            - **DATE AND PLACE**: subfolders by meetings of that group
    - **Internal**: internal notes or communicationsa
    - **Mailtool**: documents for serial emails
    - **Presentations**: presentations given by EQAR representatives externally
    - **Reports**: essential third-party reports that are of special interest for EQAR, e.g. ESG and Bologna communiqués
    - **Various**: anything that does not fit somewhere else &ndash; avoid.

- **External meetings**: link to this folder under *Documents*

- **Finances**: finance-related documents

    - **AirPlus**: related to AirPlus company and debit accounts, payment means for travel bookings
    - **AnnualAccounts**: final, audited versions of all annual accounts
    - **Envelopes**: payment envelopes
    - **Expenses**: incoming invoices, with subfolders per year, within each folder documents numbered by Octopus document number
    - **Invoices**: outgoing invoices, with subfolders per year, within each folder documents ordered by invoice number
    - **Membership fee scale**: supporting documents for calculation of membership fees (e.g. GDP data)
    - **Octopus backups**: backup files of the accounting software
    - **Reimbursement**: reimbursement forms (both internal and external)
    - **VAT**: documents related to VAT

- **Meetings**: files related to the organisation of EQAR meetings; content documents are stored under *Official documents* for EQAR statutory body meetings and here for other meetings (e.g. Members' Dialogue)

    - **MEETING_YYYY-MM-DD**: subfolders per meeting

- **Official documents**: all content documents of official statutory meetings/bodies
    - **Applications**: various internal and external templates (e.g. Internal Assessment Sheet, decisions, cover letters, ...)
    - **EBnn, GAnn, RCnn, ACnn**: subfolders for each particular meeting of the Executive Board, General Assembly, Register Committee, Appeals Committee
    - **EB, GA, RC, AC** (without number): documents and decisions made by email, and documents of a permanent nature (i.e. policies, Code of Conduct, or similar)
    - **Founding**: documents related to the official founding of EQAR
    - **Membership**: official documents related to membership in EQAR (governments, E4, ...)
    - **Statutes**: EQAR statutes, final version and earlier drafts (see archive)

- **Projects**: all documents related to specific projects (coordinated by EQAR or not)
    - **PROJECT\_ACRONYM**: subfolder for each project, with a subfolder structure within that is appropriate to the project

- **Staff**: everything related to Secretariat staff (mostly accessible to Director only)

- **Website**: documents related to the website www.eqar.eu
    - **Photos**: photos of all EQAR staff and committee members – only for small, edited pictures – use media share for big files!

## Shared Calendar

> **Relevant for:** staff, president

We are using a shared calendar via NextCloud. It can be accessed via the NextCloud web interface, Thunderbird, the Apple Calendar app or any program supporting CalDAV using the following URL:

<https://cloud.eqar.eu/>

Please prepend event titles with your initials (and those of other EQAR staff involved).

## Technical details

> This section documents the technical details and is **not** meant for regular users.

### Network

The **EQAR VPN** (_IPv4 subnet: 10.12.0.0/16_) includes the cloud infrastructure and VPN clients. It is subdivided in a number of /24 subnets, as detailed in the table below.

![Overview EQAR office network and VPN](img/Chart_EQAR-network.svg)

An internal DNS server runs on the cloud application server VPS, which is configured as sole DNS resolver on all VPN clients. The DNS server hosts the internal zones (`app.eqar.eu`, `int.eqar.eu`, `testzone.eqar.eu`) and forwards other queries to the provider's DNS servers.

The internal DNS server resolves `appsrv.eqar.eu`, `backend.deqar.eu`, etc. to their internal IP addresses, so that all services are accessed through the EQAR VPN when connected to it. This extends to all additional DNS names of these VPS, except `vpn.eqar.eu` (as the VPN connection itself can't be routed through the VPN for obvious reasons).

The canonical way to test the connection to the EQAR network is to open <https://appsrv.eqar.eu/>: it leads to the internal portal from the VPN, and to an access-denied page from external IPs (incl. from the office network when not connected to the VPN).

The following tables summarise the statically and dynamically assigned IP addresses in the networks:

| Public IP     | Host                                      | DNS name(s)                                                                           | Services (available publicly)                                                                                                 | 
| ------------- | ----------------------------------------- | ------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------- |
| 212.44.107.66 | EQAR application server (KVM VPS)         | appsrv.eqar.eu,<br />various CNAMEs,<br />vpn.eqar.eu                                 | HTTP & HTTPS<br />WireGuard (51820)<br />LDAP (from websrv)<br />SSH (from known IPs)             |
| 212.44.104.63 | EQAR webserver (LXC VPS)                  | www.eqar.eu<br />\*.eqar.eu                                                           | HTTP & HTTPS                                                                                      |

| LAN IP                        | Host                                  | Services (interal)                                                                                            | Host config   |
| ----------------------------- | ------------------------------------- | ------------------------------------------------------------------------------------------------------------- | ------------- |
| *(to update)*                 | Router (managed by EQAR)              | DHCP<br />DNS<br />default gateway                                                                            | static        |
| *(to update)*                 | Printer Ineo+ 224e                    | IPP, LPD, 9100                                                                                                | static        |
| *(to update)*                 | DHCP pool for office clients          |                                                                                                               | dynamic DHCP  |
             
| VPN IP           | Hostname                  | Host                          | Services (in addition to public)                                                          | Host config       |
| ---------------- | ------------------------- | ----------------------------- | ----------------------------------------------------------------------------------------- | ----------------- |
| 10.12.0.1        | appsrv.eqar.eu            | EQAR application server (VPS) | SSH<br />DNS<br />HTTP (nginx)                                                            | static            |
| 10.12.0.10       | eqar-db-live.int.eqar.eu  | Contact DB (appsrv Docker)    | HTTP(6080)<br />MariaDB(3306)<br />LDAP(389)                                              | static virtual IP |
| 10.12.0.20       | docker-misc.int.eqar.eu   | Various (appsrv Docker)       | Onlyoffice(8080)<br />Collabora(9980)<br />Limesurvey(7080)<br />MicroMDM(4080)           | static virtual IP |
| 10.12.0.30       | deqar-live.int.eqar.eu    | DEQAR live (appsrv Docker)    | Backend(8000)<br />Frontend(8080)<br />Postgres(5432)                                     | static virtual IP |
| 10.12.0.31       | deqar-sandbox.int.eqar.eu | DEQAR sandbox (appsrv Docker) | Backend(8000)<br />Frontend(8080)<br />Postgres(5432)<br />Wordpress(9080)                | static virtual IP |
| 10.12.0.40       | ssikit.int.eqar.eu        | SSIkit (appsrv Docker)        | Core(7000)<br />Signatory(7001)<br />Custodian(7002)<br />Auditor(7003)<br />ESSIF(7004)  | static virtual IP |
| 10.12.0.90       | docker-test.int.eqar.eu   | Test various (appsrv Docker)  | Wordpress(9080)                                                                           | static virtual IP |
| 10.12.0.91       | deqar-test.int.eqar.eu    | DEQAR test (appsrv Docker)    | Backend(8000)<br />Frontend(8080)<br />Postgres(5432)                                     | static virtual IP |
| _10.12.0/24_     |                           | _reserved (future use)_       | _routed to application server_                                                            |                   |
| 10.12.10/24      |                           | Containers (systemd-nspawn)   | running on application server                                                             |                   |
| 10.12.12/24      | _xx-mba.int.eqar.eu_      | VPN clients                   | only IPs 100-250 used                                                                     | WireGuard         |
| 10.12.100-250/24 |                           | VPN clients (local subnets)   | one /24 subnet reserved per client                                                        | WireGuard / local |

### Client Configuration

Office computers and laptops are configured and managed through:

- [Munki](https://www.munki.org/munki/) Managed Software Center, used to install:
    - System configuration profile
    - Kerberos configuration
    - All common software packages
- LDAP (user database and automount)
- User-level configuration profile (install from <https://accounts.eqar.eu/selfmodify>)

### LDAP

LDAP service is provided by [OpenLDAP](https://www.openldap.org/)'s slapd.

EQAR users, groups and network configuration (e.g. automounts) are stored under `ou=users,dc=eqar,dc=eu`. This tree is served by `ldap.int.eqar.eu` (alias for `auth-prod` container).

In addition, `ldap-contacts.int.eqar.eu` (alias for `ldap` Docker container of `eqar_db`) provides read-only access to the EQAR contact DB via LDAP under `dc=Contacts,dc=eqar,dc=eu`.

#### User template

```ldif
uid: mnovak
userPassword: {SASL}mnovak@EQAR.EU
sn: Novak
givenName: Mojca
cn: Mojca Novak
mail: mojca@novak.si
objectClass: inetOrgPerson
objectClass: organizationalPerson
objectClass: person
```

(in addition, add `memberUid:` to group)

#### Posix group template

```ldif
cn: externals
gidNumber: 1999
description: External accounts
objectClass: posixGroup
```

### Kerberos

Kerberos 5 is used for central password database and single sign-on in EQAR. The realm used is `EQAR.EU`.

The Kerberos database is hosted on `auth-prod` (alias: `kerberos.int.eqar.eu`); this machine provides both Key Distribution Center (KDC) and administration server (e.g. for password change) service.

### Single Sign-On

Depending on the service, sign on works in either of three ways:

- Natively through Kerberos or GSSAPI
- LDAP bind, forwarded to Kerberos by SASL library
- SAML service provided by SimpleSAMLphp, using LDAP as a backend

The following tables shows which service/application used which approach:

| Service       | Authentication | Groups       | EQAR staff | Committees | Externals |
| ------------- | -------------- | ------------ |:----------:|:----------:|:---------:|
| NextCloud     | LDAP           | LDAP         | X          | X          | X         |
| Slack         | SAML           | n/a          | X          |            | X         |
| Trello        | SAML           | n/a          | X          |            |           |
| Zoom          | SAML           | n/a          | X          | limited    | limited   |
| Wordpress     | LDAP           | local        | X          | X          |           |
| Matomo        | LDAP           | n/a          | X          |            |           |
| Contact DB    | PAM            | n/a          | X          |            |           |
| Profile       | Kerberos       | n/a          | X          |            |           |
| Limesurvey    | LDAP           | n/a          | X          |            | X         |
				
Login to these services is currently **not** integrated in the single sign-on solution:

| Service       | Protocol(s)   | Login type |
| ------------- | ------------- | ---------- |
| DEQAR         | web, REST API | individual |
| Email         | IMAP          | individual |
| FCm           | web           | individual |
| Formsite      | web           | shared     |

### Snapshot Backups

Snapshot backups are run using a set of [custom scripts](https://github.com/EQAR/backup-scripts), triggered by systemd timers.

The root volumes of `appsrv` is backed up nightly to the separate cloud storage.

Database snapshots are taken from all relevant applications, saved in `/var/lib/db-dumps/` and thus includes in the daily snapshot backup.

