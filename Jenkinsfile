// https://github.com/Rudd-O/shared-jenkins-libraries
@Library('shared-jenkins-libraries@master') _


genericFedoraRPMPipeline(
	{
        downloadCrateSourceFromSpecfile sha256sum: "4838a2d89bdcbcad051f18347ed6cbe3e5b9b09fb0019e1a6ec4bb2bb1d29481"
	},
	{
		SRPMStrategyRpmbuildBs()()
	},
)
