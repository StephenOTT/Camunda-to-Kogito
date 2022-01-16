# Camunda-to-Kogito


# Variables

Camunda: https://docs.camunda.org/manual/latest/user-guide/process-engine/variables/

Kogito: https://docs.jboss.org/kogito/release/1.15.0/html_single/#con-bpmn-variables_kogito-developing-process-services

Basically the same structure of local and process variables.  Kogito has Variable Labels which is very useful!



# REST API

Kogito has API Generation per workflow with OpenAPI spec


# User Tasks

Camunda and Kogito bpth have comments and attachment concepts

# Startup time

looks like kogito is faster to startup

Can compile kogito to GraalVm.


# Process History

Camunda has History Service (DB backed)

Kogito has the Index Service: Multiple backend options


# Modeler

Camunda has a much cleaner modeler

Kogito modeler has some bugs to deal with.  Look and Feel is subpar compared to Camunda (even with Camunda Modeler's bugs and issues)

Kogito is embracing VS-Code development which is a something Camunda has not embranced.  Camunda provides a ~plugin for VS-Code.


# Locking

Both support locking.  Kogito docs are very light on details: https://docs.jboss.org/kogito/release/1.15.0/html_single/#_enabling_optimistic_locking_with_persistence


# UIs

Camunda has the Tasklist, Cockpit and Admin UIs

Kogito has Task console, Management Console, Sandbox, and various other sub UIs that can be optionally combined.  

Kogito connects with OIDC for auth, and Camunda requires custom setup.


# Decision Management

Camunda has DMN

Kogito has DMN and Drools + TrustyAI and some other predictive modeling capabilities
