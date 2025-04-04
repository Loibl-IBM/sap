---

copyright:
  years: 2020
lastupdated: "2020-09-21"

keywords: SAP, {{site.data.keyword.cloud_notm}} SAP-Certified Infrastructure, {{site.data.keyword.ibm_cloud_sap}}, SAP Workloads

subcollection: sap

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:external: target="_blank" .external}
{:pre: .pre}
{:table: .aria-labeledby="caption"}
{:note: .note}
{:tip: .tip}

# Intel Bare Metal server certified profiles for SAP NetWeaver
{: #nw-iaas-offerings-profiles-intel-bm}

## Profiles list
{: #nw-iaas-intel-bm-list}

The published names are subject to change.
{: note}

The following is an overview of the SAP-certified profiles with Intel Bare Metal:

| **Profile** | **CPU Cores** | **CPU Threads (aka. vCPU)** | **Memory (RAM GB)** | **SAPS** |
| --- | --- | --- | --- | --- |
| [BI.S3.NW32](https://cloud.ibm.com/gen1/infrastructure/provision/bm?imageItemId=8451&packageId=1041&itemId=10831) | 4 | 8 | 32 GB | 11,970 |
| [BI.S3.NW64](https://cloud.ibm.com/gen1/infrastructure/provision/bm?imageItemId=8451&packageId=1043&itemId=10831) | 4 | 8 | 64 GB | 12,750 |
| [BI.S3.NW192](https://cloud.ibm.com/gen1/infrastructure/provision/bm?imageItemId=8451&packageId=989&itemId=10437) | 36 | 72 | 192 GB | 78,850 |
| [BI.S3.NW384](https://cloud.ibm.com/gen1/infrastructure/provision/bm?imageItemId=8451&packageId=987&itemId=10437) | 36 | 72 | 384 GB | 79,430 |
| [BI.S3.NW768](https://cloud.ibm.com/gen1/infrastructure/provision/bm?imageItemId=8451&packageId=985&itemId=10437) | 36 | 72 | 768 GB | 79,630 |
| [BI.S4.NW192](https://cloud.ibm.com/gen1/infrastructure/provision/bm?imageItemId=8451&packageId=2640&itemId=13285) | 32 | 64 | 192 GB | 82,470 |
| [BI.S4.NW384](https://cloud.ibm.com/gen1/infrastructure/provision/bm?imageItemId=8451&packageId=2642&itemId=13285) | 32 | 64 | 384 GB | 85,130 |
| [BI.S4.NW768](https://cloud.ibm.com/gen1/infrastructure/provision/bm?imageItemId=8451&packageId=2644&itemId=13289) | 40 | 80 | 768 GB | 112,830 |
{: caption="Table 1. SAP NetWeaver servers" caption-side="top"}

See also [SAP Note 2414097 - SAP Applications on {{site.data.keyword.cloud_notm}}: Supported DB/OS and {{site.data.keyword.cloud_notm}} Bare Metal Server Types](https://launchpad.support.sap.com/#/notes/2414097){: external}.


## Understanding Bare Metal profile names
{: #nw-iaas-intel-bm-names}

The Bare Metal profile names are contextual and sequential, below uses an SAP HANA certified server as an example:

| Profile name | Naming convention component | What it means |
| --- | --- | --- |
| BI.S3.NW384 | BI | {{site.data.keyword.cloud_notm}} Infrastructure |
| | S3 | Series 3 (processor generation)<br/><ul><li>S3 is Intel Skylake/Kaby Lake</li><li>S4 is Intel Cascade Lake</li></ul> |
| | NW | NetWeaver-certified server |
| | 384 | 384 GB RAM |
{: caption="Table 2. Profile naming for SAP NetWeaver" caption-side="top"}


## Profiles available on Hourly Consumption Billing
{: #nw-iaas-intel-bm-hourly}

The following Bare Metal servers are available on **Hourly** Consumption Billing:
- BI.S3.NW32
- BI.S4.NW192
- BI.S4.NW384
- BI.S4.NW768
