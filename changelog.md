## CAS-Addons Changelog

###Changes in version 1.5
======================================

* updated Jackson dependency to 2.2.0
* updated Jersey dependency to 1.17
* added [RegisteredServiceAuthorizer](https://github.com/Unicon/cas-addons/blob/master/src/main/java/net/unicon/cas/addons/serviceregistry/services/authorization/RegisteredServiceAuthorizer.java)
* added [DefaultRegisteredServiceAuthorizer](https://github.com/Unicon/cas-addons/blob/master/src/main/groovy/net/unicon/cas/addons/serviceregistry/services/authorization/DefaultRegisteredServiceAuthorizer.groovy)
* added [RoleBasedServiceAuthorizationException](https://github.com/Unicon/cas-addons/blob/master/src/main/java/net/unicon/cas/addons/serviceregistry/services/authorization/RoleBasedServiceAuthorizationException.java)
* added [ServiceAuthorizationAction](https://github.com/Unicon/cas-addons/blob/master/src/main/java/net/unicon/cas/addons/serviceregistry/services/authorization/ServiceAuthorizationAction.java)
* added [ServiceValidateFailureJsonView](https://github.com/Unicon/cas-addons/blob/master/src/main/java/net/unicon/cas/addons/response/ServiceValidateFailureJsonView.java)

###Changes in version 1.4 (2013-04-17)
======================================

* upgraded Stormpath Java SDK dependency to 0.7.0
* added [StormpathPrincipal](https://github.com/Unicon/cas-addons/blob/master/src/main/java/net/unicon/cas/addons/authentication/principal/StormpathPrincipal.java)
* added [StormpathPrincipalResolver](https://github.com/Unicon/cas-addons/blob/master/src/main/java/net/unicon/cas/addons/authentication/principal/StormpathPrincipalResolver.java)
* added Stormpath related custom XML schema types and parsers
* renamed `cas-addons-1.3.xsd` to `cas-addons.xsd`


###Changes in version 1.3 (2013-04-07)
======================================

* added [Custom namespace XML schema](https://github.com/Unicon/cas-addons/blob/master/src/main/resources/net/unicon/cas/addons/config/cas-addons-1.3.xsd)
* added [Custom namespace XML schema parsers](https://github.com/Unicon/cas-addons/blob/master/src/main/java/net/unicon/cas/addons/config/CasNamespaceHandler.java)


###Changes in version 1.2 (2013-02-18)
======================================

* added [RegisteredServicesPolicies](https://github.com/Unicon/cas-addons/blob/master/src/main/java/net/unicon/cas/addons/serviceregistry/services/RegisteredServicesPolicies.java)
* added [DefaultRegisteredServicesPolicies](https://github.com/Unicon/cas-addons/blob/master/src/main/java/net/unicon/cas/addons/serviceregistry/services/internal/DefaultRegisteredServicesPolicies.java)
* added [ServiceInitiatingWebSsoAwareCookieGenerator](https://github.com/Unicon/cas-addons/blob/master/src/main/java/net/unicon/cas/addons/web/support/ServiceInitiatingWebSsoAwareCookieGenerator.java)
* added [SsoDestroyingServiceValidateController](https://github.com/Unicon/cas-addons/blob/master/src/main/java/net/unicon/cas/addons/web/support/SsoDestroyingServiceValidateController.java)


###Changes in version 1.1 (2013-01-02)
======================================

* removed CAS client related classes and moved them to a sister [cas-java-clients-addons](https://github.com/Unicon/cas-java-clients-addons) project
* added gmaven plugin to the pom in order for Spock tests to run during the maven build
* updated pom dependecies to the latest versions (where available)

###Changes in version 1.1-RC1 (2012-12-07)
==========================================

* added [Assertions](https://github.com/Unicon/cas-addons/blob/master/src/main/java/net/unicon/cas/addons/authentication/support/Assertions.java)
* added [ClearpassRetrievingCasAuthenticationProvider](https://github.com/Unicon/cas-addons/blob/master/src/main/java/net/unicon/cas/addons/client/springsecurity/ClearpassRetrievingCasAuthenticationProvider.java)
* added [CentralAuthenticationServiceEventsPublishingAspect](https://github.com/Unicon/cas-addons/blob/master/src/main/java/net/unicon/cas/addons/info/events/CentralAuthenticationServiceEventsPublishingAspect.java)


###Changes in version 1.0.5 (2012-11-16)
========================================

* refactored unauthorized service view attribute `unauthorizedUrl` -> `disabledServiceUrl`

###Changes in version 1.0.4 (2012-11-12)
========================================

* removed tgt_id from Single SignOn Sessions Report

###Changes in version 1.0.3 (2012-11-11)
========================================

* added [TicketSupport](https://github.com/Unicon/cas-addons/blob/master/src/main/java/net/unicon/cas/addons/ticket/TicketSupport.java)
* added [SingleSignOnSessionsReport](https://github.com/Unicon/cas-addons/blob/master/src/main/java/net/unicon/cas/addons/info/SingleSignOnSessionsReport.java)
* added [SingleSignOnSessionsReportResource](https://github.com/Unicon/cas-addons/blob/master/src/main/java/net/unicon/cas/addons/info/SingleSignOnSessionsReportResource.java)
* updated Jackson library dependency to 2.1.0

###Changes in version 1.0.2 (2012-11-05)
========================================

* added [ShiroHashServicePasswordEncoder](https://github.com/Unicon/cas-addons/blob/master/src/main/java/net/unicon/cas/addons/authentication/handler/ShiroHashServicePasswordEncoder.java)
* added [ServiceAuthorizationCheckWithCustomView](https://github.com/Unicon/cas-addons/blob/master/src/main/java/net/unicon/cas/addons/web/flow/ServiceAuthorizationCheckWithCustomView.java)

###Changes in version 1.0.1 (2012-10-26)
========================================

* added [MongoServiceRegistryDao](https://github.com/Unicon/cas-addons/blob/master/src/main/java/net/unicon/cas/addons/serviceregistry/mongodb/MongoServiceRegistryDao.java)
* added the [info](https://github.com/Unicon/cas-addons/blob/master/src/main/java/net/unicon/cas/addons/info) package

###Changes in version 1.0 (2012-10-07)
======================================

* updated CAS dependency to 3.5.1 General Availability

###Changes in version 1.0-RC1 (2012-09-22)
=========================================

* updated CAS dependency to 3.5.1-RC1

###Changes in version 1.0-M2 (2012-09-17)
=========================================

* fixed bug preventing real-time reloading of JSON-based configured registered services

###Changes in version 1.0-M1 (2012-09-16)
=========================================

* updated JASIG's Person Directory Service to 1.5.1
* refactored `StormpathBasicAuthenticationHandler -> StormpathAuthenticationHandler` to use Stormpath's Java SDK instead of a low level REST API


###Changes in version 0.9.5 (2012-08-29)
========================================

* added [ReloadableServicesManagerSuppressionAspect](https://github.com/Unicon/cas-addons/blob/master/src/main/java/net/unicon/cas/addons/serviceregistry/ReloadableServicesManagerSuppressionAspect.java)
* refactored [JsonServiceRegistryDao](https://github.com/Unicon/cas-addons/blob/master/src/main/java/net/unicon/cas/addons/serviceregistry/JsonServiceRegistryDao.java) to support real time reloading using resource change notify/listen framework
* added [ThreadSafe](https://github.com/Unicon/cas-addons/blob/master/src/main/java/net/unicon/cas/addons/support/ThreadSafe.java)
* added [NotThreadSafe](https://github.com/Unicon/cas-addons/blob/master/src/main/java/net/unicon/cas/addons/support/NotThreadSafe.java)
* added [GuardedBy](https://github.com/Unicon/cas-addons/blob/master/src/main/java/net/unicon/cas/addons/support/GuardedBy.java)
* added [Immutable](https://github.com/Unicon/cas-addons/blob/master/src/main/java/net/unicon/cas/addons/support/Immutable.java)

###Changes in version 0.9 (2012-08-11)
======================================

* added [GrouperPersonAttributeDao](https://github.com/Unicon/cas-addons/blob/master/src/main/java/net/unicon/cas/addons/persondir/GrouperPersonAttributeDao.java)

###Changes in version 0.8 (2012-07-27) 
======================================

* added [StormpathBasicAuthenticationHandler](https://github.com/Unicon/cas-addons/blob/master/src/main/java/net/unicon/cas/addons/authentication/handler/StormpathBasicAuthenticationHandler.java)
* refactored [JsonServiceRegistryDao](https://github.com/Unicon/cas-addons/blob/master/src/main/java/net/unicon/cas/addons/serviceregistry/JsonServiceRegistryDao.java) as a 'raw' Java class instead of a Groovy one

###Changes in version 0.7 (2012-07-20)
======================================

* added [JsonBackedComplexStubPersonAttributeDao](https://github.com/Unicon/cas-addons/blob/master/src/main/java/net/unicon/cas/addons/persondir/JsonBackedComplexStubPersonAttributeDao.java)
* added [ResourceChangeDetectingEventNotifier](https://github.com/Unicon/cas-addons/blob/master/src/main/java/net/unicon/cas/addons/support/ResourceChangeDetectingEventNotifier.java)

###Changes in version 0.6 (2012-07-14)
======================================

* added [EmailAddressToPrincipalNameTransformer](https://github.com/Unicon/cas-addons/blob/master/src/main/java/net/unicon/cas/addons/authentication/handler/EmailAddressToPrincipalNameTransformer.java)
* added [EmailAddressPasswordCredentialsToPrincipalResolver](https://github.com/Unicon/cas-addons/blob/master/src/main/java/net/unicon/cas/addons/authentication/principal/EmailAddressPasswordCredentialsToPrincipalResolver.java)
* added [ServiceValidateSuccessJsonView](https://github.com/Unicon/cas-addons/blob/master/src/main/java/net/unicon/cas/addons/response/ServiceValidateSuccessJsonView.java)
* added [Cas20ServiceTicketJsonValidationFilter](https://github.com/Unicon/cas-addons/blob/master/src/main/java/net/unicon/cas/addons/client/validation/Cas20ServiceTicketJsonValidationFilter.java)
* added [Cas20ServiceTicketJsonValidator](https://github.com/Unicon/cas-addons/blob/master/src/main/java/net/unicon/cas/addons/client/validation/Cas20ServiceTicketJsonValidator.java)
* upgraded [Groovy dependency to 2.0.0](https://github.com/Unicon/cas-addons/blob/master/pom.xml)
* upgraded [Jackson dependency to 2.0.4](https://github.com/Unicon/cas-addons/blob/master/pom.xml)
* upgraded [CAS server dependency to 3.5.0](https://github.com/Unicon/cas-addons/blob/master/pom.xml)

###Changes in version 0.5 (2012-06-25)
======================================

* added [RegexRegisteredServiceWithAttributes](https://github.com/Unicon/cas-addons/blob/master/src/main/java/net/unicon/cas/addons/serviceregistry/RegexRegisteredServiceWithAttributes.java)
* added support for RegexRegisteredServiceWithAttributes in [JsonServiceRegistryDao](https://github.com/Unicon/cas-addons/blob/master/src/main/java/net/unicon/cas/addons/serviceregistry/JsonServiceRegistryDao.groovy)
* added [AdditionalAuthenticationFactorPolicy](https://github.com/Unicon/cas-addons/blob/master/src/main/java/net/unicon/cas/addons/authentication/strong/AdditionalAuthenticationFactorPolicy.java)
* added [TotpOathDetailsSource](https://github.com/Unicon/cas-addons/blob/master/src/main/java/net/unicon/cas/addons/authentication/strong/oath/totp/TotpOathDetailsSource.java)
* added [TOTP](https://github.com/Unicon/cas-addons/blob/master/src/main/java/net/unicon/cas/addons/authentication/strong/oath/totp/TOTP.java)
* added [TOTPUtils](https://github.com/Unicon/cas-addons/blob/master/src/main/java/net/unicon/cas/addons/authentication/strong/oath/totp/TOTPUtils.java)
* added [TotpAuthenticationHandler](https://github.com/Unicon/cas-addons/blob/master/src/main/java/net/unicon/cas/addons/authentication/strong/oath/totp/TotpAuthenticationHandler.java)
* added [PasswordExpirationStatusPolicySupport](https://github.com/Unicon/cas-addons/blob/master/src/main/java/net/unicon/cas/addons/authentication/support/PasswordExpirationStatusPolicySupport.java)
* upgraded CAS dependency to 3.5.0-RC2

###Changes in version 0.3 (2012-06-18)
======================================

* added groovy-eclipse-compiler to maven-compiler-plugin so that JsonServiceRegistryDao.groovy is compiled into native Java class during build time an so could be used as a regular Spring bean without requireing dynamic Groovy class loading at runtime


