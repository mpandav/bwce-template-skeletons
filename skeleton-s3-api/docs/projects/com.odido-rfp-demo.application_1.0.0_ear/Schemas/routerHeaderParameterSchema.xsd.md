# routerHeaderParameterSchema {% raw %}{#{% endraw %}Xsd .concept}

Section contains description of XSD Schema routerHeaderParameterSchema.xsd“[routerHeaderParameterSchema.xsd](routerHeaderParameterSchema.xsd)”

Section contains description of XSD Schema “routerHeaderParameterSchema.xsd”

**Parent topic:**[XSD Schemas](../../../projects/com.odido-rfp-demo.application_1.0.0_ear/common/xsd.md)

## Folder description: {% raw %}{#{% endraw %}FolderDescription}

|Folder|Description|
|------|-----------|
| |No description|

## Diagram: {% raw %}{#{% endraw %}Diagram}

![Diagram
              routerHeaderParameterSchema.xsd](routerHeaderParameterSchema.xsd.png)

## Attributes {% raw %}{#{% endraw %}Attributes}

-   *elementFormDefault :**unqualified*
-   *targetNamespace :**http://xmlns.example.com/router/headerParameters*

## Imports {% raw %}{#{% endraw %}Imports}

### Namespace: http://tns.tibco.com/bw/REST {% raw %}{#{% endraw %}unknownNamespace3}

Imported from file: 

## Overview {% raw %}{#{% endraw %}Overview}

### Elements {% raw %}{#{% endraw %}Elements}

-   [routerPostHeader](#element_routerPostHeader)
-   [router1GetHeader](#element_router1GetHeader)

### Complex Types {% raw %}{#{% endraw %}ComplexTypes}

-   [routerPostHeaderType](#type_routerPostHeaderType)
-   [router1GetHeaderType](#type_router1GetHeaderType)

## Detail {% raw %}{#{% endraw %}Detail}

### complexType routerPostHeaderType {% raw %}{#{% endraw %}type_routerPostHeaderType}

-   extension*base**Q1:httpTransportHeaders*
-   sequence:
    -   element backend*maxOccurs**1* , *minOccurs**0* , *type**xs:string*

### element routerPostHeader {% raw %}{#{% endraw %}element_routerPostHeader}

-   *type :**tns:routerPostHeaderType*

### complexType router1GetHeaderType {% raw %}{#{% endraw %}type_router1GetHeaderType}

-   extension*base**Q1:httpTransportHeaders*
-   sequence:
    -   element backend*maxOccurs**1* , *minOccurs**0* , *type**xs:string*

### element router1GetHeader {% raw %}{#{% endraw %}element_router1GetHeader}

-   *type :**tns:router1GetHeaderType*

