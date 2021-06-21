# StreamingDevOps
Streaming Dev Ops


# upload flows
* working
* curl -X POST  http://localhost:8080/nifi-api/process-groups/32bab57d-0179-1000-0e29-4ff7a467f14f/process-groups/upload


curl -X POST "http://localhost:8080/nifi-api/process-groups/root/process-groups/upload" -H "accept: application/json" -H "Content-Type: multipart/form-data" -F "file=@/Users/tspann/Downloads/nifi-toolkit-1.13.2/DemoJamEdgeCode.json ;type=application/json" -F "groupName=timTest6" -F "positionX=6359.893771701389" -F "positionY=1606.252197265625" -F "clientId=2fed26e0-017a-1000-8c17-d214b05604fa"
