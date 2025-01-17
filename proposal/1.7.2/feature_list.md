## Feature 1.7.2
> FederatedML
* New batch strategy in coordinated Hetero LR: support masked batch data and batch shuffle
* Model inference protection enhancement for Hetero SecureBoost with FED-EINI algorithm
* Hetero SecureBoost supports split feature importance on host side, disables gain feature importance.
* Offline SBT Feature transform component 
> FATE-Flow
* Separate the base connection address of the data storage table from the data table information, and compatible with historical versions;
* Optimize the component output data download interface;

> FATE-Board
* Support FATE-Board v1.7.2.1

> Bug-Fix
* Fixed Bug for HeteroPearson with changing default q_field value for spdz
* Fix Data Transform's schema label name setting problem when `with_label` is False


