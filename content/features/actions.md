# Actions API

The [Actions]({{< javadocurl >}}/org/controlsfx/control/action/Action.html) API is used by both the dialogs API and the ButtonBar API. It essentially abstracts away the notion of how a control is represented, instead focusing on the properties of the control (e.g. text, graphic, etc). This makes it really easy to reuse the same Action in multiple places in your UI. We’ve also developed convenience API to convert Actions into the common UI controls (see the ActionUtils class for these methods). In recent releases, we’ve built on to the Actions API to include functionality such as:

*   An [ActionProxy annotation]({{< javadocurl >}}/org/controlsfx/control/action/ActionProxy.html) (to create actions directly by annotating methods) which can be discovered at runtime using the [ActionMap]({{< javadocurl >}}/org/controlsfx/control/action/ActionMap.html) class.
*   [ActionTextBehavior]({{< javadocurl >}}/org/controlsfx/control/action/ActionUtils.ActionTextBehavior.html) to more easily specify what text is shown in UI controls when built from an action.
