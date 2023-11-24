# static-routerHeaderParameterSchema {% raw %}{#{% endraw %}Xsd .concept}

Section contains description of XSD Schema static-routerHeaderParameterSchema.xsd“[static-routerHeaderParameterSchema.xsd](static-routerHeaderParameterSchema.xsd)”

Section contains description of XSD Schema “static-routerHeaderParameterSchema.xsd”

**Parent topic:**[XSD Schemas](../../../projects/com.odido-rfp-demo.application_1.0.0_ear/common/xsd.md)

## Folder description: {% raw %}{#{% endraw %}FolderDescription}

|Folder|Description|
|------|-----------|
| |No description|

## Diagram: {% raw %}{#{% endraw %}Diagram}

![Diagram
              static-routerHeaderParameterSchema.xsd](static-routerHeaderParameterSchema.xsd.png)

## Attributes {% raw %}{#{% endraw %}Attributes}

-   *elementFormDefault :**unqualified*
-   *targetNamespace :**http://xmlns.example.com/static-router/headerParameters*

## Imports {% raw %}{#{% endraw %}Imports}

### Namespace: http://tns.tibco.com/bw/REST {% raw %}{#{% endraw %}unknownNamespace4}

Imported from file: 

## Overview {% raw %}{#{% endraw %}Overview}

### Elements {% raw %}{#{% endraw %}Elements}

-   [static-routerGetHeader](#element_static-routerGetHeader)

### Complex Types {% raw %}{#{% endraw %}ComplexTypes}

-   [static-routerGetHeaderType](#type_static-routerGetHeaderType)

## Detail {% raw %}{#{% endraw %}Detail}

### complexType static-routerGetHeaderType {% raw %}{#{% endraw %}type_static-routerGetHeaderType}

-   extension*base**Q1:httpTransportHeaders*
-   sequence:
    -   element backend*maxOccurs**1* , *minOccurs**1* , *type**xs:string*

### element static-routerGetHeader {% raw %}{#{% endraw %}element_static-routerGetHeader}

-   *type :**tns:static-routerGetHeaderType*

