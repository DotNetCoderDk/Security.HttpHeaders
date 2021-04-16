Security.HttpHeaders
====================

Contains examples of how to security harden you IIS webserver. Most of these examples are used on Sitecore CMS solutions, but might work for on other solutions as well. 

Remember this is provided as is. I am not liable for how this works on you solution

Web.Project.Environment.TraceDisabled.config
--------------------------------------------
Disables the trace verb from your IIS server

Web.Project.Environment.Disable-Google-FLoC.config
--------------------------------------------------
Disable the Google’s Federated Learning of Cohorts (FLoC) for visitors of your site.  
See more here: https://plausible.io/blog/google-floc 

Web.Project.Environment.Security.config	
-------------------------------------------------
Removed IIS webserver poster headers for asp.net, MVC and IIS server version

Web.Project.Environment.HSTSHeadersEnabled.config
-------------------------------------------------

