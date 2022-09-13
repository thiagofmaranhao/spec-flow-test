# spec-flow-test
Spec Flow Test

## Living Documentation

1. Install the LivingDoc CLI as a global dotnet tool
    ```
    dotnet tool install --global SpecFlow.Plus.LivingDoc.CLI
    ```
1. Navigate to the output directory of the SpecFlow project
1. Run the LivingDoc CLI by using the below command to generate the HTML report.
    ```
    livingdoc test-assembly SpecFlowCalculator.Specs.dll -t TestExecution.json
    ```
1. Open the generated HTML with your favorite browser. The HTML file is stored in the same folder as the output directory of the SpecFlow project.