# OpenCenter QA Tools

Tools to make working with OpenCenter easier for the QA Team

## Setup

	export PYTHONPATH=$PYTHONPATH:/path_of_opencenter_helper
	export CHEF_NAME=your_name
	export PATH=$PATH:path_to here

Example

    export PYTHONPATH=$PYTHONPATH:~/work/rpcsqa/jenkins/modules/bare-metal
    export CHEF_NAME=cameron
	export PATH=$PATH:~/work/opencenter-qa-tools
	
## Use


### open_dashboard

Will open the OpenCenter dashboard in your browser for the given chef
environment

    open_dashboard -h
	usage: open_dashboard [-h] [--name NAME] [--os OS]

	optional arguments:
	  -h, --help   show this help message and exit
	  --name NAME  Name for the opencenter chef environment
	  --os OS      Operating System to use for opencenter

Example

    open_dashboard --name=cameron --os=centos

### open_horizon

Will open the horizon dashboard of the openstack instance for the
given chef environment

	open_horizon -h                                                                                                                1 ↵
	usage: open_horizon [-h] [--name NAME] [--os OS]

	optional arguments:
	  -h, --help   show this help message and exit
	  --name NAME  Name for the opencenter chef environment
	  --os OS      Operating System to use for opencenter

Example

    open_horizon --name=cameron

### opencenter_env

Will set up $OPENCENTER_ENDPOINT with the endpoint given a chef
environment

	opencenter_env -h
	usage: opencenter_env [-h] [--name NAME] [--os OS]

	optional arguments:
	  -h, --help   show this help message and exit
	  --name NAME  Name for the opencenter chef environment
	  --os OS      Operating System to use for opencenter

Example

    opencenter_env --name=cameron
    Endpoint set to: https://user:password@192.168.10.1:8443
    Try: opencentercli node list

### openstack_env

	openstack_env -h
	usage: openstack_env [-h] [--name NAME] [--os OS]

	optional arguments:
	  -h, --help   show this help message and exit
	  --name NAME  Name for the opencenter chef environment
	  --os OS      Operating System to use for opencenter

Example

	openstack_env --name=cameron                                                                                                   1 ↵
	OpenStack environment set
	Try: nova-manage service list
	$OS_NO_CACHE=1
	$OS_USERNAME=admin
	$OS_AUTH_STRATEGY=keystone
	$OS_TENANT_NAME=admin
	$OS_AUTH_URL=http://192.168.10.1:5000/v2.0
	$OS_PASSWORD=secrete
