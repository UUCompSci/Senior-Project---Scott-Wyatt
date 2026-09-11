# AI Repository Assistant

## Overview

The goal of this project is to build three AI agents that help developers **understand, review, and make changes to software repositories**.

Each agent will have a specific purpose, while sharing common functionality for connecting to GitHub, reading repositories, and understanding the codebase.

---

## Epic 1 — AI Agent 1: Repository Analysis

The Repository Analysis agent will help developers quickly understand an unfamiliar GitHub repository.

It will analyze project files and configuration to identify the technology stack, explain the folder and file structure, and provide a high-level overview of the application's architecture.

### Story — Repository Access and Scanning

* Task — Connect the agent to GitHub
* Task — Access GitHub repositories
* Task — Scan repository files
* Task — Collect project configuration information
* Task — Filter unnecessary files

### Story — Technology Stack Detection

* Task — Identify programming languages
* Task — Identify frameworks and libraries
* Task — Identify build tools such as Maven
* Task — Identify databases and data technologies
* Task — Identify APIs and communication technologies such as REST and SOAP/XML
* Task — Identify testing frameworks

### Story — Repository Structure Analysis

* Task — Analyze the folder structure
* Task — Identify important files
* Task — Determine the purpose of major folders
* Task — Identify major application components
* Task — Analyze relationships between project components

### Story — Architecture Overview

* Task — Generate a high-level application overview
* Task — Explain how major components work together
* Task — Identify important architectural patterns
* Task — Generate an easy-to-understand architecture summary

### Story — Agent 1 Testing

* Task — Test against multiple GitHub repositories
* Task — Verify technology stack detection
* Task — Verify folder and file explanations
* Task — Validate architecture summaries
* Task — Improve accuracy and reliability

---

## Epic 2 — AI Agent 2: Code Review

The Code Review agent will analyze source code and identify potential problems and areas for improvement.

It will build on the repository analysis functionality from Agent 1 and combine automated analysis with AI-based code review.

### Story — Source Code Analysis

* Task — Analyze source code
* Task — Identify potential bugs
* Task — Identify poor coding practices
* Task — Identify maintainability issues
* Task — Identify potential architectural problems

### Story — Security Review

* Task — Analyze code for potential security issues
* Task — Identify common security risks
* Task — Review potentially unsafe code patterns
* Task — Generate security-related findings

### Story — Testing Review

* Task — Identify existing tests
* Task — Identify areas without sufficient test coverage
* Task — Identify missing tests
* Task — Review test quality
* Task — Recommend additional testing where appropriate

### Story — AI Code Review

* Task — Use repository context during code review
* Task — Analyze relationships between files and components
* Task — Explain why an issue may be a problem
* Task — Provide potential recommendations
* Task — Avoid unnecessary or low-value warnings

### Story — Review Findings

* Task — Assign severity levels
* Task — Assign confidence levels
* Task — Organize findings by importance
* Task — Generate a clear review summary
* Task — Provide recommended improvements

### Story — Agent 2 Testing

* Task — Test against multiple repositories
* Task — Validate identified issues
* Task — Measure false positives
* Task — Improve review accuracy
* Task — Refine severity and confidence ratings

---

## Epic 3 — AI Agent 3: Code Changes

The Code Changes agent will allow developers to request changes to a repository and have the AI safely implement those changes.

Before making significant changes, the agent will analyze the repository, determine what needs to change, and explain its proposed approach to the user.

### Story — Change Request Analysis

* Task — Accept a user's change request
* Task — Analyze the repository
* Task — Identify affected files
* Task — Identify affected components
* Task — Determine dependencies between changes
* Task — Create a proposed change plan

### Story — Change Approval

* Task — Explain proposed changes to the user
* Task — Identify potentially risky changes
* Task — Determine when user approval is required
* Task — Request approval before significant changes
* Task — Continue only after approval when required

### Story — Safe Code Changes

* Task — Create a separate Git branch
* Task — Create an isolated working environment
* Task — Implement the requested changes
* Task — Prevent accidental changes to the original branch
* Task — Handle failed or incomplete changes safely

### Story — Automated Testing

* Task — Identify appropriate tests to run
* Task — Run existing project tests
* Task — Analyze test results
* Task — Report failed tests
* Task — Use test results to identify potential problems with changes

### Story — Change Report

* Task — Identify files that were modified
* Task — Summarize the changes
* Task — Explain why the changes were made
* Task — Document test results
* Task — Generate a Markdown change report

### Story — Agent 3 Testing

* Task — Test simple code changes
* Task — Test larger code changes
* Task — Test potentially risky changes
* Task — Verify branch isolation
* Task — Verify automated testing
* Task — Validate generated change reports
