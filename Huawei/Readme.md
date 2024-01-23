# Installation note
Please do not use Modbus RTU connection with Huawei inverters, since it stops responding during its internal communication with servers.
The Huawei Dongle has to be disconnected, so that the inverter will only send data to Taphome.

### How to enable Modbus TCP communication
1. In Huawei configuration app, open Configuration section
2. Select Dongle-1
3. In section "ModBus-TCP", select "Enable (unrestricted)
