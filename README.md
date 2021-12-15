# github-actions-sandbox
Github Actions Sandbox

on:
push:
paths:
- 'image-processor-py/**'
- '!image-processor-py/docs/**'




on:
push:
paths-ignore:
- 'docs/**'




on:
push:
paths:
- 'sub-project/**'
- '!sub-project/docs/**'