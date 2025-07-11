Coming Soon™


Ore conversion recipes for the Converter that go "backwards" in the base-game conversion order, with a twist.

Unlocked in T9 in a separate milestone

All Reverse Conversion recipes require a new "Excited SAM" item (Reanimated SAM + Excited Photonic Matter) instead of Reanimated SAM and return Excited Photonic Matter as a byproduct.

Alone, these recipes allow converting any raw resource to any raw resource, except SAM.
Combined with Somersloops, you can effectively convert SAM to any other raw resource. Slooping the Reverse recipes requires finding a way to deal with the now-excess photonic. (current intended solutions are using it for the rest of your base or wastefully sinking excited SAM)

TODO

- Balance + practicality testing. Currently:
  - Same SAM cost
  - Half the speed of the vanilla recipe
  - Same recipe variable power bounds
- Split Recipe_Bauxite_From_Uranium_C, Recipe_Iron_From_Sulfur_C, Recipe_Limestone_From_Coal_C into 1/2 batch to not stall the machine. This makes their power efficiency and Slooped-machine-utilization worse though.
- Item belt/ground appearance for Excited SAM (it will reuse reanimated sam mesh and base its material with knobs turned but I need to go rip the mesh)
- Nitrogen Gas solid item to avoid voiding the packages for nitrogen gas. Current plan is X excited photonic + 1 trigon -> 500 casing, X dark matter in Quantum Encoder, where 1 casing holds 1000 units (1 cubic meter) of nitrogen gas.
- Current Photonic Matter without sloops is break even. Can fluid system be trusted with that? Maybe make it so that pre-sloop Reverse recipes require a slight Photonic Matter top-off instead of a break even?
