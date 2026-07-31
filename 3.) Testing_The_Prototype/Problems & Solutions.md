# PROBLEMS:

After testing the two prototypes, I identified several practical issues that needed to be solved before the final design could work reliably. These problems included electrical connection failures, probe pin retention, and poor print orientation for wire routing.

- I initially attempted to daisy-chain the wires and secure them with super glue, but the adhesive prevented proper electrical contact and caused intermittent failures.
- The connector pins for the button probes were too loose in the shaft assembly, leading to unreliable connections and difficult reassembly if a pin became unplugged.
- The print orientation in the slicer created support material inside the internal shafts, which obstructed wire routing and required tedious cleanup to remove.

## SOLUTIONS:

After identifying the issues, I implemented practical fixes to improve assembly reliability and simplify the build process. Each solution addressed a specific failure mode and helped make the prototype more robust for future iterations.

- Re-oriented the model in the slicer to avoid support structures inside the shafts and reduce cleanup.
- Purchased longer wires to eliminate daisy chaining and reduce the risk of loose or intermittent connections.
- Used short strips of electrical tape to secure the pins together and keep them from slipping apart.
- Enlarged the internal shafts in the final model to improve wire routing and ease component installation.