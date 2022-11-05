# ACIT4640_lab5

###To replicate the configuration on a new machine follow these instructions: 

*Install terraform (you can use this link https://developer.hashicorp.com/terraform/tutorials/aws-get-started/install-cli) 
*create a new API token on Digitalocean 
*create a .env file on your directory 
*copy your token and save it to the .env file (`export TF_VAR_do_token=<my API tocken>`)
*source your .env file by running `source .env`
*clone the ripo on the same directory 
*you can check the validation of the main.tf file by running `terraform validate`
![````111ture](https://user-images.githubusercontent.com/71790429/200103020-52bb57ee-ce9d-446b-a87d-9da56280f62d.JPG)

*After the configuration was valid you can run `terraform plan` to see what is going to be created using terraform similiar to what is shown below:
![plan](https://user-images.githubusercontent.com/71790429/200103834-b6630c49-c531-46a5-881b-42269d5446d8.JPG)

*To apply all the changes simply run `terraform apply` which will apply all the changes configured in the main.tf file. 
