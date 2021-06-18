# runbook

Use a Runbook to build and execute runbooks that can help IT staff to solve common operational problems. Runbook Automation can automate procedures that do not require human interaction, thereby increasing the efficiency of IT operations processes. Operators can spend more time innovating and are freed from performing time-consuming manual tasks.

## What is a runbook?

A runbook is a controlled set of automated and manual steps that support system and network operational processes. A runbook orchestrates all types of infrastructure elements, like applications, network components, or servers.

## Types of runbook

### Manual runbooks

Steps describe the exact procedure that an operator must follow. The operator uses standard tools, which can be accessed from their working environment.

### Semi-automated runbooks

Each step describes exactly what an operator must do. Additionally, the operator can run an automated task on a target system.

### Fully automated runbooks
The runbook runs automatically without operator interaction. 

## Lifecycle of a runbook

Runbooks start as documented procedures on a piece of paper that can become fully automated procedures.

The following steps outline the process of moving from documented procedures to fully automated runbooks:

1. Transfer your documented procedures into a runbook.

2. Assess the runbook and gather feedback.

3. Create improved versions based on the feedback. With each new version, improve the success rate.

4. Investigate which runbooks are suitable for automations. What steps can be put into an automated procedure? 

5. Provide a new version with automated steps and see how it runs.

6. Continue to provide more automations until all steps are automated. Run runbooks that are started by a trigger.

## Runbook example

1. Open a PuTTY session to host ibmrbalx49.

2. Enter the following command to navigate to the file system that is full:

    > `cd`

3. Enter the following command to identify core files in the file system:

    > `find . -name core.*`

4. Enter the following command to identify large files in the file system:

    > `du -hsm . | sort –nr`

## Acknowledgments

* [IBM Runbook Automation](https://www.ibm.com/docs/en/runbook-automation) 
* [Documentation Writing for System Administrators](https://www.usenix.org/short-topics/documentation-writing-system-administrators) - by Mark C. Langston
* [CONTRIBUTING.md](https://github.com/angular/angular/blob/master/CONTRIBUTING.md) - Contributing to Angular.

## Authors

* **Wai Mun** - *Initial work* - [iworkforthem](https://github.com/iworkforthem)

## License

This project is licensed under the Apache License License - see the [LICENSE.md](LICENSE.md) file for details
