# Module purpose

The aim of this module is to provide a checklist that simplifies the integration with **simplesamlphp_auth** and **os2web_simplesaml** modules.

# How does it work

Administrator is supposed to go to the location **/admin/config/people/os2web-simplesaml-checklist** and mark the checkboxes next to the steps that are already done.

Each time checklist is opened, it will attempt to check if any tasks have already been completed. For example, if you already have HTTPS enabled then that item will be checked. You still need to click **"Save"** to save the progress.

Please note, that not all of the checkboxes are checked automatically, meaning that if a task has been done by you and tested, it's your responsibility to mark the checkbox as done. The checkboxes that support autocheck are marked with <i>(auto)</i> suffix 

## Important warning
Clicking the checkboxes does not make your site SimpleSAML ready, instead it helps to set it up by providing step by step guidelines. Follow each step carefully and only mark it done when you tested it.
