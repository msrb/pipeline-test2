@Library('github.com/fabric8io/fabric8-pipeline-library@master')
def flow = new io.fabric8.Fabric8Commands()

node {
	def rs = flow.getServiceURL("jenkins")
	echo "${rs}"
}

