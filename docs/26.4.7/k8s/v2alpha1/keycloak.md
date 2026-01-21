---
permalink: /26.4.7/k8s/v2alpha1/keycloak/
---

# k8s.v2alpha1.keycloak



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
  * [`fn withAdditionalOptions(additionalOptions)`](#fn-specwithadditionaloptions)
  * [`fn withAdditionalOptionsMixin(additionalOptions)`](#fn-specwithadditionaloptionsmixin)
  * [`fn withEnv(env)`](#fn-specwithenv)
  * [`fn withEnvMixin(env)`](#fn-specwithenvmixin)
  * [`fn withImage(image)`](#fn-specwithimage)
  * [`fn withImagePullSecrets(imagePullSecrets)`](#fn-specwithimagepullsecrets)
  * [`fn withImagePullSecretsMixin(imagePullSecrets)`](#fn-specwithimagepullsecretsmixin)
  * [`fn withInstances(instances)`](#fn-specwithinstances)
  * [`fn withStartOptimized(startOptimized)`](#fn-specwithstartoptimized)
  * [`fn withTruststores(truststores)`](#fn-specwithtruststores)
  * [`fn withTruststoresMixin(truststores)`](#fn-specwithtruststoresmixin)
  * [`obj spec.additionalOptions`](#obj-specadditionaloptions)
    * [`fn withName(name)`](#fn-specadditionaloptionswithname)
    * [`fn withValue(value)`](#fn-specadditionaloptionswithvalue)
    * [`obj spec.additionalOptions.secret`](#obj-specadditionaloptionssecret)
      * [`fn withKey(key)`](#fn-specadditionaloptionssecretwithkey)
      * [`fn withName(name)`](#fn-specadditionaloptionssecretwithname)
      * [`fn withOptional(optional)`](#fn-specadditionaloptionssecretwithoptional)
  * [`obj spec.bootstrapAdmin`](#obj-specbootstrapadmin)
    * [`obj spec.bootstrapAdmin.service`](#obj-specbootstrapadminservice)
      * [`fn withSecret(secret)`](#fn-specbootstrapadminservicewithsecret)
    * [`obj spec.bootstrapAdmin.user`](#obj-specbootstrapadminuser)
      * [`fn withSecret(secret)`](#fn-specbootstrapadminuserwithsecret)
  * [`obj spec.cache`](#obj-speccache)
    * [`obj spec.cache.configMapFile`](#obj-speccacheconfigmapfile)
      * [`fn withKey(key)`](#fn-speccacheconfigmapfilewithkey)
      * [`fn withName(name)`](#fn-speccacheconfigmapfilewithname)
      * [`fn withOptional(optional)`](#fn-speccacheconfigmapfilewithoptional)
  * [`obj spec.db`](#obj-specdb)
    * [`fn withDatabase(database)`](#fn-specdbwithdatabase)
    * [`fn withHost(host)`](#fn-specdbwithhost)
    * [`fn withPoolInitialSize(poolInitialSize)`](#fn-specdbwithpoolinitialsize)
    * [`fn withPoolMaxSize(poolMaxSize)`](#fn-specdbwithpoolmaxsize)
    * [`fn withPoolMinSize(poolMinSize)`](#fn-specdbwithpoolminsize)
    * [`fn withPort(port)`](#fn-specdbwithport)
    * [`fn withSchema(schema)`](#fn-specdbwithschema)
    * [`fn withUrl(url)`](#fn-specdbwithurl)
    * [`fn withVendor(vendor)`](#fn-specdbwithvendor)
    * [`obj spec.db.passwordSecret`](#obj-specdbpasswordsecret)
      * [`fn withKey(key)`](#fn-specdbpasswordsecretwithkey)
      * [`fn withName(name)`](#fn-specdbpasswordsecretwithname)
      * [`fn withOptional(optional)`](#fn-specdbpasswordsecretwithoptional)
    * [`obj spec.db.usernameSecret`](#obj-specdbusernamesecret)
      * [`fn withKey(key)`](#fn-specdbusernamesecretwithkey)
      * [`fn withName(name)`](#fn-specdbusernamesecretwithname)
      * [`fn withOptional(optional)`](#fn-specdbusernamesecretwithoptional)
  * [`obj spec.env`](#obj-specenv)
    * [`fn withName(name)`](#fn-specenvwithname)
    * [`fn withValue(value)`](#fn-specenvwithvalue)
    * [`obj spec.env.secret`](#obj-specenvsecret)
      * [`fn withKey(key)`](#fn-specenvsecretwithkey)
      * [`fn withName(name)`](#fn-specenvsecretwithname)
      * [`fn withOptional(optional)`](#fn-specenvsecretwithoptional)
  * [`obj spec.features`](#obj-specfeatures)
    * [`fn withDisabled(disabled)`](#fn-specfeatureswithdisabled)
    * [`fn withDisabledMixin(disabled)`](#fn-specfeatureswithdisabledmixin)
    * [`fn withEnabled(enabled)`](#fn-specfeatureswithenabled)
    * [`fn withEnabledMixin(enabled)`](#fn-specfeatureswithenabledmixin)
  * [`obj spec.hostname`](#obj-spechostname)
    * [`fn withAdmin(admin)`](#fn-spechostnamewithadmin)
    * [`fn withAdminUrl(adminUrl)`](#fn-spechostnamewithadminurl)
    * [`fn withBackchannelDynamic(backchannelDynamic)`](#fn-spechostnamewithbackchanneldynamic)
    * [`fn withHostname(hostname)`](#fn-spechostnamewithhostname)
    * [`fn withStrict(strict)`](#fn-spechostnamewithstrict)
    * [`fn withStrictBackchannel(strictBackchannel)`](#fn-spechostnamewithstrictbackchannel)
  * [`obj spec.http`](#obj-spechttp)
    * [`fn withAnnotations(annotations)`](#fn-spechttpwithannotations)
    * [`fn withAnnotationsMixin(annotations)`](#fn-spechttpwithannotationsmixin)
    * [`fn withHttpEnabled(httpEnabled)`](#fn-spechttpwithhttpenabled)
    * [`fn withHttpPort(httpPort)`](#fn-spechttpwithhttpport)
    * [`fn withHttpsPort(httpsPort)`](#fn-spechttpwithhttpsport)
    * [`fn withLabels(labels)`](#fn-spechttpwithlabels)
    * [`fn withLabelsMixin(labels)`](#fn-spechttpwithlabelsmixin)
    * [`fn withTlsSecret(tlsSecret)`](#fn-spechttpwithtlssecret)
  * [`obj spec.httpManagement`](#obj-spechttpmanagement)
    * [`fn withPort(port)`](#fn-spechttpmanagementwithport)
  * [`obj spec.imagePullSecrets`](#obj-specimagepullsecrets)
    * [`fn withName(name)`](#fn-specimagepullsecretswithname)
  * [`obj spec.import`](#obj-specimport)
    * [`obj spec.import.scheduling`](#obj-specimportscheduling)
      * [`fn withPriorityClassName(priorityClassName)`](#fn-specimportschedulingwithpriorityclassname)
      * [`fn withTolerations(tolerations)`](#fn-specimportschedulingwithtolerations)
      * [`fn withTolerationsMixin(tolerations)`](#fn-specimportschedulingwithtolerationsmixin)
      * [`fn withTopologySpreadConstraints(topologySpreadConstraints)`](#fn-specimportschedulingwithtopologyspreadconstraints)
      * [`fn withTopologySpreadConstraintsMixin(topologySpreadConstraints)`](#fn-specimportschedulingwithtopologyspreadconstraintsmixin)
      * [`obj spec.import.scheduling.affinity`](#obj-specimportschedulingaffinity)
        * [`obj spec.import.scheduling.affinity.nodeAffinity`](#obj-specimportschedulingaffinitynodeaffinity)
          * [`fn withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-specimportschedulingaffinitynodeaffinitywithpreferredduringschedulingignoredduringexecution)
          * [`fn withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-specimportschedulingaffinitynodeaffinitywithpreferredduringschedulingignoredduringexecutionmixin)
          * [`obj spec.import.scheduling.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution`](#obj-specimportschedulingaffinitynodeaffinitypreferredduringschedulingignoredduringexecution)
            * [`fn withWeight(weight)`](#fn-specimportschedulingaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionwithweight)
            * [`obj spec.import.scheduling.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference`](#obj-specimportschedulingaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreference)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-specimportschedulingaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencewithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specimportschedulingaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencewithmatchexpressionsmixin)
              * [`fn withMatchFields(matchFields)`](#fn-specimportschedulingaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencewithmatchfields)
              * [`fn withMatchFieldsMixin(matchFields)`](#fn-specimportschedulingaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencewithmatchfieldsmixin)
              * [`obj spec.import.scheduling.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions`](#obj-specimportschedulingaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressions)
                * [`fn withKey(key)`](#fn-specimportschedulingaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-specimportschedulingaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-specimportschedulingaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-specimportschedulingaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressionswithvaluesmixin)
              * [`obj spec.import.scheduling.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields`](#obj-specimportschedulingaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfields)
                * [`fn withKey(key)`](#fn-specimportschedulingaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfieldswithkey)
                * [`fn withOperator(operator)`](#fn-specimportschedulingaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfieldswithoperator)
                * [`fn withValues(values)`](#fn-specimportschedulingaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfieldswithvalues)
                * [`fn withValuesMixin(values)`](#fn-specimportschedulingaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfieldswithvaluesmixin)
          * [`obj spec.import.scheduling.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution`](#obj-specimportschedulingaffinitynodeaffinityrequiredduringschedulingignoredduringexecution)
            * [`fn withNodeSelectorTerms(nodeSelectorTerms)`](#fn-specimportschedulingaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionwithnodeselectorterms)
            * [`fn withNodeSelectorTermsMixin(nodeSelectorTerms)`](#fn-specimportschedulingaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionwithnodeselectortermsmixin)
            * [`obj spec.import.scheduling.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms`](#obj-specimportschedulingaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectorterms)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-specimportschedulingaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermswithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specimportschedulingaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermswithmatchexpressionsmixin)
              * [`fn withMatchFields(matchFields)`](#fn-specimportschedulingaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermswithmatchfields)
              * [`fn withMatchFieldsMixin(matchFields)`](#fn-specimportschedulingaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermswithmatchfieldsmixin)
              * [`obj spec.import.scheduling.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions`](#obj-specimportschedulingaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressions)
                * [`fn withKey(key)`](#fn-specimportschedulingaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-specimportschedulingaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-specimportschedulingaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-specimportschedulingaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressionswithvaluesmixin)
              * [`obj spec.import.scheduling.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields`](#obj-specimportschedulingaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfields)
                * [`fn withKey(key)`](#fn-specimportschedulingaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfieldswithkey)
                * [`fn withOperator(operator)`](#fn-specimportschedulingaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfieldswithoperator)
                * [`fn withValues(values)`](#fn-specimportschedulingaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfieldswithvalues)
                * [`fn withValuesMixin(values)`](#fn-specimportschedulingaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfieldswithvaluesmixin)
        * [`obj spec.import.scheduling.affinity.podAffinity`](#obj-specimportschedulingaffinitypodaffinity)
          * [`fn withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-specimportschedulingaffinitypodaffinitywithpreferredduringschedulingignoredduringexecution)
          * [`fn withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-specimportschedulingaffinitypodaffinitywithpreferredduringschedulingignoredduringexecutionmixin)
          * [`fn withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-specimportschedulingaffinitypodaffinitywithrequiredduringschedulingignoredduringexecution)
          * [`fn withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-specimportschedulingaffinitypodaffinitywithrequiredduringschedulingignoredduringexecutionmixin)
          * [`obj spec.import.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution`](#obj-specimportschedulingaffinitypodaffinitypreferredduringschedulingignoredduringexecution)
            * [`fn withWeight(weight)`](#fn-specimportschedulingaffinitypodaffinitypreferredduringschedulingignoredduringexecutionwithweight)
            * [`obj spec.import.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm`](#obj-specimportschedulingaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinityterm)
              * [`fn withMatchLabelKeys(matchLabelKeys)`](#fn-specimportschedulingaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmatchlabelkeys)
              * [`fn withMatchLabelKeysMixin(matchLabelKeys)`](#fn-specimportschedulingaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmatchlabelkeysmixin)
              * [`fn withMismatchLabelKeys(mismatchLabelKeys)`](#fn-specimportschedulingaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmismatchlabelkeys)
              * [`fn withMismatchLabelKeysMixin(mismatchLabelKeys)`](#fn-specimportschedulingaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmismatchlabelkeysmixin)
              * [`fn withNamespaces(namespaces)`](#fn-specimportschedulingaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithnamespaces)
              * [`fn withNamespacesMixin(namespaces)`](#fn-specimportschedulingaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithnamespacesmixin)
              * [`fn withTopologyKey(topologyKey)`](#fn-specimportschedulingaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithtopologykey)
              * [`obj spec.import.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector`](#obj-specimportschedulingaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselector)
                * [`fn withMatchExpressions(matchExpressions)`](#fn-specimportschedulingaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchexpressions)
                * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specimportschedulingaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchexpressionsmixin)
                * [`fn withMatchLabels(matchLabels)`](#fn-specimportschedulingaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchlabels)
                * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specimportschedulingaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchlabelsmixin)
                * [`obj spec.import.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions`](#obj-specimportschedulingaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressions)
                  * [`fn withKey(key)`](#fn-specimportschedulingaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithkey)
                  * [`fn withOperator(operator)`](#fn-specimportschedulingaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithoperator)
                  * [`fn withValues(values)`](#fn-specimportschedulingaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithvalues)
                  * [`fn withValuesMixin(values)`](#fn-specimportschedulingaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithvaluesmixin)
              * [`obj spec.import.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector`](#obj-specimportschedulingaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselector)
                * [`fn withMatchExpressions(matchExpressions)`](#fn-specimportschedulingaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchexpressions)
                * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specimportschedulingaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchexpressionsmixin)
                * [`fn withMatchLabels(matchLabels)`](#fn-specimportschedulingaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchlabels)
                * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specimportschedulingaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchlabelsmixin)
                * [`obj spec.import.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions`](#obj-specimportschedulingaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressions)
                  * [`fn withKey(key)`](#fn-specimportschedulingaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithkey)
                  * [`fn withOperator(operator)`](#fn-specimportschedulingaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithoperator)
                  * [`fn withValues(values)`](#fn-specimportschedulingaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithvalues)
                  * [`fn withValuesMixin(values)`](#fn-specimportschedulingaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithvaluesmixin)
          * [`obj spec.import.scheduling.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution`](#obj-specimportschedulingaffinitypodaffinityrequiredduringschedulingignoredduringexecution)
            * [`fn withMatchLabelKeys(matchLabelKeys)`](#fn-specimportschedulingaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithmatchlabelkeys)
            * [`fn withMatchLabelKeysMixin(matchLabelKeys)`](#fn-specimportschedulingaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithmatchlabelkeysmixin)
            * [`fn withMismatchLabelKeys(mismatchLabelKeys)`](#fn-specimportschedulingaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithmismatchlabelkeys)
            * [`fn withMismatchLabelKeysMixin(mismatchLabelKeys)`](#fn-specimportschedulingaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithmismatchlabelkeysmixin)
            * [`fn withNamespaces(namespaces)`](#fn-specimportschedulingaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithnamespaces)
            * [`fn withNamespacesMixin(namespaces)`](#fn-specimportschedulingaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithnamespacesmixin)
            * [`fn withTopologyKey(topologyKey)`](#fn-specimportschedulingaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithtopologykey)
            * [`obj spec.import.scheduling.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector`](#obj-specimportschedulingaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselector)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-specimportschedulingaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specimportschedulingaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchexpressionsmixin)
              * [`fn withMatchLabels(matchLabels)`](#fn-specimportschedulingaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchlabels)
              * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specimportschedulingaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchlabelsmixin)
              * [`obj spec.import.scheduling.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions`](#obj-specimportschedulingaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressions)
                * [`fn withKey(key)`](#fn-specimportschedulingaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-specimportschedulingaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-specimportschedulingaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-specimportschedulingaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithvaluesmixin)
            * [`obj spec.import.scheduling.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector`](#obj-specimportschedulingaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselector)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-specimportschedulingaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specimportschedulingaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchexpressionsmixin)
              * [`fn withMatchLabels(matchLabels)`](#fn-specimportschedulingaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchlabels)
              * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specimportschedulingaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchlabelsmixin)
              * [`obj spec.import.scheduling.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions`](#obj-specimportschedulingaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressions)
                * [`fn withKey(key)`](#fn-specimportschedulingaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-specimportschedulingaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-specimportschedulingaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-specimportschedulingaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithvaluesmixin)
        * [`obj spec.import.scheduling.affinity.podAntiAffinity`](#obj-specimportschedulingaffinitypodantiaffinity)
          * [`fn withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-specimportschedulingaffinitypodantiaffinitywithpreferredduringschedulingignoredduringexecution)
          * [`fn withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-specimportschedulingaffinitypodantiaffinitywithpreferredduringschedulingignoredduringexecutionmixin)
          * [`fn withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-specimportschedulingaffinitypodantiaffinitywithrequiredduringschedulingignoredduringexecution)
          * [`fn withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-specimportschedulingaffinitypodantiaffinitywithrequiredduringschedulingignoredduringexecutionmixin)
          * [`obj spec.import.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution`](#obj-specimportschedulingaffinitypodantiaffinitypreferredduringschedulingignoredduringexecution)
            * [`fn withWeight(weight)`](#fn-specimportschedulingaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionwithweight)
            * [`obj spec.import.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm`](#obj-specimportschedulingaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinityterm)
              * [`fn withMatchLabelKeys(matchLabelKeys)`](#fn-specimportschedulingaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmatchlabelkeys)
              * [`fn withMatchLabelKeysMixin(matchLabelKeys)`](#fn-specimportschedulingaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmatchlabelkeysmixin)
              * [`fn withMismatchLabelKeys(mismatchLabelKeys)`](#fn-specimportschedulingaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmismatchlabelkeys)
              * [`fn withMismatchLabelKeysMixin(mismatchLabelKeys)`](#fn-specimportschedulingaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmismatchlabelkeysmixin)
              * [`fn withNamespaces(namespaces)`](#fn-specimportschedulingaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithnamespaces)
              * [`fn withNamespacesMixin(namespaces)`](#fn-specimportschedulingaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithnamespacesmixin)
              * [`fn withTopologyKey(topologyKey)`](#fn-specimportschedulingaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithtopologykey)
              * [`obj spec.import.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector`](#obj-specimportschedulingaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselector)
                * [`fn withMatchExpressions(matchExpressions)`](#fn-specimportschedulingaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchexpressions)
                * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specimportschedulingaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchexpressionsmixin)
                * [`fn withMatchLabels(matchLabels)`](#fn-specimportschedulingaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchlabels)
                * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specimportschedulingaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchlabelsmixin)
                * [`obj spec.import.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions`](#obj-specimportschedulingaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressions)
                  * [`fn withKey(key)`](#fn-specimportschedulingaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithkey)
                  * [`fn withOperator(operator)`](#fn-specimportschedulingaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithoperator)
                  * [`fn withValues(values)`](#fn-specimportschedulingaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithvalues)
                  * [`fn withValuesMixin(values)`](#fn-specimportschedulingaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithvaluesmixin)
              * [`obj spec.import.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector`](#obj-specimportschedulingaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselector)
                * [`fn withMatchExpressions(matchExpressions)`](#fn-specimportschedulingaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchexpressions)
                * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specimportschedulingaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchexpressionsmixin)
                * [`fn withMatchLabels(matchLabels)`](#fn-specimportschedulingaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchlabels)
                * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specimportschedulingaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchlabelsmixin)
                * [`obj spec.import.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions`](#obj-specimportschedulingaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressions)
                  * [`fn withKey(key)`](#fn-specimportschedulingaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithkey)
                  * [`fn withOperator(operator)`](#fn-specimportschedulingaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithoperator)
                  * [`fn withValues(values)`](#fn-specimportschedulingaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithvalues)
                  * [`fn withValuesMixin(values)`](#fn-specimportschedulingaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithvaluesmixin)
          * [`obj spec.import.scheduling.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution`](#obj-specimportschedulingaffinitypodantiaffinityrequiredduringschedulingignoredduringexecution)
            * [`fn withMatchLabelKeys(matchLabelKeys)`](#fn-specimportschedulingaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithmatchlabelkeys)
            * [`fn withMatchLabelKeysMixin(matchLabelKeys)`](#fn-specimportschedulingaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithmatchlabelkeysmixin)
            * [`fn withMismatchLabelKeys(mismatchLabelKeys)`](#fn-specimportschedulingaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithmismatchlabelkeys)
            * [`fn withMismatchLabelKeysMixin(mismatchLabelKeys)`](#fn-specimportschedulingaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithmismatchlabelkeysmixin)
            * [`fn withNamespaces(namespaces)`](#fn-specimportschedulingaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithnamespaces)
            * [`fn withNamespacesMixin(namespaces)`](#fn-specimportschedulingaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithnamespacesmixin)
            * [`fn withTopologyKey(topologyKey)`](#fn-specimportschedulingaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithtopologykey)
            * [`obj spec.import.scheduling.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector`](#obj-specimportschedulingaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselector)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-specimportschedulingaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specimportschedulingaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchexpressionsmixin)
              * [`fn withMatchLabels(matchLabels)`](#fn-specimportschedulingaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchlabels)
              * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specimportschedulingaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchlabelsmixin)
              * [`obj spec.import.scheduling.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions`](#obj-specimportschedulingaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressions)
                * [`fn withKey(key)`](#fn-specimportschedulingaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-specimportschedulingaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-specimportschedulingaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-specimportschedulingaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithvaluesmixin)
            * [`obj spec.import.scheduling.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector`](#obj-specimportschedulingaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselector)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-specimportschedulingaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specimportschedulingaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchexpressionsmixin)
              * [`fn withMatchLabels(matchLabels)`](#fn-specimportschedulingaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchlabels)
              * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specimportschedulingaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchlabelsmixin)
              * [`obj spec.import.scheduling.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions`](#obj-specimportschedulingaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressions)
                * [`fn withKey(key)`](#fn-specimportschedulingaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-specimportschedulingaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-specimportschedulingaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-specimportschedulingaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithvaluesmixin)
      * [`obj spec.import.scheduling.tolerations`](#obj-specimportschedulingtolerations)
        * [`fn withEffect(effect)`](#fn-specimportschedulingtolerationswitheffect)
        * [`fn withKey(key)`](#fn-specimportschedulingtolerationswithkey)
        * [`fn withOperator(operator)`](#fn-specimportschedulingtolerationswithoperator)
        * [`fn withTolerationSeconds(tolerationSeconds)`](#fn-specimportschedulingtolerationswithtolerationseconds)
        * [`fn withValue(value)`](#fn-specimportschedulingtolerationswithvalue)
      * [`obj spec.import.scheduling.topologySpreadConstraints`](#obj-specimportschedulingtopologyspreadconstraints)
        * [`fn withMatchLabelKeys(matchLabelKeys)`](#fn-specimportschedulingtopologyspreadconstraintswithmatchlabelkeys)
        * [`fn withMatchLabelKeysMixin(matchLabelKeys)`](#fn-specimportschedulingtopologyspreadconstraintswithmatchlabelkeysmixin)
        * [`fn withMaxSkew(maxSkew)`](#fn-specimportschedulingtopologyspreadconstraintswithmaxskew)
        * [`fn withMinDomains(minDomains)`](#fn-specimportschedulingtopologyspreadconstraintswithmindomains)
        * [`fn withNodeAffinityPolicy(nodeAffinityPolicy)`](#fn-specimportschedulingtopologyspreadconstraintswithnodeaffinitypolicy)
        * [`fn withNodeTaintsPolicy(nodeTaintsPolicy)`](#fn-specimportschedulingtopologyspreadconstraintswithnodetaintspolicy)
        * [`fn withTopologyKey(topologyKey)`](#fn-specimportschedulingtopologyspreadconstraintswithtopologykey)
        * [`fn withWhenUnsatisfiable(whenUnsatisfiable)`](#fn-specimportschedulingtopologyspreadconstraintswithwhenunsatisfiable)
        * [`obj spec.import.scheduling.topologySpreadConstraints.labelSelector`](#obj-specimportschedulingtopologyspreadconstraintslabelselector)
          * [`fn withMatchExpressions(matchExpressions)`](#fn-specimportschedulingtopologyspreadconstraintslabelselectorwithmatchexpressions)
          * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specimportschedulingtopologyspreadconstraintslabelselectorwithmatchexpressionsmixin)
          * [`fn withMatchLabels(matchLabels)`](#fn-specimportschedulingtopologyspreadconstraintslabelselectorwithmatchlabels)
          * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specimportschedulingtopologyspreadconstraintslabelselectorwithmatchlabelsmixin)
          * [`obj spec.import.scheduling.topologySpreadConstraints.labelSelector.matchExpressions`](#obj-specimportschedulingtopologyspreadconstraintslabelselectormatchexpressions)
            * [`fn withKey(key)`](#fn-specimportschedulingtopologyspreadconstraintslabelselectormatchexpressionswithkey)
            * [`fn withOperator(operator)`](#fn-specimportschedulingtopologyspreadconstraintslabelselectormatchexpressionswithoperator)
            * [`fn withValues(values)`](#fn-specimportschedulingtopologyspreadconstraintslabelselectormatchexpressionswithvalues)
            * [`fn withValuesMixin(values)`](#fn-specimportschedulingtopologyspreadconstraintslabelselectormatchexpressionswithvaluesmixin)
  * [`obj spec.ingress`](#obj-specingress)
    * [`fn withAnnotations(annotations)`](#fn-specingresswithannotations)
    * [`fn withAnnotationsMixin(annotations)`](#fn-specingresswithannotationsmixin)
    * [`fn withClassName(className)`](#fn-specingresswithclassname)
    * [`fn withEnabled(enabled)`](#fn-specingresswithenabled)
    * [`fn withLabels(labels)`](#fn-specingresswithlabels)
    * [`fn withLabelsMixin(labels)`](#fn-specingresswithlabelsmixin)
    * [`fn withTlsSecret(tlsSecret)`](#fn-specingresswithtlssecret)
  * [`obj spec.livenessProbe`](#obj-speclivenessprobe)
    * [`fn withFailureThreshold(failureThreshold)`](#fn-speclivenessprobewithfailurethreshold)
    * [`fn withPeriodSeconds(periodSeconds)`](#fn-speclivenessprobewithperiodseconds)
  * [`obj spec.networkPolicy`](#obj-specnetworkpolicy)
    * [`fn withEnabled(enabled)`](#fn-specnetworkpolicywithenabled)
    * [`fn withHttp(http)`](#fn-specnetworkpolicywithhttp)
    * [`fn withHttpMixin(http)`](#fn-specnetworkpolicywithhttpmixin)
    * [`fn withHttps(https)`](#fn-specnetworkpolicywithhttps)
    * [`fn withHttpsMixin(https)`](#fn-specnetworkpolicywithhttpsmixin)
    * [`fn withManagement(management)`](#fn-specnetworkpolicywithmanagement)
    * [`fn withManagementMixin(management)`](#fn-specnetworkpolicywithmanagementmixin)
    * [`obj spec.networkPolicy.http`](#obj-specnetworkpolicyhttp)
      * [`obj spec.networkPolicy.http.ipBlock`](#obj-specnetworkpolicyhttpipblock)
        * [`fn withCidr(cidr)`](#fn-specnetworkpolicyhttpipblockwithcidr)
        * [`fn withExcept(except)`](#fn-specnetworkpolicyhttpipblockwithexcept)
        * [`fn withExceptMixin(except)`](#fn-specnetworkpolicyhttpipblockwithexceptmixin)
      * [`obj spec.networkPolicy.http.namespaceSelector`](#obj-specnetworkpolicyhttpnamespaceselector)
        * [`fn withMatchExpressions(matchExpressions)`](#fn-specnetworkpolicyhttpnamespaceselectorwithmatchexpressions)
        * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specnetworkpolicyhttpnamespaceselectorwithmatchexpressionsmixin)
        * [`fn withMatchLabels(matchLabels)`](#fn-specnetworkpolicyhttpnamespaceselectorwithmatchlabels)
        * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specnetworkpolicyhttpnamespaceselectorwithmatchlabelsmixin)
        * [`obj spec.networkPolicy.http.namespaceSelector.matchExpressions`](#obj-specnetworkpolicyhttpnamespaceselectormatchexpressions)
          * [`fn withKey(key)`](#fn-specnetworkpolicyhttpnamespaceselectormatchexpressionswithkey)
          * [`fn withOperator(operator)`](#fn-specnetworkpolicyhttpnamespaceselectormatchexpressionswithoperator)
          * [`fn withValues(values)`](#fn-specnetworkpolicyhttpnamespaceselectormatchexpressionswithvalues)
          * [`fn withValuesMixin(values)`](#fn-specnetworkpolicyhttpnamespaceselectormatchexpressionswithvaluesmixin)
      * [`obj spec.networkPolicy.http.podSelector`](#obj-specnetworkpolicyhttppodselector)
        * [`fn withMatchExpressions(matchExpressions)`](#fn-specnetworkpolicyhttppodselectorwithmatchexpressions)
        * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specnetworkpolicyhttppodselectorwithmatchexpressionsmixin)
        * [`fn withMatchLabels(matchLabels)`](#fn-specnetworkpolicyhttppodselectorwithmatchlabels)
        * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specnetworkpolicyhttppodselectorwithmatchlabelsmixin)
        * [`obj spec.networkPolicy.http.podSelector.matchExpressions`](#obj-specnetworkpolicyhttppodselectormatchexpressions)
          * [`fn withKey(key)`](#fn-specnetworkpolicyhttppodselectormatchexpressionswithkey)
          * [`fn withOperator(operator)`](#fn-specnetworkpolicyhttppodselectormatchexpressionswithoperator)
          * [`fn withValues(values)`](#fn-specnetworkpolicyhttppodselectormatchexpressionswithvalues)
          * [`fn withValuesMixin(values)`](#fn-specnetworkpolicyhttppodselectormatchexpressionswithvaluesmixin)
    * [`obj spec.networkPolicy.https`](#obj-specnetworkpolicyhttps)
      * [`obj spec.networkPolicy.https.ipBlock`](#obj-specnetworkpolicyhttpsipblock)
        * [`fn withCidr(cidr)`](#fn-specnetworkpolicyhttpsipblockwithcidr)
        * [`fn withExcept(except)`](#fn-specnetworkpolicyhttpsipblockwithexcept)
        * [`fn withExceptMixin(except)`](#fn-specnetworkpolicyhttpsipblockwithexceptmixin)
      * [`obj spec.networkPolicy.https.namespaceSelector`](#obj-specnetworkpolicyhttpsnamespaceselector)
        * [`fn withMatchExpressions(matchExpressions)`](#fn-specnetworkpolicyhttpsnamespaceselectorwithmatchexpressions)
        * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specnetworkpolicyhttpsnamespaceselectorwithmatchexpressionsmixin)
        * [`fn withMatchLabels(matchLabels)`](#fn-specnetworkpolicyhttpsnamespaceselectorwithmatchlabels)
        * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specnetworkpolicyhttpsnamespaceselectorwithmatchlabelsmixin)
        * [`obj spec.networkPolicy.https.namespaceSelector.matchExpressions`](#obj-specnetworkpolicyhttpsnamespaceselectormatchexpressions)
          * [`fn withKey(key)`](#fn-specnetworkpolicyhttpsnamespaceselectormatchexpressionswithkey)
          * [`fn withOperator(operator)`](#fn-specnetworkpolicyhttpsnamespaceselectormatchexpressionswithoperator)
          * [`fn withValues(values)`](#fn-specnetworkpolicyhttpsnamespaceselectormatchexpressionswithvalues)
          * [`fn withValuesMixin(values)`](#fn-specnetworkpolicyhttpsnamespaceselectormatchexpressionswithvaluesmixin)
      * [`obj spec.networkPolicy.https.podSelector`](#obj-specnetworkpolicyhttpspodselector)
        * [`fn withMatchExpressions(matchExpressions)`](#fn-specnetworkpolicyhttpspodselectorwithmatchexpressions)
        * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specnetworkpolicyhttpspodselectorwithmatchexpressionsmixin)
        * [`fn withMatchLabels(matchLabels)`](#fn-specnetworkpolicyhttpspodselectorwithmatchlabels)
        * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specnetworkpolicyhttpspodselectorwithmatchlabelsmixin)
        * [`obj spec.networkPolicy.https.podSelector.matchExpressions`](#obj-specnetworkpolicyhttpspodselectormatchexpressions)
          * [`fn withKey(key)`](#fn-specnetworkpolicyhttpspodselectormatchexpressionswithkey)
          * [`fn withOperator(operator)`](#fn-specnetworkpolicyhttpspodselectormatchexpressionswithoperator)
          * [`fn withValues(values)`](#fn-specnetworkpolicyhttpspodselectormatchexpressionswithvalues)
          * [`fn withValuesMixin(values)`](#fn-specnetworkpolicyhttpspodselectormatchexpressionswithvaluesmixin)
    * [`obj spec.networkPolicy.management`](#obj-specnetworkpolicymanagement)
      * [`obj spec.networkPolicy.management.ipBlock`](#obj-specnetworkpolicymanagementipblock)
        * [`fn withCidr(cidr)`](#fn-specnetworkpolicymanagementipblockwithcidr)
        * [`fn withExcept(except)`](#fn-specnetworkpolicymanagementipblockwithexcept)
        * [`fn withExceptMixin(except)`](#fn-specnetworkpolicymanagementipblockwithexceptmixin)
      * [`obj spec.networkPolicy.management.namespaceSelector`](#obj-specnetworkpolicymanagementnamespaceselector)
        * [`fn withMatchExpressions(matchExpressions)`](#fn-specnetworkpolicymanagementnamespaceselectorwithmatchexpressions)
        * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specnetworkpolicymanagementnamespaceselectorwithmatchexpressionsmixin)
        * [`fn withMatchLabels(matchLabels)`](#fn-specnetworkpolicymanagementnamespaceselectorwithmatchlabels)
        * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specnetworkpolicymanagementnamespaceselectorwithmatchlabelsmixin)
        * [`obj spec.networkPolicy.management.namespaceSelector.matchExpressions`](#obj-specnetworkpolicymanagementnamespaceselectormatchexpressions)
          * [`fn withKey(key)`](#fn-specnetworkpolicymanagementnamespaceselectormatchexpressionswithkey)
          * [`fn withOperator(operator)`](#fn-specnetworkpolicymanagementnamespaceselectormatchexpressionswithoperator)
          * [`fn withValues(values)`](#fn-specnetworkpolicymanagementnamespaceselectormatchexpressionswithvalues)
          * [`fn withValuesMixin(values)`](#fn-specnetworkpolicymanagementnamespaceselectormatchexpressionswithvaluesmixin)
      * [`obj spec.networkPolicy.management.podSelector`](#obj-specnetworkpolicymanagementpodselector)
        * [`fn withMatchExpressions(matchExpressions)`](#fn-specnetworkpolicymanagementpodselectorwithmatchexpressions)
        * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specnetworkpolicymanagementpodselectorwithmatchexpressionsmixin)
        * [`fn withMatchLabels(matchLabels)`](#fn-specnetworkpolicymanagementpodselectorwithmatchlabels)
        * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specnetworkpolicymanagementpodselectorwithmatchlabelsmixin)
        * [`obj spec.networkPolicy.management.podSelector.matchExpressions`](#obj-specnetworkpolicymanagementpodselectormatchexpressions)
          * [`fn withKey(key)`](#fn-specnetworkpolicymanagementpodselectormatchexpressionswithkey)
          * [`fn withOperator(operator)`](#fn-specnetworkpolicymanagementpodselectormatchexpressionswithoperator)
          * [`fn withValues(values)`](#fn-specnetworkpolicymanagementpodselectormatchexpressionswithvalues)
          * [`fn withValuesMixin(values)`](#fn-specnetworkpolicymanagementpodselectormatchexpressionswithvaluesmixin)
  * [`obj spec.proxy`](#obj-specproxy)
    * [`fn withHeaders(headers)`](#fn-specproxywithheaders)
  * [`obj spec.readinessProbe`](#obj-specreadinessprobe)
    * [`fn withFailureThreshold(failureThreshold)`](#fn-specreadinessprobewithfailurethreshold)
    * [`fn withPeriodSeconds(periodSeconds)`](#fn-specreadinessprobewithperiodseconds)
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
  * [`obj spec.scheduling`](#obj-specscheduling)
    * [`fn withPriorityClassName(priorityClassName)`](#fn-specschedulingwithpriorityclassname)
    * [`fn withTolerations(tolerations)`](#fn-specschedulingwithtolerations)
    * [`fn withTolerationsMixin(tolerations)`](#fn-specschedulingwithtolerationsmixin)
    * [`fn withTopologySpreadConstraints(topologySpreadConstraints)`](#fn-specschedulingwithtopologyspreadconstraints)
    * [`fn withTopologySpreadConstraintsMixin(topologySpreadConstraints)`](#fn-specschedulingwithtopologyspreadconstraintsmixin)
    * [`obj spec.scheduling.affinity`](#obj-specschedulingaffinity)
      * [`obj spec.scheduling.affinity.nodeAffinity`](#obj-specschedulingaffinitynodeaffinity)
        * [`fn withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-specschedulingaffinitynodeaffinitywithpreferredduringschedulingignoredduringexecution)
        * [`fn withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-specschedulingaffinitynodeaffinitywithpreferredduringschedulingignoredduringexecutionmixin)
        * [`obj spec.scheduling.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution`](#obj-specschedulingaffinitynodeaffinitypreferredduringschedulingignoredduringexecution)
          * [`fn withWeight(weight)`](#fn-specschedulingaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionwithweight)
          * [`obj spec.scheduling.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference`](#obj-specschedulingaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreference)
            * [`fn withMatchExpressions(matchExpressions)`](#fn-specschedulingaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencewithmatchexpressions)
            * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specschedulingaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencewithmatchexpressionsmixin)
            * [`fn withMatchFields(matchFields)`](#fn-specschedulingaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencewithmatchfields)
            * [`fn withMatchFieldsMixin(matchFields)`](#fn-specschedulingaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencewithmatchfieldsmixin)
            * [`obj spec.scheduling.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions`](#obj-specschedulingaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressions)
              * [`fn withKey(key)`](#fn-specschedulingaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressionswithkey)
              * [`fn withOperator(operator)`](#fn-specschedulingaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressionswithoperator)
              * [`fn withValues(values)`](#fn-specschedulingaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressionswithvalues)
              * [`fn withValuesMixin(values)`](#fn-specschedulingaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressionswithvaluesmixin)
            * [`obj spec.scheduling.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields`](#obj-specschedulingaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfields)
              * [`fn withKey(key)`](#fn-specschedulingaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfieldswithkey)
              * [`fn withOperator(operator)`](#fn-specschedulingaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfieldswithoperator)
              * [`fn withValues(values)`](#fn-specschedulingaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfieldswithvalues)
              * [`fn withValuesMixin(values)`](#fn-specschedulingaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfieldswithvaluesmixin)
        * [`obj spec.scheduling.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution`](#obj-specschedulingaffinitynodeaffinityrequiredduringschedulingignoredduringexecution)
          * [`fn withNodeSelectorTerms(nodeSelectorTerms)`](#fn-specschedulingaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionwithnodeselectorterms)
          * [`fn withNodeSelectorTermsMixin(nodeSelectorTerms)`](#fn-specschedulingaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionwithnodeselectortermsmixin)
          * [`obj spec.scheduling.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms`](#obj-specschedulingaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectorterms)
            * [`fn withMatchExpressions(matchExpressions)`](#fn-specschedulingaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermswithmatchexpressions)
            * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specschedulingaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermswithmatchexpressionsmixin)
            * [`fn withMatchFields(matchFields)`](#fn-specschedulingaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermswithmatchfields)
            * [`fn withMatchFieldsMixin(matchFields)`](#fn-specschedulingaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermswithmatchfieldsmixin)
            * [`obj spec.scheduling.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions`](#obj-specschedulingaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressions)
              * [`fn withKey(key)`](#fn-specschedulingaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressionswithkey)
              * [`fn withOperator(operator)`](#fn-specschedulingaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressionswithoperator)
              * [`fn withValues(values)`](#fn-specschedulingaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressionswithvalues)
              * [`fn withValuesMixin(values)`](#fn-specschedulingaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressionswithvaluesmixin)
            * [`obj spec.scheduling.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields`](#obj-specschedulingaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfields)
              * [`fn withKey(key)`](#fn-specschedulingaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfieldswithkey)
              * [`fn withOperator(operator)`](#fn-specschedulingaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfieldswithoperator)
              * [`fn withValues(values)`](#fn-specschedulingaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfieldswithvalues)
              * [`fn withValuesMixin(values)`](#fn-specschedulingaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfieldswithvaluesmixin)
      * [`obj spec.scheduling.affinity.podAffinity`](#obj-specschedulingaffinitypodaffinity)
        * [`fn withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-specschedulingaffinitypodaffinitywithpreferredduringschedulingignoredduringexecution)
        * [`fn withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-specschedulingaffinitypodaffinitywithpreferredduringschedulingignoredduringexecutionmixin)
        * [`fn withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-specschedulingaffinitypodaffinitywithrequiredduringschedulingignoredduringexecution)
        * [`fn withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-specschedulingaffinitypodaffinitywithrequiredduringschedulingignoredduringexecutionmixin)
        * [`obj spec.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution`](#obj-specschedulingaffinitypodaffinitypreferredduringschedulingignoredduringexecution)
          * [`fn withWeight(weight)`](#fn-specschedulingaffinitypodaffinitypreferredduringschedulingignoredduringexecutionwithweight)
          * [`obj spec.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm`](#obj-specschedulingaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinityterm)
            * [`fn withMatchLabelKeys(matchLabelKeys)`](#fn-specschedulingaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmatchlabelkeys)
            * [`fn withMatchLabelKeysMixin(matchLabelKeys)`](#fn-specschedulingaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmatchlabelkeysmixin)
            * [`fn withMismatchLabelKeys(mismatchLabelKeys)`](#fn-specschedulingaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmismatchlabelkeys)
            * [`fn withMismatchLabelKeysMixin(mismatchLabelKeys)`](#fn-specschedulingaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmismatchlabelkeysmixin)
            * [`fn withNamespaces(namespaces)`](#fn-specschedulingaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithnamespaces)
            * [`fn withNamespacesMixin(namespaces)`](#fn-specschedulingaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithnamespacesmixin)
            * [`fn withTopologyKey(topologyKey)`](#fn-specschedulingaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithtopologykey)
            * [`obj spec.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector`](#obj-specschedulingaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselector)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-specschedulingaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specschedulingaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchexpressionsmixin)
              * [`fn withMatchLabels(matchLabels)`](#fn-specschedulingaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchlabels)
              * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specschedulingaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchlabelsmixin)
              * [`obj spec.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions`](#obj-specschedulingaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressions)
                * [`fn withKey(key)`](#fn-specschedulingaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-specschedulingaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-specschedulingaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-specschedulingaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithvaluesmixin)
            * [`obj spec.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector`](#obj-specschedulingaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselector)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-specschedulingaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specschedulingaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchexpressionsmixin)
              * [`fn withMatchLabels(matchLabels)`](#fn-specschedulingaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchlabels)
              * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specschedulingaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchlabelsmixin)
              * [`obj spec.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions`](#obj-specschedulingaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressions)
                * [`fn withKey(key)`](#fn-specschedulingaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-specschedulingaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-specschedulingaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-specschedulingaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithvaluesmixin)
        * [`obj spec.scheduling.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution`](#obj-specschedulingaffinitypodaffinityrequiredduringschedulingignoredduringexecution)
          * [`fn withMatchLabelKeys(matchLabelKeys)`](#fn-specschedulingaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithmatchlabelkeys)
          * [`fn withMatchLabelKeysMixin(matchLabelKeys)`](#fn-specschedulingaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithmatchlabelkeysmixin)
          * [`fn withMismatchLabelKeys(mismatchLabelKeys)`](#fn-specschedulingaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithmismatchlabelkeys)
          * [`fn withMismatchLabelKeysMixin(mismatchLabelKeys)`](#fn-specschedulingaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithmismatchlabelkeysmixin)
          * [`fn withNamespaces(namespaces)`](#fn-specschedulingaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithnamespaces)
          * [`fn withNamespacesMixin(namespaces)`](#fn-specschedulingaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithnamespacesmixin)
          * [`fn withTopologyKey(topologyKey)`](#fn-specschedulingaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithtopologykey)
          * [`obj spec.scheduling.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector`](#obj-specschedulingaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselector)
            * [`fn withMatchExpressions(matchExpressions)`](#fn-specschedulingaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchexpressions)
            * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specschedulingaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchexpressionsmixin)
            * [`fn withMatchLabels(matchLabels)`](#fn-specschedulingaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchlabels)
            * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specschedulingaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchlabelsmixin)
            * [`obj spec.scheduling.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions`](#obj-specschedulingaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressions)
              * [`fn withKey(key)`](#fn-specschedulingaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithkey)
              * [`fn withOperator(operator)`](#fn-specschedulingaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithoperator)
              * [`fn withValues(values)`](#fn-specschedulingaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithvalues)
              * [`fn withValuesMixin(values)`](#fn-specschedulingaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithvaluesmixin)
          * [`obj spec.scheduling.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector`](#obj-specschedulingaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselector)
            * [`fn withMatchExpressions(matchExpressions)`](#fn-specschedulingaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchexpressions)
            * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specschedulingaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchexpressionsmixin)
            * [`fn withMatchLabels(matchLabels)`](#fn-specschedulingaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchlabels)
            * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specschedulingaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchlabelsmixin)
            * [`obj spec.scheduling.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions`](#obj-specschedulingaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressions)
              * [`fn withKey(key)`](#fn-specschedulingaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithkey)
              * [`fn withOperator(operator)`](#fn-specschedulingaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithoperator)
              * [`fn withValues(values)`](#fn-specschedulingaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithvalues)
              * [`fn withValuesMixin(values)`](#fn-specschedulingaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithvaluesmixin)
      * [`obj spec.scheduling.affinity.podAntiAffinity`](#obj-specschedulingaffinitypodantiaffinity)
        * [`fn withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-specschedulingaffinitypodantiaffinitywithpreferredduringschedulingignoredduringexecution)
        * [`fn withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-specschedulingaffinitypodantiaffinitywithpreferredduringschedulingignoredduringexecutionmixin)
        * [`fn withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-specschedulingaffinitypodantiaffinitywithrequiredduringschedulingignoredduringexecution)
        * [`fn withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-specschedulingaffinitypodantiaffinitywithrequiredduringschedulingignoredduringexecutionmixin)
        * [`obj spec.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution`](#obj-specschedulingaffinitypodantiaffinitypreferredduringschedulingignoredduringexecution)
          * [`fn withWeight(weight)`](#fn-specschedulingaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionwithweight)
          * [`obj spec.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm`](#obj-specschedulingaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinityterm)
            * [`fn withMatchLabelKeys(matchLabelKeys)`](#fn-specschedulingaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmatchlabelkeys)
            * [`fn withMatchLabelKeysMixin(matchLabelKeys)`](#fn-specschedulingaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmatchlabelkeysmixin)
            * [`fn withMismatchLabelKeys(mismatchLabelKeys)`](#fn-specschedulingaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmismatchlabelkeys)
            * [`fn withMismatchLabelKeysMixin(mismatchLabelKeys)`](#fn-specschedulingaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmismatchlabelkeysmixin)
            * [`fn withNamespaces(namespaces)`](#fn-specschedulingaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithnamespaces)
            * [`fn withNamespacesMixin(namespaces)`](#fn-specschedulingaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithnamespacesmixin)
            * [`fn withTopologyKey(topologyKey)`](#fn-specschedulingaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithtopologykey)
            * [`obj spec.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector`](#obj-specschedulingaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselector)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-specschedulingaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specschedulingaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchexpressionsmixin)
              * [`fn withMatchLabels(matchLabels)`](#fn-specschedulingaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchlabels)
              * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specschedulingaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchlabelsmixin)
              * [`obj spec.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions`](#obj-specschedulingaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressions)
                * [`fn withKey(key)`](#fn-specschedulingaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-specschedulingaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-specschedulingaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-specschedulingaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithvaluesmixin)
            * [`obj spec.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector`](#obj-specschedulingaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselector)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-specschedulingaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specschedulingaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchexpressionsmixin)
              * [`fn withMatchLabels(matchLabels)`](#fn-specschedulingaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchlabels)
              * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specschedulingaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchlabelsmixin)
              * [`obj spec.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions`](#obj-specschedulingaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressions)
                * [`fn withKey(key)`](#fn-specschedulingaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-specschedulingaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-specschedulingaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-specschedulingaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithvaluesmixin)
        * [`obj spec.scheduling.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution`](#obj-specschedulingaffinitypodantiaffinityrequiredduringschedulingignoredduringexecution)
          * [`fn withMatchLabelKeys(matchLabelKeys)`](#fn-specschedulingaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithmatchlabelkeys)
          * [`fn withMatchLabelKeysMixin(matchLabelKeys)`](#fn-specschedulingaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithmatchlabelkeysmixin)
          * [`fn withMismatchLabelKeys(mismatchLabelKeys)`](#fn-specschedulingaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithmismatchlabelkeys)
          * [`fn withMismatchLabelKeysMixin(mismatchLabelKeys)`](#fn-specschedulingaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithmismatchlabelkeysmixin)
          * [`fn withNamespaces(namespaces)`](#fn-specschedulingaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithnamespaces)
          * [`fn withNamespacesMixin(namespaces)`](#fn-specschedulingaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithnamespacesmixin)
          * [`fn withTopologyKey(topologyKey)`](#fn-specschedulingaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithtopologykey)
          * [`obj spec.scheduling.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector`](#obj-specschedulingaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselector)
            * [`fn withMatchExpressions(matchExpressions)`](#fn-specschedulingaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchexpressions)
            * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specschedulingaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchexpressionsmixin)
            * [`fn withMatchLabels(matchLabels)`](#fn-specschedulingaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchlabels)
            * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specschedulingaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchlabelsmixin)
            * [`obj spec.scheduling.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions`](#obj-specschedulingaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressions)
              * [`fn withKey(key)`](#fn-specschedulingaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithkey)
              * [`fn withOperator(operator)`](#fn-specschedulingaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithoperator)
              * [`fn withValues(values)`](#fn-specschedulingaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithvalues)
              * [`fn withValuesMixin(values)`](#fn-specschedulingaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithvaluesmixin)
          * [`obj spec.scheduling.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector`](#obj-specschedulingaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselector)
            * [`fn withMatchExpressions(matchExpressions)`](#fn-specschedulingaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchexpressions)
            * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specschedulingaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchexpressionsmixin)
            * [`fn withMatchLabels(matchLabels)`](#fn-specschedulingaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchlabels)
            * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specschedulingaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchlabelsmixin)
            * [`obj spec.scheduling.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions`](#obj-specschedulingaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressions)
              * [`fn withKey(key)`](#fn-specschedulingaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithkey)
              * [`fn withOperator(operator)`](#fn-specschedulingaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithoperator)
              * [`fn withValues(values)`](#fn-specschedulingaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithvalues)
              * [`fn withValuesMixin(values)`](#fn-specschedulingaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithvaluesmixin)
    * [`obj spec.scheduling.tolerations`](#obj-specschedulingtolerations)
      * [`fn withEffect(effect)`](#fn-specschedulingtolerationswitheffect)
      * [`fn withKey(key)`](#fn-specschedulingtolerationswithkey)
      * [`fn withOperator(operator)`](#fn-specschedulingtolerationswithoperator)
      * [`fn withTolerationSeconds(tolerationSeconds)`](#fn-specschedulingtolerationswithtolerationseconds)
      * [`fn withValue(value)`](#fn-specschedulingtolerationswithvalue)
    * [`obj spec.scheduling.topologySpreadConstraints`](#obj-specschedulingtopologyspreadconstraints)
      * [`fn withMatchLabelKeys(matchLabelKeys)`](#fn-specschedulingtopologyspreadconstraintswithmatchlabelkeys)
      * [`fn withMatchLabelKeysMixin(matchLabelKeys)`](#fn-specschedulingtopologyspreadconstraintswithmatchlabelkeysmixin)
      * [`fn withMaxSkew(maxSkew)`](#fn-specschedulingtopologyspreadconstraintswithmaxskew)
      * [`fn withMinDomains(minDomains)`](#fn-specschedulingtopologyspreadconstraintswithmindomains)
      * [`fn withNodeAffinityPolicy(nodeAffinityPolicy)`](#fn-specschedulingtopologyspreadconstraintswithnodeaffinitypolicy)
      * [`fn withNodeTaintsPolicy(nodeTaintsPolicy)`](#fn-specschedulingtopologyspreadconstraintswithnodetaintspolicy)
      * [`fn withTopologyKey(topologyKey)`](#fn-specschedulingtopologyspreadconstraintswithtopologykey)
      * [`fn withWhenUnsatisfiable(whenUnsatisfiable)`](#fn-specschedulingtopologyspreadconstraintswithwhenunsatisfiable)
      * [`obj spec.scheduling.topologySpreadConstraints.labelSelector`](#obj-specschedulingtopologyspreadconstraintslabelselector)
        * [`fn withMatchExpressions(matchExpressions)`](#fn-specschedulingtopologyspreadconstraintslabelselectorwithmatchexpressions)
        * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specschedulingtopologyspreadconstraintslabelselectorwithmatchexpressionsmixin)
        * [`fn withMatchLabels(matchLabels)`](#fn-specschedulingtopologyspreadconstraintslabelselectorwithmatchlabels)
        * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specschedulingtopologyspreadconstraintslabelselectorwithmatchlabelsmixin)
        * [`obj spec.scheduling.topologySpreadConstraints.labelSelector.matchExpressions`](#obj-specschedulingtopologyspreadconstraintslabelselectormatchexpressions)
          * [`fn withKey(key)`](#fn-specschedulingtopologyspreadconstraintslabelselectormatchexpressionswithkey)
          * [`fn withOperator(operator)`](#fn-specschedulingtopologyspreadconstraintslabelselectormatchexpressionswithoperator)
          * [`fn withValues(values)`](#fn-specschedulingtopologyspreadconstraintslabelselectormatchexpressionswithvalues)
          * [`fn withValuesMixin(values)`](#fn-specschedulingtopologyspreadconstraintslabelselectormatchexpressionswithvaluesmixin)
  * [`obj spec.serviceMonitor`](#obj-specservicemonitor)
    * [`fn withEnabled(enabled)`](#fn-specservicemonitorwithenabled)
    * [`fn withInterval(interval)`](#fn-specservicemonitorwithinterval)
    * [`fn withScrapeTimeout(scrapeTimeout)`](#fn-specservicemonitorwithscrapetimeout)
  * [`obj spec.startupProbe`](#obj-specstartupprobe)
    * [`fn withFailureThreshold(failureThreshold)`](#fn-specstartupprobewithfailurethreshold)
    * [`fn withPeriodSeconds(periodSeconds)`](#fn-specstartupprobewithperiodseconds)
  * [`obj spec.tracing`](#obj-spectracing)
    * [`fn withCompression(compression)`](#fn-spectracingwithcompression)
    * [`fn withEnabled(enabled)`](#fn-spectracingwithenabled)
    * [`fn withEndpoint(endpoint)`](#fn-spectracingwithendpoint)
    * [`fn withProtocol(protocol)`](#fn-spectracingwithprotocol)
    * [`fn withResourceAttributes(resourceAttributes)`](#fn-spectracingwithresourceattributes)
    * [`fn withResourceAttributesMixin(resourceAttributes)`](#fn-spectracingwithresourceattributesmixin)
    * [`fn withSamplerRatio(samplerRatio)`](#fn-spectracingwithsamplerratio)
    * [`fn withSamplerType(samplerType)`](#fn-spectracingwithsamplertype)
    * [`fn withServiceName(serviceName)`](#fn-spectracingwithservicename)
  * [`obj spec.transaction`](#obj-spectransaction)
    * [`fn withXaEnabled(xaEnabled)`](#fn-spectransactionwithxaenabled)
  * [`obj spec.unsupported`](#obj-specunsupported)
    * [`obj spec.unsupported.podTemplate`](#obj-specunsupportedpodtemplate)
      * [`obj spec.unsupported.podTemplate.metadata`](#obj-specunsupportedpodtemplatemetadata)
        * [`fn withAnnotations(annotations)`](#fn-specunsupportedpodtemplatemetadatawithannotations)
        * [`fn withAnnotationsMixin(annotations)`](#fn-specunsupportedpodtemplatemetadatawithannotationsmixin)
        * [`fn withCreationTimestamp(creationTimestamp)`](#fn-specunsupportedpodtemplatemetadatawithcreationtimestamp)
        * [`fn withDeletionGracePeriodSeconds(deletionGracePeriodSeconds)`](#fn-specunsupportedpodtemplatemetadatawithdeletiongraceperiodseconds)
        * [`fn withDeletionTimestamp(deletionTimestamp)`](#fn-specunsupportedpodtemplatemetadatawithdeletiontimestamp)
        * [`fn withFinalizers(finalizers)`](#fn-specunsupportedpodtemplatemetadatawithfinalizers)
        * [`fn withFinalizersMixin(finalizers)`](#fn-specunsupportedpodtemplatemetadatawithfinalizersmixin)
        * [`fn withGenerateName(generateName)`](#fn-specunsupportedpodtemplatemetadatawithgeneratename)
        * [`fn withGeneration(generation)`](#fn-specunsupportedpodtemplatemetadatawithgeneration)
        * [`fn withLabels(labels)`](#fn-specunsupportedpodtemplatemetadatawithlabels)
        * [`fn withLabelsMixin(labels)`](#fn-specunsupportedpodtemplatemetadatawithlabelsmixin)
        * [`fn withManagedFields(managedFields)`](#fn-specunsupportedpodtemplatemetadatawithmanagedfields)
        * [`fn withManagedFieldsMixin(managedFields)`](#fn-specunsupportedpodtemplatemetadatawithmanagedfieldsmixin)
        * [`fn withName(name)`](#fn-specunsupportedpodtemplatemetadatawithname)
        * [`fn withNamespace(namespace)`](#fn-specunsupportedpodtemplatemetadatawithnamespace)
        * [`fn withOwnerReferences(ownerReferences)`](#fn-specunsupportedpodtemplatemetadatawithownerreferences)
        * [`fn withOwnerReferencesMixin(ownerReferences)`](#fn-specunsupportedpodtemplatemetadatawithownerreferencesmixin)
        * [`fn withResourceVersion(resourceVersion)`](#fn-specunsupportedpodtemplatemetadatawithresourceversion)
        * [`fn withSelfLink(selfLink)`](#fn-specunsupportedpodtemplatemetadatawithselflink)
        * [`fn withUid(uid)`](#fn-specunsupportedpodtemplatemetadatawithuid)
        * [`obj spec.unsupported.podTemplate.metadata.managedFields`](#obj-specunsupportedpodtemplatemetadatamanagedfields)
          * [`fn withApiVersion(apiVersion)`](#fn-specunsupportedpodtemplatemetadatamanagedfieldswithapiversion)
          * [`fn withFieldsType(fieldsType)`](#fn-specunsupportedpodtemplatemetadatamanagedfieldswithfieldstype)
          * [`fn withFieldsV1(fieldsV1)`](#fn-specunsupportedpodtemplatemetadatamanagedfieldswithfieldsv1)
          * [`fn withFieldsV1Mixin(fieldsV1)`](#fn-specunsupportedpodtemplatemetadatamanagedfieldswithfieldsv1mixin)
          * [`fn withManager(manager)`](#fn-specunsupportedpodtemplatemetadatamanagedfieldswithmanager)
          * [`fn withOperation(operation)`](#fn-specunsupportedpodtemplatemetadatamanagedfieldswithoperation)
          * [`fn withSubresource(subresource)`](#fn-specunsupportedpodtemplatemetadatamanagedfieldswithsubresource)
          * [`fn withTime(time)`](#fn-specunsupportedpodtemplatemetadatamanagedfieldswithtime)
        * [`obj spec.unsupported.podTemplate.metadata.ownerReferences`](#obj-specunsupportedpodtemplatemetadataownerreferences)
          * [`fn withApiVersion(apiVersion)`](#fn-specunsupportedpodtemplatemetadataownerreferenceswithapiversion)
          * [`fn withBlockOwnerDeletion(blockOwnerDeletion)`](#fn-specunsupportedpodtemplatemetadataownerreferenceswithblockownerdeletion)
          * [`fn withController(controller)`](#fn-specunsupportedpodtemplatemetadataownerreferenceswithcontroller)
          * [`fn withKind(kind)`](#fn-specunsupportedpodtemplatemetadataownerreferenceswithkind)
          * [`fn withName(name)`](#fn-specunsupportedpodtemplatemetadataownerreferenceswithname)
          * [`fn withUid(uid)`](#fn-specunsupportedpodtemplatemetadataownerreferenceswithuid)
      * [`obj spec.unsupported.podTemplate.spec`](#obj-specunsupportedpodtemplatespec)
        * [`fn withActiveDeadlineSeconds(activeDeadlineSeconds)`](#fn-specunsupportedpodtemplatespecwithactivedeadlineseconds)
        * [`fn withAutomountServiceAccountToken(automountServiceAccountToken)`](#fn-specunsupportedpodtemplatespecwithautomountserviceaccounttoken)
        * [`fn withContainers(containers)`](#fn-specunsupportedpodtemplatespecwithcontainers)
        * [`fn withContainersMixin(containers)`](#fn-specunsupportedpodtemplatespecwithcontainersmixin)
        * [`fn withDnsPolicy(dnsPolicy)`](#fn-specunsupportedpodtemplatespecwithdnspolicy)
        * [`fn withEnableServiceLinks(enableServiceLinks)`](#fn-specunsupportedpodtemplatespecwithenableservicelinks)
        * [`fn withEphemeralContainers(ephemeralContainers)`](#fn-specunsupportedpodtemplatespecwithephemeralcontainers)
        * [`fn withEphemeralContainersMixin(ephemeralContainers)`](#fn-specunsupportedpodtemplatespecwithephemeralcontainersmixin)
        * [`fn withHostAliases(hostAliases)`](#fn-specunsupportedpodtemplatespecwithhostaliases)
        * [`fn withHostAliasesMixin(hostAliases)`](#fn-specunsupportedpodtemplatespecwithhostaliasesmixin)
        * [`fn withHostIPC(hostIPC)`](#fn-specunsupportedpodtemplatespecwithhostipc)
        * [`fn withHostNetwork(hostNetwork)`](#fn-specunsupportedpodtemplatespecwithhostnetwork)
        * [`fn withHostPID(hostPID)`](#fn-specunsupportedpodtemplatespecwithhostpid)
        * [`fn withHostUsers(hostUsers)`](#fn-specunsupportedpodtemplatespecwithhostusers)
        * [`fn withHostname(hostname)`](#fn-specunsupportedpodtemplatespecwithhostname)
        * [`fn withImagePullSecrets(imagePullSecrets)`](#fn-specunsupportedpodtemplatespecwithimagepullsecrets)
        * [`fn withImagePullSecretsMixin(imagePullSecrets)`](#fn-specunsupportedpodtemplatespecwithimagepullsecretsmixin)
        * [`fn withInitContainers(initContainers)`](#fn-specunsupportedpodtemplatespecwithinitcontainers)
        * [`fn withInitContainersMixin(initContainers)`](#fn-specunsupportedpodtemplatespecwithinitcontainersmixin)
        * [`fn withNodeName(nodeName)`](#fn-specunsupportedpodtemplatespecwithnodename)
        * [`fn withNodeSelector(nodeSelector)`](#fn-specunsupportedpodtemplatespecwithnodeselector)
        * [`fn withNodeSelectorMixin(nodeSelector)`](#fn-specunsupportedpodtemplatespecwithnodeselectormixin)
        * [`fn withOverhead(overhead)`](#fn-specunsupportedpodtemplatespecwithoverhead)
        * [`fn withOverheadMixin(overhead)`](#fn-specunsupportedpodtemplatespecwithoverheadmixin)
        * [`fn withPreemptionPolicy(preemptionPolicy)`](#fn-specunsupportedpodtemplatespecwithpreemptionpolicy)
        * [`fn withPriority(priority)`](#fn-specunsupportedpodtemplatespecwithpriority)
        * [`fn withPriorityClassName(priorityClassName)`](#fn-specunsupportedpodtemplatespecwithpriorityclassname)
        * [`fn withReadinessGates(readinessGates)`](#fn-specunsupportedpodtemplatespecwithreadinessgates)
        * [`fn withReadinessGatesMixin(readinessGates)`](#fn-specunsupportedpodtemplatespecwithreadinessgatesmixin)
        * [`fn withResourceClaims(resourceClaims)`](#fn-specunsupportedpodtemplatespecwithresourceclaims)
        * [`fn withResourceClaimsMixin(resourceClaims)`](#fn-specunsupportedpodtemplatespecwithresourceclaimsmixin)
        * [`fn withRestartPolicy(restartPolicy)`](#fn-specunsupportedpodtemplatespecwithrestartpolicy)
        * [`fn withRuntimeClassName(runtimeClassName)`](#fn-specunsupportedpodtemplatespecwithruntimeclassname)
        * [`fn withSchedulerName(schedulerName)`](#fn-specunsupportedpodtemplatespecwithschedulername)
        * [`fn withSchedulingGates(schedulingGates)`](#fn-specunsupportedpodtemplatespecwithschedulinggates)
        * [`fn withSchedulingGatesMixin(schedulingGates)`](#fn-specunsupportedpodtemplatespecwithschedulinggatesmixin)
        * [`fn withServiceAccount(serviceAccount)`](#fn-specunsupportedpodtemplatespecwithserviceaccount)
        * [`fn withServiceAccountName(serviceAccountName)`](#fn-specunsupportedpodtemplatespecwithserviceaccountname)
        * [`fn withSetHostnameAsFQDN(setHostnameAsFQDN)`](#fn-specunsupportedpodtemplatespecwithsethostnameasfqdn)
        * [`fn withShareProcessNamespace(shareProcessNamespace)`](#fn-specunsupportedpodtemplatespecwithshareprocessnamespace)
        * [`fn withSubdomain(subdomain)`](#fn-specunsupportedpodtemplatespecwithsubdomain)
        * [`fn withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)`](#fn-specunsupportedpodtemplatespecwithterminationgraceperiodseconds)
        * [`fn withTolerations(tolerations)`](#fn-specunsupportedpodtemplatespecwithtolerations)
        * [`fn withTolerationsMixin(tolerations)`](#fn-specunsupportedpodtemplatespecwithtolerationsmixin)
        * [`fn withTopologySpreadConstraints(topologySpreadConstraints)`](#fn-specunsupportedpodtemplatespecwithtopologyspreadconstraints)
        * [`fn withTopologySpreadConstraintsMixin(topologySpreadConstraints)`](#fn-specunsupportedpodtemplatespecwithtopologyspreadconstraintsmixin)
        * [`fn withVolumes(volumes)`](#fn-specunsupportedpodtemplatespecwithvolumes)
        * [`fn withVolumesMixin(volumes)`](#fn-specunsupportedpodtemplatespecwithvolumesmixin)
        * [`obj spec.unsupported.podTemplate.spec.affinity`](#obj-specunsupportedpodtemplatespecaffinity)
          * [`obj spec.unsupported.podTemplate.spec.affinity.nodeAffinity`](#obj-specunsupportedpodtemplatespecaffinitynodeaffinity)
            * [`fn withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-specunsupportedpodtemplatespecaffinitynodeaffinitywithpreferredduringschedulingignoredduringexecution)
            * [`fn withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-specunsupportedpodtemplatespecaffinitynodeaffinitywithpreferredduringschedulingignoredduringexecutionmixin)
            * [`obj spec.unsupported.podTemplate.spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution`](#obj-specunsupportedpodtemplatespecaffinitynodeaffinitypreferredduringschedulingignoredduringexecution)
              * [`fn withWeight(weight)`](#fn-specunsupportedpodtemplatespecaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionwithweight)
              * [`obj spec.unsupported.podTemplate.spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference`](#obj-specunsupportedpodtemplatespecaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreference)
                * [`fn withMatchExpressions(matchExpressions)`](#fn-specunsupportedpodtemplatespecaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencewithmatchexpressions)
                * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specunsupportedpodtemplatespecaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencewithmatchexpressionsmixin)
                * [`fn withMatchFields(matchFields)`](#fn-specunsupportedpodtemplatespecaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencewithmatchfields)
                * [`fn withMatchFieldsMixin(matchFields)`](#fn-specunsupportedpodtemplatespecaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencewithmatchfieldsmixin)
                * [`obj spec.unsupported.podTemplate.spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions`](#obj-specunsupportedpodtemplatespecaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressions)
                  * [`fn withKey(key)`](#fn-specunsupportedpodtemplatespecaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressionswithkey)
                  * [`fn withOperator(operator)`](#fn-specunsupportedpodtemplatespecaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressionswithoperator)
                  * [`fn withValues(values)`](#fn-specunsupportedpodtemplatespecaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressionswithvalues)
                  * [`fn withValuesMixin(values)`](#fn-specunsupportedpodtemplatespecaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressionswithvaluesmixin)
                * [`obj spec.unsupported.podTemplate.spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields`](#obj-specunsupportedpodtemplatespecaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfields)
                  * [`fn withKey(key)`](#fn-specunsupportedpodtemplatespecaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfieldswithkey)
                  * [`fn withOperator(operator)`](#fn-specunsupportedpodtemplatespecaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfieldswithoperator)
                  * [`fn withValues(values)`](#fn-specunsupportedpodtemplatespecaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfieldswithvalues)
                  * [`fn withValuesMixin(values)`](#fn-specunsupportedpodtemplatespecaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfieldswithvaluesmixin)
            * [`obj spec.unsupported.podTemplate.spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution`](#obj-specunsupportedpodtemplatespecaffinitynodeaffinityrequiredduringschedulingignoredduringexecution)
              * [`fn withNodeSelectorTerms(nodeSelectorTerms)`](#fn-specunsupportedpodtemplatespecaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionwithnodeselectorterms)
              * [`fn withNodeSelectorTermsMixin(nodeSelectorTerms)`](#fn-specunsupportedpodtemplatespecaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionwithnodeselectortermsmixin)
              * [`obj spec.unsupported.podTemplate.spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms`](#obj-specunsupportedpodtemplatespecaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectorterms)
                * [`fn withMatchExpressions(matchExpressions)`](#fn-specunsupportedpodtemplatespecaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermswithmatchexpressions)
                * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specunsupportedpodtemplatespecaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermswithmatchexpressionsmixin)
                * [`fn withMatchFields(matchFields)`](#fn-specunsupportedpodtemplatespecaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermswithmatchfields)
                * [`fn withMatchFieldsMixin(matchFields)`](#fn-specunsupportedpodtemplatespecaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermswithmatchfieldsmixin)
                * [`obj spec.unsupported.podTemplate.spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions`](#obj-specunsupportedpodtemplatespecaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressions)
                  * [`fn withKey(key)`](#fn-specunsupportedpodtemplatespecaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressionswithkey)
                  * [`fn withOperator(operator)`](#fn-specunsupportedpodtemplatespecaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressionswithoperator)
                  * [`fn withValues(values)`](#fn-specunsupportedpodtemplatespecaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressionswithvalues)
                  * [`fn withValuesMixin(values)`](#fn-specunsupportedpodtemplatespecaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressionswithvaluesmixin)
                * [`obj spec.unsupported.podTemplate.spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields`](#obj-specunsupportedpodtemplatespecaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfields)
                  * [`fn withKey(key)`](#fn-specunsupportedpodtemplatespecaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfieldswithkey)
                  * [`fn withOperator(operator)`](#fn-specunsupportedpodtemplatespecaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfieldswithoperator)
                  * [`fn withValues(values)`](#fn-specunsupportedpodtemplatespecaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfieldswithvalues)
                  * [`fn withValuesMixin(values)`](#fn-specunsupportedpodtemplatespecaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfieldswithvaluesmixin)
          * [`obj spec.unsupported.podTemplate.spec.affinity.podAffinity`](#obj-specunsupportedpodtemplatespecaffinitypodaffinity)
            * [`fn withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-specunsupportedpodtemplatespecaffinitypodaffinitywithpreferredduringschedulingignoredduringexecution)
            * [`fn withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-specunsupportedpodtemplatespecaffinitypodaffinitywithpreferredduringschedulingignoredduringexecutionmixin)
            * [`fn withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-specunsupportedpodtemplatespecaffinitypodaffinitywithrequiredduringschedulingignoredduringexecution)
            * [`fn withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-specunsupportedpodtemplatespecaffinitypodaffinitywithrequiredduringschedulingignoredduringexecutionmixin)
            * [`obj spec.unsupported.podTemplate.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution`](#obj-specunsupportedpodtemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecution)
              * [`fn withWeight(weight)`](#fn-specunsupportedpodtemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionwithweight)
              * [`obj spec.unsupported.podTemplate.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm`](#obj-specunsupportedpodtemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinityterm)
                * [`fn withMatchLabelKeys(matchLabelKeys)`](#fn-specunsupportedpodtemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmatchlabelkeys)
                * [`fn withMatchLabelKeysMixin(matchLabelKeys)`](#fn-specunsupportedpodtemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmatchlabelkeysmixin)
                * [`fn withMismatchLabelKeys(mismatchLabelKeys)`](#fn-specunsupportedpodtemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmismatchlabelkeys)
                * [`fn withMismatchLabelKeysMixin(mismatchLabelKeys)`](#fn-specunsupportedpodtemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmismatchlabelkeysmixin)
                * [`fn withNamespaces(namespaces)`](#fn-specunsupportedpodtemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithnamespaces)
                * [`fn withNamespacesMixin(namespaces)`](#fn-specunsupportedpodtemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithnamespacesmixin)
                * [`fn withTopologyKey(topologyKey)`](#fn-specunsupportedpodtemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithtopologykey)
                * [`obj spec.unsupported.podTemplate.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector`](#obj-specunsupportedpodtemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselector)
                  * [`fn withMatchExpressions(matchExpressions)`](#fn-specunsupportedpodtemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchexpressions)
                  * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specunsupportedpodtemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchexpressionsmixin)
                  * [`fn withMatchLabels(matchLabels)`](#fn-specunsupportedpodtemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchlabels)
                  * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specunsupportedpodtemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchlabelsmixin)
                  * [`obj spec.unsupported.podTemplate.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions`](#obj-specunsupportedpodtemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressions)
                    * [`fn withKey(key)`](#fn-specunsupportedpodtemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithkey)
                    * [`fn withOperator(operator)`](#fn-specunsupportedpodtemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithoperator)
                    * [`fn withValues(values)`](#fn-specunsupportedpodtemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithvalues)
                    * [`fn withValuesMixin(values)`](#fn-specunsupportedpodtemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithvaluesmixin)
                * [`obj spec.unsupported.podTemplate.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector`](#obj-specunsupportedpodtemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselector)
                  * [`fn withMatchExpressions(matchExpressions)`](#fn-specunsupportedpodtemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchexpressions)
                  * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specunsupportedpodtemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchexpressionsmixin)
                  * [`fn withMatchLabels(matchLabels)`](#fn-specunsupportedpodtemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchlabels)
                  * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specunsupportedpodtemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchlabelsmixin)
                  * [`obj spec.unsupported.podTemplate.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions`](#obj-specunsupportedpodtemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressions)
                    * [`fn withKey(key)`](#fn-specunsupportedpodtemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithkey)
                    * [`fn withOperator(operator)`](#fn-specunsupportedpodtemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithoperator)
                    * [`fn withValues(values)`](#fn-specunsupportedpodtemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithvalues)
                    * [`fn withValuesMixin(values)`](#fn-specunsupportedpodtemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithvaluesmixin)
            * [`obj spec.unsupported.podTemplate.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution`](#obj-specunsupportedpodtemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecution)
              * [`fn withMatchLabelKeys(matchLabelKeys)`](#fn-specunsupportedpodtemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithmatchlabelkeys)
              * [`fn withMatchLabelKeysMixin(matchLabelKeys)`](#fn-specunsupportedpodtemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithmatchlabelkeysmixin)
              * [`fn withMismatchLabelKeys(mismatchLabelKeys)`](#fn-specunsupportedpodtemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithmismatchlabelkeys)
              * [`fn withMismatchLabelKeysMixin(mismatchLabelKeys)`](#fn-specunsupportedpodtemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithmismatchlabelkeysmixin)
              * [`fn withNamespaces(namespaces)`](#fn-specunsupportedpodtemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithnamespaces)
              * [`fn withNamespacesMixin(namespaces)`](#fn-specunsupportedpodtemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithnamespacesmixin)
              * [`fn withTopologyKey(topologyKey)`](#fn-specunsupportedpodtemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithtopologykey)
              * [`obj spec.unsupported.podTemplate.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector`](#obj-specunsupportedpodtemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselector)
                * [`fn withMatchExpressions(matchExpressions)`](#fn-specunsupportedpodtemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchexpressions)
                * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specunsupportedpodtemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchexpressionsmixin)
                * [`fn withMatchLabels(matchLabels)`](#fn-specunsupportedpodtemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchlabels)
                * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specunsupportedpodtemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchlabelsmixin)
                * [`obj spec.unsupported.podTemplate.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions`](#obj-specunsupportedpodtemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressions)
                  * [`fn withKey(key)`](#fn-specunsupportedpodtemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithkey)
                  * [`fn withOperator(operator)`](#fn-specunsupportedpodtemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithoperator)
                  * [`fn withValues(values)`](#fn-specunsupportedpodtemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithvalues)
                  * [`fn withValuesMixin(values)`](#fn-specunsupportedpodtemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithvaluesmixin)
              * [`obj spec.unsupported.podTemplate.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector`](#obj-specunsupportedpodtemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselector)
                * [`fn withMatchExpressions(matchExpressions)`](#fn-specunsupportedpodtemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchexpressions)
                * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specunsupportedpodtemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchexpressionsmixin)
                * [`fn withMatchLabels(matchLabels)`](#fn-specunsupportedpodtemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchlabels)
                * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specunsupportedpodtemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchlabelsmixin)
                * [`obj spec.unsupported.podTemplate.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions`](#obj-specunsupportedpodtemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressions)
                  * [`fn withKey(key)`](#fn-specunsupportedpodtemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithkey)
                  * [`fn withOperator(operator)`](#fn-specunsupportedpodtemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithoperator)
                  * [`fn withValues(values)`](#fn-specunsupportedpodtemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithvalues)
                  * [`fn withValuesMixin(values)`](#fn-specunsupportedpodtemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithvaluesmixin)
          * [`obj spec.unsupported.podTemplate.spec.affinity.podAntiAffinity`](#obj-specunsupportedpodtemplatespecaffinitypodantiaffinity)
            * [`fn withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-specunsupportedpodtemplatespecaffinitypodantiaffinitywithpreferredduringschedulingignoredduringexecution)
            * [`fn withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-specunsupportedpodtemplatespecaffinitypodantiaffinitywithpreferredduringschedulingignoredduringexecutionmixin)
            * [`fn withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-specunsupportedpodtemplatespecaffinitypodantiaffinitywithrequiredduringschedulingignoredduringexecution)
            * [`fn withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-specunsupportedpodtemplatespecaffinitypodantiaffinitywithrequiredduringschedulingignoredduringexecutionmixin)
            * [`obj spec.unsupported.podTemplate.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution`](#obj-specunsupportedpodtemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecution)
              * [`fn withWeight(weight)`](#fn-specunsupportedpodtemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionwithweight)
              * [`obj spec.unsupported.podTemplate.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm`](#obj-specunsupportedpodtemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinityterm)
                * [`fn withMatchLabelKeys(matchLabelKeys)`](#fn-specunsupportedpodtemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmatchlabelkeys)
                * [`fn withMatchLabelKeysMixin(matchLabelKeys)`](#fn-specunsupportedpodtemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmatchlabelkeysmixin)
                * [`fn withMismatchLabelKeys(mismatchLabelKeys)`](#fn-specunsupportedpodtemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmismatchlabelkeys)
                * [`fn withMismatchLabelKeysMixin(mismatchLabelKeys)`](#fn-specunsupportedpodtemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmismatchlabelkeysmixin)
                * [`fn withNamespaces(namespaces)`](#fn-specunsupportedpodtemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithnamespaces)
                * [`fn withNamespacesMixin(namespaces)`](#fn-specunsupportedpodtemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithnamespacesmixin)
                * [`fn withTopologyKey(topologyKey)`](#fn-specunsupportedpodtemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithtopologykey)
                * [`obj spec.unsupported.podTemplate.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector`](#obj-specunsupportedpodtemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselector)
                  * [`fn withMatchExpressions(matchExpressions)`](#fn-specunsupportedpodtemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchexpressions)
                  * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specunsupportedpodtemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchexpressionsmixin)
                  * [`fn withMatchLabels(matchLabels)`](#fn-specunsupportedpodtemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchlabels)
                  * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specunsupportedpodtemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchlabelsmixin)
                  * [`obj spec.unsupported.podTemplate.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions`](#obj-specunsupportedpodtemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressions)
                    * [`fn withKey(key)`](#fn-specunsupportedpodtemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithkey)
                    * [`fn withOperator(operator)`](#fn-specunsupportedpodtemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithoperator)
                    * [`fn withValues(values)`](#fn-specunsupportedpodtemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithvalues)
                    * [`fn withValuesMixin(values)`](#fn-specunsupportedpodtemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithvaluesmixin)
                * [`obj spec.unsupported.podTemplate.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector`](#obj-specunsupportedpodtemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselector)
                  * [`fn withMatchExpressions(matchExpressions)`](#fn-specunsupportedpodtemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchexpressions)
                  * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specunsupportedpodtemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchexpressionsmixin)
                  * [`fn withMatchLabels(matchLabels)`](#fn-specunsupportedpodtemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchlabels)
                  * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specunsupportedpodtemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchlabelsmixin)
                  * [`obj spec.unsupported.podTemplate.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions`](#obj-specunsupportedpodtemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressions)
                    * [`fn withKey(key)`](#fn-specunsupportedpodtemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithkey)
                    * [`fn withOperator(operator)`](#fn-specunsupportedpodtemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithoperator)
                    * [`fn withValues(values)`](#fn-specunsupportedpodtemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithvalues)
                    * [`fn withValuesMixin(values)`](#fn-specunsupportedpodtemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithvaluesmixin)
            * [`obj spec.unsupported.podTemplate.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution`](#obj-specunsupportedpodtemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecution)
              * [`fn withMatchLabelKeys(matchLabelKeys)`](#fn-specunsupportedpodtemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithmatchlabelkeys)
              * [`fn withMatchLabelKeysMixin(matchLabelKeys)`](#fn-specunsupportedpodtemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithmatchlabelkeysmixin)
              * [`fn withMismatchLabelKeys(mismatchLabelKeys)`](#fn-specunsupportedpodtemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithmismatchlabelkeys)
              * [`fn withMismatchLabelKeysMixin(mismatchLabelKeys)`](#fn-specunsupportedpodtemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithmismatchlabelkeysmixin)
              * [`fn withNamespaces(namespaces)`](#fn-specunsupportedpodtemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithnamespaces)
              * [`fn withNamespacesMixin(namespaces)`](#fn-specunsupportedpodtemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithnamespacesmixin)
              * [`fn withTopologyKey(topologyKey)`](#fn-specunsupportedpodtemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithtopologykey)
              * [`obj spec.unsupported.podTemplate.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector`](#obj-specunsupportedpodtemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselector)
                * [`fn withMatchExpressions(matchExpressions)`](#fn-specunsupportedpodtemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchexpressions)
                * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specunsupportedpodtemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchexpressionsmixin)
                * [`fn withMatchLabels(matchLabels)`](#fn-specunsupportedpodtemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchlabels)
                * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specunsupportedpodtemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchlabelsmixin)
                * [`obj spec.unsupported.podTemplate.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions`](#obj-specunsupportedpodtemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressions)
                  * [`fn withKey(key)`](#fn-specunsupportedpodtemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithkey)
                  * [`fn withOperator(operator)`](#fn-specunsupportedpodtemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithoperator)
                  * [`fn withValues(values)`](#fn-specunsupportedpodtemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithvalues)
                  * [`fn withValuesMixin(values)`](#fn-specunsupportedpodtemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithvaluesmixin)
              * [`obj spec.unsupported.podTemplate.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector`](#obj-specunsupportedpodtemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselector)
                * [`fn withMatchExpressions(matchExpressions)`](#fn-specunsupportedpodtemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchexpressions)
                * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specunsupportedpodtemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchexpressionsmixin)
                * [`fn withMatchLabels(matchLabels)`](#fn-specunsupportedpodtemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchlabels)
                * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specunsupportedpodtemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchlabelsmixin)
                * [`obj spec.unsupported.podTemplate.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions`](#obj-specunsupportedpodtemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressions)
                  * [`fn withKey(key)`](#fn-specunsupportedpodtemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithkey)
                  * [`fn withOperator(operator)`](#fn-specunsupportedpodtemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithoperator)
                  * [`fn withValues(values)`](#fn-specunsupportedpodtemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithvalues)
                  * [`fn withValuesMixin(values)`](#fn-specunsupportedpodtemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithvaluesmixin)
        * [`obj spec.unsupported.podTemplate.spec.containers`](#obj-specunsupportedpodtemplatespeccontainers)
          * [`fn withArgs(args)`](#fn-specunsupportedpodtemplatespeccontainerswithargs)
          * [`fn withArgsMixin(args)`](#fn-specunsupportedpodtemplatespeccontainerswithargsmixin)
          * [`fn withCommand(command)`](#fn-specunsupportedpodtemplatespeccontainerswithcommand)
          * [`fn withCommandMixin(command)`](#fn-specunsupportedpodtemplatespeccontainerswithcommandmixin)
          * [`fn withEnv(env)`](#fn-specunsupportedpodtemplatespeccontainerswithenv)
          * [`fn withEnvFrom(envFrom)`](#fn-specunsupportedpodtemplatespeccontainerswithenvfrom)
          * [`fn withEnvFromMixin(envFrom)`](#fn-specunsupportedpodtemplatespeccontainerswithenvfrommixin)
          * [`fn withEnvMixin(env)`](#fn-specunsupportedpodtemplatespeccontainerswithenvmixin)
          * [`fn withImage(image)`](#fn-specunsupportedpodtemplatespeccontainerswithimage)
          * [`fn withImagePullPolicy(imagePullPolicy)`](#fn-specunsupportedpodtemplatespeccontainerswithimagepullpolicy)
          * [`fn withName(name)`](#fn-specunsupportedpodtemplatespeccontainerswithname)
          * [`fn withPorts(ports)`](#fn-specunsupportedpodtemplatespeccontainerswithports)
          * [`fn withPortsMixin(ports)`](#fn-specunsupportedpodtemplatespeccontainerswithportsmixin)
          * [`fn withResizePolicy(resizePolicy)`](#fn-specunsupportedpodtemplatespeccontainerswithresizepolicy)
          * [`fn withResizePolicyMixin(resizePolicy)`](#fn-specunsupportedpodtemplatespeccontainerswithresizepolicymixin)
          * [`fn withRestartPolicy(restartPolicy)`](#fn-specunsupportedpodtemplatespeccontainerswithrestartpolicy)
          * [`fn withStdin(stdin)`](#fn-specunsupportedpodtemplatespeccontainerswithstdin)
          * [`fn withStdinOnce(stdinOnce)`](#fn-specunsupportedpodtemplatespeccontainerswithstdinonce)
          * [`fn withTerminationMessagePath(terminationMessagePath)`](#fn-specunsupportedpodtemplatespeccontainerswithterminationmessagepath)
          * [`fn withTerminationMessagePolicy(terminationMessagePolicy)`](#fn-specunsupportedpodtemplatespeccontainerswithterminationmessagepolicy)
          * [`fn withTty(tty)`](#fn-specunsupportedpodtemplatespeccontainerswithtty)
          * [`fn withVolumeDevices(volumeDevices)`](#fn-specunsupportedpodtemplatespeccontainerswithvolumedevices)
          * [`fn withVolumeDevicesMixin(volumeDevices)`](#fn-specunsupportedpodtemplatespeccontainerswithvolumedevicesmixin)
          * [`fn withVolumeMounts(volumeMounts)`](#fn-specunsupportedpodtemplatespeccontainerswithvolumemounts)
          * [`fn withVolumeMountsMixin(volumeMounts)`](#fn-specunsupportedpodtemplatespeccontainerswithvolumemountsmixin)
          * [`fn withWorkingDir(workingDir)`](#fn-specunsupportedpodtemplatespeccontainerswithworkingdir)
          * [`obj spec.unsupported.podTemplate.spec.containers.env`](#obj-specunsupportedpodtemplatespeccontainersenv)
            * [`fn withName(name)`](#fn-specunsupportedpodtemplatespeccontainersenvwithname)
            * [`fn withValue(value)`](#fn-specunsupportedpodtemplatespeccontainersenvwithvalue)
            * [`obj spec.unsupported.podTemplate.spec.containers.env.valueFrom`](#obj-specunsupportedpodtemplatespeccontainersenvvaluefrom)
              * [`obj spec.unsupported.podTemplate.spec.containers.env.valueFrom.configMapKeyRef`](#obj-specunsupportedpodtemplatespeccontainersenvvaluefromconfigmapkeyref)
                * [`fn withKey(key)`](#fn-specunsupportedpodtemplatespeccontainersenvvaluefromconfigmapkeyrefwithkey)
                * [`fn withName(name)`](#fn-specunsupportedpodtemplatespeccontainersenvvaluefromconfigmapkeyrefwithname)
                * [`fn withOptional(optional)`](#fn-specunsupportedpodtemplatespeccontainersenvvaluefromconfigmapkeyrefwithoptional)
              * [`obj spec.unsupported.podTemplate.spec.containers.env.valueFrom.fieldRef`](#obj-specunsupportedpodtemplatespeccontainersenvvaluefromfieldref)
                * [`fn withApiVersion(apiVersion)`](#fn-specunsupportedpodtemplatespeccontainersenvvaluefromfieldrefwithapiversion)
                * [`fn withFieldPath(fieldPath)`](#fn-specunsupportedpodtemplatespeccontainersenvvaluefromfieldrefwithfieldpath)
              * [`obj spec.unsupported.podTemplate.spec.containers.env.valueFrom.resourceFieldRef`](#obj-specunsupportedpodtemplatespeccontainersenvvaluefromresourcefieldref)
                * [`fn withContainerName(containerName)`](#fn-specunsupportedpodtemplatespeccontainersenvvaluefromresourcefieldrefwithcontainername)
                * [`fn withDivisor(divisor)`](#fn-specunsupportedpodtemplatespeccontainersenvvaluefromresourcefieldrefwithdivisor)
                * [`fn withResource(resource)`](#fn-specunsupportedpodtemplatespeccontainersenvvaluefromresourcefieldrefwithresource)
              * [`obj spec.unsupported.podTemplate.spec.containers.env.valueFrom.secretKeyRef`](#obj-specunsupportedpodtemplatespeccontainersenvvaluefromsecretkeyref)
                * [`fn withKey(key)`](#fn-specunsupportedpodtemplatespeccontainersenvvaluefromsecretkeyrefwithkey)
                * [`fn withName(name)`](#fn-specunsupportedpodtemplatespeccontainersenvvaluefromsecretkeyrefwithname)
                * [`fn withOptional(optional)`](#fn-specunsupportedpodtemplatespeccontainersenvvaluefromsecretkeyrefwithoptional)
          * [`obj spec.unsupported.podTemplate.spec.containers.envFrom`](#obj-specunsupportedpodtemplatespeccontainersenvfrom)
            * [`fn withPrefix(prefix)`](#fn-specunsupportedpodtemplatespeccontainersenvfromwithprefix)
            * [`obj spec.unsupported.podTemplate.spec.containers.envFrom.configMapRef`](#obj-specunsupportedpodtemplatespeccontainersenvfromconfigmapref)
              * [`fn withName(name)`](#fn-specunsupportedpodtemplatespeccontainersenvfromconfigmaprefwithname)
              * [`fn withOptional(optional)`](#fn-specunsupportedpodtemplatespeccontainersenvfromconfigmaprefwithoptional)
            * [`obj spec.unsupported.podTemplate.spec.containers.envFrom.secretRef`](#obj-specunsupportedpodtemplatespeccontainersenvfromsecretref)
              * [`fn withName(name)`](#fn-specunsupportedpodtemplatespeccontainersenvfromsecretrefwithname)
              * [`fn withOptional(optional)`](#fn-specunsupportedpodtemplatespeccontainersenvfromsecretrefwithoptional)
          * [`obj spec.unsupported.podTemplate.spec.containers.lifecycle`](#obj-specunsupportedpodtemplatespeccontainerslifecycle)
            * [`fn withStopSignal(stopSignal)`](#fn-specunsupportedpodtemplatespeccontainerslifecyclewithstopsignal)
            * [`obj spec.unsupported.podTemplate.spec.containers.lifecycle.postStart`](#obj-specunsupportedpodtemplatespeccontainerslifecyclepoststart)
              * [`obj spec.unsupported.podTemplate.spec.containers.lifecycle.postStart.exec`](#obj-specunsupportedpodtemplatespeccontainerslifecyclepoststartexec)
                * [`fn withCommand(command)`](#fn-specunsupportedpodtemplatespeccontainerslifecyclepoststartexecwithcommand)
                * [`fn withCommandMixin(command)`](#fn-specunsupportedpodtemplatespeccontainerslifecyclepoststartexecwithcommandmixin)
              * [`obj spec.unsupported.podTemplate.spec.containers.lifecycle.postStart.httpGet`](#obj-specunsupportedpodtemplatespeccontainerslifecyclepoststarthttpget)
                * [`fn withHost(host)`](#fn-specunsupportedpodtemplatespeccontainerslifecyclepoststarthttpgetwithhost)
                * [`fn withHttpHeaders(httpHeaders)`](#fn-specunsupportedpodtemplatespeccontainerslifecyclepoststarthttpgetwithhttpheaders)
                * [`fn withHttpHeadersMixin(httpHeaders)`](#fn-specunsupportedpodtemplatespeccontainerslifecyclepoststarthttpgetwithhttpheadersmixin)
                * [`fn withPath(path)`](#fn-specunsupportedpodtemplatespeccontainerslifecyclepoststarthttpgetwithpath)
                * [`fn withPort(port)`](#fn-specunsupportedpodtemplatespeccontainerslifecyclepoststarthttpgetwithport)
                * [`fn withScheme(scheme)`](#fn-specunsupportedpodtemplatespeccontainerslifecyclepoststarthttpgetwithscheme)
                * [`obj spec.unsupported.podTemplate.spec.containers.lifecycle.postStart.httpGet.httpHeaders`](#obj-specunsupportedpodtemplatespeccontainerslifecyclepoststarthttpgethttpheaders)
                  * [`fn withName(name)`](#fn-specunsupportedpodtemplatespeccontainerslifecyclepoststarthttpgethttpheaderswithname)
                  * [`fn withValue(value)`](#fn-specunsupportedpodtemplatespeccontainerslifecyclepoststarthttpgethttpheaderswithvalue)
              * [`obj spec.unsupported.podTemplate.spec.containers.lifecycle.postStart.sleep`](#obj-specunsupportedpodtemplatespeccontainerslifecyclepoststartsleep)
                * [`fn withSeconds(seconds)`](#fn-specunsupportedpodtemplatespeccontainerslifecyclepoststartsleepwithseconds)
              * [`obj spec.unsupported.podTemplate.spec.containers.lifecycle.postStart.tcpSocket`](#obj-specunsupportedpodtemplatespeccontainerslifecyclepoststarttcpsocket)
                * [`fn withHost(host)`](#fn-specunsupportedpodtemplatespeccontainerslifecyclepoststarttcpsocketwithhost)
                * [`fn withPort(port)`](#fn-specunsupportedpodtemplatespeccontainerslifecyclepoststarttcpsocketwithport)
            * [`obj spec.unsupported.podTemplate.spec.containers.lifecycle.preStop`](#obj-specunsupportedpodtemplatespeccontainerslifecycleprestop)
              * [`obj spec.unsupported.podTemplate.spec.containers.lifecycle.preStop.exec`](#obj-specunsupportedpodtemplatespeccontainerslifecycleprestopexec)
                * [`fn withCommand(command)`](#fn-specunsupportedpodtemplatespeccontainerslifecycleprestopexecwithcommand)
                * [`fn withCommandMixin(command)`](#fn-specunsupportedpodtemplatespeccontainerslifecycleprestopexecwithcommandmixin)
              * [`obj spec.unsupported.podTemplate.spec.containers.lifecycle.preStop.httpGet`](#obj-specunsupportedpodtemplatespeccontainerslifecycleprestophttpget)
                * [`fn withHost(host)`](#fn-specunsupportedpodtemplatespeccontainerslifecycleprestophttpgetwithhost)
                * [`fn withHttpHeaders(httpHeaders)`](#fn-specunsupportedpodtemplatespeccontainerslifecycleprestophttpgetwithhttpheaders)
                * [`fn withHttpHeadersMixin(httpHeaders)`](#fn-specunsupportedpodtemplatespeccontainerslifecycleprestophttpgetwithhttpheadersmixin)
                * [`fn withPath(path)`](#fn-specunsupportedpodtemplatespeccontainerslifecycleprestophttpgetwithpath)
                * [`fn withPort(port)`](#fn-specunsupportedpodtemplatespeccontainerslifecycleprestophttpgetwithport)
                * [`fn withScheme(scheme)`](#fn-specunsupportedpodtemplatespeccontainerslifecycleprestophttpgetwithscheme)
                * [`obj spec.unsupported.podTemplate.spec.containers.lifecycle.preStop.httpGet.httpHeaders`](#obj-specunsupportedpodtemplatespeccontainerslifecycleprestophttpgethttpheaders)
                  * [`fn withName(name)`](#fn-specunsupportedpodtemplatespeccontainerslifecycleprestophttpgethttpheaderswithname)
                  * [`fn withValue(value)`](#fn-specunsupportedpodtemplatespeccontainerslifecycleprestophttpgethttpheaderswithvalue)
              * [`obj spec.unsupported.podTemplate.spec.containers.lifecycle.preStop.sleep`](#obj-specunsupportedpodtemplatespeccontainerslifecycleprestopsleep)
                * [`fn withSeconds(seconds)`](#fn-specunsupportedpodtemplatespeccontainerslifecycleprestopsleepwithseconds)
              * [`obj spec.unsupported.podTemplate.spec.containers.lifecycle.preStop.tcpSocket`](#obj-specunsupportedpodtemplatespeccontainerslifecycleprestoptcpsocket)
                * [`fn withHost(host)`](#fn-specunsupportedpodtemplatespeccontainerslifecycleprestoptcpsocketwithhost)
                * [`fn withPort(port)`](#fn-specunsupportedpodtemplatespeccontainerslifecycleprestoptcpsocketwithport)
          * [`obj spec.unsupported.podTemplate.spec.containers.livenessProbe`](#obj-specunsupportedpodtemplatespeccontainerslivenessprobe)
            * [`fn withFailureThreshold(failureThreshold)`](#fn-specunsupportedpodtemplatespeccontainerslivenessprobewithfailurethreshold)
            * [`fn withInitialDelaySeconds(initialDelaySeconds)`](#fn-specunsupportedpodtemplatespeccontainerslivenessprobewithinitialdelayseconds)
            * [`fn withPeriodSeconds(periodSeconds)`](#fn-specunsupportedpodtemplatespeccontainerslivenessprobewithperiodseconds)
            * [`fn withSuccessThreshold(successThreshold)`](#fn-specunsupportedpodtemplatespeccontainerslivenessprobewithsuccessthreshold)
            * [`fn withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)`](#fn-specunsupportedpodtemplatespeccontainerslivenessprobewithterminationgraceperiodseconds)
            * [`fn withTimeoutSeconds(timeoutSeconds)`](#fn-specunsupportedpodtemplatespeccontainerslivenessprobewithtimeoutseconds)
            * [`obj spec.unsupported.podTemplate.spec.containers.livenessProbe.exec`](#obj-specunsupportedpodtemplatespeccontainerslivenessprobeexec)
              * [`fn withCommand(command)`](#fn-specunsupportedpodtemplatespeccontainerslivenessprobeexecwithcommand)
              * [`fn withCommandMixin(command)`](#fn-specunsupportedpodtemplatespeccontainerslivenessprobeexecwithcommandmixin)
            * [`obj spec.unsupported.podTemplate.spec.containers.livenessProbe.grpc`](#obj-specunsupportedpodtemplatespeccontainerslivenessprobegrpc)
              * [`fn withPort(port)`](#fn-specunsupportedpodtemplatespeccontainerslivenessprobegrpcwithport)
              * [`fn withService(service)`](#fn-specunsupportedpodtemplatespeccontainerslivenessprobegrpcwithservice)
            * [`obj spec.unsupported.podTemplate.spec.containers.livenessProbe.httpGet`](#obj-specunsupportedpodtemplatespeccontainerslivenessprobehttpget)
              * [`fn withHost(host)`](#fn-specunsupportedpodtemplatespeccontainerslivenessprobehttpgetwithhost)
              * [`fn withHttpHeaders(httpHeaders)`](#fn-specunsupportedpodtemplatespeccontainerslivenessprobehttpgetwithhttpheaders)
              * [`fn withHttpHeadersMixin(httpHeaders)`](#fn-specunsupportedpodtemplatespeccontainerslivenessprobehttpgetwithhttpheadersmixin)
              * [`fn withPath(path)`](#fn-specunsupportedpodtemplatespeccontainerslivenessprobehttpgetwithpath)
              * [`fn withPort(port)`](#fn-specunsupportedpodtemplatespeccontainerslivenessprobehttpgetwithport)
              * [`fn withScheme(scheme)`](#fn-specunsupportedpodtemplatespeccontainerslivenessprobehttpgetwithscheme)
              * [`obj spec.unsupported.podTemplate.spec.containers.livenessProbe.httpGet.httpHeaders`](#obj-specunsupportedpodtemplatespeccontainerslivenessprobehttpgethttpheaders)
                * [`fn withName(name)`](#fn-specunsupportedpodtemplatespeccontainerslivenessprobehttpgethttpheaderswithname)
                * [`fn withValue(value)`](#fn-specunsupportedpodtemplatespeccontainerslivenessprobehttpgethttpheaderswithvalue)
            * [`obj spec.unsupported.podTemplate.spec.containers.livenessProbe.tcpSocket`](#obj-specunsupportedpodtemplatespeccontainerslivenessprobetcpsocket)
              * [`fn withHost(host)`](#fn-specunsupportedpodtemplatespeccontainerslivenessprobetcpsocketwithhost)
              * [`fn withPort(port)`](#fn-specunsupportedpodtemplatespeccontainerslivenessprobetcpsocketwithport)
          * [`obj spec.unsupported.podTemplate.spec.containers.ports`](#obj-specunsupportedpodtemplatespeccontainersports)
            * [`fn withContainerPort(containerPort)`](#fn-specunsupportedpodtemplatespeccontainersportswithcontainerport)
            * [`fn withHostIP(hostIP)`](#fn-specunsupportedpodtemplatespeccontainersportswithhostip)
            * [`fn withHostPort(hostPort)`](#fn-specunsupportedpodtemplatespeccontainersportswithhostport)
            * [`fn withName(name)`](#fn-specunsupportedpodtemplatespeccontainersportswithname)
            * [`fn withProtocol(protocol)`](#fn-specunsupportedpodtemplatespeccontainersportswithprotocol)
          * [`obj spec.unsupported.podTemplate.spec.containers.readinessProbe`](#obj-specunsupportedpodtemplatespeccontainersreadinessprobe)
            * [`fn withFailureThreshold(failureThreshold)`](#fn-specunsupportedpodtemplatespeccontainersreadinessprobewithfailurethreshold)
            * [`fn withInitialDelaySeconds(initialDelaySeconds)`](#fn-specunsupportedpodtemplatespeccontainersreadinessprobewithinitialdelayseconds)
            * [`fn withPeriodSeconds(periodSeconds)`](#fn-specunsupportedpodtemplatespeccontainersreadinessprobewithperiodseconds)
            * [`fn withSuccessThreshold(successThreshold)`](#fn-specunsupportedpodtemplatespeccontainersreadinessprobewithsuccessthreshold)
            * [`fn withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)`](#fn-specunsupportedpodtemplatespeccontainersreadinessprobewithterminationgraceperiodseconds)
            * [`fn withTimeoutSeconds(timeoutSeconds)`](#fn-specunsupportedpodtemplatespeccontainersreadinessprobewithtimeoutseconds)
            * [`obj spec.unsupported.podTemplate.spec.containers.readinessProbe.exec`](#obj-specunsupportedpodtemplatespeccontainersreadinessprobeexec)
              * [`fn withCommand(command)`](#fn-specunsupportedpodtemplatespeccontainersreadinessprobeexecwithcommand)
              * [`fn withCommandMixin(command)`](#fn-specunsupportedpodtemplatespeccontainersreadinessprobeexecwithcommandmixin)
            * [`obj spec.unsupported.podTemplate.spec.containers.readinessProbe.grpc`](#obj-specunsupportedpodtemplatespeccontainersreadinessprobegrpc)
              * [`fn withPort(port)`](#fn-specunsupportedpodtemplatespeccontainersreadinessprobegrpcwithport)
              * [`fn withService(service)`](#fn-specunsupportedpodtemplatespeccontainersreadinessprobegrpcwithservice)
            * [`obj spec.unsupported.podTemplate.spec.containers.readinessProbe.httpGet`](#obj-specunsupportedpodtemplatespeccontainersreadinessprobehttpget)
              * [`fn withHost(host)`](#fn-specunsupportedpodtemplatespeccontainersreadinessprobehttpgetwithhost)
              * [`fn withHttpHeaders(httpHeaders)`](#fn-specunsupportedpodtemplatespeccontainersreadinessprobehttpgetwithhttpheaders)
              * [`fn withHttpHeadersMixin(httpHeaders)`](#fn-specunsupportedpodtemplatespeccontainersreadinessprobehttpgetwithhttpheadersmixin)
              * [`fn withPath(path)`](#fn-specunsupportedpodtemplatespeccontainersreadinessprobehttpgetwithpath)
              * [`fn withPort(port)`](#fn-specunsupportedpodtemplatespeccontainersreadinessprobehttpgetwithport)
              * [`fn withScheme(scheme)`](#fn-specunsupportedpodtemplatespeccontainersreadinessprobehttpgetwithscheme)
              * [`obj spec.unsupported.podTemplate.spec.containers.readinessProbe.httpGet.httpHeaders`](#obj-specunsupportedpodtemplatespeccontainersreadinessprobehttpgethttpheaders)
                * [`fn withName(name)`](#fn-specunsupportedpodtemplatespeccontainersreadinessprobehttpgethttpheaderswithname)
                * [`fn withValue(value)`](#fn-specunsupportedpodtemplatespeccontainersreadinessprobehttpgethttpheaderswithvalue)
            * [`obj spec.unsupported.podTemplate.spec.containers.readinessProbe.tcpSocket`](#obj-specunsupportedpodtemplatespeccontainersreadinessprobetcpsocket)
              * [`fn withHost(host)`](#fn-specunsupportedpodtemplatespeccontainersreadinessprobetcpsocketwithhost)
              * [`fn withPort(port)`](#fn-specunsupportedpodtemplatespeccontainersreadinessprobetcpsocketwithport)
          * [`obj spec.unsupported.podTemplate.spec.containers.resizePolicy`](#obj-specunsupportedpodtemplatespeccontainersresizepolicy)
            * [`fn withResourceName(resourceName)`](#fn-specunsupportedpodtemplatespeccontainersresizepolicywithresourcename)
            * [`fn withRestartPolicy(restartPolicy)`](#fn-specunsupportedpodtemplatespeccontainersresizepolicywithrestartpolicy)
          * [`obj spec.unsupported.podTemplate.spec.containers.resources`](#obj-specunsupportedpodtemplatespeccontainersresources)
            * [`fn withClaims(claims)`](#fn-specunsupportedpodtemplatespeccontainersresourceswithclaims)
            * [`fn withClaimsMixin(claims)`](#fn-specunsupportedpodtemplatespeccontainersresourceswithclaimsmixin)
            * [`fn withLimits(limits)`](#fn-specunsupportedpodtemplatespeccontainersresourceswithlimits)
            * [`fn withLimitsMixin(limits)`](#fn-specunsupportedpodtemplatespeccontainersresourceswithlimitsmixin)
            * [`fn withRequests(requests)`](#fn-specunsupportedpodtemplatespeccontainersresourceswithrequests)
            * [`fn withRequestsMixin(requests)`](#fn-specunsupportedpodtemplatespeccontainersresourceswithrequestsmixin)
            * [`obj spec.unsupported.podTemplate.spec.containers.resources.claims`](#obj-specunsupportedpodtemplatespeccontainersresourcesclaims)
              * [`fn withName(name)`](#fn-specunsupportedpodtemplatespeccontainersresourcesclaimswithname)
              * [`fn withRequest(request)`](#fn-specunsupportedpodtemplatespeccontainersresourcesclaimswithrequest)
          * [`obj spec.unsupported.podTemplate.spec.containers.securityContext`](#obj-specunsupportedpodtemplatespeccontainerssecuritycontext)
            * [`fn withAllowPrivilegeEscalation(allowPrivilegeEscalation)`](#fn-specunsupportedpodtemplatespeccontainerssecuritycontextwithallowprivilegeescalation)
            * [`fn withPrivileged(privileged)`](#fn-specunsupportedpodtemplatespeccontainerssecuritycontextwithprivileged)
            * [`fn withProcMount(procMount)`](#fn-specunsupportedpodtemplatespeccontainerssecuritycontextwithprocmount)
            * [`fn withReadOnlyRootFilesystem(readOnlyRootFilesystem)`](#fn-specunsupportedpodtemplatespeccontainerssecuritycontextwithreadonlyrootfilesystem)
            * [`fn withRunAsGroup(runAsGroup)`](#fn-specunsupportedpodtemplatespeccontainerssecuritycontextwithrunasgroup)
            * [`fn withRunAsNonRoot(runAsNonRoot)`](#fn-specunsupportedpodtemplatespeccontainerssecuritycontextwithrunasnonroot)
            * [`fn withRunAsUser(runAsUser)`](#fn-specunsupportedpodtemplatespeccontainerssecuritycontextwithrunasuser)
            * [`obj spec.unsupported.podTemplate.spec.containers.securityContext.appArmorProfile`](#obj-specunsupportedpodtemplatespeccontainerssecuritycontextapparmorprofile)
              * [`fn withLocalhostProfile(localhostProfile)`](#fn-specunsupportedpodtemplatespeccontainerssecuritycontextapparmorprofilewithlocalhostprofile)
              * [`fn withType(type)`](#fn-specunsupportedpodtemplatespeccontainerssecuritycontextapparmorprofilewithtype)
            * [`obj spec.unsupported.podTemplate.spec.containers.securityContext.capabilities`](#obj-specunsupportedpodtemplatespeccontainerssecuritycontextcapabilities)
              * [`fn withAdd(add)`](#fn-specunsupportedpodtemplatespeccontainerssecuritycontextcapabilitieswithadd)
              * [`fn withAddMixin(add)`](#fn-specunsupportedpodtemplatespeccontainerssecuritycontextcapabilitieswithaddmixin)
              * [`fn withDrop(drop)`](#fn-specunsupportedpodtemplatespeccontainerssecuritycontextcapabilitieswithdrop)
              * [`fn withDropMixin(drop)`](#fn-specunsupportedpodtemplatespeccontainerssecuritycontextcapabilitieswithdropmixin)
            * [`obj spec.unsupported.podTemplate.spec.containers.securityContext.seLinuxOptions`](#obj-specunsupportedpodtemplatespeccontainerssecuritycontextselinuxoptions)
              * [`fn withLevel(level)`](#fn-specunsupportedpodtemplatespeccontainerssecuritycontextselinuxoptionswithlevel)
              * [`fn withRole(role)`](#fn-specunsupportedpodtemplatespeccontainerssecuritycontextselinuxoptionswithrole)
              * [`fn withType(type)`](#fn-specunsupportedpodtemplatespeccontainerssecuritycontextselinuxoptionswithtype)
              * [`fn withUser(user)`](#fn-specunsupportedpodtemplatespeccontainerssecuritycontextselinuxoptionswithuser)
            * [`obj spec.unsupported.podTemplate.spec.containers.securityContext.seccompProfile`](#obj-specunsupportedpodtemplatespeccontainerssecuritycontextseccompprofile)
              * [`fn withLocalhostProfile(localhostProfile)`](#fn-specunsupportedpodtemplatespeccontainerssecuritycontextseccompprofilewithlocalhostprofile)
              * [`fn withType(type)`](#fn-specunsupportedpodtemplatespeccontainerssecuritycontextseccompprofilewithtype)
            * [`obj spec.unsupported.podTemplate.spec.containers.securityContext.windowsOptions`](#obj-specunsupportedpodtemplatespeccontainerssecuritycontextwindowsoptions)
              * [`fn withGmsaCredentialSpec(gmsaCredentialSpec)`](#fn-specunsupportedpodtemplatespeccontainerssecuritycontextwindowsoptionswithgmsacredentialspec)
              * [`fn withGmsaCredentialSpecName(gmsaCredentialSpecName)`](#fn-specunsupportedpodtemplatespeccontainerssecuritycontextwindowsoptionswithgmsacredentialspecname)
              * [`fn withHostProcess(hostProcess)`](#fn-specunsupportedpodtemplatespeccontainerssecuritycontextwindowsoptionswithhostprocess)
              * [`fn withRunAsUserName(runAsUserName)`](#fn-specunsupportedpodtemplatespeccontainerssecuritycontextwindowsoptionswithrunasusername)
          * [`obj spec.unsupported.podTemplate.spec.containers.startupProbe`](#obj-specunsupportedpodtemplatespeccontainersstartupprobe)
            * [`fn withFailureThreshold(failureThreshold)`](#fn-specunsupportedpodtemplatespeccontainersstartupprobewithfailurethreshold)
            * [`fn withInitialDelaySeconds(initialDelaySeconds)`](#fn-specunsupportedpodtemplatespeccontainersstartupprobewithinitialdelayseconds)
            * [`fn withPeriodSeconds(periodSeconds)`](#fn-specunsupportedpodtemplatespeccontainersstartupprobewithperiodseconds)
            * [`fn withSuccessThreshold(successThreshold)`](#fn-specunsupportedpodtemplatespeccontainersstartupprobewithsuccessthreshold)
            * [`fn withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)`](#fn-specunsupportedpodtemplatespeccontainersstartupprobewithterminationgraceperiodseconds)
            * [`fn withTimeoutSeconds(timeoutSeconds)`](#fn-specunsupportedpodtemplatespeccontainersstartupprobewithtimeoutseconds)
            * [`obj spec.unsupported.podTemplate.spec.containers.startupProbe.exec`](#obj-specunsupportedpodtemplatespeccontainersstartupprobeexec)
              * [`fn withCommand(command)`](#fn-specunsupportedpodtemplatespeccontainersstartupprobeexecwithcommand)
              * [`fn withCommandMixin(command)`](#fn-specunsupportedpodtemplatespeccontainersstartupprobeexecwithcommandmixin)
            * [`obj spec.unsupported.podTemplate.spec.containers.startupProbe.grpc`](#obj-specunsupportedpodtemplatespeccontainersstartupprobegrpc)
              * [`fn withPort(port)`](#fn-specunsupportedpodtemplatespeccontainersstartupprobegrpcwithport)
              * [`fn withService(service)`](#fn-specunsupportedpodtemplatespeccontainersstartupprobegrpcwithservice)
            * [`obj spec.unsupported.podTemplate.spec.containers.startupProbe.httpGet`](#obj-specunsupportedpodtemplatespeccontainersstartupprobehttpget)
              * [`fn withHost(host)`](#fn-specunsupportedpodtemplatespeccontainersstartupprobehttpgetwithhost)
              * [`fn withHttpHeaders(httpHeaders)`](#fn-specunsupportedpodtemplatespeccontainersstartupprobehttpgetwithhttpheaders)
              * [`fn withHttpHeadersMixin(httpHeaders)`](#fn-specunsupportedpodtemplatespeccontainersstartupprobehttpgetwithhttpheadersmixin)
              * [`fn withPath(path)`](#fn-specunsupportedpodtemplatespeccontainersstartupprobehttpgetwithpath)
              * [`fn withPort(port)`](#fn-specunsupportedpodtemplatespeccontainersstartupprobehttpgetwithport)
              * [`fn withScheme(scheme)`](#fn-specunsupportedpodtemplatespeccontainersstartupprobehttpgetwithscheme)
              * [`obj spec.unsupported.podTemplate.spec.containers.startupProbe.httpGet.httpHeaders`](#obj-specunsupportedpodtemplatespeccontainersstartupprobehttpgethttpheaders)
                * [`fn withName(name)`](#fn-specunsupportedpodtemplatespeccontainersstartupprobehttpgethttpheaderswithname)
                * [`fn withValue(value)`](#fn-specunsupportedpodtemplatespeccontainersstartupprobehttpgethttpheaderswithvalue)
            * [`obj spec.unsupported.podTemplate.spec.containers.startupProbe.tcpSocket`](#obj-specunsupportedpodtemplatespeccontainersstartupprobetcpsocket)
              * [`fn withHost(host)`](#fn-specunsupportedpodtemplatespeccontainersstartupprobetcpsocketwithhost)
              * [`fn withPort(port)`](#fn-specunsupportedpodtemplatespeccontainersstartupprobetcpsocketwithport)
          * [`obj spec.unsupported.podTemplate.spec.containers.volumeDevices`](#obj-specunsupportedpodtemplatespeccontainersvolumedevices)
            * [`fn withDevicePath(devicePath)`](#fn-specunsupportedpodtemplatespeccontainersvolumedeviceswithdevicepath)
            * [`fn withName(name)`](#fn-specunsupportedpodtemplatespeccontainersvolumedeviceswithname)
          * [`obj spec.unsupported.podTemplate.spec.containers.volumeMounts`](#obj-specunsupportedpodtemplatespeccontainersvolumemounts)
            * [`fn withMountPath(mountPath)`](#fn-specunsupportedpodtemplatespeccontainersvolumemountswithmountpath)
            * [`fn withMountPropagation(mountPropagation)`](#fn-specunsupportedpodtemplatespeccontainersvolumemountswithmountpropagation)
            * [`fn withName(name)`](#fn-specunsupportedpodtemplatespeccontainersvolumemountswithname)
            * [`fn withReadOnly(readOnly)`](#fn-specunsupportedpodtemplatespeccontainersvolumemountswithreadonly)
            * [`fn withRecursiveReadOnly(recursiveReadOnly)`](#fn-specunsupportedpodtemplatespeccontainersvolumemountswithrecursivereadonly)
            * [`fn withSubPath(subPath)`](#fn-specunsupportedpodtemplatespeccontainersvolumemountswithsubpath)
            * [`fn withSubPathExpr(subPathExpr)`](#fn-specunsupportedpodtemplatespeccontainersvolumemountswithsubpathexpr)
        * [`obj spec.unsupported.podTemplate.spec.dnsConfig`](#obj-specunsupportedpodtemplatespecdnsconfig)
          * [`fn withNameservers(nameservers)`](#fn-specunsupportedpodtemplatespecdnsconfigwithnameservers)
          * [`fn withNameserversMixin(nameservers)`](#fn-specunsupportedpodtemplatespecdnsconfigwithnameserversmixin)
          * [`fn withOptions(options)`](#fn-specunsupportedpodtemplatespecdnsconfigwithoptions)
          * [`fn withOptionsMixin(options)`](#fn-specunsupportedpodtemplatespecdnsconfigwithoptionsmixin)
          * [`fn withSearches(searches)`](#fn-specunsupportedpodtemplatespecdnsconfigwithsearches)
          * [`fn withSearchesMixin(searches)`](#fn-specunsupportedpodtemplatespecdnsconfigwithsearchesmixin)
          * [`obj spec.unsupported.podTemplate.spec.dnsConfig.options`](#obj-specunsupportedpodtemplatespecdnsconfigoptions)
            * [`fn withName(name)`](#fn-specunsupportedpodtemplatespecdnsconfigoptionswithname)
            * [`fn withValue(value)`](#fn-specunsupportedpodtemplatespecdnsconfigoptionswithvalue)
        * [`obj spec.unsupported.podTemplate.spec.ephemeralContainers`](#obj-specunsupportedpodtemplatespecephemeralcontainers)
          * [`fn withArgs(args)`](#fn-specunsupportedpodtemplatespecephemeralcontainerswithargs)
          * [`fn withArgsMixin(args)`](#fn-specunsupportedpodtemplatespecephemeralcontainerswithargsmixin)
          * [`fn withCommand(command)`](#fn-specunsupportedpodtemplatespecephemeralcontainerswithcommand)
          * [`fn withCommandMixin(command)`](#fn-specunsupportedpodtemplatespecephemeralcontainerswithcommandmixin)
          * [`fn withEnv(env)`](#fn-specunsupportedpodtemplatespecephemeralcontainerswithenv)
          * [`fn withEnvFrom(envFrom)`](#fn-specunsupportedpodtemplatespecephemeralcontainerswithenvfrom)
          * [`fn withEnvFromMixin(envFrom)`](#fn-specunsupportedpodtemplatespecephemeralcontainerswithenvfrommixin)
          * [`fn withEnvMixin(env)`](#fn-specunsupportedpodtemplatespecephemeralcontainerswithenvmixin)
          * [`fn withImage(image)`](#fn-specunsupportedpodtemplatespecephemeralcontainerswithimage)
          * [`fn withImagePullPolicy(imagePullPolicy)`](#fn-specunsupportedpodtemplatespecephemeralcontainerswithimagepullpolicy)
          * [`fn withName(name)`](#fn-specunsupportedpodtemplatespecephemeralcontainerswithname)
          * [`fn withPorts(ports)`](#fn-specunsupportedpodtemplatespecephemeralcontainerswithports)
          * [`fn withPortsMixin(ports)`](#fn-specunsupportedpodtemplatespecephemeralcontainerswithportsmixin)
          * [`fn withResizePolicy(resizePolicy)`](#fn-specunsupportedpodtemplatespecephemeralcontainerswithresizepolicy)
          * [`fn withResizePolicyMixin(resizePolicy)`](#fn-specunsupportedpodtemplatespecephemeralcontainerswithresizepolicymixin)
          * [`fn withRestartPolicy(restartPolicy)`](#fn-specunsupportedpodtemplatespecephemeralcontainerswithrestartpolicy)
          * [`fn withStdin(stdin)`](#fn-specunsupportedpodtemplatespecephemeralcontainerswithstdin)
          * [`fn withStdinOnce(stdinOnce)`](#fn-specunsupportedpodtemplatespecephemeralcontainerswithstdinonce)
          * [`fn withTargetContainerName(targetContainerName)`](#fn-specunsupportedpodtemplatespecephemeralcontainerswithtargetcontainername)
          * [`fn withTerminationMessagePath(terminationMessagePath)`](#fn-specunsupportedpodtemplatespecephemeralcontainerswithterminationmessagepath)
          * [`fn withTerminationMessagePolicy(terminationMessagePolicy)`](#fn-specunsupportedpodtemplatespecephemeralcontainerswithterminationmessagepolicy)
          * [`fn withTty(tty)`](#fn-specunsupportedpodtemplatespecephemeralcontainerswithtty)
          * [`fn withVolumeDevices(volumeDevices)`](#fn-specunsupportedpodtemplatespecephemeralcontainerswithvolumedevices)
          * [`fn withVolumeDevicesMixin(volumeDevices)`](#fn-specunsupportedpodtemplatespecephemeralcontainerswithvolumedevicesmixin)
          * [`fn withVolumeMounts(volumeMounts)`](#fn-specunsupportedpodtemplatespecephemeralcontainerswithvolumemounts)
          * [`fn withVolumeMountsMixin(volumeMounts)`](#fn-specunsupportedpodtemplatespecephemeralcontainerswithvolumemountsmixin)
          * [`fn withWorkingDir(workingDir)`](#fn-specunsupportedpodtemplatespecephemeralcontainerswithworkingdir)
          * [`obj spec.unsupported.podTemplate.spec.ephemeralContainers.env`](#obj-specunsupportedpodtemplatespecephemeralcontainersenv)
            * [`fn withName(name)`](#fn-specunsupportedpodtemplatespecephemeralcontainersenvwithname)
            * [`fn withValue(value)`](#fn-specunsupportedpodtemplatespecephemeralcontainersenvwithvalue)
            * [`obj spec.unsupported.podTemplate.spec.ephemeralContainers.env.valueFrom`](#obj-specunsupportedpodtemplatespecephemeralcontainersenvvaluefrom)
              * [`obj spec.unsupported.podTemplate.spec.ephemeralContainers.env.valueFrom.configMapKeyRef`](#obj-specunsupportedpodtemplatespecephemeralcontainersenvvaluefromconfigmapkeyref)
                * [`fn withKey(key)`](#fn-specunsupportedpodtemplatespecephemeralcontainersenvvaluefromconfigmapkeyrefwithkey)
                * [`fn withName(name)`](#fn-specunsupportedpodtemplatespecephemeralcontainersenvvaluefromconfigmapkeyrefwithname)
                * [`fn withOptional(optional)`](#fn-specunsupportedpodtemplatespecephemeralcontainersenvvaluefromconfigmapkeyrefwithoptional)
              * [`obj spec.unsupported.podTemplate.spec.ephemeralContainers.env.valueFrom.fieldRef`](#obj-specunsupportedpodtemplatespecephemeralcontainersenvvaluefromfieldref)
                * [`fn withApiVersion(apiVersion)`](#fn-specunsupportedpodtemplatespecephemeralcontainersenvvaluefromfieldrefwithapiversion)
                * [`fn withFieldPath(fieldPath)`](#fn-specunsupportedpodtemplatespecephemeralcontainersenvvaluefromfieldrefwithfieldpath)
              * [`obj spec.unsupported.podTemplate.spec.ephemeralContainers.env.valueFrom.resourceFieldRef`](#obj-specunsupportedpodtemplatespecephemeralcontainersenvvaluefromresourcefieldref)
                * [`fn withContainerName(containerName)`](#fn-specunsupportedpodtemplatespecephemeralcontainersenvvaluefromresourcefieldrefwithcontainername)
                * [`fn withDivisor(divisor)`](#fn-specunsupportedpodtemplatespecephemeralcontainersenvvaluefromresourcefieldrefwithdivisor)
                * [`fn withResource(resource)`](#fn-specunsupportedpodtemplatespecephemeralcontainersenvvaluefromresourcefieldrefwithresource)
              * [`obj spec.unsupported.podTemplate.spec.ephemeralContainers.env.valueFrom.secretKeyRef`](#obj-specunsupportedpodtemplatespecephemeralcontainersenvvaluefromsecretkeyref)
                * [`fn withKey(key)`](#fn-specunsupportedpodtemplatespecephemeralcontainersenvvaluefromsecretkeyrefwithkey)
                * [`fn withName(name)`](#fn-specunsupportedpodtemplatespecephemeralcontainersenvvaluefromsecretkeyrefwithname)
                * [`fn withOptional(optional)`](#fn-specunsupportedpodtemplatespecephemeralcontainersenvvaluefromsecretkeyrefwithoptional)
          * [`obj spec.unsupported.podTemplate.spec.ephemeralContainers.envFrom`](#obj-specunsupportedpodtemplatespecephemeralcontainersenvfrom)
            * [`fn withPrefix(prefix)`](#fn-specunsupportedpodtemplatespecephemeralcontainersenvfromwithprefix)
            * [`obj spec.unsupported.podTemplate.spec.ephemeralContainers.envFrom.configMapRef`](#obj-specunsupportedpodtemplatespecephemeralcontainersenvfromconfigmapref)
              * [`fn withName(name)`](#fn-specunsupportedpodtemplatespecephemeralcontainersenvfromconfigmaprefwithname)
              * [`fn withOptional(optional)`](#fn-specunsupportedpodtemplatespecephemeralcontainersenvfromconfigmaprefwithoptional)
            * [`obj spec.unsupported.podTemplate.spec.ephemeralContainers.envFrom.secretRef`](#obj-specunsupportedpodtemplatespecephemeralcontainersenvfromsecretref)
              * [`fn withName(name)`](#fn-specunsupportedpodtemplatespecephemeralcontainersenvfromsecretrefwithname)
              * [`fn withOptional(optional)`](#fn-specunsupportedpodtemplatespecephemeralcontainersenvfromsecretrefwithoptional)
          * [`obj spec.unsupported.podTemplate.spec.ephemeralContainers.lifecycle`](#obj-specunsupportedpodtemplatespecephemeralcontainerslifecycle)
            * [`fn withStopSignal(stopSignal)`](#fn-specunsupportedpodtemplatespecephemeralcontainerslifecyclewithstopsignal)
            * [`obj spec.unsupported.podTemplate.spec.ephemeralContainers.lifecycle.postStart`](#obj-specunsupportedpodtemplatespecephemeralcontainerslifecyclepoststart)
              * [`obj spec.unsupported.podTemplate.spec.ephemeralContainers.lifecycle.postStart.exec`](#obj-specunsupportedpodtemplatespecephemeralcontainerslifecyclepoststartexec)
                * [`fn withCommand(command)`](#fn-specunsupportedpodtemplatespecephemeralcontainerslifecyclepoststartexecwithcommand)
                * [`fn withCommandMixin(command)`](#fn-specunsupportedpodtemplatespecephemeralcontainerslifecyclepoststartexecwithcommandmixin)
              * [`obj spec.unsupported.podTemplate.spec.ephemeralContainers.lifecycle.postStart.httpGet`](#obj-specunsupportedpodtemplatespecephemeralcontainerslifecyclepoststarthttpget)
                * [`fn withHost(host)`](#fn-specunsupportedpodtemplatespecephemeralcontainerslifecyclepoststarthttpgetwithhost)
                * [`fn withHttpHeaders(httpHeaders)`](#fn-specunsupportedpodtemplatespecephemeralcontainerslifecyclepoststarthttpgetwithhttpheaders)
                * [`fn withHttpHeadersMixin(httpHeaders)`](#fn-specunsupportedpodtemplatespecephemeralcontainerslifecyclepoststarthttpgetwithhttpheadersmixin)
                * [`fn withPath(path)`](#fn-specunsupportedpodtemplatespecephemeralcontainerslifecyclepoststarthttpgetwithpath)
                * [`fn withPort(port)`](#fn-specunsupportedpodtemplatespecephemeralcontainerslifecyclepoststarthttpgetwithport)
                * [`fn withScheme(scheme)`](#fn-specunsupportedpodtemplatespecephemeralcontainerslifecyclepoststarthttpgetwithscheme)
                * [`obj spec.unsupported.podTemplate.spec.ephemeralContainers.lifecycle.postStart.httpGet.httpHeaders`](#obj-specunsupportedpodtemplatespecephemeralcontainerslifecyclepoststarthttpgethttpheaders)
                  * [`fn withName(name)`](#fn-specunsupportedpodtemplatespecephemeralcontainerslifecyclepoststarthttpgethttpheaderswithname)
                  * [`fn withValue(value)`](#fn-specunsupportedpodtemplatespecephemeralcontainerslifecyclepoststarthttpgethttpheaderswithvalue)
              * [`obj spec.unsupported.podTemplate.spec.ephemeralContainers.lifecycle.postStart.sleep`](#obj-specunsupportedpodtemplatespecephemeralcontainerslifecyclepoststartsleep)
                * [`fn withSeconds(seconds)`](#fn-specunsupportedpodtemplatespecephemeralcontainerslifecyclepoststartsleepwithseconds)
              * [`obj spec.unsupported.podTemplate.spec.ephemeralContainers.lifecycle.postStart.tcpSocket`](#obj-specunsupportedpodtemplatespecephemeralcontainerslifecyclepoststarttcpsocket)
                * [`fn withHost(host)`](#fn-specunsupportedpodtemplatespecephemeralcontainerslifecyclepoststarttcpsocketwithhost)
                * [`fn withPort(port)`](#fn-specunsupportedpodtemplatespecephemeralcontainerslifecyclepoststarttcpsocketwithport)
            * [`obj spec.unsupported.podTemplate.spec.ephemeralContainers.lifecycle.preStop`](#obj-specunsupportedpodtemplatespecephemeralcontainerslifecycleprestop)
              * [`obj spec.unsupported.podTemplate.spec.ephemeralContainers.lifecycle.preStop.exec`](#obj-specunsupportedpodtemplatespecephemeralcontainerslifecycleprestopexec)
                * [`fn withCommand(command)`](#fn-specunsupportedpodtemplatespecephemeralcontainerslifecycleprestopexecwithcommand)
                * [`fn withCommandMixin(command)`](#fn-specunsupportedpodtemplatespecephemeralcontainerslifecycleprestopexecwithcommandmixin)
              * [`obj spec.unsupported.podTemplate.spec.ephemeralContainers.lifecycle.preStop.httpGet`](#obj-specunsupportedpodtemplatespecephemeralcontainerslifecycleprestophttpget)
                * [`fn withHost(host)`](#fn-specunsupportedpodtemplatespecephemeralcontainerslifecycleprestophttpgetwithhost)
                * [`fn withHttpHeaders(httpHeaders)`](#fn-specunsupportedpodtemplatespecephemeralcontainerslifecycleprestophttpgetwithhttpheaders)
                * [`fn withHttpHeadersMixin(httpHeaders)`](#fn-specunsupportedpodtemplatespecephemeralcontainerslifecycleprestophttpgetwithhttpheadersmixin)
                * [`fn withPath(path)`](#fn-specunsupportedpodtemplatespecephemeralcontainerslifecycleprestophttpgetwithpath)
                * [`fn withPort(port)`](#fn-specunsupportedpodtemplatespecephemeralcontainerslifecycleprestophttpgetwithport)
                * [`fn withScheme(scheme)`](#fn-specunsupportedpodtemplatespecephemeralcontainerslifecycleprestophttpgetwithscheme)
                * [`obj spec.unsupported.podTemplate.spec.ephemeralContainers.lifecycle.preStop.httpGet.httpHeaders`](#obj-specunsupportedpodtemplatespecephemeralcontainerslifecycleprestophttpgethttpheaders)
                  * [`fn withName(name)`](#fn-specunsupportedpodtemplatespecephemeralcontainerslifecycleprestophttpgethttpheaderswithname)
                  * [`fn withValue(value)`](#fn-specunsupportedpodtemplatespecephemeralcontainerslifecycleprestophttpgethttpheaderswithvalue)
              * [`obj spec.unsupported.podTemplate.spec.ephemeralContainers.lifecycle.preStop.sleep`](#obj-specunsupportedpodtemplatespecephemeralcontainerslifecycleprestopsleep)
                * [`fn withSeconds(seconds)`](#fn-specunsupportedpodtemplatespecephemeralcontainerslifecycleprestopsleepwithseconds)
              * [`obj spec.unsupported.podTemplate.spec.ephemeralContainers.lifecycle.preStop.tcpSocket`](#obj-specunsupportedpodtemplatespecephemeralcontainerslifecycleprestoptcpsocket)
                * [`fn withHost(host)`](#fn-specunsupportedpodtemplatespecephemeralcontainerslifecycleprestoptcpsocketwithhost)
                * [`fn withPort(port)`](#fn-specunsupportedpodtemplatespecephemeralcontainerslifecycleprestoptcpsocketwithport)
          * [`obj spec.unsupported.podTemplate.spec.ephemeralContainers.livenessProbe`](#obj-specunsupportedpodtemplatespecephemeralcontainerslivenessprobe)
            * [`fn withFailureThreshold(failureThreshold)`](#fn-specunsupportedpodtemplatespecephemeralcontainerslivenessprobewithfailurethreshold)
            * [`fn withInitialDelaySeconds(initialDelaySeconds)`](#fn-specunsupportedpodtemplatespecephemeralcontainerslivenessprobewithinitialdelayseconds)
            * [`fn withPeriodSeconds(periodSeconds)`](#fn-specunsupportedpodtemplatespecephemeralcontainerslivenessprobewithperiodseconds)
            * [`fn withSuccessThreshold(successThreshold)`](#fn-specunsupportedpodtemplatespecephemeralcontainerslivenessprobewithsuccessthreshold)
            * [`fn withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)`](#fn-specunsupportedpodtemplatespecephemeralcontainerslivenessprobewithterminationgraceperiodseconds)
            * [`fn withTimeoutSeconds(timeoutSeconds)`](#fn-specunsupportedpodtemplatespecephemeralcontainerslivenessprobewithtimeoutseconds)
            * [`obj spec.unsupported.podTemplate.spec.ephemeralContainers.livenessProbe.exec`](#obj-specunsupportedpodtemplatespecephemeralcontainerslivenessprobeexec)
              * [`fn withCommand(command)`](#fn-specunsupportedpodtemplatespecephemeralcontainerslivenessprobeexecwithcommand)
              * [`fn withCommandMixin(command)`](#fn-specunsupportedpodtemplatespecephemeralcontainerslivenessprobeexecwithcommandmixin)
            * [`obj spec.unsupported.podTemplate.spec.ephemeralContainers.livenessProbe.grpc`](#obj-specunsupportedpodtemplatespecephemeralcontainerslivenessprobegrpc)
              * [`fn withPort(port)`](#fn-specunsupportedpodtemplatespecephemeralcontainerslivenessprobegrpcwithport)
              * [`fn withService(service)`](#fn-specunsupportedpodtemplatespecephemeralcontainerslivenessprobegrpcwithservice)
            * [`obj spec.unsupported.podTemplate.spec.ephemeralContainers.livenessProbe.httpGet`](#obj-specunsupportedpodtemplatespecephemeralcontainerslivenessprobehttpget)
              * [`fn withHost(host)`](#fn-specunsupportedpodtemplatespecephemeralcontainerslivenessprobehttpgetwithhost)
              * [`fn withHttpHeaders(httpHeaders)`](#fn-specunsupportedpodtemplatespecephemeralcontainerslivenessprobehttpgetwithhttpheaders)
              * [`fn withHttpHeadersMixin(httpHeaders)`](#fn-specunsupportedpodtemplatespecephemeralcontainerslivenessprobehttpgetwithhttpheadersmixin)
              * [`fn withPath(path)`](#fn-specunsupportedpodtemplatespecephemeralcontainerslivenessprobehttpgetwithpath)
              * [`fn withPort(port)`](#fn-specunsupportedpodtemplatespecephemeralcontainerslivenessprobehttpgetwithport)
              * [`fn withScheme(scheme)`](#fn-specunsupportedpodtemplatespecephemeralcontainerslivenessprobehttpgetwithscheme)
              * [`obj spec.unsupported.podTemplate.spec.ephemeralContainers.livenessProbe.httpGet.httpHeaders`](#obj-specunsupportedpodtemplatespecephemeralcontainerslivenessprobehttpgethttpheaders)
                * [`fn withName(name)`](#fn-specunsupportedpodtemplatespecephemeralcontainerslivenessprobehttpgethttpheaderswithname)
                * [`fn withValue(value)`](#fn-specunsupportedpodtemplatespecephemeralcontainerslivenessprobehttpgethttpheaderswithvalue)
            * [`obj spec.unsupported.podTemplate.spec.ephemeralContainers.livenessProbe.tcpSocket`](#obj-specunsupportedpodtemplatespecephemeralcontainerslivenessprobetcpsocket)
              * [`fn withHost(host)`](#fn-specunsupportedpodtemplatespecephemeralcontainerslivenessprobetcpsocketwithhost)
              * [`fn withPort(port)`](#fn-specunsupportedpodtemplatespecephemeralcontainerslivenessprobetcpsocketwithport)
          * [`obj spec.unsupported.podTemplate.spec.ephemeralContainers.ports`](#obj-specunsupportedpodtemplatespecephemeralcontainersports)
            * [`fn withContainerPort(containerPort)`](#fn-specunsupportedpodtemplatespecephemeralcontainersportswithcontainerport)
            * [`fn withHostIP(hostIP)`](#fn-specunsupportedpodtemplatespecephemeralcontainersportswithhostip)
            * [`fn withHostPort(hostPort)`](#fn-specunsupportedpodtemplatespecephemeralcontainersportswithhostport)
            * [`fn withName(name)`](#fn-specunsupportedpodtemplatespecephemeralcontainersportswithname)
            * [`fn withProtocol(protocol)`](#fn-specunsupportedpodtemplatespecephemeralcontainersportswithprotocol)
          * [`obj spec.unsupported.podTemplate.spec.ephemeralContainers.readinessProbe`](#obj-specunsupportedpodtemplatespecephemeralcontainersreadinessprobe)
            * [`fn withFailureThreshold(failureThreshold)`](#fn-specunsupportedpodtemplatespecephemeralcontainersreadinessprobewithfailurethreshold)
            * [`fn withInitialDelaySeconds(initialDelaySeconds)`](#fn-specunsupportedpodtemplatespecephemeralcontainersreadinessprobewithinitialdelayseconds)
            * [`fn withPeriodSeconds(periodSeconds)`](#fn-specunsupportedpodtemplatespecephemeralcontainersreadinessprobewithperiodseconds)
            * [`fn withSuccessThreshold(successThreshold)`](#fn-specunsupportedpodtemplatespecephemeralcontainersreadinessprobewithsuccessthreshold)
            * [`fn withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)`](#fn-specunsupportedpodtemplatespecephemeralcontainersreadinessprobewithterminationgraceperiodseconds)
            * [`fn withTimeoutSeconds(timeoutSeconds)`](#fn-specunsupportedpodtemplatespecephemeralcontainersreadinessprobewithtimeoutseconds)
            * [`obj spec.unsupported.podTemplate.spec.ephemeralContainers.readinessProbe.exec`](#obj-specunsupportedpodtemplatespecephemeralcontainersreadinessprobeexec)
              * [`fn withCommand(command)`](#fn-specunsupportedpodtemplatespecephemeralcontainersreadinessprobeexecwithcommand)
              * [`fn withCommandMixin(command)`](#fn-specunsupportedpodtemplatespecephemeralcontainersreadinessprobeexecwithcommandmixin)
            * [`obj spec.unsupported.podTemplate.spec.ephemeralContainers.readinessProbe.grpc`](#obj-specunsupportedpodtemplatespecephemeralcontainersreadinessprobegrpc)
              * [`fn withPort(port)`](#fn-specunsupportedpodtemplatespecephemeralcontainersreadinessprobegrpcwithport)
              * [`fn withService(service)`](#fn-specunsupportedpodtemplatespecephemeralcontainersreadinessprobegrpcwithservice)
            * [`obj spec.unsupported.podTemplate.spec.ephemeralContainers.readinessProbe.httpGet`](#obj-specunsupportedpodtemplatespecephemeralcontainersreadinessprobehttpget)
              * [`fn withHost(host)`](#fn-specunsupportedpodtemplatespecephemeralcontainersreadinessprobehttpgetwithhost)
              * [`fn withHttpHeaders(httpHeaders)`](#fn-specunsupportedpodtemplatespecephemeralcontainersreadinessprobehttpgetwithhttpheaders)
              * [`fn withHttpHeadersMixin(httpHeaders)`](#fn-specunsupportedpodtemplatespecephemeralcontainersreadinessprobehttpgetwithhttpheadersmixin)
              * [`fn withPath(path)`](#fn-specunsupportedpodtemplatespecephemeralcontainersreadinessprobehttpgetwithpath)
              * [`fn withPort(port)`](#fn-specunsupportedpodtemplatespecephemeralcontainersreadinessprobehttpgetwithport)
              * [`fn withScheme(scheme)`](#fn-specunsupportedpodtemplatespecephemeralcontainersreadinessprobehttpgetwithscheme)
              * [`obj spec.unsupported.podTemplate.spec.ephemeralContainers.readinessProbe.httpGet.httpHeaders`](#obj-specunsupportedpodtemplatespecephemeralcontainersreadinessprobehttpgethttpheaders)
                * [`fn withName(name)`](#fn-specunsupportedpodtemplatespecephemeralcontainersreadinessprobehttpgethttpheaderswithname)
                * [`fn withValue(value)`](#fn-specunsupportedpodtemplatespecephemeralcontainersreadinessprobehttpgethttpheaderswithvalue)
            * [`obj spec.unsupported.podTemplate.spec.ephemeralContainers.readinessProbe.tcpSocket`](#obj-specunsupportedpodtemplatespecephemeralcontainersreadinessprobetcpsocket)
              * [`fn withHost(host)`](#fn-specunsupportedpodtemplatespecephemeralcontainersreadinessprobetcpsocketwithhost)
              * [`fn withPort(port)`](#fn-specunsupportedpodtemplatespecephemeralcontainersreadinessprobetcpsocketwithport)
          * [`obj spec.unsupported.podTemplate.spec.ephemeralContainers.resizePolicy`](#obj-specunsupportedpodtemplatespecephemeralcontainersresizepolicy)
            * [`fn withResourceName(resourceName)`](#fn-specunsupportedpodtemplatespecephemeralcontainersresizepolicywithresourcename)
            * [`fn withRestartPolicy(restartPolicy)`](#fn-specunsupportedpodtemplatespecephemeralcontainersresizepolicywithrestartpolicy)
          * [`obj spec.unsupported.podTemplate.spec.ephemeralContainers.resources`](#obj-specunsupportedpodtemplatespecephemeralcontainersresources)
            * [`fn withClaims(claims)`](#fn-specunsupportedpodtemplatespecephemeralcontainersresourceswithclaims)
            * [`fn withClaimsMixin(claims)`](#fn-specunsupportedpodtemplatespecephemeralcontainersresourceswithclaimsmixin)
            * [`fn withLimits(limits)`](#fn-specunsupportedpodtemplatespecephemeralcontainersresourceswithlimits)
            * [`fn withLimitsMixin(limits)`](#fn-specunsupportedpodtemplatespecephemeralcontainersresourceswithlimitsmixin)
            * [`fn withRequests(requests)`](#fn-specunsupportedpodtemplatespecephemeralcontainersresourceswithrequests)
            * [`fn withRequestsMixin(requests)`](#fn-specunsupportedpodtemplatespecephemeralcontainersresourceswithrequestsmixin)
            * [`obj spec.unsupported.podTemplate.spec.ephemeralContainers.resources.claims`](#obj-specunsupportedpodtemplatespecephemeralcontainersresourcesclaims)
              * [`fn withName(name)`](#fn-specunsupportedpodtemplatespecephemeralcontainersresourcesclaimswithname)
              * [`fn withRequest(request)`](#fn-specunsupportedpodtemplatespecephemeralcontainersresourcesclaimswithrequest)
          * [`obj spec.unsupported.podTemplate.spec.ephemeralContainers.securityContext`](#obj-specunsupportedpodtemplatespecephemeralcontainerssecuritycontext)
            * [`fn withAllowPrivilegeEscalation(allowPrivilegeEscalation)`](#fn-specunsupportedpodtemplatespecephemeralcontainerssecuritycontextwithallowprivilegeescalation)
            * [`fn withPrivileged(privileged)`](#fn-specunsupportedpodtemplatespecephemeralcontainerssecuritycontextwithprivileged)
            * [`fn withProcMount(procMount)`](#fn-specunsupportedpodtemplatespecephemeralcontainerssecuritycontextwithprocmount)
            * [`fn withReadOnlyRootFilesystem(readOnlyRootFilesystem)`](#fn-specunsupportedpodtemplatespecephemeralcontainerssecuritycontextwithreadonlyrootfilesystem)
            * [`fn withRunAsGroup(runAsGroup)`](#fn-specunsupportedpodtemplatespecephemeralcontainerssecuritycontextwithrunasgroup)
            * [`fn withRunAsNonRoot(runAsNonRoot)`](#fn-specunsupportedpodtemplatespecephemeralcontainerssecuritycontextwithrunasnonroot)
            * [`fn withRunAsUser(runAsUser)`](#fn-specunsupportedpodtemplatespecephemeralcontainerssecuritycontextwithrunasuser)
            * [`obj spec.unsupported.podTemplate.spec.ephemeralContainers.securityContext.appArmorProfile`](#obj-specunsupportedpodtemplatespecephemeralcontainerssecuritycontextapparmorprofile)
              * [`fn withLocalhostProfile(localhostProfile)`](#fn-specunsupportedpodtemplatespecephemeralcontainerssecuritycontextapparmorprofilewithlocalhostprofile)
              * [`fn withType(type)`](#fn-specunsupportedpodtemplatespecephemeralcontainerssecuritycontextapparmorprofilewithtype)
            * [`obj spec.unsupported.podTemplate.spec.ephemeralContainers.securityContext.capabilities`](#obj-specunsupportedpodtemplatespecephemeralcontainerssecuritycontextcapabilities)
              * [`fn withAdd(add)`](#fn-specunsupportedpodtemplatespecephemeralcontainerssecuritycontextcapabilitieswithadd)
              * [`fn withAddMixin(add)`](#fn-specunsupportedpodtemplatespecephemeralcontainerssecuritycontextcapabilitieswithaddmixin)
              * [`fn withDrop(drop)`](#fn-specunsupportedpodtemplatespecephemeralcontainerssecuritycontextcapabilitieswithdrop)
              * [`fn withDropMixin(drop)`](#fn-specunsupportedpodtemplatespecephemeralcontainerssecuritycontextcapabilitieswithdropmixin)
            * [`obj spec.unsupported.podTemplate.spec.ephemeralContainers.securityContext.seLinuxOptions`](#obj-specunsupportedpodtemplatespecephemeralcontainerssecuritycontextselinuxoptions)
              * [`fn withLevel(level)`](#fn-specunsupportedpodtemplatespecephemeralcontainerssecuritycontextselinuxoptionswithlevel)
              * [`fn withRole(role)`](#fn-specunsupportedpodtemplatespecephemeralcontainerssecuritycontextselinuxoptionswithrole)
              * [`fn withType(type)`](#fn-specunsupportedpodtemplatespecephemeralcontainerssecuritycontextselinuxoptionswithtype)
              * [`fn withUser(user)`](#fn-specunsupportedpodtemplatespecephemeralcontainerssecuritycontextselinuxoptionswithuser)
            * [`obj spec.unsupported.podTemplate.spec.ephemeralContainers.securityContext.seccompProfile`](#obj-specunsupportedpodtemplatespecephemeralcontainerssecuritycontextseccompprofile)
              * [`fn withLocalhostProfile(localhostProfile)`](#fn-specunsupportedpodtemplatespecephemeralcontainerssecuritycontextseccompprofilewithlocalhostprofile)
              * [`fn withType(type)`](#fn-specunsupportedpodtemplatespecephemeralcontainerssecuritycontextseccompprofilewithtype)
            * [`obj spec.unsupported.podTemplate.spec.ephemeralContainers.securityContext.windowsOptions`](#obj-specunsupportedpodtemplatespecephemeralcontainerssecuritycontextwindowsoptions)
              * [`fn withGmsaCredentialSpec(gmsaCredentialSpec)`](#fn-specunsupportedpodtemplatespecephemeralcontainerssecuritycontextwindowsoptionswithgmsacredentialspec)
              * [`fn withGmsaCredentialSpecName(gmsaCredentialSpecName)`](#fn-specunsupportedpodtemplatespecephemeralcontainerssecuritycontextwindowsoptionswithgmsacredentialspecname)
              * [`fn withHostProcess(hostProcess)`](#fn-specunsupportedpodtemplatespecephemeralcontainerssecuritycontextwindowsoptionswithhostprocess)
              * [`fn withRunAsUserName(runAsUserName)`](#fn-specunsupportedpodtemplatespecephemeralcontainerssecuritycontextwindowsoptionswithrunasusername)
          * [`obj spec.unsupported.podTemplate.spec.ephemeralContainers.startupProbe`](#obj-specunsupportedpodtemplatespecephemeralcontainersstartupprobe)
            * [`fn withFailureThreshold(failureThreshold)`](#fn-specunsupportedpodtemplatespecephemeralcontainersstartupprobewithfailurethreshold)
            * [`fn withInitialDelaySeconds(initialDelaySeconds)`](#fn-specunsupportedpodtemplatespecephemeralcontainersstartupprobewithinitialdelayseconds)
            * [`fn withPeriodSeconds(periodSeconds)`](#fn-specunsupportedpodtemplatespecephemeralcontainersstartupprobewithperiodseconds)
            * [`fn withSuccessThreshold(successThreshold)`](#fn-specunsupportedpodtemplatespecephemeralcontainersstartupprobewithsuccessthreshold)
            * [`fn withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)`](#fn-specunsupportedpodtemplatespecephemeralcontainersstartupprobewithterminationgraceperiodseconds)
            * [`fn withTimeoutSeconds(timeoutSeconds)`](#fn-specunsupportedpodtemplatespecephemeralcontainersstartupprobewithtimeoutseconds)
            * [`obj spec.unsupported.podTemplate.spec.ephemeralContainers.startupProbe.exec`](#obj-specunsupportedpodtemplatespecephemeralcontainersstartupprobeexec)
              * [`fn withCommand(command)`](#fn-specunsupportedpodtemplatespecephemeralcontainersstartupprobeexecwithcommand)
              * [`fn withCommandMixin(command)`](#fn-specunsupportedpodtemplatespecephemeralcontainersstartupprobeexecwithcommandmixin)
            * [`obj spec.unsupported.podTemplate.spec.ephemeralContainers.startupProbe.grpc`](#obj-specunsupportedpodtemplatespecephemeralcontainersstartupprobegrpc)
              * [`fn withPort(port)`](#fn-specunsupportedpodtemplatespecephemeralcontainersstartupprobegrpcwithport)
              * [`fn withService(service)`](#fn-specunsupportedpodtemplatespecephemeralcontainersstartupprobegrpcwithservice)
            * [`obj spec.unsupported.podTemplate.spec.ephemeralContainers.startupProbe.httpGet`](#obj-specunsupportedpodtemplatespecephemeralcontainersstartupprobehttpget)
              * [`fn withHost(host)`](#fn-specunsupportedpodtemplatespecephemeralcontainersstartupprobehttpgetwithhost)
              * [`fn withHttpHeaders(httpHeaders)`](#fn-specunsupportedpodtemplatespecephemeralcontainersstartupprobehttpgetwithhttpheaders)
              * [`fn withHttpHeadersMixin(httpHeaders)`](#fn-specunsupportedpodtemplatespecephemeralcontainersstartupprobehttpgetwithhttpheadersmixin)
              * [`fn withPath(path)`](#fn-specunsupportedpodtemplatespecephemeralcontainersstartupprobehttpgetwithpath)
              * [`fn withPort(port)`](#fn-specunsupportedpodtemplatespecephemeralcontainersstartupprobehttpgetwithport)
              * [`fn withScheme(scheme)`](#fn-specunsupportedpodtemplatespecephemeralcontainersstartupprobehttpgetwithscheme)
              * [`obj spec.unsupported.podTemplate.spec.ephemeralContainers.startupProbe.httpGet.httpHeaders`](#obj-specunsupportedpodtemplatespecephemeralcontainersstartupprobehttpgethttpheaders)
                * [`fn withName(name)`](#fn-specunsupportedpodtemplatespecephemeralcontainersstartupprobehttpgethttpheaderswithname)
                * [`fn withValue(value)`](#fn-specunsupportedpodtemplatespecephemeralcontainersstartupprobehttpgethttpheaderswithvalue)
            * [`obj spec.unsupported.podTemplate.spec.ephemeralContainers.startupProbe.tcpSocket`](#obj-specunsupportedpodtemplatespecephemeralcontainersstartupprobetcpsocket)
              * [`fn withHost(host)`](#fn-specunsupportedpodtemplatespecephemeralcontainersstartupprobetcpsocketwithhost)
              * [`fn withPort(port)`](#fn-specunsupportedpodtemplatespecephemeralcontainersstartupprobetcpsocketwithport)
          * [`obj spec.unsupported.podTemplate.spec.ephemeralContainers.volumeDevices`](#obj-specunsupportedpodtemplatespecephemeralcontainersvolumedevices)
            * [`fn withDevicePath(devicePath)`](#fn-specunsupportedpodtemplatespecephemeralcontainersvolumedeviceswithdevicepath)
            * [`fn withName(name)`](#fn-specunsupportedpodtemplatespecephemeralcontainersvolumedeviceswithname)
          * [`obj spec.unsupported.podTemplate.spec.ephemeralContainers.volumeMounts`](#obj-specunsupportedpodtemplatespecephemeralcontainersvolumemounts)
            * [`fn withMountPath(mountPath)`](#fn-specunsupportedpodtemplatespecephemeralcontainersvolumemountswithmountpath)
            * [`fn withMountPropagation(mountPropagation)`](#fn-specunsupportedpodtemplatespecephemeralcontainersvolumemountswithmountpropagation)
            * [`fn withName(name)`](#fn-specunsupportedpodtemplatespecephemeralcontainersvolumemountswithname)
            * [`fn withReadOnly(readOnly)`](#fn-specunsupportedpodtemplatespecephemeralcontainersvolumemountswithreadonly)
            * [`fn withRecursiveReadOnly(recursiveReadOnly)`](#fn-specunsupportedpodtemplatespecephemeralcontainersvolumemountswithrecursivereadonly)
            * [`fn withSubPath(subPath)`](#fn-specunsupportedpodtemplatespecephemeralcontainersvolumemountswithsubpath)
            * [`fn withSubPathExpr(subPathExpr)`](#fn-specunsupportedpodtemplatespecephemeralcontainersvolumemountswithsubpathexpr)
        * [`obj spec.unsupported.podTemplate.spec.hostAliases`](#obj-specunsupportedpodtemplatespechostaliases)
          * [`fn withHostnames(hostnames)`](#fn-specunsupportedpodtemplatespechostaliaseswithhostnames)
          * [`fn withHostnamesMixin(hostnames)`](#fn-specunsupportedpodtemplatespechostaliaseswithhostnamesmixin)
          * [`fn withIp(ip)`](#fn-specunsupportedpodtemplatespechostaliaseswithip)
        * [`obj spec.unsupported.podTemplate.spec.imagePullSecrets`](#obj-specunsupportedpodtemplatespecimagepullsecrets)
          * [`fn withName(name)`](#fn-specunsupportedpodtemplatespecimagepullsecretswithname)
        * [`obj spec.unsupported.podTemplate.spec.initContainers`](#obj-specunsupportedpodtemplatespecinitcontainers)
          * [`fn withArgs(args)`](#fn-specunsupportedpodtemplatespecinitcontainerswithargs)
          * [`fn withArgsMixin(args)`](#fn-specunsupportedpodtemplatespecinitcontainerswithargsmixin)
          * [`fn withCommand(command)`](#fn-specunsupportedpodtemplatespecinitcontainerswithcommand)
          * [`fn withCommandMixin(command)`](#fn-specunsupportedpodtemplatespecinitcontainerswithcommandmixin)
          * [`fn withEnv(env)`](#fn-specunsupportedpodtemplatespecinitcontainerswithenv)
          * [`fn withEnvFrom(envFrom)`](#fn-specunsupportedpodtemplatespecinitcontainerswithenvfrom)
          * [`fn withEnvFromMixin(envFrom)`](#fn-specunsupportedpodtemplatespecinitcontainerswithenvfrommixin)
          * [`fn withEnvMixin(env)`](#fn-specunsupportedpodtemplatespecinitcontainerswithenvmixin)
          * [`fn withImage(image)`](#fn-specunsupportedpodtemplatespecinitcontainerswithimage)
          * [`fn withImagePullPolicy(imagePullPolicy)`](#fn-specunsupportedpodtemplatespecinitcontainerswithimagepullpolicy)
          * [`fn withName(name)`](#fn-specunsupportedpodtemplatespecinitcontainerswithname)
          * [`fn withPorts(ports)`](#fn-specunsupportedpodtemplatespecinitcontainerswithports)
          * [`fn withPortsMixin(ports)`](#fn-specunsupportedpodtemplatespecinitcontainerswithportsmixin)
          * [`fn withResizePolicy(resizePolicy)`](#fn-specunsupportedpodtemplatespecinitcontainerswithresizepolicy)
          * [`fn withResizePolicyMixin(resizePolicy)`](#fn-specunsupportedpodtemplatespecinitcontainerswithresizepolicymixin)
          * [`fn withRestartPolicy(restartPolicy)`](#fn-specunsupportedpodtemplatespecinitcontainerswithrestartpolicy)
          * [`fn withStdin(stdin)`](#fn-specunsupportedpodtemplatespecinitcontainerswithstdin)
          * [`fn withStdinOnce(stdinOnce)`](#fn-specunsupportedpodtemplatespecinitcontainerswithstdinonce)
          * [`fn withTerminationMessagePath(terminationMessagePath)`](#fn-specunsupportedpodtemplatespecinitcontainerswithterminationmessagepath)
          * [`fn withTerminationMessagePolicy(terminationMessagePolicy)`](#fn-specunsupportedpodtemplatespecinitcontainerswithterminationmessagepolicy)
          * [`fn withTty(tty)`](#fn-specunsupportedpodtemplatespecinitcontainerswithtty)
          * [`fn withVolumeDevices(volumeDevices)`](#fn-specunsupportedpodtemplatespecinitcontainerswithvolumedevices)
          * [`fn withVolumeDevicesMixin(volumeDevices)`](#fn-specunsupportedpodtemplatespecinitcontainerswithvolumedevicesmixin)
          * [`fn withVolumeMounts(volumeMounts)`](#fn-specunsupportedpodtemplatespecinitcontainerswithvolumemounts)
          * [`fn withVolumeMountsMixin(volumeMounts)`](#fn-specunsupportedpodtemplatespecinitcontainerswithvolumemountsmixin)
          * [`fn withWorkingDir(workingDir)`](#fn-specunsupportedpodtemplatespecinitcontainerswithworkingdir)
          * [`obj spec.unsupported.podTemplate.spec.initContainers.env`](#obj-specunsupportedpodtemplatespecinitcontainersenv)
            * [`fn withName(name)`](#fn-specunsupportedpodtemplatespecinitcontainersenvwithname)
            * [`fn withValue(value)`](#fn-specunsupportedpodtemplatespecinitcontainersenvwithvalue)
            * [`obj spec.unsupported.podTemplate.spec.initContainers.env.valueFrom`](#obj-specunsupportedpodtemplatespecinitcontainersenvvaluefrom)
              * [`obj spec.unsupported.podTemplate.spec.initContainers.env.valueFrom.configMapKeyRef`](#obj-specunsupportedpodtemplatespecinitcontainersenvvaluefromconfigmapkeyref)
                * [`fn withKey(key)`](#fn-specunsupportedpodtemplatespecinitcontainersenvvaluefromconfigmapkeyrefwithkey)
                * [`fn withName(name)`](#fn-specunsupportedpodtemplatespecinitcontainersenvvaluefromconfigmapkeyrefwithname)
                * [`fn withOptional(optional)`](#fn-specunsupportedpodtemplatespecinitcontainersenvvaluefromconfigmapkeyrefwithoptional)
              * [`obj spec.unsupported.podTemplate.spec.initContainers.env.valueFrom.fieldRef`](#obj-specunsupportedpodtemplatespecinitcontainersenvvaluefromfieldref)
                * [`fn withApiVersion(apiVersion)`](#fn-specunsupportedpodtemplatespecinitcontainersenvvaluefromfieldrefwithapiversion)
                * [`fn withFieldPath(fieldPath)`](#fn-specunsupportedpodtemplatespecinitcontainersenvvaluefromfieldrefwithfieldpath)
              * [`obj spec.unsupported.podTemplate.spec.initContainers.env.valueFrom.resourceFieldRef`](#obj-specunsupportedpodtemplatespecinitcontainersenvvaluefromresourcefieldref)
                * [`fn withContainerName(containerName)`](#fn-specunsupportedpodtemplatespecinitcontainersenvvaluefromresourcefieldrefwithcontainername)
                * [`fn withDivisor(divisor)`](#fn-specunsupportedpodtemplatespecinitcontainersenvvaluefromresourcefieldrefwithdivisor)
                * [`fn withResource(resource)`](#fn-specunsupportedpodtemplatespecinitcontainersenvvaluefromresourcefieldrefwithresource)
              * [`obj spec.unsupported.podTemplate.spec.initContainers.env.valueFrom.secretKeyRef`](#obj-specunsupportedpodtemplatespecinitcontainersenvvaluefromsecretkeyref)
                * [`fn withKey(key)`](#fn-specunsupportedpodtemplatespecinitcontainersenvvaluefromsecretkeyrefwithkey)
                * [`fn withName(name)`](#fn-specunsupportedpodtemplatespecinitcontainersenvvaluefromsecretkeyrefwithname)
                * [`fn withOptional(optional)`](#fn-specunsupportedpodtemplatespecinitcontainersenvvaluefromsecretkeyrefwithoptional)
          * [`obj spec.unsupported.podTemplate.spec.initContainers.envFrom`](#obj-specunsupportedpodtemplatespecinitcontainersenvfrom)
            * [`fn withPrefix(prefix)`](#fn-specunsupportedpodtemplatespecinitcontainersenvfromwithprefix)
            * [`obj spec.unsupported.podTemplate.spec.initContainers.envFrom.configMapRef`](#obj-specunsupportedpodtemplatespecinitcontainersenvfromconfigmapref)
              * [`fn withName(name)`](#fn-specunsupportedpodtemplatespecinitcontainersenvfromconfigmaprefwithname)
              * [`fn withOptional(optional)`](#fn-specunsupportedpodtemplatespecinitcontainersenvfromconfigmaprefwithoptional)
            * [`obj spec.unsupported.podTemplate.spec.initContainers.envFrom.secretRef`](#obj-specunsupportedpodtemplatespecinitcontainersenvfromsecretref)
              * [`fn withName(name)`](#fn-specunsupportedpodtemplatespecinitcontainersenvfromsecretrefwithname)
              * [`fn withOptional(optional)`](#fn-specunsupportedpodtemplatespecinitcontainersenvfromsecretrefwithoptional)
          * [`obj spec.unsupported.podTemplate.spec.initContainers.lifecycle`](#obj-specunsupportedpodtemplatespecinitcontainerslifecycle)
            * [`fn withStopSignal(stopSignal)`](#fn-specunsupportedpodtemplatespecinitcontainerslifecyclewithstopsignal)
            * [`obj spec.unsupported.podTemplate.spec.initContainers.lifecycle.postStart`](#obj-specunsupportedpodtemplatespecinitcontainerslifecyclepoststart)
              * [`obj spec.unsupported.podTemplate.spec.initContainers.lifecycle.postStart.exec`](#obj-specunsupportedpodtemplatespecinitcontainerslifecyclepoststartexec)
                * [`fn withCommand(command)`](#fn-specunsupportedpodtemplatespecinitcontainerslifecyclepoststartexecwithcommand)
                * [`fn withCommandMixin(command)`](#fn-specunsupportedpodtemplatespecinitcontainerslifecyclepoststartexecwithcommandmixin)
              * [`obj spec.unsupported.podTemplate.spec.initContainers.lifecycle.postStart.httpGet`](#obj-specunsupportedpodtemplatespecinitcontainerslifecyclepoststarthttpget)
                * [`fn withHost(host)`](#fn-specunsupportedpodtemplatespecinitcontainerslifecyclepoststarthttpgetwithhost)
                * [`fn withHttpHeaders(httpHeaders)`](#fn-specunsupportedpodtemplatespecinitcontainerslifecyclepoststarthttpgetwithhttpheaders)
                * [`fn withHttpHeadersMixin(httpHeaders)`](#fn-specunsupportedpodtemplatespecinitcontainerslifecyclepoststarthttpgetwithhttpheadersmixin)
                * [`fn withPath(path)`](#fn-specunsupportedpodtemplatespecinitcontainerslifecyclepoststarthttpgetwithpath)
                * [`fn withPort(port)`](#fn-specunsupportedpodtemplatespecinitcontainerslifecyclepoststarthttpgetwithport)
                * [`fn withScheme(scheme)`](#fn-specunsupportedpodtemplatespecinitcontainerslifecyclepoststarthttpgetwithscheme)
                * [`obj spec.unsupported.podTemplate.spec.initContainers.lifecycle.postStart.httpGet.httpHeaders`](#obj-specunsupportedpodtemplatespecinitcontainerslifecyclepoststarthttpgethttpheaders)
                  * [`fn withName(name)`](#fn-specunsupportedpodtemplatespecinitcontainerslifecyclepoststarthttpgethttpheaderswithname)
                  * [`fn withValue(value)`](#fn-specunsupportedpodtemplatespecinitcontainerslifecyclepoststarthttpgethttpheaderswithvalue)
              * [`obj spec.unsupported.podTemplate.spec.initContainers.lifecycle.postStart.sleep`](#obj-specunsupportedpodtemplatespecinitcontainerslifecyclepoststartsleep)
                * [`fn withSeconds(seconds)`](#fn-specunsupportedpodtemplatespecinitcontainerslifecyclepoststartsleepwithseconds)
              * [`obj spec.unsupported.podTemplate.spec.initContainers.lifecycle.postStart.tcpSocket`](#obj-specunsupportedpodtemplatespecinitcontainerslifecyclepoststarttcpsocket)
                * [`fn withHost(host)`](#fn-specunsupportedpodtemplatespecinitcontainerslifecyclepoststarttcpsocketwithhost)
                * [`fn withPort(port)`](#fn-specunsupportedpodtemplatespecinitcontainerslifecyclepoststarttcpsocketwithport)
            * [`obj spec.unsupported.podTemplate.spec.initContainers.lifecycle.preStop`](#obj-specunsupportedpodtemplatespecinitcontainerslifecycleprestop)
              * [`obj spec.unsupported.podTemplate.spec.initContainers.lifecycle.preStop.exec`](#obj-specunsupportedpodtemplatespecinitcontainerslifecycleprestopexec)
                * [`fn withCommand(command)`](#fn-specunsupportedpodtemplatespecinitcontainerslifecycleprestopexecwithcommand)
                * [`fn withCommandMixin(command)`](#fn-specunsupportedpodtemplatespecinitcontainerslifecycleprestopexecwithcommandmixin)
              * [`obj spec.unsupported.podTemplate.spec.initContainers.lifecycle.preStop.httpGet`](#obj-specunsupportedpodtemplatespecinitcontainerslifecycleprestophttpget)
                * [`fn withHost(host)`](#fn-specunsupportedpodtemplatespecinitcontainerslifecycleprestophttpgetwithhost)
                * [`fn withHttpHeaders(httpHeaders)`](#fn-specunsupportedpodtemplatespecinitcontainerslifecycleprestophttpgetwithhttpheaders)
                * [`fn withHttpHeadersMixin(httpHeaders)`](#fn-specunsupportedpodtemplatespecinitcontainerslifecycleprestophttpgetwithhttpheadersmixin)
                * [`fn withPath(path)`](#fn-specunsupportedpodtemplatespecinitcontainerslifecycleprestophttpgetwithpath)
                * [`fn withPort(port)`](#fn-specunsupportedpodtemplatespecinitcontainerslifecycleprestophttpgetwithport)
                * [`fn withScheme(scheme)`](#fn-specunsupportedpodtemplatespecinitcontainerslifecycleprestophttpgetwithscheme)
                * [`obj spec.unsupported.podTemplate.spec.initContainers.lifecycle.preStop.httpGet.httpHeaders`](#obj-specunsupportedpodtemplatespecinitcontainerslifecycleprestophttpgethttpheaders)
                  * [`fn withName(name)`](#fn-specunsupportedpodtemplatespecinitcontainerslifecycleprestophttpgethttpheaderswithname)
                  * [`fn withValue(value)`](#fn-specunsupportedpodtemplatespecinitcontainerslifecycleprestophttpgethttpheaderswithvalue)
              * [`obj spec.unsupported.podTemplate.spec.initContainers.lifecycle.preStop.sleep`](#obj-specunsupportedpodtemplatespecinitcontainerslifecycleprestopsleep)
                * [`fn withSeconds(seconds)`](#fn-specunsupportedpodtemplatespecinitcontainerslifecycleprestopsleepwithseconds)
              * [`obj spec.unsupported.podTemplate.spec.initContainers.lifecycle.preStop.tcpSocket`](#obj-specunsupportedpodtemplatespecinitcontainerslifecycleprestoptcpsocket)
                * [`fn withHost(host)`](#fn-specunsupportedpodtemplatespecinitcontainerslifecycleprestoptcpsocketwithhost)
                * [`fn withPort(port)`](#fn-specunsupportedpodtemplatespecinitcontainerslifecycleprestoptcpsocketwithport)
          * [`obj spec.unsupported.podTemplate.spec.initContainers.livenessProbe`](#obj-specunsupportedpodtemplatespecinitcontainerslivenessprobe)
            * [`fn withFailureThreshold(failureThreshold)`](#fn-specunsupportedpodtemplatespecinitcontainerslivenessprobewithfailurethreshold)
            * [`fn withInitialDelaySeconds(initialDelaySeconds)`](#fn-specunsupportedpodtemplatespecinitcontainerslivenessprobewithinitialdelayseconds)
            * [`fn withPeriodSeconds(periodSeconds)`](#fn-specunsupportedpodtemplatespecinitcontainerslivenessprobewithperiodseconds)
            * [`fn withSuccessThreshold(successThreshold)`](#fn-specunsupportedpodtemplatespecinitcontainerslivenessprobewithsuccessthreshold)
            * [`fn withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)`](#fn-specunsupportedpodtemplatespecinitcontainerslivenessprobewithterminationgraceperiodseconds)
            * [`fn withTimeoutSeconds(timeoutSeconds)`](#fn-specunsupportedpodtemplatespecinitcontainerslivenessprobewithtimeoutseconds)
            * [`obj spec.unsupported.podTemplate.spec.initContainers.livenessProbe.exec`](#obj-specunsupportedpodtemplatespecinitcontainerslivenessprobeexec)
              * [`fn withCommand(command)`](#fn-specunsupportedpodtemplatespecinitcontainerslivenessprobeexecwithcommand)
              * [`fn withCommandMixin(command)`](#fn-specunsupportedpodtemplatespecinitcontainerslivenessprobeexecwithcommandmixin)
            * [`obj spec.unsupported.podTemplate.spec.initContainers.livenessProbe.grpc`](#obj-specunsupportedpodtemplatespecinitcontainerslivenessprobegrpc)
              * [`fn withPort(port)`](#fn-specunsupportedpodtemplatespecinitcontainerslivenessprobegrpcwithport)
              * [`fn withService(service)`](#fn-specunsupportedpodtemplatespecinitcontainerslivenessprobegrpcwithservice)
            * [`obj spec.unsupported.podTemplate.spec.initContainers.livenessProbe.httpGet`](#obj-specunsupportedpodtemplatespecinitcontainerslivenessprobehttpget)
              * [`fn withHost(host)`](#fn-specunsupportedpodtemplatespecinitcontainerslivenessprobehttpgetwithhost)
              * [`fn withHttpHeaders(httpHeaders)`](#fn-specunsupportedpodtemplatespecinitcontainerslivenessprobehttpgetwithhttpheaders)
              * [`fn withHttpHeadersMixin(httpHeaders)`](#fn-specunsupportedpodtemplatespecinitcontainerslivenessprobehttpgetwithhttpheadersmixin)
              * [`fn withPath(path)`](#fn-specunsupportedpodtemplatespecinitcontainerslivenessprobehttpgetwithpath)
              * [`fn withPort(port)`](#fn-specunsupportedpodtemplatespecinitcontainerslivenessprobehttpgetwithport)
              * [`fn withScheme(scheme)`](#fn-specunsupportedpodtemplatespecinitcontainerslivenessprobehttpgetwithscheme)
              * [`obj spec.unsupported.podTemplate.spec.initContainers.livenessProbe.httpGet.httpHeaders`](#obj-specunsupportedpodtemplatespecinitcontainerslivenessprobehttpgethttpheaders)
                * [`fn withName(name)`](#fn-specunsupportedpodtemplatespecinitcontainerslivenessprobehttpgethttpheaderswithname)
                * [`fn withValue(value)`](#fn-specunsupportedpodtemplatespecinitcontainerslivenessprobehttpgethttpheaderswithvalue)
            * [`obj spec.unsupported.podTemplate.spec.initContainers.livenessProbe.tcpSocket`](#obj-specunsupportedpodtemplatespecinitcontainerslivenessprobetcpsocket)
              * [`fn withHost(host)`](#fn-specunsupportedpodtemplatespecinitcontainerslivenessprobetcpsocketwithhost)
              * [`fn withPort(port)`](#fn-specunsupportedpodtemplatespecinitcontainerslivenessprobetcpsocketwithport)
          * [`obj spec.unsupported.podTemplate.spec.initContainers.ports`](#obj-specunsupportedpodtemplatespecinitcontainersports)
            * [`fn withContainerPort(containerPort)`](#fn-specunsupportedpodtemplatespecinitcontainersportswithcontainerport)
            * [`fn withHostIP(hostIP)`](#fn-specunsupportedpodtemplatespecinitcontainersportswithhostip)
            * [`fn withHostPort(hostPort)`](#fn-specunsupportedpodtemplatespecinitcontainersportswithhostport)
            * [`fn withName(name)`](#fn-specunsupportedpodtemplatespecinitcontainersportswithname)
            * [`fn withProtocol(protocol)`](#fn-specunsupportedpodtemplatespecinitcontainersportswithprotocol)
          * [`obj spec.unsupported.podTemplate.spec.initContainers.readinessProbe`](#obj-specunsupportedpodtemplatespecinitcontainersreadinessprobe)
            * [`fn withFailureThreshold(failureThreshold)`](#fn-specunsupportedpodtemplatespecinitcontainersreadinessprobewithfailurethreshold)
            * [`fn withInitialDelaySeconds(initialDelaySeconds)`](#fn-specunsupportedpodtemplatespecinitcontainersreadinessprobewithinitialdelayseconds)
            * [`fn withPeriodSeconds(periodSeconds)`](#fn-specunsupportedpodtemplatespecinitcontainersreadinessprobewithperiodseconds)
            * [`fn withSuccessThreshold(successThreshold)`](#fn-specunsupportedpodtemplatespecinitcontainersreadinessprobewithsuccessthreshold)
            * [`fn withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)`](#fn-specunsupportedpodtemplatespecinitcontainersreadinessprobewithterminationgraceperiodseconds)
            * [`fn withTimeoutSeconds(timeoutSeconds)`](#fn-specunsupportedpodtemplatespecinitcontainersreadinessprobewithtimeoutseconds)
            * [`obj spec.unsupported.podTemplate.spec.initContainers.readinessProbe.exec`](#obj-specunsupportedpodtemplatespecinitcontainersreadinessprobeexec)
              * [`fn withCommand(command)`](#fn-specunsupportedpodtemplatespecinitcontainersreadinessprobeexecwithcommand)
              * [`fn withCommandMixin(command)`](#fn-specunsupportedpodtemplatespecinitcontainersreadinessprobeexecwithcommandmixin)
            * [`obj spec.unsupported.podTemplate.spec.initContainers.readinessProbe.grpc`](#obj-specunsupportedpodtemplatespecinitcontainersreadinessprobegrpc)
              * [`fn withPort(port)`](#fn-specunsupportedpodtemplatespecinitcontainersreadinessprobegrpcwithport)
              * [`fn withService(service)`](#fn-specunsupportedpodtemplatespecinitcontainersreadinessprobegrpcwithservice)
            * [`obj spec.unsupported.podTemplate.spec.initContainers.readinessProbe.httpGet`](#obj-specunsupportedpodtemplatespecinitcontainersreadinessprobehttpget)
              * [`fn withHost(host)`](#fn-specunsupportedpodtemplatespecinitcontainersreadinessprobehttpgetwithhost)
              * [`fn withHttpHeaders(httpHeaders)`](#fn-specunsupportedpodtemplatespecinitcontainersreadinessprobehttpgetwithhttpheaders)
              * [`fn withHttpHeadersMixin(httpHeaders)`](#fn-specunsupportedpodtemplatespecinitcontainersreadinessprobehttpgetwithhttpheadersmixin)
              * [`fn withPath(path)`](#fn-specunsupportedpodtemplatespecinitcontainersreadinessprobehttpgetwithpath)
              * [`fn withPort(port)`](#fn-specunsupportedpodtemplatespecinitcontainersreadinessprobehttpgetwithport)
              * [`fn withScheme(scheme)`](#fn-specunsupportedpodtemplatespecinitcontainersreadinessprobehttpgetwithscheme)
              * [`obj spec.unsupported.podTemplate.spec.initContainers.readinessProbe.httpGet.httpHeaders`](#obj-specunsupportedpodtemplatespecinitcontainersreadinessprobehttpgethttpheaders)
                * [`fn withName(name)`](#fn-specunsupportedpodtemplatespecinitcontainersreadinessprobehttpgethttpheaderswithname)
                * [`fn withValue(value)`](#fn-specunsupportedpodtemplatespecinitcontainersreadinessprobehttpgethttpheaderswithvalue)
            * [`obj spec.unsupported.podTemplate.spec.initContainers.readinessProbe.tcpSocket`](#obj-specunsupportedpodtemplatespecinitcontainersreadinessprobetcpsocket)
              * [`fn withHost(host)`](#fn-specunsupportedpodtemplatespecinitcontainersreadinessprobetcpsocketwithhost)
              * [`fn withPort(port)`](#fn-specunsupportedpodtemplatespecinitcontainersreadinessprobetcpsocketwithport)
          * [`obj spec.unsupported.podTemplate.spec.initContainers.resizePolicy`](#obj-specunsupportedpodtemplatespecinitcontainersresizepolicy)
            * [`fn withResourceName(resourceName)`](#fn-specunsupportedpodtemplatespecinitcontainersresizepolicywithresourcename)
            * [`fn withRestartPolicy(restartPolicy)`](#fn-specunsupportedpodtemplatespecinitcontainersresizepolicywithrestartpolicy)
          * [`obj spec.unsupported.podTemplate.spec.initContainers.resources`](#obj-specunsupportedpodtemplatespecinitcontainersresources)
            * [`fn withClaims(claims)`](#fn-specunsupportedpodtemplatespecinitcontainersresourceswithclaims)
            * [`fn withClaimsMixin(claims)`](#fn-specunsupportedpodtemplatespecinitcontainersresourceswithclaimsmixin)
            * [`fn withLimits(limits)`](#fn-specunsupportedpodtemplatespecinitcontainersresourceswithlimits)
            * [`fn withLimitsMixin(limits)`](#fn-specunsupportedpodtemplatespecinitcontainersresourceswithlimitsmixin)
            * [`fn withRequests(requests)`](#fn-specunsupportedpodtemplatespecinitcontainersresourceswithrequests)
            * [`fn withRequestsMixin(requests)`](#fn-specunsupportedpodtemplatespecinitcontainersresourceswithrequestsmixin)
            * [`obj spec.unsupported.podTemplate.spec.initContainers.resources.claims`](#obj-specunsupportedpodtemplatespecinitcontainersresourcesclaims)
              * [`fn withName(name)`](#fn-specunsupportedpodtemplatespecinitcontainersresourcesclaimswithname)
              * [`fn withRequest(request)`](#fn-specunsupportedpodtemplatespecinitcontainersresourcesclaimswithrequest)
          * [`obj spec.unsupported.podTemplate.spec.initContainers.securityContext`](#obj-specunsupportedpodtemplatespecinitcontainerssecuritycontext)
            * [`fn withAllowPrivilegeEscalation(allowPrivilegeEscalation)`](#fn-specunsupportedpodtemplatespecinitcontainerssecuritycontextwithallowprivilegeescalation)
            * [`fn withPrivileged(privileged)`](#fn-specunsupportedpodtemplatespecinitcontainerssecuritycontextwithprivileged)
            * [`fn withProcMount(procMount)`](#fn-specunsupportedpodtemplatespecinitcontainerssecuritycontextwithprocmount)
            * [`fn withReadOnlyRootFilesystem(readOnlyRootFilesystem)`](#fn-specunsupportedpodtemplatespecinitcontainerssecuritycontextwithreadonlyrootfilesystem)
            * [`fn withRunAsGroup(runAsGroup)`](#fn-specunsupportedpodtemplatespecinitcontainerssecuritycontextwithrunasgroup)
            * [`fn withRunAsNonRoot(runAsNonRoot)`](#fn-specunsupportedpodtemplatespecinitcontainerssecuritycontextwithrunasnonroot)
            * [`fn withRunAsUser(runAsUser)`](#fn-specunsupportedpodtemplatespecinitcontainerssecuritycontextwithrunasuser)
            * [`obj spec.unsupported.podTemplate.spec.initContainers.securityContext.appArmorProfile`](#obj-specunsupportedpodtemplatespecinitcontainerssecuritycontextapparmorprofile)
              * [`fn withLocalhostProfile(localhostProfile)`](#fn-specunsupportedpodtemplatespecinitcontainerssecuritycontextapparmorprofilewithlocalhostprofile)
              * [`fn withType(type)`](#fn-specunsupportedpodtemplatespecinitcontainerssecuritycontextapparmorprofilewithtype)
            * [`obj spec.unsupported.podTemplate.spec.initContainers.securityContext.capabilities`](#obj-specunsupportedpodtemplatespecinitcontainerssecuritycontextcapabilities)
              * [`fn withAdd(add)`](#fn-specunsupportedpodtemplatespecinitcontainerssecuritycontextcapabilitieswithadd)
              * [`fn withAddMixin(add)`](#fn-specunsupportedpodtemplatespecinitcontainerssecuritycontextcapabilitieswithaddmixin)
              * [`fn withDrop(drop)`](#fn-specunsupportedpodtemplatespecinitcontainerssecuritycontextcapabilitieswithdrop)
              * [`fn withDropMixin(drop)`](#fn-specunsupportedpodtemplatespecinitcontainerssecuritycontextcapabilitieswithdropmixin)
            * [`obj spec.unsupported.podTemplate.spec.initContainers.securityContext.seLinuxOptions`](#obj-specunsupportedpodtemplatespecinitcontainerssecuritycontextselinuxoptions)
              * [`fn withLevel(level)`](#fn-specunsupportedpodtemplatespecinitcontainerssecuritycontextselinuxoptionswithlevel)
              * [`fn withRole(role)`](#fn-specunsupportedpodtemplatespecinitcontainerssecuritycontextselinuxoptionswithrole)
              * [`fn withType(type)`](#fn-specunsupportedpodtemplatespecinitcontainerssecuritycontextselinuxoptionswithtype)
              * [`fn withUser(user)`](#fn-specunsupportedpodtemplatespecinitcontainerssecuritycontextselinuxoptionswithuser)
            * [`obj spec.unsupported.podTemplate.spec.initContainers.securityContext.seccompProfile`](#obj-specunsupportedpodtemplatespecinitcontainerssecuritycontextseccompprofile)
              * [`fn withLocalhostProfile(localhostProfile)`](#fn-specunsupportedpodtemplatespecinitcontainerssecuritycontextseccompprofilewithlocalhostprofile)
              * [`fn withType(type)`](#fn-specunsupportedpodtemplatespecinitcontainerssecuritycontextseccompprofilewithtype)
            * [`obj spec.unsupported.podTemplate.spec.initContainers.securityContext.windowsOptions`](#obj-specunsupportedpodtemplatespecinitcontainerssecuritycontextwindowsoptions)
              * [`fn withGmsaCredentialSpec(gmsaCredentialSpec)`](#fn-specunsupportedpodtemplatespecinitcontainerssecuritycontextwindowsoptionswithgmsacredentialspec)
              * [`fn withGmsaCredentialSpecName(gmsaCredentialSpecName)`](#fn-specunsupportedpodtemplatespecinitcontainerssecuritycontextwindowsoptionswithgmsacredentialspecname)
              * [`fn withHostProcess(hostProcess)`](#fn-specunsupportedpodtemplatespecinitcontainerssecuritycontextwindowsoptionswithhostprocess)
              * [`fn withRunAsUserName(runAsUserName)`](#fn-specunsupportedpodtemplatespecinitcontainerssecuritycontextwindowsoptionswithrunasusername)
          * [`obj spec.unsupported.podTemplate.spec.initContainers.startupProbe`](#obj-specunsupportedpodtemplatespecinitcontainersstartupprobe)
            * [`fn withFailureThreshold(failureThreshold)`](#fn-specunsupportedpodtemplatespecinitcontainersstartupprobewithfailurethreshold)
            * [`fn withInitialDelaySeconds(initialDelaySeconds)`](#fn-specunsupportedpodtemplatespecinitcontainersstartupprobewithinitialdelayseconds)
            * [`fn withPeriodSeconds(periodSeconds)`](#fn-specunsupportedpodtemplatespecinitcontainersstartupprobewithperiodseconds)
            * [`fn withSuccessThreshold(successThreshold)`](#fn-specunsupportedpodtemplatespecinitcontainersstartupprobewithsuccessthreshold)
            * [`fn withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)`](#fn-specunsupportedpodtemplatespecinitcontainersstartupprobewithterminationgraceperiodseconds)
            * [`fn withTimeoutSeconds(timeoutSeconds)`](#fn-specunsupportedpodtemplatespecinitcontainersstartupprobewithtimeoutseconds)
            * [`obj spec.unsupported.podTemplate.spec.initContainers.startupProbe.exec`](#obj-specunsupportedpodtemplatespecinitcontainersstartupprobeexec)
              * [`fn withCommand(command)`](#fn-specunsupportedpodtemplatespecinitcontainersstartupprobeexecwithcommand)
              * [`fn withCommandMixin(command)`](#fn-specunsupportedpodtemplatespecinitcontainersstartupprobeexecwithcommandmixin)
            * [`obj spec.unsupported.podTemplate.spec.initContainers.startupProbe.grpc`](#obj-specunsupportedpodtemplatespecinitcontainersstartupprobegrpc)
              * [`fn withPort(port)`](#fn-specunsupportedpodtemplatespecinitcontainersstartupprobegrpcwithport)
              * [`fn withService(service)`](#fn-specunsupportedpodtemplatespecinitcontainersstartupprobegrpcwithservice)
            * [`obj spec.unsupported.podTemplate.spec.initContainers.startupProbe.httpGet`](#obj-specunsupportedpodtemplatespecinitcontainersstartupprobehttpget)
              * [`fn withHost(host)`](#fn-specunsupportedpodtemplatespecinitcontainersstartupprobehttpgetwithhost)
              * [`fn withHttpHeaders(httpHeaders)`](#fn-specunsupportedpodtemplatespecinitcontainersstartupprobehttpgetwithhttpheaders)
              * [`fn withHttpHeadersMixin(httpHeaders)`](#fn-specunsupportedpodtemplatespecinitcontainersstartupprobehttpgetwithhttpheadersmixin)
              * [`fn withPath(path)`](#fn-specunsupportedpodtemplatespecinitcontainersstartupprobehttpgetwithpath)
              * [`fn withPort(port)`](#fn-specunsupportedpodtemplatespecinitcontainersstartupprobehttpgetwithport)
              * [`fn withScheme(scheme)`](#fn-specunsupportedpodtemplatespecinitcontainersstartupprobehttpgetwithscheme)
              * [`obj spec.unsupported.podTemplate.spec.initContainers.startupProbe.httpGet.httpHeaders`](#obj-specunsupportedpodtemplatespecinitcontainersstartupprobehttpgethttpheaders)
                * [`fn withName(name)`](#fn-specunsupportedpodtemplatespecinitcontainersstartupprobehttpgethttpheaderswithname)
                * [`fn withValue(value)`](#fn-specunsupportedpodtemplatespecinitcontainersstartupprobehttpgethttpheaderswithvalue)
            * [`obj spec.unsupported.podTemplate.spec.initContainers.startupProbe.tcpSocket`](#obj-specunsupportedpodtemplatespecinitcontainersstartupprobetcpsocket)
              * [`fn withHost(host)`](#fn-specunsupportedpodtemplatespecinitcontainersstartupprobetcpsocketwithhost)
              * [`fn withPort(port)`](#fn-specunsupportedpodtemplatespecinitcontainersstartupprobetcpsocketwithport)
          * [`obj spec.unsupported.podTemplate.spec.initContainers.volumeDevices`](#obj-specunsupportedpodtemplatespecinitcontainersvolumedevices)
            * [`fn withDevicePath(devicePath)`](#fn-specunsupportedpodtemplatespecinitcontainersvolumedeviceswithdevicepath)
            * [`fn withName(name)`](#fn-specunsupportedpodtemplatespecinitcontainersvolumedeviceswithname)
          * [`obj spec.unsupported.podTemplate.spec.initContainers.volumeMounts`](#obj-specunsupportedpodtemplatespecinitcontainersvolumemounts)
            * [`fn withMountPath(mountPath)`](#fn-specunsupportedpodtemplatespecinitcontainersvolumemountswithmountpath)
            * [`fn withMountPropagation(mountPropagation)`](#fn-specunsupportedpodtemplatespecinitcontainersvolumemountswithmountpropagation)
            * [`fn withName(name)`](#fn-specunsupportedpodtemplatespecinitcontainersvolumemountswithname)
            * [`fn withReadOnly(readOnly)`](#fn-specunsupportedpodtemplatespecinitcontainersvolumemountswithreadonly)
            * [`fn withRecursiveReadOnly(recursiveReadOnly)`](#fn-specunsupportedpodtemplatespecinitcontainersvolumemountswithrecursivereadonly)
            * [`fn withSubPath(subPath)`](#fn-specunsupportedpodtemplatespecinitcontainersvolumemountswithsubpath)
            * [`fn withSubPathExpr(subPathExpr)`](#fn-specunsupportedpodtemplatespecinitcontainersvolumemountswithsubpathexpr)
        * [`obj spec.unsupported.podTemplate.spec.os`](#obj-specunsupportedpodtemplatespecos)
          * [`fn withName(name)`](#fn-specunsupportedpodtemplatespecoswithname)
        * [`obj spec.unsupported.podTemplate.spec.readinessGates`](#obj-specunsupportedpodtemplatespecreadinessgates)
          * [`fn withConditionType(conditionType)`](#fn-specunsupportedpodtemplatespecreadinessgateswithconditiontype)
        * [`obj spec.unsupported.podTemplate.spec.resourceClaims`](#obj-specunsupportedpodtemplatespecresourceclaims)
          * [`fn withName(name)`](#fn-specunsupportedpodtemplatespecresourceclaimswithname)
          * [`fn withResourceClaimName(resourceClaimName)`](#fn-specunsupportedpodtemplatespecresourceclaimswithresourceclaimname)
          * [`fn withResourceClaimTemplateName(resourceClaimTemplateName)`](#fn-specunsupportedpodtemplatespecresourceclaimswithresourceclaimtemplatename)
        * [`obj spec.unsupported.podTemplate.spec.resources`](#obj-specunsupportedpodtemplatespecresources)
          * [`fn withClaims(claims)`](#fn-specunsupportedpodtemplatespecresourceswithclaims)
          * [`fn withClaimsMixin(claims)`](#fn-specunsupportedpodtemplatespecresourceswithclaimsmixin)
          * [`fn withLimits(limits)`](#fn-specunsupportedpodtemplatespecresourceswithlimits)
          * [`fn withLimitsMixin(limits)`](#fn-specunsupportedpodtemplatespecresourceswithlimitsmixin)
          * [`fn withRequests(requests)`](#fn-specunsupportedpodtemplatespecresourceswithrequests)
          * [`fn withRequestsMixin(requests)`](#fn-specunsupportedpodtemplatespecresourceswithrequestsmixin)
          * [`obj spec.unsupported.podTemplate.spec.resources.claims`](#obj-specunsupportedpodtemplatespecresourcesclaims)
            * [`fn withName(name)`](#fn-specunsupportedpodtemplatespecresourcesclaimswithname)
            * [`fn withRequest(request)`](#fn-specunsupportedpodtemplatespecresourcesclaimswithrequest)
        * [`obj spec.unsupported.podTemplate.spec.schedulingGates`](#obj-specunsupportedpodtemplatespecschedulinggates)
          * [`fn withName(name)`](#fn-specunsupportedpodtemplatespecschedulinggateswithname)
        * [`obj spec.unsupported.podTemplate.spec.securityContext`](#obj-specunsupportedpodtemplatespecsecuritycontext)
          * [`fn withFsGroup(fsGroup)`](#fn-specunsupportedpodtemplatespecsecuritycontextwithfsgroup)
          * [`fn withFsGroupChangePolicy(fsGroupChangePolicy)`](#fn-specunsupportedpodtemplatespecsecuritycontextwithfsgroupchangepolicy)
          * [`fn withRunAsGroup(runAsGroup)`](#fn-specunsupportedpodtemplatespecsecuritycontextwithrunasgroup)
          * [`fn withRunAsNonRoot(runAsNonRoot)`](#fn-specunsupportedpodtemplatespecsecuritycontextwithrunasnonroot)
          * [`fn withRunAsUser(runAsUser)`](#fn-specunsupportedpodtemplatespecsecuritycontextwithrunasuser)
          * [`fn withSeLinuxChangePolicy(seLinuxChangePolicy)`](#fn-specunsupportedpodtemplatespecsecuritycontextwithselinuxchangepolicy)
          * [`fn withSupplementalGroups(supplementalGroups)`](#fn-specunsupportedpodtemplatespecsecuritycontextwithsupplementalgroups)
          * [`fn withSupplementalGroupsMixin(supplementalGroups)`](#fn-specunsupportedpodtemplatespecsecuritycontextwithsupplementalgroupsmixin)
          * [`fn withSupplementalGroupsPolicy(supplementalGroupsPolicy)`](#fn-specunsupportedpodtemplatespecsecuritycontextwithsupplementalgroupspolicy)
          * [`fn withSysctls(sysctls)`](#fn-specunsupportedpodtemplatespecsecuritycontextwithsysctls)
          * [`fn withSysctlsMixin(sysctls)`](#fn-specunsupportedpodtemplatespecsecuritycontextwithsysctlsmixin)
          * [`obj spec.unsupported.podTemplate.spec.securityContext.appArmorProfile`](#obj-specunsupportedpodtemplatespecsecuritycontextapparmorprofile)
            * [`fn withLocalhostProfile(localhostProfile)`](#fn-specunsupportedpodtemplatespecsecuritycontextapparmorprofilewithlocalhostprofile)
            * [`fn withType(type)`](#fn-specunsupportedpodtemplatespecsecuritycontextapparmorprofilewithtype)
          * [`obj spec.unsupported.podTemplate.spec.securityContext.seLinuxOptions`](#obj-specunsupportedpodtemplatespecsecuritycontextselinuxoptions)
            * [`fn withLevel(level)`](#fn-specunsupportedpodtemplatespecsecuritycontextselinuxoptionswithlevel)
            * [`fn withRole(role)`](#fn-specunsupportedpodtemplatespecsecuritycontextselinuxoptionswithrole)
            * [`fn withType(type)`](#fn-specunsupportedpodtemplatespecsecuritycontextselinuxoptionswithtype)
            * [`fn withUser(user)`](#fn-specunsupportedpodtemplatespecsecuritycontextselinuxoptionswithuser)
          * [`obj spec.unsupported.podTemplate.spec.securityContext.seccompProfile`](#obj-specunsupportedpodtemplatespecsecuritycontextseccompprofile)
            * [`fn withLocalhostProfile(localhostProfile)`](#fn-specunsupportedpodtemplatespecsecuritycontextseccompprofilewithlocalhostprofile)
            * [`fn withType(type)`](#fn-specunsupportedpodtemplatespecsecuritycontextseccompprofilewithtype)
          * [`obj spec.unsupported.podTemplate.spec.securityContext.sysctls`](#obj-specunsupportedpodtemplatespecsecuritycontextsysctls)
            * [`fn withName(name)`](#fn-specunsupportedpodtemplatespecsecuritycontextsysctlswithname)
            * [`fn withValue(value)`](#fn-specunsupportedpodtemplatespecsecuritycontextsysctlswithvalue)
          * [`obj spec.unsupported.podTemplate.spec.securityContext.windowsOptions`](#obj-specunsupportedpodtemplatespecsecuritycontextwindowsoptions)
            * [`fn withGmsaCredentialSpec(gmsaCredentialSpec)`](#fn-specunsupportedpodtemplatespecsecuritycontextwindowsoptionswithgmsacredentialspec)
            * [`fn withGmsaCredentialSpecName(gmsaCredentialSpecName)`](#fn-specunsupportedpodtemplatespecsecuritycontextwindowsoptionswithgmsacredentialspecname)
            * [`fn withHostProcess(hostProcess)`](#fn-specunsupportedpodtemplatespecsecuritycontextwindowsoptionswithhostprocess)
            * [`fn withRunAsUserName(runAsUserName)`](#fn-specunsupportedpodtemplatespecsecuritycontextwindowsoptionswithrunasusername)
        * [`obj spec.unsupported.podTemplate.spec.tolerations`](#obj-specunsupportedpodtemplatespectolerations)
          * [`fn withEffect(effect)`](#fn-specunsupportedpodtemplatespectolerationswitheffect)
          * [`fn withKey(key)`](#fn-specunsupportedpodtemplatespectolerationswithkey)
          * [`fn withOperator(operator)`](#fn-specunsupportedpodtemplatespectolerationswithoperator)
          * [`fn withTolerationSeconds(tolerationSeconds)`](#fn-specunsupportedpodtemplatespectolerationswithtolerationseconds)
          * [`fn withValue(value)`](#fn-specunsupportedpodtemplatespectolerationswithvalue)
        * [`obj spec.unsupported.podTemplate.spec.topologySpreadConstraints`](#obj-specunsupportedpodtemplatespectopologyspreadconstraints)
          * [`fn withMatchLabelKeys(matchLabelKeys)`](#fn-specunsupportedpodtemplatespectopologyspreadconstraintswithmatchlabelkeys)
          * [`fn withMatchLabelKeysMixin(matchLabelKeys)`](#fn-specunsupportedpodtemplatespectopologyspreadconstraintswithmatchlabelkeysmixin)
          * [`fn withMaxSkew(maxSkew)`](#fn-specunsupportedpodtemplatespectopologyspreadconstraintswithmaxskew)
          * [`fn withMinDomains(minDomains)`](#fn-specunsupportedpodtemplatespectopologyspreadconstraintswithmindomains)
          * [`fn withNodeAffinityPolicy(nodeAffinityPolicy)`](#fn-specunsupportedpodtemplatespectopologyspreadconstraintswithnodeaffinitypolicy)
          * [`fn withNodeTaintsPolicy(nodeTaintsPolicy)`](#fn-specunsupportedpodtemplatespectopologyspreadconstraintswithnodetaintspolicy)
          * [`fn withTopologyKey(topologyKey)`](#fn-specunsupportedpodtemplatespectopologyspreadconstraintswithtopologykey)
          * [`fn withWhenUnsatisfiable(whenUnsatisfiable)`](#fn-specunsupportedpodtemplatespectopologyspreadconstraintswithwhenunsatisfiable)
          * [`obj spec.unsupported.podTemplate.spec.topologySpreadConstraints.labelSelector`](#obj-specunsupportedpodtemplatespectopologyspreadconstraintslabelselector)
            * [`fn withMatchExpressions(matchExpressions)`](#fn-specunsupportedpodtemplatespectopologyspreadconstraintslabelselectorwithmatchexpressions)
            * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specunsupportedpodtemplatespectopologyspreadconstraintslabelselectorwithmatchexpressionsmixin)
            * [`fn withMatchLabels(matchLabels)`](#fn-specunsupportedpodtemplatespectopologyspreadconstraintslabelselectorwithmatchlabels)
            * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specunsupportedpodtemplatespectopologyspreadconstraintslabelselectorwithmatchlabelsmixin)
            * [`obj spec.unsupported.podTemplate.spec.topologySpreadConstraints.labelSelector.matchExpressions`](#obj-specunsupportedpodtemplatespectopologyspreadconstraintslabelselectormatchexpressions)
              * [`fn withKey(key)`](#fn-specunsupportedpodtemplatespectopologyspreadconstraintslabelselectormatchexpressionswithkey)
              * [`fn withOperator(operator)`](#fn-specunsupportedpodtemplatespectopologyspreadconstraintslabelselectormatchexpressionswithoperator)
              * [`fn withValues(values)`](#fn-specunsupportedpodtemplatespectopologyspreadconstraintslabelselectormatchexpressionswithvalues)
              * [`fn withValuesMixin(values)`](#fn-specunsupportedpodtemplatespectopologyspreadconstraintslabelselectormatchexpressionswithvaluesmixin)
        * [`obj spec.unsupported.podTemplate.spec.volumes`](#obj-specunsupportedpodtemplatespecvolumes)
          * [`fn withName(name)`](#fn-specunsupportedpodtemplatespecvolumeswithname)
          * [`obj spec.unsupported.podTemplate.spec.volumes.awsElasticBlockStore`](#obj-specunsupportedpodtemplatespecvolumesawselasticblockstore)
            * [`fn withFsType(fsType)`](#fn-specunsupportedpodtemplatespecvolumesawselasticblockstorewithfstype)
            * [`fn withPartition(partition)`](#fn-specunsupportedpodtemplatespecvolumesawselasticblockstorewithpartition)
            * [`fn withReadOnly(readOnly)`](#fn-specunsupportedpodtemplatespecvolumesawselasticblockstorewithreadonly)
            * [`fn withVolumeID(volumeID)`](#fn-specunsupportedpodtemplatespecvolumesawselasticblockstorewithvolumeid)
          * [`obj spec.unsupported.podTemplate.spec.volumes.azureDisk`](#obj-specunsupportedpodtemplatespecvolumesazuredisk)
            * [`fn withCachingMode(cachingMode)`](#fn-specunsupportedpodtemplatespecvolumesazurediskwithcachingmode)
            * [`fn withDiskName(diskName)`](#fn-specunsupportedpodtemplatespecvolumesazurediskwithdiskname)
            * [`fn withDiskURI(diskURI)`](#fn-specunsupportedpodtemplatespecvolumesazurediskwithdiskuri)
            * [`fn withFsType(fsType)`](#fn-specunsupportedpodtemplatespecvolumesazurediskwithfstype)
            * [`fn withKind(kind)`](#fn-specunsupportedpodtemplatespecvolumesazurediskwithkind)
            * [`fn withReadOnly(readOnly)`](#fn-specunsupportedpodtemplatespecvolumesazurediskwithreadonly)
          * [`obj spec.unsupported.podTemplate.spec.volumes.azureFile`](#obj-specunsupportedpodtemplatespecvolumesazurefile)
            * [`fn withReadOnly(readOnly)`](#fn-specunsupportedpodtemplatespecvolumesazurefilewithreadonly)
            * [`fn withSecretName(secretName)`](#fn-specunsupportedpodtemplatespecvolumesazurefilewithsecretname)
            * [`fn withShareName(shareName)`](#fn-specunsupportedpodtemplatespecvolumesazurefilewithsharename)
          * [`obj spec.unsupported.podTemplate.spec.volumes.cephfs`](#obj-specunsupportedpodtemplatespecvolumescephfs)
            * [`fn withMonitors(monitors)`](#fn-specunsupportedpodtemplatespecvolumescephfswithmonitors)
            * [`fn withMonitorsMixin(monitors)`](#fn-specunsupportedpodtemplatespecvolumescephfswithmonitorsmixin)
            * [`fn withPath(path)`](#fn-specunsupportedpodtemplatespecvolumescephfswithpath)
            * [`fn withReadOnly(readOnly)`](#fn-specunsupportedpodtemplatespecvolumescephfswithreadonly)
            * [`fn withSecretFile(secretFile)`](#fn-specunsupportedpodtemplatespecvolumescephfswithsecretfile)
            * [`fn withUser(user)`](#fn-specunsupportedpodtemplatespecvolumescephfswithuser)
            * [`obj spec.unsupported.podTemplate.spec.volumes.cephfs.secretRef`](#obj-specunsupportedpodtemplatespecvolumescephfssecretref)
              * [`fn withName(name)`](#fn-specunsupportedpodtemplatespecvolumescephfssecretrefwithname)
          * [`obj spec.unsupported.podTemplate.spec.volumes.cinder`](#obj-specunsupportedpodtemplatespecvolumescinder)
            * [`fn withFsType(fsType)`](#fn-specunsupportedpodtemplatespecvolumescinderwithfstype)
            * [`fn withReadOnly(readOnly)`](#fn-specunsupportedpodtemplatespecvolumescinderwithreadonly)
            * [`fn withVolumeID(volumeID)`](#fn-specunsupportedpodtemplatespecvolumescinderwithvolumeid)
            * [`obj spec.unsupported.podTemplate.spec.volumes.cinder.secretRef`](#obj-specunsupportedpodtemplatespecvolumescindersecretref)
              * [`fn withName(name)`](#fn-specunsupportedpodtemplatespecvolumescindersecretrefwithname)
          * [`obj spec.unsupported.podTemplate.spec.volumes.configMap`](#obj-specunsupportedpodtemplatespecvolumesconfigmap)
            * [`fn withDefaultMode(defaultMode)`](#fn-specunsupportedpodtemplatespecvolumesconfigmapwithdefaultmode)
            * [`fn withItems(items)`](#fn-specunsupportedpodtemplatespecvolumesconfigmapwithitems)
            * [`fn withItemsMixin(items)`](#fn-specunsupportedpodtemplatespecvolumesconfigmapwithitemsmixin)
            * [`fn withName(name)`](#fn-specunsupportedpodtemplatespecvolumesconfigmapwithname)
            * [`fn withOptional(optional)`](#fn-specunsupportedpodtemplatespecvolumesconfigmapwithoptional)
            * [`obj spec.unsupported.podTemplate.spec.volumes.configMap.items`](#obj-specunsupportedpodtemplatespecvolumesconfigmapitems)
              * [`fn withKey(key)`](#fn-specunsupportedpodtemplatespecvolumesconfigmapitemswithkey)
              * [`fn withMode(mode)`](#fn-specunsupportedpodtemplatespecvolumesconfigmapitemswithmode)
              * [`fn withPath(path)`](#fn-specunsupportedpodtemplatespecvolumesconfigmapitemswithpath)
          * [`obj spec.unsupported.podTemplate.spec.volumes.csi`](#obj-specunsupportedpodtemplatespecvolumescsi)
            * [`fn withDriver(driver)`](#fn-specunsupportedpodtemplatespecvolumescsiwithdriver)
            * [`fn withFsType(fsType)`](#fn-specunsupportedpodtemplatespecvolumescsiwithfstype)
            * [`fn withReadOnly(readOnly)`](#fn-specunsupportedpodtemplatespecvolumescsiwithreadonly)
            * [`fn withVolumeAttributes(volumeAttributes)`](#fn-specunsupportedpodtemplatespecvolumescsiwithvolumeattributes)
            * [`fn withVolumeAttributesMixin(volumeAttributes)`](#fn-specunsupportedpodtemplatespecvolumescsiwithvolumeattributesmixin)
            * [`obj spec.unsupported.podTemplate.spec.volumes.csi.nodePublishSecretRef`](#obj-specunsupportedpodtemplatespecvolumescsinodepublishsecretref)
              * [`fn withName(name)`](#fn-specunsupportedpodtemplatespecvolumescsinodepublishsecretrefwithname)
          * [`obj spec.unsupported.podTemplate.spec.volumes.downwardAPI`](#obj-specunsupportedpodtemplatespecvolumesdownwardapi)
            * [`fn withDefaultMode(defaultMode)`](#fn-specunsupportedpodtemplatespecvolumesdownwardapiwithdefaultmode)
            * [`fn withItems(items)`](#fn-specunsupportedpodtemplatespecvolumesdownwardapiwithitems)
            * [`fn withItemsMixin(items)`](#fn-specunsupportedpodtemplatespecvolumesdownwardapiwithitemsmixin)
            * [`obj spec.unsupported.podTemplate.spec.volumes.downwardAPI.items`](#obj-specunsupportedpodtemplatespecvolumesdownwardapiitems)
              * [`fn withMode(mode)`](#fn-specunsupportedpodtemplatespecvolumesdownwardapiitemswithmode)
              * [`fn withPath(path)`](#fn-specunsupportedpodtemplatespecvolumesdownwardapiitemswithpath)
              * [`obj spec.unsupported.podTemplate.spec.volumes.downwardAPI.items.fieldRef`](#obj-specunsupportedpodtemplatespecvolumesdownwardapiitemsfieldref)
                * [`fn withApiVersion(apiVersion)`](#fn-specunsupportedpodtemplatespecvolumesdownwardapiitemsfieldrefwithapiversion)
                * [`fn withFieldPath(fieldPath)`](#fn-specunsupportedpodtemplatespecvolumesdownwardapiitemsfieldrefwithfieldpath)
              * [`obj spec.unsupported.podTemplate.spec.volumes.downwardAPI.items.resourceFieldRef`](#obj-specunsupportedpodtemplatespecvolumesdownwardapiitemsresourcefieldref)
                * [`fn withContainerName(containerName)`](#fn-specunsupportedpodtemplatespecvolumesdownwardapiitemsresourcefieldrefwithcontainername)
                * [`fn withDivisor(divisor)`](#fn-specunsupportedpodtemplatespecvolumesdownwardapiitemsresourcefieldrefwithdivisor)
                * [`fn withResource(resource)`](#fn-specunsupportedpodtemplatespecvolumesdownwardapiitemsresourcefieldrefwithresource)
          * [`obj spec.unsupported.podTemplate.spec.volumes.emptyDir`](#obj-specunsupportedpodtemplatespecvolumesemptydir)
            * [`fn withMedium(medium)`](#fn-specunsupportedpodtemplatespecvolumesemptydirwithmedium)
            * [`fn withSizeLimit(sizeLimit)`](#fn-specunsupportedpodtemplatespecvolumesemptydirwithsizelimit)
          * [`obj spec.unsupported.podTemplate.spec.volumes.ephemeral`](#obj-specunsupportedpodtemplatespecvolumesephemeral)
            * [`obj spec.unsupported.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate`](#obj-specunsupportedpodtemplatespecvolumesephemeralvolumeclaimtemplate)
              * [`obj spec.unsupported.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.metadata`](#obj-specunsupportedpodtemplatespecvolumesephemeralvolumeclaimtemplatemetadata)
                * [`fn withAnnotations(annotations)`](#fn-specunsupportedpodtemplatespecvolumesephemeralvolumeclaimtemplatemetadatawithannotations)
                * [`fn withAnnotationsMixin(annotations)`](#fn-specunsupportedpodtemplatespecvolumesephemeralvolumeclaimtemplatemetadatawithannotationsmixin)
                * [`fn withCreationTimestamp(creationTimestamp)`](#fn-specunsupportedpodtemplatespecvolumesephemeralvolumeclaimtemplatemetadatawithcreationtimestamp)
                * [`fn withDeletionGracePeriodSeconds(deletionGracePeriodSeconds)`](#fn-specunsupportedpodtemplatespecvolumesephemeralvolumeclaimtemplatemetadatawithdeletiongraceperiodseconds)
                * [`fn withDeletionTimestamp(deletionTimestamp)`](#fn-specunsupportedpodtemplatespecvolumesephemeralvolumeclaimtemplatemetadatawithdeletiontimestamp)
                * [`fn withFinalizers(finalizers)`](#fn-specunsupportedpodtemplatespecvolumesephemeralvolumeclaimtemplatemetadatawithfinalizers)
                * [`fn withFinalizersMixin(finalizers)`](#fn-specunsupportedpodtemplatespecvolumesephemeralvolumeclaimtemplatemetadatawithfinalizersmixin)
                * [`fn withGenerateName(generateName)`](#fn-specunsupportedpodtemplatespecvolumesephemeralvolumeclaimtemplatemetadatawithgeneratename)
                * [`fn withGeneration(generation)`](#fn-specunsupportedpodtemplatespecvolumesephemeralvolumeclaimtemplatemetadatawithgeneration)
                * [`fn withLabels(labels)`](#fn-specunsupportedpodtemplatespecvolumesephemeralvolumeclaimtemplatemetadatawithlabels)
                * [`fn withLabelsMixin(labels)`](#fn-specunsupportedpodtemplatespecvolumesephemeralvolumeclaimtemplatemetadatawithlabelsmixin)
                * [`fn withManagedFields(managedFields)`](#fn-specunsupportedpodtemplatespecvolumesephemeralvolumeclaimtemplatemetadatawithmanagedfields)
                * [`fn withManagedFieldsMixin(managedFields)`](#fn-specunsupportedpodtemplatespecvolumesephemeralvolumeclaimtemplatemetadatawithmanagedfieldsmixin)
                * [`fn withName(name)`](#fn-specunsupportedpodtemplatespecvolumesephemeralvolumeclaimtemplatemetadatawithname)
                * [`fn withNamespace(namespace)`](#fn-specunsupportedpodtemplatespecvolumesephemeralvolumeclaimtemplatemetadatawithnamespace)
                * [`fn withOwnerReferences(ownerReferences)`](#fn-specunsupportedpodtemplatespecvolumesephemeralvolumeclaimtemplatemetadatawithownerreferences)
                * [`fn withOwnerReferencesMixin(ownerReferences)`](#fn-specunsupportedpodtemplatespecvolumesephemeralvolumeclaimtemplatemetadatawithownerreferencesmixin)
                * [`fn withResourceVersion(resourceVersion)`](#fn-specunsupportedpodtemplatespecvolumesephemeralvolumeclaimtemplatemetadatawithresourceversion)
                * [`fn withSelfLink(selfLink)`](#fn-specunsupportedpodtemplatespecvolumesephemeralvolumeclaimtemplatemetadatawithselflink)
                * [`fn withUid(uid)`](#fn-specunsupportedpodtemplatespecvolumesephemeralvolumeclaimtemplatemetadatawithuid)
                * [`obj spec.unsupported.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.metadata.managedFields`](#obj-specunsupportedpodtemplatespecvolumesephemeralvolumeclaimtemplatemetadatamanagedfields)
                  * [`fn withApiVersion(apiVersion)`](#fn-specunsupportedpodtemplatespecvolumesephemeralvolumeclaimtemplatemetadatamanagedfieldswithapiversion)
                  * [`fn withFieldsType(fieldsType)`](#fn-specunsupportedpodtemplatespecvolumesephemeralvolumeclaimtemplatemetadatamanagedfieldswithfieldstype)
                  * [`fn withFieldsV1(fieldsV1)`](#fn-specunsupportedpodtemplatespecvolumesephemeralvolumeclaimtemplatemetadatamanagedfieldswithfieldsv1)
                  * [`fn withFieldsV1Mixin(fieldsV1)`](#fn-specunsupportedpodtemplatespecvolumesephemeralvolumeclaimtemplatemetadatamanagedfieldswithfieldsv1mixin)
                  * [`fn withManager(manager)`](#fn-specunsupportedpodtemplatespecvolumesephemeralvolumeclaimtemplatemetadatamanagedfieldswithmanager)
                  * [`fn withOperation(operation)`](#fn-specunsupportedpodtemplatespecvolumesephemeralvolumeclaimtemplatemetadatamanagedfieldswithoperation)
                  * [`fn withSubresource(subresource)`](#fn-specunsupportedpodtemplatespecvolumesephemeralvolumeclaimtemplatemetadatamanagedfieldswithsubresource)
                  * [`fn withTime(time)`](#fn-specunsupportedpodtemplatespecvolumesephemeralvolumeclaimtemplatemetadatamanagedfieldswithtime)
                * [`obj spec.unsupported.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.metadata.ownerReferences`](#obj-specunsupportedpodtemplatespecvolumesephemeralvolumeclaimtemplatemetadataownerreferences)
                  * [`fn withApiVersion(apiVersion)`](#fn-specunsupportedpodtemplatespecvolumesephemeralvolumeclaimtemplatemetadataownerreferenceswithapiversion)
                  * [`fn withBlockOwnerDeletion(blockOwnerDeletion)`](#fn-specunsupportedpodtemplatespecvolumesephemeralvolumeclaimtemplatemetadataownerreferenceswithblockownerdeletion)
                  * [`fn withController(controller)`](#fn-specunsupportedpodtemplatespecvolumesephemeralvolumeclaimtemplatemetadataownerreferenceswithcontroller)
                  * [`fn withKind(kind)`](#fn-specunsupportedpodtemplatespecvolumesephemeralvolumeclaimtemplatemetadataownerreferenceswithkind)
                  * [`fn withName(name)`](#fn-specunsupportedpodtemplatespecvolumesephemeralvolumeclaimtemplatemetadataownerreferenceswithname)
                  * [`fn withUid(uid)`](#fn-specunsupportedpodtemplatespecvolumesephemeralvolumeclaimtemplatemetadataownerreferenceswithuid)
              * [`obj spec.unsupported.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.spec`](#obj-specunsupportedpodtemplatespecvolumesephemeralvolumeclaimtemplatespec)
                * [`fn withAccessModes(accessModes)`](#fn-specunsupportedpodtemplatespecvolumesephemeralvolumeclaimtemplatespecwithaccessmodes)
                * [`fn withAccessModesMixin(accessModes)`](#fn-specunsupportedpodtemplatespecvolumesephemeralvolumeclaimtemplatespecwithaccessmodesmixin)
                * [`fn withStorageClassName(storageClassName)`](#fn-specunsupportedpodtemplatespecvolumesephemeralvolumeclaimtemplatespecwithstorageclassname)
                * [`fn withVolumeAttributesClassName(volumeAttributesClassName)`](#fn-specunsupportedpodtemplatespecvolumesephemeralvolumeclaimtemplatespecwithvolumeattributesclassname)
                * [`fn withVolumeMode(volumeMode)`](#fn-specunsupportedpodtemplatespecvolumesephemeralvolumeclaimtemplatespecwithvolumemode)
                * [`fn withVolumeName(volumeName)`](#fn-specunsupportedpodtemplatespecvolumesephemeralvolumeclaimtemplatespecwithvolumename)
                * [`obj spec.unsupported.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.spec.dataSource`](#obj-specunsupportedpodtemplatespecvolumesephemeralvolumeclaimtemplatespecdatasource)
                  * [`fn withApiGroup(apiGroup)`](#fn-specunsupportedpodtemplatespecvolumesephemeralvolumeclaimtemplatespecdatasourcewithapigroup)
                  * [`fn withKind(kind)`](#fn-specunsupportedpodtemplatespecvolumesephemeralvolumeclaimtemplatespecdatasourcewithkind)
                  * [`fn withName(name)`](#fn-specunsupportedpodtemplatespecvolumesephemeralvolumeclaimtemplatespecdatasourcewithname)
                * [`obj spec.unsupported.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.spec.dataSourceRef`](#obj-specunsupportedpodtemplatespecvolumesephemeralvolumeclaimtemplatespecdatasourceref)
                  * [`fn withApiGroup(apiGroup)`](#fn-specunsupportedpodtemplatespecvolumesephemeralvolumeclaimtemplatespecdatasourcerefwithapigroup)
                  * [`fn withKind(kind)`](#fn-specunsupportedpodtemplatespecvolumesephemeralvolumeclaimtemplatespecdatasourcerefwithkind)
                  * [`fn withName(name)`](#fn-specunsupportedpodtemplatespecvolumesephemeralvolumeclaimtemplatespecdatasourcerefwithname)
                  * [`fn withNamespace(namespace)`](#fn-specunsupportedpodtemplatespecvolumesephemeralvolumeclaimtemplatespecdatasourcerefwithnamespace)
                * [`obj spec.unsupported.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.spec.resources`](#obj-specunsupportedpodtemplatespecvolumesephemeralvolumeclaimtemplatespecresources)
                  * [`fn withLimits(limits)`](#fn-specunsupportedpodtemplatespecvolumesephemeralvolumeclaimtemplatespecresourceswithlimits)
                  * [`fn withLimitsMixin(limits)`](#fn-specunsupportedpodtemplatespecvolumesephemeralvolumeclaimtemplatespecresourceswithlimitsmixin)
                  * [`fn withRequests(requests)`](#fn-specunsupportedpodtemplatespecvolumesephemeralvolumeclaimtemplatespecresourceswithrequests)
                  * [`fn withRequestsMixin(requests)`](#fn-specunsupportedpodtemplatespecvolumesephemeralvolumeclaimtemplatespecresourceswithrequestsmixin)
                * [`obj spec.unsupported.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.spec.selector`](#obj-specunsupportedpodtemplatespecvolumesephemeralvolumeclaimtemplatespecselector)
                  * [`fn withMatchExpressions(matchExpressions)`](#fn-specunsupportedpodtemplatespecvolumesephemeralvolumeclaimtemplatespecselectorwithmatchexpressions)
                  * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specunsupportedpodtemplatespecvolumesephemeralvolumeclaimtemplatespecselectorwithmatchexpressionsmixin)
                  * [`fn withMatchLabels(matchLabels)`](#fn-specunsupportedpodtemplatespecvolumesephemeralvolumeclaimtemplatespecselectorwithmatchlabels)
                  * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specunsupportedpodtemplatespecvolumesephemeralvolumeclaimtemplatespecselectorwithmatchlabelsmixin)
                  * [`obj spec.unsupported.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.spec.selector.matchExpressions`](#obj-specunsupportedpodtemplatespecvolumesephemeralvolumeclaimtemplatespecselectormatchexpressions)
                    * [`fn withKey(key)`](#fn-specunsupportedpodtemplatespecvolumesephemeralvolumeclaimtemplatespecselectormatchexpressionswithkey)
                    * [`fn withOperator(operator)`](#fn-specunsupportedpodtemplatespecvolumesephemeralvolumeclaimtemplatespecselectormatchexpressionswithoperator)
                    * [`fn withValues(values)`](#fn-specunsupportedpodtemplatespecvolumesephemeralvolumeclaimtemplatespecselectormatchexpressionswithvalues)
                    * [`fn withValuesMixin(values)`](#fn-specunsupportedpodtemplatespecvolumesephemeralvolumeclaimtemplatespecselectormatchexpressionswithvaluesmixin)
          * [`obj spec.unsupported.podTemplate.spec.volumes.fc`](#obj-specunsupportedpodtemplatespecvolumesfc)
            * [`fn withFsType(fsType)`](#fn-specunsupportedpodtemplatespecvolumesfcwithfstype)
            * [`fn withLun(lun)`](#fn-specunsupportedpodtemplatespecvolumesfcwithlun)
            * [`fn withReadOnly(readOnly)`](#fn-specunsupportedpodtemplatespecvolumesfcwithreadonly)
            * [`fn withTargetWWNs(targetWWNs)`](#fn-specunsupportedpodtemplatespecvolumesfcwithtargetwwns)
            * [`fn withTargetWWNsMixin(targetWWNs)`](#fn-specunsupportedpodtemplatespecvolumesfcwithtargetwwnsmixin)
            * [`fn withWwids(wwids)`](#fn-specunsupportedpodtemplatespecvolumesfcwithwwids)
            * [`fn withWwidsMixin(wwids)`](#fn-specunsupportedpodtemplatespecvolumesfcwithwwidsmixin)
          * [`obj spec.unsupported.podTemplate.spec.volumes.flexVolume`](#obj-specunsupportedpodtemplatespecvolumesflexvolume)
            * [`fn withDriver(driver)`](#fn-specunsupportedpodtemplatespecvolumesflexvolumewithdriver)
            * [`fn withFsType(fsType)`](#fn-specunsupportedpodtemplatespecvolumesflexvolumewithfstype)
            * [`fn withOptions(options)`](#fn-specunsupportedpodtemplatespecvolumesflexvolumewithoptions)
            * [`fn withOptionsMixin(options)`](#fn-specunsupportedpodtemplatespecvolumesflexvolumewithoptionsmixin)
            * [`fn withReadOnly(readOnly)`](#fn-specunsupportedpodtemplatespecvolumesflexvolumewithreadonly)
            * [`obj spec.unsupported.podTemplate.spec.volumes.flexVolume.secretRef`](#obj-specunsupportedpodtemplatespecvolumesflexvolumesecretref)
              * [`fn withName(name)`](#fn-specunsupportedpodtemplatespecvolumesflexvolumesecretrefwithname)
          * [`obj spec.unsupported.podTemplate.spec.volumes.flocker`](#obj-specunsupportedpodtemplatespecvolumesflocker)
            * [`fn withDatasetName(datasetName)`](#fn-specunsupportedpodtemplatespecvolumesflockerwithdatasetname)
            * [`fn withDatasetUUID(datasetUUID)`](#fn-specunsupportedpodtemplatespecvolumesflockerwithdatasetuuid)
          * [`obj spec.unsupported.podTemplate.spec.volumes.gcePersistentDisk`](#obj-specunsupportedpodtemplatespecvolumesgcepersistentdisk)
            * [`fn withFsType(fsType)`](#fn-specunsupportedpodtemplatespecvolumesgcepersistentdiskwithfstype)
            * [`fn withPartition(partition)`](#fn-specunsupportedpodtemplatespecvolumesgcepersistentdiskwithpartition)
            * [`fn withPdName(pdName)`](#fn-specunsupportedpodtemplatespecvolumesgcepersistentdiskwithpdname)
            * [`fn withReadOnly(readOnly)`](#fn-specunsupportedpodtemplatespecvolumesgcepersistentdiskwithreadonly)
          * [`obj spec.unsupported.podTemplate.spec.volumes.gitRepo`](#obj-specunsupportedpodtemplatespecvolumesgitrepo)
            * [`fn withDirectory(directory)`](#fn-specunsupportedpodtemplatespecvolumesgitrepowithdirectory)
            * [`fn withRepository(repository)`](#fn-specunsupportedpodtemplatespecvolumesgitrepowithrepository)
            * [`fn withRevision(revision)`](#fn-specunsupportedpodtemplatespecvolumesgitrepowithrevision)
          * [`obj spec.unsupported.podTemplate.spec.volumes.glusterfs`](#obj-specunsupportedpodtemplatespecvolumesglusterfs)
            * [`fn withEndpoints(endpoints)`](#fn-specunsupportedpodtemplatespecvolumesglusterfswithendpoints)
            * [`fn withPath(path)`](#fn-specunsupportedpodtemplatespecvolumesglusterfswithpath)
            * [`fn withReadOnly(readOnly)`](#fn-specunsupportedpodtemplatespecvolumesglusterfswithreadonly)
          * [`obj spec.unsupported.podTemplate.spec.volumes.hostPath`](#obj-specunsupportedpodtemplatespecvolumeshostpath)
            * [`fn withPath(path)`](#fn-specunsupportedpodtemplatespecvolumeshostpathwithpath)
            * [`fn withType(type)`](#fn-specunsupportedpodtemplatespecvolumeshostpathwithtype)
          * [`obj spec.unsupported.podTemplate.spec.volumes.image`](#obj-specunsupportedpodtemplatespecvolumesimage)
            * [`fn withPullPolicy(pullPolicy)`](#fn-specunsupportedpodtemplatespecvolumesimagewithpullpolicy)
            * [`fn withReference(reference)`](#fn-specunsupportedpodtemplatespecvolumesimagewithreference)
          * [`obj spec.unsupported.podTemplate.spec.volumes.iscsi`](#obj-specunsupportedpodtemplatespecvolumesiscsi)
            * [`fn withChapAuthDiscovery(chapAuthDiscovery)`](#fn-specunsupportedpodtemplatespecvolumesiscsiwithchapauthdiscovery)
            * [`fn withChapAuthSession(chapAuthSession)`](#fn-specunsupportedpodtemplatespecvolumesiscsiwithchapauthsession)
            * [`fn withFsType(fsType)`](#fn-specunsupportedpodtemplatespecvolumesiscsiwithfstype)
            * [`fn withInitiatorName(initiatorName)`](#fn-specunsupportedpodtemplatespecvolumesiscsiwithinitiatorname)
            * [`fn withIqn(iqn)`](#fn-specunsupportedpodtemplatespecvolumesiscsiwithiqn)
            * [`fn withIscsiInterface(iscsiInterface)`](#fn-specunsupportedpodtemplatespecvolumesiscsiwithiscsiinterface)
            * [`fn withLun(lun)`](#fn-specunsupportedpodtemplatespecvolumesiscsiwithlun)
            * [`fn withPortals(portals)`](#fn-specunsupportedpodtemplatespecvolumesiscsiwithportals)
            * [`fn withPortalsMixin(portals)`](#fn-specunsupportedpodtemplatespecvolumesiscsiwithportalsmixin)
            * [`fn withReadOnly(readOnly)`](#fn-specunsupportedpodtemplatespecvolumesiscsiwithreadonly)
            * [`fn withTargetPortal(targetPortal)`](#fn-specunsupportedpodtemplatespecvolumesiscsiwithtargetportal)
            * [`obj spec.unsupported.podTemplate.spec.volumes.iscsi.secretRef`](#obj-specunsupportedpodtemplatespecvolumesiscsisecretref)
              * [`fn withName(name)`](#fn-specunsupportedpodtemplatespecvolumesiscsisecretrefwithname)
          * [`obj spec.unsupported.podTemplate.spec.volumes.nfs`](#obj-specunsupportedpodtemplatespecvolumesnfs)
            * [`fn withPath(path)`](#fn-specunsupportedpodtemplatespecvolumesnfswithpath)
            * [`fn withReadOnly(readOnly)`](#fn-specunsupportedpodtemplatespecvolumesnfswithreadonly)
            * [`fn withServer(server)`](#fn-specunsupportedpodtemplatespecvolumesnfswithserver)
          * [`obj spec.unsupported.podTemplate.spec.volumes.persistentVolumeClaim`](#obj-specunsupportedpodtemplatespecvolumespersistentvolumeclaim)
            * [`fn withClaimName(claimName)`](#fn-specunsupportedpodtemplatespecvolumespersistentvolumeclaimwithclaimname)
            * [`fn withReadOnly(readOnly)`](#fn-specunsupportedpodtemplatespecvolumespersistentvolumeclaimwithreadonly)
          * [`obj spec.unsupported.podTemplate.spec.volumes.photonPersistentDisk`](#obj-specunsupportedpodtemplatespecvolumesphotonpersistentdisk)
            * [`fn withFsType(fsType)`](#fn-specunsupportedpodtemplatespecvolumesphotonpersistentdiskwithfstype)
            * [`fn withPdID(pdID)`](#fn-specunsupportedpodtemplatespecvolumesphotonpersistentdiskwithpdid)
          * [`obj spec.unsupported.podTemplate.spec.volumes.portworxVolume`](#obj-specunsupportedpodtemplatespecvolumesportworxvolume)
            * [`fn withFsType(fsType)`](#fn-specunsupportedpodtemplatespecvolumesportworxvolumewithfstype)
            * [`fn withReadOnly(readOnly)`](#fn-specunsupportedpodtemplatespecvolumesportworxvolumewithreadonly)
            * [`fn withVolumeID(volumeID)`](#fn-specunsupportedpodtemplatespecvolumesportworxvolumewithvolumeid)
          * [`obj spec.unsupported.podTemplate.spec.volumes.projected`](#obj-specunsupportedpodtemplatespecvolumesprojected)
            * [`fn withDefaultMode(defaultMode)`](#fn-specunsupportedpodtemplatespecvolumesprojectedwithdefaultmode)
            * [`fn withSources(sources)`](#fn-specunsupportedpodtemplatespecvolumesprojectedwithsources)
            * [`fn withSourcesMixin(sources)`](#fn-specunsupportedpodtemplatespecvolumesprojectedwithsourcesmixin)
            * [`obj spec.unsupported.podTemplate.spec.volumes.projected.sources`](#obj-specunsupportedpodtemplatespecvolumesprojectedsources)
              * [`obj spec.unsupported.podTemplate.spec.volumes.projected.sources.clusterTrustBundle`](#obj-specunsupportedpodtemplatespecvolumesprojectedsourcesclustertrustbundle)
                * [`fn withName(name)`](#fn-specunsupportedpodtemplatespecvolumesprojectedsourcesclustertrustbundlewithname)
                * [`fn withOptional(optional)`](#fn-specunsupportedpodtemplatespecvolumesprojectedsourcesclustertrustbundlewithoptional)
                * [`fn withPath(path)`](#fn-specunsupportedpodtemplatespecvolumesprojectedsourcesclustertrustbundlewithpath)
                * [`fn withSignerName(signerName)`](#fn-specunsupportedpodtemplatespecvolumesprojectedsourcesclustertrustbundlewithsignername)
                * [`obj spec.unsupported.podTemplate.spec.volumes.projected.sources.clusterTrustBundle.labelSelector`](#obj-specunsupportedpodtemplatespecvolumesprojectedsourcesclustertrustbundlelabelselector)
                  * [`fn withMatchExpressions(matchExpressions)`](#fn-specunsupportedpodtemplatespecvolumesprojectedsourcesclustertrustbundlelabelselectorwithmatchexpressions)
                  * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specunsupportedpodtemplatespecvolumesprojectedsourcesclustertrustbundlelabelselectorwithmatchexpressionsmixin)
                  * [`fn withMatchLabels(matchLabels)`](#fn-specunsupportedpodtemplatespecvolumesprojectedsourcesclustertrustbundlelabelselectorwithmatchlabels)
                  * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specunsupportedpodtemplatespecvolumesprojectedsourcesclustertrustbundlelabelselectorwithmatchlabelsmixin)
                  * [`obj spec.unsupported.podTemplate.spec.volumes.projected.sources.clusterTrustBundle.labelSelector.matchExpressions`](#obj-specunsupportedpodtemplatespecvolumesprojectedsourcesclustertrustbundlelabelselectormatchexpressions)
                    * [`fn withKey(key)`](#fn-specunsupportedpodtemplatespecvolumesprojectedsourcesclustertrustbundlelabelselectormatchexpressionswithkey)
                    * [`fn withOperator(operator)`](#fn-specunsupportedpodtemplatespecvolumesprojectedsourcesclustertrustbundlelabelselectormatchexpressionswithoperator)
                    * [`fn withValues(values)`](#fn-specunsupportedpodtemplatespecvolumesprojectedsourcesclustertrustbundlelabelselectormatchexpressionswithvalues)
                    * [`fn withValuesMixin(values)`](#fn-specunsupportedpodtemplatespecvolumesprojectedsourcesclustertrustbundlelabelselectormatchexpressionswithvaluesmixin)
              * [`obj spec.unsupported.podTemplate.spec.volumes.projected.sources.configMap`](#obj-specunsupportedpodtemplatespecvolumesprojectedsourcesconfigmap)
                * [`fn withItems(items)`](#fn-specunsupportedpodtemplatespecvolumesprojectedsourcesconfigmapwithitems)
                * [`fn withItemsMixin(items)`](#fn-specunsupportedpodtemplatespecvolumesprojectedsourcesconfigmapwithitemsmixin)
                * [`fn withName(name)`](#fn-specunsupportedpodtemplatespecvolumesprojectedsourcesconfigmapwithname)
                * [`fn withOptional(optional)`](#fn-specunsupportedpodtemplatespecvolumesprojectedsourcesconfigmapwithoptional)
                * [`obj spec.unsupported.podTemplate.spec.volumes.projected.sources.configMap.items`](#obj-specunsupportedpodtemplatespecvolumesprojectedsourcesconfigmapitems)
                  * [`fn withKey(key)`](#fn-specunsupportedpodtemplatespecvolumesprojectedsourcesconfigmapitemswithkey)
                  * [`fn withMode(mode)`](#fn-specunsupportedpodtemplatespecvolumesprojectedsourcesconfigmapitemswithmode)
                  * [`fn withPath(path)`](#fn-specunsupportedpodtemplatespecvolumesprojectedsourcesconfigmapitemswithpath)
              * [`obj spec.unsupported.podTemplate.spec.volumes.projected.sources.downwardAPI`](#obj-specunsupportedpodtemplatespecvolumesprojectedsourcesdownwardapi)
                * [`fn withItems(items)`](#fn-specunsupportedpodtemplatespecvolumesprojectedsourcesdownwardapiwithitems)
                * [`fn withItemsMixin(items)`](#fn-specunsupportedpodtemplatespecvolumesprojectedsourcesdownwardapiwithitemsmixin)
                * [`obj spec.unsupported.podTemplate.spec.volumes.projected.sources.downwardAPI.items`](#obj-specunsupportedpodtemplatespecvolumesprojectedsourcesdownwardapiitems)
                  * [`fn withMode(mode)`](#fn-specunsupportedpodtemplatespecvolumesprojectedsourcesdownwardapiitemswithmode)
                  * [`fn withPath(path)`](#fn-specunsupportedpodtemplatespecvolumesprojectedsourcesdownwardapiitemswithpath)
                  * [`obj spec.unsupported.podTemplate.spec.volumes.projected.sources.downwardAPI.items.fieldRef`](#obj-specunsupportedpodtemplatespecvolumesprojectedsourcesdownwardapiitemsfieldref)
                    * [`fn withApiVersion(apiVersion)`](#fn-specunsupportedpodtemplatespecvolumesprojectedsourcesdownwardapiitemsfieldrefwithapiversion)
                    * [`fn withFieldPath(fieldPath)`](#fn-specunsupportedpodtemplatespecvolumesprojectedsourcesdownwardapiitemsfieldrefwithfieldpath)
                  * [`obj spec.unsupported.podTemplate.spec.volumes.projected.sources.downwardAPI.items.resourceFieldRef`](#obj-specunsupportedpodtemplatespecvolumesprojectedsourcesdownwardapiitemsresourcefieldref)
                    * [`fn withContainerName(containerName)`](#fn-specunsupportedpodtemplatespecvolumesprojectedsourcesdownwardapiitemsresourcefieldrefwithcontainername)
                    * [`fn withDivisor(divisor)`](#fn-specunsupportedpodtemplatespecvolumesprojectedsourcesdownwardapiitemsresourcefieldrefwithdivisor)
                    * [`fn withResource(resource)`](#fn-specunsupportedpodtemplatespecvolumesprojectedsourcesdownwardapiitemsresourcefieldrefwithresource)
              * [`obj spec.unsupported.podTemplate.spec.volumes.projected.sources.secret`](#obj-specunsupportedpodtemplatespecvolumesprojectedsourcessecret)
                * [`fn withItems(items)`](#fn-specunsupportedpodtemplatespecvolumesprojectedsourcessecretwithitems)
                * [`fn withItemsMixin(items)`](#fn-specunsupportedpodtemplatespecvolumesprojectedsourcessecretwithitemsmixin)
                * [`fn withName(name)`](#fn-specunsupportedpodtemplatespecvolumesprojectedsourcessecretwithname)
                * [`fn withOptional(optional)`](#fn-specunsupportedpodtemplatespecvolumesprojectedsourcessecretwithoptional)
                * [`obj spec.unsupported.podTemplate.spec.volumes.projected.sources.secret.items`](#obj-specunsupportedpodtemplatespecvolumesprojectedsourcessecretitems)
                  * [`fn withKey(key)`](#fn-specunsupportedpodtemplatespecvolumesprojectedsourcessecretitemswithkey)
                  * [`fn withMode(mode)`](#fn-specunsupportedpodtemplatespecvolumesprojectedsourcessecretitemswithmode)
                  * [`fn withPath(path)`](#fn-specunsupportedpodtemplatespecvolumesprojectedsourcessecretitemswithpath)
              * [`obj spec.unsupported.podTemplate.spec.volumes.projected.sources.serviceAccountToken`](#obj-specunsupportedpodtemplatespecvolumesprojectedsourcesserviceaccounttoken)
                * [`fn withAudience(audience)`](#fn-specunsupportedpodtemplatespecvolumesprojectedsourcesserviceaccounttokenwithaudience)
                * [`fn withExpirationSeconds(expirationSeconds)`](#fn-specunsupportedpodtemplatespecvolumesprojectedsourcesserviceaccounttokenwithexpirationseconds)
                * [`fn withPath(path)`](#fn-specunsupportedpodtemplatespecvolumesprojectedsourcesserviceaccounttokenwithpath)
          * [`obj spec.unsupported.podTemplate.spec.volumes.quobyte`](#obj-specunsupportedpodtemplatespecvolumesquobyte)
            * [`fn withGroup(group)`](#fn-specunsupportedpodtemplatespecvolumesquobytewithgroup)
            * [`fn withReadOnly(readOnly)`](#fn-specunsupportedpodtemplatespecvolumesquobytewithreadonly)
            * [`fn withRegistry(registry)`](#fn-specunsupportedpodtemplatespecvolumesquobytewithregistry)
            * [`fn withTenant(tenant)`](#fn-specunsupportedpodtemplatespecvolumesquobytewithtenant)
            * [`fn withUser(user)`](#fn-specunsupportedpodtemplatespecvolumesquobytewithuser)
            * [`fn withVolume(volume)`](#fn-specunsupportedpodtemplatespecvolumesquobytewithvolume)
          * [`obj spec.unsupported.podTemplate.spec.volumes.rbd`](#obj-specunsupportedpodtemplatespecvolumesrbd)
            * [`fn withFsType(fsType)`](#fn-specunsupportedpodtemplatespecvolumesrbdwithfstype)
            * [`fn withImage(image)`](#fn-specunsupportedpodtemplatespecvolumesrbdwithimage)
            * [`fn withKeyring(keyring)`](#fn-specunsupportedpodtemplatespecvolumesrbdwithkeyring)
            * [`fn withMonitors(monitors)`](#fn-specunsupportedpodtemplatespecvolumesrbdwithmonitors)
            * [`fn withMonitorsMixin(monitors)`](#fn-specunsupportedpodtemplatespecvolumesrbdwithmonitorsmixin)
            * [`fn withPool(pool)`](#fn-specunsupportedpodtemplatespecvolumesrbdwithpool)
            * [`fn withReadOnly(readOnly)`](#fn-specunsupportedpodtemplatespecvolumesrbdwithreadonly)
            * [`fn withUser(user)`](#fn-specunsupportedpodtemplatespecvolumesrbdwithuser)
            * [`obj spec.unsupported.podTemplate.spec.volumes.rbd.secretRef`](#obj-specunsupportedpodtemplatespecvolumesrbdsecretref)
              * [`fn withName(name)`](#fn-specunsupportedpodtemplatespecvolumesrbdsecretrefwithname)
          * [`obj spec.unsupported.podTemplate.spec.volumes.scaleIO`](#obj-specunsupportedpodtemplatespecvolumesscaleio)
            * [`fn withFsType(fsType)`](#fn-specunsupportedpodtemplatespecvolumesscaleiowithfstype)
            * [`fn withGateway(gateway)`](#fn-specunsupportedpodtemplatespecvolumesscaleiowithgateway)
            * [`fn withProtectionDomain(protectionDomain)`](#fn-specunsupportedpodtemplatespecvolumesscaleiowithprotectiondomain)
            * [`fn withReadOnly(readOnly)`](#fn-specunsupportedpodtemplatespecvolumesscaleiowithreadonly)
            * [`fn withSslEnabled(sslEnabled)`](#fn-specunsupportedpodtemplatespecvolumesscaleiowithsslenabled)
            * [`fn withStorageMode(storageMode)`](#fn-specunsupportedpodtemplatespecvolumesscaleiowithstoragemode)
            * [`fn withStoragePool(storagePool)`](#fn-specunsupportedpodtemplatespecvolumesscaleiowithstoragepool)
            * [`fn withSystem(system)`](#fn-specunsupportedpodtemplatespecvolumesscaleiowithsystem)
            * [`fn withVolumeName(volumeName)`](#fn-specunsupportedpodtemplatespecvolumesscaleiowithvolumename)
            * [`obj spec.unsupported.podTemplate.spec.volumes.scaleIO.secretRef`](#obj-specunsupportedpodtemplatespecvolumesscaleiosecretref)
              * [`fn withName(name)`](#fn-specunsupportedpodtemplatespecvolumesscaleiosecretrefwithname)
          * [`obj spec.unsupported.podTemplate.spec.volumes.secret`](#obj-specunsupportedpodtemplatespecvolumessecret)
            * [`fn withDefaultMode(defaultMode)`](#fn-specunsupportedpodtemplatespecvolumessecretwithdefaultmode)
            * [`fn withItems(items)`](#fn-specunsupportedpodtemplatespecvolumessecretwithitems)
            * [`fn withItemsMixin(items)`](#fn-specunsupportedpodtemplatespecvolumessecretwithitemsmixin)
            * [`fn withOptional(optional)`](#fn-specunsupportedpodtemplatespecvolumessecretwithoptional)
            * [`fn withSecretName(secretName)`](#fn-specunsupportedpodtemplatespecvolumessecretwithsecretname)
            * [`obj spec.unsupported.podTemplate.spec.volumes.secret.items`](#obj-specunsupportedpodtemplatespecvolumessecretitems)
              * [`fn withKey(key)`](#fn-specunsupportedpodtemplatespecvolumessecretitemswithkey)
              * [`fn withMode(mode)`](#fn-specunsupportedpodtemplatespecvolumessecretitemswithmode)
              * [`fn withPath(path)`](#fn-specunsupportedpodtemplatespecvolumessecretitemswithpath)
          * [`obj spec.unsupported.podTemplate.spec.volumes.storageos`](#obj-specunsupportedpodtemplatespecvolumesstorageos)
            * [`fn withFsType(fsType)`](#fn-specunsupportedpodtemplatespecvolumesstorageoswithfstype)
            * [`fn withReadOnly(readOnly)`](#fn-specunsupportedpodtemplatespecvolumesstorageoswithreadonly)
            * [`fn withVolumeName(volumeName)`](#fn-specunsupportedpodtemplatespecvolumesstorageoswithvolumename)
            * [`fn withVolumeNamespace(volumeNamespace)`](#fn-specunsupportedpodtemplatespecvolumesstorageoswithvolumenamespace)
            * [`obj spec.unsupported.podTemplate.spec.volumes.storageos.secretRef`](#obj-specunsupportedpodtemplatespecvolumesstorageossecretref)
              * [`fn withName(name)`](#fn-specunsupportedpodtemplatespecvolumesstorageossecretrefwithname)
          * [`obj spec.unsupported.podTemplate.spec.volumes.vsphereVolume`](#obj-specunsupportedpodtemplatespecvolumesvspherevolume)
            * [`fn withFsType(fsType)`](#fn-specunsupportedpodtemplatespecvolumesvspherevolumewithfstype)
            * [`fn withStoragePolicyID(storagePolicyID)`](#fn-specunsupportedpodtemplatespecvolumesvspherevolumewithstoragepolicyid)
            * [`fn withStoragePolicyName(storagePolicyName)`](#fn-specunsupportedpodtemplatespecvolumesvspherevolumewithstoragepolicyname)
            * [`fn withVolumePath(volumePath)`](#fn-specunsupportedpodtemplatespecvolumesvspherevolumewithvolumepath)
  * [`obj spec.update`](#obj-specupdate)
    * [`fn withRevision(revision)`](#fn-specupdatewithrevision)
    * [`fn withStrategy(strategy)`](#fn-specupdatewithstrategy)
    * [`obj spec.update.scheduling`](#obj-specupdatescheduling)
      * [`fn withPriorityClassName(priorityClassName)`](#fn-specupdateschedulingwithpriorityclassname)
      * [`fn withTolerations(tolerations)`](#fn-specupdateschedulingwithtolerations)
      * [`fn withTolerationsMixin(tolerations)`](#fn-specupdateschedulingwithtolerationsmixin)
      * [`fn withTopologySpreadConstraints(topologySpreadConstraints)`](#fn-specupdateschedulingwithtopologyspreadconstraints)
      * [`fn withTopologySpreadConstraintsMixin(topologySpreadConstraints)`](#fn-specupdateschedulingwithtopologyspreadconstraintsmixin)
      * [`obj spec.update.scheduling.affinity`](#obj-specupdateschedulingaffinity)
        * [`obj spec.update.scheduling.affinity.nodeAffinity`](#obj-specupdateschedulingaffinitynodeaffinity)
          * [`fn withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-specupdateschedulingaffinitynodeaffinitywithpreferredduringschedulingignoredduringexecution)
          * [`fn withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-specupdateschedulingaffinitynodeaffinitywithpreferredduringschedulingignoredduringexecutionmixin)
          * [`obj spec.update.scheduling.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution`](#obj-specupdateschedulingaffinitynodeaffinitypreferredduringschedulingignoredduringexecution)
            * [`fn withWeight(weight)`](#fn-specupdateschedulingaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionwithweight)
            * [`obj spec.update.scheduling.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference`](#obj-specupdateschedulingaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreference)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-specupdateschedulingaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencewithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specupdateschedulingaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencewithmatchexpressionsmixin)
              * [`fn withMatchFields(matchFields)`](#fn-specupdateschedulingaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencewithmatchfields)
              * [`fn withMatchFieldsMixin(matchFields)`](#fn-specupdateschedulingaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencewithmatchfieldsmixin)
              * [`obj spec.update.scheduling.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions`](#obj-specupdateschedulingaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressions)
                * [`fn withKey(key)`](#fn-specupdateschedulingaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-specupdateschedulingaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-specupdateschedulingaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-specupdateschedulingaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressionswithvaluesmixin)
              * [`obj spec.update.scheduling.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields`](#obj-specupdateschedulingaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfields)
                * [`fn withKey(key)`](#fn-specupdateschedulingaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfieldswithkey)
                * [`fn withOperator(operator)`](#fn-specupdateschedulingaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfieldswithoperator)
                * [`fn withValues(values)`](#fn-specupdateschedulingaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfieldswithvalues)
                * [`fn withValuesMixin(values)`](#fn-specupdateschedulingaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfieldswithvaluesmixin)
          * [`obj spec.update.scheduling.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution`](#obj-specupdateschedulingaffinitynodeaffinityrequiredduringschedulingignoredduringexecution)
            * [`fn withNodeSelectorTerms(nodeSelectorTerms)`](#fn-specupdateschedulingaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionwithnodeselectorterms)
            * [`fn withNodeSelectorTermsMixin(nodeSelectorTerms)`](#fn-specupdateschedulingaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionwithnodeselectortermsmixin)
            * [`obj spec.update.scheduling.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms`](#obj-specupdateschedulingaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectorterms)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-specupdateschedulingaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermswithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specupdateschedulingaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermswithmatchexpressionsmixin)
              * [`fn withMatchFields(matchFields)`](#fn-specupdateschedulingaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermswithmatchfields)
              * [`fn withMatchFieldsMixin(matchFields)`](#fn-specupdateschedulingaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermswithmatchfieldsmixin)
              * [`obj spec.update.scheduling.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions`](#obj-specupdateschedulingaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressions)
                * [`fn withKey(key)`](#fn-specupdateschedulingaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-specupdateschedulingaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-specupdateschedulingaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-specupdateschedulingaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressionswithvaluesmixin)
              * [`obj spec.update.scheduling.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields`](#obj-specupdateschedulingaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfields)
                * [`fn withKey(key)`](#fn-specupdateschedulingaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfieldswithkey)
                * [`fn withOperator(operator)`](#fn-specupdateschedulingaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfieldswithoperator)
                * [`fn withValues(values)`](#fn-specupdateschedulingaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfieldswithvalues)
                * [`fn withValuesMixin(values)`](#fn-specupdateschedulingaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfieldswithvaluesmixin)
        * [`obj spec.update.scheduling.affinity.podAffinity`](#obj-specupdateschedulingaffinitypodaffinity)
          * [`fn withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-specupdateschedulingaffinitypodaffinitywithpreferredduringschedulingignoredduringexecution)
          * [`fn withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-specupdateschedulingaffinitypodaffinitywithpreferredduringschedulingignoredduringexecutionmixin)
          * [`fn withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-specupdateschedulingaffinitypodaffinitywithrequiredduringschedulingignoredduringexecution)
          * [`fn withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-specupdateschedulingaffinitypodaffinitywithrequiredduringschedulingignoredduringexecutionmixin)
          * [`obj spec.update.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution`](#obj-specupdateschedulingaffinitypodaffinitypreferredduringschedulingignoredduringexecution)
            * [`fn withWeight(weight)`](#fn-specupdateschedulingaffinitypodaffinitypreferredduringschedulingignoredduringexecutionwithweight)
            * [`obj spec.update.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm`](#obj-specupdateschedulingaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinityterm)
              * [`fn withMatchLabelKeys(matchLabelKeys)`](#fn-specupdateschedulingaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmatchlabelkeys)
              * [`fn withMatchLabelKeysMixin(matchLabelKeys)`](#fn-specupdateschedulingaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmatchlabelkeysmixin)
              * [`fn withMismatchLabelKeys(mismatchLabelKeys)`](#fn-specupdateschedulingaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmismatchlabelkeys)
              * [`fn withMismatchLabelKeysMixin(mismatchLabelKeys)`](#fn-specupdateschedulingaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmismatchlabelkeysmixin)
              * [`fn withNamespaces(namespaces)`](#fn-specupdateschedulingaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithnamespaces)
              * [`fn withNamespacesMixin(namespaces)`](#fn-specupdateschedulingaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithnamespacesmixin)
              * [`fn withTopologyKey(topologyKey)`](#fn-specupdateschedulingaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithtopologykey)
              * [`obj spec.update.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector`](#obj-specupdateschedulingaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselector)
                * [`fn withMatchExpressions(matchExpressions)`](#fn-specupdateschedulingaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchexpressions)
                * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specupdateschedulingaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchexpressionsmixin)
                * [`fn withMatchLabels(matchLabels)`](#fn-specupdateschedulingaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchlabels)
                * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specupdateschedulingaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchlabelsmixin)
                * [`obj spec.update.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions`](#obj-specupdateschedulingaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressions)
                  * [`fn withKey(key)`](#fn-specupdateschedulingaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithkey)
                  * [`fn withOperator(operator)`](#fn-specupdateschedulingaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithoperator)
                  * [`fn withValues(values)`](#fn-specupdateschedulingaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithvalues)
                  * [`fn withValuesMixin(values)`](#fn-specupdateschedulingaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithvaluesmixin)
              * [`obj spec.update.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector`](#obj-specupdateschedulingaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselector)
                * [`fn withMatchExpressions(matchExpressions)`](#fn-specupdateschedulingaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchexpressions)
                * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specupdateschedulingaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchexpressionsmixin)
                * [`fn withMatchLabels(matchLabels)`](#fn-specupdateschedulingaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchlabels)
                * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specupdateschedulingaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchlabelsmixin)
                * [`obj spec.update.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions`](#obj-specupdateschedulingaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressions)
                  * [`fn withKey(key)`](#fn-specupdateschedulingaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithkey)
                  * [`fn withOperator(operator)`](#fn-specupdateschedulingaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithoperator)
                  * [`fn withValues(values)`](#fn-specupdateschedulingaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithvalues)
                  * [`fn withValuesMixin(values)`](#fn-specupdateschedulingaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithvaluesmixin)
          * [`obj spec.update.scheduling.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution`](#obj-specupdateschedulingaffinitypodaffinityrequiredduringschedulingignoredduringexecution)
            * [`fn withMatchLabelKeys(matchLabelKeys)`](#fn-specupdateschedulingaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithmatchlabelkeys)
            * [`fn withMatchLabelKeysMixin(matchLabelKeys)`](#fn-specupdateschedulingaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithmatchlabelkeysmixin)
            * [`fn withMismatchLabelKeys(mismatchLabelKeys)`](#fn-specupdateschedulingaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithmismatchlabelkeys)
            * [`fn withMismatchLabelKeysMixin(mismatchLabelKeys)`](#fn-specupdateschedulingaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithmismatchlabelkeysmixin)
            * [`fn withNamespaces(namespaces)`](#fn-specupdateschedulingaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithnamespaces)
            * [`fn withNamespacesMixin(namespaces)`](#fn-specupdateschedulingaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithnamespacesmixin)
            * [`fn withTopologyKey(topologyKey)`](#fn-specupdateschedulingaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithtopologykey)
            * [`obj spec.update.scheduling.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector`](#obj-specupdateschedulingaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselector)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-specupdateschedulingaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specupdateschedulingaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchexpressionsmixin)
              * [`fn withMatchLabels(matchLabels)`](#fn-specupdateschedulingaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchlabels)
              * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specupdateschedulingaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchlabelsmixin)
              * [`obj spec.update.scheduling.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions`](#obj-specupdateschedulingaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressions)
                * [`fn withKey(key)`](#fn-specupdateschedulingaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-specupdateschedulingaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-specupdateschedulingaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-specupdateschedulingaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithvaluesmixin)
            * [`obj spec.update.scheduling.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector`](#obj-specupdateschedulingaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselector)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-specupdateschedulingaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specupdateschedulingaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchexpressionsmixin)
              * [`fn withMatchLabels(matchLabels)`](#fn-specupdateschedulingaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchlabels)
              * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specupdateschedulingaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchlabelsmixin)
              * [`obj spec.update.scheduling.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions`](#obj-specupdateschedulingaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressions)
                * [`fn withKey(key)`](#fn-specupdateschedulingaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-specupdateschedulingaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-specupdateschedulingaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-specupdateschedulingaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithvaluesmixin)
        * [`obj spec.update.scheduling.affinity.podAntiAffinity`](#obj-specupdateschedulingaffinitypodantiaffinity)
          * [`fn withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-specupdateschedulingaffinitypodantiaffinitywithpreferredduringschedulingignoredduringexecution)
          * [`fn withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-specupdateschedulingaffinitypodantiaffinitywithpreferredduringschedulingignoredduringexecutionmixin)
          * [`fn withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-specupdateschedulingaffinitypodantiaffinitywithrequiredduringschedulingignoredduringexecution)
          * [`fn withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-specupdateschedulingaffinitypodantiaffinitywithrequiredduringschedulingignoredduringexecutionmixin)
          * [`obj spec.update.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution`](#obj-specupdateschedulingaffinitypodantiaffinitypreferredduringschedulingignoredduringexecution)
            * [`fn withWeight(weight)`](#fn-specupdateschedulingaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionwithweight)
            * [`obj spec.update.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm`](#obj-specupdateschedulingaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinityterm)
              * [`fn withMatchLabelKeys(matchLabelKeys)`](#fn-specupdateschedulingaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmatchlabelkeys)
              * [`fn withMatchLabelKeysMixin(matchLabelKeys)`](#fn-specupdateschedulingaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmatchlabelkeysmixin)
              * [`fn withMismatchLabelKeys(mismatchLabelKeys)`](#fn-specupdateschedulingaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmismatchlabelkeys)
              * [`fn withMismatchLabelKeysMixin(mismatchLabelKeys)`](#fn-specupdateschedulingaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmismatchlabelkeysmixin)
              * [`fn withNamespaces(namespaces)`](#fn-specupdateschedulingaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithnamespaces)
              * [`fn withNamespacesMixin(namespaces)`](#fn-specupdateschedulingaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithnamespacesmixin)
              * [`fn withTopologyKey(topologyKey)`](#fn-specupdateschedulingaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithtopologykey)
              * [`obj spec.update.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector`](#obj-specupdateschedulingaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselector)
                * [`fn withMatchExpressions(matchExpressions)`](#fn-specupdateschedulingaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchexpressions)
                * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specupdateschedulingaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchexpressionsmixin)
                * [`fn withMatchLabels(matchLabels)`](#fn-specupdateschedulingaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchlabels)
                * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specupdateschedulingaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchlabelsmixin)
                * [`obj spec.update.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions`](#obj-specupdateschedulingaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressions)
                  * [`fn withKey(key)`](#fn-specupdateschedulingaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithkey)
                  * [`fn withOperator(operator)`](#fn-specupdateschedulingaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithoperator)
                  * [`fn withValues(values)`](#fn-specupdateschedulingaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithvalues)
                  * [`fn withValuesMixin(values)`](#fn-specupdateschedulingaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithvaluesmixin)
              * [`obj spec.update.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector`](#obj-specupdateschedulingaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselector)
                * [`fn withMatchExpressions(matchExpressions)`](#fn-specupdateschedulingaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchexpressions)
                * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specupdateschedulingaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchexpressionsmixin)
                * [`fn withMatchLabels(matchLabels)`](#fn-specupdateschedulingaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchlabels)
                * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specupdateschedulingaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchlabelsmixin)
                * [`obj spec.update.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions`](#obj-specupdateschedulingaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressions)
                  * [`fn withKey(key)`](#fn-specupdateschedulingaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithkey)
                  * [`fn withOperator(operator)`](#fn-specupdateschedulingaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithoperator)
                  * [`fn withValues(values)`](#fn-specupdateschedulingaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithvalues)
                  * [`fn withValuesMixin(values)`](#fn-specupdateschedulingaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithvaluesmixin)
          * [`obj spec.update.scheduling.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution`](#obj-specupdateschedulingaffinitypodantiaffinityrequiredduringschedulingignoredduringexecution)
            * [`fn withMatchLabelKeys(matchLabelKeys)`](#fn-specupdateschedulingaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithmatchlabelkeys)
            * [`fn withMatchLabelKeysMixin(matchLabelKeys)`](#fn-specupdateschedulingaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithmatchlabelkeysmixin)
            * [`fn withMismatchLabelKeys(mismatchLabelKeys)`](#fn-specupdateschedulingaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithmismatchlabelkeys)
            * [`fn withMismatchLabelKeysMixin(mismatchLabelKeys)`](#fn-specupdateschedulingaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithmismatchlabelkeysmixin)
            * [`fn withNamespaces(namespaces)`](#fn-specupdateschedulingaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithnamespaces)
            * [`fn withNamespacesMixin(namespaces)`](#fn-specupdateschedulingaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithnamespacesmixin)
            * [`fn withTopologyKey(topologyKey)`](#fn-specupdateschedulingaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithtopologykey)
            * [`obj spec.update.scheduling.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector`](#obj-specupdateschedulingaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselector)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-specupdateschedulingaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specupdateschedulingaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchexpressionsmixin)
              * [`fn withMatchLabels(matchLabels)`](#fn-specupdateschedulingaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchlabels)
              * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specupdateschedulingaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchlabelsmixin)
              * [`obj spec.update.scheduling.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions`](#obj-specupdateschedulingaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressions)
                * [`fn withKey(key)`](#fn-specupdateschedulingaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-specupdateschedulingaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-specupdateschedulingaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-specupdateschedulingaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithvaluesmixin)
            * [`obj spec.update.scheduling.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector`](#obj-specupdateschedulingaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselector)
              * [`fn withMatchExpressions(matchExpressions)`](#fn-specupdateschedulingaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchexpressions)
              * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specupdateschedulingaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchexpressionsmixin)
              * [`fn withMatchLabels(matchLabels)`](#fn-specupdateschedulingaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchlabels)
              * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specupdateschedulingaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchlabelsmixin)
              * [`obj spec.update.scheduling.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions`](#obj-specupdateschedulingaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressions)
                * [`fn withKey(key)`](#fn-specupdateschedulingaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithkey)
                * [`fn withOperator(operator)`](#fn-specupdateschedulingaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithoperator)
                * [`fn withValues(values)`](#fn-specupdateschedulingaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithvalues)
                * [`fn withValuesMixin(values)`](#fn-specupdateschedulingaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithvaluesmixin)
      * [`obj spec.update.scheduling.tolerations`](#obj-specupdateschedulingtolerations)
        * [`fn withEffect(effect)`](#fn-specupdateschedulingtolerationswitheffect)
        * [`fn withKey(key)`](#fn-specupdateschedulingtolerationswithkey)
        * [`fn withOperator(operator)`](#fn-specupdateschedulingtolerationswithoperator)
        * [`fn withTolerationSeconds(tolerationSeconds)`](#fn-specupdateschedulingtolerationswithtolerationseconds)
        * [`fn withValue(value)`](#fn-specupdateschedulingtolerationswithvalue)
      * [`obj spec.update.scheduling.topologySpreadConstraints`](#obj-specupdateschedulingtopologyspreadconstraints)
        * [`fn withMatchLabelKeys(matchLabelKeys)`](#fn-specupdateschedulingtopologyspreadconstraintswithmatchlabelkeys)
        * [`fn withMatchLabelKeysMixin(matchLabelKeys)`](#fn-specupdateschedulingtopologyspreadconstraintswithmatchlabelkeysmixin)
        * [`fn withMaxSkew(maxSkew)`](#fn-specupdateschedulingtopologyspreadconstraintswithmaxskew)
        * [`fn withMinDomains(minDomains)`](#fn-specupdateschedulingtopologyspreadconstraintswithmindomains)
        * [`fn withNodeAffinityPolicy(nodeAffinityPolicy)`](#fn-specupdateschedulingtopologyspreadconstraintswithnodeaffinitypolicy)
        * [`fn withNodeTaintsPolicy(nodeTaintsPolicy)`](#fn-specupdateschedulingtopologyspreadconstraintswithnodetaintspolicy)
        * [`fn withTopologyKey(topologyKey)`](#fn-specupdateschedulingtopologyspreadconstraintswithtopologykey)
        * [`fn withWhenUnsatisfiable(whenUnsatisfiable)`](#fn-specupdateschedulingtopologyspreadconstraintswithwhenunsatisfiable)
        * [`obj spec.update.scheduling.topologySpreadConstraints.labelSelector`](#obj-specupdateschedulingtopologyspreadconstraintslabelselector)
          * [`fn withMatchExpressions(matchExpressions)`](#fn-specupdateschedulingtopologyspreadconstraintslabelselectorwithmatchexpressions)
          * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specupdateschedulingtopologyspreadconstraintslabelselectorwithmatchexpressionsmixin)
          * [`fn withMatchLabels(matchLabels)`](#fn-specupdateschedulingtopologyspreadconstraintslabelselectorwithmatchlabels)
          * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specupdateschedulingtopologyspreadconstraintslabelselectorwithmatchlabelsmixin)
          * [`obj spec.update.scheduling.topologySpreadConstraints.labelSelector.matchExpressions`](#obj-specupdateschedulingtopologyspreadconstraintslabelselectormatchexpressions)
            * [`fn withKey(key)`](#fn-specupdateschedulingtopologyspreadconstraintslabelselectormatchexpressionswithkey)
            * [`fn withOperator(operator)`](#fn-specupdateschedulingtopologyspreadconstraintslabelselectormatchexpressionswithoperator)
            * [`fn withValues(values)`](#fn-specupdateschedulingtopologyspreadconstraintslabelselectormatchexpressionswithvalues)
            * [`fn withValuesMixin(values)`](#fn-specupdateschedulingtopologyspreadconstraintslabelselectormatchexpressionswithvaluesmixin)

## Fields

### fn new

```ts
new(name)
```

new returns an instance of Keycloak

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



### fn spec.withAdditionalOptions

```ts
withAdditionalOptions(additionalOptions)
```

"Configuration of the Keycloak server.\nexpressed as a keys (reference: https://www.keycloak.org/server/all-config) and values that can be either direct values or references to secrets."

### fn spec.withAdditionalOptionsMixin

```ts
withAdditionalOptionsMixin(additionalOptions)
```

"Configuration of the Keycloak server.\nexpressed as a keys (reference: https://www.keycloak.org/server/all-config) and values that can be either direct values or references to secrets."

**Note:** This function appends passed data to existing values

### fn spec.withEnv

```ts
withEnv(env)
```

"Environment variables for the Keycloak server.\nValues can be either direct values or references to secrets. Use additionalOptions for first-class options rather than KC_ values here."

### fn spec.withEnvMixin

```ts
withEnvMixin(env)
```

"Environment variables for the Keycloak server.\nValues can be either direct values or references to secrets. Use additionalOptions for first-class options rather than KC_ values here."

**Note:** This function appends passed data to existing values

### fn spec.withImage

```ts
withImage(image)
```

"Custom Keycloak image to be used."

### fn spec.withImagePullSecrets

```ts
withImagePullSecrets(imagePullSecrets)
```

"Secret(s) that might be used when pulling an image from a private container image registry or repository."

### fn spec.withImagePullSecretsMixin

```ts
withImagePullSecretsMixin(imagePullSecrets)
```

"Secret(s) that might be used when pulling an image from a private container image registry or repository."

**Note:** This function appends passed data to existing values

### fn spec.withInstances

```ts
withInstances(instances)
```

"Number of Keycloak instances. Default is 1."

### fn spec.withStartOptimized

```ts
withStartOptimized(startOptimized)
```

"Set to force the behavior of the --optimized flag for the start command. If left unspecified the operator will assume custom images have already been augmented."

### fn spec.withTruststores

```ts
withTruststores(truststores)
```

"In this section you can configure Keycloak truststores."

### fn spec.withTruststoresMixin

```ts
withTruststoresMixin(truststores)
```

"In this section you can configure Keycloak truststores."

**Note:** This function appends passed data to existing values

## obj spec.additionalOptions

"Configuration of the Keycloak server.\nexpressed as a keys (reference: https://www.keycloak.org/server/all-config) and values that can be either direct values or references to secrets."

### fn spec.additionalOptions.withName

```ts
withName(name)
```



### fn spec.additionalOptions.withValue

```ts
withValue(value)
```



## obj spec.additionalOptions.secret



### fn spec.additionalOptions.secret.withKey

```ts
withKey(key)
```



### fn spec.additionalOptions.secret.withName

```ts
withName(name)
```



### fn spec.additionalOptions.secret.withOptional

```ts
withOptional(optional)
```



## obj spec.bootstrapAdmin

"In this section you can configure Keycloak's bootstrap admin - will be used only for initial cluster creation."

## obj spec.bootstrapAdmin.service

"Configures the bootstrap admin service account"

### fn spec.bootstrapAdmin.service.withSecret

```ts
withSecret(secret)
```

"Name of the Secret that contains the client-id and client-secret keys"

## obj spec.bootstrapAdmin.user

"Configures the bootstrap admin user"

### fn spec.bootstrapAdmin.user.withSecret

```ts
withSecret(secret)
```

"Name of the Secret that contains the username and password keys"

## obj spec.cache

"In this section you can configure Keycloak's cache"

## obj spec.cache.configMapFile



### fn spec.cache.configMapFile.withKey

```ts
withKey(key)
```



### fn spec.cache.configMapFile.withName

```ts
withName(name)
```



### fn spec.cache.configMapFile.withOptional

```ts
withOptional(optional)
```



## obj spec.db

"In this section you can find all properties related to connect to a database."

### fn spec.db.withDatabase

```ts
withDatabase(database)
```

"Sets the database name of the default JDBC URL of the chosen vendor. If the `url` option is set, this option is ignored."

### fn spec.db.withHost

```ts
withHost(host)
```

"Sets the hostname of the default JDBC URL of the chosen vendor. If the `url` option is set, this option is ignored."

### fn spec.db.withPoolInitialSize

```ts
withPoolInitialSize(poolInitialSize)
```

"The initial size of the connection pool."

### fn spec.db.withPoolMaxSize

```ts
withPoolMaxSize(poolMaxSize)
```

"The maximum size of the connection pool."

### fn spec.db.withPoolMinSize

```ts
withPoolMinSize(poolMinSize)
```

"The minimal size of the connection pool."

### fn spec.db.withPort

```ts
withPort(port)
```

"Sets the port of the default JDBC URL of the chosen vendor. If the `url` option is set, this option is ignored."

### fn spec.db.withSchema

```ts
withSchema(schema)
```

"The database schema to be used."

### fn spec.db.withUrl

```ts
withUrl(url)
```

"The full database JDBC URL. If not provided, a default URL is set based on the selected database vendor. For instance, if using 'postgres', the default JDBC URL would be 'jdbc:postgresql://localhost/keycloak'. "

### fn spec.db.withVendor

```ts
withVendor(vendor)
```

"The database vendor."

## obj spec.db.passwordSecret

"The reference to a secret holding the password of the database user."

### fn spec.db.passwordSecret.withKey

```ts
withKey(key)
```



### fn spec.db.passwordSecret.withName

```ts
withName(name)
```



### fn spec.db.passwordSecret.withOptional

```ts
withOptional(optional)
```



## obj spec.db.usernameSecret

"The reference to a secret holding the username of the database user."

### fn spec.db.usernameSecret.withKey

```ts
withKey(key)
```



### fn spec.db.usernameSecret.withName

```ts
withName(name)
```



### fn spec.db.usernameSecret.withOptional

```ts
withOptional(optional)
```



## obj spec.env

"Environment variables for the Keycloak server.\nValues can be either direct values or references to secrets. Use additionalOptions for first-class options rather than KC_ values here."

### fn spec.env.withName

```ts
withName(name)
```



### fn spec.env.withValue

```ts
withValue(value)
```



## obj spec.env.secret



### fn spec.env.secret.withKey

```ts
withKey(key)
```



### fn spec.env.secret.withName

```ts
withName(name)
```



### fn spec.env.secret.withOptional

```ts
withOptional(optional)
```



## obj spec.features

"In this section you can configure Keycloak features, which should be enabled/disabled."

### fn spec.features.withDisabled

```ts
withDisabled(disabled)
```

"Disabled Keycloak features"

### fn spec.features.withDisabledMixin

```ts
withDisabledMixin(disabled)
```

"Disabled Keycloak features"

**Note:** This function appends passed data to existing values

### fn spec.features.withEnabled

```ts
withEnabled(enabled)
```

"Enabled Keycloak features"

### fn spec.features.withEnabledMixin

```ts
withEnabledMixin(enabled)
```

"Enabled Keycloak features"

**Note:** This function appends passed data to existing values

## obj spec.hostname

"In this section you can configure Keycloak hostname and related properties."

### fn spec.hostname.withAdmin

```ts
withAdmin(admin)
```

"The hostname for accessing the administration console. Applicable for Hostname v1 and v2."

### fn spec.hostname.withAdminUrl

```ts
withAdminUrl(adminUrl)
```

"DEPRECATED. Sets the base URL for accessing the administration console, including scheme, host, port and path. Applicable for Hostname v1."

### fn spec.hostname.withBackchannelDynamic

```ts
withBackchannelDynamic(backchannelDynamic)
```

"Enables dynamic resolving of backchannel URLs, including hostname, scheme, port and context path. Set to true if your application accesses Keycloak via a private network. Applicable for Hostname v2."

### fn spec.hostname.withHostname

```ts
withHostname(hostname)
```

"Hostname for the Keycloak server. Applicable for Hostname v1 and v2."

### fn spec.hostname.withStrict

```ts
withStrict(strict)
```

"Disables dynamically resolving the hostname from request headers. Applicable for Hostname v1 and v2."

### fn spec.hostname.withStrictBackchannel

```ts
withStrictBackchannel(strictBackchannel)
```

"DEPRECATED. By default backchannel URLs are dynamically resolved from request headers to allow internal and external applications. Applicable for Hostname v1."

## obj spec.http

"In this section you can configure Keycloak features related to HTTP and HTTPS"

### fn spec.http.withAnnotations

```ts
withAnnotations(annotations)
```

"Annotations to be appended to the Service object"

### fn spec.http.withAnnotationsMixin

```ts
withAnnotationsMixin(annotations)
```

"Annotations to be appended to the Service object"

**Note:** This function appends passed data to existing values

### fn spec.http.withHttpEnabled

```ts
withHttpEnabled(httpEnabled)
```

"Enables the HTTP listener."

### fn spec.http.withHttpPort

```ts
withHttpPort(httpPort)
```

"The used HTTP port."

### fn spec.http.withHttpsPort

```ts
withHttpsPort(httpsPort)
```

"The used HTTPS port."

### fn spec.http.withLabels

```ts
withLabels(labels)
```

"Labels to be appended to the Service object"

### fn spec.http.withLabelsMixin

```ts
withLabelsMixin(labels)
```

"Labels to be appended to the Service object"

**Note:** This function appends passed data to existing values

### fn spec.http.withTlsSecret

```ts
withTlsSecret(tlsSecret)
```

"A secret containing the TLS configuration for HTTPS. Reference: https://kubernetes.io/docs/concepts/configuration/secret/#tls-secrets."

## obj spec.httpManagement

"In this section you can configure Keycloak's management interface setting."

### fn spec.httpManagement.withPort

```ts
withPort(port)
```

"Port of the management interface."

## obj spec.imagePullSecrets

"Secret(s) that might be used when pulling an image from a private container image registry or repository."

### fn spec.imagePullSecrets.withName

```ts
withName(name)
```



## obj spec.import

"In this section you can configure import Jobs"

## obj spec.import.scheduling

"In this section you can configure import jobs scheduling"

### fn spec.import.scheduling.withPriorityClassName

```ts
withPriorityClassName(priorityClassName)
```



### fn spec.import.scheduling.withTolerations

```ts
withTolerations(tolerations)
```



### fn spec.import.scheduling.withTolerationsMixin

```ts
withTolerationsMixin(tolerations)
```



**Note:** This function appends passed data to existing values

### fn spec.import.scheduling.withTopologySpreadConstraints

```ts
withTopologySpreadConstraints(topologySpreadConstraints)
```



### fn spec.import.scheduling.withTopologySpreadConstraintsMixin

```ts
withTopologySpreadConstraintsMixin(topologySpreadConstraints)
```



**Note:** This function appends passed data to existing values

## obj spec.import.scheduling.affinity



## obj spec.import.scheduling.affinity.nodeAffinity



### fn spec.import.scheduling.affinity.nodeAffinity.withPreferredDuringSchedulingIgnoredDuringExecution

```ts
withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.import.scheduling.affinity.nodeAffinity.withPreferredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

## obj spec.import.scheduling.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution



### fn spec.import.scheduling.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.withWeight

```ts
withWeight(weight)
```



## obj spec.import.scheduling.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference



### fn spec.import.scheduling.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.import.scheduling.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.import.scheduling.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.withMatchFields

```ts
withMatchFields(matchFields)
```



### fn spec.import.scheduling.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.withMatchFieldsMixin

```ts
withMatchFieldsMixin(matchFields)
```



**Note:** This function appends passed data to existing values

## obj spec.import.scheduling.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions



### fn spec.import.scheduling.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.import.scheduling.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.import.scheduling.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.import.scheduling.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.import.scheduling.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields



### fn spec.import.scheduling.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields.withKey

```ts
withKey(key)
```



### fn spec.import.scheduling.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields.withOperator

```ts
withOperator(operator)
```



### fn spec.import.scheduling.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields.withValues

```ts
withValues(values)
```



### fn spec.import.scheduling.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.import.scheduling.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution



### fn spec.import.scheduling.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNodeSelectorTerms

```ts
withNodeSelectorTerms(nodeSelectorTerms)
```



### fn spec.import.scheduling.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNodeSelectorTermsMixin

```ts
withNodeSelectorTermsMixin(nodeSelectorTerms)
```



**Note:** This function appends passed data to existing values

## obj spec.import.scheduling.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms



### fn spec.import.scheduling.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.import.scheduling.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.import.scheduling.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.withMatchFields

```ts
withMatchFields(matchFields)
```



### fn spec.import.scheduling.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.withMatchFieldsMixin

```ts
withMatchFieldsMixin(matchFields)
```



**Note:** This function appends passed data to existing values

## obj spec.import.scheduling.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions



### fn spec.import.scheduling.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.import.scheduling.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.import.scheduling.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.import.scheduling.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.import.scheduling.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields



### fn spec.import.scheduling.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields.withKey

```ts
withKey(key)
```



### fn spec.import.scheduling.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields.withOperator

```ts
withOperator(operator)
```



### fn spec.import.scheduling.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields.withValues

```ts
withValues(values)
```



### fn spec.import.scheduling.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.import.scheduling.affinity.podAffinity



### fn spec.import.scheduling.affinity.podAffinity.withPreferredDuringSchedulingIgnoredDuringExecution

```ts
withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.import.scheduling.affinity.podAffinity.withPreferredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

### fn spec.import.scheduling.affinity.podAffinity.withRequiredDuringSchedulingIgnoredDuringExecution

```ts
withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.import.scheduling.affinity.podAffinity.withRequiredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

## obj spec.import.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution



### fn spec.import.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.withWeight

```ts
withWeight(weight)
```



## obj spec.import.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm



### fn spec.import.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMatchLabelKeys

```ts
withMatchLabelKeys(matchLabelKeys)
```



### fn spec.import.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMatchLabelKeysMixin

```ts
withMatchLabelKeysMixin(matchLabelKeys)
```



**Note:** This function appends passed data to existing values

### fn spec.import.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMismatchLabelKeys

```ts
withMismatchLabelKeys(mismatchLabelKeys)
```



### fn spec.import.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMismatchLabelKeysMixin

```ts
withMismatchLabelKeysMixin(mismatchLabelKeys)
```



**Note:** This function appends passed data to existing values

### fn spec.import.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withNamespaces

```ts
withNamespaces(namespaces)
```



### fn spec.import.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withNamespacesMixin

```ts
withNamespacesMixin(namespaces)
```



**Note:** This function appends passed data to existing values

### fn spec.import.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withTopologyKey

```ts
withTopologyKey(topologyKey)
```



## obj spec.import.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector



### fn spec.import.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.import.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.import.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.import.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.import.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions



### fn spec.import.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.import.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.import.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.import.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.import.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector



### fn spec.import.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.import.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.import.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.import.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.import.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions



### fn spec.import.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.import.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.import.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.import.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.import.scheduling.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution



### fn spec.import.scheduling.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMatchLabelKeys

```ts
withMatchLabelKeys(matchLabelKeys)
```



### fn spec.import.scheduling.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMatchLabelKeysMixin

```ts
withMatchLabelKeysMixin(matchLabelKeys)
```



**Note:** This function appends passed data to existing values

### fn spec.import.scheduling.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMismatchLabelKeys

```ts
withMismatchLabelKeys(mismatchLabelKeys)
```



### fn spec.import.scheduling.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMismatchLabelKeysMixin

```ts
withMismatchLabelKeysMixin(mismatchLabelKeys)
```



**Note:** This function appends passed data to existing values

### fn spec.import.scheduling.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNamespaces

```ts
withNamespaces(namespaces)
```



### fn spec.import.scheduling.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNamespacesMixin

```ts
withNamespacesMixin(namespaces)
```



**Note:** This function appends passed data to existing values

### fn spec.import.scheduling.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withTopologyKey

```ts
withTopologyKey(topologyKey)
```



## obj spec.import.scheduling.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector



### fn spec.import.scheduling.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.import.scheduling.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.import.scheduling.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.import.scheduling.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.import.scheduling.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions



### fn spec.import.scheduling.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.import.scheduling.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.import.scheduling.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.import.scheduling.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.import.scheduling.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector



### fn spec.import.scheduling.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.import.scheduling.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.import.scheduling.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.import.scheduling.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.import.scheduling.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions



### fn spec.import.scheduling.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.import.scheduling.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.import.scheduling.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.import.scheduling.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.import.scheduling.affinity.podAntiAffinity



### fn spec.import.scheduling.affinity.podAntiAffinity.withPreferredDuringSchedulingIgnoredDuringExecution

```ts
withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.import.scheduling.affinity.podAntiAffinity.withPreferredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

### fn spec.import.scheduling.affinity.podAntiAffinity.withRequiredDuringSchedulingIgnoredDuringExecution

```ts
withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.import.scheduling.affinity.podAntiAffinity.withRequiredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

## obj spec.import.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution



### fn spec.import.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.withWeight

```ts
withWeight(weight)
```



## obj spec.import.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm



### fn spec.import.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMatchLabelKeys

```ts
withMatchLabelKeys(matchLabelKeys)
```



### fn spec.import.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMatchLabelKeysMixin

```ts
withMatchLabelKeysMixin(matchLabelKeys)
```



**Note:** This function appends passed data to existing values

### fn spec.import.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMismatchLabelKeys

```ts
withMismatchLabelKeys(mismatchLabelKeys)
```



### fn spec.import.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMismatchLabelKeysMixin

```ts
withMismatchLabelKeysMixin(mismatchLabelKeys)
```



**Note:** This function appends passed data to existing values

### fn spec.import.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withNamespaces

```ts
withNamespaces(namespaces)
```



### fn spec.import.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withNamespacesMixin

```ts
withNamespacesMixin(namespaces)
```



**Note:** This function appends passed data to existing values

### fn spec.import.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withTopologyKey

```ts
withTopologyKey(topologyKey)
```



## obj spec.import.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector



### fn spec.import.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.import.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.import.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.import.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.import.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions



### fn spec.import.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.import.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.import.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.import.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.import.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector



### fn spec.import.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.import.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.import.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.import.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.import.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions



### fn spec.import.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.import.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.import.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.import.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.import.scheduling.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution



### fn spec.import.scheduling.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMatchLabelKeys

```ts
withMatchLabelKeys(matchLabelKeys)
```



### fn spec.import.scheduling.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMatchLabelKeysMixin

```ts
withMatchLabelKeysMixin(matchLabelKeys)
```



**Note:** This function appends passed data to existing values

### fn spec.import.scheduling.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMismatchLabelKeys

```ts
withMismatchLabelKeys(mismatchLabelKeys)
```



### fn spec.import.scheduling.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMismatchLabelKeysMixin

```ts
withMismatchLabelKeysMixin(mismatchLabelKeys)
```



**Note:** This function appends passed data to existing values

### fn spec.import.scheduling.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNamespaces

```ts
withNamespaces(namespaces)
```



### fn spec.import.scheduling.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNamespacesMixin

```ts
withNamespacesMixin(namespaces)
```



**Note:** This function appends passed data to existing values

### fn spec.import.scheduling.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withTopologyKey

```ts
withTopologyKey(topologyKey)
```



## obj spec.import.scheduling.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector



### fn spec.import.scheduling.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.import.scheduling.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.import.scheduling.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.import.scheduling.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.import.scheduling.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions



### fn spec.import.scheduling.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.import.scheduling.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.import.scheduling.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.import.scheduling.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.import.scheduling.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector



### fn spec.import.scheduling.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.import.scheduling.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.import.scheduling.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.import.scheduling.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.import.scheduling.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions



### fn spec.import.scheduling.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.import.scheduling.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.import.scheduling.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.import.scheduling.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.import.scheduling.tolerations



### fn spec.import.scheduling.tolerations.withEffect

```ts
withEffect(effect)
```



### fn spec.import.scheduling.tolerations.withKey

```ts
withKey(key)
```



### fn spec.import.scheduling.tolerations.withOperator

```ts
withOperator(operator)
```



### fn spec.import.scheduling.tolerations.withTolerationSeconds

```ts
withTolerationSeconds(tolerationSeconds)
```



### fn spec.import.scheduling.tolerations.withValue

```ts
withValue(value)
```



## obj spec.import.scheduling.topologySpreadConstraints



### fn spec.import.scheduling.topologySpreadConstraints.withMatchLabelKeys

```ts
withMatchLabelKeys(matchLabelKeys)
```



### fn spec.import.scheduling.topologySpreadConstraints.withMatchLabelKeysMixin

```ts
withMatchLabelKeysMixin(matchLabelKeys)
```



**Note:** This function appends passed data to existing values

### fn spec.import.scheduling.topologySpreadConstraints.withMaxSkew

```ts
withMaxSkew(maxSkew)
```



### fn spec.import.scheduling.topologySpreadConstraints.withMinDomains

```ts
withMinDomains(minDomains)
```



### fn spec.import.scheduling.topologySpreadConstraints.withNodeAffinityPolicy

```ts
withNodeAffinityPolicy(nodeAffinityPolicy)
```



### fn spec.import.scheduling.topologySpreadConstraints.withNodeTaintsPolicy

```ts
withNodeTaintsPolicy(nodeTaintsPolicy)
```



### fn spec.import.scheduling.topologySpreadConstraints.withTopologyKey

```ts
withTopologyKey(topologyKey)
```



### fn spec.import.scheduling.topologySpreadConstraints.withWhenUnsatisfiable

```ts
withWhenUnsatisfiable(whenUnsatisfiable)
```



## obj spec.import.scheduling.topologySpreadConstraints.labelSelector



### fn spec.import.scheduling.topologySpreadConstraints.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.import.scheduling.topologySpreadConstraints.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.import.scheduling.topologySpreadConstraints.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.import.scheduling.topologySpreadConstraints.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.import.scheduling.topologySpreadConstraints.labelSelector.matchExpressions



### fn spec.import.scheduling.topologySpreadConstraints.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.import.scheduling.topologySpreadConstraints.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.import.scheduling.topologySpreadConstraints.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.import.scheduling.topologySpreadConstraints.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.ingress

"The deployment is, by default, exposed through a basic ingress.\nYou can change this behaviour by setting the enabled property to false."

### fn spec.ingress.withAnnotations

```ts
withAnnotations(annotations)
```

"Additional annotations to be appended to the Ingress object"

### fn spec.ingress.withAnnotationsMixin

```ts
withAnnotationsMixin(annotations)
```

"Additional annotations to be appended to the Ingress object"

**Note:** This function appends passed data to existing values

### fn spec.ingress.withClassName

```ts
withClassName(className)
```



### fn spec.ingress.withEnabled

```ts
withEnabled(enabled)
```



### fn spec.ingress.withLabels

```ts
withLabels(labels)
```

"Additional labels to be appended to the Ingress object"

### fn spec.ingress.withLabelsMixin

```ts
withLabelsMixin(labels)
```

"Additional labels to be appended to the Ingress object"

**Note:** This function appends passed data to existing values

### fn spec.ingress.withTlsSecret

```ts
withTlsSecret(tlsSecret)
```

"A secret containing the TLS configuration for re-encrypt or TLS termination scenarios. Reference: https://kubernetes.io/docs/concepts/configuration/secret/#tls-secrets."

## obj spec.livenessProbe

"Configuration for liveness probe, by default it is 10 for periodSeconds and 3 for failureThreshold"

### fn spec.livenessProbe.withFailureThreshold

```ts
withFailureThreshold(failureThreshold)
```



### fn spec.livenessProbe.withPeriodSeconds

```ts
withPeriodSeconds(periodSeconds)
```



## obj spec.networkPolicy

"Controls the ingress traffic flow into Keycloak pods."

### fn spec.networkPolicy.withEnabled

```ts
withEnabled(enabled)
```

"Enables or disables the ingress traffic control."

### fn spec.networkPolicy.withHttp

```ts
withHttp(http)
```

"A list of sources which should be able to access this endpoint. Items in this list are combined using a logical OR operation. If this field is empty or missing, this rule matches all sources (traffic not restricted by source). If this field is present and contains at least one item, this rule allows traffic only if the traffic matches at least one item in the from list."

### fn spec.networkPolicy.withHttpMixin

```ts
withHttpMixin(http)
```

"A list of sources which should be able to access this endpoint. Items in this list are combined using a logical OR operation. If this field is empty or missing, this rule matches all sources (traffic not restricted by source). If this field is present and contains at least one item, this rule allows traffic only if the traffic matches at least one item in the from list."

**Note:** This function appends passed data to existing values

### fn spec.networkPolicy.withHttps

```ts
withHttps(https)
```

"A list of sources which should be able to access this endpoint. Items in this list are combined using a logical OR operation. If this field is empty or missing, this rule matches all sources (traffic not restricted by source). If this field is present and contains at least one item, this rule allows traffic only if the traffic matches at least one item in the from list."

### fn spec.networkPolicy.withHttpsMixin

```ts
withHttpsMixin(https)
```

"A list of sources which should be able to access this endpoint. Items in this list are combined using a logical OR operation. If this field is empty or missing, this rule matches all sources (traffic not restricted by source). If this field is present and contains at least one item, this rule allows traffic only if the traffic matches at least one item in the from list."

**Note:** This function appends passed data to existing values

### fn spec.networkPolicy.withManagement

```ts
withManagement(management)
```

"A list of sources which should be able to access this endpoint. Items in this list are combined using a logical OR operation. If this field is empty or missing, this rule matches all sources (traffic not restricted by source). If this field is present and contains at least one item, this rule allows traffic only if the traffic matches at least one item in the from list."

### fn spec.networkPolicy.withManagementMixin

```ts
withManagementMixin(management)
```

"A list of sources which should be able to access this endpoint. Items in this list are combined using a logical OR operation. If this field is empty or missing, this rule matches all sources (traffic not restricted by source). If this field is present and contains at least one item, this rule allows traffic only if the traffic matches at least one item in the from list."

**Note:** This function appends passed data to existing values

## obj spec.networkPolicy.http

"A list of sources which should be able to access this endpoint. Items in this list are combined using a logical OR operation. If this field is empty or missing, this rule matches all sources (traffic not restricted by source). If this field is present and contains at least one item, this rule allows traffic only if the traffic matches at least one item in the from list."

## obj spec.networkPolicy.http.ipBlock



### fn spec.networkPolicy.http.ipBlock.withCidr

```ts
withCidr(cidr)
```



### fn spec.networkPolicy.http.ipBlock.withExcept

```ts
withExcept(except)
```



### fn spec.networkPolicy.http.ipBlock.withExceptMixin

```ts
withExceptMixin(except)
```



**Note:** This function appends passed data to existing values

## obj spec.networkPolicy.http.namespaceSelector



### fn spec.networkPolicy.http.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.networkPolicy.http.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.networkPolicy.http.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.networkPolicy.http.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.networkPolicy.http.namespaceSelector.matchExpressions



### fn spec.networkPolicy.http.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.networkPolicy.http.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.networkPolicy.http.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.networkPolicy.http.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.networkPolicy.http.podSelector



### fn spec.networkPolicy.http.podSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.networkPolicy.http.podSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.networkPolicy.http.podSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.networkPolicy.http.podSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.networkPolicy.http.podSelector.matchExpressions



### fn spec.networkPolicy.http.podSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.networkPolicy.http.podSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.networkPolicy.http.podSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.networkPolicy.http.podSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.networkPolicy.https

"A list of sources which should be able to access this endpoint. Items in this list are combined using a logical OR operation. If this field is empty or missing, this rule matches all sources (traffic not restricted by source). If this field is present and contains at least one item, this rule allows traffic only if the traffic matches at least one item in the from list."

## obj spec.networkPolicy.https.ipBlock



### fn spec.networkPolicy.https.ipBlock.withCidr

```ts
withCidr(cidr)
```



### fn spec.networkPolicy.https.ipBlock.withExcept

```ts
withExcept(except)
```



### fn spec.networkPolicy.https.ipBlock.withExceptMixin

```ts
withExceptMixin(except)
```



**Note:** This function appends passed data to existing values

## obj spec.networkPolicy.https.namespaceSelector



### fn spec.networkPolicy.https.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.networkPolicy.https.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.networkPolicy.https.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.networkPolicy.https.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.networkPolicy.https.namespaceSelector.matchExpressions



### fn spec.networkPolicy.https.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.networkPolicy.https.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.networkPolicy.https.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.networkPolicy.https.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.networkPolicy.https.podSelector



### fn spec.networkPolicy.https.podSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.networkPolicy.https.podSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.networkPolicy.https.podSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.networkPolicy.https.podSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.networkPolicy.https.podSelector.matchExpressions



### fn spec.networkPolicy.https.podSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.networkPolicy.https.podSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.networkPolicy.https.podSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.networkPolicy.https.podSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.networkPolicy.management

"A list of sources which should be able to access this endpoint. Items in this list are combined using a logical OR operation. If this field is empty or missing, this rule matches all sources (traffic not restricted by source). If this field is present and contains at least one item, this rule allows traffic only if the traffic matches at least one item in the from list."

## obj spec.networkPolicy.management.ipBlock



### fn spec.networkPolicy.management.ipBlock.withCidr

```ts
withCidr(cidr)
```



### fn spec.networkPolicy.management.ipBlock.withExcept

```ts
withExcept(except)
```



### fn spec.networkPolicy.management.ipBlock.withExceptMixin

```ts
withExceptMixin(except)
```



**Note:** This function appends passed data to existing values

## obj spec.networkPolicy.management.namespaceSelector



### fn spec.networkPolicy.management.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.networkPolicy.management.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.networkPolicy.management.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.networkPolicy.management.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.networkPolicy.management.namespaceSelector.matchExpressions



### fn spec.networkPolicy.management.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.networkPolicy.management.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.networkPolicy.management.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.networkPolicy.management.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.networkPolicy.management.podSelector



### fn spec.networkPolicy.management.podSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.networkPolicy.management.podSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.networkPolicy.management.podSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.networkPolicy.management.podSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.networkPolicy.management.podSelector.matchExpressions



### fn spec.networkPolicy.management.podSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.networkPolicy.management.podSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.networkPolicy.management.podSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.networkPolicy.management.podSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.proxy

"In this section you can configure Keycloak's reverse proxy setting"

### fn spec.proxy.withHeaders

```ts
withHeaders(headers)
```

"The proxy headers that should be accepted by the server. Misconfiguration might leave the server exposed to security vulnerabilities."

## obj spec.readinessProbe

"Configuration for readiness probe, by default it is 10 for periodSeconds and 3 for failureThreshold"

### fn spec.readinessProbe.withFailureThreshold

```ts
withFailureThreshold(failureThreshold)
```



### fn spec.readinessProbe.withPeriodSeconds

```ts
withPeriodSeconds(periodSeconds)
```



## obj spec.resources

"Compute Resources required by Keycloak container"

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



## obj spec.scheduling

"In this section you can configure Keycloak's scheduling"

### fn spec.scheduling.withPriorityClassName

```ts
withPriorityClassName(priorityClassName)
```



### fn spec.scheduling.withTolerations

```ts
withTolerations(tolerations)
```



### fn spec.scheduling.withTolerationsMixin

```ts
withTolerationsMixin(tolerations)
```



**Note:** This function appends passed data to existing values

### fn spec.scheduling.withTopologySpreadConstraints

```ts
withTopologySpreadConstraints(topologySpreadConstraints)
```



### fn spec.scheduling.withTopologySpreadConstraintsMixin

```ts
withTopologySpreadConstraintsMixin(topologySpreadConstraints)
```



**Note:** This function appends passed data to existing values

## obj spec.scheduling.affinity



## obj spec.scheduling.affinity.nodeAffinity



### fn spec.scheduling.affinity.nodeAffinity.withPreferredDuringSchedulingIgnoredDuringExecution

```ts
withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.scheduling.affinity.nodeAffinity.withPreferredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

## obj spec.scheduling.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution



### fn spec.scheduling.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.withWeight

```ts
withWeight(weight)
```



## obj spec.scheduling.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference



### fn spec.scheduling.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.scheduling.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.scheduling.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.withMatchFields

```ts
withMatchFields(matchFields)
```



### fn spec.scheduling.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.withMatchFieldsMixin

```ts
withMatchFieldsMixin(matchFields)
```



**Note:** This function appends passed data to existing values

## obj spec.scheduling.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions



### fn spec.scheduling.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.scheduling.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.scheduling.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.scheduling.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.scheduling.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields



### fn spec.scheduling.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields.withKey

```ts
withKey(key)
```



### fn spec.scheduling.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields.withOperator

```ts
withOperator(operator)
```



### fn spec.scheduling.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields.withValues

```ts
withValues(values)
```



### fn spec.scheduling.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.scheduling.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution



### fn spec.scheduling.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNodeSelectorTerms

```ts
withNodeSelectorTerms(nodeSelectorTerms)
```



### fn spec.scheduling.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNodeSelectorTermsMixin

```ts
withNodeSelectorTermsMixin(nodeSelectorTerms)
```



**Note:** This function appends passed data to existing values

## obj spec.scheduling.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms



### fn spec.scheduling.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.scheduling.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.scheduling.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.withMatchFields

```ts
withMatchFields(matchFields)
```



### fn spec.scheduling.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.withMatchFieldsMixin

```ts
withMatchFieldsMixin(matchFields)
```



**Note:** This function appends passed data to existing values

## obj spec.scheduling.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions



### fn spec.scheduling.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.scheduling.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.scheduling.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.scheduling.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.scheduling.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields



### fn spec.scheduling.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields.withKey

```ts
withKey(key)
```



### fn spec.scheduling.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields.withOperator

```ts
withOperator(operator)
```



### fn spec.scheduling.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields.withValues

```ts
withValues(values)
```



### fn spec.scheduling.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.scheduling.affinity.podAffinity



### fn spec.scheduling.affinity.podAffinity.withPreferredDuringSchedulingIgnoredDuringExecution

```ts
withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.scheduling.affinity.podAffinity.withPreferredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

### fn spec.scheduling.affinity.podAffinity.withRequiredDuringSchedulingIgnoredDuringExecution

```ts
withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.scheduling.affinity.podAffinity.withRequiredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

## obj spec.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution



### fn spec.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.withWeight

```ts
withWeight(weight)
```



## obj spec.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm



### fn spec.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMatchLabelKeys

```ts
withMatchLabelKeys(matchLabelKeys)
```



### fn spec.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMatchLabelKeysMixin

```ts
withMatchLabelKeysMixin(matchLabelKeys)
```



**Note:** This function appends passed data to existing values

### fn spec.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMismatchLabelKeys

```ts
withMismatchLabelKeys(mismatchLabelKeys)
```



### fn spec.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMismatchLabelKeysMixin

```ts
withMismatchLabelKeysMixin(mismatchLabelKeys)
```



**Note:** This function appends passed data to existing values

### fn spec.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withNamespaces

```ts
withNamespaces(namespaces)
```



### fn spec.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withNamespacesMixin

```ts
withNamespacesMixin(namespaces)
```



**Note:** This function appends passed data to existing values

### fn spec.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withTopologyKey

```ts
withTopologyKey(topologyKey)
```



## obj spec.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector



### fn spec.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions



### fn spec.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector



### fn spec.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions



### fn spec.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.scheduling.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution



### fn spec.scheduling.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMatchLabelKeys

```ts
withMatchLabelKeys(matchLabelKeys)
```



### fn spec.scheduling.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMatchLabelKeysMixin

```ts
withMatchLabelKeysMixin(matchLabelKeys)
```



**Note:** This function appends passed data to existing values

### fn spec.scheduling.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMismatchLabelKeys

```ts
withMismatchLabelKeys(mismatchLabelKeys)
```



### fn spec.scheduling.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMismatchLabelKeysMixin

```ts
withMismatchLabelKeysMixin(mismatchLabelKeys)
```



**Note:** This function appends passed data to existing values

### fn spec.scheduling.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNamespaces

```ts
withNamespaces(namespaces)
```



### fn spec.scheduling.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNamespacesMixin

```ts
withNamespacesMixin(namespaces)
```



**Note:** This function appends passed data to existing values

### fn spec.scheduling.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withTopologyKey

```ts
withTopologyKey(topologyKey)
```



## obj spec.scheduling.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector



### fn spec.scheduling.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.scheduling.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.scheduling.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.scheduling.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.scheduling.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions



### fn spec.scheduling.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.scheduling.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.scheduling.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.scheduling.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.scheduling.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector



### fn spec.scheduling.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.scheduling.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.scheduling.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.scheduling.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.scheduling.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions



### fn spec.scheduling.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.scheduling.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.scheduling.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.scheduling.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.scheduling.affinity.podAntiAffinity



### fn spec.scheduling.affinity.podAntiAffinity.withPreferredDuringSchedulingIgnoredDuringExecution

```ts
withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.scheduling.affinity.podAntiAffinity.withPreferredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

### fn spec.scheduling.affinity.podAntiAffinity.withRequiredDuringSchedulingIgnoredDuringExecution

```ts
withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.scheduling.affinity.podAntiAffinity.withRequiredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

## obj spec.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution



### fn spec.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.withWeight

```ts
withWeight(weight)
```



## obj spec.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm



### fn spec.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMatchLabelKeys

```ts
withMatchLabelKeys(matchLabelKeys)
```



### fn spec.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMatchLabelKeysMixin

```ts
withMatchLabelKeysMixin(matchLabelKeys)
```



**Note:** This function appends passed data to existing values

### fn spec.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMismatchLabelKeys

```ts
withMismatchLabelKeys(mismatchLabelKeys)
```



### fn spec.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMismatchLabelKeysMixin

```ts
withMismatchLabelKeysMixin(mismatchLabelKeys)
```



**Note:** This function appends passed data to existing values

### fn spec.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withNamespaces

```ts
withNamespaces(namespaces)
```



### fn spec.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withNamespacesMixin

```ts
withNamespacesMixin(namespaces)
```



**Note:** This function appends passed data to existing values

### fn spec.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withTopologyKey

```ts
withTopologyKey(topologyKey)
```



## obj spec.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector



### fn spec.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions



### fn spec.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector



### fn spec.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions



### fn spec.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.scheduling.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution



### fn spec.scheduling.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMatchLabelKeys

```ts
withMatchLabelKeys(matchLabelKeys)
```



### fn spec.scheduling.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMatchLabelKeysMixin

```ts
withMatchLabelKeysMixin(matchLabelKeys)
```



**Note:** This function appends passed data to existing values

### fn spec.scheduling.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMismatchLabelKeys

```ts
withMismatchLabelKeys(mismatchLabelKeys)
```



### fn spec.scheduling.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMismatchLabelKeysMixin

```ts
withMismatchLabelKeysMixin(mismatchLabelKeys)
```



**Note:** This function appends passed data to existing values

### fn spec.scheduling.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNamespaces

```ts
withNamespaces(namespaces)
```



### fn spec.scheduling.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNamespacesMixin

```ts
withNamespacesMixin(namespaces)
```



**Note:** This function appends passed data to existing values

### fn spec.scheduling.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withTopologyKey

```ts
withTopologyKey(topologyKey)
```



## obj spec.scheduling.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector



### fn spec.scheduling.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.scheduling.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.scheduling.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.scheduling.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.scheduling.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions



### fn spec.scheduling.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.scheduling.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.scheduling.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.scheduling.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.scheduling.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector



### fn spec.scheduling.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.scheduling.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.scheduling.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.scheduling.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.scheduling.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions



### fn spec.scheduling.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.scheduling.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.scheduling.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.scheduling.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.scheduling.tolerations



### fn spec.scheduling.tolerations.withEffect

```ts
withEffect(effect)
```



### fn spec.scheduling.tolerations.withKey

```ts
withKey(key)
```



### fn spec.scheduling.tolerations.withOperator

```ts
withOperator(operator)
```



### fn spec.scheduling.tolerations.withTolerationSeconds

```ts
withTolerationSeconds(tolerationSeconds)
```



### fn spec.scheduling.tolerations.withValue

```ts
withValue(value)
```



## obj spec.scheduling.topologySpreadConstraints



### fn spec.scheduling.topologySpreadConstraints.withMatchLabelKeys

```ts
withMatchLabelKeys(matchLabelKeys)
```



### fn spec.scheduling.topologySpreadConstraints.withMatchLabelKeysMixin

```ts
withMatchLabelKeysMixin(matchLabelKeys)
```



**Note:** This function appends passed data to existing values

### fn spec.scheduling.topologySpreadConstraints.withMaxSkew

```ts
withMaxSkew(maxSkew)
```



### fn spec.scheduling.topologySpreadConstraints.withMinDomains

```ts
withMinDomains(minDomains)
```



### fn spec.scheduling.topologySpreadConstraints.withNodeAffinityPolicy

```ts
withNodeAffinityPolicy(nodeAffinityPolicy)
```



### fn spec.scheduling.topologySpreadConstraints.withNodeTaintsPolicy

```ts
withNodeTaintsPolicy(nodeTaintsPolicy)
```



### fn spec.scheduling.topologySpreadConstraints.withTopologyKey

```ts
withTopologyKey(topologyKey)
```



### fn spec.scheduling.topologySpreadConstraints.withWhenUnsatisfiable

```ts
withWhenUnsatisfiable(whenUnsatisfiable)
```



## obj spec.scheduling.topologySpreadConstraints.labelSelector



### fn spec.scheduling.topologySpreadConstraints.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.scheduling.topologySpreadConstraints.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.scheduling.topologySpreadConstraints.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.scheduling.topologySpreadConstraints.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.scheduling.topologySpreadConstraints.labelSelector.matchExpressions



### fn spec.scheduling.topologySpreadConstraints.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.scheduling.topologySpreadConstraints.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.scheduling.topologySpreadConstraints.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.scheduling.topologySpreadConstraints.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.serviceMonitor

"Configuration related to the generated ServiceMonitor"

### fn spec.serviceMonitor.withEnabled

```ts
withEnabled(enabled)
```

"Enables or disables the creation of the ServiceMonitor."

### fn spec.serviceMonitor.withInterval

```ts
withInterval(interval)
```

"Interval at which metrics should be scraped"

### fn spec.serviceMonitor.withScrapeTimeout

```ts
withScrapeTimeout(scrapeTimeout)
```

"Timeout after which the scrape is ended"

## obj spec.startupProbe

"Configuration for startup probe, by default it is 1 for periodSeconds and 600 for failureThreshold"

### fn spec.startupProbe.withFailureThreshold

```ts
withFailureThreshold(failureThreshold)
```



### fn spec.startupProbe.withPeriodSeconds

```ts
withPeriodSeconds(periodSeconds)
```



## obj spec.tracing

"In this section you can configure OpenTelemetry Tracing for Keycloak."

### fn spec.tracing.withCompression

```ts
withCompression(compression)
```

"OpenTelemetry compression method used to compress payloads. If unset, compression is disabled. Possible values are: gzip, none."

### fn spec.tracing.withEnabled

```ts
withEnabled(enabled)
```

"Enables the OpenTelemetry tracing."

### fn spec.tracing.withEndpoint

```ts
withEndpoint(endpoint)
```

"OpenTelemetry endpoint to connect to."

### fn spec.tracing.withProtocol

```ts
withProtocol(protocol)
```

"OpenTelemetry protocol used for the telemetry data (default 'grpc'). For more information, check the Tracing guide."

### fn spec.tracing.withResourceAttributes

```ts
withResourceAttributes(resourceAttributes)
```

"OpenTelemetry resource attributes present in the exported trace to characterize the telemetry producer."

### fn spec.tracing.withResourceAttributesMixin

```ts
withResourceAttributesMixin(resourceAttributes)
```

"OpenTelemetry resource attributes present in the exported trace to characterize the telemetry producer."

**Note:** This function appends passed data to existing values

### fn spec.tracing.withSamplerRatio

```ts
withSamplerRatio(samplerRatio)
```

"OpenTelemetry sampler ratio. Probability that a span will be sampled. Expected double value in interval [0,1]."

### fn spec.tracing.withSamplerType

```ts
withSamplerType(samplerType)
```

"OpenTelemetry sampler to use for tracing (default 'traceidratio'). For more information, check the Tracing guide."

### fn spec.tracing.withServiceName

```ts
withServiceName(serviceName)
```

"OpenTelemetry service name. Takes precedence over 'service.name' defined in the 'resourceAttributes' map."

## obj spec.transaction

"In this section you can find all properties related to the settings of transaction behavior."

### fn spec.transaction.withXaEnabled

```ts
withXaEnabled(xaEnabled)
```

"Determine whether Keycloak should use a non-XA datasource in case the database does not support XA transactions."

## obj spec.unsupported

"In this section you can configure podTemplate advanced features, not production-ready, and not supported settings.\nUse at your own risk and open an issue with your use-case if you don't find an alternative way."

## obj spec.unsupported.podTemplate

"You can configure that will be merged with the one configured by default by the operator.\nUse at your own risk, we reserve the possibility to remove/change the way any field gets merged in future releases without notice.\nReference: https://kubernetes.io/docs/concepts/workloads/pods/#pod-templates"

## obj spec.unsupported.podTemplate.metadata



### fn spec.unsupported.podTemplate.metadata.withAnnotations

```ts
withAnnotations(annotations)
```



### fn spec.unsupported.podTemplate.metadata.withAnnotationsMixin

```ts
withAnnotationsMixin(annotations)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.metadata.withCreationTimestamp

```ts
withCreationTimestamp(creationTimestamp)
```



### fn spec.unsupported.podTemplate.metadata.withDeletionGracePeriodSeconds

```ts
withDeletionGracePeriodSeconds(deletionGracePeriodSeconds)
```



### fn spec.unsupported.podTemplate.metadata.withDeletionTimestamp

```ts
withDeletionTimestamp(deletionTimestamp)
```



### fn spec.unsupported.podTemplate.metadata.withFinalizers

```ts
withFinalizers(finalizers)
```



### fn spec.unsupported.podTemplate.metadata.withFinalizersMixin

```ts
withFinalizersMixin(finalizers)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.metadata.withGenerateName

```ts
withGenerateName(generateName)
```



### fn spec.unsupported.podTemplate.metadata.withGeneration

```ts
withGeneration(generation)
```



### fn spec.unsupported.podTemplate.metadata.withLabels

```ts
withLabels(labels)
```



### fn spec.unsupported.podTemplate.metadata.withLabelsMixin

```ts
withLabelsMixin(labels)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.metadata.withManagedFields

```ts
withManagedFields(managedFields)
```



### fn spec.unsupported.podTemplate.metadata.withManagedFieldsMixin

```ts
withManagedFieldsMixin(managedFields)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.metadata.withName

```ts
withName(name)
```



### fn spec.unsupported.podTemplate.metadata.withNamespace

```ts
withNamespace(namespace)
```



### fn spec.unsupported.podTemplate.metadata.withOwnerReferences

```ts
withOwnerReferences(ownerReferences)
```



### fn spec.unsupported.podTemplate.metadata.withOwnerReferencesMixin

```ts
withOwnerReferencesMixin(ownerReferences)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.metadata.withResourceVersion

```ts
withResourceVersion(resourceVersion)
```



### fn spec.unsupported.podTemplate.metadata.withSelfLink

```ts
withSelfLink(selfLink)
```



### fn spec.unsupported.podTemplate.metadata.withUid

```ts
withUid(uid)
```



## obj spec.unsupported.podTemplate.metadata.managedFields



### fn spec.unsupported.podTemplate.metadata.managedFields.withApiVersion

```ts
withApiVersion(apiVersion)
```



### fn spec.unsupported.podTemplate.metadata.managedFields.withFieldsType

```ts
withFieldsType(fieldsType)
```



### fn spec.unsupported.podTemplate.metadata.managedFields.withFieldsV1

```ts
withFieldsV1(fieldsV1)
```



### fn spec.unsupported.podTemplate.metadata.managedFields.withFieldsV1Mixin

```ts
withFieldsV1Mixin(fieldsV1)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.metadata.managedFields.withManager

```ts
withManager(manager)
```



### fn spec.unsupported.podTemplate.metadata.managedFields.withOperation

```ts
withOperation(operation)
```



### fn spec.unsupported.podTemplate.metadata.managedFields.withSubresource

```ts
withSubresource(subresource)
```



### fn spec.unsupported.podTemplate.metadata.managedFields.withTime

```ts
withTime(time)
```



## obj spec.unsupported.podTemplate.metadata.ownerReferences



### fn spec.unsupported.podTemplate.metadata.ownerReferences.withApiVersion

```ts
withApiVersion(apiVersion)
```



### fn spec.unsupported.podTemplate.metadata.ownerReferences.withBlockOwnerDeletion

```ts
withBlockOwnerDeletion(blockOwnerDeletion)
```



### fn spec.unsupported.podTemplate.metadata.ownerReferences.withController

```ts
withController(controller)
```



### fn spec.unsupported.podTemplate.metadata.ownerReferences.withKind

```ts
withKind(kind)
```



### fn spec.unsupported.podTemplate.metadata.ownerReferences.withName

```ts
withName(name)
```



### fn spec.unsupported.podTemplate.metadata.ownerReferences.withUid

```ts
withUid(uid)
```



## obj spec.unsupported.podTemplate.spec



### fn spec.unsupported.podTemplate.spec.withActiveDeadlineSeconds

```ts
withActiveDeadlineSeconds(activeDeadlineSeconds)
```



### fn spec.unsupported.podTemplate.spec.withAutomountServiceAccountToken

```ts
withAutomountServiceAccountToken(automountServiceAccountToken)
```



### fn spec.unsupported.podTemplate.spec.withContainers

```ts
withContainers(containers)
```



### fn spec.unsupported.podTemplate.spec.withContainersMixin

```ts
withContainersMixin(containers)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.withDnsPolicy

```ts
withDnsPolicy(dnsPolicy)
```



### fn spec.unsupported.podTemplate.spec.withEnableServiceLinks

```ts
withEnableServiceLinks(enableServiceLinks)
```



### fn spec.unsupported.podTemplate.spec.withEphemeralContainers

```ts
withEphemeralContainers(ephemeralContainers)
```



### fn spec.unsupported.podTemplate.spec.withEphemeralContainersMixin

```ts
withEphemeralContainersMixin(ephemeralContainers)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.withHostAliases

```ts
withHostAliases(hostAliases)
```



### fn spec.unsupported.podTemplate.spec.withHostAliasesMixin

```ts
withHostAliasesMixin(hostAliases)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.withHostIPC

```ts
withHostIPC(hostIPC)
```



### fn spec.unsupported.podTemplate.spec.withHostNetwork

```ts
withHostNetwork(hostNetwork)
```



### fn spec.unsupported.podTemplate.spec.withHostPID

```ts
withHostPID(hostPID)
```



### fn spec.unsupported.podTemplate.spec.withHostUsers

```ts
withHostUsers(hostUsers)
```



### fn spec.unsupported.podTemplate.spec.withHostname

```ts
withHostname(hostname)
```



### fn spec.unsupported.podTemplate.spec.withImagePullSecrets

```ts
withImagePullSecrets(imagePullSecrets)
```



### fn spec.unsupported.podTemplate.spec.withImagePullSecretsMixin

```ts
withImagePullSecretsMixin(imagePullSecrets)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.withInitContainers

```ts
withInitContainers(initContainers)
```



### fn spec.unsupported.podTemplate.spec.withInitContainersMixin

```ts
withInitContainersMixin(initContainers)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.withNodeName

```ts
withNodeName(nodeName)
```



### fn spec.unsupported.podTemplate.spec.withNodeSelector

```ts
withNodeSelector(nodeSelector)
```



### fn spec.unsupported.podTemplate.spec.withNodeSelectorMixin

```ts
withNodeSelectorMixin(nodeSelector)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.withOverhead

```ts
withOverhead(overhead)
```



### fn spec.unsupported.podTemplate.spec.withOverheadMixin

```ts
withOverheadMixin(overhead)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.withPreemptionPolicy

```ts
withPreemptionPolicy(preemptionPolicy)
```



### fn spec.unsupported.podTemplate.spec.withPriority

```ts
withPriority(priority)
```



### fn spec.unsupported.podTemplate.spec.withPriorityClassName

```ts
withPriorityClassName(priorityClassName)
```



### fn spec.unsupported.podTemplate.spec.withReadinessGates

```ts
withReadinessGates(readinessGates)
```



### fn spec.unsupported.podTemplate.spec.withReadinessGatesMixin

```ts
withReadinessGatesMixin(readinessGates)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.withResourceClaims

```ts
withResourceClaims(resourceClaims)
```



### fn spec.unsupported.podTemplate.spec.withResourceClaimsMixin

```ts
withResourceClaimsMixin(resourceClaims)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.withRestartPolicy

```ts
withRestartPolicy(restartPolicy)
```



### fn spec.unsupported.podTemplate.spec.withRuntimeClassName

```ts
withRuntimeClassName(runtimeClassName)
```



### fn spec.unsupported.podTemplate.spec.withSchedulerName

```ts
withSchedulerName(schedulerName)
```



### fn spec.unsupported.podTemplate.spec.withSchedulingGates

```ts
withSchedulingGates(schedulingGates)
```



### fn spec.unsupported.podTemplate.spec.withSchedulingGatesMixin

```ts
withSchedulingGatesMixin(schedulingGates)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.withServiceAccount

```ts
withServiceAccount(serviceAccount)
```



### fn spec.unsupported.podTemplate.spec.withServiceAccountName

```ts
withServiceAccountName(serviceAccountName)
```



### fn spec.unsupported.podTemplate.spec.withSetHostnameAsFQDN

```ts
withSetHostnameAsFQDN(setHostnameAsFQDN)
```



### fn spec.unsupported.podTemplate.spec.withShareProcessNamespace

```ts
withShareProcessNamespace(shareProcessNamespace)
```



### fn spec.unsupported.podTemplate.spec.withSubdomain

```ts
withSubdomain(subdomain)
```



### fn spec.unsupported.podTemplate.spec.withTerminationGracePeriodSeconds

```ts
withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)
```



### fn spec.unsupported.podTemplate.spec.withTolerations

```ts
withTolerations(tolerations)
```



### fn spec.unsupported.podTemplate.spec.withTolerationsMixin

```ts
withTolerationsMixin(tolerations)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.withTopologySpreadConstraints

```ts
withTopologySpreadConstraints(topologySpreadConstraints)
```



### fn spec.unsupported.podTemplate.spec.withTopologySpreadConstraintsMixin

```ts
withTopologySpreadConstraintsMixin(topologySpreadConstraints)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.withVolumes

```ts
withVolumes(volumes)
```



### fn spec.unsupported.podTemplate.spec.withVolumesMixin

```ts
withVolumesMixin(volumes)
```



**Note:** This function appends passed data to existing values

## obj spec.unsupported.podTemplate.spec.affinity



## obj spec.unsupported.podTemplate.spec.affinity.nodeAffinity



### fn spec.unsupported.podTemplate.spec.affinity.nodeAffinity.withPreferredDuringSchedulingIgnoredDuringExecution

```ts
withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.unsupported.podTemplate.spec.affinity.nodeAffinity.withPreferredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

## obj spec.unsupported.podTemplate.spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution



### fn spec.unsupported.podTemplate.spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.withWeight

```ts
withWeight(weight)
```



## obj spec.unsupported.podTemplate.spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference



### fn spec.unsupported.podTemplate.spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.unsupported.podTemplate.spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.withMatchFields

```ts
withMatchFields(matchFields)
```



### fn spec.unsupported.podTemplate.spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.withMatchFieldsMixin

```ts
withMatchFieldsMixin(matchFields)
```



**Note:** This function appends passed data to existing values

## obj spec.unsupported.podTemplate.spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions



### fn spec.unsupported.podTemplate.spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.unsupported.podTemplate.spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.unsupported.podTemplate.spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.unsupported.podTemplate.spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.unsupported.podTemplate.spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields



### fn spec.unsupported.podTemplate.spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields.withKey

```ts
withKey(key)
```



### fn spec.unsupported.podTemplate.spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields.withOperator

```ts
withOperator(operator)
```



### fn spec.unsupported.podTemplate.spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields.withValues

```ts
withValues(values)
```



### fn spec.unsupported.podTemplate.spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.unsupported.podTemplate.spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution



### fn spec.unsupported.podTemplate.spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNodeSelectorTerms

```ts
withNodeSelectorTerms(nodeSelectorTerms)
```



### fn spec.unsupported.podTemplate.spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNodeSelectorTermsMixin

```ts
withNodeSelectorTermsMixin(nodeSelectorTerms)
```



**Note:** This function appends passed data to existing values

## obj spec.unsupported.podTemplate.spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms



### fn spec.unsupported.podTemplate.spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.unsupported.podTemplate.spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.withMatchFields

```ts
withMatchFields(matchFields)
```



### fn spec.unsupported.podTemplate.spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.withMatchFieldsMixin

```ts
withMatchFieldsMixin(matchFields)
```



**Note:** This function appends passed data to existing values

## obj spec.unsupported.podTemplate.spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions



### fn spec.unsupported.podTemplate.spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.unsupported.podTemplate.spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.unsupported.podTemplate.spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.unsupported.podTemplate.spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.unsupported.podTemplate.spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields



### fn spec.unsupported.podTemplate.spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields.withKey

```ts
withKey(key)
```



### fn spec.unsupported.podTemplate.spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields.withOperator

```ts
withOperator(operator)
```



### fn spec.unsupported.podTemplate.spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields.withValues

```ts
withValues(values)
```



### fn spec.unsupported.podTemplate.spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.unsupported.podTemplate.spec.affinity.podAffinity



### fn spec.unsupported.podTemplate.spec.affinity.podAffinity.withPreferredDuringSchedulingIgnoredDuringExecution

```ts
withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.unsupported.podTemplate.spec.affinity.podAffinity.withPreferredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.affinity.podAffinity.withRequiredDuringSchedulingIgnoredDuringExecution

```ts
withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.unsupported.podTemplate.spec.affinity.podAffinity.withRequiredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

## obj spec.unsupported.podTemplate.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution



### fn spec.unsupported.podTemplate.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.withWeight

```ts
withWeight(weight)
```



## obj spec.unsupported.podTemplate.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm



### fn spec.unsupported.podTemplate.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMatchLabelKeys

```ts
withMatchLabelKeys(matchLabelKeys)
```



### fn spec.unsupported.podTemplate.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMatchLabelKeysMixin

```ts
withMatchLabelKeysMixin(matchLabelKeys)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMismatchLabelKeys

```ts
withMismatchLabelKeys(mismatchLabelKeys)
```



### fn spec.unsupported.podTemplate.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMismatchLabelKeysMixin

```ts
withMismatchLabelKeysMixin(mismatchLabelKeys)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withNamespaces

```ts
withNamespaces(namespaces)
```



### fn spec.unsupported.podTemplate.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withNamespacesMixin

```ts
withNamespacesMixin(namespaces)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withTopologyKey

```ts
withTopologyKey(topologyKey)
```



## obj spec.unsupported.podTemplate.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector



### fn spec.unsupported.podTemplate.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.unsupported.podTemplate.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.unsupported.podTemplate.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.unsupported.podTemplate.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions



### fn spec.unsupported.podTemplate.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.unsupported.podTemplate.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.unsupported.podTemplate.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.unsupported.podTemplate.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.unsupported.podTemplate.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector



### fn spec.unsupported.podTemplate.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.unsupported.podTemplate.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.unsupported.podTemplate.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.unsupported.podTemplate.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions



### fn spec.unsupported.podTemplate.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.unsupported.podTemplate.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.unsupported.podTemplate.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.unsupported.podTemplate.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.unsupported.podTemplate.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution



### fn spec.unsupported.podTemplate.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMatchLabelKeys

```ts
withMatchLabelKeys(matchLabelKeys)
```



### fn spec.unsupported.podTemplate.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMatchLabelKeysMixin

```ts
withMatchLabelKeysMixin(matchLabelKeys)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMismatchLabelKeys

```ts
withMismatchLabelKeys(mismatchLabelKeys)
```



### fn spec.unsupported.podTemplate.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMismatchLabelKeysMixin

```ts
withMismatchLabelKeysMixin(mismatchLabelKeys)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNamespaces

```ts
withNamespaces(namespaces)
```



### fn spec.unsupported.podTemplate.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNamespacesMixin

```ts
withNamespacesMixin(namespaces)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withTopologyKey

```ts
withTopologyKey(topologyKey)
```



## obj spec.unsupported.podTemplate.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector



### fn spec.unsupported.podTemplate.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.unsupported.podTemplate.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.unsupported.podTemplate.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.unsupported.podTemplate.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions



### fn spec.unsupported.podTemplate.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.unsupported.podTemplate.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.unsupported.podTemplate.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.unsupported.podTemplate.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.unsupported.podTemplate.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector



### fn spec.unsupported.podTemplate.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.unsupported.podTemplate.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.unsupported.podTemplate.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.unsupported.podTemplate.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions



### fn spec.unsupported.podTemplate.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.unsupported.podTemplate.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.unsupported.podTemplate.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.unsupported.podTemplate.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.unsupported.podTemplate.spec.affinity.podAntiAffinity



### fn spec.unsupported.podTemplate.spec.affinity.podAntiAffinity.withPreferredDuringSchedulingIgnoredDuringExecution

```ts
withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.unsupported.podTemplate.spec.affinity.podAntiAffinity.withPreferredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.affinity.podAntiAffinity.withRequiredDuringSchedulingIgnoredDuringExecution

```ts
withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.unsupported.podTemplate.spec.affinity.podAntiAffinity.withRequiredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

## obj spec.unsupported.podTemplate.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution



### fn spec.unsupported.podTemplate.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.withWeight

```ts
withWeight(weight)
```



## obj spec.unsupported.podTemplate.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm



### fn spec.unsupported.podTemplate.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMatchLabelKeys

```ts
withMatchLabelKeys(matchLabelKeys)
```



### fn spec.unsupported.podTemplate.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMatchLabelKeysMixin

```ts
withMatchLabelKeysMixin(matchLabelKeys)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMismatchLabelKeys

```ts
withMismatchLabelKeys(mismatchLabelKeys)
```



### fn spec.unsupported.podTemplate.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMismatchLabelKeysMixin

```ts
withMismatchLabelKeysMixin(mismatchLabelKeys)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withNamespaces

```ts
withNamespaces(namespaces)
```



### fn spec.unsupported.podTemplate.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withNamespacesMixin

```ts
withNamespacesMixin(namespaces)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withTopologyKey

```ts
withTopologyKey(topologyKey)
```



## obj spec.unsupported.podTemplate.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector



### fn spec.unsupported.podTemplate.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.unsupported.podTemplate.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.unsupported.podTemplate.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.unsupported.podTemplate.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions



### fn spec.unsupported.podTemplate.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.unsupported.podTemplate.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.unsupported.podTemplate.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.unsupported.podTemplate.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.unsupported.podTemplate.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector



### fn spec.unsupported.podTemplate.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.unsupported.podTemplate.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.unsupported.podTemplate.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.unsupported.podTemplate.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions



### fn spec.unsupported.podTemplate.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.unsupported.podTemplate.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.unsupported.podTemplate.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.unsupported.podTemplate.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.unsupported.podTemplate.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution



### fn spec.unsupported.podTemplate.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMatchLabelKeys

```ts
withMatchLabelKeys(matchLabelKeys)
```



### fn spec.unsupported.podTemplate.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMatchLabelKeysMixin

```ts
withMatchLabelKeysMixin(matchLabelKeys)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMismatchLabelKeys

```ts
withMismatchLabelKeys(mismatchLabelKeys)
```



### fn spec.unsupported.podTemplate.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMismatchLabelKeysMixin

```ts
withMismatchLabelKeysMixin(mismatchLabelKeys)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNamespaces

```ts
withNamespaces(namespaces)
```



### fn spec.unsupported.podTemplate.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNamespacesMixin

```ts
withNamespacesMixin(namespaces)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withTopologyKey

```ts
withTopologyKey(topologyKey)
```



## obj spec.unsupported.podTemplate.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector



### fn spec.unsupported.podTemplate.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.unsupported.podTemplate.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.unsupported.podTemplate.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.unsupported.podTemplate.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions



### fn spec.unsupported.podTemplate.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.unsupported.podTemplate.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.unsupported.podTemplate.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.unsupported.podTemplate.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.unsupported.podTemplate.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector



### fn spec.unsupported.podTemplate.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.unsupported.podTemplate.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.unsupported.podTemplate.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.unsupported.podTemplate.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions



### fn spec.unsupported.podTemplate.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.unsupported.podTemplate.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.unsupported.podTemplate.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.unsupported.podTemplate.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.unsupported.podTemplate.spec.containers



### fn spec.unsupported.podTemplate.spec.containers.withArgs

```ts
withArgs(args)
```



### fn spec.unsupported.podTemplate.spec.containers.withArgsMixin

```ts
withArgsMixin(args)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.containers.withCommand

```ts
withCommand(command)
```



### fn spec.unsupported.podTemplate.spec.containers.withCommandMixin

```ts
withCommandMixin(command)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.containers.withEnv

```ts
withEnv(env)
```



### fn spec.unsupported.podTemplate.spec.containers.withEnvFrom

```ts
withEnvFrom(envFrom)
```



### fn spec.unsupported.podTemplate.spec.containers.withEnvFromMixin

```ts
withEnvFromMixin(envFrom)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.containers.withEnvMixin

```ts
withEnvMixin(env)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.containers.withImage

```ts
withImage(image)
```



### fn spec.unsupported.podTemplate.spec.containers.withImagePullPolicy

```ts
withImagePullPolicy(imagePullPolicy)
```



### fn spec.unsupported.podTemplate.spec.containers.withName

```ts
withName(name)
```



### fn spec.unsupported.podTemplate.spec.containers.withPorts

```ts
withPorts(ports)
```



### fn spec.unsupported.podTemplate.spec.containers.withPortsMixin

```ts
withPortsMixin(ports)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.containers.withResizePolicy

```ts
withResizePolicy(resizePolicy)
```



### fn spec.unsupported.podTemplate.spec.containers.withResizePolicyMixin

```ts
withResizePolicyMixin(resizePolicy)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.containers.withRestartPolicy

```ts
withRestartPolicy(restartPolicy)
```



### fn spec.unsupported.podTemplate.spec.containers.withStdin

```ts
withStdin(stdin)
```



### fn spec.unsupported.podTemplate.spec.containers.withStdinOnce

```ts
withStdinOnce(stdinOnce)
```



### fn spec.unsupported.podTemplate.spec.containers.withTerminationMessagePath

```ts
withTerminationMessagePath(terminationMessagePath)
```



### fn spec.unsupported.podTemplate.spec.containers.withTerminationMessagePolicy

```ts
withTerminationMessagePolicy(terminationMessagePolicy)
```



### fn spec.unsupported.podTemplate.spec.containers.withTty

```ts
withTty(tty)
```



### fn spec.unsupported.podTemplate.spec.containers.withVolumeDevices

```ts
withVolumeDevices(volumeDevices)
```



### fn spec.unsupported.podTemplate.spec.containers.withVolumeDevicesMixin

```ts
withVolumeDevicesMixin(volumeDevices)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.containers.withVolumeMounts

```ts
withVolumeMounts(volumeMounts)
```



### fn spec.unsupported.podTemplate.spec.containers.withVolumeMountsMixin

```ts
withVolumeMountsMixin(volumeMounts)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.containers.withWorkingDir

```ts
withWorkingDir(workingDir)
```



## obj spec.unsupported.podTemplate.spec.containers.env



### fn spec.unsupported.podTemplate.spec.containers.env.withName

```ts
withName(name)
```



### fn spec.unsupported.podTemplate.spec.containers.env.withValue

```ts
withValue(value)
```



## obj spec.unsupported.podTemplate.spec.containers.env.valueFrom



## obj spec.unsupported.podTemplate.spec.containers.env.valueFrom.configMapKeyRef



### fn spec.unsupported.podTemplate.spec.containers.env.valueFrom.configMapKeyRef.withKey

```ts
withKey(key)
```



### fn spec.unsupported.podTemplate.spec.containers.env.valueFrom.configMapKeyRef.withName

```ts
withName(name)
```



### fn spec.unsupported.podTemplate.spec.containers.env.valueFrom.configMapKeyRef.withOptional

```ts
withOptional(optional)
```



## obj spec.unsupported.podTemplate.spec.containers.env.valueFrom.fieldRef



### fn spec.unsupported.podTemplate.spec.containers.env.valueFrom.fieldRef.withApiVersion

```ts
withApiVersion(apiVersion)
```



### fn spec.unsupported.podTemplate.spec.containers.env.valueFrom.fieldRef.withFieldPath

```ts
withFieldPath(fieldPath)
```



## obj spec.unsupported.podTemplate.spec.containers.env.valueFrom.resourceFieldRef



### fn spec.unsupported.podTemplate.spec.containers.env.valueFrom.resourceFieldRef.withContainerName

```ts
withContainerName(containerName)
```



### fn spec.unsupported.podTemplate.spec.containers.env.valueFrom.resourceFieldRef.withDivisor

```ts
withDivisor(divisor)
```



### fn spec.unsupported.podTemplate.spec.containers.env.valueFrom.resourceFieldRef.withResource

```ts
withResource(resource)
```



## obj spec.unsupported.podTemplate.spec.containers.env.valueFrom.secretKeyRef



### fn spec.unsupported.podTemplate.spec.containers.env.valueFrom.secretKeyRef.withKey

```ts
withKey(key)
```



### fn spec.unsupported.podTemplate.spec.containers.env.valueFrom.secretKeyRef.withName

```ts
withName(name)
```



### fn spec.unsupported.podTemplate.spec.containers.env.valueFrom.secretKeyRef.withOptional

```ts
withOptional(optional)
```



## obj spec.unsupported.podTemplate.spec.containers.envFrom



### fn spec.unsupported.podTemplate.spec.containers.envFrom.withPrefix

```ts
withPrefix(prefix)
```



## obj spec.unsupported.podTemplate.spec.containers.envFrom.configMapRef



### fn spec.unsupported.podTemplate.spec.containers.envFrom.configMapRef.withName

```ts
withName(name)
```



### fn spec.unsupported.podTemplate.spec.containers.envFrom.configMapRef.withOptional

```ts
withOptional(optional)
```



## obj spec.unsupported.podTemplate.spec.containers.envFrom.secretRef



### fn spec.unsupported.podTemplate.spec.containers.envFrom.secretRef.withName

```ts
withName(name)
```



### fn spec.unsupported.podTemplate.spec.containers.envFrom.secretRef.withOptional

```ts
withOptional(optional)
```



## obj spec.unsupported.podTemplate.spec.containers.lifecycle



### fn spec.unsupported.podTemplate.spec.containers.lifecycle.withStopSignal

```ts
withStopSignal(stopSignal)
```



## obj spec.unsupported.podTemplate.spec.containers.lifecycle.postStart



## obj spec.unsupported.podTemplate.spec.containers.lifecycle.postStart.exec



### fn spec.unsupported.podTemplate.spec.containers.lifecycle.postStart.exec.withCommand

```ts
withCommand(command)
```



### fn spec.unsupported.podTemplate.spec.containers.lifecycle.postStart.exec.withCommandMixin

```ts
withCommandMixin(command)
```



**Note:** This function appends passed data to existing values

## obj spec.unsupported.podTemplate.spec.containers.lifecycle.postStart.httpGet



### fn spec.unsupported.podTemplate.spec.containers.lifecycle.postStart.httpGet.withHost

```ts
withHost(host)
```



### fn spec.unsupported.podTemplate.spec.containers.lifecycle.postStart.httpGet.withHttpHeaders

```ts
withHttpHeaders(httpHeaders)
```



### fn spec.unsupported.podTemplate.spec.containers.lifecycle.postStart.httpGet.withHttpHeadersMixin

```ts
withHttpHeadersMixin(httpHeaders)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.containers.lifecycle.postStart.httpGet.withPath

```ts
withPath(path)
```



### fn spec.unsupported.podTemplate.spec.containers.lifecycle.postStart.httpGet.withPort

```ts
withPort(port)
```



### fn spec.unsupported.podTemplate.spec.containers.lifecycle.postStart.httpGet.withScheme

```ts
withScheme(scheme)
```



## obj spec.unsupported.podTemplate.spec.containers.lifecycle.postStart.httpGet.httpHeaders



### fn spec.unsupported.podTemplate.spec.containers.lifecycle.postStart.httpGet.httpHeaders.withName

```ts
withName(name)
```



### fn spec.unsupported.podTemplate.spec.containers.lifecycle.postStart.httpGet.httpHeaders.withValue

```ts
withValue(value)
```



## obj spec.unsupported.podTemplate.spec.containers.lifecycle.postStart.sleep



### fn spec.unsupported.podTemplate.spec.containers.lifecycle.postStart.sleep.withSeconds

```ts
withSeconds(seconds)
```



## obj spec.unsupported.podTemplate.spec.containers.lifecycle.postStart.tcpSocket



### fn spec.unsupported.podTemplate.spec.containers.lifecycle.postStart.tcpSocket.withHost

```ts
withHost(host)
```



### fn spec.unsupported.podTemplate.spec.containers.lifecycle.postStart.tcpSocket.withPort

```ts
withPort(port)
```



## obj spec.unsupported.podTemplate.spec.containers.lifecycle.preStop



## obj spec.unsupported.podTemplate.spec.containers.lifecycle.preStop.exec



### fn spec.unsupported.podTemplate.spec.containers.lifecycle.preStop.exec.withCommand

```ts
withCommand(command)
```



### fn spec.unsupported.podTemplate.spec.containers.lifecycle.preStop.exec.withCommandMixin

```ts
withCommandMixin(command)
```



**Note:** This function appends passed data to existing values

## obj spec.unsupported.podTemplate.spec.containers.lifecycle.preStop.httpGet



### fn spec.unsupported.podTemplate.spec.containers.lifecycle.preStop.httpGet.withHost

```ts
withHost(host)
```



### fn spec.unsupported.podTemplate.spec.containers.lifecycle.preStop.httpGet.withHttpHeaders

```ts
withHttpHeaders(httpHeaders)
```



### fn spec.unsupported.podTemplate.spec.containers.lifecycle.preStop.httpGet.withHttpHeadersMixin

```ts
withHttpHeadersMixin(httpHeaders)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.containers.lifecycle.preStop.httpGet.withPath

```ts
withPath(path)
```



### fn spec.unsupported.podTemplate.spec.containers.lifecycle.preStop.httpGet.withPort

```ts
withPort(port)
```



### fn spec.unsupported.podTemplate.spec.containers.lifecycle.preStop.httpGet.withScheme

```ts
withScheme(scheme)
```



## obj spec.unsupported.podTemplate.spec.containers.lifecycle.preStop.httpGet.httpHeaders



### fn spec.unsupported.podTemplate.spec.containers.lifecycle.preStop.httpGet.httpHeaders.withName

```ts
withName(name)
```



### fn spec.unsupported.podTemplate.spec.containers.lifecycle.preStop.httpGet.httpHeaders.withValue

```ts
withValue(value)
```



## obj spec.unsupported.podTemplate.spec.containers.lifecycle.preStop.sleep



### fn spec.unsupported.podTemplate.spec.containers.lifecycle.preStop.sleep.withSeconds

```ts
withSeconds(seconds)
```



## obj spec.unsupported.podTemplate.spec.containers.lifecycle.preStop.tcpSocket



### fn spec.unsupported.podTemplate.spec.containers.lifecycle.preStop.tcpSocket.withHost

```ts
withHost(host)
```



### fn spec.unsupported.podTemplate.spec.containers.lifecycle.preStop.tcpSocket.withPort

```ts
withPort(port)
```



## obj spec.unsupported.podTemplate.spec.containers.livenessProbe



### fn spec.unsupported.podTemplate.spec.containers.livenessProbe.withFailureThreshold

```ts
withFailureThreshold(failureThreshold)
```



### fn spec.unsupported.podTemplate.spec.containers.livenessProbe.withInitialDelaySeconds

```ts
withInitialDelaySeconds(initialDelaySeconds)
```



### fn spec.unsupported.podTemplate.spec.containers.livenessProbe.withPeriodSeconds

```ts
withPeriodSeconds(periodSeconds)
```



### fn spec.unsupported.podTemplate.spec.containers.livenessProbe.withSuccessThreshold

```ts
withSuccessThreshold(successThreshold)
```



### fn spec.unsupported.podTemplate.spec.containers.livenessProbe.withTerminationGracePeriodSeconds

```ts
withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)
```



### fn spec.unsupported.podTemplate.spec.containers.livenessProbe.withTimeoutSeconds

```ts
withTimeoutSeconds(timeoutSeconds)
```



## obj spec.unsupported.podTemplate.spec.containers.livenessProbe.exec



### fn spec.unsupported.podTemplate.spec.containers.livenessProbe.exec.withCommand

```ts
withCommand(command)
```



### fn spec.unsupported.podTemplate.spec.containers.livenessProbe.exec.withCommandMixin

```ts
withCommandMixin(command)
```



**Note:** This function appends passed data to existing values

## obj spec.unsupported.podTemplate.spec.containers.livenessProbe.grpc



### fn spec.unsupported.podTemplate.spec.containers.livenessProbe.grpc.withPort

```ts
withPort(port)
```



### fn spec.unsupported.podTemplate.spec.containers.livenessProbe.grpc.withService

```ts
withService(service)
```



## obj spec.unsupported.podTemplate.spec.containers.livenessProbe.httpGet



### fn spec.unsupported.podTemplate.spec.containers.livenessProbe.httpGet.withHost

```ts
withHost(host)
```



### fn spec.unsupported.podTemplate.spec.containers.livenessProbe.httpGet.withHttpHeaders

```ts
withHttpHeaders(httpHeaders)
```



### fn spec.unsupported.podTemplate.spec.containers.livenessProbe.httpGet.withHttpHeadersMixin

```ts
withHttpHeadersMixin(httpHeaders)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.containers.livenessProbe.httpGet.withPath

```ts
withPath(path)
```



### fn spec.unsupported.podTemplate.spec.containers.livenessProbe.httpGet.withPort

```ts
withPort(port)
```



### fn spec.unsupported.podTemplate.spec.containers.livenessProbe.httpGet.withScheme

```ts
withScheme(scheme)
```



## obj spec.unsupported.podTemplate.spec.containers.livenessProbe.httpGet.httpHeaders



### fn spec.unsupported.podTemplate.spec.containers.livenessProbe.httpGet.httpHeaders.withName

```ts
withName(name)
```



### fn spec.unsupported.podTemplate.spec.containers.livenessProbe.httpGet.httpHeaders.withValue

```ts
withValue(value)
```



## obj spec.unsupported.podTemplate.spec.containers.livenessProbe.tcpSocket



### fn spec.unsupported.podTemplate.spec.containers.livenessProbe.tcpSocket.withHost

```ts
withHost(host)
```



### fn spec.unsupported.podTemplate.spec.containers.livenessProbe.tcpSocket.withPort

```ts
withPort(port)
```



## obj spec.unsupported.podTemplate.spec.containers.ports



### fn spec.unsupported.podTemplate.spec.containers.ports.withContainerPort

```ts
withContainerPort(containerPort)
```



### fn spec.unsupported.podTemplate.spec.containers.ports.withHostIP

```ts
withHostIP(hostIP)
```



### fn spec.unsupported.podTemplate.spec.containers.ports.withHostPort

```ts
withHostPort(hostPort)
```



### fn spec.unsupported.podTemplate.spec.containers.ports.withName

```ts
withName(name)
```



### fn spec.unsupported.podTemplate.spec.containers.ports.withProtocol

```ts
withProtocol(protocol)
```



## obj spec.unsupported.podTemplate.spec.containers.readinessProbe



### fn spec.unsupported.podTemplate.spec.containers.readinessProbe.withFailureThreshold

```ts
withFailureThreshold(failureThreshold)
```



### fn spec.unsupported.podTemplate.spec.containers.readinessProbe.withInitialDelaySeconds

```ts
withInitialDelaySeconds(initialDelaySeconds)
```



### fn spec.unsupported.podTemplate.spec.containers.readinessProbe.withPeriodSeconds

```ts
withPeriodSeconds(periodSeconds)
```



### fn spec.unsupported.podTemplate.spec.containers.readinessProbe.withSuccessThreshold

```ts
withSuccessThreshold(successThreshold)
```



### fn spec.unsupported.podTemplate.spec.containers.readinessProbe.withTerminationGracePeriodSeconds

```ts
withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)
```



### fn spec.unsupported.podTemplate.spec.containers.readinessProbe.withTimeoutSeconds

```ts
withTimeoutSeconds(timeoutSeconds)
```



## obj spec.unsupported.podTemplate.spec.containers.readinessProbe.exec



### fn spec.unsupported.podTemplate.spec.containers.readinessProbe.exec.withCommand

```ts
withCommand(command)
```



### fn spec.unsupported.podTemplate.spec.containers.readinessProbe.exec.withCommandMixin

```ts
withCommandMixin(command)
```



**Note:** This function appends passed data to existing values

## obj spec.unsupported.podTemplate.spec.containers.readinessProbe.grpc



### fn spec.unsupported.podTemplate.spec.containers.readinessProbe.grpc.withPort

```ts
withPort(port)
```



### fn spec.unsupported.podTemplate.spec.containers.readinessProbe.grpc.withService

```ts
withService(service)
```



## obj spec.unsupported.podTemplate.spec.containers.readinessProbe.httpGet



### fn spec.unsupported.podTemplate.spec.containers.readinessProbe.httpGet.withHost

```ts
withHost(host)
```



### fn spec.unsupported.podTemplate.spec.containers.readinessProbe.httpGet.withHttpHeaders

```ts
withHttpHeaders(httpHeaders)
```



### fn spec.unsupported.podTemplate.spec.containers.readinessProbe.httpGet.withHttpHeadersMixin

```ts
withHttpHeadersMixin(httpHeaders)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.containers.readinessProbe.httpGet.withPath

```ts
withPath(path)
```



### fn spec.unsupported.podTemplate.spec.containers.readinessProbe.httpGet.withPort

```ts
withPort(port)
```



### fn spec.unsupported.podTemplate.spec.containers.readinessProbe.httpGet.withScheme

```ts
withScheme(scheme)
```



## obj spec.unsupported.podTemplate.spec.containers.readinessProbe.httpGet.httpHeaders



### fn spec.unsupported.podTemplate.spec.containers.readinessProbe.httpGet.httpHeaders.withName

```ts
withName(name)
```



### fn spec.unsupported.podTemplate.spec.containers.readinessProbe.httpGet.httpHeaders.withValue

```ts
withValue(value)
```



## obj spec.unsupported.podTemplate.spec.containers.readinessProbe.tcpSocket



### fn spec.unsupported.podTemplate.spec.containers.readinessProbe.tcpSocket.withHost

```ts
withHost(host)
```



### fn spec.unsupported.podTemplate.spec.containers.readinessProbe.tcpSocket.withPort

```ts
withPort(port)
```



## obj spec.unsupported.podTemplate.spec.containers.resizePolicy



### fn spec.unsupported.podTemplate.spec.containers.resizePolicy.withResourceName

```ts
withResourceName(resourceName)
```



### fn spec.unsupported.podTemplate.spec.containers.resizePolicy.withRestartPolicy

```ts
withRestartPolicy(restartPolicy)
```



## obj spec.unsupported.podTemplate.spec.containers.resources



### fn spec.unsupported.podTemplate.spec.containers.resources.withClaims

```ts
withClaims(claims)
```



### fn spec.unsupported.podTemplate.spec.containers.resources.withClaimsMixin

```ts
withClaimsMixin(claims)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.containers.resources.withLimits

```ts
withLimits(limits)
```



### fn spec.unsupported.podTemplate.spec.containers.resources.withLimitsMixin

```ts
withLimitsMixin(limits)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.containers.resources.withRequests

```ts
withRequests(requests)
```



### fn spec.unsupported.podTemplate.spec.containers.resources.withRequestsMixin

```ts
withRequestsMixin(requests)
```



**Note:** This function appends passed data to existing values

## obj spec.unsupported.podTemplate.spec.containers.resources.claims



### fn spec.unsupported.podTemplate.spec.containers.resources.claims.withName

```ts
withName(name)
```



### fn spec.unsupported.podTemplate.spec.containers.resources.claims.withRequest

```ts
withRequest(request)
```



## obj spec.unsupported.podTemplate.spec.containers.securityContext



### fn spec.unsupported.podTemplate.spec.containers.securityContext.withAllowPrivilegeEscalation

```ts
withAllowPrivilegeEscalation(allowPrivilegeEscalation)
```



### fn spec.unsupported.podTemplate.spec.containers.securityContext.withPrivileged

```ts
withPrivileged(privileged)
```



### fn spec.unsupported.podTemplate.spec.containers.securityContext.withProcMount

```ts
withProcMount(procMount)
```



### fn spec.unsupported.podTemplate.spec.containers.securityContext.withReadOnlyRootFilesystem

```ts
withReadOnlyRootFilesystem(readOnlyRootFilesystem)
```



### fn spec.unsupported.podTemplate.spec.containers.securityContext.withRunAsGroup

```ts
withRunAsGroup(runAsGroup)
```



### fn spec.unsupported.podTemplate.spec.containers.securityContext.withRunAsNonRoot

```ts
withRunAsNonRoot(runAsNonRoot)
```



### fn spec.unsupported.podTemplate.spec.containers.securityContext.withRunAsUser

```ts
withRunAsUser(runAsUser)
```



## obj spec.unsupported.podTemplate.spec.containers.securityContext.appArmorProfile



### fn spec.unsupported.podTemplate.spec.containers.securityContext.appArmorProfile.withLocalhostProfile

```ts
withLocalhostProfile(localhostProfile)
```



### fn spec.unsupported.podTemplate.spec.containers.securityContext.appArmorProfile.withType

```ts
withType(type)
```



## obj spec.unsupported.podTemplate.spec.containers.securityContext.capabilities



### fn spec.unsupported.podTemplate.spec.containers.securityContext.capabilities.withAdd

```ts
withAdd(add)
```



### fn spec.unsupported.podTemplate.spec.containers.securityContext.capabilities.withAddMixin

```ts
withAddMixin(add)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.containers.securityContext.capabilities.withDrop

```ts
withDrop(drop)
```



### fn spec.unsupported.podTemplate.spec.containers.securityContext.capabilities.withDropMixin

```ts
withDropMixin(drop)
```



**Note:** This function appends passed data to existing values

## obj spec.unsupported.podTemplate.spec.containers.securityContext.seLinuxOptions



### fn spec.unsupported.podTemplate.spec.containers.securityContext.seLinuxOptions.withLevel

```ts
withLevel(level)
```



### fn spec.unsupported.podTemplate.spec.containers.securityContext.seLinuxOptions.withRole

```ts
withRole(role)
```



### fn spec.unsupported.podTemplate.spec.containers.securityContext.seLinuxOptions.withType

```ts
withType(type)
```



### fn spec.unsupported.podTemplate.spec.containers.securityContext.seLinuxOptions.withUser

```ts
withUser(user)
```



## obj spec.unsupported.podTemplate.spec.containers.securityContext.seccompProfile



### fn spec.unsupported.podTemplate.spec.containers.securityContext.seccompProfile.withLocalhostProfile

```ts
withLocalhostProfile(localhostProfile)
```



### fn spec.unsupported.podTemplate.spec.containers.securityContext.seccompProfile.withType

```ts
withType(type)
```



## obj spec.unsupported.podTemplate.spec.containers.securityContext.windowsOptions



### fn spec.unsupported.podTemplate.spec.containers.securityContext.windowsOptions.withGmsaCredentialSpec

```ts
withGmsaCredentialSpec(gmsaCredentialSpec)
```



### fn spec.unsupported.podTemplate.spec.containers.securityContext.windowsOptions.withGmsaCredentialSpecName

```ts
withGmsaCredentialSpecName(gmsaCredentialSpecName)
```



### fn spec.unsupported.podTemplate.spec.containers.securityContext.windowsOptions.withHostProcess

```ts
withHostProcess(hostProcess)
```



### fn spec.unsupported.podTemplate.spec.containers.securityContext.windowsOptions.withRunAsUserName

```ts
withRunAsUserName(runAsUserName)
```



## obj spec.unsupported.podTemplate.spec.containers.startupProbe



### fn spec.unsupported.podTemplate.spec.containers.startupProbe.withFailureThreshold

```ts
withFailureThreshold(failureThreshold)
```



### fn spec.unsupported.podTemplate.spec.containers.startupProbe.withInitialDelaySeconds

```ts
withInitialDelaySeconds(initialDelaySeconds)
```



### fn spec.unsupported.podTemplate.spec.containers.startupProbe.withPeriodSeconds

```ts
withPeriodSeconds(periodSeconds)
```



### fn spec.unsupported.podTemplate.spec.containers.startupProbe.withSuccessThreshold

```ts
withSuccessThreshold(successThreshold)
```



### fn spec.unsupported.podTemplate.spec.containers.startupProbe.withTerminationGracePeriodSeconds

```ts
withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)
```



### fn spec.unsupported.podTemplate.spec.containers.startupProbe.withTimeoutSeconds

```ts
withTimeoutSeconds(timeoutSeconds)
```



## obj spec.unsupported.podTemplate.spec.containers.startupProbe.exec



### fn spec.unsupported.podTemplate.spec.containers.startupProbe.exec.withCommand

```ts
withCommand(command)
```



### fn spec.unsupported.podTemplate.spec.containers.startupProbe.exec.withCommandMixin

```ts
withCommandMixin(command)
```



**Note:** This function appends passed data to existing values

## obj spec.unsupported.podTemplate.spec.containers.startupProbe.grpc



### fn spec.unsupported.podTemplate.spec.containers.startupProbe.grpc.withPort

```ts
withPort(port)
```



### fn spec.unsupported.podTemplate.spec.containers.startupProbe.grpc.withService

```ts
withService(service)
```



## obj spec.unsupported.podTemplate.spec.containers.startupProbe.httpGet



### fn spec.unsupported.podTemplate.spec.containers.startupProbe.httpGet.withHost

```ts
withHost(host)
```



### fn spec.unsupported.podTemplate.spec.containers.startupProbe.httpGet.withHttpHeaders

```ts
withHttpHeaders(httpHeaders)
```



### fn spec.unsupported.podTemplate.spec.containers.startupProbe.httpGet.withHttpHeadersMixin

```ts
withHttpHeadersMixin(httpHeaders)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.containers.startupProbe.httpGet.withPath

```ts
withPath(path)
```



### fn spec.unsupported.podTemplate.spec.containers.startupProbe.httpGet.withPort

```ts
withPort(port)
```



### fn spec.unsupported.podTemplate.spec.containers.startupProbe.httpGet.withScheme

```ts
withScheme(scheme)
```



## obj spec.unsupported.podTemplate.spec.containers.startupProbe.httpGet.httpHeaders



### fn spec.unsupported.podTemplate.spec.containers.startupProbe.httpGet.httpHeaders.withName

```ts
withName(name)
```



### fn spec.unsupported.podTemplate.spec.containers.startupProbe.httpGet.httpHeaders.withValue

```ts
withValue(value)
```



## obj spec.unsupported.podTemplate.spec.containers.startupProbe.tcpSocket



### fn spec.unsupported.podTemplate.spec.containers.startupProbe.tcpSocket.withHost

```ts
withHost(host)
```



### fn spec.unsupported.podTemplate.spec.containers.startupProbe.tcpSocket.withPort

```ts
withPort(port)
```



## obj spec.unsupported.podTemplate.spec.containers.volumeDevices



### fn spec.unsupported.podTemplate.spec.containers.volumeDevices.withDevicePath

```ts
withDevicePath(devicePath)
```



### fn spec.unsupported.podTemplate.spec.containers.volumeDevices.withName

```ts
withName(name)
```



## obj spec.unsupported.podTemplate.spec.containers.volumeMounts



### fn spec.unsupported.podTemplate.spec.containers.volumeMounts.withMountPath

```ts
withMountPath(mountPath)
```



### fn spec.unsupported.podTemplate.spec.containers.volumeMounts.withMountPropagation

```ts
withMountPropagation(mountPropagation)
```



### fn spec.unsupported.podTemplate.spec.containers.volumeMounts.withName

```ts
withName(name)
```



### fn spec.unsupported.podTemplate.spec.containers.volumeMounts.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.unsupported.podTemplate.spec.containers.volumeMounts.withRecursiveReadOnly

```ts
withRecursiveReadOnly(recursiveReadOnly)
```



### fn spec.unsupported.podTemplate.spec.containers.volumeMounts.withSubPath

```ts
withSubPath(subPath)
```



### fn spec.unsupported.podTemplate.spec.containers.volumeMounts.withSubPathExpr

```ts
withSubPathExpr(subPathExpr)
```



## obj spec.unsupported.podTemplate.spec.dnsConfig



### fn spec.unsupported.podTemplate.spec.dnsConfig.withNameservers

```ts
withNameservers(nameservers)
```



### fn spec.unsupported.podTemplate.spec.dnsConfig.withNameserversMixin

```ts
withNameserversMixin(nameservers)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.dnsConfig.withOptions

```ts
withOptions(options)
```



### fn spec.unsupported.podTemplate.spec.dnsConfig.withOptionsMixin

```ts
withOptionsMixin(options)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.dnsConfig.withSearches

```ts
withSearches(searches)
```



### fn spec.unsupported.podTemplate.spec.dnsConfig.withSearchesMixin

```ts
withSearchesMixin(searches)
```



**Note:** This function appends passed data to existing values

## obj spec.unsupported.podTemplate.spec.dnsConfig.options



### fn spec.unsupported.podTemplate.spec.dnsConfig.options.withName

```ts
withName(name)
```



### fn spec.unsupported.podTemplate.spec.dnsConfig.options.withValue

```ts
withValue(value)
```



## obj spec.unsupported.podTemplate.spec.ephemeralContainers



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.withArgs

```ts
withArgs(args)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.withArgsMixin

```ts
withArgsMixin(args)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.ephemeralContainers.withCommand

```ts
withCommand(command)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.withCommandMixin

```ts
withCommandMixin(command)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.ephemeralContainers.withEnv

```ts
withEnv(env)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.withEnvFrom

```ts
withEnvFrom(envFrom)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.withEnvFromMixin

```ts
withEnvFromMixin(envFrom)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.ephemeralContainers.withEnvMixin

```ts
withEnvMixin(env)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.ephemeralContainers.withImage

```ts
withImage(image)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.withImagePullPolicy

```ts
withImagePullPolicy(imagePullPolicy)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.withName

```ts
withName(name)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.withPorts

```ts
withPorts(ports)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.withPortsMixin

```ts
withPortsMixin(ports)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.ephemeralContainers.withResizePolicy

```ts
withResizePolicy(resizePolicy)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.withResizePolicyMixin

```ts
withResizePolicyMixin(resizePolicy)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.ephemeralContainers.withRestartPolicy

```ts
withRestartPolicy(restartPolicy)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.withStdin

```ts
withStdin(stdin)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.withStdinOnce

```ts
withStdinOnce(stdinOnce)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.withTargetContainerName

```ts
withTargetContainerName(targetContainerName)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.withTerminationMessagePath

```ts
withTerminationMessagePath(terminationMessagePath)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.withTerminationMessagePolicy

```ts
withTerminationMessagePolicy(terminationMessagePolicy)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.withTty

```ts
withTty(tty)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.withVolumeDevices

```ts
withVolumeDevices(volumeDevices)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.withVolumeDevicesMixin

```ts
withVolumeDevicesMixin(volumeDevices)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.ephemeralContainers.withVolumeMounts

```ts
withVolumeMounts(volumeMounts)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.withVolumeMountsMixin

```ts
withVolumeMountsMixin(volumeMounts)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.ephemeralContainers.withWorkingDir

```ts
withWorkingDir(workingDir)
```



## obj spec.unsupported.podTemplate.spec.ephemeralContainers.env



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.env.withName

```ts
withName(name)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.env.withValue

```ts
withValue(value)
```



## obj spec.unsupported.podTemplate.spec.ephemeralContainers.env.valueFrom



## obj spec.unsupported.podTemplate.spec.ephemeralContainers.env.valueFrom.configMapKeyRef



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.env.valueFrom.configMapKeyRef.withKey

```ts
withKey(key)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.env.valueFrom.configMapKeyRef.withName

```ts
withName(name)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.env.valueFrom.configMapKeyRef.withOptional

```ts
withOptional(optional)
```



## obj spec.unsupported.podTemplate.spec.ephemeralContainers.env.valueFrom.fieldRef



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.env.valueFrom.fieldRef.withApiVersion

```ts
withApiVersion(apiVersion)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.env.valueFrom.fieldRef.withFieldPath

```ts
withFieldPath(fieldPath)
```



## obj spec.unsupported.podTemplate.spec.ephemeralContainers.env.valueFrom.resourceFieldRef



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.env.valueFrom.resourceFieldRef.withContainerName

```ts
withContainerName(containerName)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.env.valueFrom.resourceFieldRef.withDivisor

```ts
withDivisor(divisor)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.env.valueFrom.resourceFieldRef.withResource

```ts
withResource(resource)
```



## obj spec.unsupported.podTemplate.spec.ephemeralContainers.env.valueFrom.secretKeyRef



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.env.valueFrom.secretKeyRef.withKey

```ts
withKey(key)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.env.valueFrom.secretKeyRef.withName

```ts
withName(name)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.env.valueFrom.secretKeyRef.withOptional

```ts
withOptional(optional)
```



## obj spec.unsupported.podTemplate.spec.ephemeralContainers.envFrom



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.envFrom.withPrefix

```ts
withPrefix(prefix)
```



## obj spec.unsupported.podTemplate.spec.ephemeralContainers.envFrom.configMapRef



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.envFrom.configMapRef.withName

```ts
withName(name)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.envFrom.configMapRef.withOptional

```ts
withOptional(optional)
```



## obj spec.unsupported.podTemplate.spec.ephemeralContainers.envFrom.secretRef



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.envFrom.secretRef.withName

```ts
withName(name)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.envFrom.secretRef.withOptional

```ts
withOptional(optional)
```



## obj spec.unsupported.podTemplate.spec.ephemeralContainers.lifecycle



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.lifecycle.withStopSignal

```ts
withStopSignal(stopSignal)
```



## obj spec.unsupported.podTemplate.spec.ephemeralContainers.lifecycle.postStart



## obj spec.unsupported.podTemplate.spec.ephemeralContainers.lifecycle.postStart.exec



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.lifecycle.postStart.exec.withCommand

```ts
withCommand(command)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.lifecycle.postStart.exec.withCommandMixin

```ts
withCommandMixin(command)
```



**Note:** This function appends passed data to existing values

## obj spec.unsupported.podTemplate.spec.ephemeralContainers.lifecycle.postStart.httpGet



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.lifecycle.postStart.httpGet.withHost

```ts
withHost(host)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.lifecycle.postStart.httpGet.withHttpHeaders

```ts
withHttpHeaders(httpHeaders)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.lifecycle.postStart.httpGet.withHttpHeadersMixin

```ts
withHttpHeadersMixin(httpHeaders)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.ephemeralContainers.lifecycle.postStart.httpGet.withPath

```ts
withPath(path)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.lifecycle.postStart.httpGet.withPort

```ts
withPort(port)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.lifecycle.postStart.httpGet.withScheme

```ts
withScheme(scheme)
```



## obj spec.unsupported.podTemplate.spec.ephemeralContainers.lifecycle.postStart.httpGet.httpHeaders



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.lifecycle.postStart.httpGet.httpHeaders.withName

```ts
withName(name)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.lifecycle.postStart.httpGet.httpHeaders.withValue

```ts
withValue(value)
```



## obj spec.unsupported.podTemplate.spec.ephemeralContainers.lifecycle.postStart.sleep



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.lifecycle.postStart.sleep.withSeconds

```ts
withSeconds(seconds)
```



## obj spec.unsupported.podTemplate.spec.ephemeralContainers.lifecycle.postStart.tcpSocket



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.lifecycle.postStart.tcpSocket.withHost

```ts
withHost(host)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.lifecycle.postStart.tcpSocket.withPort

```ts
withPort(port)
```



## obj spec.unsupported.podTemplate.spec.ephemeralContainers.lifecycle.preStop



## obj spec.unsupported.podTemplate.spec.ephemeralContainers.lifecycle.preStop.exec



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.lifecycle.preStop.exec.withCommand

```ts
withCommand(command)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.lifecycle.preStop.exec.withCommandMixin

```ts
withCommandMixin(command)
```



**Note:** This function appends passed data to existing values

## obj spec.unsupported.podTemplate.spec.ephemeralContainers.lifecycle.preStop.httpGet



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.lifecycle.preStop.httpGet.withHost

```ts
withHost(host)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.lifecycle.preStop.httpGet.withHttpHeaders

```ts
withHttpHeaders(httpHeaders)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.lifecycle.preStop.httpGet.withHttpHeadersMixin

```ts
withHttpHeadersMixin(httpHeaders)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.ephemeralContainers.lifecycle.preStop.httpGet.withPath

```ts
withPath(path)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.lifecycle.preStop.httpGet.withPort

```ts
withPort(port)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.lifecycle.preStop.httpGet.withScheme

```ts
withScheme(scheme)
```



## obj spec.unsupported.podTemplate.spec.ephemeralContainers.lifecycle.preStop.httpGet.httpHeaders



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.lifecycle.preStop.httpGet.httpHeaders.withName

```ts
withName(name)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.lifecycle.preStop.httpGet.httpHeaders.withValue

```ts
withValue(value)
```



## obj spec.unsupported.podTemplate.spec.ephemeralContainers.lifecycle.preStop.sleep



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.lifecycle.preStop.sleep.withSeconds

```ts
withSeconds(seconds)
```



## obj spec.unsupported.podTemplate.spec.ephemeralContainers.lifecycle.preStop.tcpSocket



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.lifecycle.preStop.tcpSocket.withHost

```ts
withHost(host)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.lifecycle.preStop.tcpSocket.withPort

```ts
withPort(port)
```



## obj spec.unsupported.podTemplate.spec.ephemeralContainers.livenessProbe



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.livenessProbe.withFailureThreshold

```ts
withFailureThreshold(failureThreshold)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.livenessProbe.withInitialDelaySeconds

```ts
withInitialDelaySeconds(initialDelaySeconds)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.livenessProbe.withPeriodSeconds

```ts
withPeriodSeconds(periodSeconds)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.livenessProbe.withSuccessThreshold

```ts
withSuccessThreshold(successThreshold)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.livenessProbe.withTerminationGracePeriodSeconds

```ts
withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.livenessProbe.withTimeoutSeconds

```ts
withTimeoutSeconds(timeoutSeconds)
```



## obj spec.unsupported.podTemplate.spec.ephemeralContainers.livenessProbe.exec



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.livenessProbe.exec.withCommand

```ts
withCommand(command)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.livenessProbe.exec.withCommandMixin

```ts
withCommandMixin(command)
```



**Note:** This function appends passed data to existing values

## obj spec.unsupported.podTemplate.spec.ephemeralContainers.livenessProbe.grpc



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.livenessProbe.grpc.withPort

```ts
withPort(port)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.livenessProbe.grpc.withService

```ts
withService(service)
```



## obj spec.unsupported.podTemplate.spec.ephemeralContainers.livenessProbe.httpGet



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.livenessProbe.httpGet.withHost

```ts
withHost(host)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.livenessProbe.httpGet.withHttpHeaders

```ts
withHttpHeaders(httpHeaders)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.livenessProbe.httpGet.withHttpHeadersMixin

```ts
withHttpHeadersMixin(httpHeaders)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.ephemeralContainers.livenessProbe.httpGet.withPath

```ts
withPath(path)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.livenessProbe.httpGet.withPort

```ts
withPort(port)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.livenessProbe.httpGet.withScheme

```ts
withScheme(scheme)
```



## obj spec.unsupported.podTemplate.spec.ephemeralContainers.livenessProbe.httpGet.httpHeaders



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.livenessProbe.httpGet.httpHeaders.withName

```ts
withName(name)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.livenessProbe.httpGet.httpHeaders.withValue

```ts
withValue(value)
```



## obj spec.unsupported.podTemplate.spec.ephemeralContainers.livenessProbe.tcpSocket



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.livenessProbe.tcpSocket.withHost

```ts
withHost(host)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.livenessProbe.tcpSocket.withPort

```ts
withPort(port)
```



## obj spec.unsupported.podTemplate.spec.ephemeralContainers.ports



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.ports.withContainerPort

```ts
withContainerPort(containerPort)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.ports.withHostIP

```ts
withHostIP(hostIP)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.ports.withHostPort

```ts
withHostPort(hostPort)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.ports.withName

```ts
withName(name)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.ports.withProtocol

```ts
withProtocol(protocol)
```



## obj spec.unsupported.podTemplate.spec.ephemeralContainers.readinessProbe



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.readinessProbe.withFailureThreshold

```ts
withFailureThreshold(failureThreshold)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.readinessProbe.withInitialDelaySeconds

```ts
withInitialDelaySeconds(initialDelaySeconds)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.readinessProbe.withPeriodSeconds

```ts
withPeriodSeconds(periodSeconds)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.readinessProbe.withSuccessThreshold

```ts
withSuccessThreshold(successThreshold)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.readinessProbe.withTerminationGracePeriodSeconds

```ts
withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.readinessProbe.withTimeoutSeconds

```ts
withTimeoutSeconds(timeoutSeconds)
```



## obj spec.unsupported.podTemplate.spec.ephemeralContainers.readinessProbe.exec



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.readinessProbe.exec.withCommand

```ts
withCommand(command)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.readinessProbe.exec.withCommandMixin

```ts
withCommandMixin(command)
```



**Note:** This function appends passed data to existing values

## obj spec.unsupported.podTemplate.spec.ephemeralContainers.readinessProbe.grpc



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.readinessProbe.grpc.withPort

```ts
withPort(port)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.readinessProbe.grpc.withService

```ts
withService(service)
```



## obj spec.unsupported.podTemplate.spec.ephemeralContainers.readinessProbe.httpGet



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.readinessProbe.httpGet.withHost

```ts
withHost(host)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.readinessProbe.httpGet.withHttpHeaders

```ts
withHttpHeaders(httpHeaders)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.readinessProbe.httpGet.withHttpHeadersMixin

```ts
withHttpHeadersMixin(httpHeaders)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.ephemeralContainers.readinessProbe.httpGet.withPath

```ts
withPath(path)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.readinessProbe.httpGet.withPort

```ts
withPort(port)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.readinessProbe.httpGet.withScheme

```ts
withScheme(scheme)
```



## obj spec.unsupported.podTemplate.spec.ephemeralContainers.readinessProbe.httpGet.httpHeaders



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.readinessProbe.httpGet.httpHeaders.withName

```ts
withName(name)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.readinessProbe.httpGet.httpHeaders.withValue

```ts
withValue(value)
```



## obj spec.unsupported.podTemplate.spec.ephemeralContainers.readinessProbe.tcpSocket



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.readinessProbe.tcpSocket.withHost

```ts
withHost(host)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.readinessProbe.tcpSocket.withPort

```ts
withPort(port)
```



## obj spec.unsupported.podTemplate.spec.ephemeralContainers.resizePolicy



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.resizePolicy.withResourceName

```ts
withResourceName(resourceName)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.resizePolicy.withRestartPolicy

```ts
withRestartPolicy(restartPolicy)
```



## obj spec.unsupported.podTemplate.spec.ephemeralContainers.resources



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.resources.withClaims

```ts
withClaims(claims)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.resources.withClaimsMixin

```ts
withClaimsMixin(claims)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.ephemeralContainers.resources.withLimits

```ts
withLimits(limits)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.resources.withLimitsMixin

```ts
withLimitsMixin(limits)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.ephemeralContainers.resources.withRequests

```ts
withRequests(requests)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.resources.withRequestsMixin

```ts
withRequestsMixin(requests)
```



**Note:** This function appends passed data to existing values

## obj spec.unsupported.podTemplate.spec.ephemeralContainers.resources.claims



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.resources.claims.withName

```ts
withName(name)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.resources.claims.withRequest

```ts
withRequest(request)
```



## obj spec.unsupported.podTemplate.spec.ephemeralContainers.securityContext



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.securityContext.withAllowPrivilegeEscalation

```ts
withAllowPrivilegeEscalation(allowPrivilegeEscalation)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.securityContext.withPrivileged

```ts
withPrivileged(privileged)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.securityContext.withProcMount

```ts
withProcMount(procMount)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.securityContext.withReadOnlyRootFilesystem

```ts
withReadOnlyRootFilesystem(readOnlyRootFilesystem)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.securityContext.withRunAsGroup

```ts
withRunAsGroup(runAsGroup)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.securityContext.withRunAsNonRoot

```ts
withRunAsNonRoot(runAsNonRoot)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.securityContext.withRunAsUser

```ts
withRunAsUser(runAsUser)
```



## obj spec.unsupported.podTemplate.spec.ephemeralContainers.securityContext.appArmorProfile



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.securityContext.appArmorProfile.withLocalhostProfile

```ts
withLocalhostProfile(localhostProfile)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.securityContext.appArmorProfile.withType

```ts
withType(type)
```



## obj spec.unsupported.podTemplate.spec.ephemeralContainers.securityContext.capabilities



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.securityContext.capabilities.withAdd

```ts
withAdd(add)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.securityContext.capabilities.withAddMixin

```ts
withAddMixin(add)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.ephemeralContainers.securityContext.capabilities.withDrop

```ts
withDrop(drop)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.securityContext.capabilities.withDropMixin

```ts
withDropMixin(drop)
```



**Note:** This function appends passed data to existing values

## obj spec.unsupported.podTemplate.spec.ephemeralContainers.securityContext.seLinuxOptions



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.securityContext.seLinuxOptions.withLevel

```ts
withLevel(level)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.securityContext.seLinuxOptions.withRole

```ts
withRole(role)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.securityContext.seLinuxOptions.withType

```ts
withType(type)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.securityContext.seLinuxOptions.withUser

```ts
withUser(user)
```



## obj spec.unsupported.podTemplate.spec.ephemeralContainers.securityContext.seccompProfile



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.securityContext.seccompProfile.withLocalhostProfile

```ts
withLocalhostProfile(localhostProfile)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.securityContext.seccompProfile.withType

```ts
withType(type)
```



## obj spec.unsupported.podTemplate.spec.ephemeralContainers.securityContext.windowsOptions



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.securityContext.windowsOptions.withGmsaCredentialSpec

```ts
withGmsaCredentialSpec(gmsaCredentialSpec)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.securityContext.windowsOptions.withGmsaCredentialSpecName

```ts
withGmsaCredentialSpecName(gmsaCredentialSpecName)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.securityContext.windowsOptions.withHostProcess

```ts
withHostProcess(hostProcess)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.securityContext.windowsOptions.withRunAsUserName

```ts
withRunAsUserName(runAsUserName)
```



## obj spec.unsupported.podTemplate.spec.ephemeralContainers.startupProbe



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.startupProbe.withFailureThreshold

```ts
withFailureThreshold(failureThreshold)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.startupProbe.withInitialDelaySeconds

```ts
withInitialDelaySeconds(initialDelaySeconds)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.startupProbe.withPeriodSeconds

```ts
withPeriodSeconds(periodSeconds)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.startupProbe.withSuccessThreshold

```ts
withSuccessThreshold(successThreshold)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.startupProbe.withTerminationGracePeriodSeconds

```ts
withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.startupProbe.withTimeoutSeconds

```ts
withTimeoutSeconds(timeoutSeconds)
```



## obj spec.unsupported.podTemplate.spec.ephemeralContainers.startupProbe.exec



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.startupProbe.exec.withCommand

```ts
withCommand(command)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.startupProbe.exec.withCommandMixin

```ts
withCommandMixin(command)
```



**Note:** This function appends passed data to existing values

## obj spec.unsupported.podTemplate.spec.ephemeralContainers.startupProbe.grpc



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.startupProbe.grpc.withPort

```ts
withPort(port)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.startupProbe.grpc.withService

```ts
withService(service)
```



## obj spec.unsupported.podTemplate.spec.ephemeralContainers.startupProbe.httpGet



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.startupProbe.httpGet.withHost

```ts
withHost(host)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.startupProbe.httpGet.withHttpHeaders

```ts
withHttpHeaders(httpHeaders)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.startupProbe.httpGet.withHttpHeadersMixin

```ts
withHttpHeadersMixin(httpHeaders)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.ephemeralContainers.startupProbe.httpGet.withPath

```ts
withPath(path)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.startupProbe.httpGet.withPort

```ts
withPort(port)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.startupProbe.httpGet.withScheme

```ts
withScheme(scheme)
```



## obj spec.unsupported.podTemplate.spec.ephemeralContainers.startupProbe.httpGet.httpHeaders



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.startupProbe.httpGet.httpHeaders.withName

```ts
withName(name)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.startupProbe.httpGet.httpHeaders.withValue

```ts
withValue(value)
```



## obj spec.unsupported.podTemplate.spec.ephemeralContainers.startupProbe.tcpSocket



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.startupProbe.tcpSocket.withHost

```ts
withHost(host)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.startupProbe.tcpSocket.withPort

```ts
withPort(port)
```



## obj spec.unsupported.podTemplate.spec.ephemeralContainers.volumeDevices



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.volumeDevices.withDevicePath

```ts
withDevicePath(devicePath)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.volumeDevices.withName

```ts
withName(name)
```



## obj spec.unsupported.podTemplate.spec.ephemeralContainers.volumeMounts



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.volumeMounts.withMountPath

```ts
withMountPath(mountPath)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.volumeMounts.withMountPropagation

```ts
withMountPropagation(mountPropagation)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.volumeMounts.withName

```ts
withName(name)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.volumeMounts.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.volumeMounts.withRecursiveReadOnly

```ts
withRecursiveReadOnly(recursiveReadOnly)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.volumeMounts.withSubPath

```ts
withSubPath(subPath)
```



### fn spec.unsupported.podTemplate.spec.ephemeralContainers.volumeMounts.withSubPathExpr

```ts
withSubPathExpr(subPathExpr)
```



## obj spec.unsupported.podTemplate.spec.hostAliases



### fn spec.unsupported.podTemplate.spec.hostAliases.withHostnames

```ts
withHostnames(hostnames)
```



### fn spec.unsupported.podTemplate.spec.hostAliases.withHostnamesMixin

```ts
withHostnamesMixin(hostnames)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.hostAliases.withIp

```ts
withIp(ip)
```



## obj spec.unsupported.podTemplate.spec.imagePullSecrets



### fn spec.unsupported.podTemplate.spec.imagePullSecrets.withName

```ts
withName(name)
```



## obj spec.unsupported.podTemplate.spec.initContainers



### fn spec.unsupported.podTemplate.spec.initContainers.withArgs

```ts
withArgs(args)
```



### fn spec.unsupported.podTemplate.spec.initContainers.withArgsMixin

```ts
withArgsMixin(args)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.initContainers.withCommand

```ts
withCommand(command)
```



### fn spec.unsupported.podTemplate.spec.initContainers.withCommandMixin

```ts
withCommandMixin(command)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.initContainers.withEnv

```ts
withEnv(env)
```



### fn spec.unsupported.podTemplate.spec.initContainers.withEnvFrom

```ts
withEnvFrom(envFrom)
```



### fn spec.unsupported.podTemplate.spec.initContainers.withEnvFromMixin

```ts
withEnvFromMixin(envFrom)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.initContainers.withEnvMixin

```ts
withEnvMixin(env)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.initContainers.withImage

```ts
withImage(image)
```



### fn spec.unsupported.podTemplate.spec.initContainers.withImagePullPolicy

```ts
withImagePullPolicy(imagePullPolicy)
```



### fn spec.unsupported.podTemplate.spec.initContainers.withName

```ts
withName(name)
```



### fn spec.unsupported.podTemplate.spec.initContainers.withPorts

```ts
withPorts(ports)
```



### fn spec.unsupported.podTemplate.spec.initContainers.withPortsMixin

```ts
withPortsMixin(ports)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.initContainers.withResizePolicy

```ts
withResizePolicy(resizePolicy)
```



### fn spec.unsupported.podTemplate.spec.initContainers.withResizePolicyMixin

```ts
withResizePolicyMixin(resizePolicy)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.initContainers.withRestartPolicy

```ts
withRestartPolicy(restartPolicy)
```



### fn spec.unsupported.podTemplate.spec.initContainers.withStdin

```ts
withStdin(stdin)
```



### fn spec.unsupported.podTemplate.spec.initContainers.withStdinOnce

```ts
withStdinOnce(stdinOnce)
```



### fn spec.unsupported.podTemplate.spec.initContainers.withTerminationMessagePath

```ts
withTerminationMessagePath(terminationMessagePath)
```



### fn spec.unsupported.podTemplate.spec.initContainers.withTerminationMessagePolicy

```ts
withTerminationMessagePolicy(terminationMessagePolicy)
```



### fn spec.unsupported.podTemplate.spec.initContainers.withTty

```ts
withTty(tty)
```



### fn spec.unsupported.podTemplate.spec.initContainers.withVolumeDevices

```ts
withVolumeDevices(volumeDevices)
```



### fn spec.unsupported.podTemplate.spec.initContainers.withVolumeDevicesMixin

```ts
withVolumeDevicesMixin(volumeDevices)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.initContainers.withVolumeMounts

```ts
withVolumeMounts(volumeMounts)
```



### fn spec.unsupported.podTemplate.spec.initContainers.withVolumeMountsMixin

```ts
withVolumeMountsMixin(volumeMounts)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.initContainers.withWorkingDir

```ts
withWorkingDir(workingDir)
```



## obj spec.unsupported.podTemplate.spec.initContainers.env



### fn spec.unsupported.podTemplate.spec.initContainers.env.withName

```ts
withName(name)
```



### fn spec.unsupported.podTemplate.spec.initContainers.env.withValue

```ts
withValue(value)
```



## obj spec.unsupported.podTemplate.spec.initContainers.env.valueFrom



## obj spec.unsupported.podTemplate.spec.initContainers.env.valueFrom.configMapKeyRef



### fn spec.unsupported.podTemplate.spec.initContainers.env.valueFrom.configMapKeyRef.withKey

```ts
withKey(key)
```



### fn spec.unsupported.podTemplate.spec.initContainers.env.valueFrom.configMapKeyRef.withName

```ts
withName(name)
```



### fn spec.unsupported.podTemplate.spec.initContainers.env.valueFrom.configMapKeyRef.withOptional

```ts
withOptional(optional)
```



## obj spec.unsupported.podTemplate.spec.initContainers.env.valueFrom.fieldRef



### fn spec.unsupported.podTemplate.spec.initContainers.env.valueFrom.fieldRef.withApiVersion

```ts
withApiVersion(apiVersion)
```



### fn spec.unsupported.podTemplate.spec.initContainers.env.valueFrom.fieldRef.withFieldPath

```ts
withFieldPath(fieldPath)
```



## obj spec.unsupported.podTemplate.spec.initContainers.env.valueFrom.resourceFieldRef



### fn spec.unsupported.podTemplate.spec.initContainers.env.valueFrom.resourceFieldRef.withContainerName

```ts
withContainerName(containerName)
```



### fn spec.unsupported.podTemplate.spec.initContainers.env.valueFrom.resourceFieldRef.withDivisor

```ts
withDivisor(divisor)
```



### fn spec.unsupported.podTemplate.spec.initContainers.env.valueFrom.resourceFieldRef.withResource

```ts
withResource(resource)
```



## obj spec.unsupported.podTemplate.spec.initContainers.env.valueFrom.secretKeyRef



### fn spec.unsupported.podTemplate.spec.initContainers.env.valueFrom.secretKeyRef.withKey

```ts
withKey(key)
```



### fn spec.unsupported.podTemplate.spec.initContainers.env.valueFrom.secretKeyRef.withName

```ts
withName(name)
```



### fn spec.unsupported.podTemplate.spec.initContainers.env.valueFrom.secretKeyRef.withOptional

```ts
withOptional(optional)
```



## obj spec.unsupported.podTemplate.spec.initContainers.envFrom



### fn spec.unsupported.podTemplate.spec.initContainers.envFrom.withPrefix

```ts
withPrefix(prefix)
```



## obj spec.unsupported.podTemplate.spec.initContainers.envFrom.configMapRef



### fn spec.unsupported.podTemplate.spec.initContainers.envFrom.configMapRef.withName

```ts
withName(name)
```



### fn spec.unsupported.podTemplate.spec.initContainers.envFrom.configMapRef.withOptional

```ts
withOptional(optional)
```



## obj spec.unsupported.podTemplate.spec.initContainers.envFrom.secretRef



### fn spec.unsupported.podTemplate.spec.initContainers.envFrom.secretRef.withName

```ts
withName(name)
```



### fn spec.unsupported.podTemplate.spec.initContainers.envFrom.secretRef.withOptional

```ts
withOptional(optional)
```



## obj spec.unsupported.podTemplate.spec.initContainers.lifecycle



### fn spec.unsupported.podTemplate.spec.initContainers.lifecycle.withStopSignal

```ts
withStopSignal(stopSignal)
```



## obj spec.unsupported.podTemplate.spec.initContainers.lifecycle.postStart



## obj spec.unsupported.podTemplate.spec.initContainers.lifecycle.postStart.exec



### fn spec.unsupported.podTemplate.spec.initContainers.lifecycle.postStart.exec.withCommand

```ts
withCommand(command)
```



### fn spec.unsupported.podTemplate.spec.initContainers.lifecycle.postStart.exec.withCommandMixin

```ts
withCommandMixin(command)
```



**Note:** This function appends passed data to existing values

## obj spec.unsupported.podTemplate.spec.initContainers.lifecycle.postStart.httpGet



### fn spec.unsupported.podTemplate.spec.initContainers.lifecycle.postStart.httpGet.withHost

```ts
withHost(host)
```



### fn spec.unsupported.podTemplate.spec.initContainers.lifecycle.postStart.httpGet.withHttpHeaders

```ts
withHttpHeaders(httpHeaders)
```



### fn spec.unsupported.podTemplate.spec.initContainers.lifecycle.postStart.httpGet.withHttpHeadersMixin

```ts
withHttpHeadersMixin(httpHeaders)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.initContainers.lifecycle.postStart.httpGet.withPath

```ts
withPath(path)
```



### fn spec.unsupported.podTemplate.spec.initContainers.lifecycle.postStart.httpGet.withPort

```ts
withPort(port)
```



### fn spec.unsupported.podTemplate.spec.initContainers.lifecycle.postStart.httpGet.withScheme

```ts
withScheme(scheme)
```



## obj spec.unsupported.podTemplate.spec.initContainers.lifecycle.postStart.httpGet.httpHeaders



### fn spec.unsupported.podTemplate.spec.initContainers.lifecycle.postStart.httpGet.httpHeaders.withName

```ts
withName(name)
```



### fn spec.unsupported.podTemplate.spec.initContainers.lifecycle.postStart.httpGet.httpHeaders.withValue

```ts
withValue(value)
```



## obj spec.unsupported.podTemplate.spec.initContainers.lifecycle.postStart.sleep



### fn spec.unsupported.podTemplate.spec.initContainers.lifecycle.postStart.sleep.withSeconds

```ts
withSeconds(seconds)
```



## obj spec.unsupported.podTemplate.spec.initContainers.lifecycle.postStart.tcpSocket



### fn spec.unsupported.podTemplate.spec.initContainers.lifecycle.postStart.tcpSocket.withHost

```ts
withHost(host)
```



### fn spec.unsupported.podTemplate.spec.initContainers.lifecycle.postStart.tcpSocket.withPort

```ts
withPort(port)
```



## obj spec.unsupported.podTemplate.spec.initContainers.lifecycle.preStop



## obj spec.unsupported.podTemplate.spec.initContainers.lifecycle.preStop.exec



### fn spec.unsupported.podTemplate.spec.initContainers.lifecycle.preStop.exec.withCommand

```ts
withCommand(command)
```



### fn spec.unsupported.podTemplate.spec.initContainers.lifecycle.preStop.exec.withCommandMixin

```ts
withCommandMixin(command)
```



**Note:** This function appends passed data to existing values

## obj spec.unsupported.podTemplate.spec.initContainers.lifecycle.preStop.httpGet



### fn spec.unsupported.podTemplate.spec.initContainers.lifecycle.preStop.httpGet.withHost

```ts
withHost(host)
```



### fn spec.unsupported.podTemplate.spec.initContainers.lifecycle.preStop.httpGet.withHttpHeaders

```ts
withHttpHeaders(httpHeaders)
```



### fn spec.unsupported.podTemplate.spec.initContainers.lifecycle.preStop.httpGet.withHttpHeadersMixin

```ts
withHttpHeadersMixin(httpHeaders)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.initContainers.lifecycle.preStop.httpGet.withPath

```ts
withPath(path)
```



### fn spec.unsupported.podTemplate.spec.initContainers.lifecycle.preStop.httpGet.withPort

```ts
withPort(port)
```



### fn spec.unsupported.podTemplate.spec.initContainers.lifecycle.preStop.httpGet.withScheme

```ts
withScheme(scheme)
```



## obj spec.unsupported.podTemplate.spec.initContainers.lifecycle.preStop.httpGet.httpHeaders



### fn spec.unsupported.podTemplate.spec.initContainers.lifecycle.preStop.httpGet.httpHeaders.withName

```ts
withName(name)
```



### fn spec.unsupported.podTemplate.spec.initContainers.lifecycle.preStop.httpGet.httpHeaders.withValue

```ts
withValue(value)
```



## obj spec.unsupported.podTemplate.spec.initContainers.lifecycle.preStop.sleep



### fn spec.unsupported.podTemplate.spec.initContainers.lifecycle.preStop.sleep.withSeconds

```ts
withSeconds(seconds)
```



## obj spec.unsupported.podTemplate.spec.initContainers.lifecycle.preStop.tcpSocket



### fn spec.unsupported.podTemplate.spec.initContainers.lifecycle.preStop.tcpSocket.withHost

```ts
withHost(host)
```



### fn spec.unsupported.podTemplate.spec.initContainers.lifecycle.preStop.tcpSocket.withPort

```ts
withPort(port)
```



## obj spec.unsupported.podTemplate.spec.initContainers.livenessProbe



### fn spec.unsupported.podTemplate.spec.initContainers.livenessProbe.withFailureThreshold

```ts
withFailureThreshold(failureThreshold)
```



### fn spec.unsupported.podTemplate.spec.initContainers.livenessProbe.withInitialDelaySeconds

```ts
withInitialDelaySeconds(initialDelaySeconds)
```



### fn spec.unsupported.podTemplate.spec.initContainers.livenessProbe.withPeriodSeconds

```ts
withPeriodSeconds(periodSeconds)
```



### fn spec.unsupported.podTemplate.spec.initContainers.livenessProbe.withSuccessThreshold

```ts
withSuccessThreshold(successThreshold)
```



### fn spec.unsupported.podTemplate.spec.initContainers.livenessProbe.withTerminationGracePeriodSeconds

```ts
withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)
```



### fn spec.unsupported.podTemplate.spec.initContainers.livenessProbe.withTimeoutSeconds

```ts
withTimeoutSeconds(timeoutSeconds)
```



## obj spec.unsupported.podTemplate.spec.initContainers.livenessProbe.exec



### fn spec.unsupported.podTemplate.spec.initContainers.livenessProbe.exec.withCommand

```ts
withCommand(command)
```



### fn spec.unsupported.podTemplate.spec.initContainers.livenessProbe.exec.withCommandMixin

```ts
withCommandMixin(command)
```



**Note:** This function appends passed data to existing values

## obj spec.unsupported.podTemplate.spec.initContainers.livenessProbe.grpc



### fn spec.unsupported.podTemplate.spec.initContainers.livenessProbe.grpc.withPort

```ts
withPort(port)
```



### fn spec.unsupported.podTemplate.spec.initContainers.livenessProbe.grpc.withService

```ts
withService(service)
```



## obj spec.unsupported.podTemplate.spec.initContainers.livenessProbe.httpGet



### fn spec.unsupported.podTemplate.spec.initContainers.livenessProbe.httpGet.withHost

```ts
withHost(host)
```



### fn spec.unsupported.podTemplate.spec.initContainers.livenessProbe.httpGet.withHttpHeaders

```ts
withHttpHeaders(httpHeaders)
```



### fn spec.unsupported.podTemplate.spec.initContainers.livenessProbe.httpGet.withHttpHeadersMixin

```ts
withHttpHeadersMixin(httpHeaders)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.initContainers.livenessProbe.httpGet.withPath

```ts
withPath(path)
```



### fn spec.unsupported.podTemplate.spec.initContainers.livenessProbe.httpGet.withPort

```ts
withPort(port)
```



### fn spec.unsupported.podTemplate.spec.initContainers.livenessProbe.httpGet.withScheme

```ts
withScheme(scheme)
```



## obj spec.unsupported.podTemplate.spec.initContainers.livenessProbe.httpGet.httpHeaders



### fn spec.unsupported.podTemplate.spec.initContainers.livenessProbe.httpGet.httpHeaders.withName

```ts
withName(name)
```



### fn spec.unsupported.podTemplate.spec.initContainers.livenessProbe.httpGet.httpHeaders.withValue

```ts
withValue(value)
```



## obj spec.unsupported.podTemplate.spec.initContainers.livenessProbe.tcpSocket



### fn spec.unsupported.podTemplate.spec.initContainers.livenessProbe.tcpSocket.withHost

```ts
withHost(host)
```



### fn spec.unsupported.podTemplate.spec.initContainers.livenessProbe.tcpSocket.withPort

```ts
withPort(port)
```



## obj spec.unsupported.podTemplate.spec.initContainers.ports



### fn spec.unsupported.podTemplate.spec.initContainers.ports.withContainerPort

```ts
withContainerPort(containerPort)
```



### fn spec.unsupported.podTemplate.spec.initContainers.ports.withHostIP

```ts
withHostIP(hostIP)
```



### fn spec.unsupported.podTemplate.spec.initContainers.ports.withHostPort

```ts
withHostPort(hostPort)
```



### fn spec.unsupported.podTemplate.spec.initContainers.ports.withName

```ts
withName(name)
```



### fn spec.unsupported.podTemplate.spec.initContainers.ports.withProtocol

```ts
withProtocol(protocol)
```



## obj spec.unsupported.podTemplate.spec.initContainers.readinessProbe



### fn spec.unsupported.podTemplate.spec.initContainers.readinessProbe.withFailureThreshold

```ts
withFailureThreshold(failureThreshold)
```



### fn spec.unsupported.podTemplate.spec.initContainers.readinessProbe.withInitialDelaySeconds

```ts
withInitialDelaySeconds(initialDelaySeconds)
```



### fn spec.unsupported.podTemplate.spec.initContainers.readinessProbe.withPeriodSeconds

```ts
withPeriodSeconds(periodSeconds)
```



### fn spec.unsupported.podTemplate.spec.initContainers.readinessProbe.withSuccessThreshold

```ts
withSuccessThreshold(successThreshold)
```



### fn spec.unsupported.podTemplate.spec.initContainers.readinessProbe.withTerminationGracePeriodSeconds

```ts
withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)
```



### fn spec.unsupported.podTemplate.spec.initContainers.readinessProbe.withTimeoutSeconds

```ts
withTimeoutSeconds(timeoutSeconds)
```



## obj spec.unsupported.podTemplate.spec.initContainers.readinessProbe.exec



### fn spec.unsupported.podTemplate.spec.initContainers.readinessProbe.exec.withCommand

```ts
withCommand(command)
```



### fn spec.unsupported.podTemplate.spec.initContainers.readinessProbe.exec.withCommandMixin

```ts
withCommandMixin(command)
```



**Note:** This function appends passed data to existing values

## obj spec.unsupported.podTemplate.spec.initContainers.readinessProbe.grpc



### fn spec.unsupported.podTemplate.spec.initContainers.readinessProbe.grpc.withPort

```ts
withPort(port)
```



### fn spec.unsupported.podTemplate.spec.initContainers.readinessProbe.grpc.withService

```ts
withService(service)
```



## obj spec.unsupported.podTemplate.spec.initContainers.readinessProbe.httpGet



### fn spec.unsupported.podTemplate.spec.initContainers.readinessProbe.httpGet.withHost

```ts
withHost(host)
```



### fn spec.unsupported.podTemplate.spec.initContainers.readinessProbe.httpGet.withHttpHeaders

```ts
withHttpHeaders(httpHeaders)
```



### fn spec.unsupported.podTemplate.spec.initContainers.readinessProbe.httpGet.withHttpHeadersMixin

```ts
withHttpHeadersMixin(httpHeaders)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.initContainers.readinessProbe.httpGet.withPath

```ts
withPath(path)
```



### fn spec.unsupported.podTemplate.spec.initContainers.readinessProbe.httpGet.withPort

```ts
withPort(port)
```



### fn spec.unsupported.podTemplate.spec.initContainers.readinessProbe.httpGet.withScheme

```ts
withScheme(scheme)
```



## obj spec.unsupported.podTemplate.spec.initContainers.readinessProbe.httpGet.httpHeaders



### fn spec.unsupported.podTemplate.spec.initContainers.readinessProbe.httpGet.httpHeaders.withName

```ts
withName(name)
```



### fn spec.unsupported.podTemplate.spec.initContainers.readinessProbe.httpGet.httpHeaders.withValue

```ts
withValue(value)
```



## obj spec.unsupported.podTemplate.spec.initContainers.readinessProbe.tcpSocket



### fn spec.unsupported.podTemplate.spec.initContainers.readinessProbe.tcpSocket.withHost

```ts
withHost(host)
```



### fn spec.unsupported.podTemplate.spec.initContainers.readinessProbe.tcpSocket.withPort

```ts
withPort(port)
```



## obj spec.unsupported.podTemplate.spec.initContainers.resizePolicy



### fn spec.unsupported.podTemplate.spec.initContainers.resizePolicy.withResourceName

```ts
withResourceName(resourceName)
```



### fn spec.unsupported.podTemplate.spec.initContainers.resizePolicy.withRestartPolicy

```ts
withRestartPolicy(restartPolicy)
```



## obj spec.unsupported.podTemplate.spec.initContainers.resources



### fn spec.unsupported.podTemplate.spec.initContainers.resources.withClaims

```ts
withClaims(claims)
```



### fn spec.unsupported.podTemplate.spec.initContainers.resources.withClaimsMixin

```ts
withClaimsMixin(claims)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.initContainers.resources.withLimits

```ts
withLimits(limits)
```



### fn spec.unsupported.podTemplate.spec.initContainers.resources.withLimitsMixin

```ts
withLimitsMixin(limits)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.initContainers.resources.withRequests

```ts
withRequests(requests)
```



### fn spec.unsupported.podTemplate.spec.initContainers.resources.withRequestsMixin

```ts
withRequestsMixin(requests)
```



**Note:** This function appends passed data to existing values

## obj spec.unsupported.podTemplate.spec.initContainers.resources.claims



### fn spec.unsupported.podTemplate.spec.initContainers.resources.claims.withName

```ts
withName(name)
```



### fn spec.unsupported.podTemplate.spec.initContainers.resources.claims.withRequest

```ts
withRequest(request)
```



## obj spec.unsupported.podTemplate.spec.initContainers.securityContext



### fn spec.unsupported.podTemplate.spec.initContainers.securityContext.withAllowPrivilegeEscalation

```ts
withAllowPrivilegeEscalation(allowPrivilegeEscalation)
```



### fn spec.unsupported.podTemplate.spec.initContainers.securityContext.withPrivileged

```ts
withPrivileged(privileged)
```



### fn spec.unsupported.podTemplate.spec.initContainers.securityContext.withProcMount

```ts
withProcMount(procMount)
```



### fn spec.unsupported.podTemplate.spec.initContainers.securityContext.withReadOnlyRootFilesystem

```ts
withReadOnlyRootFilesystem(readOnlyRootFilesystem)
```



### fn spec.unsupported.podTemplate.spec.initContainers.securityContext.withRunAsGroup

```ts
withRunAsGroup(runAsGroup)
```



### fn spec.unsupported.podTemplate.spec.initContainers.securityContext.withRunAsNonRoot

```ts
withRunAsNonRoot(runAsNonRoot)
```



### fn spec.unsupported.podTemplate.spec.initContainers.securityContext.withRunAsUser

```ts
withRunAsUser(runAsUser)
```



## obj spec.unsupported.podTemplate.spec.initContainers.securityContext.appArmorProfile



### fn spec.unsupported.podTemplate.spec.initContainers.securityContext.appArmorProfile.withLocalhostProfile

```ts
withLocalhostProfile(localhostProfile)
```



### fn spec.unsupported.podTemplate.spec.initContainers.securityContext.appArmorProfile.withType

```ts
withType(type)
```



## obj spec.unsupported.podTemplate.spec.initContainers.securityContext.capabilities



### fn spec.unsupported.podTemplate.spec.initContainers.securityContext.capabilities.withAdd

```ts
withAdd(add)
```



### fn spec.unsupported.podTemplate.spec.initContainers.securityContext.capabilities.withAddMixin

```ts
withAddMixin(add)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.initContainers.securityContext.capabilities.withDrop

```ts
withDrop(drop)
```



### fn spec.unsupported.podTemplate.spec.initContainers.securityContext.capabilities.withDropMixin

```ts
withDropMixin(drop)
```



**Note:** This function appends passed data to existing values

## obj spec.unsupported.podTemplate.spec.initContainers.securityContext.seLinuxOptions



### fn spec.unsupported.podTemplate.spec.initContainers.securityContext.seLinuxOptions.withLevel

```ts
withLevel(level)
```



### fn spec.unsupported.podTemplate.spec.initContainers.securityContext.seLinuxOptions.withRole

```ts
withRole(role)
```



### fn spec.unsupported.podTemplate.spec.initContainers.securityContext.seLinuxOptions.withType

```ts
withType(type)
```



### fn spec.unsupported.podTemplate.spec.initContainers.securityContext.seLinuxOptions.withUser

```ts
withUser(user)
```



## obj spec.unsupported.podTemplate.spec.initContainers.securityContext.seccompProfile



### fn spec.unsupported.podTemplate.spec.initContainers.securityContext.seccompProfile.withLocalhostProfile

```ts
withLocalhostProfile(localhostProfile)
```



### fn spec.unsupported.podTemplate.spec.initContainers.securityContext.seccompProfile.withType

```ts
withType(type)
```



## obj spec.unsupported.podTemplate.spec.initContainers.securityContext.windowsOptions



### fn spec.unsupported.podTemplate.spec.initContainers.securityContext.windowsOptions.withGmsaCredentialSpec

```ts
withGmsaCredentialSpec(gmsaCredentialSpec)
```



### fn spec.unsupported.podTemplate.spec.initContainers.securityContext.windowsOptions.withGmsaCredentialSpecName

```ts
withGmsaCredentialSpecName(gmsaCredentialSpecName)
```



### fn spec.unsupported.podTemplate.spec.initContainers.securityContext.windowsOptions.withHostProcess

```ts
withHostProcess(hostProcess)
```



### fn spec.unsupported.podTemplate.spec.initContainers.securityContext.windowsOptions.withRunAsUserName

```ts
withRunAsUserName(runAsUserName)
```



## obj spec.unsupported.podTemplate.spec.initContainers.startupProbe



### fn spec.unsupported.podTemplate.spec.initContainers.startupProbe.withFailureThreshold

```ts
withFailureThreshold(failureThreshold)
```



### fn spec.unsupported.podTemplate.spec.initContainers.startupProbe.withInitialDelaySeconds

```ts
withInitialDelaySeconds(initialDelaySeconds)
```



### fn spec.unsupported.podTemplate.spec.initContainers.startupProbe.withPeriodSeconds

```ts
withPeriodSeconds(periodSeconds)
```



### fn spec.unsupported.podTemplate.spec.initContainers.startupProbe.withSuccessThreshold

```ts
withSuccessThreshold(successThreshold)
```



### fn spec.unsupported.podTemplate.spec.initContainers.startupProbe.withTerminationGracePeriodSeconds

```ts
withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)
```



### fn spec.unsupported.podTemplate.spec.initContainers.startupProbe.withTimeoutSeconds

```ts
withTimeoutSeconds(timeoutSeconds)
```



## obj spec.unsupported.podTemplate.spec.initContainers.startupProbe.exec



### fn spec.unsupported.podTemplate.spec.initContainers.startupProbe.exec.withCommand

```ts
withCommand(command)
```



### fn spec.unsupported.podTemplate.spec.initContainers.startupProbe.exec.withCommandMixin

```ts
withCommandMixin(command)
```



**Note:** This function appends passed data to existing values

## obj spec.unsupported.podTemplate.spec.initContainers.startupProbe.grpc



### fn spec.unsupported.podTemplate.spec.initContainers.startupProbe.grpc.withPort

```ts
withPort(port)
```



### fn spec.unsupported.podTemplate.spec.initContainers.startupProbe.grpc.withService

```ts
withService(service)
```



## obj spec.unsupported.podTemplate.spec.initContainers.startupProbe.httpGet



### fn spec.unsupported.podTemplate.spec.initContainers.startupProbe.httpGet.withHost

```ts
withHost(host)
```



### fn spec.unsupported.podTemplate.spec.initContainers.startupProbe.httpGet.withHttpHeaders

```ts
withHttpHeaders(httpHeaders)
```



### fn spec.unsupported.podTemplate.spec.initContainers.startupProbe.httpGet.withHttpHeadersMixin

```ts
withHttpHeadersMixin(httpHeaders)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.initContainers.startupProbe.httpGet.withPath

```ts
withPath(path)
```



### fn spec.unsupported.podTemplate.spec.initContainers.startupProbe.httpGet.withPort

```ts
withPort(port)
```



### fn spec.unsupported.podTemplate.spec.initContainers.startupProbe.httpGet.withScheme

```ts
withScheme(scheme)
```



## obj spec.unsupported.podTemplate.spec.initContainers.startupProbe.httpGet.httpHeaders



### fn spec.unsupported.podTemplate.spec.initContainers.startupProbe.httpGet.httpHeaders.withName

```ts
withName(name)
```



### fn spec.unsupported.podTemplate.spec.initContainers.startupProbe.httpGet.httpHeaders.withValue

```ts
withValue(value)
```



## obj spec.unsupported.podTemplate.spec.initContainers.startupProbe.tcpSocket



### fn spec.unsupported.podTemplate.spec.initContainers.startupProbe.tcpSocket.withHost

```ts
withHost(host)
```



### fn spec.unsupported.podTemplate.spec.initContainers.startupProbe.tcpSocket.withPort

```ts
withPort(port)
```



## obj spec.unsupported.podTemplate.spec.initContainers.volumeDevices



### fn spec.unsupported.podTemplate.spec.initContainers.volumeDevices.withDevicePath

```ts
withDevicePath(devicePath)
```



### fn spec.unsupported.podTemplate.spec.initContainers.volumeDevices.withName

```ts
withName(name)
```



## obj spec.unsupported.podTemplate.spec.initContainers.volumeMounts



### fn spec.unsupported.podTemplate.spec.initContainers.volumeMounts.withMountPath

```ts
withMountPath(mountPath)
```



### fn spec.unsupported.podTemplate.spec.initContainers.volumeMounts.withMountPropagation

```ts
withMountPropagation(mountPropagation)
```



### fn spec.unsupported.podTemplate.spec.initContainers.volumeMounts.withName

```ts
withName(name)
```



### fn spec.unsupported.podTemplate.spec.initContainers.volumeMounts.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.unsupported.podTemplate.spec.initContainers.volumeMounts.withRecursiveReadOnly

```ts
withRecursiveReadOnly(recursiveReadOnly)
```



### fn spec.unsupported.podTemplate.spec.initContainers.volumeMounts.withSubPath

```ts
withSubPath(subPath)
```



### fn spec.unsupported.podTemplate.spec.initContainers.volumeMounts.withSubPathExpr

```ts
withSubPathExpr(subPathExpr)
```



## obj spec.unsupported.podTemplate.spec.os



### fn spec.unsupported.podTemplate.spec.os.withName

```ts
withName(name)
```



## obj spec.unsupported.podTemplate.spec.readinessGates



### fn spec.unsupported.podTemplate.spec.readinessGates.withConditionType

```ts
withConditionType(conditionType)
```



## obj spec.unsupported.podTemplate.spec.resourceClaims



### fn spec.unsupported.podTemplate.spec.resourceClaims.withName

```ts
withName(name)
```



### fn spec.unsupported.podTemplate.spec.resourceClaims.withResourceClaimName

```ts
withResourceClaimName(resourceClaimName)
```



### fn spec.unsupported.podTemplate.spec.resourceClaims.withResourceClaimTemplateName

```ts
withResourceClaimTemplateName(resourceClaimTemplateName)
```



## obj spec.unsupported.podTemplate.spec.resources



### fn spec.unsupported.podTemplate.spec.resources.withClaims

```ts
withClaims(claims)
```



### fn spec.unsupported.podTemplate.spec.resources.withClaimsMixin

```ts
withClaimsMixin(claims)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.resources.withLimits

```ts
withLimits(limits)
```



### fn spec.unsupported.podTemplate.spec.resources.withLimitsMixin

```ts
withLimitsMixin(limits)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.resources.withRequests

```ts
withRequests(requests)
```



### fn spec.unsupported.podTemplate.spec.resources.withRequestsMixin

```ts
withRequestsMixin(requests)
```



**Note:** This function appends passed data to existing values

## obj spec.unsupported.podTemplate.spec.resources.claims



### fn spec.unsupported.podTemplate.spec.resources.claims.withName

```ts
withName(name)
```



### fn spec.unsupported.podTemplate.spec.resources.claims.withRequest

```ts
withRequest(request)
```



## obj spec.unsupported.podTemplate.spec.schedulingGates



### fn spec.unsupported.podTemplate.spec.schedulingGates.withName

```ts
withName(name)
```



## obj spec.unsupported.podTemplate.spec.securityContext



### fn spec.unsupported.podTemplate.spec.securityContext.withFsGroup

```ts
withFsGroup(fsGroup)
```



### fn spec.unsupported.podTemplate.spec.securityContext.withFsGroupChangePolicy

```ts
withFsGroupChangePolicy(fsGroupChangePolicy)
```



### fn spec.unsupported.podTemplate.spec.securityContext.withRunAsGroup

```ts
withRunAsGroup(runAsGroup)
```



### fn spec.unsupported.podTemplate.spec.securityContext.withRunAsNonRoot

```ts
withRunAsNonRoot(runAsNonRoot)
```



### fn spec.unsupported.podTemplate.spec.securityContext.withRunAsUser

```ts
withRunAsUser(runAsUser)
```



### fn spec.unsupported.podTemplate.spec.securityContext.withSeLinuxChangePolicy

```ts
withSeLinuxChangePolicy(seLinuxChangePolicy)
```



### fn spec.unsupported.podTemplate.spec.securityContext.withSupplementalGroups

```ts
withSupplementalGroups(supplementalGroups)
```



### fn spec.unsupported.podTemplate.spec.securityContext.withSupplementalGroupsMixin

```ts
withSupplementalGroupsMixin(supplementalGroups)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.securityContext.withSupplementalGroupsPolicy

```ts
withSupplementalGroupsPolicy(supplementalGroupsPolicy)
```



### fn spec.unsupported.podTemplate.spec.securityContext.withSysctls

```ts
withSysctls(sysctls)
```



### fn spec.unsupported.podTemplate.spec.securityContext.withSysctlsMixin

```ts
withSysctlsMixin(sysctls)
```



**Note:** This function appends passed data to existing values

## obj spec.unsupported.podTemplate.spec.securityContext.appArmorProfile



### fn spec.unsupported.podTemplate.spec.securityContext.appArmorProfile.withLocalhostProfile

```ts
withLocalhostProfile(localhostProfile)
```



### fn spec.unsupported.podTemplate.spec.securityContext.appArmorProfile.withType

```ts
withType(type)
```



## obj spec.unsupported.podTemplate.spec.securityContext.seLinuxOptions



### fn spec.unsupported.podTemplate.spec.securityContext.seLinuxOptions.withLevel

```ts
withLevel(level)
```



### fn spec.unsupported.podTemplate.spec.securityContext.seLinuxOptions.withRole

```ts
withRole(role)
```



### fn spec.unsupported.podTemplate.spec.securityContext.seLinuxOptions.withType

```ts
withType(type)
```



### fn spec.unsupported.podTemplate.spec.securityContext.seLinuxOptions.withUser

```ts
withUser(user)
```



## obj spec.unsupported.podTemplate.spec.securityContext.seccompProfile



### fn spec.unsupported.podTemplate.spec.securityContext.seccompProfile.withLocalhostProfile

```ts
withLocalhostProfile(localhostProfile)
```



### fn spec.unsupported.podTemplate.spec.securityContext.seccompProfile.withType

```ts
withType(type)
```



## obj spec.unsupported.podTemplate.spec.securityContext.sysctls



### fn spec.unsupported.podTemplate.spec.securityContext.sysctls.withName

```ts
withName(name)
```



### fn spec.unsupported.podTemplate.spec.securityContext.sysctls.withValue

```ts
withValue(value)
```



## obj spec.unsupported.podTemplate.spec.securityContext.windowsOptions



### fn spec.unsupported.podTemplate.spec.securityContext.windowsOptions.withGmsaCredentialSpec

```ts
withGmsaCredentialSpec(gmsaCredentialSpec)
```



### fn spec.unsupported.podTemplate.spec.securityContext.windowsOptions.withGmsaCredentialSpecName

```ts
withGmsaCredentialSpecName(gmsaCredentialSpecName)
```



### fn spec.unsupported.podTemplate.spec.securityContext.windowsOptions.withHostProcess

```ts
withHostProcess(hostProcess)
```



### fn spec.unsupported.podTemplate.spec.securityContext.windowsOptions.withRunAsUserName

```ts
withRunAsUserName(runAsUserName)
```



## obj spec.unsupported.podTemplate.spec.tolerations



### fn spec.unsupported.podTemplate.spec.tolerations.withEffect

```ts
withEffect(effect)
```



### fn spec.unsupported.podTemplate.spec.tolerations.withKey

```ts
withKey(key)
```



### fn spec.unsupported.podTemplate.spec.tolerations.withOperator

```ts
withOperator(operator)
```



### fn spec.unsupported.podTemplate.spec.tolerations.withTolerationSeconds

```ts
withTolerationSeconds(tolerationSeconds)
```



### fn spec.unsupported.podTemplate.spec.tolerations.withValue

```ts
withValue(value)
```



## obj spec.unsupported.podTemplate.spec.topologySpreadConstraints



### fn spec.unsupported.podTemplate.spec.topologySpreadConstraints.withMatchLabelKeys

```ts
withMatchLabelKeys(matchLabelKeys)
```



### fn spec.unsupported.podTemplate.spec.topologySpreadConstraints.withMatchLabelKeysMixin

```ts
withMatchLabelKeysMixin(matchLabelKeys)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.topologySpreadConstraints.withMaxSkew

```ts
withMaxSkew(maxSkew)
```



### fn spec.unsupported.podTemplate.spec.topologySpreadConstraints.withMinDomains

```ts
withMinDomains(minDomains)
```



### fn spec.unsupported.podTemplate.spec.topologySpreadConstraints.withNodeAffinityPolicy

```ts
withNodeAffinityPolicy(nodeAffinityPolicy)
```



### fn spec.unsupported.podTemplate.spec.topologySpreadConstraints.withNodeTaintsPolicy

```ts
withNodeTaintsPolicy(nodeTaintsPolicy)
```



### fn spec.unsupported.podTemplate.spec.topologySpreadConstraints.withTopologyKey

```ts
withTopologyKey(topologyKey)
```



### fn spec.unsupported.podTemplate.spec.topologySpreadConstraints.withWhenUnsatisfiable

```ts
withWhenUnsatisfiable(whenUnsatisfiable)
```



## obj spec.unsupported.podTemplate.spec.topologySpreadConstraints.labelSelector



### fn spec.unsupported.podTemplate.spec.topologySpreadConstraints.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.unsupported.podTemplate.spec.topologySpreadConstraints.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.topologySpreadConstraints.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.unsupported.podTemplate.spec.topologySpreadConstraints.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.unsupported.podTemplate.spec.topologySpreadConstraints.labelSelector.matchExpressions



### fn spec.unsupported.podTemplate.spec.topologySpreadConstraints.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.unsupported.podTemplate.spec.topologySpreadConstraints.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.unsupported.podTemplate.spec.topologySpreadConstraints.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.unsupported.podTemplate.spec.topologySpreadConstraints.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.unsupported.podTemplate.spec.volumes



### fn spec.unsupported.podTemplate.spec.volumes.withName

```ts
withName(name)
```



## obj spec.unsupported.podTemplate.spec.volumes.awsElasticBlockStore



### fn spec.unsupported.podTemplate.spec.volumes.awsElasticBlockStore.withFsType

```ts
withFsType(fsType)
```



### fn spec.unsupported.podTemplate.spec.volumes.awsElasticBlockStore.withPartition

```ts
withPartition(partition)
```



### fn spec.unsupported.podTemplate.spec.volumes.awsElasticBlockStore.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.unsupported.podTemplate.spec.volumes.awsElasticBlockStore.withVolumeID

```ts
withVolumeID(volumeID)
```



## obj spec.unsupported.podTemplate.spec.volumes.azureDisk



### fn spec.unsupported.podTemplate.spec.volumes.azureDisk.withCachingMode

```ts
withCachingMode(cachingMode)
```



### fn spec.unsupported.podTemplate.spec.volumes.azureDisk.withDiskName

```ts
withDiskName(diskName)
```



### fn spec.unsupported.podTemplate.spec.volumes.azureDisk.withDiskURI

```ts
withDiskURI(diskURI)
```



### fn spec.unsupported.podTemplate.spec.volumes.azureDisk.withFsType

```ts
withFsType(fsType)
```



### fn spec.unsupported.podTemplate.spec.volumes.azureDisk.withKind

```ts
withKind(kind)
```



### fn spec.unsupported.podTemplate.spec.volumes.azureDisk.withReadOnly

```ts
withReadOnly(readOnly)
```



## obj spec.unsupported.podTemplate.spec.volumes.azureFile



### fn spec.unsupported.podTemplate.spec.volumes.azureFile.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.unsupported.podTemplate.spec.volumes.azureFile.withSecretName

```ts
withSecretName(secretName)
```



### fn spec.unsupported.podTemplate.spec.volumes.azureFile.withShareName

```ts
withShareName(shareName)
```



## obj spec.unsupported.podTemplate.spec.volumes.cephfs



### fn spec.unsupported.podTemplate.spec.volumes.cephfs.withMonitors

```ts
withMonitors(monitors)
```



### fn spec.unsupported.podTemplate.spec.volumes.cephfs.withMonitorsMixin

```ts
withMonitorsMixin(monitors)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.volumes.cephfs.withPath

```ts
withPath(path)
```



### fn spec.unsupported.podTemplate.spec.volumes.cephfs.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.unsupported.podTemplate.spec.volumes.cephfs.withSecretFile

```ts
withSecretFile(secretFile)
```



### fn spec.unsupported.podTemplate.spec.volumes.cephfs.withUser

```ts
withUser(user)
```



## obj spec.unsupported.podTemplate.spec.volumes.cephfs.secretRef



### fn spec.unsupported.podTemplate.spec.volumes.cephfs.secretRef.withName

```ts
withName(name)
```



## obj spec.unsupported.podTemplate.spec.volumes.cinder



### fn spec.unsupported.podTemplate.spec.volumes.cinder.withFsType

```ts
withFsType(fsType)
```



### fn spec.unsupported.podTemplate.spec.volumes.cinder.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.unsupported.podTemplate.spec.volumes.cinder.withVolumeID

```ts
withVolumeID(volumeID)
```



## obj spec.unsupported.podTemplate.spec.volumes.cinder.secretRef



### fn spec.unsupported.podTemplate.spec.volumes.cinder.secretRef.withName

```ts
withName(name)
```



## obj spec.unsupported.podTemplate.spec.volumes.configMap



### fn spec.unsupported.podTemplate.spec.volumes.configMap.withDefaultMode

```ts
withDefaultMode(defaultMode)
```



### fn spec.unsupported.podTemplate.spec.volumes.configMap.withItems

```ts
withItems(items)
```



### fn spec.unsupported.podTemplate.spec.volumes.configMap.withItemsMixin

```ts
withItemsMixin(items)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.volumes.configMap.withName

```ts
withName(name)
```



### fn spec.unsupported.podTemplate.spec.volumes.configMap.withOptional

```ts
withOptional(optional)
```



## obj spec.unsupported.podTemplate.spec.volumes.configMap.items



### fn spec.unsupported.podTemplate.spec.volumes.configMap.items.withKey

```ts
withKey(key)
```



### fn spec.unsupported.podTemplate.spec.volumes.configMap.items.withMode

```ts
withMode(mode)
```



### fn spec.unsupported.podTemplate.spec.volumes.configMap.items.withPath

```ts
withPath(path)
```



## obj spec.unsupported.podTemplate.spec.volumes.csi



### fn spec.unsupported.podTemplate.spec.volumes.csi.withDriver

```ts
withDriver(driver)
```



### fn spec.unsupported.podTemplate.spec.volumes.csi.withFsType

```ts
withFsType(fsType)
```



### fn spec.unsupported.podTemplate.spec.volumes.csi.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.unsupported.podTemplate.spec.volumes.csi.withVolumeAttributes

```ts
withVolumeAttributes(volumeAttributes)
```



### fn spec.unsupported.podTemplate.spec.volumes.csi.withVolumeAttributesMixin

```ts
withVolumeAttributesMixin(volumeAttributes)
```



**Note:** This function appends passed data to existing values

## obj spec.unsupported.podTemplate.spec.volumes.csi.nodePublishSecretRef



### fn spec.unsupported.podTemplate.spec.volumes.csi.nodePublishSecretRef.withName

```ts
withName(name)
```



## obj spec.unsupported.podTemplate.spec.volumes.downwardAPI



### fn spec.unsupported.podTemplate.spec.volumes.downwardAPI.withDefaultMode

```ts
withDefaultMode(defaultMode)
```



### fn spec.unsupported.podTemplate.spec.volumes.downwardAPI.withItems

```ts
withItems(items)
```



### fn spec.unsupported.podTemplate.spec.volumes.downwardAPI.withItemsMixin

```ts
withItemsMixin(items)
```



**Note:** This function appends passed data to existing values

## obj spec.unsupported.podTemplate.spec.volumes.downwardAPI.items



### fn spec.unsupported.podTemplate.spec.volumes.downwardAPI.items.withMode

```ts
withMode(mode)
```



### fn spec.unsupported.podTemplate.spec.volumes.downwardAPI.items.withPath

```ts
withPath(path)
```



## obj spec.unsupported.podTemplate.spec.volumes.downwardAPI.items.fieldRef



### fn spec.unsupported.podTemplate.spec.volumes.downwardAPI.items.fieldRef.withApiVersion

```ts
withApiVersion(apiVersion)
```



### fn spec.unsupported.podTemplate.spec.volumes.downwardAPI.items.fieldRef.withFieldPath

```ts
withFieldPath(fieldPath)
```



## obj spec.unsupported.podTemplate.spec.volumes.downwardAPI.items.resourceFieldRef



### fn spec.unsupported.podTemplate.spec.volumes.downwardAPI.items.resourceFieldRef.withContainerName

```ts
withContainerName(containerName)
```



### fn spec.unsupported.podTemplate.spec.volumes.downwardAPI.items.resourceFieldRef.withDivisor

```ts
withDivisor(divisor)
```



### fn spec.unsupported.podTemplate.spec.volumes.downwardAPI.items.resourceFieldRef.withResource

```ts
withResource(resource)
```



## obj spec.unsupported.podTemplate.spec.volumes.emptyDir



### fn spec.unsupported.podTemplate.spec.volumes.emptyDir.withMedium

```ts
withMedium(medium)
```



### fn spec.unsupported.podTemplate.spec.volumes.emptyDir.withSizeLimit

```ts
withSizeLimit(sizeLimit)
```



## obj spec.unsupported.podTemplate.spec.volumes.ephemeral



## obj spec.unsupported.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate



## obj spec.unsupported.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.metadata



### fn spec.unsupported.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.metadata.withAnnotations

```ts
withAnnotations(annotations)
```



### fn spec.unsupported.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.metadata.withAnnotationsMixin

```ts
withAnnotationsMixin(annotations)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.metadata.withCreationTimestamp

```ts
withCreationTimestamp(creationTimestamp)
```



### fn spec.unsupported.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.metadata.withDeletionGracePeriodSeconds

```ts
withDeletionGracePeriodSeconds(deletionGracePeriodSeconds)
```



### fn spec.unsupported.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.metadata.withDeletionTimestamp

```ts
withDeletionTimestamp(deletionTimestamp)
```



### fn spec.unsupported.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.metadata.withFinalizers

```ts
withFinalizers(finalizers)
```



### fn spec.unsupported.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.metadata.withFinalizersMixin

```ts
withFinalizersMixin(finalizers)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.metadata.withGenerateName

```ts
withGenerateName(generateName)
```



### fn spec.unsupported.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.metadata.withGeneration

```ts
withGeneration(generation)
```



### fn spec.unsupported.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.metadata.withLabels

```ts
withLabels(labels)
```



### fn spec.unsupported.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.metadata.withLabelsMixin

```ts
withLabelsMixin(labels)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.metadata.withManagedFields

```ts
withManagedFields(managedFields)
```



### fn spec.unsupported.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.metadata.withManagedFieldsMixin

```ts
withManagedFieldsMixin(managedFields)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.metadata.withName

```ts
withName(name)
```



### fn spec.unsupported.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.metadata.withNamespace

```ts
withNamespace(namespace)
```



### fn spec.unsupported.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.metadata.withOwnerReferences

```ts
withOwnerReferences(ownerReferences)
```



### fn spec.unsupported.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.metadata.withOwnerReferencesMixin

```ts
withOwnerReferencesMixin(ownerReferences)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.metadata.withResourceVersion

```ts
withResourceVersion(resourceVersion)
```



### fn spec.unsupported.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.metadata.withSelfLink

```ts
withSelfLink(selfLink)
```



### fn spec.unsupported.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.metadata.withUid

```ts
withUid(uid)
```



## obj spec.unsupported.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.metadata.managedFields



### fn spec.unsupported.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.metadata.managedFields.withApiVersion

```ts
withApiVersion(apiVersion)
```



### fn spec.unsupported.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.metadata.managedFields.withFieldsType

```ts
withFieldsType(fieldsType)
```



### fn spec.unsupported.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.metadata.managedFields.withFieldsV1

```ts
withFieldsV1(fieldsV1)
```



### fn spec.unsupported.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.metadata.managedFields.withFieldsV1Mixin

```ts
withFieldsV1Mixin(fieldsV1)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.metadata.managedFields.withManager

```ts
withManager(manager)
```



### fn spec.unsupported.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.metadata.managedFields.withOperation

```ts
withOperation(operation)
```



### fn spec.unsupported.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.metadata.managedFields.withSubresource

```ts
withSubresource(subresource)
```



### fn spec.unsupported.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.metadata.managedFields.withTime

```ts
withTime(time)
```



## obj spec.unsupported.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.metadata.ownerReferences



### fn spec.unsupported.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.metadata.ownerReferences.withApiVersion

```ts
withApiVersion(apiVersion)
```



### fn spec.unsupported.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.metadata.ownerReferences.withBlockOwnerDeletion

```ts
withBlockOwnerDeletion(blockOwnerDeletion)
```



### fn spec.unsupported.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.metadata.ownerReferences.withController

```ts
withController(controller)
```



### fn spec.unsupported.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.metadata.ownerReferences.withKind

```ts
withKind(kind)
```



### fn spec.unsupported.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.metadata.ownerReferences.withName

```ts
withName(name)
```



### fn spec.unsupported.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.metadata.ownerReferences.withUid

```ts
withUid(uid)
```



## obj spec.unsupported.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.spec



### fn spec.unsupported.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.spec.withAccessModes

```ts
withAccessModes(accessModes)
```



### fn spec.unsupported.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.spec.withAccessModesMixin

```ts
withAccessModesMixin(accessModes)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.spec.withStorageClassName

```ts
withStorageClassName(storageClassName)
```



### fn spec.unsupported.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.spec.withVolumeAttributesClassName

```ts
withVolumeAttributesClassName(volumeAttributesClassName)
```



### fn spec.unsupported.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.spec.withVolumeMode

```ts
withVolumeMode(volumeMode)
```



### fn spec.unsupported.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.spec.withVolumeName

```ts
withVolumeName(volumeName)
```



## obj spec.unsupported.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.spec.dataSource



### fn spec.unsupported.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.spec.dataSource.withApiGroup

```ts
withApiGroup(apiGroup)
```



### fn spec.unsupported.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.spec.dataSource.withKind

```ts
withKind(kind)
```



### fn spec.unsupported.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.spec.dataSource.withName

```ts
withName(name)
```



## obj spec.unsupported.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.spec.dataSourceRef



### fn spec.unsupported.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.spec.dataSourceRef.withApiGroup

```ts
withApiGroup(apiGroup)
```



### fn spec.unsupported.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.spec.dataSourceRef.withKind

```ts
withKind(kind)
```



### fn spec.unsupported.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.spec.dataSourceRef.withName

```ts
withName(name)
```



### fn spec.unsupported.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.spec.dataSourceRef.withNamespace

```ts
withNamespace(namespace)
```



## obj spec.unsupported.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.spec.resources



### fn spec.unsupported.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.spec.resources.withLimits

```ts
withLimits(limits)
```



### fn spec.unsupported.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.spec.resources.withLimitsMixin

```ts
withLimitsMixin(limits)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.spec.resources.withRequests

```ts
withRequests(requests)
```



### fn spec.unsupported.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.spec.resources.withRequestsMixin

```ts
withRequestsMixin(requests)
```



**Note:** This function appends passed data to existing values

## obj spec.unsupported.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.spec.selector



### fn spec.unsupported.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.spec.selector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.unsupported.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.spec.selector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.spec.selector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.unsupported.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.spec.selector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.unsupported.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.spec.selector.matchExpressions



### fn spec.unsupported.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.spec.selector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.unsupported.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.spec.selector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.unsupported.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.spec.selector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.unsupported.podTemplate.spec.volumes.ephemeral.volumeClaimTemplate.spec.selector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.unsupported.podTemplate.spec.volumes.fc



### fn spec.unsupported.podTemplate.spec.volumes.fc.withFsType

```ts
withFsType(fsType)
```



### fn spec.unsupported.podTemplate.spec.volumes.fc.withLun

```ts
withLun(lun)
```



### fn spec.unsupported.podTemplate.spec.volumes.fc.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.unsupported.podTemplate.spec.volumes.fc.withTargetWWNs

```ts
withTargetWWNs(targetWWNs)
```



### fn spec.unsupported.podTemplate.spec.volumes.fc.withTargetWWNsMixin

```ts
withTargetWWNsMixin(targetWWNs)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.volumes.fc.withWwids

```ts
withWwids(wwids)
```



### fn spec.unsupported.podTemplate.spec.volumes.fc.withWwidsMixin

```ts
withWwidsMixin(wwids)
```



**Note:** This function appends passed data to existing values

## obj spec.unsupported.podTemplate.spec.volumes.flexVolume



### fn spec.unsupported.podTemplate.spec.volumes.flexVolume.withDriver

```ts
withDriver(driver)
```



### fn spec.unsupported.podTemplate.spec.volumes.flexVolume.withFsType

```ts
withFsType(fsType)
```



### fn spec.unsupported.podTemplate.spec.volumes.flexVolume.withOptions

```ts
withOptions(options)
```



### fn spec.unsupported.podTemplate.spec.volumes.flexVolume.withOptionsMixin

```ts
withOptionsMixin(options)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.volumes.flexVolume.withReadOnly

```ts
withReadOnly(readOnly)
```



## obj spec.unsupported.podTemplate.spec.volumes.flexVolume.secretRef



### fn spec.unsupported.podTemplate.spec.volumes.flexVolume.secretRef.withName

```ts
withName(name)
```



## obj spec.unsupported.podTemplate.spec.volumes.flocker



### fn spec.unsupported.podTemplate.spec.volumes.flocker.withDatasetName

```ts
withDatasetName(datasetName)
```



### fn spec.unsupported.podTemplate.spec.volumes.flocker.withDatasetUUID

```ts
withDatasetUUID(datasetUUID)
```



## obj spec.unsupported.podTemplate.spec.volumes.gcePersistentDisk



### fn spec.unsupported.podTemplate.spec.volumes.gcePersistentDisk.withFsType

```ts
withFsType(fsType)
```



### fn spec.unsupported.podTemplate.spec.volumes.gcePersistentDisk.withPartition

```ts
withPartition(partition)
```



### fn spec.unsupported.podTemplate.spec.volumes.gcePersistentDisk.withPdName

```ts
withPdName(pdName)
```



### fn spec.unsupported.podTemplate.spec.volumes.gcePersistentDisk.withReadOnly

```ts
withReadOnly(readOnly)
```



## obj spec.unsupported.podTemplate.spec.volumes.gitRepo



### fn spec.unsupported.podTemplate.spec.volumes.gitRepo.withDirectory

```ts
withDirectory(directory)
```



### fn spec.unsupported.podTemplate.spec.volumes.gitRepo.withRepository

```ts
withRepository(repository)
```



### fn spec.unsupported.podTemplate.spec.volumes.gitRepo.withRevision

```ts
withRevision(revision)
```



## obj spec.unsupported.podTemplate.spec.volumes.glusterfs



### fn spec.unsupported.podTemplate.spec.volumes.glusterfs.withEndpoints

```ts
withEndpoints(endpoints)
```



### fn spec.unsupported.podTemplate.spec.volumes.glusterfs.withPath

```ts
withPath(path)
```



### fn spec.unsupported.podTemplate.spec.volumes.glusterfs.withReadOnly

```ts
withReadOnly(readOnly)
```



## obj spec.unsupported.podTemplate.spec.volumes.hostPath



### fn spec.unsupported.podTemplate.spec.volumes.hostPath.withPath

```ts
withPath(path)
```



### fn spec.unsupported.podTemplate.spec.volumes.hostPath.withType

```ts
withType(type)
```



## obj spec.unsupported.podTemplate.spec.volumes.image



### fn spec.unsupported.podTemplate.spec.volumes.image.withPullPolicy

```ts
withPullPolicy(pullPolicy)
```



### fn spec.unsupported.podTemplate.spec.volumes.image.withReference

```ts
withReference(reference)
```



## obj spec.unsupported.podTemplate.spec.volumes.iscsi



### fn spec.unsupported.podTemplate.spec.volumes.iscsi.withChapAuthDiscovery

```ts
withChapAuthDiscovery(chapAuthDiscovery)
```



### fn spec.unsupported.podTemplate.spec.volumes.iscsi.withChapAuthSession

```ts
withChapAuthSession(chapAuthSession)
```



### fn spec.unsupported.podTemplate.spec.volumes.iscsi.withFsType

```ts
withFsType(fsType)
```



### fn spec.unsupported.podTemplate.spec.volumes.iscsi.withInitiatorName

```ts
withInitiatorName(initiatorName)
```



### fn spec.unsupported.podTemplate.spec.volumes.iscsi.withIqn

```ts
withIqn(iqn)
```



### fn spec.unsupported.podTemplate.spec.volumes.iscsi.withIscsiInterface

```ts
withIscsiInterface(iscsiInterface)
```



### fn spec.unsupported.podTemplate.spec.volumes.iscsi.withLun

```ts
withLun(lun)
```



### fn spec.unsupported.podTemplate.spec.volumes.iscsi.withPortals

```ts
withPortals(portals)
```



### fn spec.unsupported.podTemplate.spec.volumes.iscsi.withPortalsMixin

```ts
withPortalsMixin(portals)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.volumes.iscsi.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.unsupported.podTemplate.spec.volumes.iscsi.withTargetPortal

```ts
withTargetPortal(targetPortal)
```



## obj spec.unsupported.podTemplate.spec.volumes.iscsi.secretRef



### fn spec.unsupported.podTemplate.spec.volumes.iscsi.secretRef.withName

```ts
withName(name)
```



## obj spec.unsupported.podTemplate.spec.volumes.nfs



### fn spec.unsupported.podTemplate.spec.volumes.nfs.withPath

```ts
withPath(path)
```



### fn spec.unsupported.podTemplate.spec.volumes.nfs.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.unsupported.podTemplate.spec.volumes.nfs.withServer

```ts
withServer(server)
```



## obj spec.unsupported.podTemplate.spec.volumes.persistentVolumeClaim



### fn spec.unsupported.podTemplate.spec.volumes.persistentVolumeClaim.withClaimName

```ts
withClaimName(claimName)
```



### fn spec.unsupported.podTemplate.spec.volumes.persistentVolumeClaim.withReadOnly

```ts
withReadOnly(readOnly)
```



## obj spec.unsupported.podTemplate.spec.volumes.photonPersistentDisk



### fn spec.unsupported.podTemplate.spec.volumes.photonPersistentDisk.withFsType

```ts
withFsType(fsType)
```



### fn spec.unsupported.podTemplate.spec.volumes.photonPersistentDisk.withPdID

```ts
withPdID(pdID)
```



## obj spec.unsupported.podTemplate.spec.volumes.portworxVolume



### fn spec.unsupported.podTemplate.spec.volumes.portworxVolume.withFsType

```ts
withFsType(fsType)
```



### fn spec.unsupported.podTemplate.spec.volumes.portworxVolume.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.unsupported.podTemplate.spec.volumes.portworxVolume.withVolumeID

```ts
withVolumeID(volumeID)
```



## obj spec.unsupported.podTemplate.spec.volumes.projected



### fn spec.unsupported.podTemplate.spec.volumes.projected.withDefaultMode

```ts
withDefaultMode(defaultMode)
```



### fn spec.unsupported.podTemplate.spec.volumes.projected.withSources

```ts
withSources(sources)
```



### fn spec.unsupported.podTemplate.spec.volumes.projected.withSourcesMixin

```ts
withSourcesMixin(sources)
```



**Note:** This function appends passed data to existing values

## obj spec.unsupported.podTemplate.spec.volumes.projected.sources



## obj spec.unsupported.podTemplate.spec.volumes.projected.sources.clusterTrustBundle



### fn spec.unsupported.podTemplate.spec.volumes.projected.sources.clusterTrustBundle.withName

```ts
withName(name)
```



### fn spec.unsupported.podTemplate.spec.volumes.projected.sources.clusterTrustBundle.withOptional

```ts
withOptional(optional)
```



### fn spec.unsupported.podTemplate.spec.volumes.projected.sources.clusterTrustBundle.withPath

```ts
withPath(path)
```



### fn spec.unsupported.podTemplate.spec.volumes.projected.sources.clusterTrustBundle.withSignerName

```ts
withSignerName(signerName)
```



## obj spec.unsupported.podTemplate.spec.volumes.projected.sources.clusterTrustBundle.labelSelector



### fn spec.unsupported.podTemplate.spec.volumes.projected.sources.clusterTrustBundle.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.unsupported.podTemplate.spec.volumes.projected.sources.clusterTrustBundle.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.volumes.projected.sources.clusterTrustBundle.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.unsupported.podTemplate.spec.volumes.projected.sources.clusterTrustBundle.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.unsupported.podTemplate.spec.volumes.projected.sources.clusterTrustBundle.labelSelector.matchExpressions



### fn spec.unsupported.podTemplate.spec.volumes.projected.sources.clusterTrustBundle.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.unsupported.podTemplate.spec.volumes.projected.sources.clusterTrustBundle.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.unsupported.podTemplate.spec.volumes.projected.sources.clusterTrustBundle.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.unsupported.podTemplate.spec.volumes.projected.sources.clusterTrustBundle.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.unsupported.podTemplate.spec.volumes.projected.sources.configMap



### fn spec.unsupported.podTemplate.spec.volumes.projected.sources.configMap.withItems

```ts
withItems(items)
```



### fn spec.unsupported.podTemplate.spec.volumes.projected.sources.configMap.withItemsMixin

```ts
withItemsMixin(items)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.volumes.projected.sources.configMap.withName

```ts
withName(name)
```



### fn spec.unsupported.podTemplate.spec.volumes.projected.sources.configMap.withOptional

```ts
withOptional(optional)
```



## obj spec.unsupported.podTemplate.spec.volumes.projected.sources.configMap.items



### fn spec.unsupported.podTemplate.spec.volumes.projected.sources.configMap.items.withKey

```ts
withKey(key)
```



### fn spec.unsupported.podTemplate.spec.volumes.projected.sources.configMap.items.withMode

```ts
withMode(mode)
```



### fn spec.unsupported.podTemplate.spec.volumes.projected.sources.configMap.items.withPath

```ts
withPath(path)
```



## obj spec.unsupported.podTemplate.spec.volumes.projected.sources.downwardAPI



### fn spec.unsupported.podTemplate.spec.volumes.projected.sources.downwardAPI.withItems

```ts
withItems(items)
```



### fn spec.unsupported.podTemplate.spec.volumes.projected.sources.downwardAPI.withItemsMixin

```ts
withItemsMixin(items)
```



**Note:** This function appends passed data to existing values

## obj spec.unsupported.podTemplate.spec.volumes.projected.sources.downwardAPI.items



### fn spec.unsupported.podTemplate.spec.volumes.projected.sources.downwardAPI.items.withMode

```ts
withMode(mode)
```



### fn spec.unsupported.podTemplate.spec.volumes.projected.sources.downwardAPI.items.withPath

```ts
withPath(path)
```



## obj spec.unsupported.podTemplate.spec.volumes.projected.sources.downwardAPI.items.fieldRef



### fn spec.unsupported.podTemplate.spec.volumes.projected.sources.downwardAPI.items.fieldRef.withApiVersion

```ts
withApiVersion(apiVersion)
```



### fn spec.unsupported.podTemplate.spec.volumes.projected.sources.downwardAPI.items.fieldRef.withFieldPath

```ts
withFieldPath(fieldPath)
```



## obj spec.unsupported.podTemplate.spec.volumes.projected.sources.downwardAPI.items.resourceFieldRef



### fn spec.unsupported.podTemplate.spec.volumes.projected.sources.downwardAPI.items.resourceFieldRef.withContainerName

```ts
withContainerName(containerName)
```



### fn spec.unsupported.podTemplate.spec.volumes.projected.sources.downwardAPI.items.resourceFieldRef.withDivisor

```ts
withDivisor(divisor)
```



### fn spec.unsupported.podTemplate.spec.volumes.projected.sources.downwardAPI.items.resourceFieldRef.withResource

```ts
withResource(resource)
```



## obj spec.unsupported.podTemplate.spec.volumes.projected.sources.secret



### fn spec.unsupported.podTemplate.spec.volumes.projected.sources.secret.withItems

```ts
withItems(items)
```



### fn spec.unsupported.podTemplate.spec.volumes.projected.sources.secret.withItemsMixin

```ts
withItemsMixin(items)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.volumes.projected.sources.secret.withName

```ts
withName(name)
```



### fn spec.unsupported.podTemplate.spec.volumes.projected.sources.secret.withOptional

```ts
withOptional(optional)
```



## obj spec.unsupported.podTemplate.spec.volumes.projected.sources.secret.items



### fn spec.unsupported.podTemplate.spec.volumes.projected.sources.secret.items.withKey

```ts
withKey(key)
```



### fn spec.unsupported.podTemplate.spec.volumes.projected.sources.secret.items.withMode

```ts
withMode(mode)
```



### fn spec.unsupported.podTemplate.spec.volumes.projected.sources.secret.items.withPath

```ts
withPath(path)
```



## obj spec.unsupported.podTemplate.spec.volumes.projected.sources.serviceAccountToken



### fn spec.unsupported.podTemplate.spec.volumes.projected.sources.serviceAccountToken.withAudience

```ts
withAudience(audience)
```



### fn spec.unsupported.podTemplate.spec.volumes.projected.sources.serviceAccountToken.withExpirationSeconds

```ts
withExpirationSeconds(expirationSeconds)
```



### fn spec.unsupported.podTemplate.spec.volumes.projected.sources.serviceAccountToken.withPath

```ts
withPath(path)
```



## obj spec.unsupported.podTemplate.spec.volumes.quobyte



### fn spec.unsupported.podTemplate.spec.volumes.quobyte.withGroup

```ts
withGroup(group)
```



### fn spec.unsupported.podTemplate.spec.volumes.quobyte.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.unsupported.podTemplate.spec.volumes.quobyte.withRegistry

```ts
withRegistry(registry)
```



### fn spec.unsupported.podTemplate.spec.volumes.quobyte.withTenant

```ts
withTenant(tenant)
```



### fn spec.unsupported.podTemplate.spec.volumes.quobyte.withUser

```ts
withUser(user)
```



### fn spec.unsupported.podTemplate.spec.volumes.quobyte.withVolume

```ts
withVolume(volume)
```



## obj spec.unsupported.podTemplate.spec.volumes.rbd



### fn spec.unsupported.podTemplate.spec.volumes.rbd.withFsType

```ts
withFsType(fsType)
```



### fn spec.unsupported.podTemplate.spec.volumes.rbd.withImage

```ts
withImage(image)
```



### fn spec.unsupported.podTemplate.spec.volumes.rbd.withKeyring

```ts
withKeyring(keyring)
```



### fn spec.unsupported.podTemplate.spec.volumes.rbd.withMonitors

```ts
withMonitors(monitors)
```



### fn spec.unsupported.podTemplate.spec.volumes.rbd.withMonitorsMixin

```ts
withMonitorsMixin(monitors)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.volumes.rbd.withPool

```ts
withPool(pool)
```



### fn spec.unsupported.podTemplate.spec.volumes.rbd.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.unsupported.podTemplate.spec.volumes.rbd.withUser

```ts
withUser(user)
```



## obj spec.unsupported.podTemplate.spec.volumes.rbd.secretRef



### fn spec.unsupported.podTemplate.spec.volumes.rbd.secretRef.withName

```ts
withName(name)
```



## obj spec.unsupported.podTemplate.spec.volumes.scaleIO



### fn spec.unsupported.podTemplate.spec.volumes.scaleIO.withFsType

```ts
withFsType(fsType)
```



### fn spec.unsupported.podTemplate.spec.volumes.scaleIO.withGateway

```ts
withGateway(gateway)
```



### fn spec.unsupported.podTemplate.spec.volumes.scaleIO.withProtectionDomain

```ts
withProtectionDomain(protectionDomain)
```



### fn spec.unsupported.podTemplate.spec.volumes.scaleIO.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.unsupported.podTemplate.spec.volumes.scaleIO.withSslEnabled

```ts
withSslEnabled(sslEnabled)
```



### fn spec.unsupported.podTemplate.spec.volumes.scaleIO.withStorageMode

```ts
withStorageMode(storageMode)
```



### fn spec.unsupported.podTemplate.spec.volumes.scaleIO.withStoragePool

```ts
withStoragePool(storagePool)
```



### fn spec.unsupported.podTemplate.spec.volumes.scaleIO.withSystem

```ts
withSystem(system)
```



### fn spec.unsupported.podTemplate.spec.volumes.scaleIO.withVolumeName

```ts
withVolumeName(volumeName)
```



## obj spec.unsupported.podTemplate.spec.volumes.scaleIO.secretRef



### fn spec.unsupported.podTemplate.spec.volumes.scaleIO.secretRef.withName

```ts
withName(name)
```



## obj spec.unsupported.podTemplate.spec.volumes.secret



### fn spec.unsupported.podTemplate.spec.volumes.secret.withDefaultMode

```ts
withDefaultMode(defaultMode)
```



### fn spec.unsupported.podTemplate.spec.volumes.secret.withItems

```ts
withItems(items)
```



### fn spec.unsupported.podTemplate.spec.volumes.secret.withItemsMixin

```ts
withItemsMixin(items)
```



**Note:** This function appends passed data to existing values

### fn spec.unsupported.podTemplate.spec.volumes.secret.withOptional

```ts
withOptional(optional)
```



### fn spec.unsupported.podTemplate.spec.volumes.secret.withSecretName

```ts
withSecretName(secretName)
```



## obj spec.unsupported.podTemplate.spec.volumes.secret.items



### fn spec.unsupported.podTemplate.spec.volumes.secret.items.withKey

```ts
withKey(key)
```



### fn spec.unsupported.podTemplate.spec.volumes.secret.items.withMode

```ts
withMode(mode)
```



### fn spec.unsupported.podTemplate.spec.volumes.secret.items.withPath

```ts
withPath(path)
```



## obj spec.unsupported.podTemplate.spec.volumes.storageos



### fn spec.unsupported.podTemplate.spec.volumes.storageos.withFsType

```ts
withFsType(fsType)
```



### fn spec.unsupported.podTemplate.spec.volumes.storageos.withReadOnly

```ts
withReadOnly(readOnly)
```



### fn spec.unsupported.podTemplate.spec.volumes.storageos.withVolumeName

```ts
withVolumeName(volumeName)
```



### fn spec.unsupported.podTemplate.spec.volumes.storageos.withVolumeNamespace

```ts
withVolumeNamespace(volumeNamespace)
```



## obj spec.unsupported.podTemplate.spec.volumes.storageos.secretRef



### fn spec.unsupported.podTemplate.spec.volumes.storageos.secretRef.withName

```ts
withName(name)
```



## obj spec.unsupported.podTemplate.spec.volumes.vsphereVolume



### fn spec.unsupported.podTemplate.spec.volumes.vsphereVolume.withFsType

```ts
withFsType(fsType)
```



### fn spec.unsupported.podTemplate.spec.volumes.vsphereVolume.withStoragePolicyID

```ts
withStoragePolicyID(storagePolicyID)
```



### fn spec.unsupported.podTemplate.spec.volumes.vsphereVolume.withStoragePolicyName

```ts
withStoragePolicyName(storagePolicyName)
```



### fn spec.unsupported.podTemplate.spec.volumes.vsphereVolume.withVolumePath

```ts
withVolumePath(volumePath)
```



## obj spec.update

"Configuration related to Keycloak deployment updates."

### fn spec.update.withRevision

```ts
withRevision(revision)
```

"When use the Explicit strategy, the revision signals if a rolling update can be used or not."

### fn spec.update.withStrategy

```ts
withStrategy(strategy)
```

"Sets the update strategy to use."

## obj spec.update.scheduling

"In this section you can configure the update job's scheduling"

### fn spec.update.scheduling.withPriorityClassName

```ts
withPriorityClassName(priorityClassName)
```



### fn spec.update.scheduling.withTolerations

```ts
withTolerations(tolerations)
```



### fn spec.update.scheduling.withTolerationsMixin

```ts
withTolerationsMixin(tolerations)
```



**Note:** This function appends passed data to existing values

### fn spec.update.scheduling.withTopologySpreadConstraints

```ts
withTopologySpreadConstraints(topologySpreadConstraints)
```



### fn spec.update.scheduling.withTopologySpreadConstraintsMixin

```ts
withTopologySpreadConstraintsMixin(topologySpreadConstraints)
```



**Note:** This function appends passed data to existing values

## obj spec.update.scheduling.affinity



## obj spec.update.scheduling.affinity.nodeAffinity



### fn spec.update.scheduling.affinity.nodeAffinity.withPreferredDuringSchedulingIgnoredDuringExecution

```ts
withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.update.scheduling.affinity.nodeAffinity.withPreferredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

## obj spec.update.scheduling.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution



### fn spec.update.scheduling.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.withWeight

```ts
withWeight(weight)
```



## obj spec.update.scheduling.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference



### fn spec.update.scheduling.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.update.scheduling.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.update.scheduling.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.withMatchFields

```ts
withMatchFields(matchFields)
```



### fn spec.update.scheduling.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.withMatchFieldsMixin

```ts
withMatchFieldsMixin(matchFields)
```



**Note:** This function appends passed data to existing values

## obj spec.update.scheduling.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions



### fn spec.update.scheduling.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.update.scheduling.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.update.scheduling.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.update.scheduling.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.update.scheduling.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields



### fn spec.update.scheduling.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields.withKey

```ts
withKey(key)
```



### fn spec.update.scheduling.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields.withOperator

```ts
withOperator(operator)
```



### fn spec.update.scheduling.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields.withValues

```ts
withValues(values)
```



### fn spec.update.scheduling.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.update.scheduling.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution



### fn spec.update.scheduling.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNodeSelectorTerms

```ts
withNodeSelectorTerms(nodeSelectorTerms)
```



### fn spec.update.scheduling.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNodeSelectorTermsMixin

```ts
withNodeSelectorTermsMixin(nodeSelectorTerms)
```



**Note:** This function appends passed data to existing values

## obj spec.update.scheduling.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms



### fn spec.update.scheduling.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.update.scheduling.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.update.scheduling.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.withMatchFields

```ts
withMatchFields(matchFields)
```



### fn spec.update.scheduling.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.withMatchFieldsMixin

```ts
withMatchFieldsMixin(matchFields)
```



**Note:** This function appends passed data to existing values

## obj spec.update.scheduling.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions



### fn spec.update.scheduling.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.update.scheduling.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.update.scheduling.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.update.scheduling.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.update.scheduling.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields



### fn spec.update.scheduling.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields.withKey

```ts
withKey(key)
```



### fn spec.update.scheduling.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields.withOperator

```ts
withOperator(operator)
```



### fn spec.update.scheduling.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields.withValues

```ts
withValues(values)
```



### fn spec.update.scheduling.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.update.scheduling.affinity.podAffinity



### fn spec.update.scheduling.affinity.podAffinity.withPreferredDuringSchedulingIgnoredDuringExecution

```ts
withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.update.scheduling.affinity.podAffinity.withPreferredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

### fn spec.update.scheduling.affinity.podAffinity.withRequiredDuringSchedulingIgnoredDuringExecution

```ts
withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.update.scheduling.affinity.podAffinity.withRequiredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

## obj spec.update.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution



### fn spec.update.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.withWeight

```ts
withWeight(weight)
```



## obj spec.update.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm



### fn spec.update.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMatchLabelKeys

```ts
withMatchLabelKeys(matchLabelKeys)
```



### fn spec.update.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMatchLabelKeysMixin

```ts
withMatchLabelKeysMixin(matchLabelKeys)
```



**Note:** This function appends passed data to existing values

### fn spec.update.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMismatchLabelKeys

```ts
withMismatchLabelKeys(mismatchLabelKeys)
```



### fn spec.update.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMismatchLabelKeysMixin

```ts
withMismatchLabelKeysMixin(mismatchLabelKeys)
```



**Note:** This function appends passed data to existing values

### fn spec.update.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withNamespaces

```ts
withNamespaces(namespaces)
```



### fn spec.update.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withNamespacesMixin

```ts
withNamespacesMixin(namespaces)
```



**Note:** This function appends passed data to existing values

### fn spec.update.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withTopologyKey

```ts
withTopologyKey(topologyKey)
```



## obj spec.update.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector



### fn spec.update.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.update.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.update.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.update.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.update.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions



### fn spec.update.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.update.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.update.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.update.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.update.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector



### fn spec.update.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.update.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.update.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.update.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.update.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions



### fn spec.update.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.update.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.update.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.update.scheduling.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.update.scheduling.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution



### fn spec.update.scheduling.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMatchLabelKeys

```ts
withMatchLabelKeys(matchLabelKeys)
```



### fn spec.update.scheduling.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMatchLabelKeysMixin

```ts
withMatchLabelKeysMixin(matchLabelKeys)
```



**Note:** This function appends passed data to existing values

### fn spec.update.scheduling.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMismatchLabelKeys

```ts
withMismatchLabelKeys(mismatchLabelKeys)
```



### fn spec.update.scheduling.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMismatchLabelKeysMixin

```ts
withMismatchLabelKeysMixin(mismatchLabelKeys)
```



**Note:** This function appends passed data to existing values

### fn spec.update.scheduling.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNamespaces

```ts
withNamespaces(namespaces)
```



### fn spec.update.scheduling.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNamespacesMixin

```ts
withNamespacesMixin(namespaces)
```



**Note:** This function appends passed data to existing values

### fn spec.update.scheduling.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withTopologyKey

```ts
withTopologyKey(topologyKey)
```



## obj spec.update.scheduling.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector



### fn spec.update.scheduling.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.update.scheduling.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.update.scheduling.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.update.scheduling.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.update.scheduling.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions



### fn spec.update.scheduling.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.update.scheduling.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.update.scheduling.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.update.scheduling.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.update.scheduling.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector



### fn spec.update.scheduling.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.update.scheduling.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.update.scheduling.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.update.scheduling.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.update.scheduling.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions



### fn spec.update.scheduling.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.update.scheduling.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.update.scheduling.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.update.scheduling.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.update.scheduling.affinity.podAntiAffinity



### fn spec.update.scheduling.affinity.podAntiAffinity.withPreferredDuringSchedulingIgnoredDuringExecution

```ts
withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.update.scheduling.affinity.podAntiAffinity.withPreferredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

### fn spec.update.scheduling.affinity.podAntiAffinity.withRequiredDuringSchedulingIgnoredDuringExecution

```ts
withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)
```



### fn spec.update.scheduling.affinity.podAntiAffinity.withRequiredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)
```



**Note:** This function appends passed data to existing values

## obj spec.update.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution



### fn spec.update.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.withWeight

```ts
withWeight(weight)
```



## obj spec.update.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm



### fn spec.update.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMatchLabelKeys

```ts
withMatchLabelKeys(matchLabelKeys)
```



### fn spec.update.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMatchLabelKeysMixin

```ts
withMatchLabelKeysMixin(matchLabelKeys)
```



**Note:** This function appends passed data to existing values

### fn spec.update.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMismatchLabelKeys

```ts
withMismatchLabelKeys(mismatchLabelKeys)
```



### fn spec.update.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMismatchLabelKeysMixin

```ts
withMismatchLabelKeysMixin(mismatchLabelKeys)
```



**Note:** This function appends passed data to existing values

### fn spec.update.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withNamespaces

```ts
withNamespaces(namespaces)
```



### fn spec.update.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withNamespacesMixin

```ts
withNamespacesMixin(namespaces)
```



**Note:** This function appends passed data to existing values

### fn spec.update.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withTopologyKey

```ts
withTopologyKey(topologyKey)
```



## obj spec.update.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector



### fn spec.update.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.update.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.update.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.update.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.update.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions



### fn spec.update.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.update.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.update.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.update.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.update.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector



### fn spec.update.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.update.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.update.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.update.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.update.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions



### fn spec.update.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.update.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.update.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.update.scheduling.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.update.scheduling.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution



### fn spec.update.scheduling.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMatchLabelKeys

```ts
withMatchLabelKeys(matchLabelKeys)
```



### fn spec.update.scheduling.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMatchLabelKeysMixin

```ts
withMatchLabelKeysMixin(matchLabelKeys)
```



**Note:** This function appends passed data to existing values

### fn spec.update.scheduling.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMismatchLabelKeys

```ts
withMismatchLabelKeys(mismatchLabelKeys)
```



### fn spec.update.scheduling.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMismatchLabelKeysMixin

```ts
withMismatchLabelKeysMixin(mismatchLabelKeys)
```



**Note:** This function appends passed data to existing values

### fn spec.update.scheduling.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNamespaces

```ts
withNamespaces(namespaces)
```



### fn spec.update.scheduling.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNamespacesMixin

```ts
withNamespacesMixin(namespaces)
```



**Note:** This function appends passed data to existing values

### fn spec.update.scheduling.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withTopologyKey

```ts
withTopologyKey(topologyKey)
```



## obj spec.update.scheduling.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector



### fn spec.update.scheduling.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.update.scheduling.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.update.scheduling.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.update.scheduling.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.update.scheduling.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions



### fn spec.update.scheduling.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.update.scheduling.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.update.scheduling.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.update.scheduling.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.update.scheduling.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector



### fn spec.update.scheduling.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.update.scheduling.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.update.scheduling.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.update.scheduling.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.update.scheduling.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions



### fn spec.update.scheduling.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.update.scheduling.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.update.scheduling.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.update.scheduling.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values

## obj spec.update.scheduling.tolerations



### fn spec.update.scheduling.tolerations.withEffect

```ts
withEffect(effect)
```



### fn spec.update.scheduling.tolerations.withKey

```ts
withKey(key)
```



### fn spec.update.scheduling.tolerations.withOperator

```ts
withOperator(operator)
```



### fn spec.update.scheduling.tolerations.withTolerationSeconds

```ts
withTolerationSeconds(tolerationSeconds)
```



### fn spec.update.scheduling.tolerations.withValue

```ts
withValue(value)
```



## obj spec.update.scheduling.topologySpreadConstraints



### fn spec.update.scheduling.topologySpreadConstraints.withMatchLabelKeys

```ts
withMatchLabelKeys(matchLabelKeys)
```



### fn spec.update.scheduling.topologySpreadConstraints.withMatchLabelKeysMixin

```ts
withMatchLabelKeysMixin(matchLabelKeys)
```



**Note:** This function appends passed data to existing values

### fn spec.update.scheduling.topologySpreadConstraints.withMaxSkew

```ts
withMaxSkew(maxSkew)
```



### fn spec.update.scheduling.topologySpreadConstraints.withMinDomains

```ts
withMinDomains(minDomains)
```



### fn spec.update.scheduling.topologySpreadConstraints.withNodeAffinityPolicy

```ts
withNodeAffinityPolicy(nodeAffinityPolicy)
```



### fn spec.update.scheduling.topologySpreadConstraints.withNodeTaintsPolicy

```ts
withNodeTaintsPolicy(nodeTaintsPolicy)
```



### fn spec.update.scheduling.topologySpreadConstraints.withTopologyKey

```ts
withTopologyKey(topologyKey)
```



### fn spec.update.scheduling.topologySpreadConstraints.withWhenUnsatisfiable

```ts
withWhenUnsatisfiable(whenUnsatisfiable)
```



## obj spec.update.scheduling.topologySpreadConstraints.labelSelector



### fn spec.update.scheduling.topologySpreadConstraints.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```



### fn spec.update.scheduling.topologySpreadConstraints.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```



**Note:** This function appends passed data to existing values

### fn spec.update.scheduling.topologySpreadConstraints.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```



### fn spec.update.scheduling.topologySpreadConstraints.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```



**Note:** This function appends passed data to existing values

## obj spec.update.scheduling.topologySpreadConstraints.labelSelector.matchExpressions



### fn spec.update.scheduling.topologySpreadConstraints.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```



### fn spec.update.scheduling.topologySpreadConstraints.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```



### fn spec.update.scheduling.topologySpreadConstraints.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```



### fn spec.update.scheduling.topologySpreadConstraints.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```



**Note:** This function appends passed data to existing values