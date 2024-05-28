<h1 style="color: steelblue;">⚠️ CARML - AVM transition ⚠️</h1>

**CARML evolved to and has been rebranded as the Bicep version of Azure Verifiefd Modules ([AVM](https://aka.ms/AVM)).** AVM is a straight-line successor of CARML, the next evolutionary step. A lot of CARML’s principles and architecture decisions have formed the basis for AVM.

While this means some minor changes in things such as parameter names or "standard interfaces" (e.g., diagnostic settings, etc.), **you can still use the same modules you're used to and love, as they have been transitioned to AVM as resource or pattern modules.**

- You can find the full list of all AVM modules in the [AVM Module Indexes](https://aka.ms/AVM/ModuleIndex).
- Each module is published in the Public Bicep Registry and their source code can be found in the underlying repository ([BRM](https://aka.ms/BRM))!

A notice with additional details has been placed in each module. If for any reason, you still need access to the CARML version of the module, you can find it in the CARML repository by following the links in the module's `README.md` file.

**Going forward, only the AVM version of the modules will receive updates and new features.**

- Please do not file issues in CARML or work on improving the module in CARML as further contributions to these modules will not be integrated in the CARML repository!
- To open an AVM module issue, use the [Module Issue](https://aka.ms/BRM/AVMModuleIssue) template in the BRM repository.
- If you accidentally raise an issue in the wrong place, we will transfer it to its correct home - the AVM Bicep repository ([BRM](https://aka.ms/BRM)).

> NOTE: A few modules have been retired without being moved to AVM as is. In most of these cases, capabilities originally provided by these modules have been implemented differently in AVM - e.g., as part of all AVM modules.

In the upcoming period, **the AVM team will work on ensuring full compatibility of CARML's inner-sourcing solution (CI environment) with AVM**.

# ![AzureIcon] Common Azure Resource Modules Library

## Description

This repository includes a library of mature and curated [Bicep][Bicep] modules as well as a Continuous Integration (CI) environment leveraged for modules' validation and versioned publishing.

The CI environment supports both ARM and Bicep and can be leveraged using GitHub actions as well as Azure DevOps pipelines.

## Get started

- For introduction guidance visit the [Wiki](https://github.com/Azure/ResourceModules/wiki)
- For guidance on which version of the code to leverage, see [Disclaimer](https://github.com/azure/resourcemodules#Disclaimer)
- For information on contributing, see [Contribution](<https://github.com/Azure/ResourceModules/wiki/Contribution%20guide>)
- File an issue via [GitHub Issues](https://github.com/Azure/ResourceModules/issues/new/choose)
- For reference documentation, visit [Enterprise-Scale](https://github.com/azure/enterprise-scale)
- For an outline of the module features, visit [Module overview](https://github.com/Azure/ResourceModules/wiki/The%20library%20-%20Module%20overview)

> **Note:** To ensure the modules and environment work as expected, please ensure you are using the latest version of the used tools such as PowerShell and Bicep. Especially in case of the latter, note, that you need to manually update the Bicep CLI. For further information, see our [troubleshooting guide](./The%20CI%20environment%20-%20Troubleshooting).

## Available Resource Modules

| Provider namespace | Resource Type | Name | Deploy |
| - | - | - | - |
| `Microsoft.AAD` | [domainServices](https://github.com/Ricky-G/ResourceModules/tree/main/modules/aad/domain-service) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/aad/domain-service) |  |
| `Microsoft.AnalysisServices` | [servers](https://github.com/Ricky-G/ResourceModules/tree/main/modules/analysis-services/server) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/analysis-services/server) |  |
| `Microsoft.ApiManagement` | [service](https://github.com/Ricky-G/ResourceModules/tree/main/modules/api-management/service) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/api-management/service) |  |
| `Microsoft.App` | [containerApps](https://github.com/Ricky-G/ResourceModules/tree/main/modules/app/container-app) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/app/container-app) |  |
|  | [jobs](https://github.com/Ricky-G/ResourceModules/tree/main/modules/app/job) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/app/job) |  |
|  | [managedEnvironments](https://github.com/Ricky-G/ResourceModules/tree/main/modules/app/managed-environment) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/app/managed-environment) |  |
| `Microsoft.AppConfiguration` | [configurationStores](https://github.com/Ricky-G/ResourceModules/tree/main/modules/app-configuration/configuration-store) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/app-configuration/configuration-store) |  |
| `Microsoft.Authorization` | [locks](https://github.com/Ricky-G/ResourceModules/tree/main/modules/authorization/lock) | [<h1 style="color: steelblue;">⚠️ Retired ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/authorization/lock) |  |
|  | [policyAssignments](https://github.com/Ricky-G/ResourceModules/tree/main/modules/authorization/policy-assignment) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/authorization/policy-assignment) |  |
|  | [policyDefinitions](https://github.com/Ricky-G/ResourceModules/tree/main/modules/authorization/policy-definition) | [<h1 style="color: steelblue;">⚠️ Retired ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/authorization/policy-definition) |  |
|  | [policyExemptions](https://github.com/Ricky-G/ResourceModules/tree/main/modules/authorization/policy-exemption) | [<h1 style="color: steelblue;">⚠️ Retired ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/authorization/policy-exemption) |  |
|  | [policySetDefinitions](https://github.com/Ricky-G/ResourceModules/tree/main/modules/authorization/policy-set-definition) | [<h1 style="color: steelblue;">⚠️ Retired ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/authorization/policy-set-definition) |  |
|  | [roleAssignments](https://github.com/Ricky-G/ResourceModules/tree/main/modules/authorization/role-assignment) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/authorization/role-assignment) |  |
|  | [roleDefinitions](https://github.com/Ricky-G/ResourceModules/tree/main/modules/authorization/role-definition) | [<h1 style="color: steelblue;">⚠️ Retired ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/authorization/role-definition) |  |
| `Microsoft.Automation` | [automationAccounts](https://github.com/Ricky-G/ResourceModules/tree/main/modules/automation/automation-account) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/automation/automation-account) |  |
| `Microsoft.Batch` | [batchAccounts](https://github.com/Ricky-G/ResourceModules/tree/main/modules/batch/batch-account) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/batch/batch-account) |  |
| `Microsoft.Cache` | [redis](https://github.com/Ricky-G/ResourceModules/tree/main/modules/cache/redis) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/cache/redis) |  |
|  | [redisEnterprise](https://github.com/Ricky-G/ResourceModules/tree/main/modules/cache/redis-enterprise) | [<h1 style="color: steelblue;">⚠️ Retired ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/cache/redis-enterprise) |  |
| `Microsoft.Cdn` | [profiles](https://github.com/Ricky-G/ResourceModules/tree/main/modules/cdn/profile) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/cdn/profile) |  |
| `Microsoft.CognitiveServices` | [accounts](https://github.com/Ricky-G/ResourceModules/tree/main/modules/cognitive-services/account) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/cognitive-services/account) |  |
| `Microsoft.Compute` | [availabilitySets](https://github.com/Ricky-G/ResourceModules/tree/main/modules/compute/availability-set) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/compute/availability-set) |  |
|  | [disks](https://github.com/Ricky-G/ResourceModules/tree/main/modules/compute/disk) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/compute/disk) |  |
|  | [diskEncryptionSets](https://github.com/Ricky-G/ResourceModules/tree/main/modules/compute/disk-encryption-set) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/compute/disk-encryption-set) |  |
|  | [galleries](https://github.com/Ricky-G/ResourceModules/tree/main/modules/compute/gallery) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/compute/gallery) |  |
|  | [images](https://github.com/Ricky-G/ResourceModules/tree/main/modules/compute/image) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/compute/image) |  |
|  | [proximityPlacementGroups](https://github.com/Ricky-G/ResourceModules/tree/main/modules/compute/proximity-placement-group) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/compute/proximity-placement-group) |  |
|  | [sshPublicKeys](https://github.com/Ricky-G/ResourceModules/tree/main/modules/compute/ssh-public-key) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/compute/ssh-public-key) |  |
|  | [virtualMachines](https://github.com/Ricky-G/ResourceModules/tree/main/modules/compute/virtual-machine) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/compute/virtual-machine) |  |
|  | [virtualMachineScaleSets](https://github.com/Ricky-G/ResourceModules/tree/main/modules/compute/virtual-machine-scale-set) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/compute/virtual-machine-scale-set) |  |
| `Microsoft.Consumption` | [budgets](https://github.com/Ricky-G/ResourceModules/tree/main/modules/consumption/budget) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/consumption/budget) |  |
| `Microsoft.ContainerInstance` | [containerGroups](https://github.com/Ricky-G/ResourceModules/tree/main/modules/container-instance/container-group) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/container-instance/container-group) |  |
| `Microsoft.ContainerRegistry` | [registries](https://github.com/Ricky-G/ResourceModules/tree/main/modules/container-registry/registry) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/container-registry/registry) |  |
| `Microsoft.ContainerService` | [managedClusters](https://github.com/Ricky-G/ResourceModules/tree/main/modules/container-service/managed-cluster) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/container-service/managed-cluster) |  |
| `Microsoft.DataFactory` | [factories](https://github.com/Ricky-G/ResourceModules/tree/main/modules/data-factory/factory) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/data-factory/factory) |  |
| `Microsoft.DataProtection` | [backupVaults](https://github.com/Ricky-G/ResourceModules/tree/main/modules/data-protection/backup-vault) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/data-protection/backup-vault) |  |
| `Microsoft.Databricks` | [accessConnectors](https://github.com/Ricky-G/ResourceModules/tree/main/modules/databricks/access-connector) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/databricks/access-connector) |  |
|  | [workspaces](https://github.com/Ricky-G/ResourceModules/tree/main/modules/databricks/workspace) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/databricks/workspace) |  |
| `Microsoft.DBforMySQL` | [flexibleServers](https://github.com/Ricky-G/ResourceModules/tree/main/modules/db-for-my-sql/flexible-server) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/db-for-my-sql/flexible-server) |  |
| `Microsoft.DBforPostgreSQL` | [flexibleServers](https://github.com/Ricky-G/ResourceModules/tree/main/modules/db-for-postgre-sql/flexible-server) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/db-for-postgre-sql/flexible-server) |  |
| `Microsoft.DesktopVirtualization` | [applicationGroups](https://github.com/Ricky-G/ResourceModules/tree/main/modules/desktop-virtualization/application-group) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/desktop-virtualization/application-group) |  |
|  | [hostPools](https://github.com/Ricky-G/ResourceModules/tree/main/modules/desktop-virtualization/host-pool) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/desktop-virtualization/host-pool) |  |
|  | [scalingPlans](https://github.com/Ricky-G/ResourceModules/tree/main/modules/desktop-virtualization/scaling-plan) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/desktop-virtualization/scaling-plan) |  |
|  | [workspaces](https://github.com/Ricky-G/ResourceModules/tree/main/modules/desktop-virtualization/workspace) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/desktop-virtualization/workspace) |  |
| `Microsoft.DevTestLab` | [labs](https://github.com/Ricky-G/ResourceModules/tree/main/modules/dev-test-lab/lab) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/dev-test-lab/lab) |  |
| `Microsoft.DigitalTwins` | [digitalTwinsInstances](https://github.com/Ricky-G/ResourceModules/tree/main/modules/digital-twins/digital-twins-instance) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/digital-twins/digital-twins-instance) |  |
| `Microsoft.DocumentDB` | [databaseAccounts](https://github.com/Ricky-G/ResourceModules/tree/main/modules/document-db/database-account) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/document-db/database-account) |  |
| `Microsoft.EventGrid` | [domains](https://github.com/Ricky-G/ResourceModules/tree/main/modules/event-grid/domain) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/event-grid/domain) |  |
|  | [systemTopics](https://github.com/Ricky-G/ResourceModules/tree/main/modules/event-grid/system-topic) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/event-grid/system-topic) |  |
|  | [topics](https://github.com/Ricky-G/ResourceModules/tree/main/modules/event-grid/topic) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/event-grid/topic) |  |
| `Microsoft.EventHub` | [namespaces](https://github.com/Ricky-G/ResourceModules/tree/main/modules/event-hub/namespace) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/event-hub/namespace) |  |
| `Microsoft.HealthBot` | [healthBots](https://github.com/Ricky-G/ResourceModules/tree/main/modules/health-bot/health-bot) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/health-bot/health-bot) |  |
| `Microsoft.HealthcareApis` | [workspaces](https://github.com/Ricky-G/ResourceModules/tree/main/modules/healthcare-apis/workspace) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/healthcare-apis/workspace) |  |
| `microsoft.insights` | [actionGroups](https://github.com/Ricky-G/ResourceModules/tree/main/modules/insights/action-group) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/insights/action-group) |  |
|  | [activityLogAlerts](https://github.com/Ricky-G/ResourceModules/tree/main/modules/insights/activity-log-alert) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/insights/activity-log-alert) |  |
|  | [components](https://github.com/Ricky-G/ResourceModules/tree/main/modules/insights/component) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/insights/component) |  |
|  | [dataCollectionEndpoints](https://github.com/Ricky-G/ResourceModules/tree/main/modules/insights/data-collection-endpoint) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/insights/data-collection-endpoint) |  |
|  | [dataCollectionRules](https://github.com/Ricky-G/ResourceModules/tree/main/modules/insights/data-collection-rule) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/insights/data-collection-rule) |  |
|  | [diagnosticSettings](https://github.com/Ricky-G/ResourceModules/tree/main/modules/insights/diagnostic-setting) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/insights/diagnostic-setting) |  |
|  | [metricAlerts](https://github.com/Ricky-G/ResourceModules/tree/main/modules/insights/metric-alert) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/insights/metric-alert) |  |
|  | [privateLinkScopes](https://github.com/Ricky-G/ResourceModules/tree/main/modules/insights/private-link-scope) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/insights/private-link-scope) |  |
|  | [scheduledQueryRules](https://github.com/Ricky-G/ResourceModules/tree/main/modules/insights/scheduled-query-rule) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/insights/scheduled-query-rule) |  |
|  | [webtests](https://github.com/Ricky-G/ResourceModules/tree/main/modules/insights/webtest) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/insights/webtest) |  |
| `Microsoft.KeyVault` | [vaults](https://github.com/Ricky-G/ResourceModules/tree/main/modules/key-vault/vault) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/key-vault/vault) |  |
| `Microsoft.KubernetesConfiguration` | [extensions](https://github.com/Ricky-G/ResourceModules/tree/main/modules/kubernetes-configuration/extension) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/kubernetes-configuration/extension) |  |
|  | [fluxConfigurations](https://github.com/Ricky-G/ResourceModules/tree/main/modules/kubernetes-configuration/flux-configuration) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/kubernetes-configuration/flux-configuration) |  |
| `Microsoft.Logic` | [workflows](https://github.com/Ricky-G/ResourceModules/tree/main/modules/logic/workflow) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/logic/workflow) |  |
| `Microsoft.MachineLearningServices` | [workspaces](https://github.com/Ricky-G/ResourceModules/tree/main/modules/machine-learning-services/workspace) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/machine-learning-services/workspace) |  |
| `Microsoft.Maintenance` | [maintenanceConfigurations](https://github.com/Ricky-G/ResourceModules/tree/main/modules/maintenance/maintenance-configuration) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/maintenance/maintenance-configuration) |  |
| `Microsoft.ManagedIdentity` | [userAssignedIdentities](https://github.com/Ricky-G/ResourceModules/tree/main/modules/managed-identity/user-assigned-identity) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/managed-identity/user-assigned-identity) |  |
| `Microsoft.ManagedServices` | [registrationDefinitions](https://github.com/Ricky-G/ResourceModules/tree/main/modules/managed-services/registration-definition) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/managed-services/registration-definition) |  |
| `Microsoft.Management` | [managementGroups](https://github.com/Ricky-G/ResourceModules/tree/main/modules/management/management-group) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/management/management-group) |  |
| `Microsoft.NetApp` | [netAppAccounts](https://github.com/Ricky-G/ResourceModules/tree/main/modules/net-app/net-app-account) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/net-app/net-app-account) |  |
| `Microsoft.Network` | [applicationGateways](https://github.com/Ricky-G/ResourceModules/tree/main/modules/network/application-gateway) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/network/application-gateway) |  |
|  | [ApplicationGatewayWebApplicationFirewallPolicies](https://github.com/Ricky-G/ResourceModules/tree/main/modules/network/application-gateway-web-application-firewall-policy) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/network/application-gateway-web-application-firewall-policy) |  |
|  | [applicationSecurityGroups](https://github.com/Ricky-G/ResourceModules/tree/main/modules/network/application-security-group) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/network/application-security-group) |  |
|  | [azureFirewalls](https://github.com/Ricky-G/ResourceModules/tree/main/modules/network/azure-firewall) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/network/azure-firewall) |  |
|  | [bastionHosts](https://github.com/Ricky-G/ResourceModules/tree/main/modules/network/bastion-host) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/network/bastion-host) |  |
|  | [connections](https://github.com/Ricky-G/ResourceModules/tree/main/modules/network/connection) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/network/connection) |  |
|  | [ddosProtectionPlans](https://github.com/Ricky-G/ResourceModules/tree/main/modules/network/ddos-protection-plan) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/network/ddos-protection-plan) |  |
|  | [dnsForwardingRulesets](https://github.com/Ricky-G/ResourceModules/tree/main/modules/network/dns-forwarding-ruleset) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/network/dns-forwarding-ruleset) |  |
|  | [dnsResolvers](https://github.com/Ricky-G/ResourceModules/tree/main/modules/network/dns-resolver) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/network/dns-resolver) |  |
|  | [dnsZones](https://github.com/Ricky-G/ResourceModules/tree/main/modules/network/dns-zone) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/network/dns-zone) |  |
|  | [expressRouteCircuits](https://github.com/Ricky-G/ResourceModules/tree/main/modules/network/express-route-circuit) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/network/express-route-circuit) |  |
|  | [expressRouteGateways](https://github.com/Ricky-G/ResourceModules/tree/main/modules/network/express-route-gateway) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/network/express-route-gateway) |  |
|  | [firewallPolicies](https://github.com/Ricky-G/ResourceModules/tree/main/modules/network/firewall-policy) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/network/firewall-policy) |  |
|  | [frontDoors](https://github.com/Ricky-G/ResourceModules/tree/main/modules/network/front-door) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/network/front-door) |  |
|  | [FrontDoorWebApplicationFirewallPolicies](https://github.com/Ricky-G/ResourceModules/tree/main/modules/network/front-door-web-application-firewall-policy) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/network/front-door-web-application-firewall-policy) |  |
|  | [ipGroups](https://github.com/Ricky-G/ResourceModules/tree/main/modules/network/ip-group) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/network/ip-group) |  |
|  | [loadBalancers](https://github.com/Ricky-G/ResourceModules/tree/main/modules/network/load-balancer) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/network/load-balancer) |  |
|  | [localNetworkGateways](https://github.com/Ricky-G/ResourceModules/tree/main/modules/network/local-network-gateway) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/network/local-network-gateway) |  |
|  | [natGateways](https://github.com/Ricky-G/ResourceModules/tree/main/modules/network/nat-gateway) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/network/nat-gateway) |  |
|  | [networkInterfaces](https://github.com/Ricky-G/ResourceModules/tree/main/modules/network/network-interface) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/network/network-interface) |  |
|  | [networkManagers](https://github.com/Ricky-G/ResourceModules/tree/main/modules/network/network-manager) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/network/network-manager) |  |
|  | [networkSecurityGroups](https://github.com/Ricky-G/ResourceModules/tree/main/modules/network/network-security-group) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/network/network-security-group) |  |
|  | [networkWatchers](https://github.com/Ricky-G/ResourceModules/tree/main/modules/network/network-watcher) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/network/network-watcher) |  |
|  | [privateDnsZones](https://github.com/Ricky-G/ResourceModules/tree/main/modules/network/private-dns-zone) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/network/private-dns-zone) |  |
|  | [privateEndpoints](https://github.com/Ricky-G/ResourceModules/tree/main/modules/network/private-endpoint) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/network/private-endpoint) |  |
|  | [privateLinkServices](https://github.com/Ricky-G/ResourceModules/tree/main/modules/network/private-link-service) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/network/private-link-service) |  |
|  | [publicIPAddresses](https://github.com/Ricky-G/ResourceModules/tree/main/modules/network/public-ip-address) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/network/public-ip-address) |  |
|  | [publicIPPrefixes](https://github.com/Ricky-G/ResourceModules/tree/main/modules/network/public-ip-prefix) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/network/public-ip-prefix) |  |
|  | [routeTables](https://github.com/Ricky-G/ResourceModules/tree/main/modules/network/route-table) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/network/route-table) |  |
|  | [serviceEndpointPolicies](https://github.com/Ricky-G/ResourceModules/tree/main/modules/network/service-endpoint-policy) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/network/service-endpoint-policy) |  |
|  | [trafficmanagerprofiles](https://github.com/Ricky-G/ResourceModules/tree/main/modules/network/trafficmanagerprofile) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/network/trafficmanagerprofile) |  |
|  | [virtualHubs](https://github.com/Ricky-G/ResourceModules/tree/main/modules/network/virtual-hub) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/network/virtual-hub) |  |
|  | [virtualNetworks](https://github.com/Ricky-G/ResourceModules/tree/main/modules/network/virtual-network) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/network/virtual-network) |  |
|  | [virtualNetworkGateways](https://github.com/Ricky-G/ResourceModules/tree/main/modules/network/virtual-network-gateway) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/network/virtual-network-gateway) |  |
|  | [virtualWans](https://github.com/Ricky-G/ResourceModules/tree/main/modules/network/virtual-wan) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/network/virtual-wan) |  |
|  | [vpnGateways](https://github.com/Ricky-G/ResourceModules/tree/main/modules/network/vpn-gateway) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/network/vpn-gateway) |  |
|  | [vpnSites](https://github.com/Ricky-G/ResourceModules/tree/main/modules/network/vpn-site) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/network/vpn-site) |  |
| `Microsoft.OperationalInsights` | [workspaces](https://github.com/Ricky-G/ResourceModules/tree/main/modules/operational-insights/workspace) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/operational-insights/workspace) |  |
| `Microsoft.OperationsManagement` | [solutions](https://github.com/Ricky-G/ResourceModules/tree/main/modules/operations-management/solution) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/operations-management/solution) |  |
| `Microsoft.PolicyInsights` | [remediations](https://github.com/Ricky-G/ResourceModules/tree/main/modules/policy-insights/remediation) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/policy-insights/remediation) |  |
| `Microsoft.PowerBIDedicated` | [capacities](https://github.com/Ricky-G/ResourceModules/tree/main/modules/power-bi-dedicated/capacity) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/power-bi-dedicated/capacity) |  |
| `Microsoft.Purview` | [accounts](https://github.com/Ricky-G/ResourceModules/tree/main/modules/purview/account) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/purview/account) |  |
| `Microsoft.RecoveryServices` | [vaults](https://github.com/Ricky-G/ResourceModules/tree/main/modules/recovery-services/vault) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/recovery-services/vault) |  |
| `Microsoft.Relay` | [namespaces](https://github.com/Ricky-G/ResourceModules/tree/main/modules/relay/namespace) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/relay/namespace) |  |
| `Microsoft.ResourceGraph` | [queries](https://github.com/Ricky-G/ResourceModules/tree/main/modules/resource-graph/query) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/resource-graph/query) |  |
| `Microsoft.Resources` | [deploymentScripts](https://github.com/Ricky-G/ResourceModules/tree/main/modules/resources/deployment-script) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/resources/deployment-script) |  |
|  | [resourceGroups](https://github.com/Ricky-G/ResourceModules/tree/main/modules/resources/resource-group) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/resources/resource-group) |  |
|  | [tags](https://github.com/Ricky-G/ResourceModules/tree/main/modules/resources/tags) | [<h1 style="color: steelblue;">⚠️ Retired ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/resources/tags) |  |
| `Microsoft.Search` | [searchServices](https://github.com/Ricky-G/ResourceModules/tree/main/modules/search/search-service) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/search/search-service) |  |
| `Microsoft.Security` | [azuresecuritycenter](https://github.com/Ricky-G/ResourceModules/tree/main/modules/security/azure-security-center) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/security/azure-security-center) |  |
| `Microsoft.ServiceBus` | [namespaces](https://github.com/Ricky-G/ResourceModules/tree/main/modules/service-bus/namespace) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/service-bus/namespace) |  |
| `Microsoft.ServiceFabric` | [clusters](https://github.com/Ricky-G/ResourceModules/tree/main/modules/service-fabric/cluster) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/service-fabric/cluster) |  |
| `Microsoft.SignalRService` | [signalR](https://github.com/Ricky-G/ResourceModules/tree/main/modules/signal-r-service/signal-r) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/signal-r-service/signal-r) |  |
|  | [webPubSub](https://github.com/Ricky-G/ResourceModules/tree/main/modules/signal-r-service/web-pub-sub) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/signal-r-service/web-pub-sub) |  |
| `Microsoft.Sql` | [managedInstances](https://github.com/Ricky-G/ResourceModules/tree/main/modules/sql/managed-instance) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/sql/managed-instance) |  |
|  | [servers](https://github.com/Ricky-G/ResourceModules/tree/main/modules/sql/server) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/sql/server) |  |
| `Microsoft.Storage` | [storageAccounts](https://github.com/Ricky-G/ResourceModules/tree/main/modules/storage/storage-account) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/storage/storage-account) |  |
| `Microsoft.Synapse` | [privateLinkHubs](https://github.com/Ricky-G/ResourceModules/tree/main/modules/synapse/private-link-hub) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/synapse/private-link-hub) |  |
|  | [workspaces](https://github.com/Ricky-G/ResourceModules/tree/main/modules/synapse/workspace) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/synapse/workspace) |  |
| `Microsoft.VirtualMachineImages` | [imageTemplates](https://github.com/Ricky-G/ResourceModules/tree/main/modules/virtual-machine-images/image-template) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/virtual-machine-images/image-template) |  |
| `Microsoft.Web` | [connections](https://github.com/Ricky-G/ResourceModules/tree/main/modules/web/connection) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/web/connection) |  |
|  | [hostingEnvironments](https://github.com/Ricky-G/ResourceModules/tree/main/modules/web/hosting-environment) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/web/hosting-environment) |  |
|  | [serverfarms](https://github.com/Ricky-G/ResourceModules/tree/main/modules/web/serverfarm) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/web/serverfarm) |  |
|  | [sites](https://github.com/Ricky-G/ResourceModules/tree/main/modules/web/site) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/web/site) |  |
|  | [staticSites](https://github.com/Ricky-G/ResourceModules/tree/main/modules/web/static-site) | [<h1 style="color: steelblue;">⚠️ Moved to AVM ⚠️</h1>](https://github.com/Ricky-G/ResourceModules/tree/main/modules/web/static-site) |  |

## Platform

| Name | Status |
| - | - |
| Update API Specs file | [![.Platform: Update API Specs file](https://github.com/Ricky-G/ResourceModules/workflows/.Platform:%20Update%20API%20Specs%20file/badge.svg)](https://github.com/Ricky-G/ResourceModules/actions/workflows/platform.apiSpecs.yml) |
| Assign Pull Request to Author | [![.Platform: Assign Pull Request to Author](https://github.com/Ricky-G/ResourceModules/workflows/.Platform:%20Assign%20Pull%20Request%20to%20Author/badge.svg)](https://github.com/Ricky-G/ResourceModules/actions/workflows/platform.assignPrToAuthor.yml) |
| Test - ConvertTo-ARMTemplate.ps1 | [![.Platform: Test - ConvertTo-ARMTemplate.ps1](https://github.com/Ricky-G/ResourceModules/workflows/.Platform:%20Test%20-%20ConvertTo-ARMTemplate.ps1/badge.svg)](https://github.com/Ricky-G/ResourceModules/actions/workflows/platform.convertToArmTemplate.tests.yml) |
| Clean up deployment history | [![.Platform: Clean up deployment history](https://github.com/Ricky-G/ResourceModules/workflows/.Platform:%20Clean%20up%20deployment%20history/badge.svg)](https://github.com/Ricky-G/ResourceModules/actions/workflows/platform.deployment.history.cleanup.yml) |
| Library PSRule pre-flight validation | [![.Platform: Library PSRule pre-flight validation](https://github.com/Ricky-G/ResourceModules/workflows/.Platform:%20Library%20PSRule%20pre-flight%20validation/badge.svg)](https://github.com/Ricky-G/ResourceModules/actions/workflows/platform.librarycheck.psrule.yml) |
| Broken Links Check | [![.Platform: Broken Links Check](https://github.com/Ricky-G/ResourceModules/workflows/.Platform:%20Broken%20Links%20Check/badge.svg)](https://github.com/Ricky-G/ResourceModules/actions/workflows/platform.linkcheck.yml) |
| Linter (audit) | [![.Platform: Linter (audit)](https://github.com/Ricky-G/ResourceModules/workflows/.Platform:%20Linter%20(audit)/badge.svg)](https://github.com/Ricky-G/ResourceModules/actions/workflows/platform.linter.yml) |
| Manage issues for failing pipelines | [![.Platform: Manage issues for failing pipelines](https://github.com/Ricky-G/ResourceModules/workflows/.Platform:%20Manage%20issues%20for%20failing%20pipelines/badge.svg)](https://github.com/Ricky-G/ResourceModules/actions/workflows/platform.ManageIssueForFailingPipelines.yml) |
| Update ReadMe Module Tables | [![.Platform: Update ReadMe Module Tables](https://github.com/Ricky-G/ResourceModules/workflows/.Platform:%20Update%20ReadMe%20Module%20Tables/badge.svg)](https://github.com/Ricky-G/ResourceModules/actions/workflows/platform.updateReadMe.yml) |
| Update Static Test Documentation | [![.Platform: Update Static Test Documentation](https://github.com/Ricky-G/ResourceModules/workflows/.Platform:%20Update%20Static%20Test%20Documentation/badge.svg)](https://github.com/Ricky-G/ResourceModules/actions/workflows/platform.updateStaticTestDocs.yml) |
| Sync Docs/Wiki | [![.Platform: Sync Docs/Wiki](https://github.com/Ricky-G/ResourceModules/workflows/.Platform:%20Sync%20Docs/Wiki/badge.svg)](https://github.com/Ricky-G/ResourceModules/actions/workflows/platform.wiki-sync.yml) |

## Disclaimer

Please note that the `main` branch of this repository always contains the latest available version of the code. Some of the updates may introduce breaking changes as well.

- **Default path**: To avoid disruptions, use distinct versions available through [releases](https://github.com/Azure/ResourceModules/releases).
- **Early adopter path**: If the risk of breaking changes is understood and accepted, you can use the code in the `main` branch directly. However, the CARML team recommends against automatically pulling code from `main`. It is always recommended to review changes before you pull them into your own repository.

## Contributing

This project welcomes contributions and suggestions. Most contributions require you to agree to a Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us the rights to use your contribution. For details, visit <https://cla.opensource.microsoft.com>.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

For specific guidelines on how to contribute to this repository please refer to the [Contribution guide](https://github.com/Azure/ResourceModules/wiki/Contribution%20guide) Wiki section.

## Trademarks

This project may contain trademarks or logos for projects, products, or services. Authorized use of Microsoft trademarks or logos is subject to and must follow
[Microsoft's Trademark & Brand Guidelines](https://www.microsoft.com/en-us/legal/intellectualproperty/trademarks/usage/general).
Use of Microsoft trademarks or logos in modified versions of this project must not cause confusion or imply Microsoft sponsorship.
Any use of third-party trademarks or logos are subject to those third-party's policies.

## Learn More

- [PowerShell Documentation][PowerShellDocs]
- [Microsoft Azure Documentation][MicrosoftAzureDocs]
- [GitHubDocs][GitHubDocs]
- [Azure Resource Manager][AzureResourceManager]
- [Bicep][Bicep]

## Telemetry

Modules provided in this library have telemetry enabled by default. To learn more about this feature, please refer to the [Telemetry article](https://github.com/Azure/ResourceModules/wiki/The%20library%20-%20Module%20design#telemetry) in the wiki.

<!-- References -->

<!-- Local -->
[GitHubDocs]: <https://docs.github.com/>
[AzureIcon]: docs/media/MicrosoftAzure-32px.png

<!-- External -->
[Bicep]: <https://github.com/Azure/bicep>
[AzureResourceManager]: <https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/overview>

<!-- Docs -->
[MicrosoftAzureDocs]: <https://learn.microsoft.com/en-us/azure/>
[PowerShellDocs]: <https://learn.microsoft.com/en-us/powershell/>
