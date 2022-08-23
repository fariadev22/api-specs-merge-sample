# api-specs-merge-sample
A repository that holds sample API specification documents used in my blog for illustrating the merging process using APIMatic.

## Contents
The `MusicPlay Merge Example` directory contains all files needed to perform the merge. It is actually the parent directory that holds dedicated sub-directories for the two hypothetical API descriptions `Library API` and `User API`. In addition to that, it holds a Metadata configuration file `APIMATIC-META.json` to enable merging of the two API descriptions.

- The sub-directory `Library API` contains the OpenAPI description file `MusicPlay Library API.yaml`.

- The sub-directory `User API` contains the OpenAPI description file `MusicPlay User API.yaml` as well as a Metadata configuration file `APIMATIC-META.json` which will help in filtering out internal endpoints from the OpenAPI description when it is imported.