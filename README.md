# PIPEThesisSettings #

This repository contains all the settings for reproducing the results described in my masters year thesis.

Results may be reproduced as follows:

## QAPlugin results ##
1. Install the QAPlugin in IntelliJ.
2. Open the relevant project with IntelliJ.
3. Select Tools - QAPlug - Analyse.
4. Select `...` next to 'Run with chosen profile'.
5. Import `profileCodingRules.xml` under IDEProfiles.
6. Hit OK and run results.


## Stan4J ##
1. Make jar using maven command line options.
2. Open Stan4J.
3. Select File - New.
4. Give the project a name.
5. Select `class` as the level of detail.
6. Add the project jar.
7. Press finish.
8. On the composition graph right click and select partition.
9. Tangle graph used in report will now appear.

## Metrics Reloaded ##
1. Open the relevant project with IntelliJ.
2. Install the Metrics Reloaded plugin via Preferences - Plugins - Browse Repositores.
3. Run the Javadoc metrics by via Analyze - Calculate Metrics and selecting Jacadoc coverage metrics as the metrics profile and uncheck include test sources. Note leave the metrics scope set to the whole project.
4. Click on the projects metrics tab for project percentages.
