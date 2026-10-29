# MZ-UCA Academy Profile and Policy Reader
## Project Objective
This project demonstrates Terraform variables, outputs,
locals, data sources and a managed local file.
## Tools Used
- Terraform
- HashiCorp local provider
- Visual Studio Code
- Terminal
## Resources Managed
- local_file.academy_profile
## Data Sources Used
- data.local_file.academy_policy
## Validation
Document the result of terraform validate.
- Success! The configuration is valid.
## Execution
Document the result of terraform plan and terraform apply.
- Terraform plan : 
= After running terraform plan the resource address will display local_file.academy_profile.
== change variable defualt = "Student Engineer" to defsault = "Your Full Name" then rubn terraform plan. Obseerve the proposed plan.
- Terraform apply:
=Terraform displays the proposed changes and asks you to confirm. Type yes and wait for the apply
operation to complete. it will display:
Academy: MZ-UCA Cloud Academy
Student: Student Engineer
Environment: training
= Then run terraform apply and confirm when prompted. Open the
generated file again — the student name should now reflect your updated value.

## Testing
Explain how changing the environment variable changed the generated academy profile.
- A reusable and flexible code was used to generate academy-profile.txt. Terraform init, validate, plan and apply were run.
- A resusabled and flexible code was used to generate Academy-policy.txt. Terrraform validate, plan and apply commands were run.

## Lessons Learned
Explain the difference between variables, outputs,
locals and data sources.
- Variables are used to pass values from external sources into terraform configuration. Allows to develop templates that can be reusable in various environments with a minimal duplication of code and enhancdes flexibility of code. For example, variable values can be edited instead of rewriting the entire script of code.
- Outputs are return values that displays specific information or resource attributes from the infrastructure after the terraform apply command has be run.
- Locals are certain temporary values used to assign specific names to an expression in order to reuse code throughout the entire configuration.
- Data Sources are ways of accessing and retrieving information from external sources, cloud providers(AWS, Azure or GCP) or existing infrastructure without managing its entire lifecycle.
## Evidence
List the screenshots and files submitted with the project.

![Initializing Terraform](screenshots/Lab_02_Understanding_terraform_Variables_04.png)
![Validating Terraform](screenshots/Lab_02_Underswtanding_Terraform_Variables_05.png)
![Terraform Plan](screenshots/Lab_02_Understanding_Terraform_Variables_06.png)
![Terraform Apply](screenshots/Lab_02_Understanding_Terraform_Variables_07.png)
![Editing Variable tf File](screenshots/Lab_02_Understanding_Terraform_Variables_09.png)
![Terraform Plan](screenshots/Lab_02_Understanding_Terraform_Variables_11.png)
![Executing Terraform Apply](screenshots/Lab_02_Understanding_Terraform_Variables_12[1].png)
![Terraform Execution](screenshots/Lab_02_Understanding_Terraform_Variables_12[2].png)
![Editing Terraform Outputs tf File](screenshots/Lab_03_Understanding_Terraform_Outputs_Part_01.png)
![Validation of Terraform](screenshots/Lab_03_Understanding_Terraform_Outputs_Part_02.png)
![Terraform Apply Command](screenshots/Lab_03_Understanding_Terraform_Outputs_Part_03.png)
![Terraform Output Command](screenshots/Lab_03_Understanding_Terraform_Outputs_Part_04.png)
![Terraform Output Academy file](screenshots/Lab_03_Understanding_Terraform_Outputs_Part_06.png)
![Editing Locals tf File](screenshots/Lab_04_Understaing_Terraform_Locals_Part_06[[1]]].png)
![Editing Main tf File](screenshots/Lab_04_Understaing_Terraform_Locals_Part_02[[1]].png)
![Validating Terraform in Locals](screenshots/Lab_04_Understaing_Terraform_Locals_Part_03[[1]].png)
![Modifying Locals tf File](screenshots/Lab_04_Understaing_Terraform_Locals_Part_06[[1]].png)
![Terraform plan](screenshots/Lab_04_Understaing_Terraform_Locals_Part_07[[1]].png)
![Terraform planning](screenshots/Lab_04_Understaing_Terraform_Locals_Part_07[[2]].png)
![Terraform apply part 1](screenshots/Lab_04_Understaing_Terraform_Locals_Part_08[[1]].png)
![Terraform apply part 2](screenshots/Lab_04_Understaing_Terraform_Locals_Part_08[[2]].png)
![Creating a directory](screenshots/Lab_05_Understanding_Terraform_Data_Sources_Part_01.png)
![Move into directory](screenshots/Lab_05_Understanding_Terraform_Data_Sources_Part_02.png)
![Create Academy Policy](screenshots/Lab_05_Understanding_Terraform_Data_Sources_Part_03.png)
![Open Academy Policy](screenshots/Lab_05_Understanding_Terraform_Data_Sources_Part_03[2].png)
![Edit Academy Policy](screenshots/Lab_05_Understanding_Terraform_Data_Sources_Part_04.png)
![Edit data tf File](screenshots/Lab_05_Understanding_Terraform_Data_Sources_Part_06.png)
![Terraform Validation](screenshots/Lab_05_Understanding_Terraform_Data_Sources_Part_07.png)
![Terraform Plan](screenshots/Lab_05_Understanding_Terraform_Data_Sources_Part_08.png)
![Using Terraform Apply](screenshots/Lab_05_Understanding_Terraform_Data_Sources_Part_09[1].png)
![Continued Using Terraform Appl](screenshots/Lab_05_Understanding_Terraform_Data_Sources_Part_09[2].png)
![Edit Academy Policy](screenshots/Lab_05_Understanding_Terraform_Data_Sources_Part_10.png)
![Planning on changes](screenshots/Lab_05_Understanding_Terraform_Data_Sources_Part_11.png)
![Using Terraform Output](screenshots/Lab_05_Understanding_Terraform_Data_Sources_Part_12[TesT].png)
![Using Terraform Apply to consolidate changes](screenshots/Lab_05_Understanding_Terraform_Data_Sources_Part_13.png)
![Terraform Plan changes](screenshots/Lab_05_Understanding_Terraform_Data_Sources_Part_14.png)
![Terraform Output changes made](screenshots/Lab_05_Understanding_Terraform_Data_Sources_Part_15.png)
![Terraform Format](screenshots/Lab_06_Integrated_Terraform_Engineering_Project_Part_01.png)
![Initializing Terraform](screenshots/Lab_06_Integrated_Terraform_Engineering_Project_Part_02.png)
![Terraform Validation](screenshots/Lab_06_Integrated_Terraform_Engineering_Project_Part_03.png)
![Using Terraform Plan](screenshots/Lab_06_Integrated_Terraform_Engineering_Project_Part_04.png)
![Executing Terraform apply](screenshots/Lab_06_Integrated_Terraform_Engineering_Project_Part_05.png)
![Using Terraform Output](screenshots/Lab_06_Integrated_Terraform_Engineering_Project_Part_06.png)
