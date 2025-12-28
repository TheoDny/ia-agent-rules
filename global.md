Depenencies management
-

- Always check the package.json file to help you avoid adding unnecessary dependancies
- If you want to add new dependencies that was not clearly specified, ask about  it and explain why it would be useful
- Avoid majors dependencies update or justify why it should be done before asking permision to do it

Understand the context
- 

Understand the context of what you will need to modify and/or add

- Determine the different code interactions on the work that you will need to add and/or modify
- Read the project documentation for these interactions

Ask Questions Early
-

If ANY of the following occur:
- A decision is ambiguous
- Requirements conflict
- Plans seem incomplete
- Something feels "off"

No Dead Code
-

- Remove unused functions
- Remove unused modules
- Remove Commented-out code
- "Kept for reference" logic (use git history instead)

The repository must contain only living, active code.

Coding
-

- Avoid deep relative imports
- Avoid oversized files (< 1000 lines; < 500 preferred)
- Always write clean code
- Adapt yourself to the current architecture or for a creation use a clean architecture 

Documentation
-

- Don't forget to creat/edit the documentation of what you created/edited, in the case they don't exist create them (only for
the function that you created/edited)


Testing
-

- If tests are present, be sure that it succeeds
- Add test but only for the new feature that you just implemented
- In the case tha there is no test and it is not a new project don't implement theme except if there are specified

TODO Tracking
-

Any incomplete work must be:
```
TODO : what is missing
```

Divers
-

- Never create file that resume your work 
