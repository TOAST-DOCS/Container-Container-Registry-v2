<!-- pre-align:aligned sig=5789ecf632bb -->

<a id="container-nhn-container-registry-ncr-overview"></a>
## Container > NHN Container Registry (NCR) > Overview { #container-nhn-container-registry-ncr-overview }

A container registry service that allows you to easily and securely store, manage, and deploy Docker container images. You can integrate the NHN Container Registry (NCR) service with the NHN Kubernetes service (NKS) to build your application in a container environment easily.



<a id="components"></a>
### Components { #components }

The NCR service has the following four components.

<a id="components-registry"></a>
#### Registry

A registry is a unit for storing and managing container images. In the NCR service, all images must belong to one registry. You can specify management settings per registry. Currently, you can set up a webhook per registry to be notified of each event that occurs. In the future, various settings will be added. The name of the registry must start with a lowercase letter or number, followed by lowercase letters, numbers, underscores (\_), periods (.), or dashes (-). Registry names can be up to 255 characters.

<a id="components-image"></a>
#### Image

An image is a set of artifacts. Images can be uploaded (pushed) or downloaded (pulled) through the Docker command-line tool. Images are identified by name, and the name of an image must be unique within the registry.

<a id="components-artifact"></a>
#### Artifact

An artifact refers to a specific container image build with one or more layers. Artifacts are identified by a digest ID, which is a hash of the manifest. Artifacts can have no tag or have one or more tags. A common layer connected to artifacts within the registry is shared, allowing efficient use of storage space.

<a id="components-tag"></a>
#### Tag

A tag is a kind of identifier for identifying artifacts. Users can use tags to give each artifact some sort of version. The name of a tag must start with a lowercase letter, number, or underscore (\_), followed by lowercase letters, numbers, underscores (\_), periods (.), or dashes (-). Tag names can be up to 128 characters.



<a id="main-features"></a>
### Main Features { #main-features }

The main features of the NCR service are as follows:

* Docker command-line tool support with Docker Image Manifest v2 compatibility
* Enhanced security through HTTPS encryption, NHN Cloud authentication and permission management
* Scalability and stability based on NHN Cloud Object Storage
* Registry management using the web console
    * Create, delete, and view registries
    * View, search, and delete images and artifacts
    * Create, view, and delete tags
    * Webhook setup for deployment pipeline configuration
    * Image cleanup and protection setup
* Inter-region registry replication feature
* Private URI feature that allows users to use the NCR service from an instance unconnected with the internet gateway
* Image cache feature
* Image vulnerability scanning feature
* Image trust feature