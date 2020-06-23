# azure-devops-yaml-nested-extends

Shows how to have multiple extends and includes in Azure DevOps YAML pipelines.

#### azure-pipeline.yaml
Is the entrypoint of the pipeline.

#### level1_template.yml
Demonstrates that an `extends` can also extend another template.

#### level2_template.yml
Example how to reuse multiple templates by using "includes".

#### step1_template.yml
An includable template with `parameters`.

#### steps2_templates.yml
A template with multiple `steps`.