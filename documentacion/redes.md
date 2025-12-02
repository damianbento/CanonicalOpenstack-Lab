# REDES

1457	10.120.234.0/24	OpenStack-LAB-18 Public API

1458	 	OpenStack-LAB-18 Control

1459	 	OpenStack-LAB-18 IntApi

1460	 	OpenStack-LAB-18 Tenant

1461	10.120.238.0/24	OpenStack-LAB-18 MachineNet


Para las redes de Charmed-Openstack


| Nombre de la Red | Descripción y Uso Principal |
|:-----------------|:----------------------------|
| **External Network** | Red externa para acceso de **Floating IPs** (IPs flotantes) y **direcciones públicas**. |
| **Storage Access** | Red de acceso al **storage** (almacenamiento). Usada por los clientes para el servicio **Object Storage** (almacenamiento de objetos). |
| **Storage Replication** | Red de **replicación de storage**. Usada para la réplica de datos entre unidades de **CEPH** (o un sistema similar). |
| **Tenant Network** | Red de comunicación entre **proyectos** o **tenants** (inquilinos) de clientes. |
| **Internal Network** | Red de **Internal API**. Usada para comunicarse **internamente** entre los *endpoints* de los servicios del *backend*. |
| **Public Network** | Red de **Public API**. Usada para comunicarse con los *endpoints* de los servicios vía **CLI**, **Horizon** (dashboard) y **APIs** externas. |
| **OAM Network** | **O**peración, **A**dministración y **M**anagement **OOB** (*Out of Band*). Usada para acceso al cluster, aprovisionamiento, monitoreo, gestión y acceso a la **IPMI**. |
| **Storage Network** | Red de acceso a la **SVM** (*Storage Virtual Machine*) de **Netapp**. |

---
