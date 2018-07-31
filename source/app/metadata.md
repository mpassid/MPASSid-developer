title: App metadata
---

# Prepare application metadata


```xml

<?xml version="1.0"?>
<EntityDescriptor 
	 	xmlns="urn:oasis:names:tc:SAML:2.0:metadata" 
	 	xmlns:ds="http://www.w3.org/2000/09/xmldsig#" 
	 	entityID="https://www.examina.fi/" ID="https___www_examina_fi_">
  <SPSSODescriptor 
  	 	protocolSupportEnumeration="urn:oasis:names:tc:SAML:2.0:protocol">
    <AssertionConsumerService 
    	index="1" 
    	isDefault="true" 
    	Binding="urn:oasis:names:tc:SAML:2.0:bindings:HTTP-POST" 
    	Location="https://www.examina.fi/login/callback"/>
  </SPSSODescriptor>
</EntityDescriptor>

```

### Proceed to test environment


