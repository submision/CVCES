
This project gives 5 case data from the experimental part of the article Enabling Effective Requirements Compositional Verification for Complex Embedded Systems.

Sequence diagrams and external entity model libraries are used as inputs in the article, and the outputs of each step are requirement dependencies, subsystem architectures, and executable subsystem models according to the methodological framework of the three steps in the article.

<h2>Step 1 Identifying sub-requirements dependencies</h2>
    Extracting these dependencies requires a comprehensive understanding of the relationships between requirements and data, as well as between requirements and devices. Concurrently, it’s essential to eliminate any mutual dependencies that should not occur. This step will result in a set of requirements dependencies in terms
of a requirements dependency diagram.

<h2>Step 2 Generating architectures of verification subsystems</h2>
    The purpose of this step is to clearly define the constituents of the verification subsystems based on the requirements dependencies. Considering the architecture of embedded systems, these components include software components that are interdependent due to their dependencies, device components required by these
software elements, data storage components, and connectors that encapsulate the information of interactions among various components.

<h2>Step 3 Assembling and verifying executable verification subsystems</h2> 
    This step is to generate a set of executable verification subsystems in terms of NTA, and verify them respectively. The verification subsystems, assembled from the precise elements of NTA, can undergo formal verification for distinct properties via the UPPAAL platform. The results of each verification
subsystem are synthesized to obtain the final verification outcome.

<h2>Description of experimental data</h2>
    There are two folders, input and output, under each case folder. The input folder contains the Sequence Diagram folder and the External Solid Model Library folder. The output folder contains the requirement dependencies identified as a result of the output of step 1, the subsystem architecture represented as a component diagram as a result of the output of step 2, and the executable subsystem model assembled as a result of the output of step 3.

- Input
    - Sequence Diagram
    - External Entity Model Library
- Output
    - Step1-Output-Requirements Dependencies
    - Step2-Output-Architectures of Verification Subsystems
    - Step3-Output-Executable Verification Subsystems


