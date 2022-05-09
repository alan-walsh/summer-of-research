# summer-of-research
Example Binder repository that can be used with Jetstream2.

This repository is based on the example at https://the-turing-way.netlify.app/communication/binder/zero-to-binder.html. Additional information about Binder is available at https://mybinder.readthedocs.io/en/latest/index.html.

You can deploy this respository in https://mybinder.org/ using the launch button below:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/alan-walsh/summer-of-research/HEAD)

To deploy this repository to a Jetstream2 VM instance:
1. Click the "Create" button to create a new instance
2. Choose an image for the instance (e.g., Ubuntu 20.04)
3. (optionally) Change the name of your instance
5. Click the "Yes" radio button to launch a workflow in the instance
6. Enter the URL for your binderized code repository (e.g., https://github.com/myusername/my-binder-repo)
7. (optionally) Click the radio button to show advanced options and set up any additional settings (e.g., add an SSH keypair so that you can SSH into your instance)
9. Click "Create" to launch the instance

It will take about 5-10 minutes to create the new instance, so please be patient.

When it is done, you can launch your workflow by clicking on instances, then your instance name, and then the "Wokflow" button under the list of interactions.

Note that you can also connect to a web SSH session using the "Web Shell" button, or copy the native SSH connection string to connect using another SSH client.
