# project

[Social Media usage and Psychological Effects] Data Science Design Document


## Version History

Date	              Comment	  Author(s)	    Version

30 October 2020		            An Yee Tan	  1

## 1. Introduction

This document details the purpose, methodology, and application of data science within the link between social media usage and psychological effects. Section 2 outlines the business objective addressed by the data science work, and defines the scope of the effort. Section 3 describes the data collected and utilized during analysis. Sections 4, 5, and 6 detail the methodologies employed, why they were selected, and how they are used and tuned (Section 4), trained (Section 5), and tested (Section 6). Finally, [any further sections that are added]

## 2. Problem Statement: Data Science Scope
### Business Case
The purpose of the project is to benefit people to understand the link between usage of social media, the content they are exposed to, and the psychological effects that may arise. 

We are building this because there are many kinds of content on the social media, where different kinds of contents may result in different purpose and effects. For instance, infographics about certain topics may be educational, while photos about personal life may just merely for sharing with friends. 

We wish to benefit the users of social media, specifically Generation Z. We hope that our findings will allow people to be more aware of their usage of social media, especially the content they are exposing to. Hopefully, this research will be able to allow people to be more conscious and more objective when using social media. 

I would define success as being able to find findings where there is a link between the usage of social media, the content that they are exposed to (if possible), and its psychological effects like depression or anxiety. 

The purpose of the project from a functional benefit perspective. Why are we building this? Who will benefit? And what benefit will they receive? How do you define success? The focus here should be on data science specifically, not just the project as a whole.

### Key User Stories
(should we interview the focus group? or getting what you’ve found online?)
A typical project will have a couple key user stories that describe the targeted data science outcome. A User Story captures what a user does or needs to do as part of their work. Each User Story consists of a short description (no more than a couple sentences) written from a user's point of view, with natural language. Unlike the traditional requirement capturing, User Stories focus on what the user needs instead of what the system should deliver. This leaves room for further discussion of solutions and the result of a system that can really fit into the customers' business workflow, solving their operational problems and most importantly adding value to the organization.

## 3. Data
[Dataset 1]
Description of the source of the dataset and its content.

Property	Description

Name	A human-readable label for the data asset.

Description	A long-form description of the data asset. A complete description captures the contents of the asset, the community it serves, and the information domain it contains.

Data Source	The data source that stores, owns, or transfers the data asset. The operating source should be the ID of the Data Source in the Data Source Catalog.
Point(s) of Contact	Name and contact information for a point of contact knowledgeable about details of the data asset. 

Format	The way in which the data in encoded for storage in a computer file. Examples include text file, pdf, Access database. For a list of file formats see https://en.wikipedia.org/wiki/List_of_file_formats

Structure	Structure of the data within the payload. Options will depend on data format, but typical structures are records, tables, files, and arrays.

Schema	Some data types have a schema, a standard definition for its contents. For a table, this will include the table’s column (field) names, the fields’ data types (boolean, date, datetime, string/text, integer, float, etc.), and – if available – descriptions, examples, and format standards of the fields. Types may be specific to the data format. An example Data Asset schema for a table is given below.

Sample Data	How to access a sample of the data if available.

Volume	Total expected volume (storage space) of the data

Velocity	Data streaming velocity (ingest availability), measured in data size per time (e.g., MBs/sec)

Refresh Rate	The frequency at which the data is updated, from real-time to periodic.

Location	Physical location/access point of the data. Could be a URI for a data access endpoint or a file path on a machine.

Data access mode	Mode to access the data. Examples include web applications, APIs, raw file endpoint, etc.

Access Restrictions	The types of access restrictions that exist on the data, and what types of models are required? Examples may include impact level, PII, and security level.

Constraints	Constraints that must be respected in managing the data.

Assets Derived From	A list of assets that this data asset is derive from, including those both internal and external to the Data Source.

Notes	Any ancillary notes needed for proper utilization of the data asset.

### 4. Analytic Methodologies

This section details the methodologies proposed to be implemented during development. This section can either be organized by type of methodology or the user story that they address. 

### [Method/Model 1]

Model Selection
A description of the model and why it was selected.
Model Inputs
The inputs to the model are enumerated.

Name	Data Type	Description
		
Model Outputs

Name	Data Type	Description
		
Tunable Hyperparameters

Name	Data Type	Description
		
### Alternative Methods/Models

A short description and list of alternative methods that may be utilized instead if the primary chosen models above do not meet requirements.

## 5. Training & Tuning

If model training is required, this section documents how models are trained. Included are descriptions of how the model is trained, what the training data used is, and how frequently it is trained. 

## 6. Testing

This section describes the tests that are executed that ensure the quality of the data science work. This may include performance, stress, unit, integration, and other forms of testing.

### Performance & Stress Tests
In this section, the main metrics that we are using to measure performance is the time variable and the trigger event (or content) that we are able to obtain from the datasets. 

### Performance requirement..? 
A description of how performance tests are performed. What metrics are used to measure performance? What are the performance requirements?

### Test Data
A description of the data used for testing and validation.

### Unit Tests

### Integration Tests
