# Workflow and Description

*Brief explanation of ideas how should it work...*

1. Questions are maintained in the Knowledge Model
   * questions, answers, experts, resources, tree structure, ...
2. Change of question in DS-KM can be easily propagated to repository for that question (CI script)
3. Change in question repository could be also propagated to DS-KM (CI script)
4. `README.md` page should be generated from `data.yaml` (CI script)
5. CI tools won't be located in each repository but developed in separate repository and installed on Travis CI (e.g., via `pip install`). There should be some periodical CI runs (daily?) for question repositories.
6. Generated `README.md` should be highly linked with DSP and DS-KM ("Go to question in DSP", "Pick your answer in DSP", "Check question in DS-KM", etc.)

![Octocat](https://github.com/MarekSuchanek/DSQ-example/raw/master/resources/Octocat.png)
