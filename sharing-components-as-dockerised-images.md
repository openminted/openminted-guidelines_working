### Sharing components as Docker images



Components from frameworks and technologies other than UIMA and GATE must be registered in OpenMinTeD as Docker images.



**Step 1**

To build an OpenMinTeD-compatible Docker image of components, you must follow the specifications described at [https://openminted.github.io/releases/docker-spec/0.1.0/specification](https://openminted.github.io/releases/docker-spec/0.1.0/specification) and upload it to the OpenMinTeD Docker Registry.



**Step 2**

You can then visit the OpenMinTeD registry where you can register your component in one of the following ways:

* edit from scratch the OMTD-SHARE metadata record using the OpenMinTeD editor or

* upload an XML file with the OMTD-SHARE metadata record 

The Docker image location and identifier must be provided in the elements _&lt;distributionLocation&gt; _and _&lt;resourceIdentifier&gt;_, e.g.

`<distributionLocation>docker????/openminted/dkpro-core:1.9.0</distributionLocation>`

`<resourceIdentifier>dkpro-core:1.9.0</resourceIdentifier>`

In all of these cases, the metadata record can be viewed and edited at the end of the process.

Further requirements and recommendations for achieving interoperability across components and with the content resources are presented here.  

