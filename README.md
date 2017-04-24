# Load Testing

## CLT (Cloud-Load Testing)

Using auto provisioned agents:
* [Run simple load tests from VSTS](https://almvm.azurewebsites.net/labs/vsts/load/) 
* [Run major load tests from VS]() 

Using self-provisioned agents (CLT agents inside your subscription on Azure IaaS):
* [ARM-template create rig](https://github.com/Azure/azure-quickstart-templates/tree/master/101-vsts-cloudloadtest-rig) 
* [ARM-template create rig in a specific VNet](https://github.com/Azure/azure-quickstart-templates/tree/master/201-vsts-cloudloadtest-rig-existing-vnet)
* How to configure in VS

[Using cloud-agents on your infrastrusture](https://blogs.msdn.microsoft.com/visualstudioalm/2016/08/22/use-cloud-load-agents-on-your-infrastructure/)

<pre><code>
//Add context parametr
Context parameter name – UseStaticLoadAgents
Context parameter value – true
Context parameter name – StaticAgentsGroupName
Context parameter value – <name of the agent group>
</pre></code>


## Test Agents/Test Controller
[Configuring Test Controllers and Test Agents for Load Testing](http://msdn.microsoft.com/en-us/library/ms243155(v=vs.110).aspx)
[Setting Up Machines and Collecting Diagnostic Information Using Test Settings](https://msdn.microsoft.com/en-us/library/dd286743(v=vs.120).aspx)


## How to choose

[Original blog post](https://blogs.msdn.microsoft.com/visualstudioalm/2016/08/23/testing-privateintranet-applications-using-cloud-based-load-testing/)

<img src="https://msdnshared.blob.core.windows.net/media/2016/08/clip_image0018.png"/>

## Get performance data
* Application Insights
* [In Visual Studio](https://www.visualstudio.com/en-us/docs/test/performance-testing/getting-started/get-performance-data-for-load-tests) 

## Additional Resources
* [Cloud-Load Testing blog](https://blogs.msdn.microsoft.com/visualstudioalm/p/cltknowledgebase/)
* [Visual Studio HoL](https://almvm.azurewebsites.net/)
