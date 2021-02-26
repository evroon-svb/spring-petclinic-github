@Library('my-library@development') _


// SecuredPipeline will BUILD and DEPLOY to OCP by default. Override with
// following parameters and pass to pipeline
def pipelineConfiguration = [
	BUILD: true,
	DEPLOY: true,
	RUN_LIB_TEST: false,
	FAKE_VAR: "no exist"

]
// Call the SecuredPipeline with configuration map
SecuredPipeline(pipelineConfiguration)
