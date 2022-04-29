---
layout: home
title: Frequently Asked Questions
---

Updated: {{ site.time | date: "%-d-%m-%Y" }}
{% comment %}
short with frontmatter "date: 2021-12-23" {{ page.date | date: "%-d-%m-%Y" }}
long with build time {{ site.time | date_to_long_string }}
{% endcomment %}

- TOC
{:toc}


## General questions

### [What is the best RADIUS server?](#what-is-the-best-radius-server)

From our point of view, Radiator AAA Server is the best choice for **RADIUS**, **Diameter** and other **AAA** server needs. Because of the flexibility of Radiator, our customers call it the *Swiss Army knife of RADIUS servers*. More info on Radiator can be found from Radiator product site [https://radiatorsoftware.com/products/radiator/]()

### [Is Radiator open source?](#is-radiator-open-source)

Radiator is not open source, but when you purchase Radiator, full source code is always supplied.

### [How much does Radiator cost?](#how-much-does-radiator-cost)

You can see selected Radiator licence prices at [https://radiatorsoftware.com/pricelist/](). Pricing for the Radiator add-on modules is provided upon request by contacting Radiator sales.

### [Who is using Radiator](#who-is-using-radiator)

Radiator AAA server is used for user and network authentication by a huge range of different organisations: educational institutions, cities, governmental organisations, ISPs and telecom companies, managed service providers, utility companies, and private businesses in various fields such as hospitality, finance, defence and medical industries.

### [References](#references)

Radiator has a large and active worldwide customer base. Please see our website for customer references: [https://radiatorsoftware.com/customers/]()


### [Is there an online demo?](#is-there-an-online-demo)

There is a Radiator Demo Cloud online demo - you can book a timeslot to go through typical Radiator use cases (or possibly your own use case) with Radiator experts.

### [Where is the Radiator team based?](#where-is-the-radiator-team-based)

The Radiator team is based in Finland, where development and sales are done. At the same time, we also have a worldwide partner network providing support and consultation.

### [Who is behind Radiator?](#who-is-behind-radiator)

Radiator was developed by Australian-based *Open System Consultants (OSC)* 1998-2013, until the Finnish team acquired OSC in 2013 and took over Radiator development and business. The resulting company is Radiator Software.

### [Who is the manufacturer for Radiator?](#who-is-the-manufacturer-for-radiator)

*Radiator Software Oy* is the sole manufacturer of Radiator AAA Server software. *Radiator Software* sells Radiator licences globally and you can buy a licence directly from the Radiator team. Radiator licences are also sold through various distribution partners all over the world.


## Licencing

### [How Radiator licencing works?](#how-radiator-licencing-works)

Radiator licencing is based on the number of servers used by the customer organisation. Radiator is available in different licence sizes starting from single server **Radiator Single Pack* and up to unlimited server count **Radiator Enterprise Pack**.

Radiator can be extended with **Radiator Carrier Pack**, **Radiator SIM Pack**, **Radiator Telco Pack** and **Radiator GBA/BSF Pack**. Licencing for these add-on *Diameter modules* is based on the number of subscribers or alternatively concurrent sessions depending on the use case. 

Other flexible licencing options are also available. Please contact Radiator sales if you’re interested in **service provider** licencing, **VNF** licencing, **white-label OEM** licencing or other models.

### [Is there a demo version of Radiator?](#is-there-a-demo-version-of-radiator)

Radiator is available as an *evaluation version*. You can request a free *30 day evaluation licence* by filling out our evaluation form: [https://radiatorsoftware.com/evaluation/]().

### [What is the difference between the fully licensed and demo versions?](#what-is-the-difference-between-the-fully-licensed-and-demo-versions)

Evaluation software has the *full functionality of Radiator*. The difference is that evaluation software is time limited and requires a licence key to activate, and the source code is obscured.

## Features

### [Which RFCs, protocols and authentication methods are supported by Radiator?](#which-rfcs-protocols-and-authentication-methods-are-supported-by-radiator)

Full list can be seen from our technical documentation, but short listing is here:

- Complies with RFCs 2548, 2619, 2621, 2865, 2866, 2867, 2868, 2869, 3579, 4669, 4671, 5176, 5997
- Dictionary or other applicable support for RFCs 4372, 4849, 4675, 4849, 5080, 5447, 5580, 5607, 5904, 6158, 6929, 6519, 6572, 6677, 7055, 7268, 8044
- Supports RFC 6614, also known as RadSec – secure, reliable RADIUS proxying
- Acts as a Diameter to RADIUS gateway for NAS authentication and accounting. Supports Diameter RFCs 3588, 6733, 4072, 4005, 7155.
- Acts as a RADIUS to Diameter gateway for NAS authentication and accounting.
- Supports EAP in accordance with RFC 3748
- Supports EAP-MD-Challenge, EAP-OTP and EAP-GTC, RFC 3748
- Supports EAP TLS, RFC 5216
- Supports EAP TTLS, RFC 5281
- Supports PEAP, IETF drafts and MS-PEAP
- Supports EAP-MSCHAP-V2
- Supports Cisco LEAP
- Supports EAP-FAST, RFC 4851
- Supports EAP-pwd, RFC 5931
- Supports EAP-PSK, RFC 4764
- Supports EAP-PAX, RFC 4746
- EAP-SIM, EAP-AKA, EAP-AKA’, 3GPP AAA Server and other related features are available through Radiator SIM Pack
- Acts as authentication server for IEEE 802.1X with support for IEEE 802.1AE, also known as MACsec
- Supports HOTP, RFC 4226
- Supports TOTP, RFC 6238, sometimes referred as Google Authenticator
- RADIUS SIP Digest authentication per draft-sterman-aaa-sip-00.txt and RFC 5090
- Diameter 3GPP EIR and other carrier features are available through Radiator Carrier Pack
- Diameter 3GPP GBA/BSF support for VoLTE Supplementary Services and other related features are available through Radiator GBA/BSF Pack
- Diameter 3GPP PCRF, PCEF, OCS, and other Diameter and RADIUS related policy and charging features are available through Radiator Telco Pack
- Complies with 3GPP2 P.S0001-A Wireless IP Network Standard up to version 3GPP X.S0011

### [What platforms are supported by Radiator?](#what-platforms-are-supported-by-radiator)

Radiator supports all **the most used operating systems** (Unix, Linux, Windows and Mac OS). For a complete list for different operating systems and for example Linux distributions, please see [https://radiatorsoftware.com/supported-platforms/]().
