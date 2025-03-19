# BPMN-Extensions for Policies and Patterns

This project contains the definitions for _Policy4BPMN_ and _Pattern4BPMN_, which are extensions of BPMN to support the modeling of pattern-based workflows as well as the specification of policies, e.g., for service deployments.

For _Policy4BPMN_ the following new elements were introduced:
* _OnDemandPolicy_: New policy type to define that a service should be deployed on demand
* _LocationPolicy_: New policy type to define in what region a service should be deployed
* _DedicatedHostingPolicy_: New policy type to define whether a service shall be deployed with a dedicated instance or not
* _CloudTypePolicy_: New policy type to define what infrastructure shall be used to deploy a service, e.g. a public or private cloud

The XML Schema definition of the _Policy4BPMN_ extension can be found [here](./Policy4BPMN-Extension.xsd).


For _Pattern4BPMN_ the following new elements were introduced:
* _PatternSphere_: Extension of the BPMN subprocess that is used for attaching patterns to a set of tasks contained within the subprocess
* _BiasedInitialStatePattern_: New pattern to specify that warm-starting using biased initial state should be applied
* _ChainedOptimizationPattern_: New pattern to specify that warm-starting using chained optimization should be applied
* _CircuitCuttingPattern_: New pattern to specify that circuit cutting should be applied
* _ErrorCorrectionPattern_: New pattern to specify that error correction should be applied
* _GateErrorMitigationPattern_: New pattern to specify that gate error mitigation should be applied
* _OrchestratedExecutionPattern_: New pattern to specify that the corresponding programs should be orchestrated as a workflow
* _PreDeployedExecutionPattern_: New pattern to specify that the corresponding programs should be pre-deployed, e.g., in a hybrid runtime
* _PreTrainedFeatureExtractorPattern_: New pattern to specify that warm-starting using a pre-trained feature extractor should be applied
* _PrioritizedExecutionPattern_: New pattern to specify that quantum circuits should be executed using prioritized access
* _QuantumHardwareSelectionPattern_: New pattern to specify that quantum hardware selection should be applied
* _ReadoutErrorMitigationPattern_: New pattern to specify that readout error mitigation should be applied
* _VariationalParameterTransferPattern_: New pattern to specify that warm-starting using a variational parameter transfer should be applied

The XML Schema definition of the _Pattern4BPMN_ extension can be found [here](./Pattern4BPMN-Extension.xsd).
