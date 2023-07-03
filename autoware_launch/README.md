# autoware_launch

command for launching Autoware VWP
```bash
ros2 launch autoware_launch vwp_launch.launch.xml vehicle_model:=sample_vehicle sensor_model:=sample_sensor_kit map_path:=$HOME/autoware_map/sample-map-planning
```

## Structure

![autoware_launch](./autoware_launch.drawio.svg)

## Package Dependencies

Please see `<exec_depend>` in `package.xml`.

## Usage

You can use the command as follows at shell script to launch `*.launch.xml` in `launch` directory.

```bash
ros2 launch autoware_launch autoware.launch.xml map_path:=/path/to/map_folder vehicle_model:=lexus sensor_model:=aip_xx1
```
