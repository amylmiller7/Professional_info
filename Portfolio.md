# Portfolio

* [Independent projects](#independent-projects)
* [Software documentation](#software-documentation)
  * [AWS](#aws)
  * [Interactive Intelligence/Genesys](#interactive-intelligencegenesys)
* [Hardware documentation](#hardware-documentation)

## Independent projects

Independent projects in my GitHub repositories include technical documentation.

* [API](https://github.com/amylmiller7/API): Contains an independent project ([IWOAMovieAPI](https://github.com/amylmiller7/API/tree/master/IWOAMovieAPI)) where I designed a mock API from scratch to create comprehensive API documentation. The project includes an OpenAPI specification (YAML) defining endpoints, parameters, and responses, plus introductory documentation (Markdown) explaining how to use the API. Demonstrates technical writing skills, API design thinking, and proficiency with industry-standard documentation formats.

* [Java](https://github.com/amylmiller7/Java): Contains course-based projects where I went beyond the exercises to add complexity and functionality, demonstrating self-directed learning. Includes a [J8ET_43_Javadoc](https://github.com/amylmiller7/Java/tree/master/Java_8_Essential_Training/J8ET_43_Javadoc) project where I wrote Javadoc comments in Java source files and generated HTML documentation using IntelliJ IDEA. Demonstrates technical writing skills and comfort with developer tools and workflows.

* [JavaScript](https://github.com/amylmiller7/JavaScript): Contains course-based projects where I extended exercises to deepen my understanding of JavaScript and application of web technologies (HTML, CSS). Includes a [therapist bot project](https://github.com/amylmiller7/JavaScript/tree/master/CodingForWriters/CFW_10_therapistBot) with documentation detailing methods, parameters, and functionality. Demonstrates technical writing skills and initiative in learning programming languages and web development.

## Software documentation

### AWS

At AWS I wrote and maintained user guides (conceptual, procedural, and reference documentation), API references, CLI references, GitHub repositories, landing pages, UX content, error messages, contextual help, and code recommendations for software developers, database administrators, and other technical professionals.

I initially worked as a solo writer for Amazon CodeGuru Reviewer, a service that uses program analysis and machine learning to detect potential issues in application code. I later transitioned to a team of writers dedicated to Amazon Relational Database Service (RDS), where I focused on documentation for three database engines: two established engines (MySQL and MariaDB) and one new engine (Db2) that I architected and documented from scratch.

#### Amazon Relational Database Service (RDS)

I owned documentation for three database engines (Db2, MariaDB, and MySQL) in the Amazon RDS User Guide and the Amazon RDS API Reference, including engine-specific chapters and engine-specific content throughout both the user guide and the API reference.

**Key projects**

* **Amazon RDS for Db2**: Created private beta documentation for re:Invent 2023.  Updated and expanded content for general availability release. Continued documenting new Db2 functionality post-launch.

* **Amazon RDS Extended Support**: Led documentation effort for this multi-engine feature spanning the user guides (Amazon RDS User Guide, Amazon Aurora User Guide), the API reference, and multiple release notes. Continued expanding documentation as functionality evolved.

* **Cross-service coordination**: Regularly collaborated with writers from other AWS service teams on projects requiring coordinated releases and consistent wording, such as Db2 licenses for AWS Marketplace and the AWS License Manager integration.


**Writing samples**

> **Note**: The following PDFs are extracted from the larger user guides, so internal links in the PDFs don't work.

* [Amazon RDS for Db2 chapter in the Amazon RDS User Guide](https://github.com/amylmiller7/Professional_info/blob/master/pdfs/rds-ug-db2-chapter102825.pdf)

* [Amazon RDS for MariaDB chapter in the Amazon RDS User Guide](https://github.com/amylmiller7/Professional_info/blob/master/pdfs/rds-ug-mariadb-chapter102825.pdf)

* [Amazon RDS for MySQL chapter in the Amazon RDS User Guide](https://github.com/amylmiller7/Professional_info/blob/master/pdfs/rds-ug-mysql-chapter102825.pdf)

* [Amazon RDS Extended Support in the Amazon RDS User Guide](https://github.com/amylmiller7/Professional_info/blob/master/pdfs/rds-ug-extended-support102825.pdf)

* [Amazon RDS Extended Support in the Amazon Aurora User Guide](https://github.com/amylmiller7/Professional_info/blob/master/pdfs/aurora-ug-extended-support102825.pdf)

> **Note**: The following links point to live documentation that other writers updated after October 2025.

* [Amazon RDS User Guide](https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/Welcome.html)

* [Amazon Aurora User Guide](https://docs.aws.amazon.com/AmazonRDS/latest/AuroraUserGuide/CHAP_AuroraOverview.html)

* [Amazon RDS API Reference](https://docs.aws.amazon.com/performance-insights/latest/APIReference/Welcome.html)

#### Amazon CodeGuru Reviewer

I documented features for this code analysis service during a one-year engagement as the solo technical writer.

**Key projects**

* **Detector Library**: Created landing page and user guide content for the collection of detectors that analyze code and provide performance and security recommendations.

* **Suppress recommendations**: Documented how users configure YAML files to control which repository files CodeGuru Reviewer analyzes.

**Writing samples**

> **Note**: The following links point to live documentation that other writers updated after October 2022.

* [Amazon CodeGuru Reviewer User Guide](https://docs.aws.amazon.com/codeguru/latest/reviewer-ug/welcome.html)

* [Amazon CodeGuru Reviewer API Reference](https://docs.aws.amazon.com/codeguru/latest/reviewer-api/Welcome.html)

### Interactive Intelligence/Genesys

(Genesys acquired Interactive Intelligence in December 2016.)

As an embedded solo technical writer at Interactive Intelligence and Genesys, I worked closely with cross-functional delivery teams that practiced agile (scrum and kanban) software development. I created documentation for 14 cloud-based integrations between the Genesys Cloud platform and third-party products including Salesforce, Zendesk, Google, and Microsoft 365. I documented integration features for end-users, configuration and setup for system administrators, and customization, APIs, and SDKs for developers.

#### User guides
I architected, wrote, and maintained documentation for end-users, system administrators, and developers from scratch. The integrations included data actions, embedded clients, and SCIM.

##### Data actions integrations
These 8 data actions integrations act on data with AWS Lambda functions, the Genesys Cloud Platform API, and third-party systems (Adobe, Google, Microsoft Dynamics 365, Salesforce, and Zendesk). Users can use these data actions to make routing decisions within their interaction flow in Architect, to present information to their agents in Scripts, or to act on data in other ways.

> **Note**: The following links point to live documentation that other writers might have modified after May 2021.

* [AWS Lambda data actions integration](https://help.mypurecloud.com/articles/about-the-aws-lambda-data-actions-integration/): Explained how to set up and use the AWS Lambda data actions integration. The integration allows users to create custom actions that they can then use throughout Genesys Cloud to directly invoke AWS Lambda functions in their AWS account.

* [Genesys Cloud data actions integration](https://help.mypurecloud.com/articles/about-genesys-cloud-data-actions-integration/): Explained how to set up and use the Genesys Cloud data actions integration. The integration provides static actions and allows users to create custom actions that use the Platform API. 

* **Adobe data actions integration** (deprecated May 2024): Explained how to set up and use the Adobe data actions integration. The integration allowed users to create custom actions that they could use throughout Genesys Cloud to act on data in Adobe. The integration supported Adobe Experience Platform.

* [Google data actions integration](https://help.mypurecloud.com/articles/about-the-google-data-actions-integration/): Explained how to set up and use the Google data actions integration. The integration allows users to create custom actions that they can use throughout Genesys Cloud to act on data in Google applications. The integration supports Google Cloud and G Suite. 

* [Microsoft Dynamics 365 data actions integration](https://help.mypurecloud.com/articles/about-microsoft-dynamics-365-data-actions-integration/): Explained how to set up and use the Microsoft Dynamics 365 data actions integration. The integration provides static actions and allows users to create custom actions that they can use to act on data in Microsoft Dynamics 365. 

* [Salesforce data actions integration](https://help.mypurecloud.com/articles/about-salesforce-data-actions-integration/): Explained how to set up and use the Salesforce data actions integration. The integration provides static actions and allows users to create custom actions that they can use throughout Genesys Cloud to act on data in Salesforce. 

* [Zendesk data actions integration](https://help.mypurecloud.com/articles/about-zendesk-data-actions-integration/): Explained how to set up and use the Zendesk data actions integration. The integration provides static actions and allows users to create custom actions that they can use to act on data in Zendesk.

* [Web services data actions integration](https://help.mypurecloud.com/articles/about-web-services-data-actions-integration/): Explained how to set up and use the web services data actions integration. The integration allows users to create custom actions that they can use throughout Genesys Cloud to interface with third-party JSON-based web services. 


##### Embedded clients
These 5 embedded clients are versions of Genesys Cloud contact center services that run within third-party applications (Salesforce or Zendesk) or as browser extensions (Chrome and Firefox). Users can also use the Genesys Cloud Embeddable Framework to integrate Genesys Cloud functionality within other contact center environments.

> **Note**: The following links point to live documentation that other writers might have modified after May 2021.

* [Genesys Cloud for Salesforce](https://help.mypurecloud.com/articles/about-genesys-cloud-for-salesforce/): Explained how to run, configure, and use Genesys Cloud contact center services as an integration within Salesforce. 

* [Genesys Cloud for Zendesk](https://help.mypurecloud.com/articles/about-genesys-cloud-for-zendesk/): Explained how to run, configure, and use Genesys Cloud contact center services as an integration within Zendesk.

* [Genesys Cloud browser extensions](https://help.mypurecloud.com/articles/about-the-genesys-cloud-browser-extensions/): Explained how to run, configure, and use Genesys Cloud contact center services as extensions inside the Chrome and Firefox browsers.

* **Genesys Cloud Embeddable Framework** [(Genesys Cloud Resource Center](https://help.mypurecloud.com/articles/about-genesys-cloud-embeddable-framework/), [Genesys Cloud Developer Center](https://developer.genesys.cloud/platform/embeddable-framework/)): Explained how to integrate Genesys Cloud with other systems and tools by developing and deploying custom integrations using exposed actions and methods.

##### SCIM
This integration enables automated user provisioning and synchronization between identity management systems and Genesys Cloud using the System for Cross-domain Identity Management (SCIM) standard.

> **Note**: The following link points to live documentation that other writers might have modified after May 2021.

* **Genesys Cloud SCIM (Identity Management) integration** ([Genesys Cloud Resource Center](https://help.mypurecloud.com/articles/about-genesys-cloud-scim-identity-management/), [Genesys Cloud Developer Center](https://developer.genesys.cloud/useragentman/scim/)): Explained setup, configuration, and APIs. This integration uses SCIM APIs to sync user entities from cloud or on-premises identity management systems to Genesys Cloud. 


#### API/SDK documentation

I architected, wrote, and maintained API, SDK, and developer documentation for technical audiences both in the Genesys Cloud Resource Center and the Genesys Cloud Developer Center. 

> **Note**: Links in the following PDFs point to live documentation that other writers might have modified after May 2021.

* [Genesys Cloud SCIM (Identity Management)](https://github.com/amylmiller7/Professional_info/blob/master/pdfs/genesys_cloud_scim_identity_management_overview.pdf): Explained how to use the SCIM API implementation to simplify the management of user entities between Genesys Cloud and identity management providers. I also edited and maintained the [SCIM API](https://github.com/amylmiller7/Professional_info/blob/master/pdfs/genesys_cloud_scim_identity_management_apis.pdf) reference material.

* [Genesys Cloud Embeddable Framework](https://github.com/amylmiller7/Professional_info/blob/master/pdfs/genesys_cloud_embeddable_framework_overview.pdf): Explained how developers can use the embeddable framework in their products to integrate the core functionality of Genesys Cloud. Included information about how to [develop and deploy](https://github.com/amylmiller7/Professional_info/blob/master/pdfs/genesys_cloud_embeddable_framework_deployment_options.pdf) the framework for [private](https://github.com/amylmiller7/Professional_info/blob/master/pdfs/genesys_cloud_embeddable_framework_private_deployment.pdf) or [public](https://github.com/amylmiller7/Professional_info/blob/master/pdfs/genesys_cloud_embeddable_framework_public_deployment.pdf) deployment; the [configuration and methods](https://github.com/amylmiller7/Professional_info/blob/master/pdfs/genesys_cloud_embeddable_framework_configuration_and_methods.pdf) and [actions](https://github.com/amylmiller7/Professional_info/blob/master/pdfs/genesys_cloud_embeddable_framework_actions.pdf) to use; [condensed conversation information](https://github.com/amylmiller7/Professional_info/blob/master/pdfs/genesys_cloud_embeddable_framework_condensed_conversation_information.pdf); a full [example](https://github.com/amylmiller7/Professional_info/blob/master/pdfs/genesys_cloud_embeddable_framework_example.pdf); and information about [support](https://github.com/amylmiller7/Professional_info/blob/master/pdfs/genesys_cloud_embeddable_framework_support.pdf). For configuration and method examples, see [`settings`](https://github.com/amylmiller7/Professional_info/blob/master/pdfs/genesys_cloud_embeddable_framework_settings.pdf) and [`contactSearch`](https://github.com/amylmiller7/Professional_info/blob/master/pdfs/contactsearch.pdf).

* [SDK to route Salesforce emails](https://github.com/amylmiller7/Professional_info/blob/master/pdfs/use_the_sdk_to_route_salesforce_emails.pdf): Explained why and how to route Salesforce emails through our SDK. Described the Email class, methods, and parameters available under two different namespaces, and provides example code.

* [SDK to call the Platform API](https://github.com/amylmiller7/Professional_info/blob/master/pdfs/use_the_sdk_to_call_the_genesys_cloud_platform_api.pdf): Explained how to use the SDK to call the Genesys Cloud Platform API within Salesforce.

* [SDK to create and save diagnostic logs](https://github.com/amylmiller7/Professional_info/blob/master/pdfs/use_the_sdk_to_create_and_save_diagnostic_logs.pdf): Explained how to use the SDK to create diagnostic logs about the Genesys Cloud for Salesforce integration within Salesforce.

* [Extension point to customize click-to-dial](https://github.com/amylmiller7/Professional_info/blob/master/pdfs/use_the_extension_points_to_customize_click-to-dial.pdf): Explained how to implement an interface in Apex to customize click-to-dial behavior in Salesforce.

* [Extension point to customize screen pops](https://github.com/amylmiller7/Professional_info/blob/master/pdfs/use_the_extension_points_to_customize_screen_pop.pdf): Explained how to implement an interface in Apex to customize screen pops in Salesforce.

* [Extension point to customize saving interaction logs](https://github.com/amylmiller7/Professional_info/blob/master/pdfs/use_the_extension_points_to_customize_saving_interaction_logs.pdf): Explained how to implement an interface in Apex to customize saving interaction logs in Salesforce.

* [Salesforce events](https://github.com/amylmiller7/Professional_info/blob/master/pdfs/events_in_salesforce.pdf): Explained how to fire or listen for events either in the Salesforce console in Salesforce Classic or in all versions of Lightning Experience (with the postMessage API or Lightning Message Service).

* [Genesys Cloud for Salesforce Examples](https://github.com/amylmiller7/Professional_info/blob/master/pdfs/Genesys_Cloud_for_Salesforce_examples.pdf): Wrote README files in GitHub that described example projects for the Salesforce Classic console, Lightning Experience, and the Genesys Cloud for Salesforce SDK. These examples used events in a [Salesforce console app](https://github.com/amylmiller7/Professional_info/blob/master/pdfs/Events_in_Salesforce_Classic_Console_App.pdf); events in a [Salesforce Lightning app](https://github.com/amylmiller7/Professional_info/blob/master/pdfs/Events_in_Salesforce_Lightning_app.pdf); the SDK for [CTI extensions](https://github.com/amylmiller7/Professional_info/blob/master/pdfs/Genesys_Cloud_for_Salesforce_SDK_CTI_extensions.pdf), [DNC list updates](https://github.com/amylmiller7/Professional_info/blob/master/pdfs/Genesys_Cloud_for_Salesforce_SDK_update_DNC_list.pdf), and [Genesys Cloud Platform API calls](https://github.com/amylmiller7/Professional_info/blob/master/pdfs/Genesys_Cloud_for_Salesforce_SDK_Examples.pdf).

* [PureCloud for Salesforce Einstein Example](https://github.com/amylmiller7/Professional_info/blob/master/pdfs/PureCloud_for_Salesforce_Einstein_Example.pdf): Wrote a README file in GitHub that described how to use a Salesforce Lightning component, Apex classes, and supporting files for use with Genesys Cloud for Salesforce to display Salesforce Knowledge articles based on ACD chat messages in Genesys Cloud for Salesforce.

* [PureCloud Embeddable Framework Example](https://github.com/amylmiller7/Professional_info/blob/master/pdfs/PureCloud_Embeddable_Framework_Example.pdf): Wrote a README file in GitHub that walked through a basic setup for a Genesys Cloud Embeddable Framework example page that users can use to explore the Genesys Cloud Embeddable Framework APIs in real-time.

* [PureCloud Embeddable Framework Mystery CRM](https://github.com/amylmiller7/Professional_info/blob/master/pdfs/PureCloud_Embeddable_Framework_Mystery_CRM.pdf): Wrote a README file in GitHub that described an example application that mimicked a custom CRM environment. The application could integrate with different Genesys Cloud Embeddable Framework deployment environments: local, private, and production.

* **Web services data dip connector API (deprecated 2022)**: Explained the API and how to use it for Genesys Cloud integrations and provided example code.


## Hardware documentation

I was part of the technical editing team at Maxim Integrated for approximately two and a half years, where I edited various types of documentation about semiconductors and integrated circuits for hardware design engineers and technical audiences. 

### Application notes

I worked closely with subject matter experts (SMEs) to edit approximately 90 new and revised application notes aimed at hardware design engineers. I checked spelling, grammar, and terminology, followed the company style and format, and optimized content for search engines (SEO).

### Data sheets

I edited data sheets aimed at design engineers for the company's analog and mixed-signal devices, ensuring technical accuracy and consistency with company standards.

### Website

I edited and rewrote product, solutions, and corporate pages that ranged from heavily technical to technical marketing content. I researched the technology being discussed and adapted the content to fit the medium, message, and end-user.

### Technical marketing documentation

I worked with SMEs to edit product and solutions guides and product briefs for technical and non-technical audiences for use at trade shows, on the website, and in customer meetings. I prepared meta descriptions and abstracts of these guides for the website.
