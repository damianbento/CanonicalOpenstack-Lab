# REDES

1457	10.120.234.0/24	OpenStack-LAB-18 Public API
1458	 	OpenStack-LAB-18 Control
1459	 	OpenStack-LAB-18 IntApi
1460	 	OpenStack-LAB-18 Tenant
1461	10.120.238.0/24	OpenStack-LAB-18 MachineNet

Para las redes de Charmed-Openstack
External Network        Red externa para acceso de floating y públicas

Storage access          Red de acceso al storage
                        Usada por los clienes para el servicio object storage

Storage replication     Red de replicacion de storage
                        Usada para la replica de datos entre unidades de CEPH

Tenant network          Red de comunicacion entre proyectos de clientes

Internal Network        Red de internal API
                        USada para comunicarse internamente entre los endpoints de los servicios

Public Network          Red de Public API
                        USada para comunicarse internamente entre los endpoints de los servicios
                        via CLI y Horizon y APIs.

OAM Network             Operacion, Administration and Management OOB, (Out of band)
                        Usada para el acceso al cluster, aprovisionamiento, monitoreo y gestión
                        ademas de accedo a la IPMI

Storage Network         Red de acceso a la SVM de Netapp
