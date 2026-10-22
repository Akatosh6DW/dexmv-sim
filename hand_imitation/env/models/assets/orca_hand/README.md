# ORCA Hand Asset Link

`orcahand_description` is a symlink to the PPO-side ORCA asset tree:

`Aero-Hand/sim_rl/mujoco_playground/mujoco_playground/_src/manipulation/orca_hand/xmls/orcahand_description`

This lets DexMV scripts refer to the ORCA model through the same asset namespace
as `adroit/` without storing a second 205 MB copy of the meshes.

Use the right-hand v2 scene as:

`orca_hand/orcahand_description/v2/scene_right.xml`

