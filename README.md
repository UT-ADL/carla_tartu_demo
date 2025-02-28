# Tutorial
 
 ## Adding Tartu demo track to prebuilt Carla

- Download the [tartu_demo.tar.gz](https://github.com/UT-ADL/carla_tartu_demo/releases/download/v0.9.15.1/tartu_demo.tar.gz) map.
  
- Copy tartu_demo.tar.gz inside the import folder under Carla's ROOT directory.

- Run ./ImportAssets.sh from the ROOT directory.

- You can now delete the tartu_demo.tar.gz file from the import folder.

 ## Running Tartu demo track with traffic on prebuilt Carla

From the ROOT directory run:

- ./CarlaUE4.sh

From the ROOT/PythonAPI/util run:

- python config.py -m tartu_demo

From the ROOT/PythonAPI run:

- python generate_traffic.py

- python manual_control.py

 ## Using UT Lexus with Carla

You might also want to check out the [Lexus](https://github.com/UT-ADL/carla_lexus.git) model from UT-ADL.


