# Ground-Based Astronomical Observatory

This SysML model demonstrates the use of MBSR on baselined system requirements, which are sourced from the [Thirty Meter Telescope open-source SysML model](https://github.com/Open-MBEE/TMT-SysML-Model).

## Usage

First, ensure that the TMT SysML model has been pulled locally:

```sh
git submodule update --init --force Examples/Ground-Based_Astronomical_Observatory/TMT-SysML-Model
```

Next, you will need to "share" the package containing the TMT model. Open the `TMT-SysML-Model/TMT-2024x.mdzip` in Cameo Systems Modeler, and select the "No to all" button to ignore the missing libraries. Once open, right-click the "TMT" package directly under the top-level "Data" model package, in the right-click context menu go to "Project Usages"", and select "Share Packages". In the left pane of the Shared Packages modal window, scroll down and double-click the "TMT" package to add it to the selected packages, then click the "OK" button. A warning message will appear, select the "Stop sharing" button. Save and close the `TMT-2024x` project. Continue to ignore warnings about missing libraries, since all we need are the requirement elements from the model.

Now that the TMT package is shared, open the `Ground-Based_Astronomical_Observatory.mdzip` in Cameo Systems Modeler or equivalent, 2024x or newer. This example model imports `TMT-SysML-Model/TMT-2024x.mdzip` and contains model element relationships to retain traceability. Use the default Content Diagram to begin navigating the MBSR example model.
