# Eiffel
The Eiffel framework enables technology agnostic enterprise scale continuous integration and delivery with maintained scalability, flexibility and traceability. Eiffel is based on the concept of decentralized real time messaging, both to drive the continuous integration and delivery system and to document it.

This repository contains the Eiffel framework vocabulary, descriptions, guides and schemas along with links to relevant implementation repositories.

__IMPORTANT NOTICE:__ The contents of this repository currectly reflects a __DRAFT__. The Eiffel framework has been used in production with Ericsson for several years to great effect. What is presented here is a revision and evolution of that framework - an evolution that is currently ongoing. In other words, anything in this repository should be regarded as tentative and subject to change. It is published here to allow early access and trial and to solicit early feedback.

## Licensing and Contribution
* The contents of this repository are licensed under the [Apache License 2.0](./LICENSE)
* Contributors understand and accept that all contributions are made to this repository with the explicit understanding that contributors only contribute their original work and transfer all rights, privileges and copyrights associated with these contributions to Ericsson AB.

## Contents
1. Introduction
   1. Why Eiffel?
   1. What is Eiffel?
   1. Who Developed Eiffel?
   1. Who Should use Eiffel?
   1. How do I Get Started?
   1. How is Eiffel Technology Agnostic?
   1. How does Eiffel Achieve Scalability?
   1. How does Eiffel Achieve Flexibility?
   1. How does Eiffel Achieve Traceability?
   1. How do I Make Sense of Events?
1. Eiffel Syntax and Usage
   1. Eiffel Event Design Guidelines
   1. Notes on Custom Events
   1. [Event Structure](./eiffel-syntax-and-usage/event-structure.md)
   1. [The Meta Object](./eiffel-syntax-and-usage/the-meta-object.md)
   1. [The Links Object](./eiffel-syntax-and-usage/the-links-object.md)
   1. User Examples
1. The Eiffel Vocabulary
   1. [EiffelActivityQueuedEvent](./eiffel-vocabulary/EiffelActivityQueuedEvent.md)
   1. [EiffelActivityDequeuedEvent](./eiffel-vocabulary/EiffelActivityDequeuedEvent.md)
   1. EiffelActivityStartedEvent
   1. EiffelActivityFinished
   1. EiffelArtifactCreatedEvent
   1. EiffelConfidenceLevelModifiedEvent
   1. EiffelArtifactPublishedEvent
   1. EiffelDocumentationCreatedEvent
   1. EiffelEnvironmentDefinedEvent
   1. EiffelCompositionDefinedEvent
   1. EiffelSourceChangeCreatedEvent
   1. EiffelSourceChangeSubmittedEvent
   1. EiffelFlowContextDefinedEvent
   1. EiffelTestCaseStartedEvent
   1. EiffelTestCaseFinishedEvent
   1. EiffelTestSuiteStartedEvent
   1. EiffelTestSuiteFinishedEvent
   1. EiffelTestExecutionRecipeCollectionCreated
   1. EiffelAnnouncementEvent
   1. EiffelConfigurationChangedEvent
1. Implementations
   1. Event Persistence
   1. Event Aggregation and Analysis
   1. Activity Orchestration
   1. Event Transport and Routing
   1. Event Dispatch
   1. Visualization