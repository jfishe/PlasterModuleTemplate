# PlasterModuleTemplate

A Plaster template for automating the scaffolding of a new PowerShell module.

I'd like to thank the following community members for the guidance I got from
their work with Plaster:

* David Christian [Working with Plaster](http://overpoweredshell.com/Working-with-Plaster/)
  * Initial `template.psm1`
  * `plasterManifest.xml` items
* Kevin Marquette [Powershell: Let's build the CI/CD pipeline for a new module](https://kevinmarquette.github.io/2017-01-21-powershell-module-continious-delivery-pipeline/?utm_source=blog&utm_medium=blog&utm_content=titlelink)
  * Initial `basicTest.ps1`, `build.Depend.psd1`, `test.Depend.psd1`,
    `build.ps1`, `module.Build.ps1`, `deploy.PSDeploy.ps1`, `Help.Tests.ps1`
* Matthew Bobke who originated the [mcbobke/PlasterModuleTemplate](https://github.com/mcbobke/PlasterModuleTemplate)

## Change Log

* 0.0.2
  * Add README instructions for publishing to `PSRepository`, e.g.,
    `LocalRepo1`.
* 0.0.1
  * Add en-US\about.help.txt template file
