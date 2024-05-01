# Ivy's team created buds

Meant to contain all of the already bundled, company produced buds that will appear into the app, whenever user-created buds already exist or not.

## Process
Data extracted from https://github.com/Qalisa/buds/blob/main/list.csv by https://github.com/Qalisa/ivy-api then smartly injected into database at process startup, then will be ready to be displayed to user.

## Forcing update
Once https://github.com/Qalisa/buds/blob/main/list.csv is updated, please manually reboot any https://github.com/Qalisa/ivy-api instance to apply changes. Might require injection automation without service reboot (https://github.com/Qalisa/buds/issues/1).
