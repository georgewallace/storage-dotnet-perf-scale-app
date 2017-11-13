# Azure Storage Throughput Test

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fgeorgewallace%2Fstorage-dotnet-perf-scale-app%2Fmaster%2Fazuredeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>

1. Click Deploy button to deploy the sample to a Windows VM on Azure
2. Once deployment is completed, connect to the VM via RDP using the administrator account you defined. You will have 50 files each 1GB in the D: directory as sample data.
3. Navigate to the sample application in D:\git\storage-dotnet-perf-scale-app
`cd d:\git\storage-dotnet-perf-scale-app`
4. Run the application to upload the files to Azure Storage from the folder
`dotnet run`

When done with the sample, remember to delete the VM to ensure you do not continue to get charged for the VM.
