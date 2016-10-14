# Baller Wowza Modules

Source and distribution repository for Wowza applications

#Configuration version control

When deploying from this git never make configuration changes to Wowza servers via
the Wowza Streaming Engine Manager. Instead, edit the configuration files manually and,
push to git.

# Deployment

* Merge the contents of the "deploy" directory with the default installation directory of Wowza Streaming Engine (typically /usr/local/WowzaStreamingEngine). 

* Restart the Wowza Streaming Engine Service.
