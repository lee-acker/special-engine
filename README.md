# Graphite POC Project

This project serves as a Proof of Concept (POC) to demonstrate the value and capabilities of Graphite for team collaboration and code management.

## Project Overview

This is a simple task management application built with React and TypeScript. The application itself is intentionally straightforward to allow us to focus on demonstrating Graphite's features rather than complex application logic.

## Key Features to Demonstrate

1. **Stack-based Development**
   - Creating and managing stacks of changes
   - Dependencies between changes
   - Reviewing multiple changes together

2. **Code Review Workflow**
   - Submitting changes for review
   - Reviewing code in context
   - Providing feedback and suggestions

3. **Branch Management**
   - Organizing work into logical units
   - Managing dependencies between changes
   - Clean git history

4. **Integration Capabilities**
   - GitHub integration
   - CI/CD pipeline integration
   - IDE integration

## Getting Started

1. Install dependencies:
   ```bash
   npm install
   ```

2. Start the development server:
   ```bash
   npm start
   ```

## Development Workflow

This project will be used to demonstrate a typical development workflow using Graphite:

1. Create a new stack for a feature
2. Make changes across multiple commits
3. Submit for review
4. Address feedback
5. Merge changes

## Project Structure

```
src/
  ├── components/     # React components
  ├── types/         # TypeScript type definitions
  ├── hooks/         # Custom React hooks
  ├── utils/         # Utility functions
  └── App.tsx        # Main application component
```
