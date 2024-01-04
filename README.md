<!-- 
#################################################################################
Tractus-X - Eco Pass KIT

Copyright (c) 2022, 2024 Contributors to the Eclipse Foundation

See the NOTICE file(s) distributed with this work for additional
Information regarding copyright ownership.

This program and the accompanying materials are made available under the
terms of the Apache License, Version 2.0 which is available at

https://www.apache.org/licenses/LICENSE-2.0.

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND,
either express or implied. See the
License for the specific language govern in permissions and limitations
under the License.

SPDX-License-Identifier: Apache-2.0
################################################################################## 
-->

![Eco Pass Kit Pictotogram](/docs/resources/img/EcoPassKIT_pictogram.png)

<h1 style="display:flex; align-items: center;">&nbsp;&nbsp;Eco Pass KIT</h1>

[![Contributors][contributors-shield]][contributors-url]
[![Stargazers][stars-shield]][stars-url]
[![Apache 2.0 License][license-shield]][license-url]
[![Latest Release][release-shield]][release-url]

This is the repository of the EcoPass Kit. In this repository we collect all the information needed to use the this KIT.

The EcoPass KIT will be the key enabler for various stakeholders to use digital product passports, which represent a digital collection of specific information about a physical product in a standardized exchange format. This data is governed by agreed-upon ownership and access rights, which are conveyed through the Eclipse Data Space Connector (EDC). The primary purpose of the product pass is to enable the electronic registration, processing and sharing of product-related details among various entities in the supply chain, including several businesses and authorities. The demand for interoperable product passports exists worldwide, driven by the need to establish sustainable and transparent supply chains across different types of products, for which the adoption of standards will become crucial. In this context, Catena-X offers a decentralized ecosystem supported by standards and principles like data sovereignty, which can effectively implement such a product passport system. The objective of the EcoPass KIT is therefore to:

Provide a comprehensive overview of the business context and benefits of product passports.
Offer guidelines for industry stakeholders.
Provide a detailed description and offer tools to implement product passports.

## Reference Implementation

We have an reference implementation which is the Digital Product Pass.
You can find the repository [here](https://github.com/eclipse-tractusx/digital-product-pass)

### Documentation

To get started you can have a look into our documentation:

| Name                                                                      | Description                                                                                                                                                 |
| ----------------------------------------------------------------          |-------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [Arc42](https://github.com/eclipse-tractusx/digital-product-pass/blob/main/docs/arc42/Arc42.md)                                             | Main Architecture Document (Arc42) of the Digital Product Pass Application                                                                                      |
| [Administration Guide](https://github.com/eclipse-tractusx/digital-product-pass/blob/main/docs/admin%20guide/Admin_Guide.md)                  | Administration Guide explaining the infrastructure and how to configure the application                                                                     |
| [Data Retrieval Guide](https://github.com/eclipse-tractusx/digital-product-pass/blob/main/docs/data%20retrieval%20guide/DataRetrievalGuide.md)          | Backend documentation of the Digital Product Passport App                                                                                                                  |
| [Adoption View](/docs/page-adoption-view.md)                     | Technical Guide - Deployment in ArgoCD Hotel Budapest (integration environment)                                                                             |
| [Development View](/docs/page-software-development-view.md)                                      | Overview on general docker commands                                                                                                                         |
| [Operation View](/docs/page-software-operation-view.md)                     | This guide describes how to setup a keycloak instance in local docker container and import existing realm.json file.                                        |                                                                                                       |



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[contributors-shield]: https://img.shields.io/github/contributors/eclipse-tractusx/eco-pass-kit.svg?style=for-the-badge

[contributors-url]: https://github.com/eclipse-tractusx/eco-pass-kit/graphs/contributors

[stars-shield]: https://img.shields.io/github/stars/eclipse-tractusx/eco-pass-kit.svg?style=for-the-badge

[stars-url]: https://github.com/eclipse-tractusx/eco-pass-kit/stargazers

[license-shield]: https://img.shields.io/github/license/eclipse-tractusx/eco-pass-kit.svg?style=for-the-badge

[license-url]: https://github.com/eclipse-tractusx/eco-pass-kit/blob/main/LICENSE

[release-shield]: https://img.shields.io/github/v/release/eclipse-tractusx/eco-pass-kit.svg?style=for-the-badge

[release-url]: https://github.com/eclipse-tractusx/eco-pass-kit/releases
