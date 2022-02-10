# STIG Data

STIGs are in XCCDF format.

## STIG formatting info

The following fields are in a STIG:

* Vul ID
* Rule ID
* Rule Name
* STIG ID

To map these fields to the fields in the CIS benchmark format to ingestion
into kube-bench (insert what has to be done here)

## CIS formatting info

* Profiles
* Sections

## kube-bench control files

controls is composed of a hierarchy of groups, sub-groups and checks.
Each of the controls components have an id and a text description which are
displayed in the kube-bench output.

type specifies what kubernetes node type a controls is for. Possible values for type are master and node.

groups is a list of subgroups that test the various Kubernetes components that run on the node type specified in the controls.

The CIS Kubernetes Benchmark recommends configurations to harden Kubernetes components. These recommendations are usually configuration options and can be specified by flags to Kubernetes binaries, or in configuration files.

The Benchmark also provides commands to audit a Kubernetes installation, identify places where the cluster security can be improved, and steps to remediate these identified problems.

In kube-bench, check objects embody these recommendations.

## STIG to CIS

To map these fields to the fields in the CIS benchmark format to ingestion
into kube-bench (insert what has to be done here)

## Links

https://github.com/aquasecurity/kube-bench/blob/main/docs/controls.md
