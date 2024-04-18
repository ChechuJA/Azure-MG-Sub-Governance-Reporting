# Azure Governance Visualizer - Management Group Hierarchy

18-Apr-2024 23:31:17 (Romance Standard Time)

## HierarchyMap (Mermaid)

::: mermaid
    graph TD;
6df7235b-9451-436f-a51c-319ec465ccfe("Tenant Root Group<br/>6df7235b-9451-436f-a51c-319ec465ccfe") --> root("root")


 classDef mgr fill:#D9F0FF,stroke:#56595E,color:#000000,stroke-width:1px;
 classDef subs fill:#EEEEEE,stroke:#56595E,color:#000000,stroke-width:1px; classDef mgrprnts fill:#FFFFFF,stroke:#56595E,color:#000000,stroke-width:1px;
 class root mgr;
 class  subs;class '6df7235b-9451-436f-a51c-319ec465ccfe', mgrprnts;
:::
## Summary

Total Management Groups: 2 (depth 1)\
Total Subscriptions: 0\
Total Custom Policy definitions: 9\
Total Custom PolicySet definitions: 0\
Total Policy assignments: 0\
Total Policy assignments ManagementGroups 0\
Total Policy assignments Subscriptions 0\
Total Policy assignments ResourceGroups: 0\
Total Custom Role definitions: 0\
Total Role assignments: 3\
Total Role assignments (Tenant): 1\
Total Role assignments (ManagementGroups): 2\
Total Role assignments (Subscriptions): 0\
Total Role assignments (ResourceGroups and Resources): 0\
Total Blueprint definitions: 0\
Total Blueprint assignments: 0\
Total Resources: 0\
Total Resource Types: 0

## Hierarchy Table

| **MgLevel** | **MgName** | **MgId** | **MgParentName** | **MgParentId** | **SubName** | **SubId** |
|-------------|-------------|-------------|-------------|-------------|-------------|-------------|
| 1 | root | root | Tenant Root Group | 6df7235b-9451-436f-a51c-319ec465ccfe | none | none |

