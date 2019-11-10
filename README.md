# About this repo
This repo shows the basic roots structure.

Terraform defines a "rood module" as the current working directory holding the Terraform configuration files where the terraform apply or terraform get is run.

Each "root module" needs to comprise of the follwing files.
* `main.tf`
* `variables.tf`
* `outputs.tf`
* `readme.md`
* `.gitignore`

## Readme.md file
Each new repository needs to have a `readme.md` file. These readme files help the users of our Terraform roots give context to what the root module does. The readme is written in Markdown language which has turned into the main language for readme files.

Readme's should include the following information:

### <b>Overview</b>
Have an overview of the module. This area gives a description of the infrastructure or application the repo builds. Any additional design documents will go in this area. [draw.io](https://www.draw.io) is a great free tool.

### <b>Install Guide</b>
A quick introduction of the minimum setup you need to get up and running.

### <b>Configuration</b>
Here you should write what are all the configurations a user can enter when using the project.

Have an <b>Input</b> and <b>Outputs</b> section. These can be built using the [terraform-docs](https://github.com/segmentio/terraform-docs) to help generate the table structure.

## Example README.md

Use the `readme-default.md` as a template.