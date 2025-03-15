# mavsdk-demo

## Getting started

Run the simulator: `./run_sim.sh` and verify in QGroundControl that it is running.

```bash
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
python src/read_telem.py
```

## Source:

MavSDK demo's copied from:
https://github.com/mavlink/MAVSDK-Python/tree/main/examples

Sim:
https://github.com/JonasVautherin/px4-gazebo-headless

## More info:

- MavSDK: https://mavsdk.mavlink.io/main/en/index.html
- More MavSDK examples: https://github.com/mavlink/MAVSDK-Python/tree/main/examples
- QGroundcontrol: https://qgroundcontrol.com/
- PX4: https://px4.io/
