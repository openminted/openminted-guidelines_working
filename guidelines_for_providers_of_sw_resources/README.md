# ​Guidelines for providers of software \(applications and components\) {#guidelines-for-providers-of-s-w-resources}

OpenMinTeD targets  scholarly researchers who are agnostic to software details and peculiarities as well as expert TDM developers. It allows, therefore, the registration of

* end-user **applications **that can be used as-is to perform TDM operations on content resources, and
* **components**, i.e. pieces of software that perform basic tasks; using the OpenMinTeD Workflow Editor, TDM developers can combine together components and tune them with ancillary knowledge resources in order to build applications that will be offered to end-users.



![](/assets/4a.png)

If you wish to share TDM software through the [OpenMinTeD platform](https://services.openminted.eu/home), you must

* provide access to an **executable **of the software in one of the ways specified in the next sections, and

* register the software in the [OpenMinTeD registry](https://services.openminted.eu/resourceRegistration/component) with a **metadata record **compliant with the  [OMTD-SHARE schema](/guidelines_for_providers_of_sw_resources/recommended_schema_for_sw_resources.md), at least at the minimal level.

Furthermore, to ensure that your components are interoperable with components implemented with other frameworks or technologies and can thus can be used in “mixed” workflows, they must either support \(i.e. produce & consume\) data in [XML Metadata Interchange \(XMI\)](http://www.omg.org/spec/XMI/) format[^1] or you should provide appropriate readers and writers for converting XMI messages from and to the components’ format.

---

[^1]: As also happens in the UIMA framework.

