# EXORDIA-system
An Explanation of Reasoning through Dialogical Argumentation (EXORDIA) system using argumentation-based explanations to help experimenters better understand reasoning results. The tool also allows experimenters to easily explore different argumentative explanations for selected hypotheses of a given query answer.

# Supplementary material
All materials that we use in a user study can be found in the MATERIAL folder. This includes:
- Guidelines explaining teriminologies used in the EXORDIA system.
- Videos show how participants use the EXORDIA system.
- Data was used in tasks.
- Task questionnaire file and a document of answers for the task questionnaire.
- Post-study questionnaires.
- Excel file of results
- SPPS file shows the results of the user study.

# Requirements
- This is a Java implementation: Full java 21 support, java 21 is a requirement.
- Graphviz 13.0.1
- Maven
- It currently supports: DLGP input that supports Datalog+-, logic programming facts.
- For OWL2 and RDF/XML in Turtle format, you need to run the following command to convert into DLGP format:

      java -jar owl2dlgp-*.jar -f ./example-owl.ttl -o ./example.dlgp

- Or download the owl2dlgp tool to use:
Link: https://graphik-team.github.io/graal/downloads/owl2dlgp

# Useage
The code has been made available for reproducing the results we show in our paper. To make sure that it is possible we would refer to the CODE folder. There are two options:

1. Option1: Double-click on EXORDIA.jar to run the tool.

2. Option 2: Perform the following steps:
- To use, create a location where you store the DLGP. You can store datasets anywhere.
- Clone a repository to your local computer using a Github link.
- Go to the directory where your source code is, i.e., .\SAF-Argumentation\code
- Package the project by using the following command:
  
      mvn clean install

  

  
