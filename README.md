# Description

unRAID Docker Templates for Docker images in the "am385" repository for the unRAID Community Applications plugin.

# Usage

## Community Applications (Recomended)

This repository is crawled by the unRAID Community Applications and these templates can be added through their system via the Apps tab in unRAID.

## Manual

You can manually add templates under the "User templates" in unRAID by adding the templates you want to the correct directory.

1. Rename any of the templates you want to use with a "my-" prefix. i.e. `Lineup.xml` would become `my-Lineup.xml`
2. Navigate to /boot/config/plugins/dockerMan/templates-user in unraid
3. Copy the desired templates into this directory
4. In the unRAID UI, navigate back to the "Docker" tab and then click on the "Add Container" button
5. Click on the "Template" dropdown menu and select the desired template under the "User templates" section
6. Fill in required fields e.g. volume data, environment variables etc
7. Click on the "Apply" button at the bottom of the window to begin pulling down the Docker image
8. Once the image is downloaded you should see it appear in the "Docker" tab
