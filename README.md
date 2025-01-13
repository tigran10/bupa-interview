# Overview


This repository contains the skeleton of a Task Scheduler system implemented in Java. The project is set up with Gradle to manage dependencies and ensure smooth builds. Your task is to complete the implementation of the `Task` and `TaskScheduler` classes based on the requirements outlined in the User Story section below.

The project is intentionally left incomplete to allow you to demonstrate your skills in:


1. Clean code principles.
1. Test-driven development (TDD).
1. Well-thought-out design.


No code generation tools are allowed; you’re welcome to use online resources or discuss ideas, but the code should reflect your own work and thinking.


User Story: Task Scheduler System

As a developer:

I want to build a Task Scheduler that allows tasks to be scheduled, rescheduled, executed at a specific time, and canceled. This system should handle multiple tasks efficiently, ensure thread safety, and provide a clean API for managing tasks.

Requirements

1. Task Class:
	* Represents a task with the following attributes:
	* taskId : A unique identifier for the task.
	* runAt: The scheduled execution time.
	*	action: The task logic to execute.
	*	Must include getter methods for all fields and proper validation in the constructor.
	
1.	TaskScheduler Class:
	*	Manages the `scheduling`, `execution`, `rescheduling`, and `cancellation` of tasks.
	*	Ensure tasks execute only at or after their scheduled time.
	*	Allow concurrent access.
1. Testing:
	*	Implement unit tests to validate the behavior of the scheduler using TDD principles. lude tests for:
	*	Scheduling tasks.
	*	Rescheduling tasks.
	*	Canceling tasks.
	*	Handle edge cases
