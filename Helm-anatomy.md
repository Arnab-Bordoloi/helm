|File/ Directory|Purpose|
| :---: | :---: |
|templates|Helm will render these into K8s manifests|
|charts|Holds subcharts & dependencies for the top level Helm chart|
|Chart.yaml|Holds metadata about chart & a list of its dependencies|
|values.yaml|Helps to parameterize values so that templates can be reused|
|.helmignore| Similar to .gitignore|
|NOTES.txt|Can document notes about the chart|