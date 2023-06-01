# Checklist 
These have been compiled from myriad of online resources, books like Clean Code and also personal experiences:

- Variable should have meaningful names.
- Methods should be small like, strive for not more than 7-10 lines.
- Create multiple small methods instead of one big method.
- Ensure good Junit coverage.
- Classes should be sateless.
- Polymorphism is an alternative to if/else and should be preferred.
- Don’t over engineer follow KISS (Keep it Simple Stupid).
- Constructor injection.
- Magic numbers should be replaced with named constants.
- User input should not be used in queries directly.
- Watch out for cross site scripting in general.
- Avoid having one constants file for all constants as unrelated constants (eg db related, business related) all end up in the same file. Instead place constants in specific classes or interfaces to which they are closely related to.  

## Soft skills
Below are some tips on general attitude/behaviour towards code reviews. These have been compiled from the following link https://google.github.io/eng-practices/review/reviewer/

- Technical facts and data overrule opinions and personal preferences.
- In general, reviewers should favour approving a CL once it is in a state  where it definitely improves the overall code health of the system being worked on, even if the CL isn’t perfect.
- The reviewer should balance out the need to make forward progress compared to the importance of the changes they are suggesting. Instead of seeking perfection, what a reviewer should seek 
is continuous improvement. 
- If the author can demonstrate (either through data or based on solid engineering principles) that several approaches are equally valid, then the reviewer should accept the preference of the author. 
- Try to provide code reviews as fast as possible. One business day is max.