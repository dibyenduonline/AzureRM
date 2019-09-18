# AzureRM
sample scripts to create storage account in azure with Azure RM scripts

the command in powershell is 


Command1
Connect-AzAccount

Command2
.\Deploy-AzTemplate.ps1 -ArtifactStagingDirectory . -Location centralus -TemplateFile azuredeploy.json -TemplateParametersFile azuredeploy.parameters.json
