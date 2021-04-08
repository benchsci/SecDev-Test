# The Security Engineering Challenge
Applicants to the BenchSci Senior Security Engineer role must complete the following challenge, and submit a solution prior to the interviewing process. This will help the interviewers assess your strengths, and frame the conversation through the interview process. Take as much time as you need, however we ask that you not spend more than a few hours. 

We prefer that you use Python and/or Bash; however, this is not a hard requirement.

## Submission Instructions
1. Fork this project on github
1. Complete the project as described below within your fork
1. Push all of your changes to your fork on github and submit a pull request against benchsci/SecDev-Test. 
1. You should also email your recruiter to let them know you have submitted a solution. Make sure to include your github username in your email (so we can match applicants with pull requests).

## Project Description
Leverage the [MITRE ATT&CK framework](https://attack.mitre.org/wiki/Main_Page) and pick 1 attack technique. MITRE's Adversarial Tactics, Techniques and Common Knowledge (ATT&CK) is a curated knowledge base and model for cyber adversary behavior, reflecting the various phases of an adversary's lifecycle and the platforms they are known to target.

We request that you write an exploit that will automate the attack technique you picked.
1. Your exploit should clearly define attack preconditions (For Example: [Operating System = "Linux", Software Installed = "Spotify"])
2. Your exploit should clearly define attack action (Execution of the attack)
3. Your exploit should clearly define postconditions (This will act as a validation check if your exploit was either successfully/failed)
4. Your exploit should finally contain a comprehensive clean-up method which will remove any files, directories and reset configurations changed/added by the attack action

Your exploit should be easy to set up, and should run on either Linux or Mac OS X. It should not require any non open-source software. The exploit will be tested in a virtual machine based on the clearly defined preconditions.

There are many ways that this exploit could be built; we ask that you build it in a way that showcases one of your strengths. If you you enjoy documentation, do something interesting with defining the preconditions. If you like object-oriented design, feel free to dive deeper into the model of this problem. We're happy to tweak the requirements slightly if it helps you show off one of your strengths.

## Bonus Points
Using orchestration software (Ansible, Puppet, Chef, Terraform, and/or deployment scripts) to provision attack target machine state (meeting attack preconditions)

Once you're done, please submit a paragraph or two in your `README` about what you are particularly proud of in your implementation, and why.

## Evaluation
Evaluation of your submission will be based on the following criteria. 

1. Did your exploit fulfill the basic requirements?
2. Did you document the method for setting up and running your exploit?
3. Did you follow the instructions for submission?
4. Does your exploit work

