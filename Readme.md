<!-- default file list -->
*Files to look at*:

* [Default.aspx](./CS/Default.aspx) (VB: [Default.aspx](./VB/Default.aspx))
* [Default.aspx.cs](./CS/Default.aspx.cs) (VB: [Default.aspx.vb](./VB/Default.aspx.vb))
<!-- default file list end -->
# How to implement a custom loading panel for the ASPxCallbackPanel control
<!-- run online -->
**[[Run Online]](https://codecentral.devexpress.com/t228855/)**
<!-- run online end -->


<p>The <a href="https://documentation.devexpress.com/#AspNet/clsDevExpressWebASPxCallbackPaneltopic">ASPxCallbackPanel</a>  control provides a built-in loading panel, however you can implement a custom one. For this purpose, the default panel is hidden by setting the <a href="https://documentation.devexpress.com/#AspNet/DevExpressWebSettingsLoadingPanel_Enabledtopic">SettingsLoadingPanel.Enabled</a> property to false. The custom panel is implemented using the <a href="https://documentation.devexpress.com/#AspNet/clsDevExpressWebASPxLoadingPaneltopic">ASPxLoadingPanel</a>  control. The callback panel's <a href="https://documentation.devexpress.com/#AspNet/DevExpressWebScriptsASPxClientCallbackPanel_BeginCallbacktopic">ASPxClientCallbackPanel.BeginCallback</a>  and <a href="https://documentation.devexpress.com/#AspNet/DevExpressWebScriptsASPxClientCallbackPanel_EndCallbacktopic">ASPxClientCallbackPanel.EndCallback</a>  client-side events are used to show and hide the loading panel respectively.</p>
<p>Additionally, this example demonstrates how to add, modify, and hide controls in the ASPxCallbackPanel control in the <a href="https://documentation.devexpress.com/#AspNet/DevExpressWebASPxCallbackPanel_Callbacktopic">ASPxCallbackPanel.Callback</a>  event handler.</p>

<br/>


