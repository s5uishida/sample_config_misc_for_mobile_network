# Sample Configurations and Miscellaneous for Mobile Network

<a id="toc"></a>

## Table of Contents

- [Open5GS](#open5gs)
- [free5GC](#free5gc)
- [UPF](#upf)
- [RAN and UE](#ran_ue)
- [Performance Measurement](#performance_measurement)
- [Miscellaneous](#misc)

---

<a id="open5gs"></a>

## Open5GS

1. [One SGW-C/PGW-C, one SGW-U/PGW-U and one APN](https://github.com/s5uishida/open5gs_epc_srsran_sample_config)
2. [One SGW-C/PGW-C, Multiple SGW-Us/PGW-Us and APNs](https://github.com/s5uishida/open5gs_epc_oai_sample_config)
3. [One SMF, one UPF and one DNN](https://github.com/s5uishida/open5gs_5gc_srsran_sample_config)
4. [One SMF, Multiple UPFs and DNNs](https://github.com/s5uishida/open5gs_5gc_ueransim_sample_config)
5. [Select nearby UPF(PGW-U) according to the connected eNodeB](https://github.com/s5uishida/open5gs_epc_srsran_nearby_upf_sample_config)
6. [Select nearby UPF according to the connected gNodeB](https://github.com/s5uishida/open5gs_5gc_ueransim_nearby_upf_sample_config)
7. [Select UPF based on S-NSSAI](https://github.com/s5uishida/open5gs_5gc_ueransim_snssai_upf_sample_config)
8. [SCP Indirect communication Model C](https://github.com/s5uishida/open5gs_5gc_ueransim_scp_model_c_sample_config)
9. [VoLTE and SMS Configuration for docker_open5gs](https://github.com/s5uishida/docker_open5gs_volte_sms_config)
10. [Monitoring Metrics with Prometheus](https://github.com/s5uishida/open5gs_5gc_ueransim_metrics_sample_config)
11. [Framed Routing](https://github.com/s5uishida/open5gs_5gc_ueransim_framed_routing_sample_config)
12. [VPP-UPF(PGW-U) with DPDK](https://github.com/s5uishida/open5gs_epc_srsran_vpp_upf_dpdk_sample_config)
13. [VPP-UPF with DPDK](https://github.com/s5uishida/open5gs_5gc_ueransim_vpp_upf_dpdk_sample_config)
14. [eUPF(eBPF/XDP UPF(PGW-U))](https://github.com/s5uishida/open5gs_epc_srsran_eupf_sample_config)
15. [eUPF(eBPF/XDP UPF)](https://github.com/s5uishida/open5gs_5gc_ueransim_eupf_sample_config)

- [Install MongoDB 7.0 and Open5GS WebUI](https://github.com/s5uishida/open5gs_install_mongodb_webui)
- [A Note for Changing Network Interface of UPF from TUN to TAP in Open5GS](https://github.com/s5uishida/change_from_tun_to_tap_in_open5gs)

<a id="free5gc"></a>

## free5GC

1. [One SMF, one UPF and one DNN](https://github.com/s5uishida/free5gc_srsran_sample_config)
2. [One SMF, Multiple UPFs and DNNs](https://github.com/s5uishida/free5gc_ueransim_sample_config)
3. [Select nearby UPF according to the connected gNodeB](https://github.com/s5uishida/free5gc_ueransim_nearby_upf_sample_config)
4. [Select UPF based on S-NSSAI](https://github.com/s5uishida/free5gc_ueransim_snssai_upf_sample_config)
5. [ULCL(Uplink Classifier)](https://github.com/s5uishida/free5gc_ueransim_ulcl_sample_config)
6. [ULCL with one I-UPF and two PSA-UPFs](https://github.com/s5uishida/free5gc_ueransim_ulcl_2_sample_config)
7. [VPP-UPF with DPDK](https://github.com/s5uishida/free5gc_ueransim_vpp_upf_dpdk_sample_config)
8. [eUPF(eBPF/XDP UPF)](https://github.com/s5uishida/free5gc_ueransim_eupf_sample_config)

- [Install MongoDB 7.0 and free5GC WebUI](https://github.com/s5uishida/free5gc_install_mongodb_webui)
- [A Note for Enabling NetworkInstance IE Encoding for free5GC v3.3.0](https://github.com/s5uishida/enable_network_instance_encoding_free5gc_v3_3_0)

<a id="upf"></a>

## UPF

- [Install go-upf on Host](https://github.com/s5uishida/install_goupf)
- [Install VPP-UPF with DPDK on Host](https://github.com/s5uishida/install_vpp_upf_dpdk)
- [Install eUPF(eBPF/XDP UPF) on Host](https://github.com/s5uishida/install_eupf)

<a id="ran_ue"></a>

## RAN and UE

- [Build srsRAN_Project 5G RAN with ZeroMQ](https://github.com/s5uishida/build_srsran_5g_zmq)
- [Build srsRAN 4G UE / RAN with ZeroMQ by disabling RF plugins](https://github.com/s5uishida/build_srsran_4g_zmq_disable_rf_plugins)

<a id="performance_measurement"></a>

## Performance Measurement

**Performance measurement results are highly dependent on the measurement conditions. The results linked here are only examples of results under certain measurement conditions.**

- [Install TRex](https://github.com/s5uishida/install_trex)
- [Simple PFCP Client](https://github.com/s5uishida/simple_pfcp_client)
- [Simple Measurement of UPF Performance 6](https://github.com/s5uishida/simple_measurement_of_upf_performance_6) on Proxmox VE (hypervisor) using TRex and Simple PFCP Client
- [Simple Measurement of UPF Performance 7](https://github.com/s5uishida/simple_measurement_of_upf_performance_7) on Proxmox VE (hypervisor) using PacketRusher
- [Simple Measurement of UPF Performance 8](https://github.com/s5uishida/simple_measurement_of_upf_performance_8) on Proxmox VE (hypervisor) using srsRAN

<details><summary>Past measurement results</summary>

- [Simple Measurement of UPF Performance](https://github.com/s5uishida/simple_measurement_of_upf_performance) on Virtualbox (host os) using PacketRusher

</details>

<a id="misc"></a>

## Miscellaneous

- [Simple Confirmed Information for Mobile Network](https://github.com/s5uishida/simple_confirmed_info_for_mobile_network)
- [Install MongoDB 4.4.18 on Ubuntu 20.04 for Raspberry Pi 4B](https://github.com/s5uishida/install_mongodb_on_ubuntu_for_rp4b)
- [A Note for 5G SUCI Profile A/B Scheme](https://github.com/s5uishida/note_5g_suci_profile_ab)
- [Proxmox VE TIPS](https://github.com/s5uishida/proxmox_ve_tips)
