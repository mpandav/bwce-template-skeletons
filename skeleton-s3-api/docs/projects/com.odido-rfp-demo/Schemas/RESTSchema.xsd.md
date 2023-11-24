# RESTSchema {% raw %}{#{% endraw %}Xsd .concept}

Section contains description of XSD Schema RESTSchema.xsd“[RESTSchema.xsd](RESTSchema.xsd)”

Section contains description of XSD Schema “RESTSchema.xsd”

**Parent topic:**[XSD Schemas](../../../projects/com.odido-rfp-demo/common/xsd.md)

## Folder description: {% raw %}{#{% endraw %}FolderDescription}

|Folder|Description|
|------|-----------|
| |No description|

## Diagram: {% raw %}{#{% endraw %}Diagram}

![Diagram
              RESTSchema.xsd](RESTSchema.xsd.png)

## Attributes {% raw %}{#{% endraw %}Attributes}

-   *targetNamespace :**http://tns.tibco.com/bw/REST*

## Overview {% raw %}{#{% endraw %}Overview}

### Elements {% raw %}{#{% endraw %}Elements}

-   [messageBody](#element_messageBody)
-   [httpHeaders](#element_httpHeaders)
-   [httpResponseHeaders](#element_httpResponseHeaders)
-   [httpFaultHeaders](#element_httpFaultHeaders)
-   [dynamicConfigurations](#element_dynamicConfigurations)
-   [statusLine](#element_statusLine)
-   [client4XXError](#element_client4XXError)
-   [server5XXError](#element_server5XXError)
-   [jwtClaims](#element_jwtClaims)

### Complex Types {% raw %}{#{% endraw %}ComplexTypes}

-   [httpTransportHeaders](#type_httpTransportHeaders)
-   [httpTransportResponseHeaders](#type_httpTransportResponseHeaders)
-   [httpTransportFaultHeaders](#type_httpTransportFaultHeaders)
-   [dynamicHeadersTypeDetails](#type_dynamicHeadersTypeDetails)
-   [dynamicHeadersType](#type_dynamicHeadersType)
-   [dynamicConfigurationsType](#type_dynamicConfigurationsType)
-   [statusLineType](#type_statusLineType)
-   [client4XXErrorType](#type_client4XXErrorType)
-   [server5XXErrorType](#type_server5XXErrorType)
-   [jwtClaimElementType](#type_jwtClaimElementType)
-   [jwtClaimsType](#type_jwtClaimsType)

### Simple Types {% raw %}{#{% endraw %}SimpleTypes}

-   [tmessageBody](#type_tmessageBody)

## Detail {% raw %}{#{% endraw %}Detail}

### element messageBody {% raw %}{#{% endraw %}element_messageBody}

-   *type :**tns:tmessageBody*

### simpleType tmessageBody {% raw %}{#{% endraw %}type_tmessageBody}

-   restriction*base**string*

### complexType httpTransportHeaders {% raw %}{#{% endraw %}type_httpTransportHeaders}

-   element Accept*form**unqualified* , *minOccurs**0* , *type**string*

-   element Accept-Charset*form**unqualified* , *minOccurs**0* , *type**string*

-   element Accept-Encoding*form**unqualified* , *minOccurs**0* , *type**string*

-   element Content-Type*form**unqualified* , *minOccurs**0* , *type**string*

-   element Content-Length*form**unqualified* , *minOccurs**0* , *type**string*

-   element Connection*form**unqualified* , *minOccurs**0* , *type**string*

-   element Cookie*form**unqualified* , *minOccurs**0* , *type**string*

-   element Pragma*form**unqualified* , *minOccurs**0* , *type**string*

-   element Authorization*form**unqualified* , *minOccurs**0* , *type**string*

-   element DynamicHeaders*maxOccurs**1* , *minOccurs**0* , *type**tns:dynamicHeadersType*

### complexType httpTransportResponseHeaders {% raw %}{#{% endraw %}type_httpTransportResponseHeaders}

-   element Content-Length*form**unqualified* , *minOccurs**0* , *type**string*

-   element Connection*form**unqualified* , *minOccurs**0* , *type**string*

-   element Pragma*form**unqualified* , *minOccurs**0* , *type**string*

-   element StatusLine*form**unqualified* , *minOccurs**0* , *type**string*

-   element Location*form**unqualified* , *minOccurs**0* , *type**string*

-   element Set-Cookie*form**unqualified* , *minOccurs**0* , *type**string*

-   element Content-Type*form**unqualified* , *minOccurs**0* , *type**string*

-   element DynamicHeaders*maxOccurs**1* , *minOccurs**0* , *type**tns:dynamicHeadersType*

### complexType httpTransportFaultHeaders {% raw %}{#{% endraw %}type_httpTransportFaultHeaders}

-   element Content-Length*form**unqualified* , *minOccurs**0* , *type**string*

-   element Connection*form**unqualified* , *minOccurs**0* , *type**string*

-   element Pragma*form**unqualified* , *minOccurs**0* , *type**string*

-   element StatusLine*form**unqualified* , *minOccurs**0* , *type**string*

-   element Location*form**unqualified* , *minOccurs**0* , *type**string*

-   element Set-Cookie*form**unqualified* , *minOccurs**0* , *type**string*

-   element Content-Type*form**unqualified* , *minOccurs**0* , *type**string*

-   element DynamicHeaders*maxOccurs**1* , *minOccurs**0* , *type**tns:dynamicHeadersType*

### complexType dynamicHeadersTypeDetails {% raw %}{#{% endraw %}type_dynamicHeadersTypeDetails}

-   element Name*form**unqualified* , *maxOccurs**1* , *minOccurs**1* , *type**string*

-   element Value*form**unqualified* , *maxOccurs**1* , *minOccurs**1* , *type**string*

### complexType dynamicHeadersType {% raw %}{#{% endraw %}type_dynamicHeadersType}

-   element Header*form**unqualified* , *maxOccurs**unbounded* , *minOccurs**0* , *type**tns:dynamicHeadersTypeDetails*

### element httpHeaders {% raw %}{#{% endraw %}element_httpHeaders}

-   *type :**tns:httpTransportHeaders*

### element httpResponseHeaders {% raw %}{#{% endraw %}element_httpResponseHeaders}

-   *type :**tns:httpTransportResponseHeaders*

### element httpFaultHeaders {% raw %}{#{% endraw %}element_httpFaultHeaders}

-   *type :**tns:httpTransportFaultHeaders*

### element dynamicConfigurations {% raw %}{#{% endraw %}element_dynamicConfigurations}

-   *type :**tns:dynamicConfigurationsType*

### complexType dynamicConfigurationsType {% raw %}{#{% endraw %}type_dynamicConfigurationsType}

-   element URL*maxOccurs**1* , *minOccurs**0* , *type**string*

-   element activityTimeout*maxOccurs**1* , *minOccurs**0* , *type**integer*

### complexType statusLineType {% raw %}{#{% endraw %}type_statusLineType}

-   element statusCode*form**unqualified* , *maxOccurs**1* , *minOccurs**1* , *type**integer*

### element statusLine {% raw %}{#{% endraw %}element_statusLine}

-   *type :**tns:statusLineType*

### complexType client4XXErrorType {% raw %}{#{% endraw %}type_client4XXErrorType}

-   element statusCode*form**unqualified* , *maxOccurs**1* , *minOccurs**1* , *type**integer*

-   element message*form**unqualified* , *maxOccurs**1* , *minOccurs**0* , *type**string*

### element client4XXError {% raw %}{#{% endraw %}element_client4XXError}

-   *type :**tns:client4XXErrorType*

### complexType server5XXErrorType {% raw %}{#{% endraw %}type_server5XXErrorType}

-   element statusCode*form**unqualified* , *maxOccurs**1* , *minOccurs**1* , *type**integer*

-   element message*form**unqualified* , *maxOccurs**1* , *minOccurs**0* , *type**string*

### element server5XXError {% raw %}{#{% endraw %}element_server5XXError}

-   *type :**tns:server5XXErrorType*

### complexType jwtClaimElementType {% raw %}{#{% endraw %}type_jwtClaimElementType}

-   element Name*form**unqualified* , *maxOccurs**1* , *minOccurs**1* , *type**string*

-   element Value*form**unqualified* , *maxOccurs**1* , *minOccurs**1* , *type**string*

### complexType jwtClaimsType {% raw %}{#{% endraw %}type_jwtClaimsType}

-   element claim*maxOccurs**unbounded* , *minOccurs**0* , *type**tns:jwtClaimElementType*

-   element payload*maxOccurs**1* , *minOccurs**0* , *type**string*

### element jwtClaims {% raw %}{#{% endraw %}element_jwtClaims}

-   *type :**tns:jwtClaimsType*

