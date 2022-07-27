
    module "team1-vpc" {
         source  = ""aws_vpc" "team1-vpc"
         
         region             = "us-east-1"
         cidr_block         = "10.0.0.0/16"
         public-1           = "10.0.101.0/24"
         public-2           = "10.0.102.0/24"
         public-3           = "10.0.103.0/24"
         private-1          = "10.0.1.0/24"
         private-2          = "10.0.2.0/24"
         private-3          = "10.0.3.0/24"
         enable_nat_gateway = true
     }
