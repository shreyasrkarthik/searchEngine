# RFCs

The RFC (request for comment) process is to have the enhancements and major changes
tracked through the pull request workflow in a concise manner.

### When is it required

You need to create a RFC document when you intend to make substantial changes to
the codebase. 
Definition of "substantial" is as follows :
* New components or features which expose APIs
* Changes to implementation/behavious of existing features 

### When should I not create one?
Minor bug fixes or document updates

### Process
* RFCs are present in the rfcs/ folder
* Copy the 0000-template.md to rfcs/component_name/0000-my-feature.md and edit
* Submit pull request for the new feature and get feedback from the community.
* After approval and merge, incorporate the feedback for the subsequent code changes