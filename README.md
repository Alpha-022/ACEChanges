## Slide no. 18
### Slide Title: Multiple Regions

**Issue:** Text got cut off at last line

## Slide no.19
### Region

**Change:** Google Cloud now has **40 regions**, the slide mentions 20+.

## Slide no. 20
### Zones

**Actual Text:** Each region has three or more zones.  
**Change:** Some regions may have **two** zones (especially newer or smaller regions).

## Slide no.  27
### Compute Engine Machine Families

There are two new machine families:  **Storage Optimized** and  **GPU**

- **Storage Optimized (Z3) :** Machine types for storage-intensive workloads, like horizontal, scale-out databases.

- **GPU (N1) :** Graphics processing units (GPUs) accelerate specific workloads on your instances such as machine learning and data processing. 

## Slide no.  33
### Static IP Addresses - Remember

Not an error, just a simple typo. Instead of **an Static IP**, there should be **a Static IP**.


## Slide no. 39
### Committed use discounts

**Suggestion:** The slide mentions that "Up to 70% discount based on machine type and GPUs." This can be made clearer by saying: The discount is up to 55% for most resources, like machine types or GPUs. The discount is up to 70% for memory-optimized machine types.

**Source:** https://cloud.google.com/compute/docs/instances/signing-up-committed-use-discounts

 - **Can be included in slide:**
	- Committed use discounts don't apply to preemptible VM instances, N1 shared-core machine types, or extended memory.


## Slide no. 52
### Gcloud

**Suggestion:** Google Cloud now recommends to use `gcloud storage` commands instead of `gsutil` in Google cloud CLI.


## Slide no. 54
### gcloud config set

The last line got cut off from the slide.

## Slide no. 61
### Playing with Compute Instances - gcloud

**Change:** The **`gcloud compute instances move`** command is deprecated, and it now involves multiple steps to perform the same action.

**Source:** https://cloud.google.com/sdk/gcloud/reference/compute/instances/move

## Slide no. 69
### Managed Instance Group - Command Line - Making Updates

The last line got cut off from the slide.

## Slide no. 84
### Managed Services

**Suggestion:**  Software as a Service (SaaS) terminology can be added.

## Slide no. 91
### Serverless - My Perspective!

**Suggestion:** Instead of saying `Google Functions`, we can mention **`Cloud Run Functions`** or **`Cloud Functions`**.

## Slide no. 92
### GCP Managed Services for Compute

**Change:**  Google Cloud is moving  _**Cloud Functions**_  to  `Cloud Run`  with the name  _**Cloud Run Functions**_.

## Slide no. 105
### Playing with App Engine

The last line got cut off from the slide.

## Slide no. 125
### Kubernetes - Service

Last line got cut out from the slide

## Slide no. 126
### Container Registry - Image Repository

**Change:**  `Google Container Registry` is now  **Artifact Registry**.

## Slide no. 132-137

**Change:** Cloud Functions is now Cloud Run functions

## Slide no. 137
### Cloud Functions - Remember

**Suggestion:** The maximum timeout duration is *60 minutes (3600 seconds) for HTTP functions* and *9 minutes (540 seconds) for event-driven functions.*

**Source:** https://cloud.google.com/functions/docs/configuring/timeout

## Slide no. 138
### Cloud Run & Cloud Run for Anthos

Last line got cut out from the slide

## Slide no. 140 - 143

**Change:** `Cloud Functions` is now **`Cloud Run functions`**

## Slide no. 145
### Data States

The last line got cut off from the slide

## Slide no. 152
### Block Storage

The last line got cut off from the slide

## Slide no. 155
### GCP - Block Storage

There's new type of storage option called **Hyperdisk** available in block storage.
- The official documentation mentions: 
*Google Cloud Hyperdisk is Google's next generation block storage. By offloading and dynamically scaling out storage processing, it decouples storage performance from the VM type and size. Hyperdisk offers substantially higher performance, flexibility and efficiency when compared to Persistent Disk.*

