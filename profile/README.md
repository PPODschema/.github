# PPOD - Developing data schemas and infrastructure around the Persons-Projects-Organizations-Datasets data pattern

In our work in environmental data management, we have repeatedly observed a pattern where groups collect information
on persons, projects, organizations, and datasets. Seeing this, we have developed a number of data schemas,
vocabularies, and ontologies to help express the interrelationships between these core data classes. 
This organization has been set up to host repositories, discussions, and general development of the PPOD pattern.

At present there are four main repositories in this organization. These are:

* [PPODtottl](https://github.com/PPODschema/PPODtottl) which holds a Python script to convert a PPOD database in a
Google Sheets document into RDF Turtle format. This database describes resources of interest to the 
[UC Davis Food Systems Lab](https://foodsystemslab.ucdavis.edu).
* [PPOD_FSL](https://github.com/PPODschema/PPOD_FSL) which is a [LinkML](https://linkml.io/) schema characterizing the UC Davis FSL PPOD database.
* [PPOD_CA](https://github.com/PPODschema/PPOD_CA) which contains an RDF database describing linkages between
environmental conservation and the food system in California.
* [PPOD_Core](https://github.com/PPODschema/PPOD_Core) which contains a core LinkML schema for the PPOD data pattern.

Future work on PPOD will include extending the PPOD core schema by creating individualized application schemas for particular subject domains.


<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
