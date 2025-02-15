---
title: "Data deletion"
weight: 6

description: |
  Data deletion is handled via our backend providers. When a volume is released back to the provider, the provider will perform a wipe on the data utilizing either [NIST 800-88](https://csrc.nist.gov/publications/detail/sp/800-88/rev-1/final) or [DoD 5220.22-M](http://www.dss.mil/documents/odaa/nispom2006-5220.pdf) depending upon the offering. This wipe is done immediately before reuse.
---

{{< description >}}

All projects, except those hosted on OVH or Orange Cloud for Business, utilize encrypted volumes. The encryption key is destroyed when we release the volume back to the provider, adding another layer of protection.

## Media destruction

Media destruction is handled via our backend providers. When the provider decommissions media it undergoes destruction as outlined in NIST 800-88.

## Data subject removal

Data subject deletion requests where Platform is the controller are handled via a [support ticket](https://docs.platform.sh/overview/getting-help.html). For contracts designating Platform as the processor, deletion requests should be sent to the controller and we will forward any that we receive.

Our product is a Platform as a Service. Platform does not directly edit customer data to ensure data confidentiality, security, and integrity. All data deletion requests for customer data must be handled by the concerned data controller.