**Source:** https://cloud.google.com/compute/docs/disks

## Slide no. 164
### Let's Compare

The comparison table has been changed. New table can be found here: 
https://cloud.google.com/compute/docs/machine-images

## Slide no. 166
## Playing with Images - Command Line

The last line got cut off from the slide

## Slide no. 169
### Cloud Filestore

**Change:** Firestore now also supports the NFSv4.1 protocol. In the slide, the text can be: *It supports NFSv3 as well as the NFSv4.1 protocol*.

**Source:** https://cloud.google.com/filestore/docs/about-supported-protocols

## Slide no. 156
### Review - Global, Regional and Zonal Resources

**Change :** Instance templates are now available as both  `regional` and `global` resources. 

**Source:** https://cloud.google.com/compute/docs/instance-templates

## Slide no. 179
### Object Versioning

The statement might need a revamp : Prevents accidental deletion & provides history.

**Factual error:**  Objects can only be recovered from a deleted bucket when  _soft delete is enabled_. Object Versioning  _does not_  provide protection against bucket deletions.

**Source:**  [https://cloud.google.com/storage/docs/object-versioning](https://cloud.google.com/storage/docs/object-versioning)

## Slide no. 184
### Cloud Storage - Command Line - gsutil - 1

**Change:**  Google Cloud now recommends to use  `gcloud storage`  commands instead of  `gsutil`  in Google cloud CLI.

**Source:**  [https://cloud.google.com/storage/docs/gsutil](https://cloud.google.com/storage/docs/gsutil)

## Slide no. 189
### Cloud Identity and Access Management (IAM)

The last line got cut off from the slide.

## Slide no. 205
### Cloud Storage - Static website

**Suggestion:**  While stating that "the bucket name should match the DNS name for the website," it's important to specify that this is only applicable if you are using a  ***custom domain***. If you're using the default Google Cloud Storage domain, this requirement does not apply.

## Slide no. 223
### Relational Databases



**Suggestion:** The full form of OLAP should be **`Online Analytical Processing`**. In the slide, it is  written as "Online Analytics Processing."

## Slide no. 228

Blank slide

## Slide no. 229

The formatting of the slide is misaligned.

## Slide no. 231
### Databases - Summary

The last line got cut off from the slide

## Slide no. 237
### Cloud Datastore and Firestore

The last line got cut off from the slide.

## Slide no. 261
### Need for VPC Subnets

**Suggestion:**  We should mention that Load Balancers can also be internal.

## Slide no. 273
### Cloud Interconnect

**Change:** Cloud Interconnect offers a new option called **`Cross-Cloud Interconnect`**.

**Source:** https://cloud.google.com/network-connectivity/docs/interconnect/concepts/overview

## Slide no. 283
### Cloud Audit Logs

The last line got cut off from the slide

## Slide no. 284
### Cloud Logging - Controlling & Routing

The last line got cut off from the slide

## Slide no. 288
### Cloud Debugger

**Change :**  Cloud Debugger deprecation. Cloud Debugger was deprecated on May 16, 2022 and the service was shut down on May 31, 2023.

**Source:**  [https://cloud.google.com/stackdriver/docs/deprecations/debugger-deprecation](https://cloud.google.com/stackdriver/docs/deprecations/debugger-deprecation)

## Slide no. 303
### Resource Hierarchy & IAM Policy

Please review the point: "You can't restrict policy at a lower level if permission is given at a higher level," as mentioned in the slide. I read that deny policies have higher priority.

## Slide no. 313
### Logging IAM Roles and Service Account Roles

**Factual error:** The **serviceAccountUser** role allows running tasks as a service account, but doesn’t let users create or manage instances. *They need extra Compute Engine permissions for that.*

## Slide no. 338
### Cloud Dataproc

The last line got cut off from the slide

## Slide no. 340
### Certification Resources

- The links have been changed.  
Sample questions, learning guide, and registration are available at this link.

https://cloud.google.com/learn/certification/cloud-engineer/
