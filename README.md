# Sample images

App samples images from input project and creates new project with sampled images.

UI
- card 1: input project
- card 2: table of datasets (with select button) - or checkbox - select all 
- card 3: sampling settings
- card 4: destination project (new or existing -> start button -> progress bar -> project thumbnail)

Sampling settings
- Select: keep annotations, ignore annotations
- Sempling strategy select: number of images per dataset, percent of images per dataset, 
- dataset structure select: keep same datasets names, move results to dataset (define name)

Requirements
- operation can be applied multiple times for different datasets with different settings
- stop app manually
- do not forget to copy images metadata
- random or sequential sample
