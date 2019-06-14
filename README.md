# ToolIOControlSwing
Tool I/O Control Swing demonstrates how to work with the resource model and request exclusive control of the Tool I/O Interface through the URCap API. It also demonstrates how to check, if a specific capability is available on the underlying robot system (in this case the Tool Communication Interface and Tool Output Mode features).

For further details about resource control, please see the separate Resource Control document. The concept of system capabilities and checking their availability is described in the separate Capabilities document.

Information: 
* Available from:
  * URCap API version 1.7.0.
  * PolyScope version 3.10.0/5.4.0.

Main API interfaces: ResourceModel, ControllableResourceModel, ToolIOInterfaceController, ToolIOInterface, ToolIOInterfaceControllable, CapabilityManager.
