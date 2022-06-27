## Jak stworzyć repozytorium w [[AWS CodeCommit]]?
1. Uruchom [[AWS CloudShell]]
2. Wykonaj komendę "aws codecommit create-repository". Przykład poniżej
   ```aws codecommit create-repository --repository-name MyDemoRepo --repository-description "My demonstration repository"```
   Przykładowy wynik:
   ```
   {
	    "repositoryMetadata": {
	        "accountId": "100000000000",
	        "repositoryId": "8cc000c8-4102-44d7-8864-25cdfd57f297",
	        "repositoryName": "MyDemoRepo",
	        "repositoryDescription": "My demonstration repository",
	        "lastModifiedDate": "2022-06-02T15:20:47.401000+00:00",
	        "creationDate": "2022-06-02T15:20:47.401000+00:00",
	        "cloneUrlHttp": "https://git-codecommit.ap-northeast-1.amazonaws.com/v1/repos/MyDemoRepo",
	        "cloneUrlSsh": "ssh://git-codecommit.ap-northeast-1.amazonaws.com/v1/repos/MyDemoRepo",
	        "Arn": "arn:aws:codecommit:ap-northeast-1:100000000660:MyDemoRepo"
	    }
	}
	```
	Powiązane: [[Amazon Web Services (AWS)]]