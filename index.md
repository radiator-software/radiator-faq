---
---

<div id="radiator-links" style="font-weight: bolder;" markdown="1">
[Radiator Software ↗](https://radiatorsoftware.com/) &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
[Radiator AAA Server ↗](https://radiatorsoftware.com/products/radiator/)
</div>

Updated: {{ site.time | date: "%Y-%m-%d" }}

<div id="toc-cont" markdown="1">
- TOC
{:toc}
</div>


## General questions {#general}

### What is the best RADIUS server? {#best-radius-server}

From our point of view, Radiator AAA Server is the best choice for **RADIUS**, **RadSec**, **Diameter**, **TACACS+** and other **AAA** server needs. Because of the flexibility of Radiator, our customers call it the *Swiss Army knife of RADIUS servers*. More info on Radiator can be found from Radiator product site <https://radiatorsoftware.com/products/radiator/>

### Is Radiator open source? {#is-radiator-open-source}

Radiator is not open source, but when you purchase Radiator, full source code is always supplied.

### How much does Radiator cost? {#how-much-radiator-cost}

You can see selected Radiator licence prices at <https://radiatorsoftware.com/pricelist/>. Pricing for the Radiator add-on modules is provided upon request by contacting Radiator sales.

### Who is using Radiator? {#who-is-using-radiator}

Radiator AAA server is used for user and network authentication by a huge range of different organisations: educational institutions, cities, governmental organisations, ISPs and telecom companies, managed service providers, utility companies, and private businesses in various fields such as hospitality, finance, defence and medical industries.

### References {#references}

Radiator has a large and active worldwide customer base. Please see our website for customer references: <https://radiatorsoftware.com/customers/> and <https://radiatorsoftware.com/use-cases/>

### Is there an online demo available? {#online-demo}

There is a Radiator Demo Cloud online demo - you can book a timeslot to go through typical Radiator use cases (or possibly your own use case) with Radiator experts.

### Where is the Radiator team based? {#radiator-team-based}

The Radiator team is based in Finland, where development and sales are done. At the same time, we also have a worldwide partner network providing support and consultation.

### Who is behind Radiator? {#who-is-behind-radiator}

Radiator was developed by Australian-based *Open System Consultants (OSC)* 1998-2013, until the Finnish team acquired OSC in 2013 and took over Radiator development and business. The resulting company is Radiator Software.

### Who is the manufacturer for Radiator? {#manufacturer-for-radiator}

*Radiator Software Oy* is the sole manufacturer of Radiator AAA Server software. *Radiator Software* sells Radiator licences globally and you can buy a licence directly from the Radiator team. Radiator licences are also sold through various distribution partners all over the world.

### What do I need to know if plan to start using RADIUS or change from another product to Radiator? {#requirements-document}

It's good to create a requirements document describing what you need Radiator to do. The requirements include at least the following information:

#### 1. RADIUS clients
- The list of **client devices** that will be sending RADIUS requests to Radiator
- The associated **device types** for all client devices

#### 2. Authentication methods
- The **authentication** required for your users, together with any **user groups**
- The **authentication method** required for your users and/or groups - ie. LDAP, SQL, etc.

#### 3. Authorisation
- The **authorisation** required for your users, user groups, or devices. For example, checking if user or device belongs to certain group or is listed on the allow or deny lists.
- RADIUS **reply attributes**, Change-of-Authorisation (CoA) messages, etc. which need to be sent to the client devices. If vendor-specific RADIUS attributes (VSA) are used, the RADIUS dictionary or detailed information of such attributes.
- Any **additional functionality** which needs to be done, such as IP address allocation, VLAN assignment, etc.

#### 4. Accounting and logging
- Any **accounting** processing that is needed and where the accounting data should be stored
- What **logging** you require for user authentication, user accounting, server log, etc.

#### 5. Other requirements
- Any **special requirements** that can't be met with normal Radiator configuration (ie. hooks, scripting)
- Any other **integration with external systems**
- Expected **amount of requests** or users.

This is a basic list and there are probably other requirements that you are aware of.

## Features {#features}

### Which RFCs, protocols and authentication methods are supported by Radiator? {#rfcs-protocols-and-authentication-methods}

Full list can be seen from our technical documentation, but short listing is here:


- Complies with RFCs [2548](https://datatracker.ietf.org/doc/html/rfc2548), [2619](https://datatracker.ietf.org/doc/html/rfc2619), [2621](https://datatracker.ietf.org/doc/html/rfc2621), [2865](https://datatracker.ietf.org/doc/html/rfc2865), [2866](https://datatracker.ietf.org/doc/html/rfc2866), [2867](https://datatracker.ietf.org/doc/html/rfc2867), [2868](https://datatracker.ietf.org/doc/html/rfc2868), [2869](https://datatracker.ietf.org/doc/html/rfc2869), [3579](https://datatracker.ietf.org/doc/html/rfc3579), [4669](https://datatracker.ietf.org/doc/html/rfc4669), [4671](https://datatracker.ietf.org/doc/html/rfc4671), [5176](https://datatracker.ietf.org/doc/html/rfc5176), [5997](https://datatracker.ietf.org/doc/html/rfc5997)
- Dictionary or other applicable support for RFCs [4372](https://datatracker.ietf.org/doc/html/rfc4372), [4849](https://datatracker.ietf.org/doc/html/rfc4849), [4675](https://datatracker.ietf.org/doc/html/rfc4675), [4849](https://datatracker.ietf.org/doc/html/rfc4849), [5080](https://datatracker.ietf.org/doc/html/rfc5080), [5447](https://datatracker.ietf.org/doc/html/rfc5447), [5580](https://datatracker.ietf.org/doc/html/rfc5580), [5607](https://datatracker.ietf.org/doc/html/rfc5607), [5904](https://datatracker.ietf.org/doc/html/rfc5904), [6158](https://datatracker.ietf.org/doc/html/rfc6158), [6929](https://datatracker.ietf.org/doc/html/rfc6929), [6519](https://datatracker.ietf.org/doc/html/rfc6519), [6572](https://datatracker.ietf.org/doc/html/rfc6572), [6677](https://datatracker.ietf.org/doc/html/rfc6677), [7055](https://datatracker.ietf.org/doc/html/rfc7055), [7268](https://datatracker.ietf.org/doc/html/rfc7268), [8044](https://datatracker.ietf.org/doc/html/rfc8044)
- Supports RFC [6614](https://datatracker.ietf.org/doc/html/rfc6614), also known as RadSec – secure, reliable RADIUS proxying
- Acts as a Diameter to RADIUS gateway for NAS authentication and accounting. Supports Diameter RFCs [3588](https://datatracker.ietf.org/doc/html/rfc3588), [6733](https://datatracker.ietf.org/doc/html/rfc6733), [4072](https://datatracker.ietf.org/doc/html/rfc4072), [4005](https://datatracker.ietf.org/doc/html/rfc4005), [7155](https://datatracker.ietf.org/doc/html/rfc7155)
- Acts as a RADIUS to Diameter gateway for NAS authentication and accounting.
- Supports EAP in accordance with RFC [3748](https://datatracker.ietf.org/doc/html/rfc3748)
- Supports EAP-MD-Challenge, EAP-OTP and EAP-GTC, RFC [3748](https://datatracker.ietf.org/doc/html/rfc3748)
- Supports EAP TLS, RFC [5216](https://datatracker.ietf.org/doc/html/rfc5216)
- Supports EAP TTLS, RFC [5281](https://datatracker.ietf.org/doc/html/rfc5281)
- Supports PEAP, IETF drafts and MS-PEAP
- Supports EAP-MSCHAP-V2
- Supports Cisco LEAP
- Supports EAP-FAST, RFC [4851](https://datatracker.ietf.org/doc/html/rfc4851)
- Supports EAP-pwd, RFC [5931](https://datatracker.ietf.org/doc/html/rfc5931)
- Supports EAP-PSK, RFC [4764](https://datatracker.ietf.org/doc/html/rfc4764)
- Supports EAP-PAX, RFC [4746](https://datatracker.ietf.org/doc/html/rfc4746)
- EAP-SIM, EAP-AKA, EAP-AKA’, 3GPP AAA Server and other related features are available through Radiator SIM Pack
- Acts as authentication server for IEEE 802.1X with support for IEEE 802.1AE, also known as MACsec
- Supports HOTP, RFC [4226](https://datatracker.ietf.org/doc/html/rfc4226)
- Supports TOTP, RFC [6238](https://datatracker.ietf.org/doc/html/rfc6238), sometimes referred as Google Authenticator
- RADIUS SIP Digest authentication per draft-sterman-aaa-sip-00.txt and RFC [5090](https://datatracker.ietf.org/doc/html/rfc5090)
- Diameter 3GPP EIR and other carrier features are available through Radiator Service Provider Pack
- Diameter 3GPP GBA/BSF support for VoLTE Supplementary Services and other related features are available through Radiator GBA/BSF Pack
- Diameter 3GPP PCRF, PCEF, OCS, and other Diameter and RADIUS related policy and charging features are available through Radiator Telco Pack
- Complies with 3GPP2 P.S0001-A Wireless IP Network Standard up to version 3GPP X.S0011

### What platforms are supported by Radiator? {#supported-platforms}

Radiator supports all **the most used operating systems** (Unix, Linux, Windows and Mac OS). For a complete list for different operating systems and for example Linux distributions, please see <https://radiatorsoftware.com/supported-platforms/>

### I know I can use telnet, but can I use ssh? {#telnet-ssh}

Radiator is an AAA (authentication, authorisation and accounting) software, which provides RADIUS, RadSec, Diameter and TACACS+ protocol implementations. This means Radiator can be used among other things to authenticate SSH as well as Telnet login (shell) sessions with for example username-password or multi-factor authentication via RADIUS/RadSec protocol. The integration to actual login process can be implemented by for example `pam_radius` and SSH servers provided by the operating system.


## Database {#database}

### What databases are supported by Radiator? {#database-support}

Radiator supports SQL and LDAP databases. Database support includes a wide selection of popular databases, including but not limited to MySQL, MariaDB, Oracle, PostgreSQL, Microsoft SQL Server, and Active Directory, OpenLDAP, etc.

### Why is there no database included? {#internal-database}

Radiator doesn't include its own database, as it is designed to be integrated with existing databases so that customer's data, and database tools and frontends can be utilised without duplicating information to different systems. This saves effort as there is no need to manage and backup several different databases, and for example user data can be edited with familiar tools by non-technical staff.

### Should database be located on the same server as Radiator? {#database-location}

The basic recommendation is that Radiator and database are on different servers. If they are located on the same server, there can be performance issues if the RADIUS requests and database are using the same resources. When the database and Radiator are on different servers, the network devices between must be configured in a way that allows Radiator to access the database.

### How is database HA ensured? {#database-ha}

Radiator leverages customer's existing database infrastructure. High-availability is achieved through database backend's own mechanics and tools, be it a redundant server in next cabinet or n-way replication on different datacenters.

Multiple database sources can be specified for Radiator. Whenever Radiator connects to a database, connection to the first listed source is tried. If that connection fails, Radiator tries the second, third and so on, until all the databases are tried, and finally gives up without replying to the NAS. This gives the NAS the opportunity to fall back to another RADIUS server if all SQL databases are down.

See also [How is RADIUS high-availability achieved?](#radius-ha)

### How can I connect to Oracle database? {#oracle-connection}

Connection to Oracle database needs a bit more preparations than some other databases.

Before configuring Radiator, install and configure the needed Oracle tools and libraries, and test the database connection using Oracle's sqlplus tool.

For Oracle Instant Client, install the following packages:

  * The "Basic" package for the essential Oracle libraries.
  * The "SDK" package for the headers and makefile.
  * The "SQL*Plus" component is optional, but will help you check your configuration and DBD::Oracle determine your Oracle version.

After checking prerequisites are met, to enable Oracle support in Perl environment, you can install Perl packages

  * DBI (high-level database abstraction: <https://metacpan.org/pod/DBI>)
  * DBD::Oracle (low-level database driver: <https://metacpan.org/pod/DBD::Oracle>)

To configure Radiator for Oracle access, please see the following files in _/opt/radiator/radiator/goodies_ directory (Windows: directory _\Radiator\Radiator\goodies\\_ on the drive Radiator is installed on) for configuration samples:

  * sql.cfg
  * oracleCreate.sql

These files provide a simple example configuration for authentication from SQL-based database, as well as an example on the database structure for simple databases used in AuthBy SQL.

See also [Problems with Oracle database connection?](#oracle-connection-problem)

## Installation {#installation}

### Perl versions {#installation-perl}

Radiator requires Perl 5.8.8 or newer to function. Radiator is written entirely in Perl and is therefore highly portable. We also provide full source code. Many Unix distributions include Perl as part of the standard installation. Common Windows Perl distributions include ActivePerl and Strawberry Perl. For easy deployment on Windows environments, the Radiator MSI package contains a Strawberry Perl portable version.

### How do I install Radiator? {#installation-radiator}

Radiator offers a wide selection of installation packages in various formats, for example RPM, deb and MSI. In case a suitable format is not available, Radiator can also be installed from the source archive package. In addition of Radiator releases, we also have testing packages available. Testing packages contain changes planned for the next Radiator release.

Radiator installation packages are available for manual download from Radiator Software downloads site <https://downloads.radiatorsoftware.com/packages/> (credentials needed), and RPM and deb packages can also be installed from our repositories <https://downloads.radiatorsoftware.com/repo/> (credentials or repository key needed).

Installation instructions for various cases are available in [Radiator reference manual](https://files.radiatorsoftware.com/radiator/ref/) chapter [Installing and upgrading Radiator](https://files.radiatorsoftware.com/radiator/ref/Installation.html), as well in our web pages <https://radiatorsoftware.com/products/radiator/installation/>

### Where the packages end up on Linux distributions? {#installation-linuxenv}

When Radiator is installed on Linux, several locations are created. Radiator default configuration is available for modifications on _/etc/radiator/radiator.conf_, logs by default go to Radiator log directory _/var/log/radiator/_ and the full source code to _/opt/radiator/_. For full list of all locations created, see installation instructions on [Radiator reference manual](https://files.radiatorsoftware.com/radiator/ref/) chapter [Installing and upgrading Radiator](https://files.radiatorsoftware.com/radiator/ref/Installation.html), for example [on Red Hat Enterprise Linux and variants using RPM](https://files.radiatorsoftware.com/radiator/ref/Installation.html#Linux-el-rpm-Installation).

The Radiator goodies which has several example configurations is available in _/opt/radiator/radiator/goodies/_

### Where the packages end up on Windows environment? {#installation-winenv}

When Radiator is installed on Windows, the installation package automatically uses the disk with the most space available. The exact installation location is shown on the installation dialog once the installation is finished. Radiator is installed to the _\Radiator\Radiator\\_ directory, for example if E drive was used the location would be _E:\Radiator\Radiator\\_. The Radiator MSI package also includes Strawberry Perl, which is installed to the _\Radiator\StrawberryPerl-Radiator\\_ directory. The Radiator default configuration and default log directory is _\Program Files\Radiator\\_ directory.

The Radiator goodies which has several example configurations is available in _\Radiator\Radiator\goodies\\_

See more from Radiator reference manual chapter [Installing and upgrading on Windows](https://files.radiatorsoftware.com/radiator/ref/Windows.html).

### Where to add licence key (evaluations)? {#installation-evaluationlicense}

Radiator Software offers an evaluation license which allows trying out and testing Radiator AAA server easily. With the evaluation version, the license key must be available in the Radiator configuration.

When starting Radiator server process you may find the following line in logs indicating that the license key is not valid:

```
ERR: Your Radiator license has expired or the licensed maximum request count has been reached
```

The license key details provided by Radiator Software can be copied directly to the Radiator configuration, but the recommended option is to have the license information as a separate file, which is then included in the Radiator configuration.

- First copy your license key details to the Radiator host, target file name `license.conf` under directory `/etc/radiator` on Linux environments or `\Program Files\Radiator\` on Windows environments.
- Then check the Radiator configuration file `radiator.conf` usually located in the same directory. Make sure (and edit if needed) that the file includes lines with `DbDir` and `LicenseFile` near the top of the Radiator configuration, before the `DictionaryFile` definition.
```
  # Additional configuration files go to DbDir.
  # On Windows, replace /etc/radiator for example with C:\Program Files\Radiator
  DbDir       /etc/radiator
  # Read possible license configuration parameters from this file
  LicenseFile %D/license.conf
``` 
- Once the license key is added to the Radiator configuration, Radiator server process must be restarted so that the new content of the license file is read. Use `systemctl restart radiator` on Linux environments or restart Radiator service from Services on Windows environments.

### Can I run Radiator in a Docker container? {#run-docker}
Radiator can be run in a Docker container. Starting from Radiator 4.25 we have included Dockerfiles with the distribution to make it easier for running Radiator in a container. Check out more details from our blog: <https://blog.radiatorsoftware.com/2020/10/radiator-dockerfiles-now-available.html>

### Migrating Radiator to a new server {#installation-migrate}
Migrating Radiator to a new server is simple. First set up the new server so it has access to any needed services like databases, active directories, log services etc. and configure the new server firewall settings as needed. Once the networking side is prepared, install Radiator to the new server from deb/RPM/MSI package. Copy the existing configuration files from the old server over to the new server. If the Radiator on the new server is newer version, check if the configuration requires any changes based on the revision history: <https://radiatorsoftware.com/products/radiator/history/>. Once all the configuration files have been copied over from the old server, restart Radiator service.

After the restart check the Radiator process log file, usually named radiator.log and located under _/var/log/radiator/_ on Linux or _C:\Program Files\Radiator\\_ on Windows, for any errors that might appear. Also keep an eye on the Radiator process log file when the traffic is starting to come to the new server. For example there could be manually installed additional Perl packages on the old server that haven't been installed to the new server and such missing package would show up in the log. During the migration it is recommended to have at least `Trace 3` enabled on the Radiator configuration if the `Trace 4` (debug) level is not possible. This will ensure smooth migration as the Radiator process log can be used to identify possible issues with the new server. See more about the log levels from Radiator reference manual: <https://files.radiatorsoftware.com/radiator/ref/GlobalParameters.html#Trace>


## Configuration {#configuration}

### How to configure Radiator {#configration-howto}

When Radiator starts, it reads its configuration from a file. This configuration file is typically named _/etc/radiator/radiator.conf_ and it can be edited with a text editor. Radiator configuration files can include additional parts of configuration from one or many other files. On Windows the Radiator configuration goes to
_\Program Files\Radiator\\_ folder.

### Where can I find Radiator reference manual? {#configuration-manual}

Latest Radiator reference manual is available on our web pages, both in HTML: <https://files.radiatorsoftware.com/radiator/ref/index.html> and PDF format: <https://files.radiatorsoftware.com/radiator/ref.pdf>.

The PDF manual is also available on the disk after Radiator has been installed from a .deb or a .RPM archive, see directory _/opt/radiator/radiator/doc/_. On Windows, see _\Radiator\Radiator\doc\\_ on the drive Radiator installs on.

### Where can I find Radiator sample configurations? {#configuration-samples}

When you install Radiator from a .deb or a .RPM archive, see directory _/opt/radiator/radiator/goodies/_. This directory has configuration samples, some utility programs and other configuration related files. On Windows, see _\Radiator\Radiator\goodies\\_ on the drive Radiator installs on.

Here's an example on Linux of how to set up a basic configuration that uses a text file for user credentials and authorisation settings. On Windows, adjust the paths accordingly.

```sh
cd /etc/radiator
sudo cp -a -i radiator.conf radiator.conf.dist
sudo cp /opt/radiator/radiator/goodies/simple.cfg radiator.conf
sudo cp /opt/radiator/radiator/goodies/simple-users users
sudo systemctl restart radiator
/opt/radiator/radiator/radpwtst -trace 4 -noacct
```

Sample files in goodies directory typically show just one topic. To add authentication logging, see _authlog.cfg_ in goodies directory and add the logging specific parts into your _radiator.conf_ file. File `README` in goodies gives a brief description of each goodies file.

Our advice is to start with a simple configuration that can be tested while you add more features to it. See [Configuring Radiator](https://files.radiatorsoftware.com/radiator/ref/Configuration.html) in Radiator reference manual for more information.

### Considering the SQL timeouts and retries {#configuration-sqltimeouts}
In general the best practices regarding the timeouts, retries and keepalive settings on the Radiator configuration are dependent of the use case. For example, if database is used for authentication and/or accounting, the `Timeout` and `FailureBackoffTime` attributes depend on for example if the database is on the same or different server than the Radiator and if the network between database and Radiator is suitably fast. The same applies to other services that the Radiator may use, like Active Directory and various logging systems.

For the database connections the main attributes for controlling the timeouts are `Timeout` <https://files.radiatorsoftware.com/radiator/ref/SQL_clauses.html#Timeout> and `FailureBackoffTime` <https://files.radiatorsoftware.com/radiator/ref/SQL_clauses.html#FailureBackoffTime>. For the SQL queries the `SQLRetries` <https://files.radiatorsoftware.com/radiator/ref/SQL_clauses.html#SQLRetries> is also important.

It is important to differentiate here the database connections and SQL queries, as it is possible that connecting to the database takes extremely long time but once it is up the SQL queries itself perform fast. However, the Timeout and FailureBackoffTime attributes listed here affect both of the cases. For the database connection the Timeout defines how long time the connection is tried to accomplish, while the FailureBackoffTime defines how long the Radiator waits until trying the connection again.

For the SQL queries, the Timeout defines how long time the query is tried, SQLRetries define if the query is retried and FailureBackoffTime for how long Radiator waits until trying to connect to the SQL server again if there was an error. The default Timeout is 60 seconds, which usually is quite long time to wait before for example authentication reply is sent back to the client. The default SQLRetries is 2. When considering the proper Timeout it is important to also include the SQLRetries. For example: Timeout 10 and SQLRetries 2 means 30 seconds before Radiator considers the SQL server as not available and the FailureBackoffTime will kick in. In practice, the SQLRetries default value is usually OK as having a retry helps in the cases when there is a firewall which breaks the connectivity to the SQL server at some intervals. The Timeout value usually should be shortened from the default to a reasonable number for the environment in question.

For the FailureBackoffTime the default value is 10 minutes, which is a very long time to wait for the SQL server to be back online. In general, the reasonable value for FailureBackoffTime depends also on the system setup. Is there a secondary SQL server that can be used, are the timeouts toward SQL server result of short hiccups on the network side or is the SQL server under too heavy load and unable to perform, all of these affect how long it is reasonable to wait until trying the SQL server again.

With the NAS devices, all of the above must be also taken into account, so the NAS device has long enough timeout to wait the Radiator response while Radiator waits to connecting to the database and then the database query response. If the Radiator has FailureBackoffTime in effect from all the SQL servers configured on the Radiator configuration for authentication, and there is no fallback configuration on the Radiator that would send REJECT, then no answer is sent to the NAS allowing the NAS to trigger whatever failover configuration it has.

### WiFi offloading and test requirements with EAP-AKA {#configuration-wifioffload}
When testing for example WiFi offload with EAP-AKA, Radiator add-on modules are required as well as Diameter peering information for Radiator <--> HSS/DRA connection. In practise this requires first installing needed software:
- Radiator and Radiator Radius::UtilXS <https://files.radiatorsoftware.com/radiator/ref/Installation.html#Installation>
- Radiator Service Provider Module <https://files.radiatorsoftware.com/carrier/ref/Installing.html#Installing>
- Radiator SIM Module <https://files.radiatorsoftware.com/eap-sim/ref/InstallingSIMPack.html#InstallingSIMPack>

After the software has been installed, next steps are creating the Radiator configuration and acquiring for example test SIM cards. Check out <https://files.radiatorsoftware.com/eap-sim/ref/InstallingSIMPack.html#TestingPrerequisites> for more detailed list of the test setup needs.


## Deployment {#deployment}

### Does Radiator offer repositories? {#radiator-repositories}

Radiator repositories are available for various Unix/Linux distributions like RedHat, Ubuntu and Debian. See more from our blog <https://blog.radiatorsoftware.com/2020/03/introducing-new-radiator-repository.html>

### How do I deploy Radiator? {#deploying-radiator}

Radiator can be deployed in multiple ways. We offer both repositories as well as ready made packages for various platforms. For other systems we have the tar.gz package available.

The ready made packages for Unix/Linux environments can be used with the Radiator Software Ansible playbooks for automating not only the deployment but also the set up and management. More information on our Ansible playbooks can be found from our blog: <https://blog.radiatorsoftware.com/2020/10/radiator-software-ansible-playbooks-for.html>

Both repositories and ready made packages can also be used when deploying Radiator on Docker containers. Check out more details from our blog: <https://blog.radiatorsoftware.com/2020/10/radiator-dockerfiles-now-available.html>

For manual Radiator package deployment, see our installation instructions from <https://radiatorsoftware.com/products/radiator/installation/>


## Management {#management}

### How do I manage Radiator instances on multiple hosts? {#instances-multiple-hosts}

Radiator instances on multiple hosts can be managed with Ansible playbooks available in Radiator distribution packages from Radiator 4.25. The Radiator Software Ansible playbooks offer a more automated way to manage Radiator installation, set up, and instance management and they can be either used as is or tailored when needed. See more from our blog: <https://blog.radiatorsoftware.com/2020/10/radiator-software-ansible-playbooks-for.html>

### How do I manage Radiator instances on a single host? {#instances-single-host}

Multiple Radiator instances on a single host can be managed either with Ansible playbooks available in Radiator distribution packages from Radiator 4.25 or with systemd.

The Radiator Software Ansible playbooks offer a more automated way to manage Radiator installation, set up, and instance management and they can be either used as is or tailored when needed. See more from our blog: <https://blog.radiatorsoftware.com/2020/10/radiator-software-ansible-playbooks-for.html>

In addition to managing Radiator instances with Ansible, the Radiator instances running on the same host can be managed manually with systemd. We also offer a systemd service file which allows grouping the Radiator instances. Once grouped, all Radiator instances on the host can be controlled with a single systemctl command. Check out instructions for set up and usage from our blog: <https://blog.radiatorsoftware.com/2019/06/grouping-and-controlling-multiple.html>

### Can I use Ansible? {#ansible-management}

Starting from Radiator 4.25 we have included Radiator Software Ansible playbooks with the distribution for installation, set up, and instance management. These playbooks can be used as is or then as a starting point and tailored for specific needs. See more from our blog: <https://blog.radiatorsoftware.com/2020/10/radiator-software-ansible-playbooks-for.html>

### How is RADIUS high-availability achieved? {#radius-ha}

HA is based on running multiple parallel RADIUS servers (only active-active model is used). The selection of an active RADIUS server or load-balancing of the requests between RADIUS servers is commonly decided by the RADIUS clients. The authentication backend (e.g. LDAP, SQL) redundancy and high availability is provided by the backend and backend drivers, not the RADIUS server.

### How to implement HA and redundancy in Radiator? {#radius-ha-implementation}

High-availability is a combined result of proper:

- RADIUS client configuration
- RADIUS server configuration
- backend driver configuration
- backend design and configuration
- geographical and network positioning of RADIUS and backend servers
- network connectivity
- testing

Without considering all of these together, the RADIUS infrastructure high-availability and redundancy cannot be ensured.


## Monitoring {#monitoring}

### How SNMP is supported in Radiator? {#monitoring-snmp}

Radiator includes SNMP agent support. The agent supports SNMP versions 1 and 2c and all the SNMP objects described in the following RFCs:

- RFC [2619](https://datatracker.ietf.org/doc/html/rfc2619) - RADIUS Authentication Server MIB
- RFC [2621](https://datatracker.ietf.org/doc/html/rfc2621) - RADIUS Accounting Server MIB
- RFC [4669](https://datatracker.ietf.org/doc/html/rfc4669) - RADIUS Authentication Server MIB for IPv6
- RFC [4671](https://datatracker.ietf.org/doc/html/rfc4671) - RADIUS Accounting Server MIB for IPv6

### How can I monitor Radiator? {#monitoring-how}

Radiator monitoring can be done with the information available in various log files. The recommended approach is to log the information in suitable format, for example JSON and then visualise the information with a 3rd party tool like Splunk or Elasticsearch. See more from our blog: [Make your Radiator log data searchable, part 1](https://blog.radiatorsoftware.com/2016/06/make-your-radiator-log-data-searchable.html) and [part 2](https://blog.radiatorsoftware.com/2016/09/make-your-radiator-log-data-searchable.html).

### Is there a dashboard? {#monitoring-dashboard}

Radiator is a command line application and does not contain a dashboard itself. Due to the many options Radiator has for logging and statistics collection, creating a suitable dashboard with e.g. Splunk is possible.

### How do I integrate external monitoring solutions with Radiator? {#monitoring-external}

Simple way to integrate for example Splunk with Radiator is to log statistics information from Radiator to a JSON file with `<StatsLog FILE>`, and then use for example Splunk Universal Forwarder or a custom script to forward the needed statistics to Splunk. Similarly it is possible to integrate for example Kibana with Radiator. See more from our blog: <https://blog.radiatorsoftware.com/2016/09/make-your-radiator-log-data-searchable.html>


## Logging {#logging}

### What logging formats Radiator supports? {#logging-formats}

Radiator has a default logging format, which can be configured either with Radiator configuration parameter `LogFormat` or with a Perl hook called `LogFormatHook`. In addition, Radiator supports JSON and CEF log formats by default. Radiator goodies directory has an example on how to configure different log formats in file _logformat.cfg_

### Where does Radiator logging go? {#logging-options}

Radiator has several options for logging. Logs can go to a flat file on Radiator server, to a SQL database, to syslog logging facility or in case of Microsoft Windows logs can go to Microsoft Windows Event Log. Statistics can also be logged to REDIS.
Although Radiator can log directly to remote syslog facility/facilities, it can have performance impact on Radiator. So from performance point it is better to log to SYSLOG on the local Radiator host and then have SYSLOG itself forward logs to remote syslog facilities.

### How do I configure Radiator logs? {#logging-configure}

Each Radiator log can be configured with Radiator configuration. Radiator can log authentication, accounting and general Radiator related information. Radiator configuration can have several different logging clauses defined at the same time. For example it is possible to log authentication to both file (`<AuthLog FILE>`) and SQL (`<AuthLog SQL>`) while at the same time logging accounting to file (`<AcctLog FILE>`), SQL (`<AcctLog SQL>`) and SYSLOG (`<AcctLog SYSLOG>`). All the same options apply also to Radiator general logs with clauses like `<Log FILE>` and `<Log SYSLOG>` and for statistics with clauses like `<StatsLog FILE>` and `<StatsLog REDIS>`.
Radiator goodies directory has an example on how to configure several different logs in file _logformat.cfg_

Default configuration for log rorate is automatically configured by Radiator during installation. It is available in _/etc/logrotate.d/radiator_ and can be edited when needed.


## Licensing {#licensing}

### How Radiator licensing works? {#how-radiator-licensing-works}

Radiator licensing is based on the number of servers used by the customer organisation. Radiator is available in different licence sizes starting from single server **Radiator Single Pack** and up to unlimited server count **Radiator Enterprise Pack**.

Radiator can be extended with **Radiator Service Provider Pack**, **Radiator SIM Pack**, **Radiator Telco Pack** and **Radiator GBA/BSF Pack**. Licensing for these add-on *Diameter modules* is based on the number of subscribers or alternatively concurrent sessions depending on the use case. 

Other flexible licensing options are also available. Please contact Radiator sales if you’re interested in **service provider** licensing, **VNF** licensing, **white-label OEM** licensing or other models.

### Is there a demo version of Radiator? {#demo-version-of-radiator}

Radiator is available as an *evaluation version*. You can request a free *30 day evaluation licence* by filling out our evaluation form: <https://radiatorsoftware.com/evaluation/>

### What is the difference between the fully licensed and demo versions? {#difference-between-fully-licensed-and-demo-versions}

Evaluation software has the *full functionality of Radiator*. The difference is that evaluation software is time limited and requires a licence key to activate, and the source code is obscured.


## Support {#support}

### How can I contact Radiator support? {#contact-support}

If you have a support contract, you may send email to radius-support (at) open.com.au. Include your support contract identifier in the Subject line. This email address is reserved for support contract holders only. For the detailed information about contacting support, please see <https://radiatorsoftware.com/support/>

### What support options are available? {#support-options}

Radiator license package may include email support and telephone support. It's also possible to purchase additional support packages, including consulting, training and custom coding. For more information about paid support, please see <https://radiatorsoftware.com/support/>

Latest Radiator reference manual and other information is available at <https://radiatorsoftware.com/products/radiator/>

### How to submit feature requests? {#feature-request}

We are interested in your feedback, both positive and negative, and bug reports. Please send them to `info (at) radiatorsoftware.com`.

### How do I submit bug reports? {#bug-report}

We are interested in your feedback, both positive and negative, and bug reports. Please send them to `info (at) radiatorsoftware.com`. Radiator download access holders are entitled to free upgrades, and we do fix bugs that are reported to us, so if you report a bug, you can expect to get an upgrade with a fix one day.

## Troubleshooting {#troubleshooting}

### How to enable debug logging? {#enable-debug}

To enable the DEBUG level log of Radiator, do the following:

1. From the Radiator configuration file, locate the row starting with `Trace` and change the row to contain `Trace 4`. See more about the log levels: <https://files.radiatorsoftware.com/radiator/ref/GlobalParameters.html#Trace>
2. If the Radiator configuration does not already contain `LogTraceId` and `LogMicroseconds` add those to the configuration also. These are good values to have in the Radiator configuration even when logging level is lower than DEBUG. Good place to add them is right after the `Trace` row. See more from: <https://files.radiatorsoftware.com/radiator/ref/GlobalParameters.html#LogTraceId_common> and <https://files.radiatorsoftware.com/radiator/ref/GlobalParameters.html#LogMicroseconds>.
3. Restart Radiator so the configuration changes are taken into use. Use `sudo systemctl restart radiator` on Linux environments or restart Radiator service from Services on Windows environments.

### Where can I find Radiator configuration files? {#configuration-location}

Current Radiator installations have their configuration by default in

- **Linux**: File `radiator.conf` in directory `/etc/radiator/`
- **Windows**: File `radiator.conf` in directory `C:\Program Files\Radiator\`

If your configuration uses `Include` directives, check the main configuration files what files are included (possibly recursively) in the configuration. If you have an older or heavily modified configuration, you may need to find the files (files may have an `.cfg` extension) and directory locations separately. Also, if Radiator is set up to run as systemd instances, the config files for each instance is separated by name, for example instances auth1 and acct1 will have configuration files `radiator-auth1.conf` and `radiator-acct1.conf` accordingly.

### Where can I find Radiator log files {#logfile-location}

Current Radiator installations have log files by default in

- **Linux**: File `radiator.log` in directory `/var/log/radiator`
- **Windows**: File `radiator.log` in directory `C:\Program Files\Radiator\`

In addition to Radiator process log, there can be multiple other logs depending on your configuration, for example logs for authentication and accounting events. In addition to files, logging can also be sent for example to systemd's journald, syslog mechanism, saved to an external database or fed to a separate log analysing platform (Splunk, etc.).

To find all possible logs, you should check how your Radiator installation is configured. [See above answer](#logfile-location) if you need help finding config files. For file-based logging, configuration parameter `LogDir` defines the default directory for logging, and several different parameters define log files, for example `LogFile` and `AcctLogFileName` (full list is in Radiator [Reference manual](https://files.radiatorsoftware.com/radiator/ref/)). Also, it's good to notice that `LogFile` without a filename disables logging.

Different logs, if used in configuration, can be found by searching for blocks `<Log FILE>`, `<Log SYSLOG>`, `<Log SQL>`.

Log files normally get rotated to avoid filling up storage. Rotation settings are stored in file `/etc/logrotate.d/radiator`. If syslog or some other log shipping agent is used, check their configuration to see where logging 

### Problems with Oracle database connection? {#oracle-connection-problem}

Radiator log shows error `ERR: Radius::AuthSQL Apollo: SQL connection to 'dbi:Oracle:dbname' failed: timeout` when trying to use Oracle database.

As the connection is failing with timeout, there are several possibilities where the problem is coming from. The problem can be troubleshooted with following steps:

1. It's possible there is some firewall/routing issue between Radiator and the database. Check with telnet if it is possible to connect to the database IP and port: `telnet <IP> <port>`. The database IP can be usually found from the tnsnames.ora file <https://www.orafaq.com/wiki/Tnsnames.ora>
2. Database can be slow to respond. Check if there are any problems or errors visible in the DB logs.
3. Check if something has changed recently that could cause the issue, for example routing, firewalls, DB server/client updates.
4. Check if there are any other Radiators that are located on the same subnet and can connect to the same DB. If yes, that would indicate the problem is not in the routing or firewalls.
5. Test with sqlplus <https://www.orafaq.com/wiki/SQL*Plus> if there are any errors when trying to connect from the Radiator server to the DB with sqlplus.
6. It is possible to see the traffic between Radiator and the DB with tcpdump and Wireshark. For example:<br>
`% sudo tcpdump -w oracle.pcap host 172.31.23.114 and tcp port 1525`<br>
Stop Radiator, start tcpdump in another window and start Radiator, then generate/wait for traffic that tries to use the DB and stop tcpdump. The pcap file should show what, if anything, is exchanged between Radiator and Oracle. If there is no traffic shown on tcpdump it could be that there is a problem with DNS: <https://stackoverflow.com/questions/2364588/very-long-sql-connection-opening-time>


## Security {#security}

### Can I audit Radiator AAA Server source code? {#code-audit}

We provide full source code for licensees so code can be audited, and it's easy to track any changes between versions.

### How do I submit security issues / questions? {#security-issues}

All security related issues concerning Radiator Software products or services should be reported to the following email address: `security (at) radiatorsoftware.com`

You can find more information on page <https://radiatorsoftware.com/security-contacts/>

### How can I validate the software downloads? {#validate-downloads}

All Radiator Software software packages are signed with a Radiator Software key. You can download the key from <https://radiatorsoftware.com/product-signing-keys/>
and use it to verify the authenticity of the downloaded packages. When using Radiator Software supplied repositories, this verification is done automatically upon install or upgrade.
There are also SHA256 checksums available for each file to help check that the file was downloaded successfully.

<script>
// let toc=document.getElementById("markdown-toc")
// let toc_cont=document.getElementById("toc-cont")
// toc.parentNode.removeChild(toc);
// toc_cont.appendChild(toc);
</script>
