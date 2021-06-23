---
name: Design audit
label: audit
about: Template for UI/UX audit of a project or feature
---

Please make sure you add this to the GitHub board for the next release.

# [Project/Feature name] audit

Tested on: [branch/master...]

## 🐛 Bugs
Report bugs directly in Kibana.

### [Bug 1]

- [ ] [Description of bug](Link to reported bug)

## 🌟 Enhancements

### [Enhancement 1]

- [ ] [Description of enhancement]
<details>
<summary>View screens</summary>
// screenshot goes here
</details>



-----
Consider the following things in your audit (remove this part once you are done with your audit):

### Navigation
Does the view make sense where it is presented in the navigation?

### Consistency
Are the components and icons used in a consistent way?

### Data
Is the data presented in a meaningful way?
Is the data consistent across the views (for example, the same in the chart and the table.

### Responsive
Is this view taking different screensizes into account? Can the UI be used on very wide/narrow screens?

### Labels/Text
Are there descriptive labels? Is any information missing? Are the provided descriptions useful? Could any of it be misinterpreted? Is it the wording consistent with other views?

### Dark theme
Do the colors also work in dark theme?

### Telemetry
Which data should we capture?

### Permissions/Errors/Empty states
What does the view look like:
- if a user does not have the permissions to perform a certain action?
- if the data is not loading?
- if an error happens?

### Scaleability
Is this UI usable in very large setups with a lot of entities?

-----

When creating engineering issues, add the version as a label and `bug` or `polish` labels depending on the issue type.
