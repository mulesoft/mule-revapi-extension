def UPSTREAM_PROJECTS_LIST = [ "Mule-runtime/api-annotations/1.2.0-JULY-2021" ]

Map pipelineParams = [ "upstreamProjects" : UPSTREAM_PROJECTS_LIST.join(','),
                       "mavenSettingsXmlId" : "mule-runtime-maven-settings-MuleSettings",
                       "projectType" : "Runtime"]

runtimeBuild(pipelineParams)
