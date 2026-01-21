---
permalink: /26.4.7/k8s/v2alpha1/keycloakRealmImport/
---

# k8s.v2alpha1.keycloakRealmImport



## Index

* [`fn new(name)`](#fn-new)
* [`obj metadata`](#obj-metadata)
  * [`fn withAnnotations(annotations)`](#fn-metadatawithannotations)
  * [`fn withAnnotationsMixin(annotations)`](#fn-metadatawithannotationsmixin)
  * [`fn withClusterName(clusterName)`](#fn-metadatawithclustername)
  * [`fn withCreationTimestamp(creationTimestamp)`](#fn-metadatawithcreationtimestamp)
  * [`fn withDeletionGracePeriodSeconds(deletionGracePeriodSeconds)`](#fn-metadatawithdeletiongraceperiodseconds)
  * [`fn withDeletionTimestamp(deletionTimestamp)`](#fn-metadatawithdeletiontimestamp)
  * [`fn withFinalizers(finalizers)`](#fn-metadatawithfinalizers)
  * [`fn withFinalizersMixin(finalizers)`](#fn-metadatawithfinalizersmixin)
  * [`fn withGenerateName(generateName)`](#fn-metadatawithgeneratename)
  * [`fn withGeneration(generation)`](#fn-metadatawithgeneration)
  * [`fn withLabels(labels)`](#fn-metadatawithlabels)
  * [`fn withLabelsMixin(labels)`](#fn-metadatawithlabelsmixin)
  * [`fn withName(name)`](#fn-metadatawithname)
  * [`fn withNamespace(namespace)`](#fn-metadatawithnamespace)
  * [`fn withOwnerReferences(ownerReferences)`](#fn-metadatawithownerreferences)
  * [`fn withOwnerReferencesMixin(ownerReferences)`](#fn-metadatawithownerreferencesmixin)
  * [`fn withResourceVersion(resourceVersion)`](#fn-metadatawithresourceversion)
  * [`fn withSelfLink(selfLink)`](#fn-metadatawithselflink)
  * [`fn withUid(uid)`](#fn-metadatawithuid)
* [`obj spec`](#obj-spec)
  * [`fn withKeycloakCRName(keycloakCRName)`](#fn-specwithkeycloakcrname)
  * [`fn withPlaceholders(placeholders)`](#fn-specwithplaceholders)
  * [`fn withPlaceholdersMixin(placeholders)`](#fn-specwithplaceholdersmixin)
  * [`obj spec.realm`](#obj-specrealm)
    * [`fn withAccessCodeLifespan(accessCodeLifespan)`](#fn-specrealmwithaccesscodelifespan)
    * [`fn withAccessCodeLifespanLogin(accessCodeLifespanLogin)`](#fn-specrealmwithaccesscodelifespanlogin)
    * [`fn withAccessCodeLifespanUserAction(accessCodeLifespanUserAction)`](#fn-specrealmwithaccesscodelifespanuseraction)
    * [`fn withAccessTokenLifespan(accessTokenLifespan)`](#fn-specrealmwithaccesstokenlifespan)
    * [`fn withAccessTokenLifespanForImplicitFlow(accessTokenLifespanForImplicitFlow)`](#fn-specrealmwithaccesstokenlifespanforimplicitflow)
    * [`fn withAccountTheme(accountTheme)`](#fn-specrealmwithaccounttheme)
    * [`fn withActionTokenGeneratedByAdminLifespan(actionTokenGeneratedByAdminLifespan)`](#fn-specrealmwithactiontokengeneratedbyadminlifespan)
    * [`fn withActionTokenGeneratedByUserLifespan(actionTokenGeneratedByUserLifespan)`](#fn-specrealmwithactiontokengeneratedbyuserlifespan)
    * [`fn withAdminEventsDetailsEnabled(adminEventsDetailsEnabled)`](#fn-specrealmwithadmineventsdetailsenabled)
    * [`fn withAdminEventsEnabled(adminEventsEnabled)`](#fn-specrealmwithadmineventsenabled)
    * [`fn withAdminPermissionsEnabled(adminPermissionsEnabled)`](#fn-specrealmwithadminpermissionsenabled)
    * [`fn withAdminTheme(adminTheme)`](#fn-specrealmwithadmintheme)
    * [`fn withApplicationScopeMappings(applicationScopeMappings)`](#fn-specrealmwithapplicationscopemappings)
    * [`fn withApplicationScopeMappingsMixin(applicationScopeMappings)`](#fn-specrealmwithapplicationscopemappingsmixin)
    * [`fn withApplications(applications)`](#fn-specrealmwithapplications)
    * [`fn withApplicationsMixin(applications)`](#fn-specrealmwithapplicationsmixin)
    * [`fn withAttributes(attributes)`](#fn-specrealmwithattributes)
    * [`fn withAttributesMixin(attributes)`](#fn-specrealmwithattributesmixin)
    * [`fn withAuthenticationFlows(authenticationFlows)`](#fn-specrealmwithauthenticationflows)
    * [`fn withAuthenticationFlowsMixin(authenticationFlows)`](#fn-specrealmwithauthenticationflowsmixin)
    * [`fn withAuthenticatorConfig(authenticatorConfig)`](#fn-specrealmwithauthenticatorconfig)
    * [`fn withAuthenticatorConfigMixin(authenticatorConfig)`](#fn-specrealmwithauthenticatorconfigmixin)
    * [`fn withBrowserFlow(browserFlow)`](#fn-specrealmwithbrowserflow)
    * [`fn withBrowserSecurityHeaders(browserSecurityHeaders)`](#fn-specrealmwithbrowsersecurityheaders)
    * [`fn withBrowserSecurityHeadersMixin(browserSecurityHeaders)`](#fn-specrealmwithbrowsersecurityheadersmixin)
    * [`fn withBruteForceProtected(bruteForceProtected)`](#fn-specrealmwithbruteforceprotected)
    * [`fn withBruteForceStrategy(bruteForceStrategy)`](#fn-specrealmwithbruteforcestrategy)
    * [`fn withCertificate(certificate)`](#fn-specrealmwithcertificate)
    * [`fn withClientAuthenticationFlow(clientAuthenticationFlow)`](#fn-specrealmwithclientauthenticationflow)
    * [`fn withClientOfflineSessionIdleTimeout(clientOfflineSessionIdleTimeout)`](#fn-specrealmwithclientofflinesessionidletimeout)
    * [`fn withClientOfflineSessionMaxLifespan(clientOfflineSessionMaxLifespan)`](#fn-specrealmwithclientofflinesessionmaxlifespan)
    * [`fn withClientPolicies(clientPolicies)`](#fn-specrealmwithclientpolicies)
    * [`fn withClientProfiles(clientProfiles)`](#fn-specrealmwithclientprofiles)
    * [`fn withClientScopeMappings(clientScopeMappings)`](#fn-specrealmwithclientscopemappings)
    * [`fn withClientScopeMappingsMixin(clientScopeMappings)`](#fn-specrealmwithclientscopemappingsmixin)
    * [`fn withClientScopes(clientScopes)`](#fn-specrealmwithclientscopes)
    * [`fn withClientScopesMixin(clientScopes)`](#fn-specrealmwithclientscopesmixin)
    * [`fn withClientSessionIdleTimeout(clientSessionIdleTimeout)`](#fn-specrealmwithclientsessionidletimeout)
    * [`fn withClientSessionMaxLifespan(clientSessionMaxLifespan)`](#fn-specrealmwithclientsessionmaxlifespan)
    * [`fn withClientTemplates(clientTemplates)`](#fn-specrealmwithclienttemplates)
    * [`fn withClientTemplatesMixin(clientTemplates)`](#fn-specrealmwithclienttemplatesmixin)
    * [`fn withClients(clients)`](#fn-specrealmwithclients)
    * [`fn withClientsMixin(clients)`](#fn-specrealmwithclientsmixin)
    * [`fn withCodeSecret(codeSecret)`](#fn-specrealmwithcodesecret)
    * [`fn withComponents(components)`](#fn-specrealmwithcomponents)
    * [`fn withComponentsMixin(components)`](#fn-specrealmwithcomponentsmixin)
    * [`fn withDefaultDefaultClientScopes(defaultDefaultClientScopes)`](#fn-specrealmwithdefaultdefaultclientscopes)
    * [`fn withDefaultDefaultClientScopesMixin(defaultDefaultClientScopes)`](#fn-specrealmwithdefaultdefaultclientscopesmixin)
    * [`fn withDefaultGroups(defaultGroups)`](#fn-specrealmwithdefaultgroups)
    * [`fn withDefaultGroupsMixin(defaultGroups)`](#fn-specrealmwithdefaultgroupsmixin)
    * [`fn withDefaultLocale(defaultLocale)`](#fn-specrealmwithdefaultlocale)
    * [`fn withDefaultOptionalClientScopes(defaultOptionalClientScopes)`](#fn-specrealmwithdefaultoptionalclientscopes)
    * [`fn withDefaultOptionalClientScopesMixin(defaultOptionalClientScopes)`](#fn-specrealmwithdefaultoptionalclientscopesmixin)
    * [`fn withDefaultRoles(defaultRoles)`](#fn-specrealmwithdefaultroles)
    * [`fn withDefaultRolesMixin(defaultRoles)`](#fn-specrealmwithdefaultrolesmixin)
    * [`fn withDefaultSignatureAlgorithm(defaultSignatureAlgorithm)`](#fn-specrealmwithdefaultsignaturealgorithm)
    * [`fn withDirectGrantFlow(directGrantFlow)`](#fn-specrealmwithdirectgrantflow)
    * [`fn withDisplayName(displayName)`](#fn-specrealmwithdisplayname)
    * [`fn withDisplayNameHtml(displayNameHtml)`](#fn-specrealmwithdisplaynamehtml)
    * [`fn withDockerAuthenticationFlow(dockerAuthenticationFlow)`](#fn-specrealmwithdockerauthenticationflow)
    * [`fn withDuplicateEmailsAllowed(duplicateEmailsAllowed)`](#fn-specrealmwithduplicateemailsallowed)
    * [`fn withEditUsernameAllowed(editUsernameAllowed)`](#fn-specrealmwitheditusernameallowed)
    * [`fn withEmailTheme(emailTheme)`](#fn-specrealmwithemailtheme)
    * [`fn withEnabled(enabled)`](#fn-specrealmwithenabled)
    * [`fn withEnabledEventTypes(enabledEventTypes)`](#fn-specrealmwithenabledeventtypes)
    * [`fn withEnabledEventTypesMixin(enabledEventTypes)`](#fn-specrealmwithenabledeventtypesmixin)
    * [`fn withEventsEnabled(eventsEnabled)`](#fn-specrealmwitheventsenabled)
    * [`fn withEventsExpiration(eventsExpiration)`](#fn-specrealmwitheventsexpiration)
    * [`fn withEventsListeners(eventsListeners)`](#fn-specrealmwitheventslisteners)
    * [`fn withEventsListenersMixin(eventsListeners)`](#fn-specrealmwitheventslistenersmixin)
    * [`fn withFailureFactor(failureFactor)`](#fn-specrealmwithfailurefactor)
    * [`fn withFederatedUsers(federatedUsers)`](#fn-specrealmwithfederatedusers)
    * [`fn withFederatedUsersMixin(federatedUsers)`](#fn-specrealmwithfederatedusersmixin)
    * [`fn withFirstBrokerLoginFlow(firstBrokerLoginFlow)`](#fn-specrealmwithfirstbrokerloginflow)
    * [`fn withGroups(groups)`](#fn-specrealmwithgroups)
    * [`fn withGroupsMixin(groups)`](#fn-specrealmwithgroupsmixin)
    * [`fn withId(id)`](#fn-specrealmwithid)
    * [`fn withIdentityProviderMappers(identityProviderMappers)`](#fn-specrealmwithidentityprovidermappers)
    * [`fn withIdentityProviderMappersMixin(identityProviderMappers)`](#fn-specrealmwithidentityprovidermappersmixin)
    * [`fn withIdentityProviders(identityProviders)`](#fn-specrealmwithidentityproviders)
    * [`fn withIdentityProvidersMixin(identityProviders)`](#fn-specrealmwithidentityprovidersmixin)
    * [`fn withInternationalizationEnabled(internationalizationEnabled)`](#fn-specrealmwithinternationalizationenabled)
    * [`fn withKeycloakVersion(keycloakVersion)`](#fn-specrealmwithkeycloakversion)
    * [`fn withLocalizationTexts(localizationTexts)`](#fn-specrealmwithlocalizationtexts)
    * [`fn withLocalizationTextsMixin(localizationTexts)`](#fn-specrealmwithlocalizationtextsmixin)
    * [`fn withLoginTheme(loginTheme)`](#fn-specrealmwithlogintheme)
    * [`fn withLoginWithEmailAllowed(loginWithEmailAllowed)`](#fn-specrealmwithloginwithemailallowed)
    * [`fn withMaxDeltaTimeSeconds(maxDeltaTimeSeconds)`](#fn-specrealmwithmaxdeltatimeseconds)
    * [`fn withMaxFailureWaitSeconds(maxFailureWaitSeconds)`](#fn-specrealmwithmaxfailurewaitseconds)
    * [`fn withMaxTemporaryLockouts(maxTemporaryLockouts)`](#fn-specrealmwithmaxtemporarylockouts)
    * [`fn withMinimumQuickLoginWaitSeconds(minimumQuickLoginWaitSeconds)`](#fn-specrealmwithminimumquickloginwaitseconds)
    * [`fn withNotBefore(notBefore)`](#fn-specrealmwithnotbefore)
    * [`fn withOauth2DeviceCodeLifespan(oauth2DeviceCodeLifespan)`](#fn-specrealmwithoauth2devicecodelifespan)
    * [`fn withOauth2DevicePollingInterval(oauth2DevicePollingInterval)`](#fn-specrealmwithoauth2devicepollinginterval)
    * [`fn withOauthClients(oauthClients)`](#fn-specrealmwithoauthclients)
    * [`fn withOauthClientsMixin(oauthClients)`](#fn-specrealmwithoauthclientsmixin)
    * [`fn withOfflineSessionIdleTimeout(offlineSessionIdleTimeout)`](#fn-specrealmwithofflinesessionidletimeout)
    * [`fn withOfflineSessionMaxLifespan(offlineSessionMaxLifespan)`](#fn-specrealmwithofflinesessionmaxlifespan)
    * [`fn withOfflineSessionMaxLifespanEnabled(offlineSessionMaxLifespanEnabled)`](#fn-specrealmwithofflinesessionmaxlifespanenabled)
    * [`fn withOrganizations(organizations)`](#fn-specrealmwithorganizations)
    * [`fn withOrganizationsEnabled(organizationsEnabled)`](#fn-specrealmwithorganizationsenabled)
    * [`fn withOrganizationsMixin(organizations)`](#fn-specrealmwithorganizationsmixin)
    * [`fn withOtpPolicyAlgorithm(otpPolicyAlgorithm)`](#fn-specrealmwithotppolicyalgorithm)
    * [`fn withOtpPolicyCodeReusable(otpPolicyCodeReusable)`](#fn-specrealmwithotppolicycodereusable)
    * [`fn withOtpPolicyDigits(otpPolicyDigits)`](#fn-specrealmwithotppolicydigits)
    * [`fn withOtpPolicyInitialCounter(otpPolicyInitialCounter)`](#fn-specrealmwithotppolicyinitialcounter)
    * [`fn withOtpPolicyLookAheadWindow(otpPolicyLookAheadWindow)`](#fn-specrealmwithotppolicylookaheadwindow)
    * [`fn withOtpPolicyPeriod(otpPolicyPeriod)`](#fn-specrealmwithotppolicyperiod)
    * [`fn withOtpPolicyType(otpPolicyType)`](#fn-specrealmwithotppolicytype)
    * [`fn withOtpSupportedApplications(otpSupportedApplications)`](#fn-specrealmwithotpsupportedapplications)
    * [`fn withOtpSupportedApplicationsMixin(otpSupportedApplications)`](#fn-specrealmwithotpsupportedapplicationsmixin)
    * [`fn withPasswordCredentialGrantAllowed(passwordCredentialGrantAllowed)`](#fn-specrealmwithpasswordcredentialgrantallowed)
    * [`fn withPasswordPolicy(passwordPolicy)`](#fn-specrealmwithpasswordpolicy)
    * [`fn withPermanentLockout(permanentLockout)`](#fn-specrealmwithpermanentlockout)
    * [`fn withPrivateKey(privateKey)`](#fn-specrealmwithprivatekey)
    * [`fn withProtocolMappers(protocolMappers)`](#fn-specrealmwithprotocolmappers)
    * [`fn withProtocolMappersMixin(protocolMappers)`](#fn-specrealmwithprotocolmappersmixin)
    * [`fn withPublicKey(publicKey)`](#fn-specrealmwithpublickey)
    * [`fn withQuickLoginCheckMilliSeconds(quickLoginCheckMilliSeconds)`](#fn-specrealmwithquicklogincheckmilliseconds)
    * [`fn withRealm(realm)`](#fn-specrealmwithrealm)
    * [`fn withRefreshTokenMaxReuse(refreshTokenMaxReuse)`](#fn-specrealmwithrefreshtokenmaxreuse)
    * [`fn withRegistrationAllowed(registrationAllowed)`](#fn-specrealmwithregistrationallowed)
    * [`fn withRegistrationEmailAsUsername(registrationEmailAsUsername)`](#fn-specrealmwithregistrationemailasusername)
    * [`fn withRegistrationFlow(registrationFlow)`](#fn-specrealmwithregistrationflow)
    * [`fn withRememberMe(rememberMe)`](#fn-specrealmwithrememberme)
    * [`fn withRequiredActions(requiredActions)`](#fn-specrealmwithrequiredactions)
    * [`fn withRequiredActionsMixin(requiredActions)`](#fn-specrealmwithrequiredactionsmixin)
    * [`fn withRequiredCredentials(requiredCredentials)`](#fn-specrealmwithrequiredcredentials)
    * [`fn withRequiredCredentialsMixin(requiredCredentials)`](#fn-specrealmwithrequiredcredentialsmixin)
    * [`fn withResetCredentialsFlow(resetCredentialsFlow)`](#fn-specrealmwithresetcredentialsflow)
    * [`fn withResetPasswordAllowed(resetPasswordAllowed)`](#fn-specrealmwithresetpasswordallowed)
    * [`fn withRevokeRefreshToken(revokeRefreshToken)`](#fn-specrealmwithrevokerefreshtoken)
    * [`fn withScopeMappings(scopeMappings)`](#fn-specrealmwithscopemappings)
    * [`fn withScopeMappingsMixin(scopeMappings)`](#fn-specrealmwithscopemappingsmixin)
    * [`fn withSmtpServer(smtpServer)`](#fn-specrealmwithsmtpserver)
    * [`fn withSmtpServerMixin(smtpServer)`](#fn-specrealmwithsmtpservermixin)
    * [`fn withSocial(social)`](#fn-specrealmwithsocial)
    * [`fn withSocialProviders(socialProviders)`](#fn-specrealmwithsocialproviders)
    * [`fn withSocialProvidersMixin(socialProviders)`](#fn-specrealmwithsocialprovidersmixin)
    * [`fn withSslRequired(sslRequired)`](#fn-specrealmwithsslrequired)
    * [`fn withSsoSessionIdleTimeout(ssoSessionIdleTimeout)`](#fn-specrealmwithssosessionidletimeout)
    * [`fn withSsoSessionIdleTimeoutRememberMe(ssoSessionIdleTimeoutRememberMe)`](#fn-specrealmwithssosessionidletimeoutrememberme)
    * [`fn withSsoSessionMaxLifespan(ssoSessionMaxLifespan)`](#fn-specrealmwithssosessionmaxlifespan)
    * [`fn withSsoSessionMaxLifespanRememberMe(ssoSessionMaxLifespanRememberMe)`](#fn-specrealmwithssosessionmaxlifespanrememberme)
    * [`fn withSupportedLocales(supportedLocales)`](#fn-specrealmwithsupportedlocales)
    * [`fn withSupportedLocalesMixin(supportedLocales)`](#fn-specrealmwithsupportedlocalesmixin)
    * [`fn withUpdateProfileOnInitialSocialLogin(updateProfileOnInitialSocialLogin)`](#fn-specrealmwithupdateprofileoninitialsociallogin)
    * [`fn withUserFederationMappers(userFederationMappers)`](#fn-specrealmwithuserfederationmappers)
    * [`fn withUserFederationMappersMixin(userFederationMappers)`](#fn-specrealmwithuserfederationmappersmixin)
    * [`fn withUserFederationProviders(userFederationProviders)`](#fn-specrealmwithuserfederationproviders)
    * [`fn withUserFederationProvidersMixin(userFederationProviders)`](#fn-specrealmwithuserfederationprovidersmixin)
    * [`fn withUserManagedAccessAllowed(userManagedAccessAllowed)`](#fn-specrealmwithusermanagedaccessallowed)
    * [`fn withUsers(users)`](#fn-specrealmwithusers)
    * [`fn withUsersMixin(users)`](#fn-specrealmwithusersmixin)
    * [`fn withVerifiableCredentialsEnabled(verifiableCredentialsEnabled)`](#fn-specrealmwithverifiablecredentialsenabled)
    * [`fn withVerifyEmail(verifyEmail)`](#fn-specrealmwithverifyemail)
    * [`fn withWaitIncrementSeconds(waitIncrementSeconds)`](#fn-specrealmwithwaitincrementseconds)
    * [`fn withWebAuthnPolicyAcceptableAaguids(webAuthnPolicyAcceptableAaguids)`](#fn-specrealmwithwebauthnpolicyacceptableaaguids)
    * [`fn withWebAuthnPolicyAcceptableAaguidsMixin(webAuthnPolicyAcceptableAaguids)`](#fn-specrealmwithwebauthnpolicyacceptableaaguidsmixin)
    * [`fn withWebAuthnPolicyAttestationConveyancePreference(webAuthnPolicyAttestationConveyancePreference)`](#fn-specrealmwithwebauthnpolicyattestationconveyancepreference)
    * [`fn withWebAuthnPolicyAuthenticatorAttachment(webAuthnPolicyAuthenticatorAttachment)`](#fn-specrealmwithwebauthnpolicyauthenticatorattachment)
    * [`fn withWebAuthnPolicyAvoidSameAuthenticatorRegister(webAuthnPolicyAvoidSameAuthenticatorRegister)`](#fn-specrealmwithwebauthnpolicyavoidsameauthenticatorregister)
    * [`fn withWebAuthnPolicyCreateTimeout(webAuthnPolicyCreateTimeout)`](#fn-specrealmwithwebauthnpolicycreatetimeout)
    * [`fn withWebAuthnPolicyExtraOrigins(webAuthnPolicyExtraOrigins)`](#fn-specrealmwithwebauthnpolicyextraorigins)
    * [`fn withWebAuthnPolicyExtraOriginsMixin(webAuthnPolicyExtraOrigins)`](#fn-specrealmwithwebauthnpolicyextraoriginsmixin)
    * [`fn withWebAuthnPolicyPasswordlessAcceptableAaguids(webAuthnPolicyPasswordlessAcceptableAaguids)`](#fn-specrealmwithwebauthnpolicypasswordlessacceptableaaguids)
    * [`fn withWebAuthnPolicyPasswordlessAcceptableAaguidsMixin(webAuthnPolicyPasswordlessAcceptableAaguids)`](#fn-specrealmwithwebauthnpolicypasswordlessacceptableaaguidsmixin)
    * [`fn withWebAuthnPolicyPasswordlessAttestationConveyancePreference(webAuthnPolicyPasswordlessAttestationConveyancePreference)`](#fn-specrealmwithwebauthnpolicypasswordlessattestationconveyancepreference)
    * [`fn withWebAuthnPolicyPasswordlessAuthenticatorAttachment(webAuthnPolicyPasswordlessAuthenticatorAttachment)`](#fn-specrealmwithwebauthnpolicypasswordlessauthenticatorattachment)
    * [`fn withWebAuthnPolicyPasswordlessAvoidSameAuthenticatorRegister(webAuthnPolicyPasswordlessAvoidSameAuthenticatorRegister)`](#fn-specrealmwithwebauthnpolicypasswordlessavoidsameauthenticatorregister)
    * [`fn withWebAuthnPolicyPasswordlessCreateTimeout(webAuthnPolicyPasswordlessCreateTimeout)`](#fn-specrealmwithwebauthnpolicypasswordlesscreatetimeout)
    * [`fn withWebAuthnPolicyPasswordlessExtraOrigins(webAuthnPolicyPasswordlessExtraOrigins)`](#fn-specrealmwithwebauthnpolicypasswordlessextraorigins)
    * [`fn withWebAuthnPolicyPasswordlessExtraOriginsMixin(webAuthnPolicyPasswordlessExtraOrigins)`](#fn-specrealmwithwebauthnpolicypasswordlessextraoriginsmixin)
    * [`fn withWebAuthnPolicyPasswordlessPasskeysEnabled(webAuthnPolicyPasswordlessPasskeysEnabled)`](#fn-specrealmwithwebauthnpolicypasswordlesspasskeysenabled)
    * [`fn withWebAuthnPolicyPasswordlessRequireResidentKey(webAuthnPolicyPasswordlessRequireResidentKey)`](#fn-specrealmwithwebauthnpolicypasswordlessrequireresidentkey)
    * [`fn withWebAuthnPolicyPasswordlessRpEntityName(webAuthnPolicyPasswordlessRpEntityName)`](#fn-specrealmwithwebauthnpolicypasswordlessrpentityname)
    * [`fn withWebAuthnPolicyPasswordlessRpId(webAuthnPolicyPasswordlessRpId)`](#fn-specrealmwithwebauthnpolicypasswordlessrpid)
    * [`fn withWebAuthnPolicyPasswordlessSignatureAlgorithms(webAuthnPolicyPasswordlessSignatureAlgorithms)`](#fn-specrealmwithwebauthnpolicypasswordlesssignaturealgorithms)
    * [`fn withWebAuthnPolicyPasswordlessSignatureAlgorithmsMixin(webAuthnPolicyPasswordlessSignatureAlgorithms)`](#fn-specrealmwithwebauthnpolicypasswordlesssignaturealgorithmsmixin)
    * [`fn withWebAuthnPolicyPasswordlessUserVerificationRequirement(webAuthnPolicyPasswordlessUserVerificationRequirement)`](#fn-specrealmwithwebauthnpolicypasswordlessuserverificationrequirement)
    * [`fn withWebAuthnPolicyRequireResidentKey(webAuthnPolicyRequireResidentKey)`](#fn-specrealmwithwebauthnpolicyrequireresidentkey)
    * [`fn withWebAuthnPolicyRpEntityName(webAuthnPolicyRpEntityName)`](#fn-specrealmwithwebauthnpolicyrpentityname)
    * [`fn withWebAuthnPolicyRpId(webAuthnPolicyRpId)`](#fn-specrealmwithwebauthnpolicyrpid)
    * [`fn withWebAuthnPolicySignatureAlgorithms(webAuthnPolicySignatureAlgorithms)`](#fn-specrealmwithwebauthnpolicysignaturealgorithms)
    * [`fn withWebAuthnPolicySignatureAlgorithmsMixin(webAuthnPolicySignatureAlgorithms)`](#fn-specrealmwithwebauthnpolicysignaturealgorithmsmixin)
    * [`fn withWebAuthnPolicyUserVerificationRequirement(webAuthnPolicyUserVerificationRequirement)`](#fn-specrealmwithwebauthnpolicyuserverificationrequirement)
    * [`obj spec.realm.adminPermissionsClient`](#obj-specrealmadminpermissionsclient)
      * [`fn withAccess(access)`](#fn-specrealmadminpermissionsclientwithaccess)
      * [`fn withAccessMixin(access)`](#fn-specrealmadminpermissionsclientwithaccessmixin)
      * [`fn withAdminUrl(adminUrl)`](#fn-specrealmadminpermissionsclientwithadminurl)
      * [`fn withAlwaysDisplayInConsole(alwaysDisplayInConsole)`](#fn-specrealmadminpermissionsclientwithalwaysdisplayinconsole)
      * [`fn withAttributes(attributes)`](#fn-specrealmadminpermissionsclientwithattributes)
      * [`fn withAttributesMixin(attributes)`](#fn-specrealmadminpermissionsclientwithattributesmixin)
      * [`fn withAuthenticationFlowBindingOverrides(authenticationFlowBindingOverrides)`](#fn-specrealmadminpermissionsclientwithauthenticationflowbindingoverrides)
      * [`fn withAuthenticationFlowBindingOverridesMixin(authenticationFlowBindingOverrides)`](#fn-specrealmadminpermissionsclientwithauthenticationflowbindingoverridesmixin)
      * [`fn withAuthorizationServicesEnabled(authorizationServicesEnabled)`](#fn-specrealmadminpermissionsclientwithauthorizationservicesenabled)
      * [`fn withBaseUrl(baseUrl)`](#fn-specrealmadminpermissionsclientwithbaseurl)
      * [`fn withBearerOnly(bearerOnly)`](#fn-specrealmadminpermissionsclientwithbeareronly)
      * [`fn withClientAuthenticatorType(clientAuthenticatorType)`](#fn-specrealmadminpermissionsclientwithclientauthenticatortype)
      * [`fn withClientId(clientId)`](#fn-specrealmadminpermissionsclientwithclientid)
      * [`fn withClientTemplate(clientTemplate)`](#fn-specrealmadminpermissionsclientwithclienttemplate)
      * [`fn withConsentRequired(consentRequired)`](#fn-specrealmadminpermissionsclientwithconsentrequired)
      * [`fn withDefaultClientScopes(defaultClientScopes)`](#fn-specrealmadminpermissionsclientwithdefaultclientscopes)
      * [`fn withDefaultClientScopesMixin(defaultClientScopes)`](#fn-specrealmadminpermissionsclientwithdefaultclientscopesmixin)
      * [`fn withDefaultRoles(defaultRoles)`](#fn-specrealmadminpermissionsclientwithdefaultroles)
      * [`fn withDefaultRolesMixin(defaultRoles)`](#fn-specrealmadminpermissionsclientwithdefaultrolesmixin)
      * [`fn withDescription(description)`](#fn-specrealmadminpermissionsclientwithdescription)
      * [`fn withDirectAccessGrantsEnabled(directAccessGrantsEnabled)`](#fn-specrealmadminpermissionsclientwithdirectaccessgrantsenabled)
      * [`fn withDirectGrantsOnly(directGrantsOnly)`](#fn-specrealmadminpermissionsclientwithdirectgrantsonly)
      * [`fn withEnabled(enabled)`](#fn-specrealmadminpermissionsclientwithenabled)
      * [`fn withFrontchannelLogout(frontchannelLogout)`](#fn-specrealmadminpermissionsclientwithfrontchannellogout)
      * [`fn withFullScopeAllowed(fullScopeAllowed)`](#fn-specrealmadminpermissionsclientwithfullscopeallowed)
      * [`fn withId(id)`](#fn-specrealmadminpermissionsclientwithid)
      * [`fn withImplicitFlowEnabled(implicitFlowEnabled)`](#fn-specrealmadminpermissionsclientwithimplicitflowenabled)
      * [`fn withName(name)`](#fn-specrealmadminpermissionsclientwithname)
      * [`fn withNodeReRegistrationTimeout(nodeReRegistrationTimeout)`](#fn-specrealmadminpermissionsclientwithnodereregistrationtimeout)
      * [`fn withNotBefore(notBefore)`](#fn-specrealmadminpermissionsclientwithnotbefore)
      * [`fn withOptionalClientScopes(optionalClientScopes)`](#fn-specrealmadminpermissionsclientwithoptionalclientscopes)
      * [`fn withOptionalClientScopesMixin(optionalClientScopes)`](#fn-specrealmadminpermissionsclientwithoptionalclientscopesmixin)
      * [`fn withOrigin(origin)`](#fn-specrealmadminpermissionsclientwithorigin)
      * [`fn withProtocol(protocol)`](#fn-specrealmadminpermissionsclientwithprotocol)
      * [`fn withProtocolMappers(protocolMappers)`](#fn-specrealmadminpermissionsclientwithprotocolmappers)
      * [`fn withProtocolMappersMixin(protocolMappers)`](#fn-specrealmadminpermissionsclientwithprotocolmappersmixin)
      * [`fn withPublicClient(publicClient)`](#fn-specrealmadminpermissionsclientwithpublicclient)
      * [`fn withRedirectUris(redirectUris)`](#fn-specrealmadminpermissionsclientwithredirecturis)
      * [`fn withRedirectUrisMixin(redirectUris)`](#fn-specrealmadminpermissionsclientwithredirecturismixin)
      * [`fn withRegisteredNodes(registeredNodes)`](#fn-specrealmadminpermissionsclientwithregisterednodes)
      * [`fn withRegisteredNodesMixin(registeredNodes)`](#fn-specrealmadminpermissionsclientwithregisterednodesmixin)
      * [`fn withRegistrationAccessToken(registrationAccessToken)`](#fn-specrealmadminpermissionsclientwithregistrationaccesstoken)
      * [`fn withRootUrl(rootUrl)`](#fn-specrealmadminpermissionsclientwithrooturl)
      * [`fn withSecret(secret)`](#fn-specrealmadminpermissionsclientwithsecret)
      * [`fn withServiceAccountsEnabled(serviceAccountsEnabled)`](#fn-specrealmadminpermissionsclientwithserviceaccountsenabled)
      * [`fn withStandardFlowEnabled(standardFlowEnabled)`](#fn-specrealmadminpermissionsclientwithstandardflowenabled)
      * [`fn withSurrogateAuthRequired(surrogateAuthRequired)`](#fn-specrealmadminpermissionsclientwithsurrogateauthrequired)
      * [`fn withType(type)`](#fn-specrealmadminpermissionsclientwithtype)
      * [`fn withUseTemplateConfig(useTemplateConfig)`](#fn-specrealmadminpermissionsclientwithusetemplateconfig)
      * [`fn withUseTemplateMappers(useTemplateMappers)`](#fn-specrealmadminpermissionsclientwithusetemplatemappers)
      * [`fn withUseTemplateScope(useTemplateScope)`](#fn-specrealmadminpermissionsclientwithusetemplatescope)
      * [`fn withWebOrigins(webOrigins)`](#fn-specrealmadminpermissionsclientwithweborigins)
      * [`fn withWebOriginsMixin(webOrigins)`](#fn-specrealmadminpermissionsclientwithweboriginsmixin)
      * [`obj spec.realm.adminPermissionsClient.authorizationSettings`](#obj-specrealmadminpermissionsclientauthorizationsettings)
        * [`fn withAllowRemoteResourceManagement(allowRemoteResourceManagement)`](#fn-specrealmadminpermissionsclientauthorizationsettingswithallowremoteresourcemanagement)
        * [`fn withClientId(clientId)`](#fn-specrealmadminpermissionsclientauthorizationsettingswithclientid)
        * [`fn withDecisionStrategy(decisionStrategy)`](#fn-specrealmadminpermissionsclientauthorizationsettingswithdecisionstrategy)
        * [`fn withId(id)`](#fn-specrealmadminpermissionsclientauthorizationsettingswithid)
        * [`fn withName(name)`](#fn-specrealmadminpermissionsclientauthorizationsettingswithname)
        * [`fn withPolicies(policies)`](#fn-specrealmadminpermissionsclientauthorizationsettingswithpolicies)
        * [`fn withPoliciesMixin(policies)`](#fn-specrealmadminpermissionsclientauthorizationsettingswithpoliciesmixin)
        * [`fn withPolicyEnforcementMode(policyEnforcementMode)`](#fn-specrealmadminpermissionsclientauthorizationsettingswithpolicyenforcementmode)
        * [`fn withResources(resources)`](#fn-specrealmadminpermissionsclientauthorizationsettingswithresources)
        * [`fn withResourcesMixin(resources)`](#fn-specrealmadminpermissionsclientauthorizationsettingswithresourcesmixin)
        * [`fn withScopes(scopes)`](#fn-specrealmadminpermissionsclientauthorizationsettingswithscopes)
        * [`fn withScopesMixin(scopes)`](#fn-specrealmadminpermissionsclientauthorizationsettingswithscopesmixin)
        * [`obj spec.realm.adminPermissionsClient.authorizationSettings.authorizationSchema`](#obj-specrealmadminpermissionsclientauthorizationsettingsauthorizationschema)
          * [`fn withResourceTypes(resourceTypes)`](#fn-specrealmadminpermissionsclientauthorizationsettingsauthorizationschemawithresourcetypes)
          * [`fn withResourceTypesMixin(resourceTypes)`](#fn-specrealmadminpermissionsclientauthorizationsettingsauthorizationschemawithresourcetypesmixin)
        * [`obj spec.realm.adminPermissionsClient.authorizationSettings.policies`](#obj-specrealmadminpermissionsclientauthorizationsettingspolicies)
          * [`fn withConfig(config)`](#fn-specrealmadminpermissionsclientauthorizationsettingspolicieswithconfig)
          * [`fn withConfigMixin(config)`](#fn-specrealmadminpermissionsclientauthorizationsettingspolicieswithconfigmixin)
          * [`fn withDecisionStrategy(decisionStrategy)`](#fn-specrealmadminpermissionsclientauthorizationsettingspolicieswithdecisionstrategy)
          * [`fn withDescription(description)`](#fn-specrealmadminpermissionsclientauthorizationsettingspolicieswithdescription)
          * [`fn withId(id)`](#fn-specrealmadminpermissionsclientauthorizationsettingspolicieswithid)
          * [`fn withLogic(logic)`](#fn-specrealmadminpermissionsclientauthorizationsettingspolicieswithlogic)
          * [`fn withName(name)`](#fn-specrealmadminpermissionsclientauthorizationsettingspolicieswithname)
          * [`fn withOwner(owner)`](#fn-specrealmadminpermissionsclientauthorizationsettingspolicieswithowner)
          * [`fn withPolicies(policies)`](#fn-specrealmadminpermissionsclientauthorizationsettingspolicieswithpolicies)
          * [`fn withPoliciesMixin(policies)`](#fn-specrealmadminpermissionsclientauthorizationsettingspolicieswithpoliciesmixin)
          * [`fn withResourceType(resourceType)`](#fn-specrealmadminpermissionsclientauthorizationsettingspolicieswithresourcetype)
          * [`fn withResources(resources)`](#fn-specrealmadminpermissionsclientauthorizationsettingspolicieswithresources)
          * [`fn withResourcesData(resourcesData)`](#fn-specrealmadminpermissionsclientauthorizationsettingspolicieswithresourcesdata)
          * [`fn withResourcesDataMixin(resourcesData)`](#fn-specrealmadminpermissionsclientauthorizationsettingspolicieswithresourcesdatamixin)
          * [`fn withResourcesMixin(resources)`](#fn-specrealmadminpermissionsclientauthorizationsettingspolicieswithresourcesmixin)
          * [`fn withScopes(scopes)`](#fn-specrealmadminpermissionsclientauthorizationsettingspolicieswithscopes)
          * [`fn withScopesData(scopesData)`](#fn-specrealmadminpermissionsclientauthorizationsettingspolicieswithscopesdata)
          * [`fn withScopesDataMixin(scopesData)`](#fn-specrealmadminpermissionsclientauthorizationsettingspolicieswithscopesdatamixin)
          * [`fn withScopesMixin(scopes)`](#fn-specrealmadminpermissionsclientauthorizationsettingspolicieswithscopesmixin)
          * [`fn withType(type)`](#fn-specrealmadminpermissionsclientauthorizationsettingspolicieswithtype)
          * [`obj spec.realm.adminPermissionsClient.authorizationSettings.policies.resourcesData`](#obj-specrealmadminpermissionsclientauthorizationsettingspoliciesresourcesdata)
            * [`fn withAttributes(attributes)`](#fn-specrealmadminpermissionsclientauthorizationsettingspoliciesresourcesdatawithattributes)
            * [`fn withAttributesMixin(attributes)`](#fn-specrealmadminpermissionsclientauthorizationsettingspoliciesresourcesdatawithattributesmixin)
            * [`fn withDisplayName(displayName)`](#fn-specrealmadminpermissionsclientauthorizationsettingspoliciesresourcesdatawithdisplayname)
            * [`fn withIcon_uri(icon_uri)`](#fn-specrealmadminpermissionsclientauthorizationsettingspoliciesresourcesdatawithicon_uri)
            * [`fn withName(name)`](#fn-specrealmadminpermissionsclientauthorizationsettingspoliciesresourcesdatawithname)
            * [`fn withOwnerManagedAccess(ownerManagedAccess)`](#fn-specrealmadminpermissionsclientauthorizationsettingspoliciesresourcesdatawithownermanagedaccess)
            * [`fn withScopes(scopes)`](#fn-specrealmadminpermissionsclientauthorizationsettingspoliciesresourcesdatawithscopes)
            * [`fn withScopesMixin(scopes)`](#fn-specrealmadminpermissionsclientauthorizationsettingspoliciesresourcesdatawithscopesmixin)
            * [`fn withType(type)`](#fn-specrealmadminpermissionsclientauthorizationsettingspoliciesresourcesdatawithtype)
            * [`fn withUris(uris)`](#fn-specrealmadminpermissionsclientauthorizationsettingspoliciesresourcesdatawithuris)
            * [`fn withUrisMixin(uris)`](#fn-specrealmadminpermissionsclientauthorizationsettingspoliciesresourcesdatawithurismixin)
            * [`fn with_id(_id)`](#fn-specrealmadminpermissionsclientauthorizationsettingspoliciesresourcesdatawith_id)
            * [`obj spec.realm.adminPermissionsClient.authorizationSettings.policies.resourcesData.owner`](#obj-specrealmadminpermissionsclientauthorizationsettingspoliciesresourcesdataowner)
              * [`fn withId(id)`](#fn-specrealmadminpermissionsclientauthorizationsettingspoliciesresourcesdataownerwithid)
              * [`fn withName(name)`](#fn-specrealmadminpermissionsclientauthorizationsettingspoliciesresourcesdataownerwithname)
            * [`obj spec.realm.adminPermissionsClient.authorizationSettings.policies.resourcesData.scopes`](#obj-specrealmadminpermissionsclientauthorizationsettingspoliciesresourcesdatascopes)
              * [`fn withDisplayName(displayName)`](#fn-specrealmadminpermissionsclientauthorizationsettingspoliciesresourcesdatascopeswithdisplayname)
              * [`fn withIconUri(iconUri)`](#fn-specrealmadminpermissionsclientauthorizationsettingspoliciesresourcesdatascopeswithiconuri)
              * [`fn withId(id)`](#fn-specrealmadminpermissionsclientauthorizationsettingspoliciesresourcesdatascopeswithid)
              * [`fn withName(name)`](#fn-specrealmadminpermissionsclientauthorizationsettingspoliciesresourcesdatascopeswithname)
          * [`obj spec.realm.adminPermissionsClient.authorizationSettings.policies.scopesData`](#obj-specrealmadminpermissionsclientauthorizationsettingspoliciesscopesdata)
            * [`fn withDisplayName(displayName)`](#fn-specrealmadminpermissionsclientauthorizationsettingspoliciesscopesdatawithdisplayname)
            * [`fn withIconUri(iconUri)`](#fn-specrealmadminpermissionsclientauthorizationsettingspoliciesscopesdatawithiconuri)
            * [`fn withId(id)`](#fn-specrealmadminpermissionsclientauthorizationsettingspoliciesscopesdatawithid)
            * [`fn withName(name)`](#fn-specrealmadminpermissionsclientauthorizationsettingspoliciesscopesdatawithname)
        * [`obj spec.realm.adminPermissionsClient.authorizationSettings.resources`](#obj-specrealmadminpermissionsclientauthorizationsettingsresources)
          * [`fn withAttributes(attributes)`](#fn-specrealmadminpermissionsclientauthorizationsettingsresourceswithattributes)
          * [`fn withAttributesMixin(attributes)`](#fn-specrealmadminpermissionsclientauthorizationsettingsresourceswithattributesmixin)
          * [`fn withDisplayName(displayName)`](#fn-specrealmadminpermissionsclientauthorizationsettingsresourceswithdisplayname)
          * [`fn withIcon_uri(icon_uri)`](#fn-specrealmadminpermissionsclientauthorizationsettingsresourceswithicon_uri)
          * [`fn withName(name)`](#fn-specrealmadminpermissionsclientauthorizationsettingsresourceswithname)
          * [`fn withOwnerManagedAccess(ownerManagedAccess)`](#fn-specrealmadminpermissionsclientauthorizationsettingsresourceswithownermanagedaccess)
          * [`fn withScopes(scopes)`](#fn-specrealmadminpermissionsclientauthorizationsettingsresourceswithscopes)
          * [`fn withScopesMixin(scopes)`](#fn-specrealmadminpermissionsclientauthorizationsettingsresourceswithscopesmixin)
          * [`fn withType(type)`](#fn-specrealmadminpermissionsclientauthorizationsettingsresourceswithtype)
          * [`fn withUris(uris)`](#fn-specrealmadminpermissionsclientauthorizationsettingsresourceswithuris)
          * [`fn withUrisMixin(uris)`](#fn-specrealmadminpermissionsclientauthorizationsettingsresourceswithurismixin)
          * [`fn with_id(_id)`](#fn-specrealmadminpermissionsclientauthorizationsettingsresourceswith_id)
          * [`obj spec.realm.adminPermissionsClient.authorizationSettings.resources.owner`](#obj-specrealmadminpermissionsclientauthorizationsettingsresourcesowner)
            * [`fn withId(id)`](#fn-specrealmadminpermissionsclientauthorizationsettingsresourcesownerwithid)
            * [`fn withName(name)`](#fn-specrealmadminpermissionsclientauthorizationsettingsresourcesownerwithname)
          * [`obj spec.realm.adminPermissionsClient.authorizationSettings.resources.scopes`](#obj-specrealmadminpermissionsclientauthorizationsettingsresourcesscopes)
            * [`fn withDisplayName(displayName)`](#fn-specrealmadminpermissionsclientauthorizationsettingsresourcesscopeswithdisplayname)
            * [`fn withIconUri(iconUri)`](#fn-specrealmadminpermissionsclientauthorizationsettingsresourcesscopeswithiconuri)
            * [`fn withId(id)`](#fn-specrealmadminpermissionsclientauthorizationsettingsresourcesscopeswithid)
            * [`fn withName(name)`](#fn-specrealmadminpermissionsclientauthorizationsettingsresourcesscopeswithname)
        * [`obj spec.realm.adminPermissionsClient.authorizationSettings.scopes`](#obj-specrealmadminpermissionsclientauthorizationsettingsscopes)
          * [`fn withDisplayName(displayName)`](#fn-specrealmadminpermissionsclientauthorizationsettingsscopeswithdisplayname)
          * [`fn withIconUri(iconUri)`](#fn-specrealmadminpermissionsclientauthorizationsettingsscopeswithiconuri)
          * [`fn withId(id)`](#fn-specrealmadminpermissionsclientauthorizationsettingsscopeswithid)
          * [`fn withName(name)`](#fn-specrealmadminpermissionsclientauthorizationsettingsscopeswithname)
      * [`obj spec.realm.adminPermissionsClient.protocolMappers`](#obj-specrealmadminpermissionsclientprotocolmappers)
        * [`fn withConfig(config)`](#fn-specrealmadminpermissionsclientprotocolmapperswithconfig)
        * [`fn withConfigMixin(config)`](#fn-specrealmadminpermissionsclientprotocolmapperswithconfigmixin)
        * [`fn withConsentRequired(consentRequired)`](#fn-specrealmadminpermissionsclientprotocolmapperswithconsentrequired)
        * [`fn withConsentText(consentText)`](#fn-specrealmadminpermissionsclientprotocolmapperswithconsenttext)
        * [`fn withId(id)`](#fn-specrealmadminpermissionsclientprotocolmapperswithid)
        * [`fn withName(name)`](#fn-specrealmadminpermissionsclientprotocolmapperswithname)
        * [`fn withProtocol(protocol)`](#fn-specrealmadminpermissionsclientprotocolmapperswithprotocol)
        * [`fn withProtocolMapper(protocolMapper)`](#fn-specrealmadminpermissionsclientprotocolmapperswithprotocolmapper)
    * [`obj spec.realm.applications`](#obj-specrealmapplications)
      * [`fn withAccess(access)`](#fn-specrealmapplicationswithaccess)
      * [`fn withAccessMixin(access)`](#fn-specrealmapplicationswithaccessmixin)
      * [`fn withAdminUrl(adminUrl)`](#fn-specrealmapplicationswithadminurl)
      * [`fn withAlwaysDisplayInConsole(alwaysDisplayInConsole)`](#fn-specrealmapplicationswithalwaysdisplayinconsole)
      * [`fn withAttributes(attributes)`](#fn-specrealmapplicationswithattributes)
      * [`fn withAttributesMixin(attributes)`](#fn-specrealmapplicationswithattributesmixin)
      * [`fn withAuthenticationFlowBindingOverrides(authenticationFlowBindingOverrides)`](#fn-specrealmapplicationswithauthenticationflowbindingoverrides)
      * [`fn withAuthenticationFlowBindingOverridesMixin(authenticationFlowBindingOverrides)`](#fn-specrealmapplicationswithauthenticationflowbindingoverridesmixin)
      * [`fn withAuthorizationServicesEnabled(authorizationServicesEnabled)`](#fn-specrealmapplicationswithauthorizationservicesenabled)
      * [`fn withBaseUrl(baseUrl)`](#fn-specrealmapplicationswithbaseurl)
      * [`fn withBearerOnly(bearerOnly)`](#fn-specrealmapplicationswithbeareronly)
      * [`fn withClientAuthenticatorType(clientAuthenticatorType)`](#fn-specrealmapplicationswithclientauthenticatortype)
      * [`fn withClientId(clientId)`](#fn-specrealmapplicationswithclientid)
      * [`fn withClientTemplate(clientTemplate)`](#fn-specrealmapplicationswithclienttemplate)
      * [`fn withConsentRequired(consentRequired)`](#fn-specrealmapplicationswithconsentrequired)
      * [`fn withDefaultClientScopes(defaultClientScopes)`](#fn-specrealmapplicationswithdefaultclientscopes)
      * [`fn withDefaultClientScopesMixin(defaultClientScopes)`](#fn-specrealmapplicationswithdefaultclientscopesmixin)
      * [`fn withDefaultRoles(defaultRoles)`](#fn-specrealmapplicationswithdefaultroles)
      * [`fn withDefaultRolesMixin(defaultRoles)`](#fn-specrealmapplicationswithdefaultrolesmixin)
      * [`fn withDescription(description)`](#fn-specrealmapplicationswithdescription)
      * [`fn withDirectAccessGrantsEnabled(directAccessGrantsEnabled)`](#fn-specrealmapplicationswithdirectaccessgrantsenabled)
      * [`fn withDirectGrantsOnly(directGrantsOnly)`](#fn-specrealmapplicationswithdirectgrantsonly)
      * [`fn withEnabled(enabled)`](#fn-specrealmapplicationswithenabled)
      * [`fn withFrontchannelLogout(frontchannelLogout)`](#fn-specrealmapplicationswithfrontchannellogout)
      * [`fn withFullScopeAllowed(fullScopeAllowed)`](#fn-specrealmapplicationswithfullscopeallowed)
      * [`fn withId(id)`](#fn-specrealmapplicationswithid)
      * [`fn withImplicitFlowEnabled(implicitFlowEnabled)`](#fn-specrealmapplicationswithimplicitflowenabled)
      * [`fn withName(name)`](#fn-specrealmapplicationswithname)
      * [`fn withNodeReRegistrationTimeout(nodeReRegistrationTimeout)`](#fn-specrealmapplicationswithnodereregistrationtimeout)
      * [`fn withNotBefore(notBefore)`](#fn-specrealmapplicationswithnotbefore)
      * [`fn withOptionalClientScopes(optionalClientScopes)`](#fn-specrealmapplicationswithoptionalclientscopes)
      * [`fn withOptionalClientScopesMixin(optionalClientScopes)`](#fn-specrealmapplicationswithoptionalclientscopesmixin)
      * [`fn withOrigin(origin)`](#fn-specrealmapplicationswithorigin)
      * [`fn withProtocol(protocol)`](#fn-specrealmapplicationswithprotocol)
      * [`fn withProtocolMappers(protocolMappers)`](#fn-specrealmapplicationswithprotocolmappers)
      * [`fn withProtocolMappersMixin(protocolMappers)`](#fn-specrealmapplicationswithprotocolmappersmixin)
      * [`fn withPublicClient(publicClient)`](#fn-specrealmapplicationswithpublicclient)
      * [`fn withRedirectUris(redirectUris)`](#fn-specrealmapplicationswithredirecturis)
      * [`fn withRedirectUrisMixin(redirectUris)`](#fn-specrealmapplicationswithredirecturismixin)
      * [`fn withRegisteredNodes(registeredNodes)`](#fn-specrealmapplicationswithregisterednodes)
      * [`fn withRegisteredNodesMixin(registeredNodes)`](#fn-specrealmapplicationswithregisterednodesmixin)
      * [`fn withRegistrationAccessToken(registrationAccessToken)`](#fn-specrealmapplicationswithregistrationaccesstoken)
      * [`fn withRootUrl(rootUrl)`](#fn-specrealmapplicationswithrooturl)
      * [`fn withSecret(secret)`](#fn-specrealmapplicationswithsecret)
      * [`fn withServiceAccountsEnabled(serviceAccountsEnabled)`](#fn-specrealmapplicationswithserviceaccountsenabled)
      * [`fn withStandardFlowEnabled(standardFlowEnabled)`](#fn-specrealmapplicationswithstandardflowenabled)
      * [`fn withSurrogateAuthRequired(surrogateAuthRequired)`](#fn-specrealmapplicationswithsurrogateauthrequired)
      * [`fn withType(type)`](#fn-specrealmapplicationswithtype)
      * [`fn withUseTemplateConfig(useTemplateConfig)`](#fn-specrealmapplicationswithusetemplateconfig)
      * [`fn withUseTemplateMappers(useTemplateMappers)`](#fn-specrealmapplicationswithusetemplatemappers)
      * [`fn withUseTemplateScope(useTemplateScope)`](#fn-specrealmapplicationswithusetemplatescope)
      * [`fn withWebOrigins(webOrigins)`](#fn-specrealmapplicationswithweborigins)
      * [`fn withWebOriginsMixin(webOrigins)`](#fn-specrealmapplicationswithweboriginsmixin)
      * [`obj spec.realm.applications.authorizationSettings`](#obj-specrealmapplicationsauthorizationsettings)
        * [`fn withAllowRemoteResourceManagement(allowRemoteResourceManagement)`](#fn-specrealmapplicationsauthorizationsettingswithallowremoteresourcemanagement)
        * [`fn withClientId(clientId)`](#fn-specrealmapplicationsauthorizationsettingswithclientid)
        * [`fn withDecisionStrategy(decisionStrategy)`](#fn-specrealmapplicationsauthorizationsettingswithdecisionstrategy)
        * [`fn withId(id)`](#fn-specrealmapplicationsauthorizationsettingswithid)
        * [`fn withName(name)`](#fn-specrealmapplicationsauthorizationsettingswithname)
        * [`fn withPolicies(policies)`](#fn-specrealmapplicationsauthorizationsettingswithpolicies)
        * [`fn withPoliciesMixin(policies)`](#fn-specrealmapplicationsauthorizationsettingswithpoliciesmixin)
        * [`fn withPolicyEnforcementMode(policyEnforcementMode)`](#fn-specrealmapplicationsauthorizationsettingswithpolicyenforcementmode)
        * [`fn withResources(resources)`](#fn-specrealmapplicationsauthorizationsettingswithresources)
        * [`fn withResourcesMixin(resources)`](#fn-specrealmapplicationsauthorizationsettingswithresourcesmixin)
        * [`fn withScopes(scopes)`](#fn-specrealmapplicationsauthorizationsettingswithscopes)
        * [`fn withScopesMixin(scopes)`](#fn-specrealmapplicationsauthorizationsettingswithscopesmixin)
        * [`obj spec.realm.applications.authorizationSettings.authorizationSchema`](#obj-specrealmapplicationsauthorizationsettingsauthorizationschema)
          * [`fn withResourceTypes(resourceTypes)`](#fn-specrealmapplicationsauthorizationsettingsauthorizationschemawithresourcetypes)
          * [`fn withResourceTypesMixin(resourceTypes)`](#fn-specrealmapplicationsauthorizationsettingsauthorizationschemawithresourcetypesmixin)
        * [`obj spec.realm.applications.authorizationSettings.policies`](#obj-specrealmapplicationsauthorizationsettingspolicies)
          * [`fn withConfig(config)`](#fn-specrealmapplicationsauthorizationsettingspolicieswithconfig)
          * [`fn withConfigMixin(config)`](#fn-specrealmapplicationsauthorizationsettingspolicieswithconfigmixin)
          * [`fn withDecisionStrategy(decisionStrategy)`](#fn-specrealmapplicationsauthorizationsettingspolicieswithdecisionstrategy)
          * [`fn withDescription(description)`](#fn-specrealmapplicationsauthorizationsettingspolicieswithdescription)
          * [`fn withId(id)`](#fn-specrealmapplicationsauthorizationsettingspolicieswithid)
          * [`fn withLogic(logic)`](#fn-specrealmapplicationsauthorizationsettingspolicieswithlogic)
          * [`fn withName(name)`](#fn-specrealmapplicationsauthorizationsettingspolicieswithname)
          * [`fn withOwner(owner)`](#fn-specrealmapplicationsauthorizationsettingspolicieswithowner)
          * [`fn withPolicies(policies)`](#fn-specrealmapplicationsauthorizationsettingspolicieswithpolicies)
          * [`fn withPoliciesMixin(policies)`](#fn-specrealmapplicationsauthorizationsettingspolicieswithpoliciesmixin)
          * [`fn withResourceType(resourceType)`](#fn-specrealmapplicationsauthorizationsettingspolicieswithresourcetype)
          * [`fn withResources(resources)`](#fn-specrealmapplicationsauthorizationsettingspolicieswithresources)
          * [`fn withResourcesData(resourcesData)`](#fn-specrealmapplicationsauthorizationsettingspolicieswithresourcesdata)
          * [`fn withResourcesDataMixin(resourcesData)`](#fn-specrealmapplicationsauthorizationsettingspolicieswithresourcesdatamixin)
          * [`fn withResourcesMixin(resources)`](#fn-specrealmapplicationsauthorizationsettingspolicieswithresourcesmixin)
          * [`fn withScopes(scopes)`](#fn-specrealmapplicationsauthorizationsettingspolicieswithscopes)
          * [`fn withScopesData(scopesData)`](#fn-specrealmapplicationsauthorizationsettingspolicieswithscopesdata)
          * [`fn withScopesDataMixin(scopesData)`](#fn-specrealmapplicationsauthorizationsettingspolicieswithscopesdatamixin)
          * [`fn withScopesMixin(scopes)`](#fn-specrealmapplicationsauthorizationsettingspolicieswithscopesmixin)
          * [`fn withType(type)`](#fn-specrealmapplicationsauthorizationsettingspolicieswithtype)
          * [`obj spec.realm.applications.authorizationSettings.policies.resourcesData`](#obj-specrealmapplicationsauthorizationsettingspoliciesresourcesdata)
            * [`fn withAttributes(attributes)`](#fn-specrealmapplicationsauthorizationsettingspoliciesresourcesdatawithattributes)
            * [`fn withAttributesMixin(attributes)`](#fn-specrealmapplicationsauthorizationsettingspoliciesresourcesdatawithattributesmixin)
            * [`fn withDisplayName(displayName)`](#fn-specrealmapplicationsauthorizationsettingspoliciesresourcesdatawithdisplayname)
            * [`fn withIcon_uri(icon_uri)`](#fn-specrealmapplicationsauthorizationsettingspoliciesresourcesdatawithicon_uri)
            * [`fn withName(name)`](#fn-specrealmapplicationsauthorizationsettingspoliciesresourcesdatawithname)
            * [`fn withOwnerManagedAccess(ownerManagedAccess)`](#fn-specrealmapplicationsauthorizationsettingspoliciesresourcesdatawithownermanagedaccess)
            * [`fn withScopes(scopes)`](#fn-specrealmapplicationsauthorizationsettingspoliciesresourcesdatawithscopes)
            * [`fn withScopesMixin(scopes)`](#fn-specrealmapplicationsauthorizationsettingspoliciesresourcesdatawithscopesmixin)
            * [`fn withType(type)`](#fn-specrealmapplicationsauthorizationsettingspoliciesresourcesdatawithtype)
            * [`fn withUris(uris)`](#fn-specrealmapplicationsauthorizationsettingspoliciesresourcesdatawithuris)
            * [`fn withUrisMixin(uris)`](#fn-specrealmapplicationsauthorizationsettingspoliciesresourcesdatawithurismixin)
            * [`fn with_id(_id)`](#fn-specrealmapplicationsauthorizationsettingspoliciesresourcesdatawith_id)
            * [`obj spec.realm.applications.authorizationSettings.policies.resourcesData.owner`](#obj-specrealmapplicationsauthorizationsettingspoliciesresourcesdataowner)
              * [`fn withId(id)`](#fn-specrealmapplicationsauthorizationsettingspoliciesresourcesdataownerwithid)
              * [`fn withName(name)`](#fn-specrealmapplicationsauthorizationsettingspoliciesresourcesdataownerwithname)
            * [`obj spec.realm.applications.authorizationSettings.policies.resourcesData.scopes`](#obj-specrealmapplicationsauthorizationsettingspoliciesresourcesdatascopes)
              * [`fn withDisplayName(displayName)`](#fn-specrealmapplicationsauthorizationsettingspoliciesresourcesdatascopeswithdisplayname)
              * [`fn withIconUri(iconUri)`](#fn-specrealmapplicationsauthorizationsettingspoliciesresourcesdatascopeswithiconuri)
              * [`fn withId(id)`](#fn-specrealmapplicationsauthorizationsettingspoliciesresourcesdatascopeswithid)
              * [`fn withName(name)`](#fn-specrealmapplicationsauthorizationsettingspoliciesresourcesdatascopeswithname)
          * [`obj spec.realm.applications.authorizationSettings.policies.scopesData`](#obj-specrealmapplicationsauthorizationsettingspoliciesscopesdata)
            * [`fn withDisplayName(displayName)`](#fn-specrealmapplicationsauthorizationsettingspoliciesscopesdatawithdisplayname)
            * [`fn withIconUri(iconUri)`](#fn-specrealmapplicationsauthorizationsettingspoliciesscopesdatawithiconuri)
            * [`fn withId(id)`](#fn-specrealmapplicationsauthorizationsettingspoliciesscopesdatawithid)
            * [`fn withName(name)`](#fn-specrealmapplicationsauthorizationsettingspoliciesscopesdatawithname)
        * [`obj spec.realm.applications.authorizationSettings.resources`](#obj-specrealmapplicationsauthorizationsettingsresources)
          * [`fn withAttributes(attributes)`](#fn-specrealmapplicationsauthorizationsettingsresourceswithattributes)
          * [`fn withAttributesMixin(attributes)`](#fn-specrealmapplicationsauthorizationsettingsresourceswithattributesmixin)
          * [`fn withDisplayName(displayName)`](#fn-specrealmapplicationsauthorizationsettingsresourceswithdisplayname)
          * [`fn withIcon_uri(icon_uri)`](#fn-specrealmapplicationsauthorizationsettingsresourceswithicon_uri)
          * [`fn withName(name)`](#fn-specrealmapplicationsauthorizationsettingsresourceswithname)
          * [`fn withOwnerManagedAccess(ownerManagedAccess)`](#fn-specrealmapplicationsauthorizationsettingsresourceswithownermanagedaccess)
          * [`fn withScopes(scopes)`](#fn-specrealmapplicationsauthorizationsettingsresourceswithscopes)
          * [`fn withScopesMixin(scopes)`](#fn-specrealmapplicationsauthorizationsettingsresourceswithscopesmixin)
          * [`fn withType(type)`](#fn-specrealmapplicationsauthorizationsettingsresourceswithtype)
          * [`fn withUris(uris)`](#fn-specrealmapplicationsauthorizationsettingsresourceswithuris)
          * [`fn withUrisMixin(uris)`](#fn-specrealmapplicationsauthorizationsettingsresourceswithurismixin)
          * [`fn with_id(_id)`](#fn-specrealmapplicationsauthorizationsettingsresourceswith_id)
          * [`obj spec.realm.applications.authorizationSettings.resources.owner`](#obj-specrealmapplicationsauthorizationsettingsresourcesowner)
            * [`fn withId(id)`](#fn-specrealmapplicationsauthorizationsettingsresourcesownerwithid)
            * [`fn withName(name)`](#fn-specrealmapplicationsauthorizationsettingsresourcesownerwithname)
          * [`obj spec.realm.applications.authorizationSettings.resources.scopes`](#obj-specrealmapplicationsauthorizationsettingsresourcesscopes)
            * [`fn withDisplayName(displayName)`](#fn-specrealmapplicationsauthorizationsettingsresourcesscopeswithdisplayname)
            * [`fn withIconUri(iconUri)`](#fn-specrealmapplicationsauthorizationsettingsresourcesscopeswithiconuri)
            * [`fn withId(id)`](#fn-specrealmapplicationsauthorizationsettingsresourcesscopeswithid)
            * [`fn withName(name)`](#fn-specrealmapplicationsauthorizationsettingsresourcesscopeswithname)
        * [`obj spec.realm.applications.authorizationSettings.scopes`](#obj-specrealmapplicationsauthorizationsettingsscopes)
          * [`fn withDisplayName(displayName)`](#fn-specrealmapplicationsauthorizationsettingsscopeswithdisplayname)
          * [`fn withIconUri(iconUri)`](#fn-specrealmapplicationsauthorizationsettingsscopeswithiconuri)
          * [`fn withId(id)`](#fn-specrealmapplicationsauthorizationsettingsscopeswithid)
          * [`fn withName(name)`](#fn-specrealmapplicationsauthorizationsettingsscopeswithname)
      * [`obj spec.realm.applications.claims`](#obj-specrealmapplicationsclaims)
        * [`fn withAddress(address)`](#fn-specrealmapplicationsclaimswithaddress)
        * [`fn withEmail(email)`](#fn-specrealmapplicationsclaimswithemail)
        * [`fn withGender(gender)`](#fn-specrealmapplicationsclaimswithgender)
        * [`fn withLocale(locale)`](#fn-specrealmapplicationsclaimswithlocale)
        * [`fn withName(name)`](#fn-specrealmapplicationsclaimswithname)
        * [`fn withPhone(phone)`](#fn-specrealmapplicationsclaimswithphone)
        * [`fn withPicture(picture)`](#fn-specrealmapplicationsclaimswithpicture)
        * [`fn withProfile(profile)`](#fn-specrealmapplicationsclaimswithprofile)
        * [`fn withUsername(username)`](#fn-specrealmapplicationsclaimswithusername)
        * [`fn withWebsite(website)`](#fn-specrealmapplicationsclaimswithwebsite)
      * [`obj spec.realm.applications.protocolMappers`](#obj-specrealmapplicationsprotocolmappers)
        * [`fn withConfig(config)`](#fn-specrealmapplicationsprotocolmapperswithconfig)
        * [`fn withConfigMixin(config)`](#fn-specrealmapplicationsprotocolmapperswithconfigmixin)
        * [`fn withConsentRequired(consentRequired)`](#fn-specrealmapplicationsprotocolmapperswithconsentrequired)
        * [`fn withConsentText(consentText)`](#fn-specrealmapplicationsprotocolmapperswithconsenttext)
        * [`fn withId(id)`](#fn-specrealmapplicationsprotocolmapperswithid)
        * [`fn withName(name)`](#fn-specrealmapplicationsprotocolmapperswithname)
        * [`fn withProtocol(protocol)`](#fn-specrealmapplicationsprotocolmapperswithprotocol)
        * [`fn withProtocolMapper(protocolMapper)`](#fn-specrealmapplicationsprotocolmapperswithprotocolmapper)
    * [`obj spec.realm.authenticationFlows`](#obj-specrealmauthenticationflows)
      * [`fn withAlias(alias)`](#fn-specrealmauthenticationflowswithalias)
      * [`fn withAuthenticationExecutions(authenticationExecutions)`](#fn-specrealmauthenticationflowswithauthenticationexecutions)
      * [`fn withAuthenticationExecutionsMixin(authenticationExecutions)`](#fn-specrealmauthenticationflowswithauthenticationexecutionsmixin)
      * [`fn withBuiltIn(builtIn)`](#fn-specrealmauthenticationflowswithbuiltin)
      * [`fn withDescription(description)`](#fn-specrealmauthenticationflowswithdescription)
      * [`fn withId(id)`](#fn-specrealmauthenticationflowswithid)
      * [`fn withProviderId(providerId)`](#fn-specrealmauthenticationflowswithproviderid)
      * [`fn withTopLevel(topLevel)`](#fn-specrealmauthenticationflowswithtoplevel)
      * [`obj spec.realm.authenticationFlows.authenticationExecutions`](#obj-specrealmauthenticationflowsauthenticationexecutions)
        * [`fn withAuthenticator(authenticator)`](#fn-specrealmauthenticationflowsauthenticationexecutionswithauthenticator)
        * [`fn withAuthenticatorConfig(authenticatorConfig)`](#fn-specrealmauthenticationflowsauthenticationexecutionswithauthenticatorconfig)
        * [`fn withAuthenticatorFlow(authenticatorFlow)`](#fn-specrealmauthenticationflowsauthenticationexecutionswithauthenticatorflow)
        * [`fn withAutheticatorFlow(autheticatorFlow)`](#fn-specrealmauthenticationflowsauthenticationexecutionswithautheticatorflow)
        * [`fn withFlowAlias(flowAlias)`](#fn-specrealmauthenticationflowsauthenticationexecutionswithflowalias)
        * [`fn withPriority(priority)`](#fn-specrealmauthenticationflowsauthenticationexecutionswithpriority)
        * [`fn withRequirement(requirement)`](#fn-specrealmauthenticationflowsauthenticationexecutionswithrequirement)
        * [`fn withUserSetupAllowed(userSetupAllowed)`](#fn-specrealmauthenticationflowsauthenticationexecutionswithusersetupallowed)
    * [`obj spec.realm.authenticatorConfig`](#obj-specrealmauthenticatorconfig)
      * [`fn withAlias(alias)`](#fn-specrealmauthenticatorconfigwithalias)
      * [`fn withConfig(config)`](#fn-specrealmauthenticatorconfigwithconfig)
      * [`fn withConfigMixin(config)`](#fn-specrealmauthenticatorconfigwithconfigmixin)
      * [`fn withId(id)`](#fn-specrealmauthenticatorconfigwithid)
    * [`obj spec.realm.clientScopes`](#obj-specrealmclientscopes)
      * [`fn withAttributes(attributes)`](#fn-specrealmclientscopeswithattributes)
      * [`fn withAttributesMixin(attributes)`](#fn-specrealmclientscopeswithattributesmixin)
      * [`fn withDescription(description)`](#fn-specrealmclientscopeswithdescription)
      * [`fn withId(id)`](#fn-specrealmclientscopeswithid)
      * [`fn withName(name)`](#fn-specrealmclientscopeswithname)
      * [`fn withProtocol(protocol)`](#fn-specrealmclientscopeswithprotocol)
      * [`fn withProtocolMappers(protocolMappers)`](#fn-specrealmclientscopeswithprotocolmappers)
      * [`fn withProtocolMappersMixin(protocolMappers)`](#fn-specrealmclientscopeswithprotocolmappersmixin)
      * [`obj spec.realm.clientScopes.protocolMappers`](#obj-specrealmclientscopesprotocolmappers)
        * [`fn withConfig(config)`](#fn-specrealmclientscopesprotocolmapperswithconfig)
        * [`fn withConfigMixin(config)`](#fn-specrealmclientscopesprotocolmapperswithconfigmixin)
        * [`fn withConsentRequired(consentRequired)`](#fn-specrealmclientscopesprotocolmapperswithconsentrequired)
        * [`fn withConsentText(consentText)`](#fn-specrealmclientscopesprotocolmapperswithconsenttext)
        * [`fn withId(id)`](#fn-specrealmclientscopesprotocolmapperswithid)
        * [`fn withName(name)`](#fn-specrealmclientscopesprotocolmapperswithname)
        * [`fn withProtocol(protocol)`](#fn-specrealmclientscopesprotocolmapperswithprotocol)
        * [`fn withProtocolMapper(protocolMapper)`](#fn-specrealmclientscopesprotocolmapperswithprotocolmapper)
    * [`obj spec.realm.clientTemplates`](#obj-specrealmclienttemplates)
      * [`fn withAttributes(attributes)`](#fn-specrealmclienttemplateswithattributes)
      * [`fn withAttributesMixin(attributes)`](#fn-specrealmclienttemplateswithattributesmixin)
      * [`fn withBearerOnly(bearerOnly)`](#fn-specrealmclienttemplateswithbeareronly)
      * [`fn withConsentRequired(consentRequired)`](#fn-specrealmclienttemplateswithconsentrequired)
      * [`fn withDescription(description)`](#fn-specrealmclienttemplateswithdescription)
      * [`fn withDirectAccessGrantsEnabled(directAccessGrantsEnabled)`](#fn-specrealmclienttemplateswithdirectaccessgrantsenabled)
      * [`fn withFrontchannelLogout(frontchannelLogout)`](#fn-specrealmclienttemplateswithfrontchannellogout)
      * [`fn withFullScopeAllowed(fullScopeAllowed)`](#fn-specrealmclienttemplateswithfullscopeallowed)
      * [`fn withId(id)`](#fn-specrealmclienttemplateswithid)
      * [`fn withImplicitFlowEnabled(implicitFlowEnabled)`](#fn-specrealmclienttemplateswithimplicitflowenabled)
      * [`fn withName(name)`](#fn-specrealmclienttemplateswithname)
      * [`fn withProtocol(protocol)`](#fn-specrealmclienttemplateswithprotocol)
      * [`fn withProtocolMappers(protocolMappers)`](#fn-specrealmclienttemplateswithprotocolmappers)
      * [`fn withProtocolMappersMixin(protocolMappers)`](#fn-specrealmclienttemplateswithprotocolmappersmixin)
      * [`fn withPublicClient(publicClient)`](#fn-specrealmclienttemplateswithpublicclient)
      * [`fn withServiceAccountsEnabled(serviceAccountsEnabled)`](#fn-specrealmclienttemplateswithserviceaccountsenabled)
      * [`fn withStandardFlowEnabled(standardFlowEnabled)`](#fn-specrealmclienttemplateswithstandardflowenabled)
      * [`obj spec.realm.clientTemplates.protocolMappers`](#obj-specrealmclienttemplatesprotocolmappers)
        * [`fn withConfig(config)`](#fn-specrealmclienttemplatesprotocolmapperswithconfig)
        * [`fn withConfigMixin(config)`](#fn-specrealmclienttemplatesprotocolmapperswithconfigmixin)
        * [`fn withConsentRequired(consentRequired)`](#fn-specrealmclienttemplatesprotocolmapperswithconsentrequired)
        * [`fn withConsentText(consentText)`](#fn-specrealmclienttemplatesprotocolmapperswithconsenttext)
        * [`fn withId(id)`](#fn-specrealmclienttemplatesprotocolmapperswithid)
        * [`fn withName(name)`](#fn-specrealmclienttemplatesprotocolmapperswithname)
        * [`fn withProtocol(protocol)`](#fn-specrealmclienttemplatesprotocolmapperswithprotocol)
        * [`fn withProtocolMapper(protocolMapper)`](#fn-specrealmclienttemplatesprotocolmapperswithprotocolmapper)
    * [`obj spec.realm.clients`](#obj-specrealmclients)
      * [`fn withAccess(access)`](#fn-specrealmclientswithaccess)
      * [`fn withAccessMixin(access)`](#fn-specrealmclientswithaccessmixin)
      * [`fn withAdminUrl(adminUrl)`](#fn-specrealmclientswithadminurl)
      * [`fn withAlwaysDisplayInConsole(alwaysDisplayInConsole)`](#fn-specrealmclientswithalwaysdisplayinconsole)
      * [`fn withAttributes(attributes)`](#fn-specrealmclientswithattributes)
      * [`fn withAttributesMixin(attributes)`](#fn-specrealmclientswithattributesmixin)
      * [`fn withAuthenticationFlowBindingOverrides(authenticationFlowBindingOverrides)`](#fn-specrealmclientswithauthenticationflowbindingoverrides)
      * [`fn withAuthenticationFlowBindingOverridesMixin(authenticationFlowBindingOverrides)`](#fn-specrealmclientswithauthenticationflowbindingoverridesmixin)
      * [`fn withAuthorizationServicesEnabled(authorizationServicesEnabled)`](#fn-specrealmclientswithauthorizationservicesenabled)
      * [`fn withBaseUrl(baseUrl)`](#fn-specrealmclientswithbaseurl)
      * [`fn withBearerOnly(bearerOnly)`](#fn-specrealmclientswithbeareronly)
      * [`fn withClientAuthenticatorType(clientAuthenticatorType)`](#fn-specrealmclientswithclientauthenticatortype)
      * [`fn withClientId(clientId)`](#fn-specrealmclientswithclientid)
      * [`fn withClientTemplate(clientTemplate)`](#fn-specrealmclientswithclienttemplate)
      * [`fn withConsentRequired(consentRequired)`](#fn-specrealmclientswithconsentrequired)
      * [`fn withDefaultClientScopes(defaultClientScopes)`](#fn-specrealmclientswithdefaultclientscopes)
      * [`fn withDefaultClientScopesMixin(defaultClientScopes)`](#fn-specrealmclientswithdefaultclientscopesmixin)
      * [`fn withDefaultRoles(defaultRoles)`](#fn-specrealmclientswithdefaultroles)
      * [`fn withDefaultRolesMixin(defaultRoles)`](#fn-specrealmclientswithdefaultrolesmixin)
      * [`fn withDescription(description)`](#fn-specrealmclientswithdescription)
      * [`fn withDirectAccessGrantsEnabled(directAccessGrantsEnabled)`](#fn-specrealmclientswithdirectaccessgrantsenabled)
      * [`fn withDirectGrantsOnly(directGrantsOnly)`](#fn-specrealmclientswithdirectgrantsonly)
      * [`fn withEnabled(enabled)`](#fn-specrealmclientswithenabled)
      * [`fn withFrontchannelLogout(frontchannelLogout)`](#fn-specrealmclientswithfrontchannellogout)
      * [`fn withFullScopeAllowed(fullScopeAllowed)`](#fn-specrealmclientswithfullscopeallowed)
      * [`fn withId(id)`](#fn-specrealmclientswithid)
      * [`fn withImplicitFlowEnabled(implicitFlowEnabled)`](#fn-specrealmclientswithimplicitflowenabled)
      * [`fn withName(name)`](#fn-specrealmclientswithname)
      * [`fn withNodeReRegistrationTimeout(nodeReRegistrationTimeout)`](#fn-specrealmclientswithnodereregistrationtimeout)
      * [`fn withNotBefore(notBefore)`](#fn-specrealmclientswithnotbefore)
      * [`fn withOptionalClientScopes(optionalClientScopes)`](#fn-specrealmclientswithoptionalclientscopes)
      * [`fn withOptionalClientScopesMixin(optionalClientScopes)`](#fn-specrealmclientswithoptionalclientscopesmixin)
      * [`fn withOrigin(origin)`](#fn-specrealmclientswithorigin)
      * [`fn withProtocol(protocol)`](#fn-specrealmclientswithprotocol)
      * [`fn withProtocolMappers(protocolMappers)`](#fn-specrealmclientswithprotocolmappers)
      * [`fn withProtocolMappersMixin(protocolMappers)`](#fn-specrealmclientswithprotocolmappersmixin)
      * [`fn withPublicClient(publicClient)`](#fn-specrealmclientswithpublicclient)
      * [`fn withRedirectUris(redirectUris)`](#fn-specrealmclientswithredirecturis)
      * [`fn withRedirectUrisMixin(redirectUris)`](#fn-specrealmclientswithredirecturismixin)
      * [`fn withRegisteredNodes(registeredNodes)`](#fn-specrealmclientswithregisterednodes)
      * [`fn withRegisteredNodesMixin(registeredNodes)`](#fn-specrealmclientswithregisterednodesmixin)
      * [`fn withRegistrationAccessToken(registrationAccessToken)`](#fn-specrealmclientswithregistrationaccesstoken)
      * [`fn withRootUrl(rootUrl)`](#fn-specrealmclientswithrooturl)
      * [`fn withSecret(secret)`](#fn-specrealmclientswithsecret)
      * [`fn withServiceAccountsEnabled(serviceAccountsEnabled)`](#fn-specrealmclientswithserviceaccountsenabled)
      * [`fn withStandardFlowEnabled(standardFlowEnabled)`](#fn-specrealmclientswithstandardflowenabled)
      * [`fn withSurrogateAuthRequired(surrogateAuthRequired)`](#fn-specrealmclientswithsurrogateauthrequired)
      * [`fn withType(type)`](#fn-specrealmclientswithtype)
      * [`fn withUseTemplateConfig(useTemplateConfig)`](#fn-specrealmclientswithusetemplateconfig)
      * [`fn withUseTemplateMappers(useTemplateMappers)`](#fn-specrealmclientswithusetemplatemappers)
      * [`fn withUseTemplateScope(useTemplateScope)`](#fn-specrealmclientswithusetemplatescope)
      * [`fn withWebOrigins(webOrigins)`](#fn-specrealmclientswithweborigins)
      * [`fn withWebOriginsMixin(webOrigins)`](#fn-specrealmclientswithweboriginsmixin)
      * [`obj spec.realm.clients.authorizationSettings`](#obj-specrealmclientsauthorizationsettings)
        * [`fn withAllowRemoteResourceManagement(allowRemoteResourceManagement)`](#fn-specrealmclientsauthorizationsettingswithallowremoteresourcemanagement)
        * [`fn withClientId(clientId)`](#fn-specrealmclientsauthorizationsettingswithclientid)
        * [`fn withDecisionStrategy(decisionStrategy)`](#fn-specrealmclientsauthorizationsettingswithdecisionstrategy)
        * [`fn withId(id)`](#fn-specrealmclientsauthorizationsettingswithid)
        * [`fn withName(name)`](#fn-specrealmclientsauthorizationsettingswithname)
        * [`fn withPolicies(policies)`](#fn-specrealmclientsauthorizationsettingswithpolicies)
        * [`fn withPoliciesMixin(policies)`](#fn-specrealmclientsauthorizationsettingswithpoliciesmixin)
        * [`fn withPolicyEnforcementMode(policyEnforcementMode)`](#fn-specrealmclientsauthorizationsettingswithpolicyenforcementmode)
        * [`fn withResources(resources)`](#fn-specrealmclientsauthorizationsettingswithresources)
        * [`fn withResourcesMixin(resources)`](#fn-specrealmclientsauthorizationsettingswithresourcesmixin)
        * [`fn withScopes(scopes)`](#fn-specrealmclientsauthorizationsettingswithscopes)
        * [`fn withScopesMixin(scopes)`](#fn-specrealmclientsauthorizationsettingswithscopesmixin)
        * [`obj spec.realm.clients.authorizationSettings.authorizationSchema`](#obj-specrealmclientsauthorizationsettingsauthorizationschema)
          * [`fn withResourceTypes(resourceTypes)`](#fn-specrealmclientsauthorizationsettingsauthorizationschemawithresourcetypes)
          * [`fn withResourceTypesMixin(resourceTypes)`](#fn-specrealmclientsauthorizationsettingsauthorizationschemawithresourcetypesmixin)
        * [`obj spec.realm.clients.authorizationSettings.policies`](#obj-specrealmclientsauthorizationsettingspolicies)
          * [`fn withConfig(config)`](#fn-specrealmclientsauthorizationsettingspolicieswithconfig)
          * [`fn withConfigMixin(config)`](#fn-specrealmclientsauthorizationsettingspolicieswithconfigmixin)
          * [`fn withDecisionStrategy(decisionStrategy)`](#fn-specrealmclientsauthorizationsettingspolicieswithdecisionstrategy)
          * [`fn withDescription(description)`](#fn-specrealmclientsauthorizationsettingspolicieswithdescription)
          * [`fn withId(id)`](#fn-specrealmclientsauthorizationsettingspolicieswithid)
          * [`fn withLogic(logic)`](#fn-specrealmclientsauthorizationsettingspolicieswithlogic)
          * [`fn withName(name)`](#fn-specrealmclientsauthorizationsettingspolicieswithname)
          * [`fn withOwner(owner)`](#fn-specrealmclientsauthorizationsettingspolicieswithowner)
          * [`fn withPolicies(policies)`](#fn-specrealmclientsauthorizationsettingspolicieswithpolicies)
          * [`fn withPoliciesMixin(policies)`](#fn-specrealmclientsauthorizationsettingspolicieswithpoliciesmixin)
          * [`fn withResourceType(resourceType)`](#fn-specrealmclientsauthorizationsettingspolicieswithresourcetype)
          * [`fn withResources(resources)`](#fn-specrealmclientsauthorizationsettingspolicieswithresources)
          * [`fn withResourcesData(resourcesData)`](#fn-specrealmclientsauthorizationsettingspolicieswithresourcesdata)
          * [`fn withResourcesDataMixin(resourcesData)`](#fn-specrealmclientsauthorizationsettingspolicieswithresourcesdatamixin)
          * [`fn withResourcesMixin(resources)`](#fn-specrealmclientsauthorizationsettingspolicieswithresourcesmixin)
          * [`fn withScopes(scopes)`](#fn-specrealmclientsauthorizationsettingspolicieswithscopes)
          * [`fn withScopesData(scopesData)`](#fn-specrealmclientsauthorizationsettingspolicieswithscopesdata)
          * [`fn withScopesDataMixin(scopesData)`](#fn-specrealmclientsauthorizationsettingspolicieswithscopesdatamixin)
          * [`fn withScopesMixin(scopes)`](#fn-specrealmclientsauthorizationsettingspolicieswithscopesmixin)
          * [`fn withType(type)`](#fn-specrealmclientsauthorizationsettingspolicieswithtype)
          * [`obj spec.realm.clients.authorizationSettings.policies.resourcesData`](#obj-specrealmclientsauthorizationsettingspoliciesresourcesdata)
            * [`fn withAttributes(attributes)`](#fn-specrealmclientsauthorizationsettingspoliciesresourcesdatawithattributes)
            * [`fn withAttributesMixin(attributes)`](#fn-specrealmclientsauthorizationsettingspoliciesresourcesdatawithattributesmixin)
            * [`fn withDisplayName(displayName)`](#fn-specrealmclientsauthorizationsettingspoliciesresourcesdatawithdisplayname)
            * [`fn withIcon_uri(icon_uri)`](#fn-specrealmclientsauthorizationsettingspoliciesresourcesdatawithicon_uri)
            * [`fn withName(name)`](#fn-specrealmclientsauthorizationsettingspoliciesresourcesdatawithname)
            * [`fn withOwnerManagedAccess(ownerManagedAccess)`](#fn-specrealmclientsauthorizationsettingspoliciesresourcesdatawithownermanagedaccess)
            * [`fn withScopes(scopes)`](#fn-specrealmclientsauthorizationsettingspoliciesresourcesdatawithscopes)
            * [`fn withScopesMixin(scopes)`](#fn-specrealmclientsauthorizationsettingspoliciesresourcesdatawithscopesmixin)
            * [`fn withType(type)`](#fn-specrealmclientsauthorizationsettingspoliciesresourcesdatawithtype)
            * [`fn withUris(uris)`](#fn-specrealmclientsauthorizationsettingspoliciesresourcesdatawithuris)
            * [`fn withUrisMixin(uris)`](#fn-specrealmclientsauthorizationsettingspoliciesresourcesdatawithurismixin)
            * [`fn with_id(_id)`](#fn-specrealmclientsauthorizationsettingspoliciesresourcesdatawith_id)
            * [`obj spec.realm.clients.authorizationSettings.policies.resourcesData.owner`](#obj-specrealmclientsauthorizationsettingspoliciesresourcesdataowner)
              * [`fn withId(id)`](#fn-specrealmclientsauthorizationsettingspoliciesresourcesdataownerwithid)
              * [`fn withName(name)`](#fn-specrealmclientsauthorizationsettingspoliciesresourcesdataownerwithname)
            * [`obj spec.realm.clients.authorizationSettings.policies.resourcesData.scopes`](#obj-specrealmclientsauthorizationsettingspoliciesresourcesdatascopes)
              * [`fn withDisplayName(displayName)`](#fn-specrealmclientsauthorizationsettingspoliciesresourcesdatascopeswithdisplayname)
              * [`fn withIconUri(iconUri)`](#fn-specrealmclientsauthorizationsettingspoliciesresourcesdatascopeswithiconuri)
              * [`fn withId(id)`](#fn-specrealmclientsauthorizationsettingspoliciesresourcesdatascopeswithid)
              * [`fn withName(name)`](#fn-specrealmclientsauthorizationsettingspoliciesresourcesdatascopeswithname)
          * [`obj spec.realm.clients.authorizationSettings.policies.scopesData`](#obj-specrealmclientsauthorizationsettingspoliciesscopesdata)
            * [`fn withDisplayName(displayName)`](#fn-specrealmclientsauthorizationsettingspoliciesscopesdatawithdisplayname)
            * [`fn withIconUri(iconUri)`](#fn-specrealmclientsauthorizationsettingspoliciesscopesdatawithiconuri)
            * [`fn withId(id)`](#fn-specrealmclientsauthorizationsettingspoliciesscopesdatawithid)
            * [`fn withName(name)`](#fn-specrealmclientsauthorizationsettingspoliciesscopesdatawithname)
        * [`obj spec.realm.clients.authorizationSettings.resources`](#obj-specrealmclientsauthorizationsettingsresources)
          * [`fn withAttributes(attributes)`](#fn-specrealmclientsauthorizationsettingsresourceswithattributes)
          * [`fn withAttributesMixin(attributes)`](#fn-specrealmclientsauthorizationsettingsresourceswithattributesmixin)
          * [`fn withDisplayName(displayName)`](#fn-specrealmclientsauthorizationsettingsresourceswithdisplayname)
          * [`fn withIcon_uri(icon_uri)`](#fn-specrealmclientsauthorizationsettingsresourceswithicon_uri)
          * [`fn withName(name)`](#fn-specrealmclientsauthorizationsettingsresourceswithname)
          * [`fn withOwnerManagedAccess(ownerManagedAccess)`](#fn-specrealmclientsauthorizationsettingsresourceswithownermanagedaccess)
          * [`fn withScopes(scopes)`](#fn-specrealmclientsauthorizationsettingsresourceswithscopes)
          * [`fn withScopesMixin(scopes)`](#fn-specrealmclientsauthorizationsettingsresourceswithscopesmixin)
          * [`fn withType(type)`](#fn-specrealmclientsauthorizationsettingsresourceswithtype)
          * [`fn withUris(uris)`](#fn-specrealmclientsauthorizationsettingsresourceswithuris)
          * [`fn withUrisMixin(uris)`](#fn-specrealmclientsauthorizationsettingsresourceswithurismixin)
          * [`fn with_id(_id)`](#fn-specrealmclientsauthorizationsettingsresourceswith_id)
          * [`obj spec.realm.clients.authorizationSettings.resources.owner`](#obj-specrealmclientsauthorizationsettingsresourcesowner)
            * [`fn withId(id)`](#fn-specrealmclientsauthorizationsettingsresourcesownerwithid)
            * [`fn withName(name)`](#fn-specrealmclientsauthorizationsettingsresourcesownerwithname)
          * [`obj spec.realm.clients.authorizationSettings.resources.scopes`](#obj-specrealmclientsauthorizationsettingsresourcesscopes)
            * [`fn withDisplayName(displayName)`](#fn-specrealmclientsauthorizationsettingsresourcesscopeswithdisplayname)
            * [`fn withIconUri(iconUri)`](#fn-specrealmclientsauthorizationsettingsresourcesscopeswithiconuri)
            * [`fn withId(id)`](#fn-specrealmclientsauthorizationsettingsresourcesscopeswithid)
            * [`fn withName(name)`](#fn-specrealmclientsauthorizationsettingsresourcesscopeswithname)
        * [`obj spec.realm.clients.authorizationSettings.scopes`](#obj-specrealmclientsauthorizationsettingsscopes)
          * [`fn withDisplayName(displayName)`](#fn-specrealmclientsauthorizationsettingsscopeswithdisplayname)
          * [`fn withIconUri(iconUri)`](#fn-specrealmclientsauthorizationsettingsscopeswithiconuri)
          * [`fn withId(id)`](#fn-specrealmclientsauthorizationsettingsscopeswithid)
          * [`fn withName(name)`](#fn-specrealmclientsauthorizationsettingsscopeswithname)
      * [`obj spec.realm.clients.protocolMappers`](#obj-specrealmclientsprotocolmappers)
        * [`fn withConfig(config)`](#fn-specrealmclientsprotocolmapperswithconfig)
        * [`fn withConfigMixin(config)`](#fn-specrealmclientsprotocolmapperswithconfigmixin)
        * [`fn withConsentRequired(consentRequired)`](#fn-specrealmclientsprotocolmapperswithconsentrequired)
        * [`fn withConsentText(consentText)`](#fn-specrealmclientsprotocolmapperswithconsenttext)
        * [`fn withId(id)`](#fn-specrealmclientsprotocolmapperswithid)
        * [`fn withName(name)`](#fn-specrealmclientsprotocolmapperswithname)
        * [`fn withProtocol(protocol)`](#fn-specrealmclientsprotocolmapperswithprotocol)
        * [`fn withProtocolMapper(protocolMapper)`](#fn-specrealmclientsprotocolmapperswithprotocolmapper)
    * [`obj spec.realm.defaultRole`](#obj-specrealmdefaultrole)
      * [`fn withAttributes(attributes)`](#fn-specrealmdefaultrolewithattributes)
      * [`fn withAttributesMixin(attributes)`](#fn-specrealmdefaultrolewithattributesmixin)
      * [`fn withClientRole(clientRole)`](#fn-specrealmdefaultrolewithclientrole)
      * [`fn withComposite(composite)`](#fn-specrealmdefaultrolewithcomposite)
      * [`fn withContainerId(containerId)`](#fn-specrealmdefaultrolewithcontainerid)
      * [`fn withDescription(description)`](#fn-specrealmdefaultrolewithdescription)
      * [`fn withId(id)`](#fn-specrealmdefaultrolewithid)
      * [`fn withName(name)`](#fn-specrealmdefaultrolewithname)
      * [`fn withScopeParamRequired(scopeParamRequired)`](#fn-specrealmdefaultrolewithscopeparamrequired)
      * [`obj spec.realm.defaultRole.composites`](#obj-specrealmdefaultrolecomposites)
        * [`fn withApplication(application)`](#fn-specrealmdefaultrolecompositeswithapplication)
        * [`fn withApplicationMixin(application)`](#fn-specrealmdefaultrolecompositeswithapplicationmixin)
        * [`fn withClient(client)`](#fn-specrealmdefaultrolecompositeswithclient)
        * [`fn withClientMixin(client)`](#fn-specrealmdefaultrolecompositeswithclientmixin)
        * [`fn withRealm(realm)`](#fn-specrealmdefaultrolecompositeswithrealm)
        * [`fn withRealmMixin(realm)`](#fn-specrealmdefaultrolecompositeswithrealmmixin)
    * [`obj spec.realm.federatedUsers`](#obj-specrealmfederatedusers)
      * [`fn withAccess(access)`](#fn-specrealmfederateduserswithaccess)
      * [`fn withAccessMixin(access)`](#fn-specrealmfederateduserswithaccessmixin)
      * [`fn withApplicationRoles(applicationRoles)`](#fn-specrealmfederateduserswithapplicationroles)
      * [`fn withApplicationRolesMixin(applicationRoles)`](#fn-specrealmfederateduserswithapplicationrolesmixin)
      * [`fn withAttributes(attributes)`](#fn-specrealmfederateduserswithattributes)
      * [`fn withAttributesMixin(attributes)`](#fn-specrealmfederateduserswithattributesmixin)
      * [`fn withClientConsents(clientConsents)`](#fn-specrealmfederateduserswithclientconsents)
      * [`fn withClientConsentsMixin(clientConsents)`](#fn-specrealmfederateduserswithclientconsentsmixin)
      * [`fn withClientRoles(clientRoles)`](#fn-specrealmfederateduserswithclientroles)
      * [`fn withClientRolesMixin(clientRoles)`](#fn-specrealmfederateduserswithclientrolesmixin)
      * [`fn withCreatedTimestamp(createdTimestamp)`](#fn-specrealmfederateduserswithcreatedtimestamp)
      * [`fn withCredentials(credentials)`](#fn-specrealmfederateduserswithcredentials)
      * [`fn withCredentialsMixin(credentials)`](#fn-specrealmfederateduserswithcredentialsmixin)
      * [`fn withDisableableCredentialTypes(disableableCredentialTypes)`](#fn-specrealmfederateduserswithdisableablecredentialtypes)
      * [`fn withDisableableCredentialTypesMixin(disableableCredentialTypes)`](#fn-specrealmfederateduserswithdisableablecredentialtypesmixin)
      * [`fn withEmail(email)`](#fn-specrealmfederateduserswithemail)
      * [`fn withEmailVerified(emailVerified)`](#fn-specrealmfederateduserswithemailverified)
      * [`fn withEnabled(enabled)`](#fn-specrealmfederateduserswithenabled)
      * [`fn withFederatedIdentities(federatedIdentities)`](#fn-specrealmfederateduserswithfederatedidentities)
      * [`fn withFederatedIdentitiesMixin(federatedIdentities)`](#fn-specrealmfederateduserswithfederatedidentitiesmixin)
      * [`fn withFederationLink(federationLink)`](#fn-specrealmfederateduserswithfederationlink)
      * [`fn withFirstName(firstName)`](#fn-specrealmfederateduserswithfirstname)
      * [`fn withGroups(groups)`](#fn-specrealmfederateduserswithgroups)
      * [`fn withGroupsMixin(groups)`](#fn-specrealmfederateduserswithgroupsmixin)
      * [`fn withId(id)`](#fn-specrealmfederateduserswithid)
      * [`fn withLastName(lastName)`](#fn-specrealmfederateduserswithlastname)
      * [`fn withNotBefore(notBefore)`](#fn-specrealmfederateduserswithnotbefore)
      * [`fn withOrigin(origin)`](#fn-specrealmfederateduserswithorigin)
      * [`fn withRealmRoles(realmRoles)`](#fn-specrealmfederateduserswithrealmroles)
      * [`fn withRealmRolesMixin(realmRoles)`](#fn-specrealmfederateduserswithrealmrolesmixin)
      * [`fn withRequiredActions(requiredActions)`](#fn-specrealmfederateduserswithrequiredactions)
      * [`fn withRequiredActionsMixin(requiredActions)`](#fn-specrealmfederateduserswithrequiredactionsmixin)
      * [`fn withSelf(Self)`](#fn-specrealmfederateduserswithself)
      * [`fn withServiceAccountClientId(serviceAccountClientId)`](#fn-specrealmfederateduserswithserviceaccountclientid)
      * [`fn withSocialLinks(socialLinks)`](#fn-specrealmfederateduserswithsociallinks)
      * [`fn withSocialLinksMixin(socialLinks)`](#fn-specrealmfederateduserswithsociallinksmixin)
      * [`fn withTotp(totp)`](#fn-specrealmfederateduserswithtotp)
      * [`fn withUsername(username)`](#fn-specrealmfederateduserswithusername)
      * [`obj spec.realm.federatedUsers.clientConsents`](#obj-specrealmfederatedusersclientconsents)
        * [`fn withClientId(clientId)`](#fn-specrealmfederatedusersclientconsentswithclientid)
        * [`fn withCreatedDate(createdDate)`](#fn-specrealmfederatedusersclientconsentswithcreateddate)
        * [`fn withGrantedClientScopes(grantedClientScopes)`](#fn-specrealmfederatedusersclientconsentswithgrantedclientscopes)
        * [`fn withGrantedClientScopesMixin(grantedClientScopes)`](#fn-specrealmfederatedusersclientconsentswithgrantedclientscopesmixin)
        * [`fn withGrantedRealmRoles(grantedRealmRoles)`](#fn-specrealmfederatedusersclientconsentswithgrantedrealmroles)
        * [`fn withGrantedRealmRolesMixin(grantedRealmRoles)`](#fn-specrealmfederatedusersclientconsentswithgrantedrealmrolesmixin)
        * [`fn withLastUpdatedDate(lastUpdatedDate)`](#fn-specrealmfederatedusersclientconsentswithlastupdateddate)
      * [`obj spec.realm.federatedUsers.credentials`](#obj-specrealmfederateduserscredentials)
        * [`fn withAlgorithm(algorithm)`](#fn-specrealmfederateduserscredentialswithalgorithm)
        * [`fn withConfig(config)`](#fn-specrealmfederateduserscredentialswithconfig)
        * [`fn withConfigMixin(config)`](#fn-specrealmfederateduserscredentialswithconfigmixin)
        * [`fn withCounter(counter)`](#fn-specrealmfederateduserscredentialswithcounter)
        * [`fn withCreatedDate(createdDate)`](#fn-specrealmfederateduserscredentialswithcreateddate)
        * [`fn withCredentialData(credentialData)`](#fn-specrealmfederateduserscredentialswithcredentialdata)
        * [`fn withDevice(device)`](#fn-specrealmfederateduserscredentialswithdevice)
        * [`fn withDigits(digits)`](#fn-specrealmfederateduserscredentialswithdigits)
        * [`fn withFederationLink(federationLink)`](#fn-specrealmfederateduserscredentialswithfederationlink)
        * [`fn withHashIterations(hashIterations)`](#fn-specrealmfederateduserscredentialswithhashiterations)
        * [`fn withHashedSaltedValue(hashedSaltedValue)`](#fn-specrealmfederateduserscredentialswithhashedsaltedvalue)
        * [`fn withId(id)`](#fn-specrealmfederateduserscredentialswithid)
        * [`fn withPeriod(period)`](#fn-specrealmfederateduserscredentialswithperiod)
        * [`fn withPriority(priority)`](#fn-specrealmfederateduserscredentialswithpriority)
        * [`fn withSalt(salt)`](#fn-specrealmfederateduserscredentialswithsalt)
        * [`fn withSecretData(secretData)`](#fn-specrealmfederateduserscredentialswithsecretdata)
        * [`fn withTemporary(temporary)`](#fn-specrealmfederateduserscredentialswithtemporary)
        * [`fn withType(type)`](#fn-specrealmfederateduserscredentialswithtype)
        * [`fn withUserLabel(userLabel)`](#fn-specrealmfederateduserscredentialswithuserlabel)
        * [`fn withValue(value)`](#fn-specrealmfederateduserscredentialswithvalue)
      * [`obj spec.realm.federatedUsers.federatedIdentities`](#obj-specrealmfederatedusersfederatedidentities)
        * [`fn withIdentityProvider(identityProvider)`](#fn-specrealmfederatedusersfederatedidentitieswithidentityprovider)
        * [`fn withUserId(userId)`](#fn-specrealmfederatedusersfederatedidentitieswithuserid)
        * [`fn withUserName(userName)`](#fn-specrealmfederatedusersfederatedidentitieswithusername)
      * [`obj spec.realm.federatedUsers.socialLinks`](#obj-specrealmfederateduserssociallinks)
        * [`fn withSocialProvider(socialProvider)`](#fn-specrealmfederateduserssociallinkswithsocialprovider)
        * [`fn withSocialUserId(socialUserId)`](#fn-specrealmfederateduserssociallinkswithsocialuserid)
        * [`fn withSocialUsername(socialUsername)`](#fn-specrealmfederateduserssociallinkswithsocialusername)
      * [`obj spec.realm.federatedUsers.userProfileMetadata`](#obj-specrealmfederatedusersuserprofilemetadata)
        * [`fn withAttributes(attributes)`](#fn-specrealmfederatedusersuserprofilemetadatawithattributes)
        * [`fn withAttributesMixin(attributes)`](#fn-specrealmfederatedusersuserprofilemetadatawithattributesmixin)
        * [`fn withGroups(groups)`](#fn-specrealmfederatedusersuserprofilemetadatawithgroups)
        * [`fn withGroupsMixin(groups)`](#fn-specrealmfederatedusersuserprofilemetadatawithgroupsmixin)
        * [`obj spec.realm.federatedUsers.userProfileMetadata.attributes`](#obj-specrealmfederatedusersuserprofilemetadataattributes)
          * [`fn withAnnotations(annotations)`](#fn-specrealmfederatedusersuserprofilemetadataattributeswithannotations)
          * [`fn withAnnotationsMixin(annotations)`](#fn-specrealmfederatedusersuserprofilemetadataattributeswithannotationsmixin)
          * [`fn withDefaultValue(defaultValue)`](#fn-specrealmfederatedusersuserprofilemetadataattributeswithdefaultvalue)
          * [`fn withDisplayName(displayName)`](#fn-specrealmfederatedusersuserprofilemetadataattributeswithdisplayname)
          * [`fn withGroup(group)`](#fn-specrealmfederatedusersuserprofilemetadataattributeswithgroup)
          * [`fn withMultivalued(multivalued)`](#fn-specrealmfederatedusersuserprofilemetadataattributeswithmultivalued)
          * [`fn withName(name)`](#fn-specrealmfederatedusersuserprofilemetadataattributeswithname)
          * [`fn withReadOnly(readOnly)`](#fn-specrealmfederatedusersuserprofilemetadataattributeswithreadonly)
          * [`fn withRequired(required)`](#fn-specrealmfederatedusersuserprofilemetadataattributeswithrequired)
          * [`fn withValidators(validators)`](#fn-specrealmfederatedusersuserprofilemetadataattributeswithvalidators)
          * [`fn withValidatorsMixin(validators)`](#fn-specrealmfederatedusersuserprofilemetadataattributeswithvalidatorsmixin)
        * [`obj spec.realm.federatedUsers.userProfileMetadata.groups`](#obj-specrealmfederatedusersuserprofilemetadatagroups)
          * [`fn withAnnotations(annotations)`](#fn-specrealmfederatedusersuserprofilemetadatagroupswithannotations)
          * [`fn withAnnotationsMixin(annotations)`](#fn-specrealmfederatedusersuserprofilemetadatagroupswithannotationsmixin)
          * [`fn withDisplayDescription(displayDescription)`](#fn-specrealmfederatedusersuserprofilemetadatagroupswithdisplaydescription)
          * [`fn withDisplayHeader(displayHeader)`](#fn-specrealmfederatedusersuserprofilemetadatagroupswithdisplayheader)
          * [`fn withName(name)`](#fn-specrealmfederatedusersuserprofilemetadatagroupswithname)
    * [`obj spec.realm.groups`](#obj-specrealmgroups)
      * [`fn withAccess(access)`](#fn-specrealmgroupswithaccess)
      * [`fn withAccessMixin(access)`](#fn-specrealmgroupswithaccessmixin)
      * [`fn withAttributes(attributes)`](#fn-specrealmgroupswithattributes)
      * [`fn withAttributesMixin(attributes)`](#fn-specrealmgroupswithattributesmixin)
      * [`fn withClientRoles(clientRoles)`](#fn-specrealmgroupswithclientroles)
      * [`fn withClientRolesMixin(clientRoles)`](#fn-specrealmgroupswithclientrolesmixin)
      * [`fn withDescription(description)`](#fn-specrealmgroupswithdescription)
      * [`fn withId(id)`](#fn-specrealmgroupswithid)
      * [`fn withName(name)`](#fn-specrealmgroupswithname)
      * [`fn withParentId(parentId)`](#fn-specrealmgroupswithparentid)
      * [`fn withPath(path)`](#fn-specrealmgroupswithpath)
      * [`fn withRealmRoles(realmRoles)`](#fn-specrealmgroupswithrealmroles)
      * [`fn withRealmRolesMixin(realmRoles)`](#fn-specrealmgroupswithrealmrolesmixin)
      * [`fn withSubGroupCount(subGroupCount)`](#fn-specrealmgroupswithsubgroupcount)
      * [`fn withSubGroups(subGroups)`](#fn-specrealmgroupswithsubgroups)
      * [`fn withSubGroupsMixin(subGroups)`](#fn-specrealmgroupswithsubgroupsmixin)
      * [`obj spec.realm.groups.subGroups`](#obj-specrealmgroupssubgroups)
        * [`fn withAccess(access)`](#fn-specrealmgroupssubgroupswithaccess)
        * [`fn withAccessMixin(access)`](#fn-specrealmgroupssubgroupswithaccessmixin)
        * [`fn withAttributes(attributes)`](#fn-specrealmgroupssubgroupswithattributes)
        * [`fn withAttributesMixin(attributes)`](#fn-specrealmgroupssubgroupswithattributesmixin)
        * [`fn withClientRoles(clientRoles)`](#fn-specrealmgroupssubgroupswithclientroles)
        * [`fn withClientRolesMixin(clientRoles)`](#fn-specrealmgroupssubgroupswithclientrolesmixin)
        * [`fn withDescription(description)`](#fn-specrealmgroupssubgroupswithdescription)
        * [`fn withId(id)`](#fn-specrealmgroupssubgroupswithid)
        * [`fn withName(name)`](#fn-specrealmgroupssubgroupswithname)
        * [`fn withParentId(parentId)`](#fn-specrealmgroupssubgroupswithparentid)
        * [`fn withPath(path)`](#fn-specrealmgroupssubgroupswithpath)
        * [`fn withRealmRoles(realmRoles)`](#fn-specrealmgroupssubgroupswithrealmroles)
        * [`fn withRealmRolesMixin(realmRoles)`](#fn-specrealmgroupssubgroupswithrealmrolesmixin)
        * [`fn withSubGroupCount(subGroupCount)`](#fn-specrealmgroupssubgroupswithsubgroupcount)
        * [`fn withSubGroups(subGroups)`](#fn-specrealmgroupssubgroupswithsubgroups)
        * [`fn withSubGroupsMixin(subGroups)`](#fn-specrealmgroupssubgroupswithsubgroupsmixin)
        * [`obj spec.realm.groups.subGroups.subGroups`](#obj-specrealmgroupssubgroupssubgroups)
          * [`fn withAccess(access)`](#fn-specrealmgroupssubgroupssubgroupswithaccess)
          * [`fn withAccessMixin(access)`](#fn-specrealmgroupssubgroupssubgroupswithaccessmixin)
          * [`fn withAttributes(attributes)`](#fn-specrealmgroupssubgroupssubgroupswithattributes)
          * [`fn withAttributesMixin(attributes)`](#fn-specrealmgroupssubgroupssubgroupswithattributesmixin)
          * [`fn withClientRoles(clientRoles)`](#fn-specrealmgroupssubgroupssubgroupswithclientroles)
          * [`fn withClientRolesMixin(clientRoles)`](#fn-specrealmgroupssubgroupssubgroupswithclientrolesmixin)
          * [`fn withDescription(description)`](#fn-specrealmgroupssubgroupssubgroupswithdescription)
          * [`fn withId(id)`](#fn-specrealmgroupssubgroupssubgroupswithid)
          * [`fn withName(name)`](#fn-specrealmgroupssubgroupssubgroupswithname)
          * [`fn withParentId(parentId)`](#fn-specrealmgroupssubgroupssubgroupswithparentid)
          * [`fn withPath(path)`](#fn-specrealmgroupssubgroupssubgroupswithpath)
          * [`fn withRealmRoles(realmRoles)`](#fn-specrealmgroupssubgroupssubgroupswithrealmroles)
          * [`fn withRealmRolesMixin(realmRoles)`](#fn-specrealmgroupssubgroupssubgroupswithrealmrolesmixin)
          * [`fn withSubGroupCount(subGroupCount)`](#fn-specrealmgroupssubgroupssubgroupswithsubgroupcount)
          * [`fn withSubGroups(subGroups)`](#fn-specrealmgroupssubgroupssubgroupswithsubgroups)
          * [`fn withSubGroupsMixin(subGroups)`](#fn-specrealmgroupssubgroupssubgroupswithsubgroupsmixin)
          * [`obj spec.realm.groups.subGroups.subGroups.subGroups`](#obj-specrealmgroupssubgroupssubgroupssubgroups)
            * [`fn withAccess(access)`](#fn-specrealmgroupssubgroupssubgroupssubgroupswithaccess)
            * [`fn withAccessMixin(access)`](#fn-specrealmgroupssubgroupssubgroupssubgroupswithaccessmixin)
            * [`fn withAttributes(attributes)`](#fn-specrealmgroupssubgroupssubgroupssubgroupswithattributes)
            * [`fn withAttributesMixin(attributes)`](#fn-specrealmgroupssubgroupssubgroupssubgroupswithattributesmixin)
            * [`fn withClientRoles(clientRoles)`](#fn-specrealmgroupssubgroupssubgroupssubgroupswithclientroles)
            * [`fn withClientRolesMixin(clientRoles)`](#fn-specrealmgroupssubgroupssubgroupssubgroupswithclientrolesmixin)
            * [`fn withDescription(description)`](#fn-specrealmgroupssubgroupssubgroupssubgroupswithdescription)
            * [`fn withId(id)`](#fn-specrealmgroupssubgroupssubgroupssubgroupswithid)
            * [`fn withName(name)`](#fn-specrealmgroupssubgroupssubgroupssubgroupswithname)
            * [`fn withParentId(parentId)`](#fn-specrealmgroupssubgroupssubgroupssubgroupswithparentid)
            * [`fn withPath(path)`](#fn-specrealmgroupssubgroupssubgroupssubgroupswithpath)
            * [`fn withRealmRoles(realmRoles)`](#fn-specrealmgroupssubgroupssubgroupssubgroupswithrealmroles)
            * [`fn withRealmRolesMixin(realmRoles)`](#fn-specrealmgroupssubgroupssubgroupssubgroupswithrealmrolesmixin)
            * [`fn withSubGroupCount(subGroupCount)`](#fn-specrealmgroupssubgroupssubgroupssubgroupswithsubgroupcount)
            * [`fn withSubGroups(subGroups)`](#fn-specrealmgroupssubgroupssubgroupssubgroupswithsubgroups)
            * [`fn withSubGroupsMixin(subGroups)`](#fn-specrealmgroupssubgroupssubgroupssubgroupswithsubgroupsmixin)
            * [`obj spec.realm.groups.subGroups.subGroups.subGroups.subGroups`](#obj-specrealmgroupssubgroupssubgroupssubgroupssubgroups)
              * [`fn withAccess(access)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupswithaccess)
              * [`fn withAccessMixin(access)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupswithaccessmixin)
              * [`fn withAttributes(attributes)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupswithattributes)
              * [`fn withAttributesMixin(attributes)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupswithattributesmixin)
              * [`fn withClientRoles(clientRoles)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupswithclientroles)
              * [`fn withClientRolesMixin(clientRoles)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupswithclientrolesmixin)
              * [`fn withDescription(description)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupswithdescription)
              * [`fn withId(id)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupswithid)
              * [`fn withName(name)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupswithname)
              * [`fn withParentId(parentId)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupswithparentid)
              * [`fn withPath(path)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupswithpath)
              * [`fn withRealmRoles(realmRoles)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupswithrealmroles)
              * [`fn withRealmRolesMixin(realmRoles)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupswithrealmrolesmixin)
              * [`fn withSubGroupCount(subGroupCount)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupswithsubgroupcount)
              * [`fn withSubGroups(subGroups)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupswithsubgroups)
              * [`fn withSubGroupsMixin(subGroups)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupswithsubgroupsmixin)
              * [`obj spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups`](#obj-specrealmgroupssubgroupssubgroupssubgroupssubgroupssubgroups)
                * [`fn withAccess(access)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupssubgroupswithaccess)
                * [`fn withAccessMixin(access)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupssubgroupswithaccessmixin)
                * [`fn withAttributes(attributes)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupssubgroupswithattributes)
                * [`fn withAttributesMixin(attributes)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupssubgroupswithattributesmixin)
                * [`fn withClientRoles(clientRoles)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupssubgroupswithclientroles)
                * [`fn withClientRolesMixin(clientRoles)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupssubgroupswithclientrolesmixin)
                * [`fn withDescription(description)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupssubgroupswithdescription)
                * [`fn withId(id)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupssubgroupswithid)
                * [`fn withName(name)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupssubgroupswithname)
                * [`fn withParentId(parentId)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupssubgroupswithparentid)
                * [`fn withPath(path)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupssubgroupswithpath)
                * [`fn withRealmRoles(realmRoles)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupssubgroupswithrealmroles)
                * [`fn withRealmRolesMixin(realmRoles)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupssubgroupswithrealmrolesmixin)
                * [`fn withSubGroupCount(subGroupCount)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupssubgroupswithsubgroupcount)
                * [`fn withSubGroups(subGroups)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupssubgroupswithsubgroups)
                * [`fn withSubGroupsMixin(subGroups)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupssubgroupswithsubgroupsmixin)
                * [`obj spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups`](#obj-specrealmgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroups)
                  * [`fn withAccess(access)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupswithaccess)
                  * [`fn withAccessMixin(access)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupswithaccessmixin)
                  * [`fn withAttributes(attributes)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupswithattributes)
                  * [`fn withAttributesMixin(attributes)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupswithattributesmixin)
                  * [`fn withClientRoles(clientRoles)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupswithclientroles)
                  * [`fn withClientRolesMixin(clientRoles)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupswithclientrolesmixin)
                  * [`fn withDescription(description)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupswithdescription)
                  * [`fn withId(id)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupswithid)
                  * [`fn withName(name)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupswithname)
                  * [`fn withParentId(parentId)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupswithparentid)
                  * [`fn withPath(path)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupswithpath)
                  * [`fn withRealmRoles(realmRoles)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupswithrealmroles)
                  * [`fn withRealmRolesMixin(realmRoles)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupswithrealmrolesmixin)
                  * [`fn withSubGroupCount(subGroupCount)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupswithsubgroupcount)
                  * [`fn withSubGroups(subGroups)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupswithsubgroups)
                  * [`fn withSubGroupsMixin(subGroups)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupswithsubgroupsmixin)
                  * [`obj spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups`](#obj-specrealmgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroups)
                    * [`fn withAccess(access)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupswithaccess)
                    * [`fn withAccessMixin(access)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupswithaccessmixin)
                    * [`fn withAttributes(attributes)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupswithattributes)
                    * [`fn withAttributesMixin(attributes)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupswithattributesmixin)
                    * [`fn withClientRoles(clientRoles)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupswithclientroles)
                    * [`fn withClientRolesMixin(clientRoles)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupswithclientrolesmixin)
                    * [`fn withDescription(description)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupswithdescription)
                    * [`fn withId(id)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupswithid)
                    * [`fn withName(name)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupswithname)
                    * [`fn withParentId(parentId)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupswithparentid)
                    * [`fn withPath(path)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupswithpath)
                    * [`fn withRealmRoles(realmRoles)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupswithrealmroles)
                    * [`fn withRealmRolesMixin(realmRoles)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupswithrealmrolesmixin)
                    * [`fn withSubGroupCount(subGroupCount)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupswithsubgroupcount)
                    * [`fn withSubGroups(subGroups)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupswithsubgroups)
                    * [`fn withSubGroupsMixin(subGroups)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupswithsubgroupsmixin)
                    * [`obj spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups`](#obj-specrealmgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroups)
                      * [`fn withAccess(access)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupswithaccess)
                      * [`fn withAccessMixin(access)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupswithaccessmixin)
                      * [`fn withAttributes(attributes)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupswithattributes)
                      * [`fn withAttributesMixin(attributes)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupswithattributesmixin)
                      * [`fn withClientRoles(clientRoles)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupswithclientroles)
                      * [`fn withClientRolesMixin(clientRoles)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupswithclientrolesmixin)
                      * [`fn withDescription(description)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupswithdescription)
                      * [`fn withId(id)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupswithid)
                      * [`fn withName(name)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupswithname)
                      * [`fn withParentId(parentId)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupswithparentid)
                      * [`fn withPath(path)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupswithpath)
                      * [`fn withRealmRoles(realmRoles)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupswithrealmroles)
                      * [`fn withRealmRolesMixin(realmRoles)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupswithrealmrolesmixin)
                      * [`fn withSubGroupCount(subGroupCount)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupswithsubgroupcount)
                      * [`fn withSubGroups(subGroups)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupswithsubgroups)
                      * [`fn withSubGroupsMixin(subGroups)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupswithsubgroupsmixin)
                      * [`obj spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups`](#obj-specrealmgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroups)
                        * [`fn withAccess(access)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupswithaccess)
                        * [`fn withAccessMixin(access)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupswithaccessmixin)
                        * [`fn withAttributes(attributes)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupswithattributes)
                        * [`fn withAttributesMixin(attributes)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupswithattributesmixin)
                        * [`fn withClientRoles(clientRoles)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupswithclientroles)
                        * [`fn withClientRolesMixin(clientRoles)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupswithclientrolesmixin)
                        * [`fn withDescription(description)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupswithdescription)
                        * [`fn withId(id)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupswithid)
                        * [`fn withName(name)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupswithname)
                        * [`fn withParentId(parentId)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupswithparentid)
                        * [`fn withPath(path)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupswithpath)
                        * [`fn withRealmRoles(realmRoles)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupswithrealmroles)
                        * [`fn withRealmRolesMixin(realmRoles)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupswithrealmrolesmixin)
                        * [`fn withSubGroupCount(subGroupCount)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupswithsubgroupcount)
                        * [`fn withSubGroups(subGroups)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupswithsubgroups)
                        * [`fn withSubGroupsMixin(subGroups)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupswithsubgroupsmixin)
                        * [`obj spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups`](#obj-specrealmgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroups)
                          * [`fn withAccess(access)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupswithaccess)
                          * [`fn withAccessMixin(access)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupswithaccessmixin)
                          * [`fn withAttributes(attributes)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupswithattributes)
                          * [`fn withAttributesMixin(attributes)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupswithattributesmixin)
                          * [`fn withClientRoles(clientRoles)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupswithclientroles)
                          * [`fn withClientRolesMixin(clientRoles)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupswithclientrolesmixin)
                          * [`fn withDescription(description)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupswithdescription)
                          * [`fn withId(id)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupswithid)
                          * [`fn withName(name)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupswithname)
                          * [`fn withParentId(parentId)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupswithparentid)
                          * [`fn withPath(path)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupswithpath)
                          * [`fn withRealmRoles(realmRoles)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupswithrealmroles)
                          * [`fn withRealmRolesMixin(realmRoles)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupswithrealmrolesmixin)
                          * [`fn withSubGroupCount(subGroupCount)`](#fn-specrealmgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupssubgroupswithsubgroupcount)
    * [`obj spec.realm.identityProviderMappers`](#obj-specrealmidentityprovidermappers)
      * [`fn withConfig(config)`](#fn-specrealmidentityprovidermapperswithconfig)
      * [`fn withConfigMixin(config)`](#fn-specrealmidentityprovidermapperswithconfigmixin)
      * [`fn withId(id)`](#fn-specrealmidentityprovidermapperswithid)
      * [`fn withIdentityProviderAlias(identityProviderAlias)`](#fn-specrealmidentityprovidermapperswithidentityprovideralias)
      * [`fn withIdentityProviderMapper(identityProviderMapper)`](#fn-specrealmidentityprovidermapperswithidentityprovidermapper)
      * [`fn withName(name)`](#fn-specrealmidentityprovidermapperswithname)
    * [`obj spec.realm.identityProviders`](#obj-specrealmidentityproviders)
      * [`fn withAddReadTokenRoleOnCreate(addReadTokenRoleOnCreate)`](#fn-specrealmidentityproviderswithaddreadtokenroleoncreate)
      * [`fn withAlias(alias)`](#fn-specrealmidentityproviderswithalias)
      * [`fn withAuthenticateByDefault(authenticateByDefault)`](#fn-specrealmidentityproviderswithauthenticatebydefault)
      * [`fn withConfig(config)`](#fn-specrealmidentityproviderswithconfig)
      * [`fn withConfigMixin(config)`](#fn-specrealmidentityproviderswithconfigmixin)
      * [`fn withDisplayName(displayName)`](#fn-specrealmidentityproviderswithdisplayname)
      * [`fn withEnabled(enabled)`](#fn-specrealmidentityproviderswithenabled)
      * [`fn withFirstBrokerLoginFlowAlias(firstBrokerLoginFlowAlias)`](#fn-specrealmidentityproviderswithfirstbrokerloginflowalias)
      * [`fn withHideOnLogin(hideOnLogin)`](#fn-specrealmidentityproviderswithhideonlogin)
      * [`fn withInternalId(internalId)`](#fn-specrealmidentityproviderswithinternalid)
      * [`fn withLinkOnly(linkOnly)`](#fn-specrealmidentityproviderswithlinkonly)
      * [`fn withOrganizationId(organizationId)`](#fn-specrealmidentityproviderswithorganizationid)
      * [`fn withPostBrokerLoginFlowAlias(postBrokerLoginFlowAlias)`](#fn-specrealmidentityproviderswithpostbrokerloginflowalias)
      * [`fn withProviderId(providerId)`](#fn-specrealmidentityproviderswithproviderid)
      * [`fn withStoreToken(storeToken)`](#fn-specrealmidentityproviderswithstoretoken)
      * [`fn withTrustEmail(trustEmail)`](#fn-specrealmidentityproviderswithtrustemail)
      * [`fn withUpdateProfileFirstLoginMode(updateProfileFirstLoginMode)`](#fn-specrealmidentityproviderswithupdateprofilefirstloginmode)
    * [`obj spec.realm.oauthClients`](#obj-specrealmoauthclients)
      * [`fn withAccess(access)`](#fn-specrealmoauthclientswithaccess)
      * [`fn withAccessMixin(access)`](#fn-specrealmoauthclientswithaccessmixin)
      * [`fn withAdminUrl(adminUrl)`](#fn-specrealmoauthclientswithadminurl)
      * [`fn withAlwaysDisplayInConsole(alwaysDisplayInConsole)`](#fn-specrealmoauthclientswithalwaysdisplayinconsole)
      * [`fn withAttributes(attributes)`](#fn-specrealmoauthclientswithattributes)
      * [`fn withAttributesMixin(attributes)`](#fn-specrealmoauthclientswithattributesmixin)
      * [`fn withAuthenticationFlowBindingOverrides(authenticationFlowBindingOverrides)`](#fn-specrealmoauthclientswithauthenticationflowbindingoverrides)
      * [`fn withAuthenticationFlowBindingOverridesMixin(authenticationFlowBindingOverrides)`](#fn-specrealmoauthclientswithauthenticationflowbindingoverridesmixin)
      * [`fn withAuthorizationServicesEnabled(authorizationServicesEnabled)`](#fn-specrealmoauthclientswithauthorizationservicesenabled)
      * [`fn withBaseUrl(baseUrl)`](#fn-specrealmoauthclientswithbaseurl)
      * [`fn withBearerOnly(bearerOnly)`](#fn-specrealmoauthclientswithbeareronly)
      * [`fn withClientAuthenticatorType(clientAuthenticatorType)`](#fn-specrealmoauthclientswithclientauthenticatortype)
      * [`fn withClientId(clientId)`](#fn-specrealmoauthclientswithclientid)
      * [`fn withClientTemplate(clientTemplate)`](#fn-specrealmoauthclientswithclienttemplate)
      * [`fn withConsentRequired(consentRequired)`](#fn-specrealmoauthclientswithconsentrequired)
      * [`fn withDefaultClientScopes(defaultClientScopes)`](#fn-specrealmoauthclientswithdefaultclientscopes)
      * [`fn withDefaultClientScopesMixin(defaultClientScopes)`](#fn-specrealmoauthclientswithdefaultclientscopesmixin)
      * [`fn withDefaultRoles(defaultRoles)`](#fn-specrealmoauthclientswithdefaultroles)
      * [`fn withDefaultRolesMixin(defaultRoles)`](#fn-specrealmoauthclientswithdefaultrolesmixin)
      * [`fn withDescription(description)`](#fn-specrealmoauthclientswithdescription)
      * [`fn withDirectAccessGrantsEnabled(directAccessGrantsEnabled)`](#fn-specrealmoauthclientswithdirectaccessgrantsenabled)
      * [`fn withDirectGrantsOnly(directGrantsOnly)`](#fn-specrealmoauthclientswithdirectgrantsonly)
      * [`fn withEnabled(enabled)`](#fn-specrealmoauthclientswithenabled)
      * [`fn withFrontchannelLogout(frontchannelLogout)`](#fn-specrealmoauthclientswithfrontchannellogout)
      * [`fn withFullScopeAllowed(fullScopeAllowed)`](#fn-specrealmoauthclientswithfullscopeallowed)
      * [`fn withId(id)`](#fn-specrealmoauthclientswithid)
      * [`fn withImplicitFlowEnabled(implicitFlowEnabled)`](#fn-specrealmoauthclientswithimplicitflowenabled)
      * [`fn withName(name)`](#fn-specrealmoauthclientswithname)
      * [`fn withNodeReRegistrationTimeout(nodeReRegistrationTimeout)`](#fn-specrealmoauthclientswithnodereregistrationtimeout)
      * [`fn withNotBefore(notBefore)`](#fn-specrealmoauthclientswithnotbefore)
      * [`fn withOptionalClientScopes(optionalClientScopes)`](#fn-specrealmoauthclientswithoptionalclientscopes)
      * [`fn withOptionalClientScopesMixin(optionalClientScopes)`](#fn-specrealmoauthclientswithoptionalclientscopesmixin)
      * [`fn withOrigin(origin)`](#fn-specrealmoauthclientswithorigin)
      * [`fn withProtocol(protocol)`](#fn-specrealmoauthclientswithprotocol)
      * [`fn withProtocolMappers(protocolMappers)`](#fn-specrealmoauthclientswithprotocolmappers)
      * [`fn withProtocolMappersMixin(protocolMappers)`](#fn-specrealmoauthclientswithprotocolmappersmixin)
      * [`fn withPublicClient(publicClient)`](#fn-specrealmoauthclientswithpublicclient)
      * [`fn withRedirectUris(redirectUris)`](#fn-specrealmoauthclientswithredirecturis)
      * [`fn withRedirectUrisMixin(redirectUris)`](#fn-specrealmoauthclientswithredirecturismixin)
      * [`fn withRegisteredNodes(registeredNodes)`](#fn-specrealmoauthclientswithregisterednodes)
      * [`fn withRegisteredNodesMixin(registeredNodes)`](#fn-specrealmoauthclientswithregisterednodesmixin)
      * [`fn withRegistrationAccessToken(registrationAccessToken)`](#fn-specrealmoauthclientswithregistrationaccesstoken)
      * [`fn withRootUrl(rootUrl)`](#fn-specrealmoauthclientswithrooturl)
      * [`fn withSecret(secret)`](#fn-specrealmoauthclientswithsecret)
      * [`fn withServiceAccountsEnabled(serviceAccountsEnabled)`](#fn-specrealmoauthclientswithserviceaccountsenabled)
      * [`fn withStandardFlowEnabled(standardFlowEnabled)`](#fn-specrealmoauthclientswithstandardflowenabled)
      * [`fn withSurrogateAuthRequired(surrogateAuthRequired)`](#fn-specrealmoauthclientswithsurrogateauthrequired)
      * [`fn withType(type)`](#fn-specrealmoauthclientswithtype)
      * [`fn withUseTemplateConfig(useTemplateConfig)`](#fn-specrealmoauthclientswithusetemplateconfig)
      * [`fn withUseTemplateMappers(useTemplateMappers)`](#fn-specrealmoauthclientswithusetemplatemappers)
      * [`fn withUseTemplateScope(useTemplateScope)`](#fn-specrealmoauthclientswithusetemplatescope)
      * [`fn withWebOrigins(webOrigins)`](#fn-specrealmoauthclientswithweborigins)
      * [`fn withWebOriginsMixin(webOrigins)`](#fn-specrealmoauthclientswithweboriginsmixin)
      * [`obj spec.realm.oauthClients.authorizationSettings`](#obj-specrealmoauthclientsauthorizationsettings)
        * [`fn withAllowRemoteResourceManagement(allowRemoteResourceManagement)`](#fn-specrealmoauthclientsauthorizationsettingswithallowremoteresourcemanagement)
        * [`fn withClientId(clientId)`](#fn-specrealmoauthclientsauthorizationsettingswithclientid)
        * [`fn withDecisionStrategy(decisionStrategy)`](#fn-specrealmoauthclientsauthorizationsettingswithdecisionstrategy)
        * [`fn withId(id)`](#fn-specrealmoauthclientsauthorizationsettingswithid)
        * [`fn withName(name)`](#fn-specrealmoauthclientsauthorizationsettingswithname)
        * [`fn withPolicies(policies)`](#fn-specrealmoauthclientsauthorizationsettingswithpolicies)
        * [`fn withPoliciesMixin(policies)`](#fn-specrealmoauthclientsauthorizationsettingswithpoliciesmixin)
        * [`fn withPolicyEnforcementMode(policyEnforcementMode)`](#fn-specrealmoauthclientsauthorizationsettingswithpolicyenforcementmode)
        * [`fn withResources(resources)`](#fn-specrealmoauthclientsauthorizationsettingswithresources)
        * [`fn withResourcesMixin(resources)`](#fn-specrealmoauthclientsauthorizationsettingswithresourcesmixin)
        * [`fn withScopes(scopes)`](#fn-specrealmoauthclientsauthorizationsettingswithscopes)
        * [`fn withScopesMixin(scopes)`](#fn-specrealmoauthclientsauthorizationsettingswithscopesmixin)
        * [`obj spec.realm.oauthClients.authorizationSettings.authorizationSchema`](#obj-specrealmoauthclientsauthorizationsettingsauthorizationschema)
          * [`fn withResourceTypes(resourceTypes)`](#fn-specrealmoauthclientsauthorizationsettingsauthorizationschemawithresourcetypes)
          * [`fn withResourceTypesMixin(resourceTypes)`](#fn-specrealmoauthclientsauthorizationsettingsauthorizationschemawithresourcetypesmixin)
        * [`obj spec.realm.oauthClients.authorizationSettings.policies`](#obj-specrealmoauthclientsauthorizationsettingspolicies)
          * [`fn withConfig(config)`](#fn-specrealmoauthclientsauthorizationsettingspolicieswithconfig)
          * [`fn withConfigMixin(config)`](#fn-specrealmoauthclientsauthorizationsettingspolicieswithconfigmixin)
          * [`fn withDecisionStrategy(decisionStrategy)`](#fn-specrealmoauthclientsauthorizationsettingspolicieswithdecisionstrategy)
          * [`fn withDescription(description)`](#fn-specrealmoauthclientsauthorizationsettingspolicieswithdescription)
          * [`fn withId(id)`](#fn-specrealmoauthclientsauthorizationsettingspolicieswithid)
          * [`fn withLogic(logic)`](#fn-specrealmoauthclientsauthorizationsettingspolicieswithlogic)
          * [`fn withName(name)`](#fn-specrealmoauthclientsauthorizationsettingspolicieswithname)
          * [`fn withOwner(owner)`](#fn-specrealmoauthclientsauthorizationsettingspolicieswithowner)
          * [`fn withPolicies(policies)`](#fn-specrealmoauthclientsauthorizationsettingspolicieswithpolicies)
          * [`fn withPoliciesMixin(policies)`](#fn-specrealmoauthclientsauthorizationsettingspolicieswithpoliciesmixin)
          * [`fn withResourceType(resourceType)`](#fn-specrealmoauthclientsauthorizationsettingspolicieswithresourcetype)
          * [`fn withResources(resources)`](#fn-specrealmoauthclientsauthorizationsettingspolicieswithresources)
          * [`fn withResourcesData(resourcesData)`](#fn-specrealmoauthclientsauthorizationsettingspolicieswithresourcesdata)
          * [`fn withResourcesDataMixin(resourcesData)`](#fn-specrealmoauthclientsauthorizationsettingspolicieswithresourcesdatamixin)
          * [`fn withResourcesMixin(resources)`](#fn-specrealmoauthclientsauthorizationsettingspolicieswithresourcesmixin)
          * [`fn withScopes(scopes)`](#fn-specrealmoauthclientsauthorizationsettingspolicieswithscopes)
          * [`fn withScopesData(scopesData)`](#fn-specrealmoauthclientsauthorizationsettingspolicieswithscopesdata)
          * [`fn withScopesDataMixin(scopesData)`](#fn-specrealmoauthclientsauthorizationsettingspolicieswithscopesdatamixin)
          * [`fn withScopesMixin(scopes)`](#fn-specrealmoauthclientsauthorizationsettingspolicieswithscopesmixin)
          * [`fn withType(type)`](#fn-specrealmoauthclientsauthorizationsettingspolicieswithtype)
          * [`obj spec.realm.oauthClients.authorizationSettings.policies.resourcesData`](#obj-specrealmoauthclientsauthorizationsettingspoliciesresourcesdata)
            * [`fn withAttributes(attributes)`](#fn-specrealmoauthclientsauthorizationsettingspoliciesresourcesdatawithattributes)
            * [`fn withAttributesMixin(attributes)`](#fn-specrealmoauthclientsauthorizationsettingspoliciesresourcesdatawithattributesmixin)
            * [`fn withDisplayName(displayName)`](#fn-specrealmoauthclientsauthorizationsettingspoliciesresourcesdatawithdisplayname)
            * [`fn withIcon_uri(icon_uri)`](#fn-specrealmoauthclientsauthorizationsettingspoliciesresourcesdatawithicon_uri)
            * [`fn withName(name)`](#fn-specrealmoauthclientsauthorizationsettingspoliciesresourcesdatawithname)
            * [`fn withOwnerManagedAccess(ownerManagedAccess)`](#fn-specrealmoauthclientsauthorizationsettingspoliciesresourcesdatawithownermanagedaccess)
            * [`fn withScopes(scopes)`](#fn-specrealmoauthclientsauthorizationsettingspoliciesresourcesdatawithscopes)
            * [`fn withScopesMixin(scopes)`](#fn-specrealmoauthclientsauthorizationsettingspoliciesresourcesdatawithscopesmixin)
            * [`fn withType(type)`](#fn-specrealmoauthclientsauthorizationsettingspoliciesresourcesdatawithtype)
            * [`fn withUris(uris)`](#fn-specrealmoauthclientsauthorizationsettingspoliciesresourcesdatawithuris)
            * [`fn withUrisMixin(uris)`](#fn-specrealmoauthclientsauthorizationsettingspoliciesresourcesdatawithurismixin)
            * [`fn with_id(_id)`](#fn-specrealmoauthclientsauthorizationsettingspoliciesresourcesdatawith_id)
            * [`obj spec.realm.oauthClients.authorizationSettings.policies.resourcesData.owner`](#obj-specrealmoauthclientsauthorizationsettingspoliciesresourcesdataowner)
              * [`fn withId(id)`](#fn-specrealmoauthclientsauthorizationsettingspoliciesresourcesdataownerwithid)
              * [`fn withName(name)`](#fn-specrealmoauthclientsauthorizationsettingspoliciesresourcesdataownerwithname)
            * [`obj spec.realm.oauthClients.authorizationSettings.policies.resourcesData.scopes`](#obj-specrealmoauthclientsauthorizationsettingspoliciesresourcesdatascopes)
              * [`fn withDisplayName(displayName)`](#fn-specrealmoauthclientsauthorizationsettingspoliciesresourcesdatascopeswithdisplayname)
              * [`fn withIconUri(iconUri)`](#fn-specrealmoauthclientsauthorizationsettingspoliciesresourcesdatascopeswithiconuri)
              * [`fn withId(id)`](#fn-specrealmoauthclientsauthorizationsettingspoliciesresourcesdatascopeswithid)
              * [`fn withName(name)`](#fn-specrealmoauthclientsauthorizationsettingspoliciesresourcesdatascopeswithname)
          * [`obj spec.realm.oauthClients.authorizationSettings.policies.scopesData`](#obj-specrealmoauthclientsauthorizationsettingspoliciesscopesdata)
            * [`fn withDisplayName(displayName)`](#fn-specrealmoauthclientsauthorizationsettingspoliciesscopesdatawithdisplayname)
            * [`fn withIconUri(iconUri)`](#fn-specrealmoauthclientsauthorizationsettingspoliciesscopesdatawithiconuri)
            * [`fn withId(id)`](#fn-specrealmoauthclientsauthorizationsettingspoliciesscopesdatawithid)
            * [`fn withName(name)`](#fn-specrealmoauthclientsauthorizationsettingspoliciesscopesdatawithname)
        * [`obj spec.realm.oauthClients.authorizationSettings.resources`](#obj-specrealmoauthclientsauthorizationsettingsresources)
          * [`fn withAttributes(attributes)`](#fn-specrealmoauthclientsauthorizationsettingsresourceswithattributes)
          * [`fn withAttributesMixin(attributes)`](#fn-specrealmoauthclientsauthorizationsettingsresourceswithattributesmixin)
          * [`fn withDisplayName(displayName)`](#fn-specrealmoauthclientsauthorizationsettingsresourceswithdisplayname)
          * [`fn withIcon_uri(icon_uri)`](#fn-specrealmoauthclientsauthorizationsettingsresourceswithicon_uri)
          * [`fn withName(name)`](#fn-specrealmoauthclientsauthorizationsettingsresourceswithname)
          * [`fn withOwnerManagedAccess(ownerManagedAccess)`](#fn-specrealmoauthclientsauthorizationsettingsresourceswithownermanagedaccess)
          * [`fn withScopes(scopes)`](#fn-specrealmoauthclientsauthorizationsettingsresourceswithscopes)
          * [`fn withScopesMixin(scopes)`](#fn-specrealmoauthclientsauthorizationsettingsresourceswithscopesmixin)
          * [`fn withType(type)`](#fn-specrealmoauthclientsauthorizationsettingsresourceswithtype)
          * [`fn withUris(uris)`](#fn-specrealmoauthclientsauthorizationsettingsresourceswithuris)
          * [`fn withUrisMixin(uris)`](#fn-specrealmoauthclientsauthorizationsettingsresourceswithurismixin)
          * [`fn with_id(_id)`](#fn-specrealmoauthclientsauthorizationsettingsresourceswith_id)
          * [`obj spec.realm.oauthClients.authorizationSettings.resources.owner`](#obj-specrealmoauthclientsauthorizationsettingsresourcesowner)
            * [`fn withId(id)`](#fn-specrealmoauthclientsauthorizationsettingsresourcesownerwithid)
            * [`fn withName(name)`](#fn-specrealmoauthclientsauthorizationsettingsresourcesownerwithname)
          * [`obj spec.realm.oauthClients.authorizationSettings.resources.scopes`](#obj-specrealmoauthclientsauthorizationsettingsresourcesscopes)
            * [`fn withDisplayName(displayName)`](#fn-specrealmoauthclientsauthorizationsettingsresourcesscopeswithdisplayname)
            * [`fn withIconUri(iconUri)`](#fn-specrealmoauthclientsauthorizationsettingsresourcesscopeswithiconuri)
            * [`fn withId(id)`](#fn-specrealmoauthclientsauthorizationsettingsresourcesscopeswithid)
            * [`fn withName(name)`](#fn-specrealmoauthclientsauthorizationsettingsresourcesscopeswithname)
        * [`obj spec.realm.oauthClients.authorizationSettings.scopes`](#obj-specrealmoauthclientsauthorizationsettingsscopes)
          * [`fn withDisplayName(displayName)`](#fn-specrealmoauthclientsauthorizationsettingsscopeswithdisplayname)
          * [`fn withIconUri(iconUri)`](#fn-specrealmoauthclientsauthorizationsettingsscopeswithiconuri)
          * [`fn withId(id)`](#fn-specrealmoauthclientsauthorizationsettingsscopeswithid)
          * [`fn withName(name)`](#fn-specrealmoauthclientsauthorizationsettingsscopeswithname)
      * [`obj spec.realm.oauthClients.claims`](#obj-specrealmoauthclientsclaims)
        * [`fn withAddress(address)`](#fn-specrealmoauthclientsclaimswithaddress)
        * [`fn withEmail(email)`](#fn-specrealmoauthclientsclaimswithemail)
        * [`fn withGender(gender)`](#fn-specrealmoauthclientsclaimswithgender)
        * [`fn withLocale(locale)`](#fn-specrealmoauthclientsclaimswithlocale)
        * [`fn withName(name)`](#fn-specrealmoauthclientsclaimswithname)
        * [`fn withPhone(phone)`](#fn-specrealmoauthclientsclaimswithphone)
        * [`fn withPicture(picture)`](#fn-specrealmoauthclientsclaimswithpicture)
        * [`fn withProfile(profile)`](#fn-specrealmoauthclientsclaimswithprofile)
        * [`fn withUsername(username)`](#fn-specrealmoauthclientsclaimswithusername)
        * [`fn withWebsite(website)`](#fn-specrealmoauthclientsclaimswithwebsite)
      * [`obj spec.realm.oauthClients.protocolMappers`](#obj-specrealmoauthclientsprotocolmappers)
        * [`fn withConfig(config)`](#fn-specrealmoauthclientsprotocolmapperswithconfig)
        * [`fn withConfigMixin(config)`](#fn-specrealmoauthclientsprotocolmapperswithconfigmixin)
        * [`fn withConsentRequired(consentRequired)`](#fn-specrealmoauthclientsprotocolmapperswithconsentrequired)
        * [`fn withConsentText(consentText)`](#fn-specrealmoauthclientsprotocolmapperswithconsenttext)
        * [`fn withId(id)`](#fn-specrealmoauthclientsprotocolmapperswithid)
        * [`fn withName(name)`](#fn-specrealmoauthclientsprotocolmapperswithname)
        * [`fn withProtocol(protocol)`](#fn-specrealmoauthclientsprotocolmapperswithprotocol)
        * [`fn withProtocolMapper(protocolMapper)`](#fn-specrealmoauthclientsprotocolmapperswithprotocolmapper)
    * [`obj spec.realm.organizations`](#obj-specrealmorganizations)
      * [`fn withAlias(alias)`](#fn-specrealmorganizationswithalias)
      * [`fn withAttributes(attributes)`](#fn-specrealmorganizationswithattributes)
      * [`fn withAttributesMixin(attributes)`](#fn-specrealmorganizationswithattributesmixin)
      * [`fn withDescription(description)`](#fn-specrealmorganizationswithdescription)
      * [`fn withDomains(domains)`](#fn-specrealmorganizationswithdomains)
      * [`fn withDomainsMixin(domains)`](#fn-specrealmorganizationswithdomainsmixin)
      * [`fn withEnabled(enabled)`](#fn-specrealmorganizationswithenabled)
      * [`fn withId(id)`](#fn-specrealmorganizationswithid)
      * [`fn withIdentityProviders(identityProviders)`](#fn-specrealmorganizationswithidentityproviders)
      * [`fn withIdentityProvidersMixin(identityProviders)`](#fn-specrealmorganizationswithidentityprovidersmixin)
      * [`fn withMembers(members)`](#fn-specrealmorganizationswithmembers)
      * [`fn withMembersMixin(members)`](#fn-specrealmorganizationswithmembersmixin)
      * [`fn withName(name)`](#fn-specrealmorganizationswithname)
      * [`fn withRedirectUrl(redirectUrl)`](#fn-specrealmorganizationswithredirecturl)
      * [`obj spec.realm.organizations.domains`](#obj-specrealmorganizationsdomains)
        * [`fn withName(name)`](#fn-specrealmorganizationsdomainswithname)
        * [`fn withVerified(verified)`](#fn-specrealmorganizationsdomainswithverified)
      * [`obj spec.realm.organizations.identityProviders`](#obj-specrealmorganizationsidentityproviders)
        * [`fn withAddReadTokenRoleOnCreate(addReadTokenRoleOnCreate)`](#fn-specrealmorganizationsidentityproviderswithaddreadtokenroleoncreate)
        * [`fn withAlias(alias)`](#fn-specrealmorganizationsidentityproviderswithalias)
        * [`fn withAuthenticateByDefault(authenticateByDefault)`](#fn-specrealmorganizationsidentityproviderswithauthenticatebydefault)
        * [`fn withConfig(config)`](#fn-specrealmorganizationsidentityproviderswithconfig)
        * [`fn withConfigMixin(config)`](#fn-specrealmorganizationsidentityproviderswithconfigmixin)
        * [`fn withDisplayName(displayName)`](#fn-specrealmorganizationsidentityproviderswithdisplayname)
        * [`fn withEnabled(enabled)`](#fn-specrealmorganizationsidentityproviderswithenabled)
        * [`fn withFirstBrokerLoginFlowAlias(firstBrokerLoginFlowAlias)`](#fn-specrealmorganizationsidentityproviderswithfirstbrokerloginflowalias)
        * [`fn withHideOnLogin(hideOnLogin)`](#fn-specrealmorganizationsidentityproviderswithhideonlogin)
        * [`fn withInternalId(internalId)`](#fn-specrealmorganizationsidentityproviderswithinternalid)
        * [`fn withLinkOnly(linkOnly)`](#fn-specrealmorganizationsidentityproviderswithlinkonly)
        * [`fn withOrganizationId(organizationId)`](#fn-specrealmorganizationsidentityproviderswithorganizationid)
        * [`fn withPostBrokerLoginFlowAlias(postBrokerLoginFlowAlias)`](#fn-specrealmorganizationsidentityproviderswithpostbrokerloginflowalias)
        * [`fn withProviderId(providerId)`](#fn-specrealmorganizationsidentityproviderswithproviderid)
        * [`fn withStoreToken(storeToken)`](#fn-specrealmorganizationsidentityproviderswithstoretoken)
        * [`fn withTrustEmail(trustEmail)`](#fn-specrealmorganizationsidentityproviderswithtrustemail)
        * [`fn withUpdateProfileFirstLoginMode(updateProfileFirstLoginMode)`](#fn-specrealmorganizationsidentityproviderswithupdateprofilefirstloginmode)
      * [`obj spec.realm.organizations.members`](#obj-specrealmorganizationsmembers)
        * [`fn withAccess(access)`](#fn-specrealmorganizationsmemberswithaccess)
        * [`fn withAccessMixin(access)`](#fn-specrealmorganizationsmemberswithaccessmixin)
        * [`fn withApplicationRoles(applicationRoles)`](#fn-specrealmorganizationsmemberswithapplicationroles)
        * [`fn withApplicationRolesMixin(applicationRoles)`](#fn-specrealmorganizationsmemberswithapplicationrolesmixin)
        * [`fn withAttributes(attributes)`](#fn-specrealmorganizationsmemberswithattributes)
        * [`fn withAttributesMixin(attributes)`](#fn-specrealmorganizationsmemberswithattributesmixin)
        * [`fn withClientConsents(clientConsents)`](#fn-specrealmorganizationsmemberswithclientconsents)
        * [`fn withClientConsentsMixin(clientConsents)`](#fn-specrealmorganizationsmemberswithclientconsentsmixin)
        * [`fn withClientRoles(clientRoles)`](#fn-specrealmorganizationsmemberswithclientroles)
        * [`fn withClientRolesMixin(clientRoles)`](#fn-specrealmorganizationsmemberswithclientrolesmixin)
        * [`fn withCreatedTimestamp(createdTimestamp)`](#fn-specrealmorganizationsmemberswithcreatedtimestamp)
        * [`fn withCredentials(credentials)`](#fn-specrealmorganizationsmemberswithcredentials)
        * [`fn withCredentialsMixin(credentials)`](#fn-specrealmorganizationsmemberswithcredentialsmixin)
        * [`fn withDisableableCredentialTypes(disableableCredentialTypes)`](#fn-specrealmorganizationsmemberswithdisableablecredentialtypes)
        * [`fn withDisableableCredentialTypesMixin(disableableCredentialTypes)`](#fn-specrealmorganizationsmemberswithdisableablecredentialtypesmixin)
        * [`fn withEmail(email)`](#fn-specrealmorganizationsmemberswithemail)
        * [`fn withEmailVerified(emailVerified)`](#fn-specrealmorganizationsmemberswithemailverified)
        * [`fn withEnabled(enabled)`](#fn-specrealmorganizationsmemberswithenabled)
        * [`fn withFederatedIdentities(federatedIdentities)`](#fn-specrealmorganizationsmemberswithfederatedidentities)
        * [`fn withFederatedIdentitiesMixin(federatedIdentities)`](#fn-specrealmorganizationsmemberswithfederatedidentitiesmixin)
        * [`fn withFederationLink(federationLink)`](#fn-specrealmorganizationsmemberswithfederationlink)
        * [`fn withFirstName(firstName)`](#fn-specrealmorganizationsmemberswithfirstname)
        * [`fn withGroups(groups)`](#fn-specrealmorganizationsmemberswithgroups)
        * [`fn withGroupsMixin(groups)`](#fn-specrealmorganizationsmemberswithgroupsmixin)
        * [`fn withId(id)`](#fn-specrealmorganizationsmemberswithid)
        * [`fn withLastName(lastName)`](#fn-specrealmorganizationsmemberswithlastname)
        * [`fn withMembershipType(membershipType)`](#fn-specrealmorganizationsmemberswithmembershiptype)
        * [`fn withNotBefore(notBefore)`](#fn-specrealmorganizationsmemberswithnotbefore)
        * [`fn withOrigin(origin)`](#fn-specrealmorganizationsmemberswithorigin)
        * [`fn withRealmRoles(realmRoles)`](#fn-specrealmorganizationsmemberswithrealmroles)
        * [`fn withRealmRolesMixin(realmRoles)`](#fn-specrealmorganizationsmemberswithrealmrolesmixin)
        * [`fn withRequiredActions(requiredActions)`](#fn-specrealmorganizationsmemberswithrequiredactions)
        * [`fn withRequiredActionsMixin(requiredActions)`](#fn-specrealmorganizationsmemberswithrequiredactionsmixin)
        * [`fn withSelf(Self)`](#fn-specrealmorganizationsmemberswithself)
        * [`fn withServiceAccountClientId(serviceAccountClientId)`](#fn-specrealmorganizationsmemberswithserviceaccountclientid)
        * [`fn withSocialLinks(socialLinks)`](#fn-specrealmorganizationsmemberswithsociallinks)
        * [`fn withSocialLinksMixin(socialLinks)`](#fn-specrealmorganizationsmemberswithsociallinksmixin)
        * [`fn withTotp(totp)`](#fn-specrealmorganizationsmemberswithtotp)
        * [`fn withUsername(username)`](#fn-specrealmorganizationsmemberswithusername)
        * [`obj spec.realm.organizations.members.clientConsents`](#obj-specrealmorganizationsmembersclientconsents)
          * [`fn withClientId(clientId)`](#fn-specrealmorganizationsmembersclientconsentswithclientid)
          * [`fn withCreatedDate(createdDate)`](#fn-specrealmorganizationsmembersclientconsentswithcreateddate)
          * [`fn withGrantedClientScopes(grantedClientScopes)`](#fn-specrealmorganizationsmembersclientconsentswithgrantedclientscopes)
          * [`fn withGrantedClientScopesMixin(grantedClientScopes)`](#fn-specrealmorganizationsmembersclientconsentswithgrantedclientscopesmixin)
          * [`fn withGrantedRealmRoles(grantedRealmRoles)`](#fn-specrealmorganizationsmembersclientconsentswithgrantedrealmroles)
          * [`fn withGrantedRealmRolesMixin(grantedRealmRoles)`](#fn-specrealmorganizationsmembersclientconsentswithgrantedrealmrolesmixin)
          * [`fn withLastUpdatedDate(lastUpdatedDate)`](#fn-specrealmorganizationsmembersclientconsentswithlastupdateddate)
        * [`obj spec.realm.organizations.members.credentials`](#obj-specrealmorganizationsmemberscredentials)
          * [`fn withAlgorithm(algorithm)`](#fn-specrealmorganizationsmemberscredentialswithalgorithm)
          * [`fn withConfig(config)`](#fn-specrealmorganizationsmemberscredentialswithconfig)
          * [`fn withConfigMixin(config)`](#fn-specrealmorganizationsmemberscredentialswithconfigmixin)
          * [`fn withCounter(counter)`](#fn-specrealmorganizationsmemberscredentialswithcounter)
          * [`fn withCreatedDate(createdDate)`](#fn-specrealmorganizationsmemberscredentialswithcreateddate)
          * [`fn withCredentialData(credentialData)`](#fn-specrealmorganizationsmemberscredentialswithcredentialdata)
          * [`fn withDevice(device)`](#fn-specrealmorganizationsmemberscredentialswithdevice)
          * [`fn withDigits(digits)`](#fn-specrealmorganizationsmemberscredentialswithdigits)
          * [`fn withFederationLink(federationLink)`](#fn-specrealmorganizationsmemberscredentialswithfederationlink)
          * [`fn withHashIterations(hashIterations)`](#fn-specrealmorganizationsmemberscredentialswithhashiterations)
          * [`fn withHashedSaltedValue(hashedSaltedValue)`](#fn-specrealmorganizationsmemberscredentialswithhashedsaltedvalue)
          * [`fn withId(id)`](#fn-specrealmorganizationsmemberscredentialswithid)
          * [`fn withPeriod(period)`](#fn-specrealmorganizationsmemberscredentialswithperiod)
          * [`fn withPriority(priority)`](#fn-specrealmorganizationsmemberscredentialswithpriority)
          * [`fn withSalt(salt)`](#fn-specrealmorganizationsmemberscredentialswithsalt)
          * [`fn withSecretData(secretData)`](#fn-specrealmorganizationsmemberscredentialswithsecretdata)
          * [`fn withTemporary(temporary)`](#fn-specrealmorganizationsmemberscredentialswithtemporary)
          * [`fn withType(type)`](#fn-specrealmorganizationsmemberscredentialswithtype)
          * [`fn withUserLabel(userLabel)`](#fn-specrealmorganizationsmemberscredentialswithuserlabel)
          * [`fn withValue(value)`](#fn-specrealmorganizationsmemberscredentialswithvalue)
        * [`obj spec.realm.organizations.members.federatedIdentities`](#obj-specrealmorganizationsmembersfederatedidentities)
          * [`fn withIdentityProvider(identityProvider)`](#fn-specrealmorganizationsmembersfederatedidentitieswithidentityprovider)
          * [`fn withUserId(userId)`](#fn-specrealmorganizationsmembersfederatedidentitieswithuserid)
          * [`fn withUserName(userName)`](#fn-specrealmorganizationsmembersfederatedidentitieswithusername)
        * [`obj spec.realm.organizations.members.socialLinks`](#obj-specrealmorganizationsmemberssociallinks)
          * [`fn withSocialProvider(socialProvider)`](#fn-specrealmorganizationsmemberssociallinkswithsocialprovider)
          * [`fn withSocialUserId(socialUserId)`](#fn-specrealmorganizationsmemberssociallinkswithsocialuserid)
          * [`fn withSocialUsername(socialUsername)`](#fn-specrealmorganizationsmemberssociallinkswithsocialusername)
        * [`obj spec.realm.organizations.members.userProfileMetadata`](#obj-specrealmorganizationsmembersuserprofilemetadata)
          * [`fn withAttributes(attributes)`](#fn-specrealmorganizationsmembersuserprofilemetadatawithattributes)
          * [`fn withAttributesMixin(attributes)`](#fn-specrealmorganizationsmembersuserprofilemetadatawithattributesmixin)
          * [`fn withGroups(groups)`](#fn-specrealmorganizationsmembersuserprofilemetadatawithgroups)
          * [`fn withGroupsMixin(groups)`](#fn-specrealmorganizationsmembersuserprofilemetadatawithgroupsmixin)
          * [`obj spec.realm.organizations.members.userProfileMetadata.attributes`](#obj-specrealmorganizationsmembersuserprofilemetadataattributes)
            * [`fn withAnnotations(annotations)`](#fn-specrealmorganizationsmembersuserprofilemetadataattributeswithannotations)
            * [`fn withAnnotationsMixin(annotations)`](#fn-specrealmorganizationsmembersuserprofilemetadataattributeswithannotationsmixin)
            * [`fn withDefaultValue(defaultValue)`](#fn-specrealmorganizationsmembersuserprofilemetadataattributeswithdefaultvalue)
            * [`fn withDisplayName(displayName)`](#fn-specrealmorganizationsmembersuserprofilemetadataattributeswithdisplayname)
            * [`fn withGroup(group)`](#fn-specrealmorganizationsmembersuserprofilemetadataattributeswithgroup)
            * [`fn withMultivalued(multivalued)`](#fn-specrealmorganizationsmembersuserprofilemetadataattributeswithmultivalued)
            * [`fn withName(name)`](#fn-specrealmorganizationsmembersuserprofilemetadataattributeswithname)
            * [`fn withReadOnly(readOnly)`](#fn-specrealmorganizationsmembersuserprofilemetadataattributeswithreadonly)
            * [`fn withRequired(required)`](#fn-specrealmorganizationsmembersuserprofilemetadataattributeswithrequired)
            * [`fn withValidators(validators)`](#fn-specrealmorganizationsmembersuserprofilemetadataattributeswithvalidators)
            * [`fn withValidatorsMixin(validators)`](#fn-specrealmorganizationsmembersuserprofilemetadataattributeswithvalidatorsmixin)
          * [`obj spec.realm.organizations.members.userProfileMetadata.groups`](#obj-specrealmorganizationsmembersuserprofilemetadatagroups)
            * [`fn withAnnotations(annotations)`](#fn-specrealmorganizationsmembersuserprofilemetadatagroupswithannotations)
            * [`fn withAnnotationsMixin(annotations)`](#fn-specrealmorganizationsmembersuserprofilemetadatagroupswithannotationsmixin)
            * [`fn withDisplayDescription(displayDescription)`](#fn-specrealmorganizationsmembersuserprofilemetadatagroupswithdisplaydescription)
            * [`fn withDisplayHeader(displayHeader)`](#fn-specrealmorganizationsmembersuserprofilemetadatagroupswithdisplayheader)
            * [`fn withName(name)`](#fn-specrealmorganizationsmembersuserprofilemetadatagroupswithname)
    * [`obj spec.realm.protocolMappers`](#obj-specrealmprotocolmappers)
      * [`fn withConfig(config)`](#fn-specrealmprotocolmapperswithconfig)
      * [`fn withConfigMixin(config)`](#fn-specrealmprotocolmapperswithconfigmixin)
      * [`fn withConsentRequired(consentRequired)`](#fn-specrealmprotocolmapperswithconsentrequired)
      * [`fn withConsentText(consentText)`](#fn-specrealmprotocolmapperswithconsenttext)
      * [`fn withId(id)`](#fn-specrealmprotocolmapperswithid)
      * [`fn withName(name)`](#fn-specrealmprotocolmapperswithname)
      * [`fn withProtocol(protocol)`](#fn-specrealmprotocolmapperswithprotocol)
      * [`fn withProtocolMapper(protocolMapper)`](#fn-specrealmprotocolmapperswithprotocolmapper)
    * [`obj spec.realm.requiredActions`](#obj-specrealmrequiredactions)
      * [`fn withAlias(alias)`](#fn-specrealmrequiredactionswithalias)
      * [`fn withConfig(config)`](#fn-specrealmrequiredactionswithconfig)
      * [`fn withConfigMixin(config)`](#fn-specrealmrequiredactionswithconfigmixin)
      * [`fn withDefaultAction(defaultAction)`](#fn-specrealmrequiredactionswithdefaultaction)
      * [`fn withEnabled(enabled)`](#fn-specrealmrequiredactionswithenabled)
      * [`fn withName(name)`](#fn-specrealmrequiredactionswithname)
      * [`fn withPriority(priority)`](#fn-specrealmrequiredactionswithpriority)
      * [`fn withProviderId(providerId)`](#fn-specrealmrequiredactionswithproviderid)
    * [`obj spec.realm.roles`](#obj-specrealmroles)
      * [`fn withApplication(application)`](#fn-specrealmroleswithapplication)
      * [`fn withApplicationMixin(application)`](#fn-specrealmroleswithapplicationmixin)
      * [`fn withClient(client)`](#fn-specrealmroleswithclient)
      * [`fn withClientMixin(client)`](#fn-specrealmroleswithclientmixin)
      * [`fn withRealm(realm)`](#fn-specrealmroleswithrealm)
      * [`fn withRealmMixin(realm)`](#fn-specrealmroleswithrealmmixin)
      * [`obj spec.realm.roles.realm`](#obj-specrealmrolesrealm)
        * [`fn withAttributes(attributes)`](#fn-specrealmrolesrealmwithattributes)
        * [`fn withAttributesMixin(attributes)`](#fn-specrealmrolesrealmwithattributesmixin)
        * [`fn withClientRole(clientRole)`](#fn-specrealmrolesrealmwithclientrole)
        * [`fn withComposite(composite)`](#fn-specrealmrolesrealmwithcomposite)
        * [`fn withContainerId(containerId)`](#fn-specrealmrolesrealmwithcontainerid)
        * [`fn withDescription(description)`](#fn-specrealmrolesrealmwithdescription)
        * [`fn withId(id)`](#fn-specrealmrolesrealmwithid)
        * [`fn withName(name)`](#fn-specrealmrolesrealmwithname)
        * [`fn withScopeParamRequired(scopeParamRequired)`](#fn-specrealmrolesrealmwithscopeparamrequired)
        * [`obj spec.realm.roles.realm.composites`](#obj-specrealmrolesrealmcomposites)
          * [`fn withApplication(application)`](#fn-specrealmrolesrealmcompositeswithapplication)
          * [`fn withApplicationMixin(application)`](#fn-specrealmrolesrealmcompositeswithapplicationmixin)
          * [`fn withClient(client)`](#fn-specrealmrolesrealmcompositeswithclient)
          * [`fn withClientMixin(client)`](#fn-specrealmrolesrealmcompositeswithclientmixin)
          * [`fn withRealm(realm)`](#fn-specrealmrolesrealmcompositeswithrealm)
          * [`fn withRealmMixin(realm)`](#fn-specrealmrolesrealmcompositeswithrealmmixin)
    * [`obj spec.realm.scopeMappings`](#obj-specrealmscopemappings)
      * [`fn withClient(client)`](#fn-specrealmscopemappingswithclient)
      * [`fn withClientScope(clientScope)`](#fn-specrealmscopemappingswithclientscope)
      * [`fn withClientTemplate(clientTemplate)`](#fn-specrealmscopemappingswithclienttemplate)
      * [`fn withRoles(roles)`](#fn-specrealmscopemappingswithroles)
      * [`fn withRolesMixin(roles)`](#fn-specrealmscopemappingswithrolesmixin)
      * [`fn withSelf(Self)`](#fn-specrealmscopemappingswithself)
    * [`obj spec.realm.userFederationMappers`](#obj-specrealmuserfederationmappers)
      * [`fn withConfig(config)`](#fn-specrealmuserfederationmapperswithconfig)
      * [`fn withConfigMixin(config)`](#fn-specrealmuserfederationmapperswithconfigmixin)
      * [`fn withFederationMapperType(federationMapperType)`](#fn-specrealmuserfederationmapperswithfederationmappertype)
      * [`fn withFederationProviderDisplayName(federationProviderDisplayName)`](#fn-specrealmuserfederationmapperswithfederationproviderdisplayname)
      * [`fn withId(id)`](#fn-specrealmuserfederationmapperswithid)
      * [`fn withName(name)`](#fn-specrealmuserfederationmapperswithname)
    * [`obj spec.realm.userFederationProviders`](#obj-specrealmuserfederationproviders)
      * [`fn withChangedSyncPeriod(changedSyncPeriod)`](#fn-specrealmuserfederationproviderswithchangedsyncperiod)
      * [`fn withConfig(config)`](#fn-specrealmuserfederationproviderswithconfig)
      * [`fn withConfigMixin(config)`](#fn-specrealmuserfederationproviderswithconfigmixin)
      * [`fn withDisplayName(displayName)`](#fn-specrealmuserfederationproviderswithdisplayname)
      * [`fn withFullSyncPeriod(fullSyncPeriod)`](#fn-specrealmuserfederationproviderswithfullsyncperiod)
      * [`fn withId(id)`](#fn-specrealmuserfederationproviderswithid)
      * [`fn withLastSync(lastSync)`](#fn-specrealmuserfederationproviderswithlastsync)
      * [`fn withPriority(priority)`](#fn-specrealmuserfederationproviderswithpriority)
      * [`fn withProviderName(providerName)`](#fn-specrealmuserfederationproviderswithprovidername)
    * [`obj spec.realm.users`](#obj-specrealmusers)
      * [`fn withAccess(access)`](#fn-specrealmuserswithaccess)
      * [`fn withAccessMixin(access)`](#fn-specrealmuserswithaccessmixin)
      * [`fn withApplicationRoles(applicationRoles)`](#fn-specrealmuserswithapplicationroles)
      * [`fn withApplicationRolesMixin(applicationRoles)`](#fn-specrealmuserswithapplicationrolesmixin)
      * [`fn withAttributes(attributes)`](#fn-specrealmuserswithattributes)
      * [`fn withAttributesMixin(attributes)`](#fn-specrealmuserswithattributesmixin)
      * [`fn withClientConsents(clientConsents)`](#fn-specrealmuserswithclientconsents)
      * [`fn withClientConsentsMixin(clientConsents)`](#fn-specrealmuserswithclientconsentsmixin)
      * [`fn withClientRoles(clientRoles)`](#fn-specrealmuserswithclientroles)
      * [`fn withClientRolesMixin(clientRoles)`](#fn-specrealmuserswithclientrolesmixin)
      * [`fn withCreatedTimestamp(createdTimestamp)`](#fn-specrealmuserswithcreatedtimestamp)
      * [`fn withCredentials(credentials)`](#fn-specrealmuserswithcredentials)
      * [`fn withCredentialsMixin(credentials)`](#fn-specrealmuserswithcredentialsmixin)
      * [`fn withDisableableCredentialTypes(disableableCredentialTypes)`](#fn-specrealmuserswithdisableablecredentialtypes)
      * [`fn withDisableableCredentialTypesMixin(disableableCredentialTypes)`](#fn-specrealmuserswithdisableablecredentialtypesmixin)
      * [`fn withEmail(email)`](#fn-specrealmuserswithemail)
      * [`fn withEmailVerified(emailVerified)`](#fn-specrealmuserswithemailverified)
      * [`fn withEnabled(enabled)`](#fn-specrealmuserswithenabled)
      * [`fn withFederatedIdentities(federatedIdentities)`](#fn-specrealmuserswithfederatedidentities)
      * [`fn withFederatedIdentitiesMixin(federatedIdentities)`](#fn-specrealmuserswithfederatedidentitiesmixin)
      * [`fn withFederationLink(federationLink)`](#fn-specrealmuserswithfederationlink)
      * [`fn withFirstName(firstName)`](#fn-specrealmuserswithfirstname)
      * [`fn withGroups(groups)`](#fn-specrealmuserswithgroups)
      * [`fn withGroupsMixin(groups)`](#fn-specrealmuserswithgroupsmixin)
      * [`fn withId(id)`](#fn-specrealmuserswithid)
      * [`fn withLastName(lastName)`](#fn-specrealmuserswithlastname)
      * [`fn withNotBefore(notBefore)`](#fn-specrealmuserswithnotbefore)
      * [`fn withOrigin(origin)`](#fn-specrealmuserswithorigin)
      * [`fn withRealmRoles(realmRoles)`](#fn-specrealmuserswithrealmroles)
      * [`fn withRealmRolesMixin(realmRoles)`](#fn-specrealmuserswithrealmrolesmixin)
      * [`fn withRequiredActions(requiredActions)`](#fn-specrealmuserswithrequiredactions)
      * [`fn withRequiredActionsMixin(requiredActions)`](#fn-specrealmuserswithrequiredactionsmixin)
      * [`fn withSelf(Self)`](#fn-specrealmuserswithself)
      * [`fn withServiceAccountClientId(serviceAccountClientId)`](#fn-specrealmuserswithserviceaccountclientid)
      * [`fn withSocialLinks(socialLinks)`](#fn-specrealmuserswithsociallinks)
      * [`fn withSocialLinksMixin(socialLinks)`](#fn-specrealmuserswithsociallinksmixin)
      * [`fn withTotp(totp)`](#fn-specrealmuserswithtotp)
      * [`fn withUsername(username)`](#fn-specrealmuserswithusername)
      * [`obj spec.realm.users.clientConsents`](#obj-specrealmusersclientconsents)
        * [`fn withClientId(clientId)`](#fn-specrealmusersclientconsentswithclientid)
        * [`fn withCreatedDate(createdDate)`](#fn-specrealmusersclientconsentswithcreateddate)
        * [`fn withGrantedClientScopes(grantedClientScopes)`](#fn-specrealmusersclientconsentswithgrantedclientscopes)
        * [`fn withGrantedClientScopesMixin(grantedClientScopes)`](#fn-specrealmusersclientconsentswithgrantedclientscopesmixin)
        * [`fn withGrantedRealmRoles(grantedRealmRoles)`](#fn-specrealmusersclientconsentswithgrantedrealmroles)
        * [`fn withGrantedRealmRolesMixin(grantedRealmRoles)`](#fn-specrealmusersclientconsentswithgrantedrealmrolesmixin)
        * [`fn withLastUpdatedDate(lastUpdatedDate)`](#fn-specrealmusersclientconsentswithlastupdateddate)
      * [`obj spec.realm.users.credentials`](#obj-specrealmuserscredentials)
        * [`fn withAlgorithm(algorithm)`](#fn-specrealmuserscredentialswithalgorithm)
        * [`fn withConfig(config)`](#fn-specrealmuserscredentialswithconfig)
        * [`fn withConfigMixin(config)`](#fn-specrealmuserscredentialswithconfigmixin)
        * [`fn withCounter(counter)`](#fn-specrealmuserscredentialswithcounter)
        * [`fn withCreatedDate(createdDate)`](#fn-specrealmuserscredentialswithcreateddate)
        * [`fn withCredentialData(credentialData)`](#fn-specrealmuserscredentialswithcredentialdata)
        * [`fn withDevice(device)`](#fn-specrealmuserscredentialswithdevice)
        * [`fn withDigits(digits)`](#fn-specrealmuserscredentialswithdigits)
        * [`fn withFederationLink(federationLink)`](#fn-specrealmuserscredentialswithfederationlink)
        * [`fn withHashIterations(hashIterations)`](#fn-specrealmuserscredentialswithhashiterations)
        * [`fn withHashedSaltedValue(hashedSaltedValue)`](#fn-specrealmuserscredentialswithhashedsaltedvalue)
        * [`fn withId(id)`](#fn-specrealmuserscredentialswithid)
        * [`fn withPeriod(period)`](#fn-specrealmuserscredentialswithperiod)
        * [`fn withPriority(priority)`](#fn-specrealmuserscredentialswithpriority)
        * [`fn withSalt(salt)`](#fn-specrealmuserscredentialswithsalt)
        * [`fn withSecretData(secretData)`](#fn-specrealmuserscredentialswithsecretdata)
        * [`fn withTemporary(temporary)`](#fn-specrealmuserscredentialswithtemporary)
        * [`fn withType(type)`](#fn-specrealmuserscredentialswithtype)
        * [`fn withUserLabel(userLabel)`](#fn-specrealmuserscredentialswithuserlabel)
        * [`fn withValue(value)`](#fn-specrealmuserscredentialswithvalue)
      * [`obj spec.realm.users.federatedIdentities`](#obj-specrealmusersfederatedidentities)
        * [`fn withIdentityProvider(identityProvider)`](#fn-specrealmusersfederatedidentitieswithidentityprovider)
        * [`fn withUserId(userId)`](#fn-specrealmusersfederatedidentitieswithuserid)
        * [`fn withUserName(userName)`](#fn-specrealmusersfederatedidentitieswithusername)
      * [`obj spec.realm.users.socialLinks`](#obj-specrealmuserssociallinks)
        * [`fn withSocialProvider(socialProvider)`](#fn-specrealmuserssociallinkswithsocialprovider)
        * [`fn withSocialUserId(socialUserId)`](#fn-specrealmuserssociallinkswithsocialuserid)
        * [`fn withSocialUsername(socialUsername)`](#fn-specrealmuserssociallinkswithsocialusername)
      * [`obj spec.realm.users.userProfileMetadata`](#obj-specrealmusersuserprofilemetadata)
        * [`fn withAttributes(attributes)`](#fn-specrealmusersuserprofilemetadatawithattributes)
        * [`fn withAttributesMixin(attributes)`](#fn-specrealmusersuserprofilemetadatawithattributesmixin)
        * [`fn withGroups(groups)`](#fn-specrealmusersuserprofilemetadatawithgroups)
        * [`fn withGroupsMixin(groups)`](#fn-specrealmusersuserprofilemetadatawithgroupsmixin)
        * [`obj spec.realm.users.userProfileMetadata.attributes`](#obj-specrealmusersuserprofilemetadataattributes)
          * [`fn withAnnotations(annotations)`](#fn-specrealmusersuserprofilemetadataattributeswithannotations)
          * [`fn withAnnotationsMixin(annotations)`](#fn-specrealmusersuserprofilemetadataattributeswithannotationsmixin)
          * [`fn withDefaultValue(defaultValue)`](#fn-specrealmusersuserprofilemetadataattributeswithdefaultvalue)
          * [`fn withDisplayName(displayName)`](#fn-specrealmusersuserprofilemetadataattributeswithdisplayname)
          * [`fn withGroup(group)`](#fn-specrealmusersuserprofilemetadataattributeswithgroup)
          * [`fn withMultivalued(multivalued)`](#fn-specrealmusersuserprofilemetadataattributeswithmultivalued)
          * [`fn withName(name)`](#fn-specrealmusersuserprofilemetadataattributeswithname)
          * [`fn withReadOnly(readOnly)`](#fn-specrealmusersuserprofilemetadataattributeswithreadonly)
          * [`fn withRequired(required)`](#fn-specrealmusersuserprofilemetadataattributeswithrequired)
          * [`fn withValidators(validators)`](#fn-specrealmusersuserprofilemetadataattributeswithvalidators)
          * [`fn withValidatorsMixin(validators)`](#fn-specrealmusersuserprofilemetadataattributeswithvalidatorsmixin)
        * [`obj spec.realm.users.userProfileMetadata.groups`](#obj-specrealmusersuserprofilemetadatagroups)
          * [`fn withAnnotations(annotations)`](#fn-specrealmusersuserprofilemetadatagroupswithannotations)
          * [`fn withAnnotationsMixin(annotations)`](#fn-specrealmusersuserprofilemetadatagroupswithannotationsmixin)
          * [`fn withDisplayDescription(displayDescription)`](#fn-specrealmusersuserprofilemetadatagroupswithdisplaydescription)
          * [`fn withDisplayHeader(displayHeader)`](#fn-specrealmusersuserprofilemetadatagroupswithdisplayheader)
          * [`fn withName(name)`](#fn-specrealmusersuserprofilemetadatagroupswithname)
  * [`obj spec.resources`](#obj-specresources)
    * [`fn withClaims(claims)`](#fn-specresourceswithclaims)
    * [`fn withClaimsMixin(claims)`](#fn-specresourceswithclaimsmixin)
    * [`fn withLimits(limits)`](#fn-specresourceswithlimits)
    * [`fn withLimitsMixin(limits)`](#fn-specresourceswithlimitsmixin)
    * [`fn withRequests(requests)`](#fn-specresourceswithrequests)
    * [`fn withRequestsMixin(requests)`](#fn-specresourceswithrequestsmixin)
    * [`obj spec.resources.claims`](#obj-specresourcesclaims)
      * [`fn withName(name)`](#fn-specresourcesclaimswithname)
      * [`fn withRequest(request)`](#fn-specresourcesclaimswithrequest)

## Fields

### fn new

```ts
new(name)
```

new returns an instance of KeycloakRealmImport

## obj metadata

"ObjectMeta is metadata that all persisted resources must have, which includes all objects users must create."

### fn metadata.withAnnotations

```ts
withAnnotations(annotations)
```

"Annotations is an unstructured key value map stored with a resource that may be set by external tools to store and retrieve arbitrary metadata. They are not queryable and should be preserved when modifying objects. More info: http://kubernetes.io/docs/user-guide/annotations"

### fn metadata.withAnnotationsMixin

```ts
withAnnotationsMixin(annotations)
```

"Annotations is an unstructured key value map stored with a resource that may be set by external tools to store and retrieve arbitrary metadata. They are not queryable and should be preserved when modifying objects. More info: http://kubernetes.io/docs/user-guide/annotations"

**Note:** This function appends passed data to existing values

### fn metadata.withClusterName

```ts
withClusterName(clusterName)
```

"The name of the cluster which the object belongs to. This is used to distinguish resources with same name and namespace in different clusters. This field is not set anywhere right now and apiserver is going to ignore it if set in create or update request."

### fn metadata.withCreationTimestamp

```ts
withCreationTimestamp(creationTimestamp)
```

"Time is a wrapper around time.Time which supports correct marshaling to YAML and JSON.  Wrappers are provided for many of the factory methods that the time package offers."

### fn metadata.withDeletionGracePeriodSeconds

```ts
withDeletionGracePeriodSeconds(deletionGracePeriodSeconds)
```

"Number of seconds allowed for this object to gracefully terminate before it will be removed from the system. Only set when deletionTimestamp is also set. May only be shortened. Read-only."

### fn metadata.withDeletionTimestamp

```ts
withDeletionTimestamp(deletionTimestamp)
```

"Time is a wrapper around time.Time which supports correct marshaling to YAML and JSON.  Wrappers are provided for many of the factory methods that the time package offers."

### fn metadata.withFinalizers

```ts
withFinalizers(finalizers)
```

"Must be empty before the object is deleted from the registry. Each entry is an identifier for the responsible component that will remove the entry from the list. If the deletionTimestamp of the object is non-nil, entries in this list can only be removed. Finalizers may be processed and removed in any order.  Order is NOT enforced because it introduces significant risk of stuck finalizers. finalizers is a shared field, any actor with permission can reorder it. If the finalizer list is processed in order, then this can lead to a situation in which the component responsible for the first finalizer in the list is waiting for a signal (field value, external system, or other) produced by a component responsible for a finalizer later in the list, resulting in a deadlock. Without enforced ordering finalizers are free to order amongst themselves and are not vulnerable to ordering changes in the list."

### fn metadata.withFinalizersMixin

```ts
withFinalizersMixin(finalizers)
```

"Must be empty before the object is deleted from the registry. Each entry is an identifier for the responsible component that will remove the entry from the list. If the deletionTimestamp of the object is non-nil, entries in this list can only be removed. Finalizers may be processed and removed in any order.  Order is NOT enforced because it introduces significant risk of stuck finalizers. finalizers is a shared field, any actor with permission can reorder it. If the finalizer list is processed in order, then this can lead to a situation in which the component responsible for the first finalizer in the list is waiting for a signal (field value, external system, or other) produced by a component responsible for a finalizer later in the list, resulting in a deadlock. Without enforced ordering finalizers are free to order amongst themselves and are not vulnerable to ordering changes in the list."

**Note:** This function appends passed data to existing values

### fn metadata.withGenerateName

```ts
withGenerateName(generateName)
```

"GenerateName is an optional prefix, used by the server, to generate a unique name ONLY IF the Name field has not been provided. If this field is used, the name returned to the client will be different than the name passed. This value will also be combined with a unique suffix. The provided value has the same validation rules as the Name field, and may be truncated by the length of the suffix required to make the value unique on the server.\n\nIf this field is specified and the generated name exists, the server will NOT return a 409 - instead, it will either return 201 Created or 500 with Reason ServerTimeout indicating a unique name could not be found in the time allotted, and the client should retry (optionally after the time indicated in the Retry-After header).\n\nApplied only if Name is not specified. More info: https://git.k8s.io/community/contributors/devel/sig-architecture/api-conventions.md#idempotency"

### fn metadata.withGeneration

```ts
withGeneration(generation)
```

"A sequence number representing a specific generation of the desired state. Populated by the system. Read-only."

### fn metadata.withLabels

```ts
withLabels(labels)
```

"Map of string keys and values that can be used to organize and categorize (scope and select) objects. May match selectors of replication controllers and services. More info: http://kubernetes.io/docs/user-guide/labels"

### fn metadata.withLabelsMixin

```ts
withLabelsMixin(labels)
```

"Map of string keys and values that can be used to organize and categorize (scope and select) objects. May match selectors of replication controllers and services. More info: http://kubernetes.io/docs/user-guide/labels"

**Note:** This function appends passed data to existing values

### fn metadata.withName

```ts
withName(name)
```

"Name must be unique within a namespace. Is required when creating resources, although some resources may allow a client to request the generation of an appropriate name automatically. Name is primarily intended for creation idempotence and configuration definition. Cannot be updated. More info: http://kubernetes.io/docs/user-guide/identifiers#names"

### fn metadata.withNamespace

```ts
withNamespace(namespace)
```

"Namespace defines the space within which each name must be unique. An empty namespace is equivalent to the \"default\" namespace, but \"default\" is the canonical representation. Not all objects are required to be scoped to a namespace - the value of this field for those objects will be empty.\n\nMust be a DNS_LABEL. Cannot be updated. More info: http://kubernetes.io/docs/user-guide/namespaces"

### fn metadata.withOwnerReferences

```ts
withOwnerReferences(ownerReferences)
```

"List of objects depended by this object. If ALL objects in the list have been deleted, this object will be garbage collected. If this object is managed by a controller, then an entry in this list will point to this controller, with the controller field set to true. There cannot be more than one managing controller."

### fn metadata.withOwnerReferencesMixin

```ts
withOwnerReferencesMixin(ownerReferences)
```

"List of objects depended by this object. If ALL objects in the list have been deleted, this object will be garbage collected. If this object is managed by a controller, then an entry in this list will point to this controller, with the controller field set to true. There cannot be more than one managing controller."

**Note:** This function appends passed data to existing values

### fn metadata.withResourceVersion

```ts
withResourceVersion(resourceVersion)
```

"An opaque value that represents the internal version of this object that can be used by clients to determine when objects have changed. May be used for optimistic concurrency, change detection, and the watch operation on a resource or set of resources. Clients must treat these values as opaque and passed unmodified back to the server. They may only be valid for a particular resource or set of resources.\n\nPopulated by the system. Read-only. Value must be treated as opaque by clients and . More info: https://git.k8s.io/community/contributors/devel/sig-architecture/api-conventions.md#concurrency-control-and-consistency"

### fn metadata.withSelfLink

```ts
withSelfLink(selfLink)
```

"SelfLink is a URL representing this object. Populated by the system. Read-only.\n\nDEPRECATED Kubernetes will stop propagating this field in 1.20 release and the field is planned to be removed in 1.21 release."

### fn metadata.withUid

```ts
withUid(uid)
```

"UID is the unique in time and space value for this object. It is typically generated by the server on successful creation of a resource and is not allowed to change on PUT operations.\n\nPopulated by the system. Read-only. More info: http://kubernetes.io/docs/user-guide/identifiers#uids"

## obj spec



### fn spec.withKeycloakCRName

```ts
withKeycloakCRName(keycloakCRName)
```

"The name of the Keycloak CR to reference, in the same namespace."

### fn spec.withPlaceholders

```ts
withPlaceholders(placeholders)
```

"Optionally set to replace ENV variable placeholders in the realm import."

### fn spec.withPlaceholdersMixin

```ts
withPlaceholdersMixin(placeholders)
```

"Optionally set to replace ENV variable placeholders in the realm import."

**Note:** This function appends passed data to existing values

## obj spec.realm

"The RealmRepresentation to import into Keycloak."

### fn spec.realm.withAccessCodeLifespan

```ts
withAccessCodeLifespan(accessCodeLifespan)
```



### fn spec.realm.withAccessCodeLifespanLogin

```ts
withAccessCodeLifespanLogin(accessCodeLifespanLogin)
```



### fn spec.realm.withAccessCodeLifespanUserAction

```ts
withAccessCodeLifespanUserAction(accessCodeLifespanUserAction)
```



### fn spec.realm.withAccessTokenLifespan

```ts
withAccessTokenLifespan(accessTokenLifespan)
```



### fn spec.realm.withAccessTokenLifespanForImplicitFlow

```ts
withAccessTokenLifespanForImplicitFlow(accessTokenLifespanForImplicitFlow)
```



### fn spec.realm.withAccountTheme

```ts
withAccountTheme(accountTheme)
```



### fn spec.realm.withActionTokenGeneratedByAdminLifespan

```ts
withActionTokenGeneratedByAdminLifespan(actionTokenGeneratedByAdminLifespan)
```



### fn spec.realm.withActionTokenGeneratedByUserLifespan

```ts
withActionTokenGeneratedByUserLifespan(actionTokenGeneratedByUserLifespan)
```



### fn spec.realm.withAdminEventsDetailsEnabled

```ts
withAdminEventsDetailsEnabled(adminEventsDetailsEnabled)
```



### fn spec.realm.withAdminEventsEnabled

```ts
withAdminEventsEnabled(adminEventsEnabled)
```



### fn spec.realm.withAdminPermissionsEnabled

```ts
withAdminPermissionsEnabled(adminPermissionsEnabled)
```



### fn spec.realm.withAdminTheme

```ts
withAdminTheme(adminTheme)
```



### fn spec.realm.withApplicationScopeMappings

```ts
withApplicationScopeMappings(applicationScopeMappings)
```



### fn spec.realm.withApplicationScopeMappingsMixin

```ts
withApplicationScopeMappingsMixin(applicationScopeMappings)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.withApplications

```ts
withApplications(applications)
```



### fn spec.realm.withApplicationsMixin

```ts
withApplicationsMixin(applications)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.withAttributes

```ts
withAttributes(attributes)
```



### fn spec.realm.withAttributesMixin

```ts
withAttributesMixin(attributes)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.withAuthenticationFlows

```ts
withAuthenticationFlows(authenticationFlows)
```



### fn spec.realm.withAuthenticationFlowsMixin

```ts
withAuthenticationFlowsMixin(authenticationFlows)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.withAuthenticatorConfig

```ts
withAuthenticatorConfig(authenticatorConfig)
```



### fn spec.realm.withAuthenticatorConfigMixin

```ts
withAuthenticatorConfigMixin(authenticatorConfig)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.withBrowserFlow

```ts
withBrowserFlow(browserFlow)
```



### fn spec.realm.withBrowserSecurityHeaders

```ts
withBrowserSecurityHeaders(browserSecurityHeaders)
```



### fn spec.realm.withBrowserSecurityHeadersMixin

```ts
withBrowserSecurityHeadersMixin(browserSecurityHeaders)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.withBruteForceProtected

```ts
withBruteForceProtected(bruteForceProtected)
```



### fn spec.realm.withBruteForceStrategy

```ts
withBruteForceStrategy(bruteForceStrategy)
```



### fn spec.realm.withCertificate

```ts
withCertificate(certificate)
```



### fn spec.realm.withClientAuthenticationFlow

```ts
withClientAuthenticationFlow(clientAuthenticationFlow)
```



### fn spec.realm.withClientOfflineSessionIdleTimeout

```ts
withClientOfflineSessionIdleTimeout(clientOfflineSessionIdleTimeout)
```



### fn spec.realm.withClientOfflineSessionMaxLifespan

```ts
withClientOfflineSessionMaxLifespan(clientOfflineSessionMaxLifespan)
```



### fn spec.realm.withClientPolicies

```ts
withClientPolicies(clientPolicies)
```



### fn spec.realm.withClientProfiles

```ts
withClientProfiles(clientProfiles)
```



### fn spec.realm.withClientScopeMappings

```ts
withClientScopeMappings(clientScopeMappings)
```



### fn spec.realm.withClientScopeMappingsMixin

```ts
withClientScopeMappingsMixin(clientScopeMappings)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.withClientScopes

```ts
withClientScopes(clientScopes)
```



### fn spec.realm.withClientScopesMixin

```ts
withClientScopesMixin(clientScopes)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.withClientSessionIdleTimeout

```ts
withClientSessionIdleTimeout(clientSessionIdleTimeout)
```



### fn spec.realm.withClientSessionMaxLifespan

```ts
withClientSessionMaxLifespan(clientSessionMaxLifespan)
```



### fn spec.realm.withClientTemplates

```ts
withClientTemplates(clientTemplates)
```



### fn spec.realm.withClientTemplatesMixin

```ts
withClientTemplatesMixin(clientTemplates)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.withClients

```ts
withClients(clients)
```



### fn spec.realm.withClientsMixin

```ts
withClientsMixin(clients)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.withCodeSecret

```ts
withCodeSecret(codeSecret)
```



### fn spec.realm.withComponents

```ts
withComponents(components)
```



### fn spec.realm.withComponentsMixin

```ts
withComponentsMixin(components)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.withDefaultDefaultClientScopes

```ts
withDefaultDefaultClientScopes(defaultDefaultClientScopes)
```



### fn spec.realm.withDefaultDefaultClientScopesMixin

```ts
withDefaultDefaultClientScopesMixin(defaultDefaultClientScopes)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.withDefaultGroups

```ts
withDefaultGroups(defaultGroups)
```



### fn spec.realm.withDefaultGroupsMixin

```ts
withDefaultGroupsMixin(defaultGroups)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.withDefaultLocale

```ts
withDefaultLocale(defaultLocale)
```



### fn spec.realm.withDefaultOptionalClientScopes

```ts
withDefaultOptionalClientScopes(defaultOptionalClientScopes)
```



### fn spec.realm.withDefaultOptionalClientScopesMixin

```ts
withDefaultOptionalClientScopesMixin(defaultOptionalClientScopes)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.withDefaultRoles

```ts
withDefaultRoles(defaultRoles)
```



### fn spec.realm.withDefaultRolesMixin

```ts
withDefaultRolesMixin(defaultRoles)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.withDefaultSignatureAlgorithm

```ts
withDefaultSignatureAlgorithm(defaultSignatureAlgorithm)
```



### fn spec.realm.withDirectGrantFlow

```ts
withDirectGrantFlow(directGrantFlow)
```



### fn spec.realm.withDisplayName

```ts
withDisplayName(displayName)
```



### fn spec.realm.withDisplayNameHtml

```ts
withDisplayNameHtml(displayNameHtml)
```



### fn spec.realm.withDockerAuthenticationFlow

```ts
withDockerAuthenticationFlow(dockerAuthenticationFlow)
```



### fn spec.realm.withDuplicateEmailsAllowed

```ts
withDuplicateEmailsAllowed(duplicateEmailsAllowed)
```



### fn spec.realm.withEditUsernameAllowed

```ts
withEditUsernameAllowed(editUsernameAllowed)
```



### fn spec.realm.withEmailTheme

```ts
withEmailTheme(emailTheme)
```



### fn spec.realm.withEnabled

```ts
withEnabled(enabled)
```



### fn spec.realm.withEnabledEventTypes

```ts
withEnabledEventTypes(enabledEventTypes)
```



### fn spec.realm.withEnabledEventTypesMixin

```ts
withEnabledEventTypesMixin(enabledEventTypes)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.withEventsEnabled

```ts
withEventsEnabled(eventsEnabled)
```



### fn spec.realm.withEventsExpiration

```ts
withEventsExpiration(eventsExpiration)
```



### fn spec.realm.withEventsListeners

```ts
withEventsListeners(eventsListeners)
```



### fn spec.realm.withEventsListenersMixin

```ts
withEventsListenersMixin(eventsListeners)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.withFailureFactor

```ts
withFailureFactor(failureFactor)
```



### fn spec.realm.withFederatedUsers

```ts
withFederatedUsers(federatedUsers)
```



### fn spec.realm.withFederatedUsersMixin

```ts
withFederatedUsersMixin(federatedUsers)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.withFirstBrokerLoginFlow

```ts
withFirstBrokerLoginFlow(firstBrokerLoginFlow)
```



### fn spec.realm.withGroups

```ts
withGroups(groups)
```



### fn spec.realm.withGroupsMixin

```ts
withGroupsMixin(groups)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.withId

```ts
withId(id)
```



### fn spec.realm.withIdentityProviderMappers

```ts
withIdentityProviderMappers(identityProviderMappers)
```



### fn spec.realm.withIdentityProviderMappersMixin

```ts
withIdentityProviderMappersMixin(identityProviderMappers)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.withIdentityProviders

```ts
withIdentityProviders(identityProviders)
```



### fn spec.realm.withIdentityProvidersMixin

```ts
withIdentityProvidersMixin(identityProviders)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.withInternationalizationEnabled

```ts
withInternationalizationEnabled(internationalizationEnabled)
```



### fn spec.realm.withKeycloakVersion

```ts
withKeycloakVersion(keycloakVersion)
```



### fn spec.realm.withLocalizationTexts

```ts
withLocalizationTexts(localizationTexts)
```



### fn spec.realm.withLocalizationTextsMixin

```ts
withLocalizationTextsMixin(localizationTexts)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.withLoginTheme

```ts
withLoginTheme(loginTheme)
```



### fn spec.realm.withLoginWithEmailAllowed

```ts
withLoginWithEmailAllowed(loginWithEmailAllowed)
```



### fn spec.realm.withMaxDeltaTimeSeconds

```ts
withMaxDeltaTimeSeconds(maxDeltaTimeSeconds)
```



### fn spec.realm.withMaxFailureWaitSeconds

```ts
withMaxFailureWaitSeconds(maxFailureWaitSeconds)
```



### fn spec.realm.withMaxTemporaryLockouts

```ts
withMaxTemporaryLockouts(maxTemporaryLockouts)
```



### fn spec.realm.withMinimumQuickLoginWaitSeconds

```ts
withMinimumQuickLoginWaitSeconds(minimumQuickLoginWaitSeconds)
```



### fn spec.realm.withNotBefore

```ts
withNotBefore(notBefore)
```



### fn spec.realm.withOauth2DeviceCodeLifespan

```ts
withOauth2DeviceCodeLifespan(oauth2DeviceCodeLifespan)
```



### fn spec.realm.withOauth2DevicePollingInterval

```ts
withOauth2DevicePollingInterval(oauth2DevicePollingInterval)
```



### fn spec.realm.withOauthClients

```ts
withOauthClients(oauthClients)
```



### fn spec.realm.withOauthClientsMixin

```ts
withOauthClientsMixin(oauthClients)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.withOfflineSessionIdleTimeout

```ts
withOfflineSessionIdleTimeout(offlineSessionIdleTimeout)
```



### fn spec.realm.withOfflineSessionMaxLifespan

```ts
withOfflineSessionMaxLifespan(offlineSessionMaxLifespan)
```



### fn spec.realm.withOfflineSessionMaxLifespanEnabled

```ts
withOfflineSessionMaxLifespanEnabled(offlineSessionMaxLifespanEnabled)
```



### fn spec.realm.withOrganizations

```ts
withOrganizations(organizations)
```



### fn spec.realm.withOrganizationsEnabled

```ts
withOrganizationsEnabled(organizationsEnabled)
```



### fn spec.realm.withOrganizationsMixin

```ts
withOrganizationsMixin(organizations)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.withOtpPolicyAlgorithm

```ts
withOtpPolicyAlgorithm(otpPolicyAlgorithm)
```



### fn spec.realm.withOtpPolicyCodeReusable

```ts
withOtpPolicyCodeReusable(otpPolicyCodeReusable)
```



### fn spec.realm.withOtpPolicyDigits

```ts
withOtpPolicyDigits(otpPolicyDigits)
```



### fn spec.realm.withOtpPolicyInitialCounter

```ts
withOtpPolicyInitialCounter(otpPolicyInitialCounter)
```



### fn spec.realm.withOtpPolicyLookAheadWindow

```ts
withOtpPolicyLookAheadWindow(otpPolicyLookAheadWindow)
```



### fn spec.realm.withOtpPolicyPeriod

```ts
withOtpPolicyPeriod(otpPolicyPeriod)
```



### fn spec.realm.withOtpPolicyType

```ts
withOtpPolicyType(otpPolicyType)
```



### fn spec.realm.withOtpSupportedApplications

```ts
withOtpSupportedApplications(otpSupportedApplications)
```



### fn spec.realm.withOtpSupportedApplicationsMixin

```ts
withOtpSupportedApplicationsMixin(otpSupportedApplications)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.withPasswordCredentialGrantAllowed

```ts
withPasswordCredentialGrantAllowed(passwordCredentialGrantAllowed)
```



### fn spec.realm.withPasswordPolicy

```ts
withPasswordPolicy(passwordPolicy)
```



### fn spec.realm.withPermanentLockout

```ts
withPermanentLockout(permanentLockout)
```



### fn spec.realm.withPrivateKey

```ts
withPrivateKey(privateKey)
```



### fn spec.realm.withProtocolMappers

```ts
withProtocolMappers(protocolMappers)
```



### fn spec.realm.withProtocolMappersMixin

```ts
withProtocolMappersMixin(protocolMappers)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.withPublicKey

```ts
withPublicKey(publicKey)
```



### fn spec.realm.withQuickLoginCheckMilliSeconds

```ts
withQuickLoginCheckMilliSeconds(quickLoginCheckMilliSeconds)
```



### fn spec.realm.withRealm

```ts
withRealm(realm)
```



### fn spec.realm.withRefreshTokenMaxReuse

```ts
withRefreshTokenMaxReuse(refreshTokenMaxReuse)
```



### fn spec.realm.withRegistrationAllowed

```ts
withRegistrationAllowed(registrationAllowed)
```



### fn spec.realm.withRegistrationEmailAsUsername

```ts
withRegistrationEmailAsUsername(registrationEmailAsUsername)
```



### fn spec.realm.withRegistrationFlow

```ts
withRegistrationFlow(registrationFlow)
```



### fn spec.realm.withRememberMe

```ts
withRememberMe(rememberMe)
```



### fn spec.realm.withRequiredActions

```ts
withRequiredActions(requiredActions)
```



### fn spec.realm.withRequiredActionsMixin

```ts
withRequiredActionsMixin(requiredActions)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.withRequiredCredentials

```ts
withRequiredCredentials(requiredCredentials)
```



### fn spec.realm.withRequiredCredentialsMixin

```ts
withRequiredCredentialsMixin(requiredCredentials)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.withResetCredentialsFlow

```ts
withResetCredentialsFlow(resetCredentialsFlow)
```



### fn spec.realm.withResetPasswordAllowed

```ts
withResetPasswordAllowed(resetPasswordAllowed)
```



### fn spec.realm.withRevokeRefreshToken

```ts
withRevokeRefreshToken(revokeRefreshToken)
```



### fn spec.realm.withScopeMappings

```ts
withScopeMappings(scopeMappings)
```



### fn spec.realm.withScopeMappingsMixin

```ts
withScopeMappingsMixin(scopeMappings)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.withSmtpServer

```ts
withSmtpServer(smtpServer)
```



### fn spec.realm.withSmtpServerMixin

```ts
withSmtpServerMixin(smtpServer)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.withSocial

```ts
withSocial(social)
```



### fn spec.realm.withSocialProviders

```ts
withSocialProviders(socialProviders)
```



### fn spec.realm.withSocialProvidersMixin

```ts
withSocialProvidersMixin(socialProviders)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.withSslRequired

```ts
withSslRequired(sslRequired)
```



### fn spec.realm.withSsoSessionIdleTimeout

```ts
withSsoSessionIdleTimeout(ssoSessionIdleTimeout)
```



### fn spec.realm.withSsoSessionIdleTimeoutRememberMe

```ts
withSsoSessionIdleTimeoutRememberMe(ssoSessionIdleTimeoutRememberMe)
```



### fn spec.realm.withSsoSessionMaxLifespan

```ts
withSsoSessionMaxLifespan(ssoSessionMaxLifespan)
```



### fn spec.realm.withSsoSessionMaxLifespanRememberMe

```ts
withSsoSessionMaxLifespanRememberMe(ssoSessionMaxLifespanRememberMe)
```



### fn spec.realm.withSupportedLocales

```ts
withSupportedLocales(supportedLocales)
```



### fn spec.realm.withSupportedLocalesMixin

```ts
withSupportedLocalesMixin(supportedLocales)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.withUpdateProfileOnInitialSocialLogin

```ts
withUpdateProfileOnInitialSocialLogin(updateProfileOnInitialSocialLogin)
```



### fn spec.realm.withUserFederationMappers

```ts
withUserFederationMappers(userFederationMappers)
```



### fn spec.realm.withUserFederationMappersMixin

```ts
withUserFederationMappersMixin(userFederationMappers)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.withUserFederationProviders

```ts
withUserFederationProviders(userFederationProviders)
```



### fn spec.realm.withUserFederationProvidersMixin

```ts
withUserFederationProvidersMixin(userFederationProviders)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.withUserManagedAccessAllowed

```ts
withUserManagedAccessAllowed(userManagedAccessAllowed)
```



### fn spec.realm.withUsers

```ts
withUsers(users)
```



### fn spec.realm.withUsersMixin

```ts
withUsersMixin(users)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.withVerifiableCredentialsEnabled

```ts
withVerifiableCredentialsEnabled(verifiableCredentialsEnabled)
```



### fn spec.realm.withVerifyEmail

```ts
withVerifyEmail(verifyEmail)
```



### fn spec.realm.withWaitIncrementSeconds

```ts
withWaitIncrementSeconds(waitIncrementSeconds)
```



### fn spec.realm.withWebAuthnPolicyAcceptableAaguids

```ts
withWebAuthnPolicyAcceptableAaguids(webAuthnPolicyAcceptableAaguids)
```



### fn spec.realm.withWebAuthnPolicyAcceptableAaguidsMixin

```ts
withWebAuthnPolicyAcceptableAaguidsMixin(webAuthnPolicyAcceptableAaguids)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.withWebAuthnPolicyAttestationConveyancePreference

```ts
withWebAuthnPolicyAttestationConveyancePreference(webAuthnPolicyAttestationConveyancePreference)
```



### fn spec.realm.withWebAuthnPolicyAuthenticatorAttachment

```ts
withWebAuthnPolicyAuthenticatorAttachment(webAuthnPolicyAuthenticatorAttachment)
```



### fn spec.realm.withWebAuthnPolicyAvoidSameAuthenticatorRegister

```ts
withWebAuthnPolicyAvoidSameAuthenticatorRegister(webAuthnPolicyAvoidSameAuthenticatorRegister)
```



### fn spec.realm.withWebAuthnPolicyCreateTimeout

```ts
withWebAuthnPolicyCreateTimeout(webAuthnPolicyCreateTimeout)
```



### fn spec.realm.withWebAuthnPolicyExtraOrigins

```ts
withWebAuthnPolicyExtraOrigins(webAuthnPolicyExtraOrigins)
```



### fn spec.realm.withWebAuthnPolicyExtraOriginsMixin

```ts
withWebAuthnPolicyExtraOriginsMixin(webAuthnPolicyExtraOrigins)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.withWebAuthnPolicyPasswordlessAcceptableAaguids

```ts
withWebAuthnPolicyPasswordlessAcceptableAaguids(webAuthnPolicyPasswordlessAcceptableAaguids)
```



### fn spec.realm.withWebAuthnPolicyPasswordlessAcceptableAaguidsMixin

```ts
withWebAuthnPolicyPasswordlessAcceptableAaguidsMixin(webAuthnPolicyPasswordlessAcceptableAaguids)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.withWebAuthnPolicyPasswordlessAttestationConveyancePreference

```ts
withWebAuthnPolicyPasswordlessAttestationConveyancePreference(webAuthnPolicyPasswordlessAttestationConveyancePreference)
```



### fn spec.realm.withWebAuthnPolicyPasswordlessAuthenticatorAttachment

```ts
withWebAuthnPolicyPasswordlessAuthenticatorAttachment(webAuthnPolicyPasswordlessAuthenticatorAttachment)
```



### fn spec.realm.withWebAuthnPolicyPasswordlessAvoidSameAuthenticatorRegister

```ts
withWebAuthnPolicyPasswordlessAvoidSameAuthenticatorRegister(webAuthnPolicyPasswordlessAvoidSameAuthenticatorRegister)
```



### fn spec.realm.withWebAuthnPolicyPasswordlessCreateTimeout

```ts
withWebAuthnPolicyPasswordlessCreateTimeout(webAuthnPolicyPasswordlessCreateTimeout)
```



### fn spec.realm.withWebAuthnPolicyPasswordlessExtraOrigins

```ts
withWebAuthnPolicyPasswordlessExtraOrigins(webAuthnPolicyPasswordlessExtraOrigins)
```



### fn spec.realm.withWebAuthnPolicyPasswordlessExtraOriginsMixin

```ts
withWebAuthnPolicyPasswordlessExtraOriginsMixin(webAuthnPolicyPasswordlessExtraOrigins)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.withWebAuthnPolicyPasswordlessPasskeysEnabled

```ts
withWebAuthnPolicyPasswordlessPasskeysEnabled(webAuthnPolicyPasswordlessPasskeysEnabled)
```



### fn spec.realm.withWebAuthnPolicyPasswordlessRequireResidentKey

```ts
withWebAuthnPolicyPasswordlessRequireResidentKey(webAuthnPolicyPasswordlessRequireResidentKey)
```



### fn spec.realm.withWebAuthnPolicyPasswordlessRpEntityName

```ts
withWebAuthnPolicyPasswordlessRpEntityName(webAuthnPolicyPasswordlessRpEntityName)
```



### fn spec.realm.withWebAuthnPolicyPasswordlessRpId

```ts
withWebAuthnPolicyPasswordlessRpId(webAuthnPolicyPasswordlessRpId)
```



### fn spec.realm.withWebAuthnPolicyPasswordlessSignatureAlgorithms

```ts
withWebAuthnPolicyPasswordlessSignatureAlgorithms(webAuthnPolicyPasswordlessSignatureAlgorithms)
```



### fn spec.realm.withWebAuthnPolicyPasswordlessSignatureAlgorithmsMixin

```ts
withWebAuthnPolicyPasswordlessSignatureAlgorithmsMixin(webAuthnPolicyPasswordlessSignatureAlgorithms)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.withWebAuthnPolicyPasswordlessUserVerificationRequirement

```ts
withWebAuthnPolicyPasswordlessUserVerificationRequirement(webAuthnPolicyPasswordlessUserVerificationRequirement)
```



### fn spec.realm.withWebAuthnPolicyRequireResidentKey

```ts
withWebAuthnPolicyRequireResidentKey(webAuthnPolicyRequireResidentKey)
```



### fn spec.realm.withWebAuthnPolicyRpEntityName

```ts
withWebAuthnPolicyRpEntityName(webAuthnPolicyRpEntityName)
```



### fn spec.realm.withWebAuthnPolicyRpId

```ts
withWebAuthnPolicyRpId(webAuthnPolicyRpId)
```



### fn spec.realm.withWebAuthnPolicySignatureAlgorithms

```ts
withWebAuthnPolicySignatureAlgorithms(webAuthnPolicySignatureAlgorithms)
```



### fn spec.realm.withWebAuthnPolicySignatureAlgorithmsMixin

```ts
withWebAuthnPolicySignatureAlgorithmsMixin(webAuthnPolicySignatureAlgorithms)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.withWebAuthnPolicyUserVerificationRequirement

```ts
withWebAuthnPolicyUserVerificationRequirement(webAuthnPolicyUserVerificationRequirement)
```



## obj spec.realm.adminPermissionsClient



### fn spec.realm.adminPermissionsClient.withAccess

```ts
withAccess(access)
```



### fn spec.realm.adminPermissionsClient.withAccessMixin

```ts
withAccessMixin(access)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.adminPermissionsClient.withAdminUrl

```ts
withAdminUrl(adminUrl)
```



### fn spec.realm.adminPermissionsClient.withAlwaysDisplayInConsole

```ts
withAlwaysDisplayInConsole(alwaysDisplayInConsole)
```



### fn spec.realm.adminPermissionsClient.withAttributes

```ts
withAttributes(attributes)
```



### fn spec.realm.adminPermissionsClient.withAttributesMixin

```ts
withAttributesMixin(attributes)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.adminPermissionsClient.withAuthenticationFlowBindingOverrides

```ts
withAuthenticationFlowBindingOverrides(authenticationFlowBindingOverrides)
```



### fn spec.realm.adminPermissionsClient.withAuthenticationFlowBindingOverridesMixin

```ts
withAuthenticationFlowBindingOverridesMixin(authenticationFlowBindingOverrides)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.adminPermissionsClient.withAuthorizationServicesEnabled

```ts
withAuthorizationServicesEnabled(authorizationServicesEnabled)
```



### fn spec.realm.adminPermissionsClient.withBaseUrl

```ts
withBaseUrl(baseUrl)
```



### fn spec.realm.adminPermissionsClient.withBearerOnly

```ts
withBearerOnly(bearerOnly)
```



### fn spec.realm.adminPermissionsClient.withClientAuthenticatorType

```ts
withClientAuthenticatorType(clientAuthenticatorType)
```



### fn spec.realm.adminPermissionsClient.withClientId

```ts
withClientId(clientId)
```



### fn spec.realm.adminPermissionsClient.withClientTemplate

```ts
withClientTemplate(clientTemplate)
```



### fn spec.realm.adminPermissionsClient.withConsentRequired

```ts
withConsentRequired(consentRequired)
```



### fn spec.realm.adminPermissionsClient.withDefaultClientScopes

```ts
withDefaultClientScopes(defaultClientScopes)
```



### fn spec.realm.adminPermissionsClient.withDefaultClientScopesMixin

```ts
withDefaultClientScopesMixin(defaultClientScopes)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.adminPermissionsClient.withDefaultRoles

```ts
withDefaultRoles(defaultRoles)
```



### fn spec.realm.adminPermissionsClient.withDefaultRolesMixin

```ts
withDefaultRolesMixin(defaultRoles)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.adminPermissionsClient.withDescription

```ts
withDescription(description)
```



### fn spec.realm.adminPermissionsClient.withDirectAccessGrantsEnabled

```ts
withDirectAccessGrantsEnabled(directAccessGrantsEnabled)
```



### fn spec.realm.adminPermissionsClient.withDirectGrantsOnly

```ts
withDirectGrantsOnly(directGrantsOnly)
```



### fn spec.realm.adminPermissionsClient.withEnabled

```ts
withEnabled(enabled)
```



### fn spec.realm.adminPermissionsClient.withFrontchannelLogout

```ts
withFrontchannelLogout(frontchannelLogout)
```



### fn spec.realm.adminPermissionsClient.withFullScopeAllowed

```ts
withFullScopeAllowed(fullScopeAllowed)
```



### fn spec.realm.adminPermissionsClient.withId

```ts
withId(id)
```



### fn spec.realm.adminPermissionsClient.withImplicitFlowEnabled

```ts
withImplicitFlowEnabled(implicitFlowEnabled)
```



### fn spec.realm.adminPermissionsClient.withName

```ts
withName(name)
```



### fn spec.realm.adminPermissionsClient.withNodeReRegistrationTimeout

```ts
withNodeReRegistrationTimeout(nodeReRegistrationTimeout)
```



### fn spec.realm.adminPermissionsClient.withNotBefore

```ts
withNotBefore(notBefore)
```



### fn spec.realm.adminPermissionsClient.withOptionalClientScopes

```ts
withOptionalClientScopes(optionalClientScopes)
```



### fn spec.realm.adminPermissionsClient.withOptionalClientScopesMixin

```ts
withOptionalClientScopesMixin(optionalClientScopes)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.adminPermissionsClient.withOrigin

```ts
withOrigin(origin)
```



### fn spec.realm.adminPermissionsClient.withProtocol

```ts
withProtocol(protocol)
```



### fn spec.realm.adminPermissionsClient.withProtocolMappers

```ts
withProtocolMappers(protocolMappers)
```



### fn spec.realm.adminPermissionsClient.withProtocolMappersMixin

```ts
withProtocolMappersMixin(protocolMappers)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.adminPermissionsClient.withPublicClient

```ts
withPublicClient(publicClient)
```



### fn spec.realm.adminPermissionsClient.withRedirectUris

```ts
withRedirectUris(redirectUris)
```



### fn spec.realm.adminPermissionsClient.withRedirectUrisMixin

```ts
withRedirectUrisMixin(redirectUris)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.adminPermissionsClient.withRegisteredNodes

```ts
withRegisteredNodes(registeredNodes)
```



### fn spec.realm.adminPermissionsClient.withRegisteredNodesMixin

```ts
withRegisteredNodesMixin(registeredNodes)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.adminPermissionsClient.withRegistrationAccessToken

```ts
withRegistrationAccessToken(registrationAccessToken)
```



### fn spec.realm.adminPermissionsClient.withRootUrl

```ts
withRootUrl(rootUrl)
```



### fn spec.realm.adminPermissionsClient.withSecret

```ts
withSecret(secret)
```



### fn spec.realm.adminPermissionsClient.withServiceAccountsEnabled

```ts
withServiceAccountsEnabled(serviceAccountsEnabled)
```



### fn spec.realm.adminPermissionsClient.withStandardFlowEnabled

```ts
withStandardFlowEnabled(standardFlowEnabled)
```



### fn spec.realm.adminPermissionsClient.withSurrogateAuthRequired

```ts
withSurrogateAuthRequired(surrogateAuthRequired)
```



### fn spec.realm.adminPermissionsClient.withType

```ts
withType(type)
```



### fn spec.realm.adminPermissionsClient.withUseTemplateConfig

```ts
withUseTemplateConfig(useTemplateConfig)
```



### fn spec.realm.adminPermissionsClient.withUseTemplateMappers

```ts
withUseTemplateMappers(useTemplateMappers)
```



### fn spec.realm.adminPermissionsClient.withUseTemplateScope

```ts
withUseTemplateScope(useTemplateScope)
```



### fn spec.realm.adminPermissionsClient.withWebOrigins

```ts
withWebOrigins(webOrigins)
```



### fn spec.realm.adminPermissionsClient.withWebOriginsMixin

```ts
withWebOriginsMixin(webOrigins)
```



**Note:** This function appends passed data to existing values

## obj spec.realm.adminPermissionsClient.authorizationSettings



### fn spec.realm.adminPermissionsClient.authorizationSettings.withAllowRemoteResourceManagement

```ts
withAllowRemoteResourceManagement(allowRemoteResourceManagement)
```



### fn spec.realm.adminPermissionsClient.authorizationSettings.withClientId

```ts
withClientId(clientId)
```



### fn spec.realm.adminPermissionsClient.authorizationSettings.withDecisionStrategy

```ts
withDecisionStrategy(decisionStrategy)
```



### fn spec.realm.adminPermissionsClient.authorizationSettings.withId

```ts
withId(id)
```



### fn spec.realm.adminPermissionsClient.authorizationSettings.withName

```ts
withName(name)
```



### fn spec.realm.adminPermissionsClient.authorizationSettings.withPolicies

```ts
withPolicies(policies)
```



### fn spec.realm.adminPermissionsClient.authorizationSettings.withPoliciesMixin

```ts
withPoliciesMixin(policies)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.adminPermissionsClient.authorizationSettings.withPolicyEnforcementMode

```ts
withPolicyEnforcementMode(policyEnforcementMode)
```



### fn spec.realm.adminPermissionsClient.authorizationSettings.withResources

```ts
withResources(resources)
```



### fn spec.realm.adminPermissionsClient.authorizationSettings.withResourcesMixin

```ts
withResourcesMixin(resources)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.adminPermissionsClient.authorizationSettings.withScopes

```ts
withScopes(scopes)
```



### fn spec.realm.adminPermissionsClient.authorizationSettings.withScopesMixin

```ts
withScopesMixin(scopes)
```



**Note:** This function appends passed data to existing values

## obj spec.realm.adminPermissionsClient.authorizationSettings.authorizationSchema



### fn spec.realm.adminPermissionsClient.authorizationSettings.authorizationSchema.withResourceTypes

```ts
withResourceTypes(resourceTypes)
```



### fn spec.realm.adminPermissionsClient.authorizationSettings.authorizationSchema.withResourceTypesMixin

```ts
withResourceTypesMixin(resourceTypes)
```



**Note:** This function appends passed data to existing values

## obj spec.realm.adminPermissionsClient.authorizationSettings.policies



### fn spec.realm.adminPermissionsClient.authorizationSettings.policies.withConfig

```ts
withConfig(config)
```



### fn spec.realm.adminPermissionsClient.authorizationSettings.policies.withConfigMixin

```ts
withConfigMixin(config)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.adminPermissionsClient.authorizationSettings.policies.withDecisionStrategy

```ts
withDecisionStrategy(decisionStrategy)
```



### fn spec.realm.adminPermissionsClient.authorizationSettings.policies.withDescription

```ts
withDescription(description)
```



### fn spec.realm.adminPermissionsClient.authorizationSettings.policies.withId

```ts
withId(id)
```



### fn spec.realm.adminPermissionsClient.authorizationSettings.policies.withLogic

```ts
withLogic(logic)
```



### fn spec.realm.adminPermissionsClient.authorizationSettings.policies.withName

```ts
withName(name)
```



### fn spec.realm.adminPermissionsClient.authorizationSettings.policies.withOwner

```ts
withOwner(owner)
```



### fn spec.realm.adminPermissionsClient.authorizationSettings.policies.withPolicies

```ts
withPolicies(policies)
```



### fn spec.realm.adminPermissionsClient.authorizationSettings.policies.withPoliciesMixin

```ts
withPoliciesMixin(policies)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.adminPermissionsClient.authorizationSettings.policies.withResourceType

```ts
withResourceType(resourceType)
```



### fn spec.realm.adminPermissionsClient.authorizationSettings.policies.withResources

```ts
withResources(resources)
```



### fn spec.realm.adminPermissionsClient.authorizationSettings.policies.withResourcesData

```ts
withResourcesData(resourcesData)
```



### fn spec.realm.adminPermissionsClient.authorizationSettings.policies.withResourcesDataMixin

```ts
withResourcesDataMixin(resourcesData)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.adminPermissionsClient.authorizationSettings.policies.withResourcesMixin

```ts
withResourcesMixin(resources)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.adminPermissionsClient.authorizationSettings.policies.withScopes

```ts
withScopes(scopes)
```



### fn spec.realm.adminPermissionsClient.authorizationSettings.policies.withScopesData

```ts
withScopesData(scopesData)
```



### fn spec.realm.adminPermissionsClient.authorizationSettings.policies.withScopesDataMixin

```ts
withScopesDataMixin(scopesData)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.adminPermissionsClient.authorizationSettings.policies.withScopesMixin

```ts
withScopesMixin(scopes)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.adminPermissionsClient.authorizationSettings.policies.withType

```ts
withType(type)
```



## obj spec.realm.adminPermissionsClient.authorizationSettings.policies.resourcesData



### fn spec.realm.adminPermissionsClient.authorizationSettings.policies.resourcesData.withAttributes

```ts
withAttributes(attributes)
```



### fn spec.realm.adminPermissionsClient.authorizationSettings.policies.resourcesData.withAttributesMixin

```ts
withAttributesMixin(attributes)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.adminPermissionsClient.authorizationSettings.policies.resourcesData.withDisplayName

```ts
withDisplayName(displayName)
```



### fn spec.realm.adminPermissionsClient.authorizationSettings.policies.resourcesData.withIcon_uri

```ts
withIcon_uri(icon_uri)
```



### fn spec.realm.adminPermissionsClient.authorizationSettings.policies.resourcesData.withName

```ts
withName(name)
```



### fn spec.realm.adminPermissionsClient.authorizationSettings.policies.resourcesData.withOwnerManagedAccess

```ts
withOwnerManagedAccess(ownerManagedAccess)
```



### fn spec.realm.adminPermissionsClient.authorizationSettings.policies.resourcesData.withScopes

```ts
withScopes(scopes)
```



### fn spec.realm.adminPermissionsClient.authorizationSettings.policies.resourcesData.withScopesMixin

```ts
withScopesMixin(scopes)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.adminPermissionsClient.authorizationSettings.policies.resourcesData.withType

```ts
withType(type)
```



### fn spec.realm.adminPermissionsClient.authorizationSettings.policies.resourcesData.withUris

```ts
withUris(uris)
```



### fn spec.realm.adminPermissionsClient.authorizationSettings.policies.resourcesData.withUrisMixin

```ts
withUrisMixin(uris)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.adminPermissionsClient.authorizationSettings.policies.resourcesData.with_id

```ts
with_id(_id)
```



## obj spec.realm.adminPermissionsClient.authorizationSettings.policies.resourcesData.owner



### fn spec.realm.adminPermissionsClient.authorizationSettings.policies.resourcesData.owner.withId

```ts
withId(id)
```



### fn spec.realm.adminPermissionsClient.authorizationSettings.policies.resourcesData.owner.withName

```ts
withName(name)
```



## obj spec.realm.adminPermissionsClient.authorizationSettings.policies.resourcesData.scopes



### fn spec.realm.adminPermissionsClient.authorizationSettings.policies.resourcesData.scopes.withDisplayName

```ts
withDisplayName(displayName)
```



### fn spec.realm.adminPermissionsClient.authorizationSettings.policies.resourcesData.scopes.withIconUri

```ts
withIconUri(iconUri)
```



### fn spec.realm.adminPermissionsClient.authorizationSettings.policies.resourcesData.scopes.withId

```ts
withId(id)
```



### fn spec.realm.adminPermissionsClient.authorizationSettings.policies.resourcesData.scopes.withName

```ts
withName(name)
```



## obj spec.realm.adminPermissionsClient.authorizationSettings.policies.scopesData



### fn spec.realm.adminPermissionsClient.authorizationSettings.policies.scopesData.withDisplayName

```ts
withDisplayName(displayName)
```



### fn spec.realm.adminPermissionsClient.authorizationSettings.policies.scopesData.withIconUri

```ts
withIconUri(iconUri)
```



### fn spec.realm.adminPermissionsClient.authorizationSettings.policies.scopesData.withId

```ts
withId(id)
```



### fn spec.realm.adminPermissionsClient.authorizationSettings.policies.scopesData.withName

```ts
withName(name)
```



## obj spec.realm.adminPermissionsClient.authorizationSettings.resources



### fn spec.realm.adminPermissionsClient.authorizationSettings.resources.withAttributes

```ts
withAttributes(attributes)
```



### fn spec.realm.adminPermissionsClient.authorizationSettings.resources.withAttributesMixin

```ts
withAttributesMixin(attributes)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.adminPermissionsClient.authorizationSettings.resources.withDisplayName

```ts
withDisplayName(displayName)
```



### fn spec.realm.adminPermissionsClient.authorizationSettings.resources.withIcon_uri

```ts
withIcon_uri(icon_uri)
```



### fn spec.realm.adminPermissionsClient.authorizationSettings.resources.withName

```ts
withName(name)
```



### fn spec.realm.adminPermissionsClient.authorizationSettings.resources.withOwnerManagedAccess

```ts
withOwnerManagedAccess(ownerManagedAccess)
```



### fn spec.realm.adminPermissionsClient.authorizationSettings.resources.withScopes

```ts
withScopes(scopes)
```



### fn spec.realm.adminPermissionsClient.authorizationSettings.resources.withScopesMixin

```ts
withScopesMixin(scopes)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.adminPermissionsClient.authorizationSettings.resources.withType

```ts
withType(type)
```



### fn spec.realm.adminPermissionsClient.authorizationSettings.resources.withUris

```ts
withUris(uris)
```



### fn spec.realm.adminPermissionsClient.authorizationSettings.resources.withUrisMixin

```ts
withUrisMixin(uris)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.adminPermissionsClient.authorizationSettings.resources.with_id

```ts
with_id(_id)
```



## obj spec.realm.adminPermissionsClient.authorizationSettings.resources.owner



### fn spec.realm.adminPermissionsClient.authorizationSettings.resources.owner.withId

```ts
withId(id)
```



### fn spec.realm.adminPermissionsClient.authorizationSettings.resources.owner.withName

```ts
withName(name)
```



## obj spec.realm.adminPermissionsClient.authorizationSettings.resources.scopes



### fn spec.realm.adminPermissionsClient.authorizationSettings.resources.scopes.withDisplayName

```ts
withDisplayName(displayName)
```



### fn spec.realm.adminPermissionsClient.authorizationSettings.resources.scopes.withIconUri

```ts
withIconUri(iconUri)
```



### fn spec.realm.adminPermissionsClient.authorizationSettings.resources.scopes.withId

```ts
withId(id)
```



### fn spec.realm.adminPermissionsClient.authorizationSettings.resources.scopes.withName

```ts
withName(name)
```



## obj spec.realm.adminPermissionsClient.authorizationSettings.scopes



### fn spec.realm.adminPermissionsClient.authorizationSettings.scopes.withDisplayName

```ts
withDisplayName(displayName)
```



### fn spec.realm.adminPermissionsClient.authorizationSettings.scopes.withIconUri

```ts
withIconUri(iconUri)
```



### fn spec.realm.adminPermissionsClient.authorizationSettings.scopes.withId

```ts
withId(id)
```



### fn spec.realm.adminPermissionsClient.authorizationSettings.scopes.withName

```ts
withName(name)
```



## obj spec.realm.adminPermissionsClient.protocolMappers



### fn spec.realm.adminPermissionsClient.protocolMappers.withConfig

```ts
withConfig(config)
```



### fn spec.realm.adminPermissionsClient.protocolMappers.withConfigMixin

```ts
withConfigMixin(config)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.adminPermissionsClient.protocolMappers.withConsentRequired

```ts
withConsentRequired(consentRequired)
```



### fn spec.realm.adminPermissionsClient.protocolMappers.withConsentText

```ts
withConsentText(consentText)
```



### fn spec.realm.adminPermissionsClient.protocolMappers.withId

```ts
withId(id)
```



### fn spec.realm.adminPermissionsClient.protocolMappers.withName

```ts
withName(name)
```



### fn spec.realm.adminPermissionsClient.protocolMappers.withProtocol

```ts
withProtocol(protocol)
```



### fn spec.realm.adminPermissionsClient.protocolMappers.withProtocolMapper

```ts
withProtocolMapper(protocolMapper)
```



## obj spec.realm.applications



### fn spec.realm.applications.withAccess

```ts
withAccess(access)
```



### fn spec.realm.applications.withAccessMixin

```ts
withAccessMixin(access)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.applications.withAdminUrl

```ts
withAdminUrl(adminUrl)
```



### fn spec.realm.applications.withAlwaysDisplayInConsole

```ts
withAlwaysDisplayInConsole(alwaysDisplayInConsole)
```



### fn spec.realm.applications.withAttributes

```ts
withAttributes(attributes)
```



### fn spec.realm.applications.withAttributesMixin

```ts
withAttributesMixin(attributes)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.applications.withAuthenticationFlowBindingOverrides

```ts
withAuthenticationFlowBindingOverrides(authenticationFlowBindingOverrides)
```



### fn spec.realm.applications.withAuthenticationFlowBindingOverridesMixin

```ts
withAuthenticationFlowBindingOverridesMixin(authenticationFlowBindingOverrides)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.applications.withAuthorizationServicesEnabled

```ts
withAuthorizationServicesEnabled(authorizationServicesEnabled)
```



### fn spec.realm.applications.withBaseUrl

```ts
withBaseUrl(baseUrl)
```



### fn spec.realm.applications.withBearerOnly

```ts
withBearerOnly(bearerOnly)
```



### fn spec.realm.applications.withClientAuthenticatorType

```ts
withClientAuthenticatorType(clientAuthenticatorType)
```



### fn spec.realm.applications.withClientId

```ts
withClientId(clientId)
```



### fn spec.realm.applications.withClientTemplate

```ts
withClientTemplate(clientTemplate)
```



### fn spec.realm.applications.withConsentRequired

```ts
withConsentRequired(consentRequired)
```



### fn spec.realm.applications.withDefaultClientScopes

```ts
withDefaultClientScopes(defaultClientScopes)
```



### fn spec.realm.applications.withDefaultClientScopesMixin

```ts
withDefaultClientScopesMixin(defaultClientScopes)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.applications.withDefaultRoles

```ts
withDefaultRoles(defaultRoles)
```



### fn spec.realm.applications.withDefaultRolesMixin

```ts
withDefaultRolesMixin(defaultRoles)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.applications.withDescription

```ts
withDescription(description)
```



### fn spec.realm.applications.withDirectAccessGrantsEnabled

```ts
withDirectAccessGrantsEnabled(directAccessGrantsEnabled)
```



### fn spec.realm.applications.withDirectGrantsOnly

```ts
withDirectGrantsOnly(directGrantsOnly)
```



### fn spec.realm.applications.withEnabled

```ts
withEnabled(enabled)
```



### fn spec.realm.applications.withFrontchannelLogout

```ts
withFrontchannelLogout(frontchannelLogout)
```



### fn spec.realm.applications.withFullScopeAllowed

```ts
withFullScopeAllowed(fullScopeAllowed)
```



### fn spec.realm.applications.withId

```ts
withId(id)
```



### fn spec.realm.applications.withImplicitFlowEnabled

```ts
withImplicitFlowEnabled(implicitFlowEnabled)
```



### fn spec.realm.applications.withName

```ts
withName(name)
```



### fn spec.realm.applications.withNodeReRegistrationTimeout

```ts
withNodeReRegistrationTimeout(nodeReRegistrationTimeout)
```



### fn spec.realm.applications.withNotBefore

```ts
withNotBefore(notBefore)
```



### fn spec.realm.applications.withOptionalClientScopes

```ts
withOptionalClientScopes(optionalClientScopes)
```



### fn spec.realm.applications.withOptionalClientScopesMixin

```ts
withOptionalClientScopesMixin(optionalClientScopes)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.applications.withOrigin

```ts
withOrigin(origin)
```



### fn spec.realm.applications.withProtocol

```ts
withProtocol(protocol)
```



### fn spec.realm.applications.withProtocolMappers

```ts
withProtocolMappers(protocolMappers)
```



### fn spec.realm.applications.withProtocolMappersMixin

```ts
withProtocolMappersMixin(protocolMappers)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.applications.withPublicClient

```ts
withPublicClient(publicClient)
```



### fn spec.realm.applications.withRedirectUris

```ts
withRedirectUris(redirectUris)
```



### fn spec.realm.applications.withRedirectUrisMixin

```ts
withRedirectUrisMixin(redirectUris)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.applications.withRegisteredNodes

```ts
withRegisteredNodes(registeredNodes)
```



### fn spec.realm.applications.withRegisteredNodesMixin

```ts
withRegisteredNodesMixin(registeredNodes)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.applications.withRegistrationAccessToken

```ts
withRegistrationAccessToken(registrationAccessToken)
```



### fn spec.realm.applications.withRootUrl

```ts
withRootUrl(rootUrl)
```



### fn spec.realm.applications.withSecret

```ts
withSecret(secret)
```



### fn spec.realm.applications.withServiceAccountsEnabled

```ts
withServiceAccountsEnabled(serviceAccountsEnabled)
```



### fn spec.realm.applications.withStandardFlowEnabled

```ts
withStandardFlowEnabled(standardFlowEnabled)
```



### fn spec.realm.applications.withSurrogateAuthRequired

```ts
withSurrogateAuthRequired(surrogateAuthRequired)
```



### fn spec.realm.applications.withType

```ts
withType(type)
```



### fn spec.realm.applications.withUseTemplateConfig

```ts
withUseTemplateConfig(useTemplateConfig)
```



### fn spec.realm.applications.withUseTemplateMappers

```ts
withUseTemplateMappers(useTemplateMappers)
```



### fn spec.realm.applications.withUseTemplateScope

```ts
withUseTemplateScope(useTemplateScope)
```



### fn spec.realm.applications.withWebOrigins

```ts
withWebOrigins(webOrigins)
```



### fn spec.realm.applications.withWebOriginsMixin

```ts
withWebOriginsMixin(webOrigins)
```



**Note:** This function appends passed data to existing values

## obj spec.realm.applications.authorizationSettings



### fn spec.realm.applications.authorizationSettings.withAllowRemoteResourceManagement

```ts
withAllowRemoteResourceManagement(allowRemoteResourceManagement)
```



### fn spec.realm.applications.authorizationSettings.withClientId

```ts
withClientId(clientId)
```



### fn spec.realm.applications.authorizationSettings.withDecisionStrategy

```ts
withDecisionStrategy(decisionStrategy)
```



### fn spec.realm.applications.authorizationSettings.withId

```ts
withId(id)
```



### fn spec.realm.applications.authorizationSettings.withName

```ts
withName(name)
```



### fn spec.realm.applications.authorizationSettings.withPolicies

```ts
withPolicies(policies)
```



### fn spec.realm.applications.authorizationSettings.withPoliciesMixin

```ts
withPoliciesMixin(policies)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.applications.authorizationSettings.withPolicyEnforcementMode

```ts
withPolicyEnforcementMode(policyEnforcementMode)
```



### fn spec.realm.applications.authorizationSettings.withResources

```ts
withResources(resources)
```



### fn spec.realm.applications.authorizationSettings.withResourcesMixin

```ts
withResourcesMixin(resources)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.applications.authorizationSettings.withScopes

```ts
withScopes(scopes)
```



### fn spec.realm.applications.authorizationSettings.withScopesMixin

```ts
withScopesMixin(scopes)
```



**Note:** This function appends passed data to existing values

## obj spec.realm.applications.authorizationSettings.authorizationSchema



### fn spec.realm.applications.authorizationSettings.authorizationSchema.withResourceTypes

```ts
withResourceTypes(resourceTypes)
```



### fn spec.realm.applications.authorizationSettings.authorizationSchema.withResourceTypesMixin

```ts
withResourceTypesMixin(resourceTypes)
```



**Note:** This function appends passed data to existing values

## obj spec.realm.applications.authorizationSettings.policies



### fn spec.realm.applications.authorizationSettings.policies.withConfig

```ts
withConfig(config)
```



### fn spec.realm.applications.authorizationSettings.policies.withConfigMixin

```ts
withConfigMixin(config)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.applications.authorizationSettings.policies.withDecisionStrategy

```ts
withDecisionStrategy(decisionStrategy)
```



### fn spec.realm.applications.authorizationSettings.policies.withDescription

```ts
withDescription(description)
```



### fn spec.realm.applications.authorizationSettings.policies.withId

```ts
withId(id)
```



### fn spec.realm.applications.authorizationSettings.policies.withLogic

```ts
withLogic(logic)
```



### fn spec.realm.applications.authorizationSettings.policies.withName

```ts
withName(name)
```



### fn spec.realm.applications.authorizationSettings.policies.withOwner

```ts
withOwner(owner)
```



### fn spec.realm.applications.authorizationSettings.policies.withPolicies

```ts
withPolicies(policies)
```



### fn spec.realm.applications.authorizationSettings.policies.withPoliciesMixin

```ts
withPoliciesMixin(policies)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.applications.authorizationSettings.policies.withResourceType

```ts
withResourceType(resourceType)
```



### fn spec.realm.applications.authorizationSettings.policies.withResources

```ts
withResources(resources)
```



### fn spec.realm.applications.authorizationSettings.policies.withResourcesData

```ts
withResourcesData(resourcesData)
```



### fn spec.realm.applications.authorizationSettings.policies.withResourcesDataMixin

```ts
withResourcesDataMixin(resourcesData)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.applications.authorizationSettings.policies.withResourcesMixin

```ts
withResourcesMixin(resources)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.applications.authorizationSettings.policies.withScopes

```ts
withScopes(scopes)
```



### fn spec.realm.applications.authorizationSettings.policies.withScopesData

```ts
withScopesData(scopesData)
```



### fn spec.realm.applications.authorizationSettings.policies.withScopesDataMixin

```ts
withScopesDataMixin(scopesData)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.applications.authorizationSettings.policies.withScopesMixin

```ts
withScopesMixin(scopes)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.applications.authorizationSettings.policies.withType

```ts
withType(type)
```



## obj spec.realm.applications.authorizationSettings.policies.resourcesData



### fn spec.realm.applications.authorizationSettings.policies.resourcesData.withAttributes

```ts
withAttributes(attributes)
```



### fn spec.realm.applications.authorizationSettings.policies.resourcesData.withAttributesMixin

```ts
withAttributesMixin(attributes)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.applications.authorizationSettings.policies.resourcesData.withDisplayName

```ts
withDisplayName(displayName)
```



### fn spec.realm.applications.authorizationSettings.policies.resourcesData.withIcon_uri

```ts
withIcon_uri(icon_uri)
```



### fn spec.realm.applications.authorizationSettings.policies.resourcesData.withName

```ts
withName(name)
```



### fn spec.realm.applications.authorizationSettings.policies.resourcesData.withOwnerManagedAccess

```ts
withOwnerManagedAccess(ownerManagedAccess)
```



### fn spec.realm.applications.authorizationSettings.policies.resourcesData.withScopes

```ts
withScopes(scopes)
```



### fn spec.realm.applications.authorizationSettings.policies.resourcesData.withScopesMixin

```ts
withScopesMixin(scopes)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.applications.authorizationSettings.policies.resourcesData.withType

```ts
withType(type)
```



### fn spec.realm.applications.authorizationSettings.policies.resourcesData.withUris

```ts
withUris(uris)
```



### fn spec.realm.applications.authorizationSettings.policies.resourcesData.withUrisMixin

```ts
withUrisMixin(uris)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.applications.authorizationSettings.policies.resourcesData.with_id

```ts
with_id(_id)
```



## obj spec.realm.applications.authorizationSettings.policies.resourcesData.owner



### fn spec.realm.applications.authorizationSettings.policies.resourcesData.owner.withId

```ts
withId(id)
```



### fn spec.realm.applications.authorizationSettings.policies.resourcesData.owner.withName

```ts
withName(name)
```



## obj spec.realm.applications.authorizationSettings.policies.resourcesData.scopes



### fn spec.realm.applications.authorizationSettings.policies.resourcesData.scopes.withDisplayName

```ts
withDisplayName(displayName)
```



### fn spec.realm.applications.authorizationSettings.policies.resourcesData.scopes.withIconUri

```ts
withIconUri(iconUri)
```



### fn spec.realm.applications.authorizationSettings.policies.resourcesData.scopes.withId

```ts
withId(id)
```



### fn spec.realm.applications.authorizationSettings.policies.resourcesData.scopes.withName

```ts
withName(name)
```



## obj spec.realm.applications.authorizationSettings.policies.scopesData



### fn spec.realm.applications.authorizationSettings.policies.scopesData.withDisplayName

```ts
withDisplayName(displayName)
```



### fn spec.realm.applications.authorizationSettings.policies.scopesData.withIconUri

```ts
withIconUri(iconUri)
```



### fn spec.realm.applications.authorizationSettings.policies.scopesData.withId

```ts
withId(id)
```



### fn spec.realm.applications.authorizationSettings.policies.scopesData.withName

```ts
withName(name)
```



## obj spec.realm.applications.authorizationSettings.resources



### fn spec.realm.applications.authorizationSettings.resources.withAttributes

```ts
withAttributes(attributes)
```



### fn spec.realm.applications.authorizationSettings.resources.withAttributesMixin

```ts
withAttributesMixin(attributes)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.applications.authorizationSettings.resources.withDisplayName

```ts
withDisplayName(displayName)
```



### fn spec.realm.applications.authorizationSettings.resources.withIcon_uri

```ts
withIcon_uri(icon_uri)
```



### fn spec.realm.applications.authorizationSettings.resources.withName

```ts
withName(name)
```



### fn spec.realm.applications.authorizationSettings.resources.withOwnerManagedAccess

```ts
withOwnerManagedAccess(ownerManagedAccess)
```



### fn spec.realm.applications.authorizationSettings.resources.withScopes

```ts
withScopes(scopes)
```



### fn spec.realm.applications.authorizationSettings.resources.withScopesMixin

```ts
withScopesMixin(scopes)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.applications.authorizationSettings.resources.withType

```ts
withType(type)
```



### fn spec.realm.applications.authorizationSettings.resources.withUris

```ts
withUris(uris)
```



### fn spec.realm.applications.authorizationSettings.resources.withUrisMixin

```ts
withUrisMixin(uris)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.applications.authorizationSettings.resources.with_id

```ts
with_id(_id)
```



## obj spec.realm.applications.authorizationSettings.resources.owner



### fn spec.realm.applications.authorizationSettings.resources.owner.withId

```ts
withId(id)
```



### fn spec.realm.applications.authorizationSettings.resources.owner.withName

```ts
withName(name)
```



## obj spec.realm.applications.authorizationSettings.resources.scopes



### fn spec.realm.applications.authorizationSettings.resources.scopes.withDisplayName

```ts
withDisplayName(displayName)
```



### fn spec.realm.applications.authorizationSettings.resources.scopes.withIconUri

```ts
withIconUri(iconUri)
```



### fn spec.realm.applications.authorizationSettings.resources.scopes.withId

```ts
withId(id)
```



### fn spec.realm.applications.authorizationSettings.resources.scopes.withName

```ts
withName(name)
```



## obj spec.realm.applications.authorizationSettings.scopes



### fn spec.realm.applications.authorizationSettings.scopes.withDisplayName

```ts
withDisplayName(displayName)
```



### fn spec.realm.applications.authorizationSettings.scopes.withIconUri

```ts
withIconUri(iconUri)
```



### fn spec.realm.applications.authorizationSettings.scopes.withId

```ts
withId(id)
```



### fn spec.realm.applications.authorizationSettings.scopes.withName

```ts
withName(name)
```



## obj spec.realm.applications.claims



### fn spec.realm.applications.claims.withAddress

```ts
withAddress(address)
```



### fn spec.realm.applications.claims.withEmail

```ts
withEmail(email)
```



### fn spec.realm.applications.claims.withGender

```ts
withGender(gender)
```



### fn spec.realm.applications.claims.withLocale

```ts
withLocale(locale)
```



### fn spec.realm.applications.claims.withName

```ts
withName(name)
```



### fn spec.realm.applications.claims.withPhone

```ts
withPhone(phone)
```



### fn spec.realm.applications.claims.withPicture

```ts
withPicture(picture)
```



### fn spec.realm.applications.claims.withProfile

```ts
withProfile(profile)
```



### fn spec.realm.applications.claims.withUsername

```ts
withUsername(username)
```



### fn spec.realm.applications.claims.withWebsite

```ts
withWebsite(website)
```



## obj spec.realm.applications.protocolMappers



### fn spec.realm.applications.protocolMappers.withConfig

```ts
withConfig(config)
```



### fn spec.realm.applications.protocolMappers.withConfigMixin

```ts
withConfigMixin(config)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.applications.protocolMappers.withConsentRequired

```ts
withConsentRequired(consentRequired)
```



### fn spec.realm.applications.protocolMappers.withConsentText

```ts
withConsentText(consentText)
```



### fn spec.realm.applications.protocolMappers.withId

```ts
withId(id)
```



### fn spec.realm.applications.protocolMappers.withName

```ts
withName(name)
```



### fn spec.realm.applications.protocolMappers.withProtocol

```ts
withProtocol(protocol)
```



### fn spec.realm.applications.protocolMappers.withProtocolMapper

```ts
withProtocolMapper(protocolMapper)
```



## obj spec.realm.authenticationFlows



### fn spec.realm.authenticationFlows.withAlias

```ts
withAlias(alias)
```



### fn spec.realm.authenticationFlows.withAuthenticationExecutions

```ts
withAuthenticationExecutions(authenticationExecutions)
```



### fn spec.realm.authenticationFlows.withAuthenticationExecutionsMixin

```ts
withAuthenticationExecutionsMixin(authenticationExecutions)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.authenticationFlows.withBuiltIn

```ts
withBuiltIn(builtIn)
```



### fn spec.realm.authenticationFlows.withDescription

```ts
withDescription(description)
```



### fn spec.realm.authenticationFlows.withId

```ts
withId(id)
```



### fn spec.realm.authenticationFlows.withProviderId

```ts
withProviderId(providerId)
```



### fn spec.realm.authenticationFlows.withTopLevel

```ts
withTopLevel(topLevel)
```



## obj spec.realm.authenticationFlows.authenticationExecutions



### fn spec.realm.authenticationFlows.authenticationExecutions.withAuthenticator

```ts
withAuthenticator(authenticator)
```



### fn spec.realm.authenticationFlows.authenticationExecutions.withAuthenticatorConfig

```ts
withAuthenticatorConfig(authenticatorConfig)
```



### fn spec.realm.authenticationFlows.authenticationExecutions.withAuthenticatorFlow

```ts
withAuthenticatorFlow(authenticatorFlow)
```



### fn spec.realm.authenticationFlows.authenticationExecutions.withAutheticatorFlow

```ts
withAutheticatorFlow(autheticatorFlow)
```



### fn spec.realm.authenticationFlows.authenticationExecutions.withFlowAlias

```ts
withFlowAlias(flowAlias)
```



### fn spec.realm.authenticationFlows.authenticationExecutions.withPriority

```ts
withPriority(priority)
```



### fn spec.realm.authenticationFlows.authenticationExecutions.withRequirement

```ts
withRequirement(requirement)
```



### fn spec.realm.authenticationFlows.authenticationExecutions.withUserSetupAllowed

```ts
withUserSetupAllowed(userSetupAllowed)
```



## obj spec.realm.authenticatorConfig



### fn spec.realm.authenticatorConfig.withAlias

```ts
withAlias(alias)
```



### fn spec.realm.authenticatorConfig.withConfig

```ts
withConfig(config)
```



### fn spec.realm.authenticatorConfig.withConfigMixin

```ts
withConfigMixin(config)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.authenticatorConfig.withId

```ts
withId(id)
```



## obj spec.realm.clientScopes



### fn spec.realm.clientScopes.withAttributes

```ts
withAttributes(attributes)
```



### fn spec.realm.clientScopes.withAttributesMixin

```ts
withAttributesMixin(attributes)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.clientScopes.withDescription

```ts
withDescription(description)
```



### fn spec.realm.clientScopes.withId

```ts
withId(id)
```



### fn spec.realm.clientScopes.withName

```ts
withName(name)
```



### fn spec.realm.clientScopes.withProtocol

```ts
withProtocol(protocol)
```



### fn spec.realm.clientScopes.withProtocolMappers

```ts
withProtocolMappers(protocolMappers)
```



### fn spec.realm.clientScopes.withProtocolMappersMixin

```ts
withProtocolMappersMixin(protocolMappers)
```



**Note:** This function appends passed data to existing values

## obj spec.realm.clientScopes.protocolMappers



### fn spec.realm.clientScopes.protocolMappers.withConfig

```ts
withConfig(config)
```



### fn spec.realm.clientScopes.protocolMappers.withConfigMixin

```ts
withConfigMixin(config)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.clientScopes.protocolMappers.withConsentRequired

```ts
withConsentRequired(consentRequired)
```



### fn spec.realm.clientScopes.protocolMappers.withConsentText

```ts
withConsentText(consentText)
```



### fn spec.realm.clientScopes.protocolMappers.withId

```ts
withId(id)
```



### fn spec.realm.clientScopes.protocolMappers.withName

```ts
withName(name)
```



### fn spec.realm.clientScopes.protocolMappers.withProtocol

```ts
withProtocol(protocol)
```



### fn spec.realm.clientScopes.protocolMappers.withProtocolMapper

```ts
withProtocolMapper(protocolMapper)
```



## obj spec.realm.clientTemplates



### fn spec.realm.clientTemplates.withAttributes

```ts
withAttributes(attributes)
```



### fn spec.realm.clientTemplates.withAttributesMixin

```ts
withAttributesMixin(attributes)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.clientTemplates.withBearerOnly

```ts
withBearerOnly(bearerOnly)
```



### fn spec.realm.clientTemplates.withConsentRequired

```ts
withConsentRequired(consentRequired)
```



### fn spec.realm.clientTemplates.withDescription

```ts
withDescription(description)
```



### fn spec.realm.clientTemplates.withDirectAccessGrantsEnabled

```ts
withDirectAccessGrantsEnabled(directAccessGrantsEnabled)
```



### fn spec.realm.clientTemplates.withFrontchannelLogout

```ts
withFrontchannelLogout(frontchannelLogout)
```



### fn spec.realm.clientTemplates.withFullScopeAllowed

```ts
withFullScopeAllowed(fullScopeAllowed)
```



### fn spec.realm.clientTemplates.withId

```ts
withId(id)
```



### fn spec.realm.clientTemplates.withImplicitFlowEnabled

```ts
withImplicitFlowEnabled(implicitFlowEnabled)
```



### fn spec.realm.clientTemplates.withName

```ts
withName(name)
```



### fn spec.realm.clientTemplates.withProtocol

```ts
withProtocol(protocol)
```



### fn spec.realm.clientTemplates.withProtocolMappers

```ts
withProtocolMappers(protocolMappers)
```



### fn spec.realm.clientTemplates.withProtocolMappersMixin

```ts
withProtocolMappersMixin(protocolMappers)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.clientTemplates.withPublicClient

```ts
withPublicClient(publicClient)
```



### fn spec.realm.clientTemplates.withServiceAccountsEnabled

```ts
withServiceAccountsEnabled(serviceAccountsEnabled)
```



### fn spec.realm.clientTemplates.withStandardFlowEnabled

```ts
withStandardFlowEnabled(standardFlowEnabled)
```



## obj spec.realm.clientTemplates.protocolMappers



### fn spec.realm.clientTemplates.protocolMappers.withConfig

```ts
withConfig(config)
```



### fn spec.realm.clientTemplates.protocolMappers.withConfigMixin

```ts
withConfigMixin(config)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.clientTemplates.protocolMappers.withConsentRequired

```ts
withConsentRequired(consentRequired)
```



### fn spec.realm.clientTemplates.protocolMappers.withConsentText

```ts
withConsentText(consentText)
```



### fn spec.realm.clientTemplates.protocolMappers.withId

```ts
withId(id)
```



### fn spec.realm.clientTemplates.protocolMappers.withName

```ts
withName(name)
```



### fn spec.realm.clientTemplates.protocolMappers.withProtocol

```ts
withProtocol(protocol)
```



### fn spec.realm.clientTemplates.protocolMappers.withProtocolMapper

```ts
withProtocolMapper(protocolMapper)
```



## obj spec.realm.clients



### fn spec.realm.clients.withAccess

```ts
withAccess(access)
```



### fn spec.realm.clients.withAccessMixin

```ts
withAccessMixin(access)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.clients.withAdminUrl

```ts
withAdminUrl(adminUrl)
```



### fn spec.realm.clients.withAlwaysDisplayInConsole

```ts
withAlwaysDisplayInConsole(alwaysDisplayInConsole)
```



### fn spec.realm.clients.withAttributes

```ts
withAttributes(attributes)
```



### fn spec.realm.clients.withAttributesMixin

```ts
withAttributesMixin(attributes)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.clients.withAuthenticationFlowBindingOverrides

```ts
withAuthenticationFlowBindingOverrides(authenticationFlowBindingOverrides)
```



### fn spec.realm.clients.withAuthenticationFlowBindingOverridesMixin

```ts
withAuthenticationFlowBindingOverridesMixin(authenticationFlowBindingOverrides)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.clients.withAuthorizationServicesEnabled

```ts
withAuthorizationServicesEnabled(authorizationServicesEnabled)
```



### fn spec.realm.clients.withBaseUrl

```ts
withBaseUrl(baseUrl)
```



### fn spec.realm.clients.withBearerOnly

```ts
withBearerOnly(bearerOnly)
```



### fn spec.realm.clients.withClientAuthenticatorType

```ts
withClientAuthenticatorType(clientAuthenticatorType)
```



### fn spec.realm.clients.withClientId

```ts
withClientId(clientId)
```



### fn spec.realm.clients.withClientTemplate

```ts
withClientTemplate(clientTemplate)
```



### fn spec.realm.clients.withConsentRequired

```ts
withConsentRequired(consentRequired)
```



### fn spec.realm.clients.withDefaultClientScopes

```ts
withDefaultClientScopes(defaultClientScopes)
```



### fn spec.realm.clients.withDefaultClientScopesMixin

```ts
withDefaultClientScopesMixin(defaultClientScopes)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.clients.withDefaultRoles

```ts
withDefaultRoles(defaultRoles)
```



### fn spec.realm.clients.withDefaultRolesMixin

```ts
withDefaultRolesMixin(defaultRoles)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.clients.withDescription

```ts
withDescription(description)
```



### fn spec.realm.clients.withDirectAccessGrantsEnabled

```ts
withDirectAccessGrantsEnabled(directAccessGrantsEnabled)
```



### fn spec.realm.clients.withDirectGrantsOnly

```ts
withDirectGrantsOnly(directGrantsOnly)
```



### fn spec.realm.clients.withEnabled

```ts
withEnabled(enabled)
```



### fn spec.realm.clients.withFrontchannelLogout

```ts
withFrontchannelLogout(frontchannelLogout)
```



### fn spec.realm.clients.withFullScopeAllowed

```ts
withFullScopeAllowed(fullScopeAllowed)
```



### fn spec.realm.clients.withId

```ts
withId(id)
```



### fn spec.realm.clients.withImplicitFlowEnabled

```ts
withImplicitFlowEnabled(implicitFlowEnabled)
```



### fn spec.realm.clients.withName

```ts
withName(name)
```



### fn spec.realm.clients.withNodeReRegistrationTimeout

```ts
withNodeReRegistrationTimeout(nodeReRegistrationTimeout)
```



### fn spec.realm.clients.withNotBefore

```ts
withNotBefore(notBefore)
```



### fn spec.realm.clients.withOptionalClientScopes

```ts
withOptionalClientScopes(optionalClientScopes)
```



### fn spec.realm.clients.withOptionalClientScopesMixin

```ts
withOptionalClientScopesMixin(optionalClientScopes)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.clients.withOrigin

```ts
withOrigin(origin)
```



### fn spec.realm.clients.withProtocol

```ts
withProtocol(protocol)
```



### fn spec.realm.clients.withProtocolMappers

```ts
withProtocolMappers(protocolMappers)
```



### fn spec.realm.clients.withProtocolMappersMixin

```ts
withProtocolMappersMixin(protocolMappers)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.clients.withPublicClient

```ts
withPublicClient(publicClient)
```



### fn spec.realm.clients.withRedirectUris

```ts
withRedirectUris(redirectUris)
```



### fn spec.realm.clients.withRedirectUrisMixin

```ts
withRedirectUrisMixin(redirectUris)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.clients.withRegisteredNodes

```ts
withRegisteredNodes(registeredNodes)
```



### fn spec.realm.clients.withRegisteredNodesMixin

```ts
withRegisteredNodesMixin(registeredNodes)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.clients.withRegistrationAccessToken

```ts
withRegistrationAccessToken(registrationAccessToken)
```



### fn spec.realm.clients.withRootUrl

```ts
withRootUrl(rootUrl)
```



### fn spec.realm.clients.withSecret

```ts
withSecret(secret)
```



### fn spec.realm.clients.withServiceAccountsEnabled

```ts
withServiceAccountsEnabled(serviceAccountsEnabled)
```



### fn spec.realm.clients.withStandardFlowEnabled

```ts
withStandardFlowEnabled(standardFlowEnabled)
```



### fn spec.realm.clients.withSurrogateAuthRequired

```ts
withSurrogateAuthRequired(surrogateAuthRequired)
```



### fn spec.realm.clients.withType

```ts
withType(type)
```



### fn spec.realm.clients.withUseTemplateConfig

```ts
withUseTemplateConfig(useTemplateConfig)
```



### fn spec.realm.clients.withUseTemplateMappers

```ts
withUseTemplateMappers(useTemplateMappers)
```



### fn spec.realm.clients.withUseTemplateScope

```ts
withUseTemplateScope(useTemplateScope)
```



### fn spec.realm.clients.withWebOrigins

```ts
withWebOrigins(webOrigins)
```



### fn spec.realm.clients.withWebOriginsMixin

```ts
withWebOriginsMixin(webOrigins)
```



**Note:** This function appends passed data to existing values

## obj spec.realm.clients.authorizationSettings



### fn spec.realm.clients.authorizationSettings.withAllowRemoteResourceManagement

```ts
withAllowRemoteResourceManagement(allowRemoteResourceManagement)
```



### fn spec.realm.clients.authorizationSettings.withClientId

```ts
withClientId(clientId)
```



### fn spec.realm.clients.authorizationSettings.withDecisionStrategy

```ts
withDecisionStrategy(decisionStrategy)
```



### fn spec.realm.clients.authorizationSettings.withId

```ts
withId(id)
```



### fn spec.realm.clients.authorizationSettings.withName

```ts
withName(name)
```



### fn spec.realm.clients.authorizationSettings.withPolicies

```ts
withPolicies(policies)
```



### fn spec.realm.clients.authorizationSettings.withPoliciesMixin

```ts
withPoliciesMixin(policies)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.clients.authorizationSettings.withPolicyEnforcementMode

```ts
withPolicyEnforcementMode(policyEnforcementMode)
```



### fn spec.realm.clients.authorizationSettings.withResources

```ts
withResources(resources)
```



### fn spec.realm.clients.authorizationSettings.withResourcesMixin

```ts
withResourcesMixin(resources)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.clients.authorizationSettings.withScopes

```ts
withScopes(scopes)
```



### fn spec.realm.clients.authorizationSettings.withScopesMixin

```ts
withScopesMixin(scopes)
```



**Note:** This function appends passed data to existing values

## obj spec.realm.clients.authorizationSettings.authorizationSchema



### fn spec.realm.clients.authorizationSettings.authorizationSchema.withResourceTypes

```ts
withResourceTypes(resourceTypes)
```



### fn spec.realm.clients.authorizationSettings.authorizationSchema.withResourceTypesMixin

```ts
withResourceTypesMixin(resourceTypes)
```



**Note:** This function appends passed data to existing values

## obj spec.realm.clients.authorizationSettings.policies



### fn spec.realm.clients.authorizationSettings.policies.withConfig

```ts
withConfig(config)
```



### fn spec.realm.clients.authorizationSettings.policies.withConfigMixin

```ts
withConfigMixin(config)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.clients.authorizationSettings.policies.withDecisionStrategy

```ts
withDecisionStrategy(decisionStrategy)
```



### fn spec.realm.clients.authorizationSettings.policies.withDescription

```ts
withDescription(description)
```



### fn spec.realm.clients.authorizationSettings.policies.withId

```ts
withId(id)
```



### fn spec.realm.clients.authorizationSettings.policies.withLogic

```ts
withLogic(logic)
```



### fn spec.realm.clients.authorizationSettings.policies.withName

```ts
withName(name)
```



### fn spec.realm.clients.authorizationSettings.policies.withOwner

```ts
withOwner(owner)
```



### fn spec.realm.clients.authorizationSettings.policies.withPolicies

```ts
withPolicies(policies)
```



### fn spec.realm.clients.authorizationSettings.policies.withPoliciesMixin

```ts
withPoliciesMixin(policies)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.clients.authorizationSettings.policies.withResourceType

```ts
withResourceType(resourceType)
```



### fn spec.realm.clients.authorizationSettings.policies.withResources

```ts
withResources(resources)
```



### fn spec.realm.clients.authorizationSettings.policies.withResourcesData

```ts
withResourcesData(resourcesData)
```



### fn spec.realm.clients.authorizationSettings.policies.withResourcesDataMixin

```ts
withResourcesDataMixin(resourcesData)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.clients.authorizationSettings.policies.withResourcesMixin

```ts
withResourcesMixin(resources)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.clients.authorizationSettings.policies.withScopes

```ts
withScopes(scopes)
```



### fn spec.realm.clients.authorizationSettings.policies.withScopesData

```ts
withScopesData(scopesData)
```



### fn spec.realm.clients.authorizationSettings.policies.withScopesDataMixin

```ts
withScopesDataMixin(scopesData)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.clients.authorizationSettings.policies.withScopesMixin

```ts
withScopesMixin(scopes)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.clients.authorizationSettings.policies.withType

```ts
withType(type)
```



## obj spec.realm.clients.authorizationSettings.policies.resourcesData



### fn spec.realm.clients.authorizationSettings.policies.resourcesData.withAttributes

```ts
withAttributes(attributes)
```



### fn spec.realm.clients.authorizationSettings.policies.resourcesData.withAttributesMixin

```ts
withAttributesMixin(attributes)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.clients.authorizationSettings.policies.resourcesData.withDisplayName

```ts
withDisplayName(displayName)
```



### fn spec.realm.clients.authorizationSettings.policies.resourcesData.withIcon_uri

```ts
withIcon_uri(icon_uri)
```



### fn spec.realm.clients.authorizationSettings.policies.resourcesData.withName

```ts
withName(name)
```



### fn spec.realm.clients.authorizationSettings.policies.resourcesData.withOwnerManagedAccess

```ts
withOwnerManagedAccess(ownerManagedAccess)
```



### fn spec.realm.clients.authorizationSettings.policies.resourcesData.withScopes

```ts
withScopes(scopes)
```



### fn spec.realm.clients.authorizationSettings.policies.resourcesData.withScopesMixin

```ts
withScopesMixin(scopes)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.clients.authorizationSettings.policies.resourcesData.withType

```ts
withType(type)
```



### fn spec.realm.clients.authorizationSettings.policies.resourcesData.withUris

```ts
withUris(uris)
```



### fn spec.realm.clients.authorizationSettings.policies.resourcesData.withUrisMixin

```ts
withUrisMixin(uris)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.clients.authorizationSettings.policies.resourcesData.with_id

```ts
with_id(_id)
```



## obj spec.realm.clients.authorizationSettings.policies.resourcesData.owner



### fn spec.realm.clients.authorizationSettings.policies.resourcesData.owner.withId

```ts
withId(id)
```



### fn spec.realm.clients.authorizationSettings.policies.resourcesData.owner.withName

```ts
withName(name)
```



## obj spec.realm.clients.authorizationSettings.policies.resourcesData.scopes



### fn spec.realm.clients.authorizationSettings.policies.resourcesData.scopes.withDisplayName

```ts
withDisplayName(displayName)
```



### fn spec.realm.clients.authorizationSettings.policies.resourcesData.scopes.withIconUri

```ts
withIconUri(iconUri)
```



### fn spec.realm.clients.authorizationSettings.policies.resourcesData.scopes.withId

```ts
withId(id)
```



### fn spec.realm.clients.authorizationSettings.policies.resourcesData.scopes.withName

```ts
withName(name)
```



## obj spec.realm.clients.authorizationSettings.policies.scopesData



### fn spec.realm.clients.authorizationSettings.policies.scopesData.withDisplayName

```ts
withDisplayName(displayName)
```



### fn spec.realm.clients.authorizationSettings.policies.scopesData.withIconUri

```ts
withIconUri(iconUri)
```



### fn spec.realm.clients.authorizationSettings.policies.scopesData.withId

```ts
withId(id)
```



### fn spec.realm.clients.authorizationSettings.policies.scopesData.withName

```ts
withName(name)
```



## obj spec.realm.clients.authorizationSettings.resources



### fn spec.realm.clients.authorizationSettings.resources.withAttributes

```ts
withAttributes(attributes)
```



### fn spec.realm.clients.authorizationSettings.resources.withAttributesMixin

```ts
withAttributesMixin(attributes)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.clients.authorizationSettings.resources.withDisplayName

```ts
withDisplayName(displayName)
```



### fn spec.realm.clients.authorizationSettings.resources.withIcon_uri

```ts
withIcon_uri(icon_uri)
```



### fn spec.realm.clients.authorizationSettings.resources.withName

```ts
withName(name)
```



### fn spec.realm.clients.authorizationSettings.resources.withOwnerManagedAccess

```ts
withOwnerManagedAccess(ownerManagedAccess)
```



### fn spec.realm.clients.authorizationSettings.resources.withScopes

```ts
withScopes(scopes)
```



### fn spec.realm.clients.authorizationSettings.resources.withScopesMixin

```ts
withScopesMixin(scopes)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.clients.authorizationSettings.resources.withType

```ts
withType(type)
```



### fn spec.realm.clients.authorizationSettings.resources.withUris

```ts
withUris(uris)
```



### fn spec.realm.clients.authorizationSettings.resources.withUrisMixin

```ts
withUrisMixin(uris)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.clients.authorizationSettings.resources.with_id

```ts
with_id(_id)
```



## obj spec.realm.clients.authorizationSettings.resources.owner



### fn spec.realm.clients.authorizationSettings.resources.owner.withId

```ts
withId(id)
```



### fn spec.realm.clients.authorizationSettings.resources.owner.withName

```ts
withName(name)
```



## obj spec.realm.clients.authorizationSettings.resources.scopes



### fn spec.realm.clients.authorizationSettings.resources.scopes.withDisplayName

```ts
withDisplayName(displayName)
```



### fn spec.realm.clients.authorizationSettings.resources.scopes.withIconUri

```ts
withIconUri(iconUri)
```



### fn spec.realm.clients.authorizationSettings.resources.scopes.withId

```ts
withId(id)
```



### fn spec.realm.clients.authorizationSettings.resources.scopes.withName

```ts
withName(name)
```



## obj spec.realm.clients.authorizationSettings.scopes



### fn spec.realm.clients.authorizationSettings.scopes.withDisplayName

```ts
withDisplayName(displayName)
```



### fn spec.realm.clients.authorizationSettings.scopes.withIconUri

```ts
withIconUri(iconUri)
```



### fn spec.realm.clients.authorizationSettings.scopes.withId

```ts
withId(id)
```



### fn spec.realm.clients.authorizationSettings.scopes.withName

```ts
withName(name)
```



## obj spec.realm.clients.protocolMappers



### fn spec.realm.clients.protocolMappers.withConfig

```ts
withConfig(config)
```



### fn spec.realm.clients.protocolMappers.withConfigMixin

```ts
withConfigMixin(config)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.clients.protocolMappers.withConsentRequired

```ts
withConsentRequired(consentRequired)
```



### fn spec.realm.clients.protocolMappers.withConsentText

```ts
withConsentText(consentText)
```



### fn spec.realm.clients.protocolMappers.withId

```ts
withId(id)
```



### fn spec.realm.clients.protocolMappers.withName

```ts
withName(name)
```



### fn spec.realm.clients.protocolMappers.withProtocol

```ts
withProtocol(protocol)
```



### fn spec.realm.clients.protocolMappers.withProtocolMapper

```ts
withProtocolMapper(protocolMapper)
```



## obj spec.realm.defaultRole



### fn spec.realm.defaultRole.withAttributes

```ts
withAttributes(attributes)
```



### fn spec.realm.defaultRole.withAttributesMixin

```ts
withAttributesMixin(attributes)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.defaultRole.withClientRole

```ts
withClientRole(clientRole)
```



### fn spec.realm.defaultRole.withComposite

```ts
withComposite(composite)
```



### fn spec.realm.defaultRole.withContainerId

```ts
withContainerId(containerId)
```



### fn spec.realm.defaultRole.withDescription

```ts
withDescription(description)
```



### fn spec.realm.defaultRole.withId

```ts
withId(id)
```



### fn spec.realm.defaultRole.withName

```ts
withName(name)
```



### fn spec.realm.defaultRole.withScopeParamRequired

```ts
withScopeParamRequired(scopeParamRequired)
```



## obj spec.realm.defaultRole.composites



### fn spec.realm.defaultRole.composites.withApplication

```ts
withApplication(application)
```



### fn spec.realm.defaultRole.composites.withApplicationMixin

```ts
withApplicationMixin(application)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.defaultRole.composites.withClient

```ts
withClient(client)
```



### fn spec.realm.defaultRole.composites.withClientMixin

```ts
withClientMixin(client)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.defaultRole.composites.withRealm

```ts
withRealm(realm)
```



### fn spec.realm.defaultRole.composites.withRealmMixin

```ts
withRealmMixin(realm)
```



**Note:** This function appends passed data to existing values

## obj spec.realm.federatedUsers



### fn spec.realm.federatedUsers.withAccess

```ts
withAccess(access)
```



### fn spec.realm.federatedUsers.withAccessMixin

```ts
withAccessMixin(access)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.federatedUsers.withApplicationRoles

```ts
withApplicationRoles(applicationRoles)
```



### fn spec.realm.federatedUsers.withApplicationRolesMixin

```ts
withApplicationRolesMixin(applicationRoles)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.federatedUsers.withAttributes

```ts
withAttributes(attributes)
```



### fn spec.realm.federatedUsers.withAttributesMixin

```ts
withAttributesMixin(attributes)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.federatedUsers.withClientConsents

```ts
withClientConsents(clientConsents)
```



### fn spec.realm.federatedUsers.withClientConsentsMixin

```ts
withClientConsentsMixin(clientConsents)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.federatedUsers.withClientRoles

```ts
withClientRoles(clientRoles)
```



### fn spec.realm.federatedUsers.withClientRolesMixin

```ts
withClientRolesMixin(clientRoles)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.federatedUsers.withCreatedTimestamp

```ts
withCreatedTimestamp(createdTimestamp)
```



### fn spec.realm.federatedUsers.withCredentials

```ts
withCredentials(credentials)
```



### fn spec.realm.federatedUsers.withCredentialsMixin

```ts
withCredentialsMixin(credentials)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.federatedUsers.withDisableableCredentialTypes

```ts
withDisableableCredentialTypes(disableableCredentialTypes)
```



### fn spec.realm.federatedUsers.withDisableableCredentialTypesMixin

```ts
withDisableableCredentialTypesMixin(disableableCredentialTypes)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.federatedUsers.withEmail

```ts
withEmail(email)
```



### fn spec.realm.federatedUsers.withEmailVerified

```ts
withEmailVerified(emailVerified)
```



### fn spec.realm.federatedUsers.withEnabled

```ts
withEnabled(enabled)
```



### fn spec.realm.federatedUsers.withFederatedIdentities

```ts
withFederatedIdentities(federatedIdentities)
```



### fn spec.realm.federatedUsers.withFederatedIdentitiesMixin

```ts
withFederatedIdentitiesMixin(federatedIdentities)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.federatedUsers.withFederationLink

```ts
withFederationLink(federationLink)
```



### fn spec.realm.federatedUsers.withFirstName

```ts
withFirstName(firstName)
```



### fn spec.realm.federatedUsers.withGroups

```ts
withGroups(groups)
```



### fn spec.realm.federatedUsers.withGroupsMixin

```ts
withGroupsMixin(groups)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.federatedUsers.withId

```ts
withId(id)
```



### fn spec.realm.federatedUsers.withLastName

```ts
withLastName(lastName)
```



### fn spec.realm.federatedUsers.withNotBefore

```ts
withNotBefore(notBefore)
```



### fn spec.realm.federatedUsers.withOrigin

```ts
withOrigin(origin)
```



### fn spec.realm.federatedUsers.withRealmRoles

```ts
withRealmRoles(realmRoles)
```



### fn spec.realm.federatedUsers.withRealmRolesMixin

```ts
withRealmRolesMixin(realmRoles)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.federatedUsers.withRequiredActions

```ts
withRequiredActions(requiredActions)
```



### fn spec.realm.federatedUsers.withRequiredActionsMixin

```ts
withRequiredActionsMixin(requiredActions)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.federatedUsers.withSelf

```ts
withSelf(Self)
```



### fn spec.realm.federatedUsers.withServiceAccountClientId

```ts
withServiceAccountClientId(serviceAccountClientId)
```



### fn spec.realm.federatedUsers.withSocialLinks

```ts
withSocialLinks(socialLinks)
```



### fn spec.realm.federatedUsers.withSocialLinksMixin

```ts
withSocialLinksMixin(socialLinks)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.federatedUsers.withTotp

```ts
withTotp(totp)
```



### fn spec.realm.federatedUsers.withUsername

```ts
withUsername(username)
```



## obj spec.realm.federatedUsers.clientConsents



### fn spec.realm.federatedUsers.clientConsents.withClientId

```ts
withClientId(clientId)
```



### fn spec.realm.federatedUsers.clientConsents.withCreatedDate

```ts
withCreatedDate(createdDate)
```



### fn spec.realm.federatedUsers.clientConsents.withGrantedClientScopes

```ts
withGrantedClientScopes(grantedClientScopes)
```



### fn spec.realm.federatedUsers.clientConsents.withGrantedClientScopesMixin

```ts
withGrantedClientScopesMixin(grantedClientScopes)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.federatedUsers.clientConsents.withGrantedRealmRoles

```ts
withGrantedRealmRoles(grantedRealmRoles)
```



### fn spec.realm.federatedUsers.clientConsents.withGrantedRealmRolesMixin

```ts
withGrantedRealmRolesMixin(grantedRealmRoles)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.federatedUsers.clientConsents.withLastUpdatedDate

```ts
withLastUpdatedDate(lastUpdatedDate)
```



## obj spec.realm.federatedUsers.credentials



### fn spec.realm.federatedUsers.credentials.withAlgorithm

```ts
withAlgorithm(algorithm)
```



### fn spec.realm.federatedUsers.credentials.withConfig

```ts
withConfig(config)
```



### fn spec.realm.federatedUsers.credentials.withConfigMixin

```ts
withConfigMixin(config)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.federatedUsers.credentials.withCounter

```ts
withCounter(counter)
```



### fn spec.realm.federatedUsers.credentials.withCreatedDate

```ts
withCreatedDate(createdDate)
```



### fn spec.realm.federatedUsers.credentials.withCredentialData

```ts
withCredentialData(credentialData)
```



### fn spec.realm.federatedUsers.credentials.withDevice

```ts
withDevice(device)
```



### fn spec.realm.federatedUsers.credentials.withDigits

```ts
withDigits(digits)
```



### fn spec.realm.federatedUsers.credentials.withFederationLink

```ts
withFederationLink(federationLink)
```



### fn spec.realm.federatedUsers.credentials.withHashIterations

```ts
withHashIterations(hashIterations)
```



### fn spec.realm.federatedUsers.credentials.withHashedSaltedValue

```ts
withHashedSaltedValue(hashedSaltedValue)
```



### fn spec.realm.federatedUsers.credentials.withId

```ts
withId(id)
```



### fn spec.realm.federatedUsers.credentials.withPeriod

```ts
withPeriod(period)
```



### fn spec.realm.federatedUsers.credentials.withPriority

```ts
withPriority(priority)
```



### fn spec.realm.federatedUsers.credentials.withSalt

```ts
withSalt(salt)
```



### fn spec.realm.federatedUsers.credentials.withSecretData

```ts
withSecretData(secretData)
```



### fn spec.realm.federatedUsers.credentials.withTemporary

```ts
withTemporary(temporary)
```



### fn spec.realm.federatedUsers.credentials.withType

```ts
withType(type)
```



### fn spec.realm.federatedUsers.credentials.withUserLabel

```ts
withUserLabel(userLabel)
```



### fn spec.realm.federatedUsers.credentials.withValue

```ts
withValue(value)
```



## obj spec.realm.federatedUsers.federatedIdentities



### fn spec.realm.federatedUsers.federatedIdentities.withIdentityProvider

```ts
withIdentityProvider(identityProvider)
```



### fn spec.realm.federatedUsers.federatedIdentities.withUserId

```ts
withUserId(userId)
```



### fn spec.realm.federatedUsers.federatedIdentities.withUserName

```ts
withUserName(userName)
```



## obj spec.realm.federatedUsers.socialLinks



### fn spec.realm.federatedUsers.socialLinks.withSocialProvider

```ts
withSocialProvider(socialProvider)
```



### fn spec.realm.federatedUsers.socialLinks.withSocialUserId

```ts
withSocialUserId(socialUserId)
```



### fn spec.realm.federatedUsers.socialLinks.withSocialUsername

```ts
withSocialUsername(socialUsername)
```



## obj spec.realm.federatedUsers.userProfileMetadata



### fn spec.realm.federatedUsers.userProfileMetadata.withAttributes

```ts
withAttributes(attributes)
```



### fn spec.realm.federatedUsers.userProfileMetadata.withAttributesMixin

```ts
withAttributesMixin(attributes)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.federatedUsers.userProfileMetadata.withGroups

```ts
withGroups(groups)
```



### fn spec.realm.federatedUsers.userProfileMetadata.withGroupsMixin

```ts
withGroupsMixin(groups)
```



**Note:** This function appends passed data to existing values

## obj spec.realm.federatedUsers.userProfileMetadata.attributes



### fn spec.realm.federatedUsers.userProfileMetadata.attributes.withAnnotations

```ts
withAnnotations(annotations)
```



### fn spec.realm.federatedUsers.userProfileMetadata.attributes.withAnnotationsMixin

```ts
withAnnotationsMixin(annotations)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.federatedUsers.userProfileMetadata.attributes.withDefaultValue

```ts
withDefaultValue(defaultValue)
```



### fn spec.realm.federatedUsers.userProfileMetadata.attributes.withDisplayName

```ts
withDisplayName(displayName)
```



### fn spec.realm.federatedUsers.userProfileMetadata.attributes.withGroup

```ts
withGroup(group)
```



### fn spec.realm.federatedUsers.userProfileMetadata.attributes.withMultivalued

```ts
withMultivalued(multivalued)
```



### fn spec.realm.federatedUsers.userProfileMetadata.attributes.withName

```ts
withName(name)
```



### fn spec.realm.federatedUsers.userProfileMetadata.attributes.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.realm.federatedUsers.userProfileMetadata.attributes.withRequired

```ts
withRequired(required)
```



### fn spec.realm.federatedUsers.userProfileMetadata.attributes.withValidators

```ts
withValidators(validators)
```



### fn spec.realm.federatedUsers.userProfileMetadata.attributes.withValidatorsMixin

```ts
withValidatorsMixin(validators)
```



**Note:** This function appends passed data to existing values

## obj spec.realm.federatedUsers.userProfileMetadata.groups



### fn spec.realm.federatedUsers.userProfileMetadata.groups.withAnnotations

```ts
withAnnotations(annotations)
```



### fn spec.realm.federatedUsers.userProfileMetadata.groups.withAnnotationsMixin

```ts
withAnnotationsMixin(annotations)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.federatedUsers.userProfileMetadata.groups.withDisplayDescription

```ts
withDisplayDescription(displayDescription)
```



### fn spec.realm.federatedUsers.userProfileMetadata.groups.withDisplayHeader

```ts
withDisplayHeader(displayHeader)
```



### fn spec.realm.federatedUsers.userProfileMetadata.groups.withName

```ts
withName(name)
```



## obj spec.realm.groups



### fn spec.realm.groups.withAccess

```ts
withAccess(access)
```



### fn spec.realm.groups.withAccessMixin

```ts
withAccessMixin(access)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.groups.withAttributes

```ts
withAttributes(attributes)
```



### fn spec.realm.groups.withAttributesMixin

```ts
withAttributesMixin(attributes)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.groups.withClientRoles

```ts
withClientRoles(clientRoles)
```



### fn spec.realm.groups.withClientRolesMixin

```ts
withClientRolesMixin(clientRoles)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.groups.withDescription

```ts
withDescription(description)
```



### fn spec.realm.groups.withId

```ts
withId(id)
```



### fn spec.realm.groups.withName

```ts
withName(name)
```



### fn spec.realm.groups.withParentId

```ts
withParentId(parentId)
```



### fn spec.realm.groups.withPath

```ts
withPath(path)
```



### fn spec.realm.groups.withRealmRoles

```ts
withRealmRoles(realmRoles)
```



### fn spec.realm.groups.withRealmRolesMixin

```ts
withRealmRolesMixin(realmRoles)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.groups.withSubGroupCount

```ts
withSubGroupCount(subGroupCount)
```



### fn spec.realm.groups.withSubGroups

```ts
withSubGroups(subGroups)
```



### fn spec.realm.groups.withSubGroupsMixin

```ts
withSubGroupsMixin(subGroups)
```



**Note:** This function appends passed data to existing values

## obj spec.realm.groups.subGroups



### fn spec.realm.groups.subGroups.withAccess

```ts
withAccess(access)
```



### fn spec.realm.groups.subGroups.withAccessMixin

```ts
withAccessMixin(access)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.groups.subGroups.withAttributes

```ts
withAttributes(attributes)
```



### fn spec.realm.groups.subGroups.withAttributesMixin

```ts
withAttributesMixin(attributes)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.groups.subGroups.withClientRoles

```ts
withClientRoles(clientRoles)
```



### fn spec.realm.groups.subGroups.withClientRolesMixin

```ts
withClientRolesMixin(clientRoles)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.groups.subGroups.withDescription

```ts
withDescription(description)
```



### fn spec.realm.groups.subGroups.withId

```ts
withId(id)
```



### fn spec.realm.groups.subGroups.withName

```ts
withName(name)
```



### fn spec.realm.groups.subGroups.withParentId

```ts
withParentId(parentId)
```



### fn spec.realm.groups.subGroups.withPath

```ts
withPath(path)
```



### fn spec.realm.groups.subGroups.withRealmRoles

```ts
withRealmRoles(realmRoles)
```



### fn spec.realm.groups.subGroups.withRealmRolesMixin

```ts
withRealmRolesMixin(realmRoles)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.groups.subGroups.withSubGroupCount

```ts
withSubGroupCount(subGroupCount)
```



### fn spec.realm.groups.subGroups.withSubGroups

```ts
withSubGroups(subGroups)
```



### fn spec.realm.groups.subGroups.withSubGroupsMixin

```ts
withSubGroupsMixin(subGroups)
```



**Note:** This function appends passed data to existing values

## obj spec.realm.groups.subGroups.subGroups



### fn spec.realm.groups.subGroups.subGroups.withAccess

```ts
withAccess(access)
```



### fn spec.realm.groups.subGroups.subGroups.withAccessMixin

```ts
withAccessMixin(access)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.groups.subGroups.subGroups.withAttributes

```ts
withAttributes(attributes)
```



### fn spec.realm.groups.subGroups.subGroups.withAttributesMixin

```ts
withAttributesMixin(attributes)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.groups.subGroups.subGroups.withClientRoles

```ts
withClientRoles(clientRoles)
```



### fn spec.realm.groups.subGroups.subGroups.withClientRolesMixin

```ts
withClientRolesMixin(clientRoles)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.groups.subGroups.subGroups.withDescription

```ts
withDescription(description)
```



### fn spec.realm.groups.subGroups.subGroups.withId

```ts
withId(id)
```



### fn spec.realm.groups.subGroups.subGroups.withName

```ts
withName(name)
```



### fn spec.realm.groups.subGroups.subGroups.withParentId

```ts
withParentId(parentId)
```



### fn spec.realm.groups.subGroups.subGroups.withPath

```ts
withPath(path)
```



### fn spec.realm.groups.subGroups.subGroups.withRealmRoles

```ts
withRealmRoles(realmRoles)
```



### fn spec.realm.groups.subGroups.subGroups.withRealmRolesMixin

```ts
withRealmRolesMixin(realmRoles)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.groups.subGroups.subGroups.withSubGroupCount

```ts
withSubGroupCount(subGroupCount)
```



### fn spec.realm.groups.subGroups.subGroups.withSubGroups

```ts
withSubGroups(subGroups)
```



### fn spec.realm.groups.subGroups.subGroups.withSubGroupsMixin

```ts
withSubGroupsMixin(subGroups)
```



**Note:** This function appends passed data to existing values

## obj spec.realm.groups.subGroups.subGroups.subGroups



### fn spec.realm.groups.subGroups.subGroups.subGroups.withAccess

```ts
withAccess(access)
```



### fn spec.realm.groups.subGroups.subGroups.subGroups.withAccessMixin

```ts
withAccessMixin(access)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.groups.subGroups.subGroups.subGroups.withAttributes

```ts
withAttributes(attributes)
```



### fn spec.realm.groups.subGroups.subGroups.subGroups.withAttributesMixin

```ts
withAttributesMixin(attributes)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.groups.subGroups.subGroups.subGroups.withClientRoles

```ts
withClientRoles(clientRoles)
```



### fn spec.realm.groups.subGroups.subGroups.subGroups.withClientRolesMixin

```ts
withClientRolesMixin(clientRoles)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.groups.subGroups.subGroups.subGroups.withDescription

```ts
withDescription(description)
```



### fn spec.realm.groups.subGroups.subGroups.subGroups.withId

```ts
withId(id)
```



### fn spec.realm.groups.subGroups.subGroups.subGroups.withName

```ts
withName(name)
```



### fn spec.realm.groups.subGroups.subGroups.subGroups.withParentId

```ts
withParentId(parentId)
```



### fn spec.realm.groups.subGroups.subGroups.subGroups.withPath

```ts
withPath(path)
```



### fn spec.realm.groups.subGroups.subGroups.subGroups.withRealmRoles

```ts
withRealmRoles(realmRoles)
```



### fn spec.realm.groups.subGroups.subGroups.subGroups.withRealmRolesMixin

```ts
withRealmRolesMixin(realmRoles)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.groups.subGroups.subGroups.subGroups.withSubGroupCount

```ts
withSubGroupCount(subGroupCount)
```



### fn spec.realm.groups.subGroups.subGroups.subGroups.withSubGroups

```ts
withSubGroups(subGroups)
```



### fn spec.realm.groups.subGroups.subGroups.subGroups.withSubGroupsMixin

```ts
withSubGroupsMixin(subGroups)
```



**Note:** This function appends passed data to existing values

## obj spec.realm.groups.subGroups.subGroups.subGroups.subGroups



### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.withAccess

```ts
withAccess(access)
```



### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.withAccessMixin

```ts
withAccessMixin(access)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.withAttributes

```ts
withAttributes(attributes)
```



### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.withAttributesMixin

```ts
withAttributesMixin(attributes)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.withClientRoles

```ts
withClientRoles(clientRoles)
```



### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.withClientRolesMixin

```ts
withClientRolesMixin(clientRoles)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.withDescription

```ts
withDescription(description)
```



### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.withId

```ts
withId(id)
```



### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.withName

```ts
withName(name)
```



### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.withParentId

```ts
withParentId(parentId)
```



### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.withPath

```ts
withPath(path)
```



### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.withRealmRoles

```ts
withRealmRoles(realmRoles)
```



### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.withRealmRolesMixin

```ts
withRealmRolesMixin(realmRoles)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.withSubGroupCount

```ts
withSubGroupCount(subGroupCount)
```



### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.withSubGroups

```ts
withSubGroups(subGroups)
```



### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.withSubGroupsMixin

```ts
withSubGroupsMixin(subGroups)
```



**Note:** This function appends passed data to existing values

## obj spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups



### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.withAccess

```ts
withAccess(access)
```



### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.withAccessMixin

```ts
withAccessMixin(access)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.withAttributes

```ts
withAttributes(attributes)
```



### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.withAttributesMixin

```ts
withAttributesMixin(attributes)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.withClientRoles

```ts
withClientRoles(clientRoles)
```



### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.withClientRolesMixin

```ts
withClientRolesMixin(clientRoles)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.withDescription

```ts
withDescription(description)
```



### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.withId

```ts
withId(id)
```



### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.withName

```ts
withName(name)
```



### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.withParentId

```ts
withParentId(parentId)
```



### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.withPath

```ts
withPath(path)
```



### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.withRealmRoles

```ts
withRealmRoles(realmRoles)
```



### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.withRealmRolesMixin

```ts
withRealmRolesMixin(realmRoles)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.withSubGroupCount

```ts
withSubGroupCount(subGroupCount)
```



### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.withSubGroups

```ts
withSubGroups(subGroups)
```



### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.withSubGroupsMixin

```ts
withSubGroupsMixin(subGroups)
```



**Note:** This function appends passed data to existing values

## obj spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups



### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.withAccess

```ts
withAccess(access)
```



### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.withAccessMixin

```ts
withAccessMixin(access)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.withAttributes

```ts
withAttributes(attributes)
```



### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.withAttributesMixin

```ts
withAttributesMixin(attributes)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.withClientRoles

```ts
withClientRoles(clientRoles)
```



### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.withClientRolesMixin

```ts
withClientRolesMixin(clientRoles)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.withDescription

```ts
withDescription(description)
```



### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.withId

```ts
withId(id)
```



### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.withName

```ts
withName(name)
```



### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.withParentId

```ts
withParentId(parentId)
```



### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.withPath

```ts
withPath(path)
```



### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.withRealmRoles

```ts
withRealmRoles(realmRoles)
```



### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.withRealmRolesMixin

```ts
withRealmRolesMixin(realmRoles)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.withSubGroupCount

```ts
withSubGroupCount(subGroupCount)
```



### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.withSubGroups

```ts
withSubGroups(subGroups)
```



### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.withSubGroupsMixin

```ts
withSubGroupsMixin(subGroups)
```



**Note:** This function appends passed data to existing values

## obj spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups



### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.withAccess

```ts
withAccess(access)
```



### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.withAccessMixin

```ts
withAccessMixin(access)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.withAttributes

```ts
withAttributes(attributes)
```



### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.withAttributesMixin

```ts
withAttributesMixin(attributes)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.withClientRoles

```ts
withClientRoles(clientRoles)
```



### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.withClientRolesMixin

```ts
withClientRolesMixin(clientRoles)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.withDescription

```ts
withDescription(description)
```



### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.withId

```ts
withId(id)
```



### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.withName

```ts
withName(name)
```



### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.withParentId

```ts
withParentId(parentId)
```



### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.withPath

```ts
withPath(path)
```



### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.withRealmRoles

```ts
withRealmRoles(realmRoles)
```



### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.withRealmRolesMixin

```ts
withRealmRolesMixin(realmRoles)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.withSubGroupCount

```ts
withSubGroupCount(subGroupCount)
```



### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.withSubGroups

```ts
withSubGroups(subGroups)
```



### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.withSubGroupsMixin

```ts
withSubGroupsMixin(subGroups)
```



**Note:** This function appends passed data to existing values

## obj spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups



### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.withAccess

```ts
withAccess(access)
```



### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.withAccessMixin

```ts
withAccessMixin(access)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.withAttributes

```ts
withAttributes(attributes)
```



### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.withAttributesMixin

```ts
withAttributesMixin(attributes)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.withClientRoles

```ts
withClientRoles(clientRoles)
```



### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.withClientRolesMixin

```ts
withClientRolesMixin(clientRoles)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.withDescription

```ts
withDescription(description)
```



### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.withId

```ts
withId(id)
```



### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.withName

```ts
withName(name)
```



### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.withParentId

```ts
withParentId(parentId)
```



### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.withPath

```ts
withPath(path)
```



### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.withRealmRoles

```ts
withRealmRoles(realmRoles)
```



### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.withRealmRolesMixin

```ts
withRealmRolesMixin(realmRoles)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.withSubGroupCount

```ts
withSubGroupCount(subGroupCount)
```



### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.withSubGroups

```ts
withSubGroups(subGroups)
```



### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.withSubGroupsMixin

```ts
withSubGroupsMixin(subGroups)
```



**Note:** This function appends passed data to existing values

## obj spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups



### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.withAccess

```ts
withAccess(access)
```



### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.withAccessMixin

```ts
withAccessMixin(access)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.withAttributes

```ts
withAttributes(attributes)
```



### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.withAttributesMixin

```ts
withAttributesMixin(attributes)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.withClientRoles

```ts
withClientRoles(clientRoles)
```



### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.withClientRolesMixin

```ts
withClientRolesMixin(clientRoles)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.withDescription

```ts
withDescription(description)
```



### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.withId

```ts
withId(id)
```



### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.withName

```ts
withName(name)
```



### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.withParentId

```ts
withParentId(parentId)
```



### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.withPath

```ts
withPath(path)
```



### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.withRealmRoles

```ts
withRealmRoles(realmRoles)
```



### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.withRealmRolesMixin

```ts
withRealmRolesMixin(realmRoles)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.withSubGroupCount

```ts
withSubGroupCount(subGroupCount)
```



### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.withSubGroups

```ts
withSubGroups(subGroups)
```



### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.withSubGroupsMixin

```ts
withSubGroupsMixin(subGroups)
```



**Note:** This function appends passed data to existing values

## obj spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups



### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.withAccess

```ts
withAccess(access)
```



### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.withAccessMixin

```ts
withAccessMixin(access)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.withAttributes

```ts
withAttributes(attributes)
```



### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.withAttributesMixin

```ts
withAttributesMixin(attributes)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.withClientRoles

```ts
withClientRoles(clientRoles)
```



### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.withClientRolesMixin

```ts
withClientRolesMixin(clientRoles)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.withDescription

```ts
withDescription(description)
```



### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.withId

```ts
withId(id)
```



### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.withName

```ts
withName(name)
```



### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.withParentId

```ts
withParentId(parentId)
```



### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.withPath

```ts
withPath(path)
```



### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.withRealmRoles

```ts
withRealmRoles(realmRoles)
```



### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.withRealmRolesMixin

```ts
withRealmRolesMixin(realmRoles)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.groups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.subGroups.withSubGroupCount

```ts
withSubGroupCount(subGroupCount)
```



## obj spec.realm.identityProviderMappers



### fn spec.realm.identityProviderMappers.withConfig

```ts
withConfig(config)
```



### fn spec.realm.identityProviderMappers.withConfigMixin

```ts
withConfigMixin(config)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.identityProviderMappers.withId

```ts
withId(id)
```



### fn spec.realm.identityProviderMappers.withIdentityProviderAlias

```ts
withIdentityProviderAlias(identityProviderAlias)
```



### fn spec.realm.identityProviderMappers.withIdentityProviderMapper

```ts
withIdentityProviderMapper(identityProviderMapper)
```



### fn spec.realm.identityProviderMappers.withName

```ts
withName(name)
```



## obj spec.realm.identityProviders



### fn spec.realm.identityProviders.withAddReadTokenRoleOnCreate

```ts
withAddReadTokenRoleOnCreate(addReadTokenRoleOnCreate)
```



### fn spec.realm.identityProviders.withAlias

```ts
withAlias(alias)
```



### fn spec.realm.identityProviders.withAuthenticateByDefault

```ts
withAuthenticateByDefault(authenticateByDefault)
```



### fn spec.realm.identityProviders.withConfig

```ts
withConfig(config)
```



### fn spec.realm.identityProviders.withConfigMixin

```ts
withConfigMixin(config)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.identityProviders.withDisplayName

```ts
withDisplayName(displayName)
```



### fn spec.realm.identityProviders.withEnabled

```ts
withEnabled(enabled)
```



### fn spec.realm.identityProviders.withFirstBrokerLoginFlowAlias

```ts
withFirstBrokerLoginFlowAlias(firstBrokerLoginFlowAlias)
```



### fn spec.realm.identityProviders.withHideOnLogin

```ts
withHideOnLogin(hideOnLogin)
```



### fn spec.realm.identityProviders.withInternalId

```ts
withInternalId(internalId)
```



### fn spec.realm.identityProviders.withLinkOnly

```ts
withLinkOnly(linkOnly)
```



### fn spec.realm.identityProviders.withOrganizationId

```ts
withOrganizationId(organizationId)
```



### fn spec.realm.identityProviders.withPostBrokerLoginFlowAlias

```ts
withPostBrokerLoginFlowAlias(postBrokerLoginFlowAlias)
```



### fn spec.realm.identityProviders.withProviderId

```ts
withProviderId(providerId)
```



### fn spec.realm.identityProviders.withStoreToken

```ts
withStoreToken(storeToken)
```



### fn spec.realm.identityProviders.withTrustEmail

```ts
withTrustEmail(trustEmail)
```



### fn spec.realm.identityProviders.withUpdateProfileFirstLoginMode

```ts
withUpdateProfileFirstLoginMode(updateProfileFirstLoginMode)
```



## obj spec.realm.oauthClients



### fn spec.realm.oauthClients.withAccess

```ts
withAccess(access)
```



### fn spec.realm.oauthClients.withAccessMixin

```ts
withAccessMixin(access)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.oauthClients.withAdminUrl

```ts
withAdminUrl(adminUrl)
```



### fn spec.realm.oauthClients.withAlwaysDisplayInConsole

```ts
withAlwaysDisplayInConsole(alwaysDisplayInConsole)
```



### fn spec.realm.oauthClients.withAttributes

```ts
withAttributes(attributes)
```



### fn spec.realm.oauthClients.withAttributesMixin

```ts
withAttributesMixin(attributes)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.oauthClients.withAuthenticationFlowBindingOverrides

```ts
withAuthenticationFlowBindingOverrides(authenticationFlowBindingOverrides)
```



### fn spec.realm.oauthClients.withAuthenticationFlowBindingOverridesMixin

```ts
withAuthenticationFlowBindingOverridesMixin(authenticationFlowBindingOverrides)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.oauthClients.withAuthorizationServicesEnabled

```ts
withAuthorizationServicesEnabled(authorizationServicesEnabled)
```



### fn spec.realm.oauthClients.withBaseUrl

```ts
withBaseUrl(baseUrl)
```



### fn spec.realm.oauthClients.withBearerOnly

```ts
withBearerOnly(bearerOnly)
```



### fn spec.realm.oauthClients.withClientAuthenticatorType

```ts
withClientAuthenticatorType(clientAuthenticatorType)
```



### fn spec.realm.oauthClients.withClientId

```ts
withClientId(clientId)
```



### fn spec.realm.oauthClients.withClientTemplate

```ts
withClientTemplate(clientTemplate)
```



### fn spec.realm.oauthClients.withConsentRequired

```ts
withConsentRequired(consentRequired)
```



### fn spec.realm.oauthClients.withDefaultClientScopes

```ts
withDefaultClientScopes(defaultClientScopes)
```



### fn spec.realm.oauthClients.withDefaultClientScopesMixin

```ts
withDefaultClientScopesMixin(defaultClientScopes)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.oauthClients.withDefaultRoles

```ts
withDefaultRoles(defaultRoles)
```



### fn spec.realm.oauthClients.withDefaultRolesMixin

```ts
withDefaultRolesMixin(defaultRoles)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.oauthClients.withDescription

```ts
withDescription(description)
```



### fn spec.realm.oauthClients.withDirectAccessGrantsEnabled

```ts
withDirectAccessGrantsEnabled(directAccessGrantsEnabled)
```



### fn spec.realm.oauthClients.withDirectGrantsOnly

```ts
withDirectGrantsOnly(directGrantsOnly)
```



### fn spec.realm.oauthClients.withEnabled

```ts
withEnabled(enabled)
```



### fn spec.realm.oauthClients.withFrontchannelLogout

```ts
withFrontchannelLogout(frontchannelLogout)
```



### fn spec.realm.oauthClients.withFullScopeAllowed

```ts
withFullScopeAllowed(fullScopeAllowed)
```



### fn spec.realm.oauthClients.withId

```ts
withId(id)
```



### fn spec.realm.oauthClients.withImplicitFlowEnabled

```ts
withImplicitFlowEnabled(implicitFlowEnabled)
```



### fn spec.realm.oauthClients.withName

```ts
withName(name)
```



### fn spec.realm.oauthClients.withNodeReRegistrationTimeout

```ts
withNodeReRegistrationTimeout(nodeReRegistrationTimeout)
```



### fn spec.realm.oauthClients.withNotBefore

```ts
withNotBefore(notBefore)
```



### fn spec.realm.oauthClients.withOptionalClientScopes

```ts
withOptionalClientScopes(optionalClientScopes)
```



### fn spec.realm.oauthClients.withOptionalClientScopesMixin

```ts
withOptionalClientScopesMixin(optionalClientScopes)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.oauthClients.withOrigin

```ts
withOrigin(origin)
```



### fn spec.realm.oauthClients.withProtocol

```ts
withProtocol(protocol)
```



### fn spec.realm.oauthClients.withProtocolMappers

```ts
withProtocolMappers(protocolMappers)
```



### fn spec.realm.oauthClients.withProtocolMappersMixin

```ts
withProtocolMappersMixin(protocolMappers)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.oauthClients.withPublicClient

```ts
withPublicClient(publicClient)
```



### fn spec.realm.oauthClients.withRedirectUris

```ts
withRedirectUris(redirectUris)
```



### fn spec.realm.oauthClients.withRedirectUrisMixin

```ts
withRedirectUrisMixin(redirectUris)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.oauthClients.withRegisteredNodes

```ts
withRegisteredNodes(registeredNodes)
```



### fn spec.realm.oauthClients.withRegisteredNodesMixin

```ts
withRegisteredNodesMixin(registeredNodes)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.oauthClients.withRegistrationAccessToken

```ts
withRegistrationAccessToken(registrationAccessToken)
```



### fn spec.realm.oauthClients.withRootUrl

```ts
withRootUrl(rootUrl)
```



### fn spec.realm.oauthClients.withSecret

```ts
withSecret(secret)
```



### fn spec.realm.oauthClients.withServiceAccountsEnabled

```ts
withServiceAccountsEnabled(serviceAccountsEnabled)
```



### fn spec.realm.oauthClients.withStandardFlowEnabled

```ts
withStandardFlowEnabled(standardFlowEnabled)
```



### fn spec.realm.oauthClients.withSurrogateAuthRequired

```ts
withSurrogateAuthRequired(surrogateAuthRequired)
```



### fn spec.realm.oauthClients.withType

```ts
withType(type)
```



### fn spec.realm.oauthClients.withUseTemplateConfig

```ts
withUseTemplateConfig(useTemplateConfig)
```



### fn spec.realm.oauthClients.withUseTemplateMappers

```ts
withUseTemplateMappers(useTemplateMappers)
```



### fn spec.realm.oauthClients.withUseTemplateScope

```ts
withUseTemplateScope(useTemplateScope)
```



### fn spec.realm.oauthClients.withWebOrigins

```ts
withWebOrigins(webOrigins)
```



### fn spec.realm.oauthClients.withWebOriginsMixin

```ts
withWebOriginsMixin(webOrigins)
```



**Note:** This function appends passed data to existing values

## obj spec.realm.oauthClients.authorizationSettings



### fn spec.realm.oauthClients.authorizationSettings.withAllowRemoteResourceManagement

```ts
withAllowRemoteResourceManagement(allowRemoteResourceManagement)
```



### fn spec.realm.oauthClients.authorizationSettings.withClientId

```ts
withClientId(clientId)
```



### fn spec.realm.oauthClients.authorizationSettings.withDecisionStrategy

```ts
withDecisionStrategy(decisionStrategy)
```



### fn spec.realm.oauthClients.authorizationSettings.withId

```ts
withId(id)
```



### fn spec.realm.oauthClients.authorizationSettings.withName

```ts
withName(name)
```



### fn spec.realm.oauthClients.authorizationSettings.withPolicies

```ts
withPolicies(policies)
```



### fn spec.realm.oauthClients.authorizationSettings.withPoliciesMixin

```ts
withPoliciesMixin(policies)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.oauthClients.authorizationSettings.withPolicyEnforcementMode

```ts
withPolicyEnforcementMode(policyEnforcementMode)
```



### fn spec.realm.oauthClients.authorizationSettings.withResources

```ts
withResources(resources)
```



### fn spec.realm.oauthClients.authorizationSettings.withResourcesMixin

```ts
withResourcesMixin(resources)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.oauthClients.authorizationSettings.withScopes

```ts
withScopes(scopes)
```



### fn spec.realm.oauthClients.authorizationSettings.withScopesMixin

```ts
withScopesMixin(scopes)
```



**Note:** This function appends passed data to existing values

## obj spec.realm.oauthClients.authorizationSettings.authorizationSchema



### fn spec.realm.oauthClients.authorizationSettings.authorizationSchema.withResourceTypes

```ts
withResourceTypes(resourceTypes)
```



### fn spec.realm.oauthClients.authorizationSettings.authorizationSchema.withResourceTypesMixin

```ts
withResourceTypesMixin(resourceTypes)
```



**Note:** This function appends passed data to existing values

## obj spec.realm.oauthClients.authorizationSettings.policies



### fn spec.realm.oauthClients.authorizationSettings.policies.withConfig

```ts
withConfig(config)
```



### fn spec.realm.oauthClients.authorizationSettings.policies.withConfigMixin

```ts
withConfigMixin(config)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.oauthClients.authorizationSettings.policies.withDecisionStrategy

```ts
withDecisionStrategy(decisionStrategy)
```



### fn spec.realm.oauthClients.authorizationSettings.policies.withDescription

```ts
withDescription(description)
```



### fn spec.realm.oauthClients.authorizationSettings.policies.withId

```ts
withId(id)
```



### fn spec.realm.oauthClients.authorizationSettings.policies.withLogic

```ts
withLogic(logic)
```



### fn spec.realm.oauthClients.authorizationSettings.policies.withName

```ts
withName(name)
```



### fn spec.realm.oauthClients.authorizationSettings.policies.withOwner

```ts
withOwner(owner)
```



### fn spec.realm.oauthClients.authorizationSettings.policies.withPolicies

```ts
withPolicies(policies)
```



### fn spec.realm.oauthClients.authorizationSettings.policies.withPoliciesMixin

```ts
withPoliciesMixin(policies)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.oauthClients.authorizationSettings.policies.withResourceType

```ts
withResourceType(resourceType)
```



### fn spec.realm.oauthClients.authorizationSettings.policies.withResources

```ts
withResources(resources)
```



### fn spec.realm.oauthClients.authorizationSettings.policies.withResourcesData

```ts
withResourcesData(resourcesData)
```



### fn spec.realm.oauthClients.authorizationSettings.policies.withResourcesDataMixin

```ts
withResourcesDataMixin(resourcesData)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.oauthClients.authorizationSettings.policies.withResourcesMixin

```ts
withResourcesMixin(resources)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.oauthClients.authorizationSettings.policies.withScopes

```ts
withScopes(scopes)
```



### fn spec.realm.oauthClients.authorizationSettings.policies.withScopesData

```ts
withScopesData(scopesData)
```



### fn spec.realm.oauthClients.authorizationSettings.policies.withScopesDataMixin

```ts
withScopesDataMixin(scopesData)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.oauthClients.authorizationSettings.policies.withScopesMixin

```ts
withScopesMixin(scopes)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.oauthClients.authorizationSettings.policies.withType

```ts
withType(type)
```



## obj spec.realm.oauthClients.authorizationSettings.policies.resourcesData



### fn spec.realm.oauthClients.authorizationSettings.policies.resourcesData.withAttributes

```ts
withAttributes(attributes)
```



### fn spec.realm.oauthClients.authorizationSettings.policies.resourcesData.withAttributesMixin

```ts
withAttributesMixin(attributes)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.oauthClients.authorizationSettings.policies.resourcesData.withDisplayName

```ts
withDisplayName(displayName)
```



### fn spec.realm.oauthClients.authorizationSettings.policies.resourcesData.withIcon_uri

```ts
withIcon_uri(icon_uri)
```



### fn spec.realm.oauthClients.authorizationSettings.policies.resourcesData.withName

```ts
withName(name)
```



### fn spec.realm.oauthClients.authorizationSettings.policies.resourcesData.withOwnerManagedAccess

```ts
withOwnerManagedAccess(ownerManagedAccess)
```



### fn spec.realm.oauthClients.authorizationSettings.policies.resourcesData.withScopes

```ts
withScopes(scopes)
```



### fn spec.realm.oauthClients.authorizationSettings.policies.resourcesData.withScopesMixin

```ts
withScopesMixin(scopes)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.oauthClients.authorizationSettings.policies.resourcesData.withType

```ts
withType(type)
```



### fn spec.realm.oauthClients.authorizationSettings.policies.resourcesData.withUris

```ts
withUris(uris)
```



### fn spec.realm.oauthClients.authorizationSettings.policies.resourcesData.withUrisMixin

```ts
withUrisMixin(uris)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.oauthClients.authorizationSettings.policies.resourcesData.with_id

```ts
with_id(_id)
```



## obj spec.realm.oauthClients.authorizationSettings.policies.resourcesData.owner



### fn spec.realm.oauthClients.authorizationSettings.policies.resourcesData.owner.withId

```ts
withId(id)
```



### fn spec.realm.oauthClients.authorizationSettings.policies.resourcesData.owner.withName

```ts
withName(name)
```



## obj spec.realm.oauthClients.authorizationSettings.policies.resourcesData.scopes



### fn spec.realm.oauthClients.authorizationSettings.policies.resourcesData.scopes.withDisplayName

```ts
withDisplayName(displayName)
```



### fn spec.realm.oauthClients.authorizationSettings.policies.resourcesData.scopes.withIconUri

```ts
withIconUri(iconUri)
```



### fn spec.realm.oauthClients.authorizationSettings.policies.resourcesData.scopes.withId

```ts
withId(id)
```



### fn spec.realm.oauthClients.authorizationSettings.policies.resourcesData.scopes.withName

```ts
withName(name)
```



## obj spec.realm.oauthClients.authorizationSettings.policies.scopesData



### fn spec.realm.oauthClients.authorizationSettings.policies.scopesData.withDisplayName

```ts
withDisplayName(displayName)
```



### fn spec.realm.oauthClients.authorizationSettings.policies.scopesData.withIconUri

```ts
withIconUri(iconUri)
```



### fn spec.realm.oauthClients.authorizationSettings.policies.scopesData.withId

```ts
withId(id)
```



### fn spec.realm.oauthClients.authorizationSettings.policies.scopesData.withName

```ts
withName(name)
```



## obj spec.realm.oauthClients.authorizationSettings.resources



### fn spec.realm.oauthClients.authorizationSettings.resources.withAttributes

```ts
withAttributes(attributes)
```



### fn spec.realm.oauthClients.authorizationSettings.resources.withAttributesMixin

```ts
withAttributesMixin(attributes)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.oauthClients.authorizationSettings.resources.withDisplayName

```ts
withDisplayName(displayName)
```



### fn spec.realm.oauthClients.authorizationSettings.resources.withIcon_uri

```ts
withIcon_uri(icon_uri)
```



### fn spec.realm.oauthClients.authorizationSettings.resources.withName

```ts
withName(name)
```



### fn spec.realm.oauthClients.authorizationSettings.resources.withOwnerManagedAccess

```ts
withOwnerManagedAccess(ownerManagedAccess)
```



### fn spec.realm.oauthClients.authorizationSettings.resources.withScopes

```ts
withScopes(scopes)
```



### fn spec.realm.oauthClients.authorizationSettings.resources.withScopesMixin

```ts
withScopesMixin(scopes)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.oauthClients.authorizationSettings.resources.withType

```ts
withType(type)
```



### fn spec.realm.oauthClients.authorizationSettings.resources.withUris

```ts
withUris(uris)
```



### fn spec.realm.oauthClients.authorizationSettings.resources.withUrisMixin

```ts
withUrisMixin(uris)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.oauthClients.authorizationSettings.resources.with_id

```ts
with_id(_id)
```



## obj spec.realm.oauthClients.authorizationSettings.resources.owner



### fn spec.realm.oauthClients.authorizationSettings.resources.owner.withId

```ts
withId(id)
```



### fn spec.realm.oauthClients.authorizationSettings.resources.owner.withName

```ts
withName(name)
```



## obj spec.realm.oauthClients.authorizationSettings.resources.scopes



### fn spec.realm.oauthClients.authorizationSettings.resources.scopes.withDisplayName

```ts
withDisplayName(displayName)
```



### fn spec.realm.oauthClients.authorizationSettings.resources.scopes.withIconUri

```ts
withIconUri(iconUri)
```



### fn spec.realm.oauthClients.authorizationSettings.resources.scopes.withId

```ts
withId(id)
```



### fn spec.realm.oauthClients.authorizationSettings.resources.scopes.withName

```ts
withName(name)
```



## obj spec.realm.oauthClients.authorizationSettings.scopes



### fn spec.realm.oauthClients.authorizationSettings.scopes.withDisplayName

```ts
withDisplayName(displayName)
```



### fn spec.realm.oauthClients.authorizationSettings.scopes.withIconUri

```ts
withIconUri(iconUri)
```



### fn spec.realm.oauthClients.authorizationSettings.scopes.withId

```ts
withId(id)
```



### fn spec.realm.oauthClients.authorizationSettings.scopes.withName

```ts
withName(name)
```



## obj spec.realm.oauthClients.claims



### fn spec.realm.oauthClients.claims.withAddress

```ts
withAddress(address)
```



### fn spec.realm.oauthClients.claims.withEmail

```ts
withEmail(email)
```



### fn spec.realm.oauthClients.claims.withGender

```ts
withGender(gender)
```



### fn spec.realm.oauthClients.claims.withLocale

```ts
withLocale(locale)
```



### fn spec.realm.oauthClients.claims.withName

```ts
withName(name)
```



### fn spec.realm.oauthClients.claims.withPhone

```ts
withPhone(phone)
```



### fn spec.realm.oauthClients.claims.withPicture

```ts
withPicture(picture)
```



### fn spec.realm.oauthClients.claims.withProfile

```ts
withProfile(profile)
```



### fn spec.realm.oauthClients.claims.withUsername

```ts
withUsername(username)
```



### fn spec.realm.oauthClients.claims.withWebsite

```ts
withWebsite(website)
```



## obj spec.realm.oauthClients.protocolMappers



### fn spec.realm.oauthClients.protocolMappers.withConfig

```ts
withConfig(config)
```



### fn spec.realm.oauthClients.protocolMappers.withConfigMixin

```ts
withConfigMixin(config)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.oauthClients.protocolMappers.withConsentRequired

```ts
withConsentRequired(consentRequired)
```



### fn spec.realm.oauthClients.protocolMappers.withConsentText

```ts
withConsentText(consentText)
```



### fn spec.realm.oauthClients.protocolMappers.withId

```ts
withId(id)
```



### fn spec.realm.oauthClients.protocolMappers.withName

```ts
withName(name)
```



### fn spec.realm.oauthClients.protocolMappers.withProtocol

```ts
withProtocol(protocol)
```



### fn spec.realm.oauthClients.protocolMappers.withProtocolMapper

```ts
withProtocolMapper(protocolMapper)
```



## obj spec.realm.organizations



### fn spec.realm.organizations.withAlias

```ts
withAlias(alias)
```



### fn spec.realm.organizations.withAttributes

```ts
withAttributes(attributes)
```



### fn spec.realm.organizations.withAttributesMixin

```ts
withAttributesMixin(attributes)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.organizations.withDescription

```ts
withDescription(description)
```



### fn spec.realm.organizations.withDomains

```ts
withDomains(domains)
```



### fn spec.realm.organizations.withDomainsMixin

```ts
withDomainsMixin(domains)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.organizations.withEnabled

```ts
withEnabled(enabled)
```



### fn spec.realm.organizations.withId

```ts
withId(id)
```



### fn spec.realm.organizations.withIdentityProviders

```ts
withIdentityProviders(identityProviders)
```



### fn spec.realm.organizations.withIdentityProvidersMixin

```ts
withIdentityProvidersMixin(identityProviders)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.organizations.withMembers

```ts
withMembers(members)
```



### fn spec.realm.organizations.withMembersMixin

```ts
withMembersMixin(members)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.organizations.withName

```ts
withName(name)
```



### fn spec.realm.organizations.withRedirectUrl

```ts
withRedirectUrl(redirectUrl)
```



## obj spec.realm.organizations.domains



### fn spec.realm.organizations.domains.withName

```ts
withName(name)
```



### fn spec.realm.organizations.domains.withVerified

```ts
withVerified(verified)
```



## obj spec.realm.organizations.identityProviders



### fn spec.realm.organizations.identityProviders.withAddReadTokenRoleOnCreate

```ts
withAddReadTokenRoleOnCreate(addReadTokenRoleOnCreate)
```



### fn spec.realm.organizations.identityProviders.withAlias

```ts
withAlias(alias)
```



### fn spec.realm.organizations.identityProviders.withAuthenticateByDefault

```ts
withAuthenticateByDefault(authenticateByDefault)
```



### fn spec.realm.organizations.identityProviders.withConfig

```ts
withConfig(config)
```



### fn spec.realm.organizations.identityProviders.withConfigMixin

```ts
withConfigMixin(config)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.organizations.identityProviders.withDisplayName

```ts
withDisplayName(displayName)
```



### fn spec.realm.organizations.identityProviders.withEnabled

```ts
withEnabled(enabled)
```



### fn spec.realm.organizations.identityProviders.withFirstBrokerLoginFlowAlias

```ts
withFirstBrokerLoginFlowAlias(firstBrokerLoginFlowAlias)
```



### fn spec.realm.organizations.identityProviders.withHideOnLogin

```ts
withHideOnLogin(hideOnLogin)
```



### fn spec.realm.organizations.identityProviders.withInternalId

```ts
withInternalId(internalId)
```



### fn spec.realm.organizations.identityProviders.withLinkOnly

```ts
withLinkOnly(linkOnly)
```



### fn spec.realm.organizations.identityProviders.withOrganizationId

```ts
withOrganizationId(organizationId)
```



### fn spec.realm.organizations.identityProviders.withPostBrokerLoginFlowAlias

```ts
withPostBrokerLoginFlowAlias(postBrokerLoginFlowAlias)
```



### fn spec.realm.organizations.identityProviders.withProviderId

```ts
withProviderId(providerId)
```



### fn spec.realm.organizations.identityProviders.withStoreToken

```ts
withStoreToken(storeToken)
```



### fn spec.realm.organizations.identityProviders.withTrustEmail

```ts
withTrustEmail(trustEmail)
```



### fn spec.realm.organizations.identityProviders.withUpdateProfileFirstLoginMode

```ts
withUpdateProfileFirstLoginMode(updateProfileFirstLoginMode)
```



## obj spec.realm.organizations.members



### fn spec.realm.organizations.members.withAccess

```ts
withAccess(access)
```



### fn spec.realm.organizations.members.withAccessMixin

```ts
withAccessMixin(access)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.organizations.members.withApplicationRoles

```ts
withApplicationRoles(applicationRoles)
```



### fn spec.realm.organizations.members.withApplicationRolesMixin

```ts
withApplicationRolesMixin(applicationRoles)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.organizations.members.withAttributes

```ts
withAttributes(attributes)
```



### fn spec.realm.organizations.members.withAttributesMixin

```ts
withAttributesMixin(attributes)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.organizations.members.withClientConsents

```ts
withClientConsents(clientConsents)
```



### fn spec.realm.organizations.members.withClientConsentsMixin

```ts
withClientConsentsMixin(clientConsents)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.organizations.members.withClientRoles

```ts
withClientRoles(clientRoles)
```



### fn spec.realm.organizations.members.withClientRolesMixin

```ts
withClientRolesMixin(clientRoles)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.organizations.members.withCreatedTimestamp

```ts
withCreatedTimestamp(createdTimestamp)
```



### fn spec.realm.organizations.members.withCredentials

```ts
withCredentials(credentials)
```



### fn spec.realm.organizations.members.withCredentialsMixin

```ts
withCredentialsMixin(credentials)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.organizations.members.withDisableableCredentialTypes

```ts
withDisableableCredentialTypes(disableableCredentialTypes)
```



### fn spec.realm.organizations.members.withDisableableCredentialTypesMixin

```ts
withDisableableCredentialTypesMixin(disableableCredentialTypes)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.organizations.members.withEmail

```ts
withEmail(email)
```



### fn spec.realm.organizations.members.withEmailVerified

```ts
withEmailVerified(emailVerified)
```



### fn spec.realm.organizations.members.withEnabled

```ts
withEnabled(enabled)
```



### fn spec.realm.organizations.members.withFederatedIdentities

```ts
withFederatedIdentities(federatedIdentities)
```



### fn spec.realm.organizations.members.withFederatedIdentitiesMixin

```ts
withFederatedIdentitiesMixin(federatedIdentities)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.organizations.members.withFederationLink

```ts
withFederationLink(federationLink)
```



### fn spec.realm.organizations.members.withFirstName

```ts
withFirstName(firstName)
```



### fn spec.realm.organizations.members.withGroups

```ts
withGroups(groups)
```



### fn spec.realm.organizations.members.withGroupsMixin

```ts
withGroupsMixin(groups)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.organizations.members.withId

```ts
withId(id)
```



### fn spec.realm.organizations.members.withLastName

```ts
withLastName(lastName)
```



### fn spec.realm.organizations.members.withMembershipType

```ts
withMembershipType(membershipType)
```



### fn spec.realm.organizations.members.withNotBefore

```ts
withNotBefore(notBefore)
```



### fn spec.realm.organizations.members.withOrigin

```ts
withOrigin(origin)
```



### fn spec.realm.organizations.members.withRealmRoles

```ts
withRealmRoles(realmRoles)
```



### fn spec.realm.organizations.members.withRealmRolesMixin

```ts
withRealmRolesMixin(realmRoles)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.organizations.members.withRequiredActions

```ts
withRequiredActions(requiredActions)
```



### fn spec.realm.organizations.members.withRequiredActionsMixin

```ts
withRequiredActionsMixin(requiredActions)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.organizations.members.withSelf

```ts
withSelf(Self)
```



### fn spec.realm.organizations.members.withServiceAccountClientId

```ts
withServiceAccountClientId(serviceAccountClientId)
```



### fn spec.realm.organizations.members.withSocialLinks

```ts
withSocialLinks(socialLinks)
```



### fn spec.realm.organizations.members.withSocialLinksMixin

```ts
withSocialLinksMixin(socialLinks)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.organizations.members.withTotp

```ts
withTotp(totp)
```



### fn spec.realm.organizations.members.withUsername

```ts
withUsername(username)
```



## obj spec.realm.organizations.members.clientConsents



### fn spec.realm.organizations.members.clientConsents.withClientId

```ts
withClientId(clientId)
```



### fn spec.realm.organizations.members.clientConsents.withCreatedDate

```ts
withCreatedDate(createdDate)
```



### fn spec.realm.organizations.members.clientConsents.withGrantedClientScopes

```ts
withGrantedClientScopes(grantedClientScopes)
```



### fn spec.realm.organizations.members.clientConsents.withGrantedClientScopesMixin

```ts
withGrantedClientScopesMixin(grantedClientScopes)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.organizations.members.clientConsents.withGrantedRealmRoles

```ts
withGrantedRealmRoles(grantedRealmRoles)
```



### fn spec.realm.organizations.members.clientConsents.withGrantedRealmRolesMixin

```ts
withGrantedRealmRolesMixin(grantedRealmRoles)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.organizations.members.clientConsents.withLastUpdatedDate

```ts
withLastUpdatedDate(lastUpdatedDate)
```



## obj spec.realm.organizations.members.credentials



### fn spec.realm.organizations.members.credentials.withAlgorithm

```ts
withAlgorithm(algorithm)
```



### fn spec.realm.organizations.members.credentials.withConfig

```ts
withConfig(config)
```



### fn spec.realm.organizations.members.credentials.withConfigMixin

```ts
withConfigMixin(config)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.organizations.members.credentials.withCounter

```ts
withCounter(counter)
```



### fn spec.realm.organizations.members.credentials.withCreatedDate

```ts
withCreatedDate(createdDate)
```



### fn spec.realm.organizations.members.credentials.withCredentialData

```ts
withCredentialData(credentialData)
```



### fn spec.realm.organizations.members.credentials.withDevice

```ts
withDevice(device)
```



### fn spec.realm.organizations.members.credentials.withDigits

```ts
withDigits(digits)
```



### fn spec.realm.organizations.members.credentials.withFederationLink

```ts
withFederationLink(federationLink)
```



### fn spec.realm.organizations.members.credentials.withHashIterations

```ts
withHashIterations(hashIterations)
```



### fn spec.realm.organizations.members.credentials.withHashedSaltedValue

```ts
withHashedSaltedValue(hashedSaltedValue)
```



### fn spec.realm.organizations.members.credentials.withId

```ts
withId(id)
```



### fn spec.realm.organizations.members.credentials.withPeriod

```ts
withPeriod(period)
```



### fn spec.realm.organizations.members.credentials.withPriority

```ts
withPriority(priority)
```



### fn spec.realm.organizations.members.credentials.withSalt

```ts
withSalt(salt)
```



### fn spec.realm.organizations.members.credentials.withSecretData

```ts
withSecretData(secretData)
```



### fn spec.realm.organizations.members.credentials.withTemporary

```ts
withTemporary(temporary)
```



### fn spec.realm.organizations.members.credentials.withType

```ts
withType(type)
```



### fn spec.realm.organizations.members.credentials.withUserLabel

```ts
withUserLabel(userLabel)
```



### fn spec.realm.organizations.members.credentials.withValue

```ts
withValue(value)
```



## obj spec.realm.organizations.members.federatedIdentities



### fn spec.realm.organizations.members.federatedIdentities.withIdentityProvider

```ts
withIdentityProvider(identityProvider)
```



### fn spec.realm.organizations.members.federatedIdentities.withUserId

```ts
withUserId(userId)
```



### fn spec.realm.organizations.members.federatedIdentities.withUserName

```ts
withUserName(userName)
```



## obj spec.realm.organizations.members.socialLinks



### fn spec.realm.organizations.members.socialLinks.withSocialProvider

```ts
withSocialProvider(socialProvider)
```



### fn spec.realm.organizations.members.socialLinks.withSocialUserId

```ts
withSocialUserId(socialUserId)
```



### fn spec.realm.organizations.members.socialLinks.withSocialUsername

```ts
withSocialUsername(socialUsername)
```



## obj spec.realm.organizations.members.userProfileMetadata



### fn spec.realm.organizations.members.userProfileMetadata.withAttributes

```ts
withAttributes(attributes)
```



### fn spec.realm.organizations.members.userProfileMetadata.withAttributesMixin

```ts
withAttributesMixin(attributes)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.organizations.members.userProfileMetadata.withGroups

```ts
withGroups(groups)
```



### fn spec.realm.organizations.members.userProfileMetadata.withGroupsMixin

```ts
withGroupsMixin(groups)
```



**Note:** This function appends passed data to existing values

## obj spec.realm.organizations.members.userProfileMetadata.attributes



### fn spec.realm.organizations.members.userProfileMetadata.attributes.withAnnotations

```ts
withAnnotations(annotations)
```



### fn spec.realm.organizations.members.userProfileMetadata.attributes.withAnnotationsMixin

```ts
withAnnotationsMixin(annotations)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.organizations.members.userProfileMetadata.attributes.withDefaultValue

```ts
withDefaultValue(defaultValue)
```



### fn spec.realm.organizations.members.userProfileMetadata.attributes.withDisplayName

```ts
withDisplayName(displayName)
```



### fn spec.realm.organizations.members.userProfileMetadata.attributes.withGroup

```ts
withGroup(group)
```



### fn spec.realm.organizations.members.userProfileMetadata.attributes.withMultivalued

```ts
withMultivalued(multivalued)
```



### fn spec.realm.organizations.members.userProfileMetadata.attributes.withName

```ts
withName(name)
```



### fn spec.realm.organizations.members.userProfileMetadata.attributes.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.realm.organizations.members.userProfileMetadata.attributes.withRequired

```ts
withRequired(required)
```



### fn spec.realm.organizations.members.userProfileMetadata.attributes.withValidators

```ts
withValidators(validators)
```



### fn spec.realm.organizations.members.userProfileMetadata.attributes.withValidatorsMixin

```ts
withValidatorsMixin(validators)
```



**Note:** This function appends passed data to existing values

## obj spec.realm.organizations.members.userProfileMetadata.groups



### fn spec.realm.organizations.members.userProfileMetadata.groups.withAnnotations

```ts
withAnnotations(annotations)
```



### fn spec.realm.organizations.members.userProfileMetadata.groups.withAnnotationsMixin

```ts
withAnnotationsMixin(annotations)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.organizations.members.userProfileMetadata.groups.withDisplayDescription

```ts
withDisplayDescription(displayDescription)
```



### fn spec.realm.organizations.members.userProfileMetadata.groups.withDisplayHeader

```ts
withDisplayHeader(displayHeader)
```



### fn spec.realm.organizations.members.userProfileMetadata.groups.withName

```ts
withName(name)
```



## obj spec.realm.protocolMappers



### fn spec.realm.protocolMappers.withConfig

```ts
withConfig(config)
```



### fn spec.realm.protocolMappers.withConfigMixin

```ts
withConfigMixin(config)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.protocolMappers.withConsentRequired

```ts
withConsentRequired(consentRequired)
```



### fn spec.realm.protocolMappers.withConsentText

```ts
withConsentText(consentText)
```



### fn spec.realm.protocolMappers.withId

```ts
withId(id)
```



### fn spec.realm.protocolMappers.withName

```ts
withName(name)
```



### fn spec.realm.protocolMappers.withProtocol

```ts
withProtocol(protocol)
```



### fn spec.realm.protocolMappers.withProtocolMapper

```ts
withProtocolMapper(protocolMapper)
```



## obj spec.realm.requiredActions



### fn spec.realm.requiredActions.withAlias

```ts
withAlias(alias)
```



### fn spec.realm.requiredActions.withConfig

```ts
withConfig(config)
```



### fn spec.realm.requiredActions.withConfigMixin

```ts
withConfigMixin(config)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.requiredActions.withDefaultAction

```ts
withDefaultAction(defaultAction)
```



### fn spec.realm.requiredActions.withEnabled

```ts
withEnabled(enabled)
```



### fn spec.realm.requiredActions.withName

```ts
withName(name)
```



### fn spec.realm.requiredActions.withPriority

```ts
withPriority(priority)
```



### fn spec.realm.requiredActions.withProviderId

```ts
withProviderId(providerId)
```



## obj spec.realm.roles



### fn spec.realm.roles.withApplication

```ts
withApplication(application)
```



### fn spec.realm.roles.withApplicationMixin

```ts
withApplicationMixin(application)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.roles.withClient

```ts
withClient(client)
```



### fn spec.realm.roles.withClientMixin

```ts
withClientMixin(client)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.roles.withRealm

```ts
withRealm(realm)
```



### fn spec.realm.roles.withRealmMixin

```ts
withRealmMixin(realm)
```



**Note:** This function appends passed data to existing values

## obj spec.realm.roles.realm



### fn spec.realm.roles.realm.withAttributes

```ts
withAttributes(attributes)
```



### fn spec.realm.roles.realm.withAttributesMixin

```ts
withAttributesMixin(attributes)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.roles.realm.withClientRole

```ts
withClientRole(clientRole)
```



### fn spec.realm.roles.realm.withComposite

```ts
withComposite(composite)
```



### fn spec.realm.roles.realm.withContainerId

```ts
withContainerId(containerId)
```



### fn spec.realm.roles.realm.withDescription

```ts
withDescription(description)
```



### fn spec.realm.roles.realm.withId

```ts
withId(id)
```



### fn spec.realm.roles.realm.withName

```ts
withName(name)
```



### fn spec.realm.roles.realm.withScopeParamRequired

```ts
withScopeParamRequired(scopeParamRequired)
```



## obj spec.realm.roles.realm.composites



### fn spec.realm.roles.realm.composites.withApplication

```ts
withApplication(application)
```



### fn spec.realm.roles.realm.composites.withApplicationMixin

```ts
withApplicationMixin(application)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.roles.realm.composites.withClient

```ts
withClient(client)
```



### fn spec.realm.roles.realm.composites.withClientMixin

```ts
withClientMixin(client)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.roles.realm.composites.withRealm

```ts
withRealm(realm)
```



### fn spec.realm.roles.realm.composites.withRealmMixin

```ts
withRealmMixin(realm)
```



**Note:** This function appends passed data to existing values

## obj spec.realm.scopeMappings



### fn spec.realm.scopeMappings.withClient

```ts
withClient(client)
```



### fn spec.realm.scopeMappings.withClientScope

```ts
withClientScope(clientScope)
```



### fn spec.realm.scopeMappings.withClientTemplate

```ts
withClientTemplate(clientTemplate)
```



### fn spec.realm.scopeMappings.withRoles

```ts
withRoles(roles)
```



### fn spec.realm.scopeMappings.withRolesMixin

```ts
withRolesMixin(roles)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.scopeMappings.withSelf

```ts
withSelf(Self)
```



## obj spec.realm.userFederationMappers



### fn spec.realm.userFederationMappers.withConfig

```ts
withConfig(config)
```



### fn spec.realm.userFederationMappers.withConfigMixin

```ts
withConfigMixin(config)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.userFederationMappers.withFederationMapperType

```ts
withFederationMapperType(federationMapperType)
```



### fn spec.realm.userFederationMappers.withFederationProviderDisplayName

```ts
withFederationProviderDisplayName(federationProviderDisplayName)
```



### fn spec.realm.userFederationMappers.withId

```ts
withId(id)
```



### fn spec.realm.userFederationMappers.withName

```ts
withName(name)
```



## obj spec.realm.userFederationProviders



### fn spec.realm.userFederationProviders.withChangedSyncPeriod

```ts
withChangedSyncPeriod(changedSyncPeriod)
```



### fn spec.realm.userFederationProviders.withConfig

```ts
withConfig(config)
```



### fn spec.realm.userFederationProviders.withConfigMixin

```ts
withConfigMixin(config)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.userFederationProviders.withDisplayName

```ts
withDisplayName(displayName)
```



### fn spec.realm.userFederationProviders.withFullSyncPeriod

```ts
withFullSyncPeriod(fullSyncPeriod)
```



### fn spec.realm.userFederationProviders.withId

```ts
withId(id)
```



### fn spec.realm.userFederationProviders.withLastSync

```ts
withLastSync(lastSync)
```



### fn spec.realm.userFederationProviders.withPriority

```ts
withPriority(priority)
```



### fn spec.realm.userFederationProviders.withProviderName

```ts
withProviderName(providerName)
```



## obj spec.realm.users



### fn spec.realm.users.withAccess

```ts
withAccess(access)
```



### fn spec.realm.users.withAccessMixin

```ts
withAccessMixin(access)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.users.withApplicationRoles

```ts
withApplicationRoles(applicationRoles)
```



### fn spec.realm.users.withApplicationRolesMixin

```ts
withApplicationRolesMixin(applicationRoles)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.users.withAttributes

```ts
withAttributes(attributes)
```



### fn spec.realm.users.withAttributesMixin

```ts
withAttributesMixin(attributes)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.users.withClientConsents

```ts
withClientConsents(clientConsents)
```



### fn spec.realm.users.withClientConsentsMixin

```ts
withClientConsentsMixin(clientConsents)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.users.withClientRoles

```ts
withClientRoles(clientRoles)
```



### fn spec.realm.users.withClientRolesMixin

```ts
withClientRolesMixin(clientRoles)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.users.withCreatedTimestamp

```ts
withCreatedTimestamp(createdTimestamp)
```



### fn spec.realm.users.withCredentials

```ts
withCredentials(credentials)
```



### fn spec.realm.users.withCredentialsMixin

```ts
withCredentialsMixin(credentials)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.users.withDisableableCredentialTypes

```ts
withDisableableCredentialTypes(disableableCredentialTypes)
```



### fn spec.realm.users.withDisableableCredentialTypesMixin

```ts
withDisableableCredentialTypesMixin(disableableCredentialTypes)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.users.withEmail

```ts
withEmail(email)
```



### fn spec.realm.users.withEmailVerified

```ts
withEmailVerified(emailVerified)
```



### fn spec.realm.users.withEnabled

```ts
withEnabled(enabled)
```



### fn spec.realm.users.withFederatedIdentities

```ts
withFederatedIdentities(federatedIdentities)
```



### fn spec.realm.users.withFederatedIdentitiesMixin

```ts
withFederatedIdentitiesMixin(federatedIdentities)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.users.withFederationLink

```ts
withFederationLink(federationLink)
```



### fn spec.realm.users.withFirstName

```ts
withFirstName(firstName)
```



### fn spec.realm.users.withGroups

```ts
withGroups(groups)
```



### fn spec.realm.users.withGroupsMixin

```ts
withGroupsMixin(groups)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.users.withId

```ts
withId(id)
```



### fn spec.realm.users.withLastName

```ts
withLastName(lastName)
```



### fn spec.realm.users.withNotBefore

```ts
withNotBefore(notBefore)
```



### fn spec.realm.users.withOrigin

```ts
withOrigin(origin)
```



### fn spec.realm.users.withRealmRoles

```ts
withRealmRoles(realmRoles)
```



### fn spec.realm.users.withRealmRolesMixin

```ts
withRealmRolesMixin(realmRoles)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.users.withRequiredActions

```ts
withRequiredActions(requiredActions)
```



### fn spec.realm.users.withRequiredActionsMixin

```ts
withRequiredActionsMixin(requiredActions)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.users.withSelf

```ts
withSelf(Self)
```



### fn spec.realm.users.withServiceAccountClientId

```ts
withServiceAccountClientId(serviceAccountClientId)
```



### fn spec.realm.users.withSocialLinks

```ts
withSocialLinks(socialLinks)
```



### fn spec.realm.users.withSocialLinksMixin

```ts
withSocialLinksMixin(socialLinks)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.users.withTotp

```ts
withTotp(totp)
```



### fn spec.realm.users.withUsername

```ts
withUsername(username)
```



## obj spec.realm.users.clientConsents



### fn spec.realm.users.clientConsents.withClientId

```ts
withClientId(clientId)
```



### fn spec.realm.users.clientConsents.withCreatedDate

```ts
withCreatedDate(createdDate)
```



### fn spec.realm.users.clientConsents.withGrantedClientScopes

```ts
withGrantedClientScopes(grantedClientScopes)
```



### fn spec.realm.users.clientConsents.withGrantedClientScopesMixin

```ts
withGrantedClientScopesMixin(grantedClientScopes)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.users.clientConsents.withGrantedRealmRoles

```ts
withGrantedRealmRoles(grantedRealmRoles)
```



### fn spec.realm.users.clientConsents.withGrantedRealmRolesMixin

```ts
withGrantedRealmRolesMixin(grantedRealmRoles)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.users.clientConsents.withLastUpdatedDate

```ts
withLastUpdatedDate(lastUpdatedDate)
```



## obj spec.realm.users.credentials



### fn spec.realm.users.credentials.withAlgorithm

```ts
withAlgorithm(algorithm)
```



### fn spec.realm.users.credentials.withConfig

```ts
withConfig(config)
```



### fn spec.realm.users.credentials.withConfigMixin

```ts
withConfigMixin(config)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.users.credentials.withCounter

```ts
withCounter(counter)
```



### fn spec.realm.users.credentials.withCreatedDate

```ts
withCreatedDate(createdDate)
```



### fn spec.realm.users.credentials.withCredentialData

```ts
withCredentialData(credentialData)
```



### fn spec.realm.users.credentials.withDevice

```ts
withDevice(device)
```



### fn spec.realm.users.credentials.withDigits

```ts
withDigits(digits)
```



### fn spec.realm.users.credentials.withFederationLink

```ts
withFederationLink(federationLink)
```



### fn spec.realm.users.credentials.withHashIterations

```ts
withHashIterations(hashIterations)
```



### fn spec.realm.users.credentials.withHashedSaltedValue

```ts
withHashedSaltedValue(hashedSaltedValue)
```



### fn spec.realm.users.credentials.withId

```ts
withId(id)
```



### fn spec.realm.users.credentials.withPeriod

```ts
withPeriod(period)
```



### fn spec.realm.users.credentials.withPriority

```ts
withPriority(priority)
```



### fn spec.realm.users.credentials.withSalt

```ts
withSalt(salt)
```



### fn spec.realm.users.credentials.withSecretData

```ts
withSecretData(secretData)
```



### fn spec.realm.users.credentials.withTemporary

```ts
withTemporary(temporary)
```



### fn spec.realm.users.credentials.withType

```ts
withType(type)
```



### fn spec.realm.users.credentials.withUserLabel

```ts
withUserLabel(userLabel)
```



### fn spec.realm.users.credentials.withValue

```ts
withValue(value)
```



## obj spec.realm.users.federatedIdentities



### fn spec.realm.users.federatedIdentities.withIdentityProvider

```ts
withIdentityProvider(identityProvider)
```



### fn spec.realm.users.federatedIdentities.withUserId

```ts
withUserId(userId)
```



### fn spec.realm.users.federatedIdentities.withUserName

```ts
withUserName(userName)
```



## obj spec.realm.users.socialLinks



### fn spec.realm.users.socialLinks.withSocialProvider

```ts
withSocialProvider(socialProvider)
```



### fn spec.realm.users.socialLinks.withSocialUserId

```ts
withSocialUserId(socialUserId)
```



### fn spec.realm.users.socialLinks.withSocialUsername

```ts
withSocialUsername(socialUsername)
```



## obj spec.realm.users.userProfileMetadata



### fn spec.realm.users.userProfileMetadata.withAttributes

```ts
withAttributes(attributes)
```



### fn spec.realm.users.userProfileMetadata.withAttributesMixin

```ts
withAttributesMixin(attributes)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.users.userProfileMetadata.withGroups

```ts
withGroups(groups)
```



### fn spec.realm.users.userProfileMetadata.withGroupsMixin

```ts
withGroupsMixin(groups)
```



**Note:** This function appends passed data to existing values

## obj spec.realm.users.userProfileMetadata.attributes



### fn spec.realm.users.userProfileMetadata.attributes.withAnnotations

```ts
withAnnotations(annotations)
```



### fn spec.realm.users.userProfileMetadata.attributes.withAnnotationsMixin

```ts
withAnnotationsMixin(annotations)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.users.userProfileMetadata.attributes.withDefaultValue

```ts
withDefaultValue(defaultValue)
```



### fn spec.realm.users.userProfileMetadata.attributes.withDisplayName

```ts
withDisplayName(displayName)
```



### fn spec.realm.users.userProfileMetadata.attributes.withGroup

```ts
withGroup(group)
```



### fn spec.realm.users.userProfileMetadata.attributes.withMultivalued

```ts
withMultivalued(multivalued)
```



### fn spec.realm.users.userProfileMetadata.attributes.withName

```ts
withName(name)
```



### fn spec.realm.users.userProfileMetadata.attributes.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.realm.users.userProfileMetadata.attributes.withRequired

```ts
withRequired(required)
```



### fn spec.realm.users.userProfileMetadata.attributes.withValidators

```ts
withValidators(validators)
```



### fn spec.realm.users.userProfileMetadata.attributes.withValidatorsMixin

```ts
withValidatorsMixin(validators)
```



**Note:** This function appends passed data to existing values

## obj spec.realm.users.userProfileMetadata.groups



### fn spec.realm.users.userProfileMetadata.groups.withAnnotations

```ts
withAnnotations(annotations)
```



### fn spec.realm.users.userProfileMetadata.groups.withAnnotationsMixin

```ts
withAnnotationsMixin(annotations)
```



**Note:** This function appends passed data to existing values

### fn spec.realm.users.userProfileMetadata.groups.withDisplayDescription

```ts
withDisplayDescription(displayDescription)
```



### fn spec.realm.users.userProfileMetadata.groups.withDisplayHeader

```ts
withDisplayHeader(displayHeader)
```



### fn spec.realm.users.userProfileMetadata.groups.withName

```ts
withName(name)
```



## obj spec.resources

"Compute Resources required by Keycloak container. If not specified, the value is inherited from the Keycloak CR."

### fn spec.resources.withClaims

```ts
withClaims(claims)
```



### fn spec.resources.withClaimsMixin

```ts
withClaimsMixin(claims)
```



**Note:** This function appends passed data to existing values

### fn spec.resources.withLimits

```ts
withLimits(limits)
```



### fn spec.resources.withLimitsMixin

```ts
withLimitsMixin(limits)
```



**Note:** This function appends passed data to existing values

### fn spec.resources.withRequests

```ts
withRequests(requests)
```



### fn spec.resources.withRequestsMixin

```ts
withRequestsMixin(requests)
```



**Note:** This function appends passed data to existing values

## obj spec.resources.claims



### fn spec.resources.claims.withName

```ts
withName(name)
```



### fn spec.resources.claims.withRequest

```ts
withRequest(request)
```

