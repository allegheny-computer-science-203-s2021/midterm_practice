# CMPSC 203 Midterm Sample Questions

Here are examples of the kinds of questions that might be asked. This is not intended to be a sample exam; it does not cover all topics you might be asked a question about, it is just providing some example questions.


1. What are the five core stages of the software development life cycle?


2. For each of the five stages, describe what occurs, what tools/techniques are available to assist with the stage, and the outcome/deliverable.


3. Briefly discuss tasks and the relationship between tasks and user stories and how a team can estimate the time it will take to complete a user story.


4. The process of gathering the software requirements from customer, analyzing and documenting them is known as *software engineering*. Mark the correct answer with an X inside the brackets.

  	- [ ] True
  	- [ ] False
  

5. What estimate should the development team go with if a user story estimate and a task estimate don't agree and why?


6. Describe the three topics the development team discusses during a standup/scrum meeting.


7. What are two main causes of complexity? Mark the correct answer with an X inside the brackets.

  	- [ ] Obscurity and modularity
  	- [ ] Change amplification and cognitive load
  	- [ ] Obscurity and dependencies
  	- [ ] Dependencies and modularity


8. Consider a task of creating a [Door Dash](https://www.doordash.com/) type of a software.

  	(a) Give an example of a requirement for this system.
  
  	(b) Convert this requirement to a user story. Does it satisfy INVEST criteria?
  
  	(c) Convert this user story to specific tasks.
  
  	(d) For one of the tasks, specify the priority and an estimate. Justify the answers given here.
  
  	(e) Assuming only the task listed above, calculate velocity. Provide all assumptions made, including but not limited to the number of work days and team size. 


9. Consider the following code snippet:

  ```
  public class Employee { 
  	public string name;
  	public string address;
  	...
	private void setName (String newName) { ... }
	private void getName () { ... }
	...
  	public void ComputePay() { ... }
  }
  ```

  Using SRP analysis, identify one violation to this principle. Explain your answer.
  
  
10. Consider the following code snippet:

   ```
   def test_scan():
    # pylint: disable=len-as-condition

    assert len(compute_tf_cookbook.words) == 0
    compute_tf_cookbook.scan()
    assert len(compute_tf_cookbook.words) != 0
  ```
  
  What is this type of method called? What is its general purpose? How is it helpful? What is its one downside?
   