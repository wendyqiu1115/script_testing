# Initialization Tag Template for Integrating Braze Web SDK

Welcome to the Braze GTM script wiki! By following the step-by-step instruction, you can integrate Braze Web SDK in your own page within a few steps via Google Tag Manager custom templates.

We assume that you've already created a Google Tag Manager account and a web container. If not, you can create one by following the [simple guidance](https://support.google.com/tagmanager/answer/6103696). 

After you create a container, you can add GTM container snippet to your website by following the instruction in GTM workspace.

## Installation

1. Go to `Templates` tab of Google Tag Manager.

2. Click `Search Gallery` and select Braze Initialization Template from the gallery.
3. Click `Add to workspace`
4. Go to `Tags` tab of Google Tag Manager.
5. Click `New` and select `Braze Web SDK Initialization Template` from `Custom` module to create a new tag.
6. Find your API key and base url, input them into the field. You can find some useful information [here](https://www.braze.com/docs/user_guide/administrative/access_braze/sdk_endpoints/).
7. Customize all the other settings (you can see more options inside the collapsible menu by clicking `Advanced Options`).
8. Select a trigger for this template tag (e.g. `All Pages`).
9. If you want to debug, click `Preview` button on the page.
10. Click `Submit` on the upper right corner of the page.
11. Click `Publish` to publish your tag.

