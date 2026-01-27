newman run "DVAPI CICD.postman_collection.json" -e "DVAPI Test.postman_environment.json" --export-environment "DVAPI Test.postman_environment.json"

newman run "DVAPI CICD.postman_collection.json" -e "DVAPI Test.postman_environment.json" --export-environment "DVAPI Test.postman_environment.json" --reporters cli,htmlextra --reporter-htmlextra-export newman/report.html

newman run "D:\Working\TestingDocs\API\Course\Collections\DVAPI CICD.postman_collection.json" -e "D:\Working\TestingDocs\API\Course\Collections\DVAPI Test.postman_environment.json" --export-environment "D:\Working\TestingDocs\API\Course\Collections\DVAPI Test.postman_environment.json" --reporters cli,htmlextra --reporter-htmlextra-export newman/report.html