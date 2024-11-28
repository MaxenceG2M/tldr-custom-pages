# StGit

> Use Git with a patch phylosophie

- First of all, init

`stg init`

- Create a patch

`stg new [{{my_patch_name}}] [-m '{{message}}']`

- Update a patch with changes from the working tree

`stg refresh`

- List patchs

`stg series`

- Show a patch

`stg show {{patch_name}}`

- Clean a branch

`stg branch --cleanup {{banch_name}}`
`stg branch --delete {{banch_name}}`
