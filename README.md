# test_chatgpt_readme
test_chatgpt


## VPC Exposed Inputs 

| Name                                                                                            | Description                                                                                                                                       | Type          | Default                                                              | Required |
|-------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------|---------------|----------------------------------------------------------------------|:--------:|
| <a name="input_vpc_name"></a> [vpc\_name](#input\_vpc\_name)                                    | Name of virtual private cloud                                                                                                                     | `string`      | `my-vpc`                                                             | no |
| <a name="input_vpc_id"></a> [vpc\_id](#input\_vpc\_id)                                           | ID of virtual private cloud                                                                                                                       | `string`      | `auto`                                                               | no |
| <a name="input_vpc_cidr"></a> [vpc\_cidr](#input\_vpc\_cidr)                                    | (Optional) The IPv4 CIDR block for the VPC. CIDR can be explicitly set or it can be derived from IPAM using ipv4_netmask_length & ipv4_ipam_pool_id | `string`      | `10.0.0.0/16`                                                        | no |
| <a name="input_vpc_azs"></a> [vpc\_azs](#input\_vpc\_azs)                                       | A list of availability zones names or ids in the region                                                                                           | `list(string)`      | `["ap-south-2a", "ap-south-2b", "ap-south-2c"]`                      | no |
| <a name="input_vpc_private_subnets"></a> [vpc\_private\_subnets](#input\_vpc\_private\_subnets) | List of IDs of private subnets                                                                                                                    | `list(string)` | `["10.0.1.0/24", "10.0.2.0/24", "10.0.3.0/24"]`                      | no |
| <a name="input_vpc_tags"></a> [vpc\_tags](#input\_vpc\_tags)                                    | A map of tags to add to all resources                                                                                                             | `map(string)` | `{Owner: "Intel.Cloud.Optimization.Modules@intel.com", Duration: "4"}` | no |



### asdasdsadasdasda

| Key Name | Description | Type | Value |
| --- | --- | --- | --- |
| <a name="input_vpc_state"></a> [vpc_state](#input_vpc_state) | Represents the state of the VPC | String | present |
| <a name="input_vpc_name"></a> [vpc_name](#input_vpc_name) | Name of the VPC | String | "my-vpc" |
| <a name="input_vpc_cidr"></a> [vpc_cidr](#input_vpc_cidr) | CIDR block for the VPC | String | "10.0.0.0/16" |
| <a name="input_vpc_azs"></a> [vpc_azs](#input_vpc_azs) | List of Availability Zones for the VPC | List of Strings | ["ap-south-2a", "ap-south-2b", "ap-south-2c"] |
| <a name="input_vpc_private_subnets"></a> [vpc_private_subnets](#input_vpc_private_subnets) | List of private subnets in the VPC | List of Strings | ["10.0.1.0/24", "10.0.2.0/24", "10.0.3.0/24"] |
| <a name="input_vpc_tags"></a> [vpc_tags](#input_vpc_tags) | Tags associated with the VPC | Dictionary | { Owner: "Intel.Cloud.Optimization.Modules@intel.com", Duration: "4" } |
