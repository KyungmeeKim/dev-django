# dev-django
<<조건>>  
web: nginx / was: Django / db: 온프레미스(mysql 가정)  
  
<<주요 기능>>  
1.	K8S hpa를 활용한 AWS 클러스터 오토스케일링을 적용  
2.	Nginx access log 보존하기 위해서 외부볼륨으로 NFS 사용  
3.	RBAC 특정 사용자 및 그룹에게 Role을 할당하여namespace에 대한 권한 관리  
4.	endpoint  
