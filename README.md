# alfred-warp
An Alfred workflow to open currently selected Finder window in Warp

## Installation
Clone the repo or download the `Warp.alfredworkflow` directly and open with Alfred to import the workflow.

## Usage
Open alfred prompt, input `fw` (Finder to Warp) and press Enter.

## Behavior
1. The workflow first try get the path using `insertion location` if it is valid. This is super convenient if one would like to open Desktop in Warp by just focusing on Desktop and using `fw`.
2. If the first step failed, the workflow will try to use the path of the folder of the front Finder window if it exists.
3. Otherwise, the workflow will use the Home directory (`~`).
