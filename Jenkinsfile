node {
	stage('Unit Tests') 
	{
		sh "sbt clean test"
		sh "sbt clean coverage"
		sh "sbt clean coverageReport"
	}
}
