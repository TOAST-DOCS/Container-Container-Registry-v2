<!-- pre-align:aligned sig=265591c02f39 -->

<a id="container-nhn-container-registry-ncr-release-notes"></a>
## Container > NHN Container Registry (NCR) > Release Notes { #container-nhn-container-registry-ncr-release-notes }

<a id="august-26-2025"></a>
### August 26, 2025 { #august-26-2025 }

<a id="august-26-2025-feature-updates"></a>
#### Feature Updates

* Added a feature to identify and delete images in the target NCR that are identical to images that exist in the source registry.

<a id="november-26-2024"></a>
### November 26, 2024 { #november-26-2024 }

<a id="november-26-2024-feature-updates"></a>
#### Feature Updates

* Multi platform images are available from the NCR console.
  
<a id="august-27-2024"></a>
### August 27, 2024 { #august-27-2024 }

<a id="august-27-2024-added-features"></a>
#### Added Features

* Released Public APIs for NCR.
  * For more information about Public API, see [API Guide](./public-api/).
* You receive notifications about events that occur in the registry through Resource Watcher.
  * For more information, see [Resource Watcher](/Governance%20&%20Audit/Resource%20Watcher/en/overview).
* You can view a list of image signatures

<a id="august-27-2024-feature-updates"></a>
#### Feature Updates

* Added the feature to replicate between projects.


<a id="may-28-2024"></a>
### May 28, 2024 { #may-28-2024 }

<a id="may-28-2024-added-features"></a>
#### Added Features
* Added the featue to block deployment of unsigned images.

<a id="may-28-2024-feature-updates"></a>
#### Feature Updates
* Modified image cleanup/protection policies to identify images that contain `/`.
* Expanded artifact lookup items.
* Modified image cleanup policies to be unlimited in number.

<a id="february-27-2024"></a>
### February 27, 2024 { #february-27-2024 }

<a id="february-27-2024-added-features"></a>
#### Added Features
* You can checkout events occurred in the NCR console from CloudTrail.
* Added an overwrite option to the image replication feature.

<a id="february-27-2024-feature-updates"></a>
#### Feature Updates
* Made modifications so that image keyword search is available.

<a id="november-28-2023"></a>
### November 28, 2023 { #november-28-2023 }

<a id="november-28-2023-added-features"></a>
#### Added Features
* Added the feature to set whether to use Public URIs.
* Added the `Image Uploader` permission, which allows you to upload images only.

<a id="august-29-2023"></a>
### August 29, 2023 { #august-29-2023 }

<a id="august-29-2023-feature-updates"></a>
#### Feature Updates

* Added the feature to manage OCI artifacts.
* Added the Quota feature.

<a id="may-30-2023"></a>
### May 30, 2023 { #may-30-2023 }

<a id="may-30-2023-feature-updates"></a>
#### Feature Updates

* Added the feature to replicate pull between regions.

<a id="march-28-2023"></a>
### March 28, 2023 { #march-28-2023 }

<a id="march-28-2023-added-features"></a>
#### Added Features

* Added the image trust feature.

<a id="january-31-2023"></a>
### January 31, 2023 { #january-31-2023 }

<a id="january-31-2023-added-features"></a>
#### Added Features

* Added the image vulnerability scanning feature.

<a id="november-29-2022"></a>
### November 29, 2022 { #november-29-2022 }

<a id="november-29-2022-added-features"></a>
#### Added Features

* Added the image cache feature.

<a id="september-27-2022"></a>
### September 27, 2022 { #september-27-2022 }

<a id="september-27-2022-added-features"></a>
#### Added Features

* Added the Private URI feature
  * Added the Private URI feature that allows users to use the NCR service from an instance unconnected with the internet gateway.
  * For more details, see [Private URI User Guide](./user-guide/#private-uri).

<a id="july-26-2022"></a>
### July 26, 2022 { #july-26-2022 }

<a id="july-26-2022-added-features"></a>
#### Added Features

* Added image cleanup and image protection features.

<a id="may-24-2022"></a>
### May 24, 2022 { #may-24-2022 }

<a id="may-24-2022-feature-updates"></a>
#### Feature Updates

* Made modifications so that nhncloud.com is used as the registry domain.

<a id="april-26-2022"></a>
### April 26, 2022 { #april-26-2022 }

<a id="april-26-2022-feature-updates"></a>
#### Feature Updates

* Made modifications so that the Garbage Collection feature is not exposed to users.

<a id="march-29-2022"></a>
### March 29, 2022 { #march-29-2022 }

<a id="march-29-2022-added-features"></a>
#### Added Features

* Added the inter-region replication feature.

<a id="march-29-2022-feature-updates"></a>
#### Feature Updates

* Changed the name of the Container Registry service to NHN Container Registry (NCR).

<a id="january-25-2022"></a>
### January 25, 2022 { #january-25-2022 }

<a id="january-25-2022-bug-fixes"></a>
#### Bug Fixes
* Fixed an issue where service activation failed intermittently.
* Fixed an issue where the token validity period was set shorter than intended.
* Subdivided error messages generated due to invalid endpoint when creating webhooks.


<a id="november-23-2021"></a>
### November 23, 2021 { #november-23-2021 }
<a id="november-23-2021-new-service-release"></a>
#### New Service Release
* Provides a more stable and comfortable environment with improvements from the previous version of Container Registry service.
* Provides various features by supplementing the drawbacks of the previous version of Container Registry service. Supported features will be updated continuously.
