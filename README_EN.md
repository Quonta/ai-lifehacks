# ai-lifehacks

Practical methods and workflows for using AI effectively.

[日本語版](README.md)

## Contents

### Multi-Quonta System

A method for reviewing outputs from multiple AI threads with different contexts.

#### Details

When a task reaches a stopping point, the result is reviewed in another AI thread.

Even with the same model, different conversation histories can produce different feedback, perspectives, and improvements.

I usually use around three threads.

It can be used for emails, notes, writing, plans, and design ideas.

### Triangular Workflow

A cyclical workflow that divides AI roles into Design, Test, and Review.

#### Details

For programming or other creation tasks, AI threads are divided into three roles: Design, Test, and Review.

The Design thread creates the work.  
The Test thread tries it and checks the result.  
The full result is then passed to the Review thread.

The Review thread examines the outcome from both human and AI perspectives, writes notes for improvement, and returns them to Design for the next cycle.

This process is repeated many times.
