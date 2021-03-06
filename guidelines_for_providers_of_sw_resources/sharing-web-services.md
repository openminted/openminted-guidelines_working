### Sharing apps/components as web services

#### 

#### **Step 1 - Preparing and packaging**

If you intend to share your TDM software \(application or component\) as a web service through OpenMinTeD, please ensure that it uses UIMA CAS XMI messaging system as specified at [https://openminted.github.io/releases/processing-web-services/1.0.0/specification](https://openminted.github.io/releases/processing-web-services/1.0.0/specification).

#### **Step 2 - Registering in OpenMinTeD**

You can then visit the [OpenMinTeD registry](https://services.openminted.eu/resourceRegistration/component) where you can register your web service in one of the following ways:

* edit from scratch the [OMTD-SHARE](/the_omtd-share_metadata_schema.md) metadata record[^1] using the OpenMinTeD editor or
* upload an XML file with the [OMTD-SHARE](/the_omtd-share_metadata_schema.md) metadata record. 

In both cases, the metadata record can be viewed and edited at the end of the process.

You must provide the the URL where the web service can be executed in the metadata element _&lt;distributionLocation&gt;_, e.g.

`<distributionLocation>http://nactem.ac.uk/api/openminted/chebi</distributionLocation>`

Further requirements and recommendations for achieving interoperability across components and with the content resources are presented [here](/guidelines_for_providers_of_sw_resources/how-to-make-your-components-interoperable.md).

[^1]: You can find example metadata records [here](/guidelines_for_providers_of_sw_resources/examples-for-software-resources.md).

