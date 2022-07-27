
    module "vpc-t1" {
         source  = "aiyadjaz/vpc-t1/aws"
         
         region             = "us-east-1"
         cidr_block         = "10.0.0.0/16"
         public_subnet1     = "10.0.1.0/24"
         public_subnet2     = "10.0.2.0/24"
         public_subnet3     = "10.0.3.0/24"
         private_subnet1    = "10.0.101.0/24"
         private_subnet2    = "10.0.102.0/24"
         private_subnet3    = "10.0.103.0/24"
         enable_nat_gateway = true
    
         tags = {
              Name = "main"
         }
     }
