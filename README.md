# Awesome-Soap-Web-Services-API

# Top SOAP Web Services API Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on SOAP Protocol Implementation, WSDL Tooling & Self-Hosted Web Service Frameworks*  
**Last updated: October 2026**

This repository tracks notable **commercial SOAP API platforms** and **open-source projects** that implement the SOAP protocol, generate WSDL-based clients and servers, and enable integration with legacy enterprise systems — from financial messaging and logistics to telecom and ERP.

**Examples** include Salesforce SOAP API, PayPal SOAP API, eBay SOAP API, FedEx Web Services, UPS Developer Kit, Sabre Web Services, Amadeus SOAP API, Workday SOAP API, NetSuite SuiteTalk, and SAP NetWeaver SOAP (the category leaders).

**Open-source emphasis**: SOAP web services remain critical for enterprise integration despite the rise of REST. **Apache CXF** leads as the most comprehensive open-source services framework with full WS-* support including WS-Security, WS-Addressing, and WS-ReliableMessaging . **Spring Web Services** delivers contract-first SOAP development with Spring ecosystem integration . **Zeep** provides a fast, modern Python SOAP client with WSDL introspection . **gSOAP** delivers C/C++ XML data bindings for high-performance SOAP services . **Apache Axis2** provides a modular SOAP engine with hot deployment and REST support . **node-soap** brings SOAP client and server capabilities to Node.js . This section is heavily expanded.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Salesforce SOAP API](https://developer.salesforce.com/docs/atlas.en-us.api.meta/api/sforce_api_quickstart_intro.htm)**  
  **Salesforce's SOAP-based API** — enterprise integration with full metadata access, bulk operations, and WSDL-based client generation. **Best for Salesforce integrations requiring SOAP**.

- **[PayPal SOAP API](https://developer.paypal.com/)**  
  **PayPal's legacy SOAP API** — payment processing, recurring billing, and transaction management. **Best for legacy PayPal integrations**.

- **[FedEx Web Services](https://developer.fedex.com/)**  
  **FedEx's SOAP-based shipping API** — rate quotes, shipping labels, tracking, and pickup scheduling. **Best for logistics integration with FedEx**.

- **[UPS Developer Kit](https://developer.ups.com/)**  
  **UPS's SOAP API** — shipping, rating, tracking, and address validation. **Best for logistics integration with UPS**.

- **[Sabre Web Services](https://developer.sabre.com/)**  
  **Sabre's SOAP APIs** — travel booking, flight availability, and reservation management. **Best for travel industry integration**.

- **[Amadeus SOAP API](https://developers.amadeus.com/)**  
  **Amadeus's SOAP APIs** — flight search, booking, and travel management. **Best for travel industry integration**.

- **[Workday SOAP API](https://community.workday.com/)**  
  **Workday's SOAP-based web services** — HR, payroll, and financial data integration. **Best for Workday integrations**.

- **[NetSuite SuiteTalk](https://docs.oracle.com/en/cloud/saas/netsuite/ns-online-help/)**  
  **NetSuite's SOAP-based web services** — ERP data integration with full record access. **Best for NetSuite integrations**.

- **[SAP NetWeaver SOAP](https://help.sap.com/)**  
  **SAP's SOAP-based web services** — enterprise integration with SAP systems. **Best for SAP integrations**.

- **[eBay SOAP API](https://developer.ebay.com/)**  
  **eBay's legacy SOAP API** — listing management, order processing, and seller tools. **Best for legacy eBay integrations**.

## Open-Source GitHub Projects

### Java SOAP Frameworks

- **[Apache CXF](https://github.com/apache/cxf)**  
  **The most comprehensive open-source services framework**, Apache-2.0 licensed with **active development** (4.1.1 released March 2025) . **Supports SOAP, REST, XML/HTTP, and CORBA** with pluggable transports (HTTP, JMS, JBI) . **Full WS-* standards support**: WS-I Basic Profile, WSDL, WS-Addressing, WS-Policy, WS-ReliableMessaging, WS-Security, WS-SecurityPolicy, WS-SecureConversation, and WS-Trust . **JAX-WS and JAX-RS frontends** with code-first and contract-first development . **Spring XML configuration** and Maven plugin integration . **The de facto enterprise SOAP framework** — used by thousands of organizations . **Best for enterprise SOAP and WS-* services**.

- **[Spring Web Services](https://github.com/spring-projects/spring-ws)**  
  **Contract-first SOAP service development**, Apache-2.0 licensed . **Document-driven web services** with WS-I Basic Profile compliance . **Powerful mappings** — distribute requests by payload, SOAP Action header, or XPath expression . **Supports JAXB, Castor, XMLBeans, JiBX, and XStream** for marshalling . **WS-Security integration with Spring Security** — sign, encrypt, and authenticate SOAP messages . **Reuses Spring expertise** — Spring application contexts for all configuration . **Best for Spring-based SOAP services**.

- **[Apache Axis2](https://github.com/apache/axis2-java)**  
  **The successor to Apache Axis SOAP stack**, Apache-2.0 licensed . **SOAP 1.1 and 1.2 support** with integrated REST/POX support . **Hot deployment** — add services without server shutdown . **AXIOM object model** for high-performance XML processing . **Asynchronous web services** with non-blocking clients and transports . **WSDL 1.1 and 2.0 support** for stub generation . **Best for high-performance SOAP engines**.

### Python SOAP Clients

- **[Zeep](https://github.com/mvantellingen/python-zeep)**  
  **Fast and modern Python SOAP client**, MIT licensed . **WSDL introspection** — inspects WSDL documents and generates code for services and types . **SOAP 1.1 and 1.2 support** with HTTP bindings . **WS-Addressing, WSSE (UsernameToken/x.509 signing), and asyncio via httpx** . **Built on lxml and requests** for performance . **Python 3.7-3.11 and PyPy compatible** . **Best for Python SOAP integrations**.

### C/C++ SOAP Toolkits

- **[gSOAP](https://github.com/Genivia/gsoap)**  
  **The most comprehensive C/C++ SOAP toolkit**, commercial with open-source availability . **XML to C/C++ language binding** for SOAP/XML web services . **wsdl2h and soapcpp2 tools** for WSDL/XSD translation and code generation . **High-performance, portable, and platform-independent** generated code . **Active development** with regular releases (2.8.135 as of September 2025) . **Best for high-performance C/C++ SOAP services**.

- **[Apache Axis2/C](https://github.com/apache/axis2-c)**  
  **C implementation of Axis2 architecture**, Apache-2.0 licensed . **SOAP 1.1 and 1.2 support** with REST/POX support . **MTOM/XOP support** for binary attachments . **Portable and embeddable** for legacy system integration . **WS-Addressing, WS-Policy, and WS-SecurityPolicy** built in . **Best for embedded and legacy C SOAP services**.

### JavaScript/Node.js SOAP

- **[node-soap](https://github.com/vpulim/node-soap)**  
  **SOAP client and server for Node.js**, MIT licensed with **2,963 GitHub stars** . **WSDL-based client and server generation** . **Active maintenance** with regular updates . **Best for Node.js SOAP integrations**.

### Go SOAP SDKs

- **[soap-go](https://github.com/way-platform/soap-go)**  
  **Go SDK and CLI tool for SOAP web services**, MIT licensed . **SOAP 1.1, WSDL 1.1, and XSD 1.0 support** . **Code generation from WSDL files** with CLI tool for gen, doc, and call operations . **SOAP envelope primitives** with header and body manipulation . **Best for Go SOAP integrations**.

### Rust SOAP Clients

- **[rsoap](https://github.com/ouertani/rsoap)**  
  **Rust SOAP client with compile-time WSDL code generation**, MIT licensed . **Typed request/response structs** generated from WSDL at compile time . **SOAP 1.1 and 1.2 support** with auto-detection from WSDL binding . **WS-Security transport binding (mTLS)** via optional Cargo feature . **Fault detection on any HTTP status** . **Best for Rust SOAP integrations**.

### PHP SOAP Extensions

- **[BeSimpleSoap](https://github.com/natlibfi/besimple-soap)**  
  **PHP SOAP client and server extensions**, open-source . **Extends native PHP SoapClient and SoapServer** with SwA, MTOM, and WS-Security . **WS-Addressing support** . **Components**: SoapClient, SoapServer, SoapCommon, SoapWsdl . **Best for PHP SOAP services**.

### Scala SOAP

- **[Play SOAP](https://github.com/playframework/play-soap)**  
  **SOAP support for Play Framework**, Apache-2.0 licensed with **35 GitHub stars** . **Scala-based SOAP client and server** . **Active development** (last pushed June 2025) . **Best for Scala/Play Framework SOAP services**.

### Additional Strong Open-Source Options

- **Apache Rampart/C** — WS-Security implementation for Axis2/C .
- **Apache Sandesha2/C** — WS-ReliableMessaging for Axis2/C .
- **Apache Savan/C** — WS-Eventing for Axis2/C .
- **Python Zeep examples** — WSDL inspection and typed client generation .
- **gSOAP wsdl2h** — WSDL/XSD to C/C++ translator .
- **gSOAP soapcpp2** — Code generator for services and XML data bindings .

**Frameworks for building custom SOAP web services**: Combine **Apache CXF** for enterprise-grade WS-* support with JAX-WS and JAX-RS frontends . Use **Spring Web Services** for contract-first SOAP development with Spring Security integration . Deploy **Zeep** for Python SOAP client development with WSDL introspection . Choose **gSOAP** for high-performance C/C++ SOAP services . Integrate **node-soap** for Node.js SOAP client and server implementations . Use **soap-go** for Go-based SOAP integrations . Choose **rsoap** for Rust SOAP clients with compile-time type safety . Note that true enterprise SOAP APIs with managed infrastructure, carrier-grade reliability, and vendor-supported SLAs (Salesforce SOAP API, FedEx Web Services, SAP NetWeaver) remain primarily commercial territory; open-source stacks provide strong SOAP protocol implementations, WSDL tooling, and WS-* standards support that require integration for complete SOAP web services.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- SOAP web services handle sensitive enterprise data and may involve WS-Security obligations. Self-hosted implementations require proper security hardening, XML security configuration (XXE prevention, XML bomb protection), and compliance with enterprise security policies.
- **SOAP remains critical for enterprise integration** — financial messaging (ISO 20022), logistics (FedEx/UPS), and ERP (SAP/NetSuite) still rely heavily on SOAP .
- **License considerations**: Apache CXF uses Apache-2.0 , Spring Web Services uses Apache-2.0 , Zeep uses MIT , gSOAP is commercial with open-source availability , and node-soap uses MIT . Verify licensing against your use case before committing.
- **Security is paramount** — WS-Security, XML encryption, and XML signature are essential for production SOAP services. Never expose SOAP endpoints without proper authentication and encryption .
- The open-source ecosystem provides strong SOAP protocol implementations, WSDL tooling, and WS-* standards support, but **managed infrastructure, carrier-grade reliability, and vendor-supported SLAs** remain primarily commercial offerings.

---

**Made for integration engineers, enterprise architects, and organizations seeking SOAP web services sovereignty.**  
Let's make SOAP web services more open, transparent, and interoperable.
