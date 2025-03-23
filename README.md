# Product Overview

## Platform Vision

This project is a white-label video course platform designed to provide independent teachers with a flexible and customisable solution to deliver online education. The platform allows teachers to create, organise, and deliver courses to students in an integrated and scalable way, while students can access the content and their progress at their own pace, and engage in a guided learning experience.

As a white-label SaaS, the platform is built to be easily customisable, allowing each independent teacher to manage their own space (Tenant) with their own branding and content.

The first Tenant of this product is the PHP Training platform.

## **Domain-Driven Design Approach**

This platform is built following **Domain-Driven Design (DDD)** principles to ensure a well-structured and maintainable system. By focusing on the **business domain**, we aim to create a model that accurately reflects how teachers and students interact with courses, topics and content.  

Key aspects of our DDD approach:  
- [**Ubiquitous Language**](./1.domain/1.ubiquitous-language) – Establishing a shared terminology to align developers and domain experts.  
- [**Domain Scenarios**](./1.domain/2.domain-scenarios)  – Summarising the main scenarios from our real-domain-world which we want to cover in our software.
- [**Domain Model**](./1.domain/3.domain-model)  – Structuring business logic to mirror real-world teaching workflows.

By leveraging DDD, we create a **scalable and adaptable architecture** that evolves alongside the needs of independent teachers and students.  

## MVP Goals

The primary goal of the Minimum Viable Product (MVP) is to provide a functional, simple, and scalable platform for independent teachers and students. The MVP will focus on the following core features:

### Teacher Features:
- **Course Creation**: Teachers can create and organise Courses, including adding Topics and Contents.
- **Content Management**: Teachers can add various types of Content (text, video, activity, knowledge assessment) to Topics.
- **Course Dependency Management**: Teachers can define dependencies between Topics to guide Students in their learning path.

### Student Features:
- **Course Enrollment**: Students can sign up in a specific Tenant platform and enroll in a Course.
- **Content Access**: Students can access all content for the Course from day one and interact with the materials (e.g., watching videos, reading text, completing activities).
- **Interaction with Content**: Students' interactions with the Content (e.g., watching videos, completing assessments) will be recorded as logs in order to track their studies.

### Certification:
- **Certificate Request**: When a Student fulfils the Course requirements, they will have the option to request a Certificate. Teachers will manually review requests and upload Certificates as PDFs or other formats.
- **Manual Certification Process**: Teachers will manage Certificate issuance manually, maintaining full control over the Certificate process.

### Interaction & Communication:
- **Discord**: All communication between Students and Teachers will be handled through a dedicated Discord server for each teacher.

### Data Analytics (Future Work):
- The platform will collect interaction data for analysis to define the criteria for issuing Certificates and improving Content delivery.
- Analytics and progress tracking will be implemented in future updates.

## Decisions for the MVP:
- **Manual Teacher Account Creation**: Teachers will be added manually to the platform to create their Courses and manage their Content.
- **Multi-Tenant Architecture**: Each independent Teacher will have their own Tenant within the platform, where they can control their Courses, Topics, and Content. Tenants will be initially instantiated manually.
- **Student Enrollment**: Students can sign up for each Teacher’s platform and access the Teacher’s Courses.

## **MVP Architecture Overview**  

The platform's architecture is designed to support a **scalable, modular monolith** while ensuring flexibility for future growth. The **MVP Architecture** document details about our choices in terms of key technologies, infrastructure setup and deployment strategies.  

📄 **For a detailed breakdown, see:** [Architecture Overview](./2.architecture/1.architecture)  

## Future Vision

After the MVP, future updates will focus on expanding features such as automated Certificate generation, Student interaction enhancements, and advanced data analytics for performance tracking and reporting. The platform will continue to evolve based on feedback and the needs of the Teachers and Students using it.

## Target Audience

- **Independent Teachers**: Educators who wish to offer online courses and require an easy-to-use platform to manage their content and students.
- **Students**: Individuals looking for flexible learning opportunities across a wide range of Topics and Courses.