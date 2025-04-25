# Contributing Projects to Killed by Skate702

Project data for this website is managed centrally in the `projects.yaml` file located in the root directory of this repository. To add a new project or update an existing one, please follow the formatting guidelines below.

## Formatting Project Entries

Each project is represented as an item in the main list within `projects.yaml`. Ensure your entry adheres to the following structure and conventions:

**Example Entry:**

```yaml
- id: nodecg-io # Unique identifier (lowercase, hyphens for spaces)
  name: "nodecg-io" # Display name (use quotes if needed)
  born: "May 21, 2020" # Start date/period (string)
  killed: "Apr 13, 2025" # End date/period (string)
  status: archived # Must be one of the allowed statuses (see below)
  description: "A NodeCG-bundle which implements Social Media API's in the NodeCG framework." # Short description
  fate: "Killed in favor of stubits" # Reason for inclusion in this archive
  links: # Optional list of relevant links
    - label: "GitHub" # Text label for the link
      url: "[https://github.com/codeoverflow-org/nodecg-io](https://github.com/codeoverflow-org/nodecg-io)" # Full URL
    - label: "Docs"
      url: "[https://nodecg.io/](https://nodecg.io/)"
