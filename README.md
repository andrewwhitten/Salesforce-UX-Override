# Salesforce-UX-Override
A LWC component that demonstates how to override CSS on a Lightning page that it is added to.

This approach is for edge case scenarios that have no straightforward Salesforce configuration approach. IT IS NOT RECOMMENDED.

The first thing to understand is that <B>this is a last resort</B>. Please fully investigate your challenge and requirements with Salesforce supported approaches before even considering this unsupported approach. Contact Salesforce Support for advice first.

Got this far? OK. So all we are doing here is adding a CSS file to the Salesforce page that changes the styling. Specifically styling can be used to hide standard screen components, such as the 'Save & New' button when creating records.
