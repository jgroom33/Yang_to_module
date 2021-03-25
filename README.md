# Yang_to_module

The goal is to create ansible modules.  The methodology is as follows:

1. parse yang
2. convert yang to rmb template
3. convert rmb template to ansible module

Details:

In reverse order

Example end artifact (module): https://github.com/ansible-collections/junipernetworks.junos/blob/main/plugins/modules/junos_l2_interfaces.py

Example rmb template: https://github.com/ansible-network/resource_module_models/blob/master/models/junos/l2_interfaces/junos_l2_interfaces.yaml

BGP prop example that links a single prop:

* Example YANG: https://github.com/Juniper/yang/blob/master/20.4/20.4R1/junos-ex/conf/junos-ex-conf-fabric%402019-01-01.yang#L899
* Example RMB template: https://github.com/ansible-network/resource_module_models/blob/master/models/junos/bgp_global/bgp_global.yaml#L631
