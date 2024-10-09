# Create my first release

- ```kubectl apply -f rpa.yaml``` to create the rpa
- ```kubectl apply -f ec.yaml``` to add the pocily
- ```kubectl apply -f release-plan.yaml``` to create the release-plan
- ```kubectl apply -f first-release.yaml``` to create the first-release

The key points aref:
1. ensure your application name and namespace are consistent.
2. you release the snapshot, so please ensure the snapshot is correct.
3. some parameters are mandatory but options in docs, so the yamls do not follow
the ui rules.
