# Composite Actions in Github

A reusabe action : 

# Requires :

1. A `action.yml` file in root of dedicated repo which must be publicly visible.
2. Create a release for that repo with a tag.
3. Use that reponame/releasetag anywhere to invoke reusable composite action.
4. yml must use `uses: "composite"` property.
5. yml must specify name, description, runs whereas input and output are optional, No on event trigger should be used.
