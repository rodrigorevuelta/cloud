# cloud
example of cloud architecture using cloudformation

the diagram of the architecture is shown in cloud.png

to create the deployment there are two stacks:

$./sh/create-cf.sh udagram-network udagram-network.yml udagram-network.json
$./sh/create-cf.sh udagram-server udagram-server.yml udagram-server.json

The output of the stack udagram-server show the url of the load balancer