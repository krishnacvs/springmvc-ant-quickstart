#!/usr/bin/groovy
def project_info = [
'SDLC-Build' = "1",
'SDLC-branch' = "local"
'SLDC-Version' = "1.1"
];
def branch = "${project_info['SDLC-branch']}";

antPipelinePluign {
 antTargets = [clean: "clean", compile:"build", package="package-release"]
}