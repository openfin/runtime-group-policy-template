# OpenFin Runtime Group Policy Template

## Overview
Group Policy Template (ADM file) for the OpenFin Runtime

### Instructions

1. Download the file
2. Start->Run->gpedit.msc
3. Right click on Administrative Templates, Add/Remove Templates...
4. Load openfin.adm.  For Runtime v26.102+, load openfin-v26.adm.
5. The settings will appear under Administrative Templates->Classic Administrative Templates (ADM)

When upgrading Runtime to v26.102+, please load openfin-v26.adm because some of policy key names have been deprecated, including AuthServerAllowlist and AuthNegotiateDelegateAllowlist.  If the deprecated keys are configured, please copy values to the new key names.  The existing polices will be stored under "openfin/Removed policies" in Group Policy.  Please do not remove deprecate keys if older versions of Runtime are still needed.

## License
MIT

The code in this repository is covered by the included license.

However, if you run this code, it may call on the OpenFin RVM or OpenFin Runtime, which are covered by OpenFin’s Developer, Community, and Enterprise licenses. You can learn more about OpenFin licensing at the links listed below or just email us at support@openfin.co with questions.

https://openfin.co/developer-agreement/ <br/>
https://openfin.co/licensing/

## Support
Please enter an issue in the repo for any questions or problems. 
<br> Alternatively, please contact us at support@openfin.co
