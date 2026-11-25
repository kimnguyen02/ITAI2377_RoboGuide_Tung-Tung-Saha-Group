# Team contribution verification 

## José Tuozzo — System Architecture, Integration & Evaluation

Main responsibility: Make sure all project components work together as one complete system.

Specific responsibilities:
- System architecture: Design the overall system structure and determine how data preprocessing, retrieval, evaluation, and the assistant interact.
- Corpus and schema integration: Coordinate the integration of the prepared knowledge base into the system and ensure that document records follow a consistent data structure.
- Pipeline integration: Connect the data preparation, retrieval, and response components into a functional workflow.
- Retrieval evaluation: Compare baseline and hybrid retrieval methods using metrics such as Recall@3 and MRR@5.
- End-to-end testing: Test the complete workflow, from submitting a user question to receiving an answer with supporting references.
- Technical documentation: Review and edit technical documentation, architecture descriptions, and final project materials.

## Kim Nguyen — Data Acquisition, Preprocessing & Quality Assurance

Main responsibility: Build and maintain the reliable knowledge base that RoboGuide uses to answer questions.

Specific responsibilities:
- Official-source collection: Identify and collect relevant information from official SunFounder PiDog documentation, FAQs, GitHub repositories, and Robot HAT documentation.
- Source manifest management: Record source URLs, document titles, source IDs, and provenance information to maintain traceability.
- Hardware version tagging: Identify and label documentation according to compatible PiDog hardware versions and subsystems.
- Data parsing and cleaning: Extract useful technical information, remove unnecessary website content, standardize text, and organize records into a consistent format.
- Duplicate detection: Identify repeated documentation and remove duplicate records.
- Conflict review: Check for inconsistent or conflicting instructions across sources and flag information requiring further verification.
- Data quality validation: Check for missing fields, incorrect metadata, invalid records, and source traceability.

## Huu Huynh — AI Retrieval, Response Generation & User Interface

Main responsibility: Develop the mechanisms that allow RoboGuide to understand questions, find relevant information, and communicate answers to users.

Specific responsibilities:
- Embedding development: Explore and implement text embeddings to represent questions and documentation as numerical vectors.
- Retrieval and indexing: Develop the document retrieval and indexing mechanisms to identify relevant technical information.
- Entity and feature extraction: Identify important technical entities, API names, error messages, and other features that improve retrieval relevance.
- Prompt engineering: Design prompts and response instructions to help the assistant provide relevant, evidence-grounded answers.
- Response generation: Develop the answer-generation workflow, including source references and appropriate abstention when evidence is insufficient.
- User interface development: Create the interface through which students submit questions and receive answers.
- User testing: Test the assistant with representative PiDog questions and review usability, response relevance, and potential issues.

