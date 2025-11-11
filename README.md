# legion-power-management

Bridge between power-profiles-daemon and Lenovo hardware power profiles on systems without kernel support.

## Requirements

- [power-profiles-monitor](https://github.com/DmitriySafronov/power-profiles-monitor) scripts & systemd units bundle
- [power-sources-monitor](https://github.com/DmitriySafronov/power-sources-monitor) scripts & systemd units bundle
- acpi_call/acpi-call kernel module from your distro
- [legion-wmi](https://github.com/DmitriySafronov/legion-wmi) kernel module

## Usage
Remember to enable all 4 (four) system services. And reboot.
