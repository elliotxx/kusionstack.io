# deployment

Source: [base/pkg/kusion_kubernetes/api/apps/v1/deployment.k](https://github.com/KusionStack/konfig/blob/main/base/pkg/kusion_kubernetes/api/apps/v1/deployment.k)

This is the deployment module in kusion\_kubernetes.api.apps.v1 package.<br />This file was generated by the KCL auto-gen tool. DO NOT EDIT.<br />Editing this file might prove futile when you re-run the KCL auto-gen generate command.

## Schema Deployment

Deployment enables declarative updates for Pods and ReplicaSets.

### Attributes

|Name and Description|Type|Default Value|Required|
|--------------------|----|-------------|--------|
|**apiVersion**<br />APIVersion defines the versioned schema of this representation of an object. Servers should convert recognized schemas to the latest internal value, and may reject unrecognized values. More info: https://git.k8s.io/community/contributors/devel/sig-architecture/api-conventions.md\#resources|"apps/v1"|"apps/v1"|**required**|
|**kind**<br />Kind is a string value representing the REST resource this object represents. Servers may infer this from the endpoint the client submits requests to. Cannot be updated. In CamelCase. More info: https://git.k8s.io/community/contributors/devel/sig-architecture/api-conventions.md\#types-kinds|"Deployment"|"Deployment"|**required**|
|**metadata**<br />Standard object's metadata. More info: https://git.k8s.io/community/contributors/devel/sig-architecture/api-conventions.md\#metadata|[apis.ObjectMeta](../../../apimachinery/apis/doc_object_meta#schema-objectmeta)|Undefined|optional|
|**spec**<br />Specification of the desired behavior of the Deployment.|[DeploymentSpec](doc_deployment_spec#schema-deploymentspec)|Undefined|optional|
<!-- Auto generated by kcl-doc tool, please do not edit. -->