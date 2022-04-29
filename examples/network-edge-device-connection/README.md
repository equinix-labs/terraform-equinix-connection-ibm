# Network Edge Device Connection Example

This example demonstrates usage of the Equinix Connection IBM module to establish a non-redundant Equinix Fabric L2 Connection from a Equinix Network Edge device to IBM Direct Link 2.0. It will:

- Create Equinix Fabric l2 connection with 200 Mbps bandwidth.
- Approve IBM connection request.
- Configure BGP session from IBM DL gateway to your Network Edge device.
- Create an IBM Direct Link virtual connection to a VPC.

## Usage

To provision this example, you should clone the github repository and run terraform from within this directory:

```bash
git clone https://github.com/equinix-labs/terraform-equinix-fabric-connection-ibm.git
cd terraform-equinix-fabric-connection-ibm/examples/network-edge-device-connection
terraform init
terraform apply
```

Note that this example may create resources which cost money. Run 'terraform destroy' when you don't need these resources.

## Variables

See <https://registry.terraform.io/modules/equinix-labs/fabric-connection-ibm/equinix/latest/examples/network-edge-device-connection?tab=inputs> for a description of all variables.

## Outputs

See <https://registry.terraform.io/modules/equinix-labs/fabric-connection-ibm/equinix/latest/examples/network-edge-device-connection?tab=outputs> for a description of all outputs.
